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
			ご清聴ありがとうございました
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
			src="../assets/stellarforce.png" 
			alt="Stellar Force" 
			class="h-16 w-auto drop-shadow-xl"
			v-motion
			:initial="{ rotateY: 90 }"
			:enter="{ rotateY: 0, transition: { delay: 1500, duration: 700 } }"
		/>
		</div>
	</div>
</div>
