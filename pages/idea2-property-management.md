---
layout: default
---

# アイデア2
## 統合型物件検索＋空室状況管理プラットフォーム

<div class="flex flex-row items-center w-full min-h-[10rem]">
	<div class="flex-1">
		<div 
		v-motion
		:initial="{ x: -100, opacity: 0 }"
		:enter="{ x: 0, opacity: 1, transition: { delay: 300, duration: 800 } }"
		class="text-xl mt-8"
		>🏢 物件管理の革新：統合検索と空室管理の一元化
		</div>
	</div>
	<div class="flex-1 flex justify-end">
		<div v-motion
		:initial="{ x: 100, opacity: 0, scale: 0.8 }"
		:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 200, duration: 900 } }"
		class="mr-2"
		>
			<img src="/assets/building.jpg" alt="物件管理" class="w-80 h-80 drop-shadow-2xl rounded-2xl bg-white object-cover" />
		</div>
	</div>
</div>

---
transition: slide-up
---

# 🔍 現在の問題点

<div class="grid grid-cols-1 gap-2">
	<div 
		v-motion
		:initial="{ y: 40, opacity: 0, scale: 0.95 }"
		:enter="{ y: 0, opacity: 1, scale: 1, transition: { delay: 200, duration: 600, type: 'spring' } }"
		class="bg-red-100 p-6 rounded-lg"
	>
		<div class="flex items-center mb-4">
			<carbon:data-unstructured class="text-red-500 mr-3 text-2xl" />
			<h3 class="text-xl font-bold text-red-700">断片的な物件情報収集</h3>
		</div>
		<p class="text-gray-700">
			複数のサイトから手動で物件情報を収集しており、非常に時間と手間がかかります。
		</p>
	</div>
	<div 
		v-motion
		:initial="{ x: -60, opacity: 0, scale: 0.9 }"
		:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 400, duration: 600, type: 'spring' } }"
		class="bg-orange-100 p-6 rounded-lg"
	>
		<div class="flex items-center mb-4">
			<carbon:time class="text-orange-500 mr-3 text-2xl" />
			<h3 class="text-xl font-bold text-orange-700">リアルタイムな空室状況の把握困難</h3>
		</div>
		<p class="text-gray-700">
			物件の空室状況やリノベーション進捗がタイムリーに確認できず、機会損失につながっています。
		</p>
	</div>
	<div 
		v-motion
		:initial="{ x: 60, opacity: 0, scale: 0.9 }"
		:enter="{ x: 0, opacity: 1, scale: 1, transition: { delay: 600, duration: 600, type: 'spring' } }"
		class="bg-yellow-100 p-6 rounded-lg"
	>
		<div class="flex items-center mb-4">
			<carbon:money class="text-yellow-500 mr-3 text-2xl" />
			<h3 class="text-xl font-bold text-yellow-700">空室期間の長期化リスク</h3>
		</div>
		<p class="text-gray-700">
			物件の準備状況（清掃、修繕、リノベーションなど）の管理が煩雑なため、不必要な空室期間が発生し、収益機会を逃す可能性があります。
		</p>
	</div>
</div>

---
layout: full
layoutClass: gap-8
---

# 🛠️ 主要機能


<div class="flex flex-row gap-4 w-full">
	<div class="flex-1 space-y-4">
		<div
			v-motion
			:initial="{ x: -80, y: 40, opacity: 0, scale: 0.8 }"
			:enter="{ x: 0, y: 0, opacity: 1, scale: 1, transition: { delay: 200, duration: 600, type: 'spring' } }"
			class="feature-card"
		>
			<carbon:search class="text-blue-500 text-2xl mb-2" />
			<h3 class="font-bold text-lg mb-2">複数サイト横断検索</h3>
			<p class="text-sm opacity-80">複数の外部物件サイトから情報を集約し、一元的に検索・比較する機能</p>
		</div>
		<div
			v-motion
			:initial="{ x: -80, y: 40, opacity: 0, scale: 0.8 }"
			:enter="{ x: 0, y: 0, opacity: 1, scale: 1, transition: { delay: 400, duration: 600, type: 'spring' } }"
			class="feature-card"
		>
			<carbon:dashboard class="text-green-500 text-2xl mb-2" />
			<h3 class="font-bold text-lg mb-2">リアルタイム空室管理</h3>
			<p class="text-sm opacity-80">全物件の入居状況、空室予定、リノベーション状況などをリアルタイムで表示するダッシュボード</p>
		</div>
	</div>
	<div class="flex-1 space-y-4">
		<div
			v-motion
			:initial="{ x: 80, y: 40, opacity: 0, scale: 0.8 }"
			:enter="{ x: 0, y: 0, opacity: 1, scale: 1, transition: { delay: 600, duration: 600, type: 'spring' } }"
			class="feature-card"
		>
			<carbon:flow class="text-purple-500 text-2xl mb-2" />
			<h3 class="font-bold text-lg mb-2">リノベーション・準備ワークフロー管理</h3>
			<p class="text-sm opacity-80">物件の清掃、修繕、リノベーションなどのタスク進捗管理と担当者割り当て</p>
		</div>
		<div
			v-motion
			:initial="{ x: 80, y: 40, opacity: 0, scale: 0.8 }"
			:enter="{ x: 0, y: 0, opacity: 1, scale: 1, transition: { delay: 800, duration: 600, type: 'spring' } }"
			class="feature-card"
		>
			<carbon:building class="text-orange-500 text-2xl mb-2" />
			<h3 class="font-bold text-lg mb-2">物件情報の一元管理</h3>
			<p class="text-sm opacity-80">物件の基本情報、写真、図面、契約履歴などを集約して管理</p>
		</div>
	</div>
</div>


<style>
.feature-card {
@apply bg-white p-4 rounded-lg shadow-md border border-gray-200;
}
.cloud-bg {
background: #fff;
border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
box-shadow: 0 2px 8px 0 #0001;
min-width: 120px;
min-height: 90px;
}
</style>

---
layout: center
---

# 🔄 アプリケーションの仕組み

<div class="relative w-full h-70 flex items-center justify-center">
<!-- Cloud with site logos (left) -->
	<div v-motion
		:initial="{ x: -200, opacity: 0 }"
		:enter="{ x: 0, opacity: 1, transition: { delay: 400, duration: 600 } }"
		class="absolute left-cloud"
	>
		<div class="flex flex-col items-center">
			<div class="cloud-bg flex flex-col items-center justify-center p-4" style="border: 2px solid #b3e0ff; background: linear-gradient(135deg, #e0f7fa 60%, #b3e0ff 100%); box-shadow: 0 4px 16px 0 #b3e0ff88;">
				<img src="../assets/suumo.jpg" alt="SUUMO" class="h-6 mb-2" />
				<img src="../assets/weekly-monthly.svg" alt="WEEKLY & MONTHLY" class="h-6 mb-2" />
				<img src="../assets/good-monthly.png" alt="グッドマンスリー" class="h-6 mb-2" />
			</div>
			<div class="text-center text-xs mt-2">外部ウェブサイトAPI</div>
			<style>
			.cloud-bg {
				background: linear-gradient(135deg, #e0f7fa 60%, #b3e0ff 100%);
				border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
				box-shadow: 0 4px 16px 0 #b3e0ff88;
				min-width: 120px;
				min-height: 90px;
				border: 2px solid #b3e0ff;
			}
			</style>
		</div>
	</div>
	<!-- Application (center) -->
	<div v-motion
		:initial="{ scale: 0, opacity: 0 }"
		:enter="{ scale: 1, opacity: 1, transition: { delay: 600, duration: 700 } }"
		class="absolute center-app"
	>
		<div class="flex flex-col items-center">
			<carbon:application-web class="text-6xl text-blue-500 mb-2" />
			<div class="text-center font-bold text-base">アプリケーション</div>
		</div>
	</div>
	<!-- Employee (right) -->
	<div v-motion
		:initial="{ x: 100, opacity: 0 }"
		:enter="{ x: 0, opacity: 1, transition: { delay: 800, duration: 600 } }"
		class="absolute right-employee"
		style=""
	>
		<div class="flex flex-col items-center">
		<carbon:user-filled class="text-6xl text-black mb-2" />
			<div style="background: #fff; border-radius: 8px; padding: 2px; display: inline-block;">
				<img src="/assets/stellarforce.png" alt="Stellar Force" style="height: 20px; width: auto; display: block;" />
			</div>
		<div class="text-center font-bold text-base">従業員</div>
		</div>
	</div>
	<!-- Arrow: Cloud → Application (with label) -->
	<div v-motion
		:initial="{ opacity: 0 }"
		:enter="{ opacity: 1, transition: { delay: 900, duration: 600 } }"
		class="absolute arrow-cloud-app flex flex-col items-center"
	>
		<carbon:arrow-right class="text-2xl text-black" />
		<div class="text-xs mt-1 text-black">24時間ごとに<br>データ取得</div>
	</div>
	<!-- Arrow: Application → Employee (通知) -->
	<div v-motion
		:initial="{ opacity: 0 }"
		:enter="{ opacity: 1, transition: { delay: 1000, duration: 600 } }"
		class="absolute arrow-app-emp-notify flex flex-col items-center"
	>
		<carbon:arrow-right class="text-2xl text-black" />
		<div class="text-xs mt-1 text-black">通知</div>
	</div>
	<!-- Arrow: Employee → Application (アクセス) -->
	<div v-motion
		:initial="{ opacity: 0 }"
		:enter="{ opacity: 1, transition: { delay: 1100, duration: 600 } }"
		class="absolute arrow-emp-app-access flex flex-col items-center"
	>
		<carbon:arrow-left class="text-2xl text-black" />
		<div class="text-xs mt-1 text-black">アプリアクセス</div>
	</div>
</div>

<style>
.left-cloud {
	left: -20%; 
	top: 40%;
	transform: translate(-50%, -50%);
}
.center-app {
	left: 50%; 
	top: 45%;
	transform: translate(-150%, -50%);
}
.right-employee {
	right: -20%; 
	top: 40%;
	transform: translate(50%, -50%);
}
.arrow-cloud-app {
left: 28%;
top: 50%;
transform: translate(-50%, -50%);
}
.arrow-app-emp-notify {
left: 85%;
top: 65%;
transform: translate(-50%, -50%);
}
.arrow-emp-app-access {
left: 81%;
top: 45%;
transform: translate(-50%, -50%);
}
</style>