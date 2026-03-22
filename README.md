[未命名.html](https://github.com/user-attachments/files/26164948/default.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>经典贪吃蛇 - 游戏介绍</title>
    <!-- 引入与游戏一致的样式库 -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        snake: '#22c55e',
                        dark: '#111827',
                        food: '#ef4444'
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-dark text-white min-h-screen">
    <div class="max-w-3xl mx-auto px-4 py-16 flex flex-col items-center text-center">
        
        <!-- 标题区域 -->
        <div class="mb-10">
            <h1 class="text-[clamp(2.5rem,5vw,4rem)] font-bold text-snake mb-3">🐍 经典贪吃蛇</h1>
            <p class="text-gray-300 text-lg">极简复古 | 轻松上手 | 无限挑战</p>
        </div>

        <!-- 游戏预览图 -->
        <div class="w-full max-w-sm bg-black rounded-lg p-3 mb-10 border-2 border-gray-700">
            <div class="aspect-square bg-black rounded flex items-center justify-center text-snake text-7xl">
                🐍
            </div>
        </div>

        <!-- 游戏简介 -->
        <div class="mb-10 w-full">
            <h2 class="text-xl font-semibold text-snake mb-4">游戏简介</h2>
            <p class="text-gray-200 leading-relaxed">
                经典贪吃蛇是一款陪伴几代人的休闲小游戏。通过控制蛇的方向吃掉食物，让蛇不断变长，同时避免撞墙或撞到自己。
                游戏节奏轻松，难度随分数动态提升，越玩越刺激！
            </p>
        </div>

        <!-- 玩法说明 -->
        <div class="mb-10 w-full text-left">
            <h2 class="text-xl font-semibold text-snake mb-4 text-center">玩法说明</h2>
            <div class="grid md:grid-cols-2 gap-4">
                <div class="bg-gray-800 p-4 rounded-lg">
                    <p><i class="fa fa-keyboard-o text-snake mr-2"></i> 方向键控制移动</p>
                </div>
                <div class="bg-gray-800 p-4 rounded-lg">
                    <p><i class="fa fa-apple text-food mr-2"></i> 吃掉红色苹果得分</p>
                </div>
                <div class="bg-gray-800 p-4 rounded-lg">
                    <p><i class="fa fa-arrows-h text-snake mr-2"></i> 手机滑动/虚拟按键操作</p>
                </div>
                <div class="bg-gray-800 p-4 rounded-lg">
                    <p><i class="fa fa-warning text-yellow-400 mr-2"></i> 不能撞墙/不能咬到自己</p>
                </div>
            </div>
        </div>

        <!-- 游戏特色 -->
        <div class="mb-12 w-full">
            <h2 class="text-xl font-semibold text-snake mb-4">游戏特色</h2>
            <div class="flex flex-wrap justify-center gap-4">
                <span class="px-4 py-2 bg-gray-800 rounded-full">🎮 全设备支持</span>
                <span class="px-4 py-2 bg-gray-800 rounded-full">🚀 动态速度提升</span>
                <span class="px-4 py-2 bg-gray-800 rounded-full">📊 最高分记录</span>
                <span class="px-4 py-2 bg-gray-800 rounded-full">🔊 音效开关</span>
                <span class="px-4 py-2 bg-gray-800 rounded-full">⏸ 可暂停游戏</span>
            </div>
        </div>

        <!-- 开始游戏按钮 -->
        <a href="index.html" class="bg-snake hover:bg-green-500 text-white font-bold text-xl px-10 py-3 rounded-lg transition-colors mb-6">
            开始游戏
        </a>

        <p class="text-gray-400 text-sm">© 2026 经典贪吃蛇 | 纯前端网页游戏</p>
    </div>
</body>
</html>
