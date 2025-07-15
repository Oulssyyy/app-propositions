# ⚠️ リスクと対策
## 各アプリケーションの潜在的リスク

<div class="flex flex-row items-center w-full min-h-[10rem]">
	<div class="flex-1">
		<div 
		v-motion
		:initial="{ x: -100, opacity: 0 }"
		:enter="{ x: 0, opacity: 1, transition: { delay: 300, duration: 800 } }"
		class="text-xl mt-8"
		>
		🛡️ リスクを事前に把握し、適切な対策を講じる
		</div>
	</div>
	<div class="flex-1 flex justify-end">
		<div v-motion
		:initial="{ x: 100, opacity: 0, scale: 0.8 }"
		:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 200, duration: 900 } }"
		class="mr-2"
		>
			<img src="/assets/risks.jpg" alt="リスク" class="w-80 h-80 drop-shadow-2xl rounded-2xl bg-white object-cover" />
		</div>
	</div>
</div>

---
layout: default
---

# 🚨 リスク分析

<div class="grid grid-cols-3 gap-8 mt-8">
	<div  
		class="risk-section"
		v-motion
		:initial="{ y: 40, opacity: 0 }"
		:enter="{ y: 0, opacity: 1, transition: { delay: 200, duration: 600 } }"
	>
		<div class="risk-header">
			<carbon:mail-all class="text-blue-500 text-3xl mb-3" />
			<h3 class="font-bold text-lg mb-4">メール自動送信</h3>
		</div>
		<div class="risk-content">
			<div class="risk-item">
				<carbon:warning class="text-red-500 text-lg mr-2" />
				<span class="text-sm">誤送信のリスク</span>
			</div>
			<div class="risk-item">
				<carbon:password class="text-red-500 text-lg mr-2" />
				<span class="text-sm">顧客情報管理の課題</span>
			</div>
		</div>
	</div>
	<div  
		class="risk-section"
		v-motion
		:initial="{ y: 40, opacity: 0 }"
		:enter="{ y: 0, opacity: 1, transition: { delay: 400, duration: 600 } }"
	>
		<div class="risk-header">
			<carbon:search class="text-green-500 text-3xl mb-3" />
			<h3 class="font-bold text-lg mb-4">統合型プラットフォーム</h3>
		</div>
		<div class="risk-content">
			<div class="risk-item">
				<carbon:network-overlay class="text-orange-500 text-lg mr-2" />
				<span class="text-sm">情報連携の複雑さ</span>
			</div>
			<div class="risk-item">
				<carbon:time class="text-orange-500 text-lg mr-2" />
				<span class="text-sm">リアルタイム更新の負荷</span>
			</div>
		</div>
	</div>
	<div  
		class="risk-section"
		v-motion
		:initial="{ y: 40, opacity: 0 }"
		:enter="{ y: 0, opacity: 1, transition: { delay: 600, duration: 600 } }"
	>
		<div class="risk-header">
			<carbon:document class="text-purple-500 text-3xl mb-3" />
			<h3 class="font-bold text-lg mb-4">契約書・請求書自動作成</h3>
		</div>
		<div class="risk-content">
			<div class="risk-item">
				<carbon:rule class="text-purple-500 text-lg mr-2" />
				<span class="text-sm">法務要件の正確性</span>
			</div>
			<div class="risk-item">
				<carbon:workflow-automation class="text-purple-500 text-lg mr-2" />
				<span class="text-sm">承認フローの整合性</span>
			</div>
		</div>
	</div>
</div>



<style>
.risk-section {
@apply bg-white p-6 rounded-lg shadow-lg border border-gray-200 h-full;
}

.risk-header {
@apply text-center mb-4;
}

.risk-content {
@apply space-y-3;
}

.risk-item {
@apply flex items-center p-2 bg-red-50 rounded;
}

.summary-card {
@apply bg-white p-6 rounded-lg shadow-lg border border-gray-200;
}
</style>

---
layout: center
class: text-center
---

# 🎯 まとめ

<div class="grid grid-cols-3 gap-8 mt-12">
	<div 
		class="summary-card" 
		v-motion 
		:initial="{ y: 40, opacity: 0 }" 
		:enter="{ y: 0, opacity: 1, transition: { delay: 0, duration: 600 } }"
	>
		<carbon:mail-all class="text-4xl text-blue-500 mb-4" />
		<h3 class="font-bold text-lg mb-2">メール自動送信</h3>
		<p class="text-sm opacity-80">業務効率化とミス削減</p>
	</div>
	<div 
		class="summary-card" 
		v-motion 
		:initial="{ y: 40, opacity: 0 }" 
		:enter="{ y: 0, opacity: 1, transition: { delay: 200, duration: 600 } }"
	>
		<carbon:search class="text-4xl text-green-500 mb-4" />
		<h3 class="font-bold text-lg mb-2">統合型物件検索</h3>
		<p class="text-sm opacity-80">一元管理とリアルタイム監視</p>
	</div>
	<div 
		class="summary-card" 
		v-motion 
		:initial="{ y: 40, opacity: 0 }" 
		:enter="{ y: 0, opacity: 1, transition: { delay: 400, duration: 600 } }"
	>
		<carbon:document class="text-4xl text-purple-500 mb-4" />
		<h3 class="font-bold text-lg mb-2">契約書自動作成</h3>
		<p class="text-sm opacity-80">文書作成の自動化</p>
	</div>
</div>

<div 
v-motion
:initial="{ y: 50, opacity: 0 }"
:enter="{ y: 0, opacity: 1, transition: { delay: 600, duration: 800 } }"
class="mt-8"
>
	<h3 class="text-xl font-bold mb-4">次のステップ</h3>
	<div class="grid grid-cols-2 gap-6">
		<div>
			<div class="bg-blue-50 p-4 rounded-lg">
				<p class="text-sm font-semibold mb-2">各チームからのフィードバックを募集</p>
				<p class="text-xs mt-2 opacity-70">ご意見をもとに、より良いシステム設計を目指します。</p>
			</div>
		</div>
		<div>
			<div class="bg-gray-100 p-4 rounded-lg mb-4 mt-8 md:mt-0">
				<p class="text-sm">詳細な要件定義と技術的実装の検討を進め、段階的な導入を提案します。</p>
			</div>
		</div>
	</div>
</div>

---
background: ../assets/estate.jpg
transition: slide-down
---

<div class="fixed inset-0 flex flex-col items-center justify-center" style="background-image: url('../assets/estate.jpg'); background-size: cover; background-position: center; margin: 0; padding: 0;">
	<div class="absolute inset-0 bg-white bg-opacity-70"></div>
	<h1 
		class="text-4xl font-bold mb-4 text-black"
		v-motion
		:initial="{ y: -40, opacity: 0 }"
		:enter="{ y: 0, opacity	: 1, transition: { delay: 200, duration: 700 } }"
	>
		<span style="background: linear-gradient(45deg, #0d1333 0%, #0d47a1 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; display: inline-block;">
		ステラーフォースの未来を共に創造しましょう
		</span>
	</h1>
	<div 
		v-motion
		:initial="{ y: 50, opacity: 0 }"
		:enter="{ y: 0, opacity: 1, transition: { delay: 700, duration: 800 } }"
	>
		<h2 class="text-2xl" style="color: #0d47a1;">ご質問やご意見をお聞かせください</h2>
	</div>
	<div 
		class="mt-8 flex justify-center"
		v-motion
		:initial="{ scale: 0.8, opacity: 0 }"
		:enter="{ scale: 1, opacity: 1, transition: { delay: 1200, duration: 600, type: 'spring' } }"
	>
		<div class="bg-white bg-opacity-90 rounded-xl p-2 shadow-lg">
		<img 
			src="/assets/stellarforce.png" 
			alt="Stellar Force" 
			class="h-16 w-auto drop-shadow-xl"
			v-motion
			:initial="{ rotateY: 90 }"
			:enter="{ rotateY: 0, transition: { delay: 1500, duration: 700 } }"
		/>
		</div>
	</div>
</div>
