---
layout: default
---

# 🤖 AIの活用
## 各アプリケーションでの人工知能の統合

<div class="flex flex-row items-center w-full min-h-[10rem]">
	<div class="flex-1">
		<div 
		v-motion
		:initial="{ x: -100, opacity: 0 }"
		:enter="{ x: 0, opacity: 1, transition: { delay: 300, duration: 800 } }"
		class="text-xl mt-8"
		>
		🧠 AI技術による更なる価値創造と効率化
		</div>
	</div>
	<div class="flex-1 flex justify-end">
		<div v-motion
		:initial="{ x: 100, opacity: 0, scale: 0.8 }"
		:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 200, duration: 900 } }"
		class="mr-2"
		>
		<img src="/assets/ai.jpg" alt="AI活用" class="w-80 h-80 drop-shadow-2xl rounded-2xl bg-white object-cover" />
		</div>
	</div>
</div>

---
layout: default
---

# 🤖 AI機能の詳細
<div class="grid grid-cols-3 gap-8 mt-8">
	<div 
		class="ai-section"
		v-motion
		:initial="{ y: 40, opacity: 0 }"
		:enter="{ y: 0, opacity: 1, transition: { delay: 200, duration: 700 } }"
	>
		<div class="ai-header">
			<carbon:mail-all class="text-blue-500 text-3xl mb-3" />
			<h3 class="font-bold text-lg mb-4">メール自動送信</h3>
		</div>
		<div class="ai-features">
			<div class="ai-item">
				<carbon:user-identification class="text-blue-400 text-lg mr-2" />
				<span class="text-sm">カスタムメール送信</span>
			</div>
			<div class="ai-item">
				<carbon:user-profile class="text-blue-400 text-lg mr-2" />
				<span class="text-sm">顧客プロフィールによるパーソナルメール</span>
			</div>
			<div class="ai-item">
				<carbon:reply class="text-blue-400 text-lg mr-2" />
				<span class="text-sm">自動返信</span>
			</div>
		</div>
	</div>
	<div 
		class="ai-section"
		v-motion
		:initial="{ y: 40, opacity: 0 }"
		:enter="{ y: 0, opacity: 1, transition: { delay: 400, duration: 700 } }"
	>
		<div class="ai-header">
			<carbon:search class="text-green-500 text-3xl mb-3" />
			<h3 class="font-bold text-lg mb-4">統合型物件検索</h3>
		</div>
		<div class="ai-features">
			<div class="ai-item">
				<carbon:classification class="text-green-400 text-lg mr-2" />
				<span class="text-sm">AIによる物件の自動カテゴリー分け</span>
			</div>
		</div>
	</div>
	<div 
		class="ai-section"
		v-motion
		:initial="{ y: 40, opacity: 0 }"
		:enter="{ y: 0, opacity: 1, transition: { delay: 600, duration: 700 } }"
	>
		<div class="ai-header">
			<carbon:document class="text-purple-500 text-3xl mb-3" />
			<h3 class="font-bold text-lg mb-4">契約書・請求書自動作成</h3>
		</div>
		<div class="ai-features">
			<div class="ai-item">
				<carbon:error-filled class="text-purple-400 text-lg mr-2" />
				<span class="text-sm">AI請求エラー検出</span>
			</div>
			<div class="ai-item">
				<carbon:automatic class="text-purple-400 text-lg mr-2" />
				<span class="text-sm">自動契約修正</span>
			</div>
		</div>
	</div>	
</div>



<style>
.ai-section {
@apply bg-white p-6 rounded-lg shadow-lg border border-gray-200 h-full;
}

.ai-header {
@apply text-center mb-4;
}

.ai-features {
@apply space-y-3;
}

.ai-item {
@apply flex items-center p-2 bg-gray-50 rounded;
}

.value-card {
@apply bg-white p-6 rounded-lg shadow-lg border border-gray-200 text-center;
}
</style>

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
