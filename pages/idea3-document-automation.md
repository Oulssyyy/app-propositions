# アイデア3
## ドキュメント自動生成アプリケーション

<div class="flex flex-row items-center w-full min-h-[10rem]">
	<div class="flex-1">
		<div 
			v-motion
			:initial="{ x: -100, opacity: 0 }"
			:enter="{ x: 0, opacity: 1, transition: { delay: 300, duration: 800 } }"
			class="text-xl mt-8"
		>📄 書類作成の自動化で業務効率UP
		</div>
	</div>
	<div class="flex-1 flex justify-end">
		<div v-motion
			:initial="{ x: 100, opacity: 0, scale: 0.8 }"
			:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 200, duration: 900 } }"
			class="mr-2"
		>
			<img src="/assets/contract.jpg" alt="ドキュメント自動生成" class="w-80 h-80 drop-shadow-2xl rounded-2xl bg-white object-cover" />
		</div>
	</div>
</div>

---
transition: slide-up
---

# 📋 現在の問題点

<div class="grid grid-cols-1 md:grid-cols-2 gap-4">
	<div  
		v-motion
		:initial="{ y: 40, opacity: 0, scale: 0.9 }"
		:enter="{ y: 0, opacity: 1, scale: 1, transition: { delay: 100, duration: 600 } }"
		class="bg-red-100 p-6 rounded-lg"
	>
		<div class="flex items-center mb-4">
			<carbon:edit class="text-red-500 mr-3 text-2xl" />
			<h3 class="text-xl font-bold text-red-700">手動テンプレート入力</h3>
		</div>
		<p class="text-gray-700">
			現在、契約書や請求書は既存のテンプレートを使用して手動で入力・作成されており、時間と労力を要します。
		</p>
	</div>
	<div 
		v-motion
		:initial="{ x: 60, opacity: 0, scale: 0.9 }"
		:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 250, duration: 600 } }"
		class="bg-orange-100 p-6 rounded-lg"
	>
		<div class="flex items-center mb-4">
			<carbon:information class="text-orange-500 mr-3 text-2xl" />
			<h3 class="text-xl font-bold text-orange-700">情報収集の必要性</h3>
		</div>
		<p class="text-gray-700">
			この機能の詳細な要件については、社内の関連チーム（例：法務、財務、営業）と連携し、生成すべき文書の種類や具体的なワークフローを確認する必要があります。
		</p>
	</div>
	<div 
		v-motion
		:initial="{ y: 40, opacity: 0, scale: 0.9 }"
		:enter="{ y: 0, opacity: 1, scale: 1, transition: { delay: 400, duration: 600 } }"
		class="bg-yellow-100 p-6 rounded-lg"
	>
		<div class="flex items-center mb-4">
			<carbon:warning class="text-yellow-500 mr-3 text-2xl" />
			<h3 class="text-xl font-bold text-yellow-700">ヒューマンエラーのリスク</h3>
		</div>
		<p class="text-gray-700">
			手動でのデータ入力は、誤字脱字や数値の誤りなど、人的ミスを引き起こす可能性があります。
		</p>
	</div>
	<div 
		v-motion
		:initial="{ x: 60, opacity: 0, scale: 0.9 }"
		:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 550, duration: 600 } }"
		class="bg-purple-100 p-6 rounded-lg"
	>
		<div class="flex items-center mb-4">
			<carbon:growth class="text-purple-500 mr-3 text-2xl" />
			<h3 class="text-xl font-bold text-purple-700">スケーラビリティの限界</h3>
		</div>
		<p class="text-gray-700">
			顧客や契約が増えるにつれて、手動での処理では対応が困難になり、作成に時間がかかるようになります。
		</p>
	</div>
</div>

---
layout: full
layoutClass: gap-4
---

# 🎯 主要機能

<div class="flex flex-row gap-4 w-full">
	<div class="flex-1 space-y-4">
		<div
			v-motion
			:initial="{ x: -60, opacity: 0, scale: 0.8 }"
			:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 200, duration: 600 } }"
			class="feature-card"
		>
			<carbon:data-structured class="text-blue-500 text-2xl mb-2" />
			<h3 class="font-bold text-lg mb-2">データ駆動型文書生成</h3>
			<p class="text-sm opacity-80">企業データから直接情報を取得し、契約書や請求書などの文書を自動生成</p>
		</div>
		<div
			v-motion
			:initial="{ y: 60, opacity: 0, scale: 0.8 }"
			:enter="{ y: 0, opacity: 1, scale: 1, transition: { delay: 400, duration: 600 } }"
			class="feature-card"
		>
			<carbon:version class="text-purple-500 text-2xl mb-2" />
			<h3 class="font-bold text-lg mb-2">文書バージョン管理</h3>
			<p class="text-sm opacity-80">作成された文書の変更履歴を記録し、いつでも以前のバージョンにアクセス可能</p>
		</div>
	</div>
	<div class="flex-1 space-y-4">
		<div
			v-motion
			:initial="{ x: 60, opacity: 0, scale: 0.8 }"
			:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 600, duration: 600 } }"
			class="feature-card"
		>
			<carbon:template class="text-orange-500 text-2xl mb-2" />
			<h3 class="font-bold text-lg mb-2">テンプレートカスタマイズ</h3>
			<p class="text-sm opacity-80">さまざまな種類の文書に対応できるよう、テンプレートを自由に編集・管理</p>
		</div>
		<div
			v-motion
			:initial="{ y: -60, opacity: 0, scale: 0.8 }"
			:enter="{ y: 0, opacity: 1, scale: 1, transition: { delay: 800, duration: 600 } }"
			class="feature-card"
		>
			<carbon:notification class="text-teal-500 text-2xl mb-2" />
			<h3 class="font-bold text-lg mb-2">文書発行アラート</h3>
			<p class="text-sm opacity-80">文書が作成または送信された際に、関係者に自動的に通知を送信</p>
		</div>
	</div>
</div>

<style>
.feature-card {
@apply bg-white p-4 rounded-lg shadow-md border border-gray-200;
}
</style>

---
layout: center
---

# 🔄 アプリケーションの仕組み

<div class="flex justify-center items-center space-x-8 mt-12">
	<div v-motion
	:initial="{ scale: 0, rotate: 180 }"
	:enter="{ scale: 1, rotate: 0, transition: { delay: 300, duration: 800 } }"
	class="flow-item"
	>
		<div class="bg-white rounded-lg shadow-md border border-gray-200 flex flex-col items-center">
				<img src="../assets/stellarforce.png" alt="Database" class="w-20 h-20 object-contain mb-2" />
		</div>
		<div class="text-center">企業データ</div>
	</div>
	<div v-motion
		:initial="{ x: -50, opacity: 0 }"
		:enter="{ x: 0, opacity: 1, transition: { delay: 800, duration: 600 } }"
		class="arrow flex flex-col items-center"
	>
		<carbon:arrow-right class="text-3xl text-black" />
		<span class="text-xs text-black mt-1">データ取得</span>
	</div>
	<div v-motion
		:initial="{ scale: 0, rotate: -180 }"
		:enter="{ scale: 1, rotate: 0, transition: { delay: 1000, duration: 800 } }"
		class="flow-item">
		<carbon:application class="text-4xl text-blue-500 mb-2" />
		<div class="text-center">アプリケーション</div>
	</div>
	<div v-motion
		:initial="{ x: -50, opacity: 0 }"
		:enter="{ x: 0, opacity: 1, transition: { delay: 1300, duration: 600 } }"
		class="arrow flex flex-col items-center">
		<carbon:arrow-right class="text-3xl text-black" />
		<span class="text-xs text-black mt-1">作成</span>
	</div>
	<div v-motion
		:initial="{ scale: 0, rotate: -180 }"
		:enter="{ scale: 1, rotate: 0, transition: { delay: 1500, duration: 800 } }"
		class="flow-item">
		<carbon:document class="text-4xl text-purple-500 mb-2" />
		<div class="text-center">書類</div>
	</div>
</div>


<style>
.flow-item {
@apply bg-white p-6 rounded-lg shadow-lg border border-gray-200 text-center;
}

.arrow {
@apply flex items-center justify-center;
}
</style>
