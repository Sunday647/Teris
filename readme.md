This is a simple single-player game, Teris
这是我做的第一个单机小游戏--俄罗斯方块。俄罗斯方块也是我小时候玩的第一款游戏，在自己家的电视上~。~O(∩_∩)O哈哈~

这个游戏的目录很简单：
index.html   ------- 游戏的页面架构
style.css    ------- 游戏的表现层，页面所有样式的渲染
js           ------- 游戏的行为层，各种操作的逻辑架构
--square.js               ---- 定义生成方块的基本属性和方法
--squareFactory.js        ---- 工厂模式，生成7中俄罗斯方块，每种方块在继承基本方块属性方法后，定义自己的属性值
--game.js                 ---- 定义游戏的各种操作：初始化，方向键和空格键操作，执行下一个方块，计时，∫，加分，消/加行等
--local.js                ---- 本地页面的游戏操作，如开始、结束等。
                              （因为打算后期改进做一个双人battle版的，已经完成80%，双人版中对应有remote.js）
--scriptjs                ---- 游戏的开始
