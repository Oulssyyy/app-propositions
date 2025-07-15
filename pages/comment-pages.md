---
layout: center
---

# 🔮 AIがもたらす価値
<div class="grid grid-cols-2 gap-8">
	<div 
		class="value-card"
		v-motion
		:initial="{ y: 40, opacity: 0 }"
		:enter="{ y: 0, opacity: 1, transition: { delay: 200, duration: 700 } }"
	>
		<carbon:user-avatar class="text-4xl text-blue-500 mb-4" />
		<h3 class="font-bold text-xl mb-3">パーソナライゼーション</h3>
		<p class="text-sm opacity-80">
		顧客一人ひとりの特性やニーズに合わせた最適なサービス提供を実現
		</p>
	</div>
	<div 
		class="value-card"
		v-motion
		:initial="{ y: 40, opacity: 0 }"
		:enter="{ y: 0, opacity: 1, transition: { delay: 400, duration: 700 } }"
	>
		<carbon:analytics class="text-4xl text-green-500 mb-4" />
		<h3 class="font-bold text-xl mb-3">予測分析</h3>
		<p class="text-sm opacity-80">
		過去のデータから将来のトレンドを予測し、戦略的な意思決定をサポート
		</p>
	</div>
	<div 
		class="value-card"
		v-motion
		:initial="{ y: 40, opacity: 0 }"
		:enter="{ y: 0, opacity: 1, transition: { delay: 600, duration: 700 } }"
	>
		<carbon:automatic class="text-4xl text-purple-500 mb-4" />
		<h3 class="font-bold text-xl mb-3">自動化の高度化</h3>
		<p class="text-sm opacity-80">
		従来の単純な自動化を超えた、状況に応じた柔軟な処理の実現
		</p>
	</div>
	<div 
		class="value-card"
		v-motion
		:initial="{ y: 40, opacity: 0 }"
		:enter="{ y: 0, opacity: 1, transition: { delay: 800, duration: 700 } }"
	>
		<carbon:error-filled class="text-4xl text-red-500 mb-4" />
		<h3 class="font-bold text-xl mb-3">エラー検出・修正</h3>
		<p class="text-sm opacity-80">
		人間では見逃しがちなエラーを自動で検出し、修正提案を行う
		</p>
	</div>
</div>

<style>
.value-card {
@apply bg-white p-6 rounded-lg shadow-lg border border-gray-200 text-center;
}
</style>

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