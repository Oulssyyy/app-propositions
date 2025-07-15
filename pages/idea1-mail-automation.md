---
layout: default
---

# アイデア1
## メール自動送信アプリケーション

<div class="flex flex-row items-center w-full min-h-[10rem]">
	<div class="flex-1">
		<div 
			v-motion
			:initial="{ x: -100, opacity: 0 }"
			:enter="{ x: 0, opacity: 1, transition: { delay: 300, duration: 800 } }"
			class="text-xl mt-8"
		>
			📧 メール業務の自動化
		</div>
	</div>
	<div class="flex-1 flex justify-end">
		<div v-motion
			:initial="{ x: 100, opacity: 0, scale: 0.8 }"
			:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 200, duration: 900 } }"
		>
			<img src="/assets/automation.jpg" alt="メール自動送信" class="w-96 h-96 drop-shadow-2xl rounded-2xl bg-white object-cover" />
		</div>
	</div>
</div>

---
transition: slide-up
---

# 🚨 現在の問題点

<div class="grid grid-cols-1 gap-2">
	<div
		v-motion
		:initial="{ x: -80, opacity: 0, scale: 0.9 }"
		:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 200, duration: 600, type: 'spring' } }"
		class="bg-red-100 p-6 rounded-lg"
	>
		<div class="flex items-center mb-4">
			<carbon:warning class="text-red-500 mr-3 text-2xl" />
			<h3 class="text-xl font-bold text-red-700">手動作業による負担</h3>
		</div>
		<p class="text-gray-700">
			入居、契約延長、退去案内などのメール送信がすべて手作業で行われており、多くの時間と労力を消費しています。
		</p>
	</div>
	<div
		v-motion
		:initial="{ x: 80, opacity: 0, scale: 0.9 }"
		:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 400, duration: 600, type: 'spring' } }"
		class="bg-orange-100 p-6 rounded-lg"
	>
		<div class="flex items-center mb-4">
			<carbon:error class="text-orange-500 mr-3 text-2xl" />
			<h3 class="text-xl font-bold text-orange-700">人的ミスのリスク</h3>
		</div>
		<p class="text-gray-700">
			送信日時、宛先、内容の誤りなど、手動による作業が原因のヒューマンエラーが発生する可能性があります。
		</p>
	</div>
	<div
		v-motion
		:initial="{ y: 60, opacity: 0, scale: 0.9 }"
		:enter="{ y: 0, opacity: 1, scale: 1, transition: { delay: 600, duration: 600, type: 'spring' } }"
		class="bg-yellow-100 p-6 rounded-lg"
	>
		<div class="flex items-center mb-4">
			<carbon:scale class="text-yellow-500 mr-3 text-2xl" />
			<h3 class="text-xl font-bold text-yellow-700">スケーラビリティの限界</h3>
		</div>
		<p class="text-gray-700">
			契約数が増加するにつれて、手動でのメール送信は処理能力の限界に達し、業務遅延や品質低下を招く恐れがあります。
		</p>
	</div>
</div>

---
layout: full
layoutClass: gap-16
---

# ✨ 主要機能

<div class="flex flex-row gap-8 w-full">
	<div class="flex-1 space-y-4">
		<div
			class="feature-card"
			v-motion
			:initial="{ x: -80, opacity: 0, scale: 0.9 }"
			:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 200, duration: 600, type: 'spring' } }"
		>
			<span class="text-blue-500 text-2xl mb-2">📤</span>
			<h3 class="font-bold text-lg mb-2">自動送信設定</h3>
			<p class="text-sm opacity-80">契約開始日・終了日、イベント（入居、延長、退去）に基づいたメールの自動送信設定</p>
		</div>
		<div
			class="feature-card"
			v-motion
			:initial="{ x: -80, opacity: 0, scale: 0.9, rotate: -8 }"
			:enter="{ x: 0, opacity: 1, scale: 1, rotate: 0, transition: { delay: 400, duration: 600, type: 'spring' } }"
		>
			<span class="text-green-500 text-2xl mb-2">📝</span>
			<h3 class="font-bold text-lg mb-2">テンプレート管理</h3>
			<p class="text-sm opacity-80">用途に応じたメールテンプレートの作成、編集、管理機能</p>
		</div>
	</div>
	<div class="flex-1 space-y-4">
		<div
			class="feature-card"
			v-motion
			:initial="{ x: 80, opacity: 0, scale: 0.9, rotate: 8 }"
			:enter="{ x: 0, opacity: 1, scale: 1, rotate: 0, transition: { delay: 600, duration: 600, type: 'spring' } }"
		>
			<span class="text-orange-500 text-2xl mb-2">📊</span>
			<h3 class="font-bold text-lg mb-2">送信履歴とログ</h3>
			<p class="text-sm opacity-80">送信されたメールの履歴、ステータス、エラーログの一元管理</p>
		</div>
		<div
			class="feature-card"
			v-motion
			:initial="{ x: 80, opacity: 0, scale: 0.9, rotate: -8 }"
			:enter="{ x: 0, opacity: 1, scale: 1, rotate: 0, transition: { delay: 800, duration: 600, type: 'spring' } }"
		>
			<span class="text-teal-500 text-2xl mb-2">👤</span>
			<h3 class="font-bold text-lg mb-2">個別カスタマイズ</h3>
			<p class="text-sm opacity-80">受信者ごとの情報差し込み（氏名、物件名など）によるパーソナライズ</p>
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

<div class="relative w-full h-96 flex items-center justify-center">
	<!-- Application centrale -->
	<div
		v-motion
		:initial="{ scale: 0, opacity: 0, y: 40 }"
		:enter="{ scale: 1, opacity: 1, y: 70, transition: { delay: 500, duration: 800 } }"
		class="center-app flex flex-col items-center justify-center"
		style="transform: translateY(40px);"
	>
		<carbon:application class="text-6xl text-blue-500 mb-2" />
		<div class="text-center font-bold text-lg">アプリケーション</div>
	</div>
	<!-- Données d'entreprise (Stellar Force) - En haut -->
	<div v-motion
		:initial="{ y: -200, opacity: 0 }"
		:enter="{ y: 0, opacity: 1, transition: { delay: 800, duration: 600 }, x: -100 }"
		class="absolute top-data left-1/2"
		style="left: 35%; transform: translate(-50%, 0);"
	>
		<div class="flex flex-col items-center bg-white p-4 rounded-lg shadow-lg border border-gray-200">
			<img src="/assets/stellarforce.png" alt="Stellar Force" class="w-full h-12 mb-2" />
			<div class="text-center text-sm font-semibold">企業データ</div>
		</div>
	</div>
	<!-- Configuration - À gauche -->
	<div v-motion
		:initial="{ x: -200, opacity: 0 }"
		:enter="{ x: 0, opacity: 1, transition: { delay: 1000, duration: 600 } }"
		class="absolute left-config"
	>
		<div class="flex flex-col items-center bg-white p-4 rounded-lg shadow-lg border border-gray-200">
			<carbon:settings class="text-4xl text-green-500 mb-2" />
			<div class="text-center text-sm font-semibold">設定データ</div>
		</div>
	</div>
	<!-- Envoi de mails - À droite -->
	<div v-motion
		:initial="{ x: 200, opacity: 0 }"
		:enter="{ x: 0, opacity: 1, transition: { delay: 1200, duration: 600 } }"
		class="absolute right-mail"
	>
		<div class="flex flex-col items-center bg-white p-4 rounded-lg shadow-lg border border-gray-200">
		<carbon:send class="text-4xl text-purple-500 mb-2" />
		<div class="text-center text-sm font-semibold">メール送信</div>
		</div>
	</div>
	<!-- Flèches bidirectionnelles vers données d'entreprise -->
	<div v-motion
		:initial="{ opacity: 0 }"
		:enter="{ opacity: 1, transition: { delay: 1400, duration: 800 } }"
		class="absolute top-arrow-up">
		<carbon:arrow-up class="text-2xl text-blue-500" />
	</div>
	<div v-motion
		:initial="{ opacity: 0 }"
		:enter="{ opacity: 1, transition: { delay: 1400, duration: 800 } }"
		class="absolute top-arrow-down">
		<carbon:arrow-down class="text-2xl text-blue-500" />
	</div>
	<!-- Flèche depuis configuration vers application -->
	<div v-motion
		:initial="{ opacity: 0 }"
		:enter="{ opacity: 1, transition: { delay: 1600, duration: 800 } }"
		class="absolute left-arrow">
		<carbon:arrow-right class="text-2xl text-green-500" />
	</div>
	<!-- Flèche depuis application vers envoi de mails -->
	<div v-motion
		:initial="{ opacity: 0 }"
		:enter="{ opacity: 1, transition: { delay: 1800, duration: 800 } }"
		class="absolute right-arrow">
		<carbon:arrow-right class="text-2xl text-purple-500" />
	</div>
</div>

<style>
.center-app {
left: 50%;
top: 50%;
@apply bg-white p-6 rounded-lg shadow-lg border border-gray-200;
}

.top-data {
left: 0%;
top: 0%;
}

.left-config {
left: -15%;
top: 60%;
}

.right-mail {
right: -15%;
top: 60%;
}

.top-arrow-up {
left: 40%;
top: 35%;
}

.top-arrow-down {
left: 55%;
top: 35%;
}

.left-arrow {
left: 15%;
top: 70%;
}

.right-arrow {
right: 15%;
top: 70%;
}
</style>
---