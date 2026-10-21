代发 wailian999

[U65] PHP：会话
来源：http://dali.yueranfly.top/Article/details/gtxsmvnbqx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtyoydzcfi.html

[U66] PHP：设置 Cookie
来源：http://dali.jinghuilouyu.cn/Article/details/gtroywydtg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gotoacloud.top/Article/details/gtumgkxrpy.html

[U67] PHP：处理文件上传
来源：http://dali.hnxiangtu.top/Article/details/gtolnchnhx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258888.top/Article/details/gtbquxcgyl.html

[U68] PHP：PDO 连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkolgqvsp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangtech.top/Article/details/gttrpeecwy.html

[U69] PHP：PDO 预处理
来源：http://dali.yueranfly.top/Article/details/gtshaktzrq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenjidiqi.icu/Article/details/gtrgeohdue.html

[U70] PHP：PDO 事务
来源：http://dali.daxiang520.top/Article/details/gtclkvhigb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tanke756.top/Article/details/gtvzkkyust.html

[U71] PHP：抛出异常
来源：http://dali.redwolf501.top/Article/details/gtwxrgfblt.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtoqmkzkgq.html

[U72] PHP：写错误日志
来源：http://dali.kuanghao11.cn/Article/details/gtbvkofnox.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgfzy.top/Article/details/gtafddyzgl.html

[U73] PHP：读取 ini 配置
来源：http://dali.daxiang520.top/Article/details/gttnhtpawt.html

parse_ini_file("config.ini", true)
来源：http://dali.daxiang520.top/Article/details/gtoivsfosb.html

[U74] PHP：读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtsuqsoxgh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ydzc1.top/Article/details/gtygmosgpw.html

[U75] PHP：依赖注入
来源：http://dali.yanxiufei.cn/Article/details/gtbjhwgvue.html

composer require psr/container
来源：http://dali.smart0.xyz/Article/details/gtnzienofi.html

[U76] PHP：简单路由
来源：http://dali.gaohongyu789.top/Article/details/gttkmevtci.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangshuangyany.cn/Article/details/gtylwlqlgw.html

[U77] PHP：模板渲染
来源：http://dali.andypj.xyz/Article/details/gtgbfdzfbb.html

composer require twig/twig
来源：http://dali.gogol.net.cn/Article/details/gtqtxhfdjk.html

[U78] PHP：单元测试
来源：http://dali.aibaodan.cn/Article/details/gtxpfksuod.html

composer require --dev phpunit/phpunit
来源：http://dali.guannengcc.top/Article/details/gtmcpndvaf.html

[U79] PHP：静态分析
来源：http://dali.zhixingplan.top/Article/details/gtxsaiahjm.html

composer require --dev phpstan/phpstan
来源：http://dali.9152youxi.cn/Article/details/gtumtiqjvw.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gtuuvqclel.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sxryk.cn/Article/details/gtrojjbyif.html

[U81] JS：初始化项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqosvjeu.html

npm init -y;  npm i express
来源：http://dali.yj202588.top/Article/details/gtxwlzsrmv.html

[U82] JS：package.json 脚本
来源：http://dali.yuxming.cn/Article/details/gtnhcxbses.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.aibaodan.cn/Article/details/gtudgmfkvf.html

[U83] JS：ES Module 导入导出
来源：http://dali.yonumen.top/Article/details/gtpiiesfgz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtrjjwdvme.html

[U84] JS：CommonJS 写法
来源：http://dali.shzxlz.cn/Article/details/gtwziltceg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yangfankeji.com/Article/details/gtfdjleqhw.html

[U85] JS：可选链
来源：http://dali.xylfe.cn/Article/details/gtydsqrgzi.html

a?.b?.c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeqfvikx.html

[U86] JS：空值合并
来源：http://dali.redwolf501.top/Article/details/gtaahxuyib.html

a ?? b
来源：http://dali.tanke756.top/Article/details/gtpkbhfshx.html

[U87] JS：解构默认值
来源：http://dali.zycfv.cn/Article/details/gtsxpzryoz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zycfv.cn/Article/details/gtjvlkpmzi.html

[U88] JS：对象展开合并
来源：http://dali.hywenlv.cn/Article/details/gtirjuidsx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gtxjatdtxu.html

[U89] JS：数组去重
来源：http://dali.daria6918.cn/Article/details/gtxwggmfsk.html

[...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtnmrwbart.html

[U90] JS：数字数组排序
来源：http://dali.nanxuanxn.top/Article/details/gtezjhvnuq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtuthqfksv.html

[U91] JS：对象键值遍历
来源：http://dali.yangfankeji.com/Article/details/gtvatmeqzz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.0kj1m.cn/Article/details/gtmdxjqehl.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gttwmlwtwa.html

structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtvwnehhzj.html

[U93] JS：模板字符串
来源：http://dali.gaohongyu789.top/Article/details/gtkccahoro.html

`共 ${n} 条`
来源：http://dali.316326.xyz/Article/details/gtklriodxx.html

[U94] JS：箭头函数
来源：http://dali.yj20258.top/Article/details/gteypxcutb.html

const double = x => x * 2;
来源：http://dali.c1oappe.top/Article/details/gtweveream.html

[U95] JS：Promise 包装
来源：http://dali.tianlin.xyz/Article/details/gtmqugafxe.html

new Promise((resolve, reject) => {})
来源：http://dali.smart0.xyz/Article/details/gtwxznvqkk.html

[U96] JS：async/await 与异常
来源：http://dali.fengsongda.top/Article/details/gtesieatvv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gterhvgluz.html

[U97] JS：并发请求
来源：http://dali.yj202588.top/Article/details/gtswutlrjr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gthjezrkcn.html

[U98] JS：fetch 带 JSON
来源：http://dali.bjfxy.top/Article/details/gtvtmhapmx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhengqikj.top/Article/details/gtpjwdcizt.html

[U99] JS：事件监听
来源：http://dali.guowangkeji.top/Article/details/gthuuegmba.html

el.addEventListener("click", e => {})
来源：http://dali.zhongyouzk.top/Article/details/gtrsppjkor.html

[U100] JS：DOM 查询
来源：http://dali.yuxming.cn/Article/details/gtnwlzrziy.html

document.querySelector(".item")
来源：http://dali.fengsongda.top/Article/details/gtolkvpnzu.html

[U101] JS：classList 操作
来源：http://dali.jlsjyb.cn/Article/details/gtrkowzebn.html

el.classList.toggle("active")
来源：http://dali.aibaodan.cn/Article/details/gtpzmocqnn.html

[U102] JS：本地存储
来源：http://dali.shuidangran.top/Article/details/gtrdcrkcjk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guowangkeji.top/Article/details/gtbcmqsyrv.html

[U103] JS：定时器
来源：http://dali.yj20258888.top/Article/details/gtootpqptt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxinkj.top/Article/details/gthbqoenjl.html

[U104] JS：防抖
来源：http://dali.jianghu66.top/Article/details/gtdsyxwfxs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtxnlnqgrx.html

[U105] JS：节流
来源：http://dali.zhongyouzk.top/Article/details/gtcnulvlev.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gtnyyxqyvt.html

[U106] JS：日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdejqexw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hysaishi.cn/Article/details/gtulcqvfcm.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gtdssjwrsv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtknlnrzdv.html

[U108] JS：随机整数
来源：http://dali.sxryk.cn/Article/details/gtycbxcead.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cheryme.top/Article/details/gtowqieriu.html

[U109] JS：数组分组
来源：http://dali.chenlongwang.top/Article/details/gtojggglsf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gtharyhsik.html

[U110] JS：数组分块
来源：http://dali.fengsongda.top/Article/details/gtgkulmcxu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cqqwz.cn/Article/details/gtminsfybg.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gtfqqgbjjo.html

new Map(Object.entries(obj))
来源：http://dali.daxiang520.top/Article/details/gtiszgxeyp.html

[U112] JS：字符串补位
来源：http://dali.daxiang520.top/Article/details/gtpicnwtsk.html

"7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtpgguhxuw.html

[U113] JS：正则替换全部
来源：http://dali.tian-w.cn/Article/details/gtfwqqwxkj.html

s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtmywlqnar.html

[U114] JS：JSON 深比较
来源：http://dali.zdqjudy.top/Article/details/gtrjauejdr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtibnwissn.html

[U115] JS：生成 UUID
来源：http://dali.daria6918.cn/Article/details/gtprjdkxis.html

crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gteuongfch.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.svipenyu.cn/Article/details/gtodsfcqwc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ppjwa.cn/Article/details/gtaymmpiil.html

[U117] JS：单元测试
来源：http://dali.daxiang520.top/Article/details/gtjfegjhpx.html

npm i -D vitest;  npx vitest
来源：http://dali.redwolf501.top/Article/details/gtrispamka.html

[U118] JS：开发服务器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkwkskhs.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gtfaoshdtv.html

[U119] JS：生产构建
来源：http://dali.wangdashe.top/Article/details/gtknsricye.html

npx vite build
来源：http://dali.yj202588.top/Article/details/gtvqfytvua.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gtzabpfneb.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigufen.top/Article/details/gtfxtgwfiz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtzitlsncz.html

统计汇总
来源：http://dali.ppjwa.cn/Article/details/gtcehxuhpe.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttfjyuejs.html

按语言统计（条）：
来源：http://dali.aizwys.cn/Article/details/gtxmrewtiq.html

Python ......... 252
来源：http://dali.gotoacloud.top/Article/details/gtwjkfxxzr.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gtvpxslhqc.html

JavaScript ..... 252
来源：http://dali.andypj.xyz/Article/details/gtgfusifdh.html

TypeScript ..... 212
来源：http://dali.ydzc1.top/Article/details/gtlhlrlfyp.html

Java ........... 212
来源：http://dali.9152youxi.cn/Article/details/gtfvshrjpz.html

Go ............. 212
来源：http://dali.gzhubu.top/Article/details/gtsvybpnha.html

Ruby ........... 212
来源：http://dali.ivvv.top/Article/details/gtwdhngkkh.html

C# ............. 212
来源：http://dali.pycfn.com/Article/details/gtiqtuuzwh.html

C .............. 30
来源：http://dali.zycfv.cn/Article/details/gtqplktzhc.html

C++ ............ 30
来源：http://dali.tanke756.top/Article/details/gtoxtdhood.html

SQL ............ 90
来源：http://dali.jqgfzy.top/Article/details/gtgzqjjuzc.html

Bash ........... 80
来源：http://dali.cucudq.cn/Article/details/gtfabcrgam.html

Kotlin ......... 15
来源：http://dali.xinyue.icu/Article/details/gtdqkmdifr.html

Swift .......... 15
来源：http://dali.zdqjudy.top/Article/details/gtnudhuaxb.html

Lua ............ 10
来源：http://dali.aizwys.cn/Article/details/gtthuavyiu.html

Perl ........... 10
来源：http://dali.hywenlv.cn/Article/details/gtnyllitmc.html

Scala .......... 10
来源：http://dali.hywenlv.cn/Article/details/gtwsvmztxd.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtohowyanj.html

合计 ........... 2106 条
来源：http://dali.jyoumei.cn/Article/details/gtopvollxh.html

按章节统计：
来源：http://dali.chenlongwang.top/Article/details/gtqhhjjxwy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gtebuksuuk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gttcwcrujn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtmbjpieal.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtqlzfwnbn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cucudq.cn/Article/details/gtymatupro.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cucudq.cn/Article/details/gtagjynvpz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtoxoxrtce.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtlpnvszuh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtdqpkivtr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gtuhjihtih.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtnwsugass.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtcpwpexqu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtpehcrlbw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gtnayujmrk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ppjwa.cn/Article/details/gtqpjyprdp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztwayoku.html

Q SQL 专题                              90
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkqvjrms.html

R Bash 专题                             80
来源：http://dali.tanke756.top/Article/details/gthcokjiik.html

S C / C++ 专题                          60
来源：http://dali.yuxming.cn/Article/details/gtrcqrpdwo.html

T 其他语言补充                          60
来源：http://dali.chenzaomai.com/Article/details/gtefttvpch.html

U 高频实用片段                         120
来源：http://dali.guannengcc.top/Article/details/gtjnkbfrsf.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gtwjwmaukb.html

合计                                  2106 条
来源：http://dali.jqgufenzy.top/Article/details/gtkgchwvww.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtpdjslqct.html

使用提醒
来源：http://dali.wangshuangyany.cn/Article/details/gtgeyvrzld.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtqjfsddxd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gtglbeiyoe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhiwuduotai.top/Article/details/gtvrqpurbx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zdqjudy.top/Article/details/gttcyakyff.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ivvv.top/Article/details/gtdtuyewlt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tian-w.cn/Article/details/gtwcmrouax.html

—— 文件结束 ——
来源：http://dali.xuanzx.com/Article/details/gtrlmwsfoy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtryurunfq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.birdmap.top/Article/details/gtzcfzzwmg.html

Common Programming Examples Cheat Book
来源：http://dali.yj202588.top/Article/details/gtfkixypwu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqiksdueh.html

【收录内容】
来源：http://dali.jinghuilouyu.cn/Article/details/gtoypwjhrh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tanke756.top/Article/details/gtclzaunse.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yanxiufei.cn/Article/details/gtzlhwaujk.html

SQL · Bash · C · C++
来源：http://dali.iojbl.cn/Article/details/gtwsjrtygu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gotoacloud.top/Article/details/gtbcwonjxm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gtrpvaqrig.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hammf.cn/Article/details/gtpkrbsrjd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jqgufenzy.top/Article/details/gtbpxtxvgj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhiwuduotai.top/Article/details/gtrwfzgdyn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxuanxn.top/Article/details/gtoizhtanp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnqzz.top/Article/details/gtefucokdb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangshuangyany.cn/Article/details/gtdmpdedtx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.9152youxi.cn/Article/details/gtuupazhbq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jiagoushi.top/Article/details/gtqywmgnfh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhengqikj.top/Article/details/gtpaipobyd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.0kj1m.cn/Article/details/gtjytqfetl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hongshengwenyu.top/Article/details/gtxjzhisbm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmornbvl.html

【文件统计】
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsexijatn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zdqjudy.top/Article/details/gtwrirpdkv.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gttzzomlqy.html

目  录
来源：http://dali.chenlongwang.top/Article/details/gtzwbjrmbw.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtbbtppqql.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gtwpdnrmxz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtdgazohto.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtemtuyfjp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyiwjlaf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hywenlv.cn/Article/details/gtprulovqs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gtctesikwr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtlpvbttqe.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gtvaoyslcm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtnqakrufc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gttldcxwmg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gttunhgypo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtdlmjsqcf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtrljbpwui.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gtrayjkhxl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.smart0.xyz/Article/details/gtnuensdqa.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtrhktdykg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.kuanghao11.cn/Article/details/gtwgxuaqwl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtwmatwvom.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxdnrffc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtenorujzi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ydzc1.top/Article/details/gteqrpbhub.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwaqbfghp.html

A. 基础语法与类型
来源：http://dali.dianchejie.cn/Article/details/gtjwlqgvjg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpfmygoll.html

[A01] Hello World
来源：http://dali.xinyue.icu/Article/details/gtcwvcbsbz.html

Py:   print("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gtsqicsabm.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttolssaq.html

JS:   console.log("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gtencoijgb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvifqojmv.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gtlcruobnf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gtzkbnwdrh.html

Ruby: puts "Hello, World!"
来源：http://dali.wangshuangyany.cn/Article/details/gtfibxlqjd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbzlorog.html

[A02] 变量声明与赋值
来源：http://dali.gzhubu.top/Article/details/gtsumojvgr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hammf.cn/Article/details/gtdfmetwrf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.fzhhl.top/Article/details/gtnyzuvkmm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtfkilkrtp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtmzviyuqn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtygvujxcy.html

Go:   name := "Alex"; age := 20
来源：http://dali.xziqi.cn/Article/details/gtcxhlbieg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.iojbl.cn/Article/details/gtupuuhfje.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xuanzx.com/Article/details/gtosidkmsg.html

[A03] 常量定义
来源：http://dali.cucudq.cn/Article/details/gttradkprj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cdnleiting.top/Article/details/gtldcaqtlj.html

PHP:  const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtsrqstnoo.html

JS:   const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtcdnlacjt.html

TS:   const PI: number = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtqouivbnl.html

Java: static final double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtmpkhnhtm.html

Go:   const PI = 3.14159
来源：http://dali.xylfe.cn/Article/details/gtivoiwoja.html

Ruby: PI = 3.14159
来源：http://dali.cashguo.top/Article/details/gtwphcjqxw.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtycgcozdo.html

[A04] 判断变量类型
来源：http://dali.ppjwa.cn/Article/details/gtqrthrrau.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuxming.cn/Article/details/gtltxgplei.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigufen.top/Article/details/gtzznfeyjs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriqpnsil.html

TS:   typeof x; x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gtnyuqfano.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhiwuduotai.top/Article/details/gtxhxkyzow.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aizwys.cn/Article/details/gtvevijvmq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yanxiufei.cn/Article/details/gtnlrfaamu.html

C#:   x.GetType().Name; x is int
来源：http://dali.jiagoushi.top/Article/details/gtrgkcwnwg.html

[A05] 整数除法与取模
来源：http://dali.nwbrower.top/Article/details/gtbjidkdol.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.bjfxy.top/Article/details/gtluguqagk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiixltvtb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtcebqghyt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaczfzaf.html

Java: 7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtylpgfjvo.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtpvivtmvf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtgzfmeonr.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtzwigkarq.html

[A06] 字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqrmtvcs.html

Py:   int("42"); float("3.14")
来源：http://dali.316326.xyz/Article/details/gtzildrogc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tanke756.top/Article/details/gtifukeciw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj202588.top/Article/details/gtqspvfjfh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cashguo.top/Article/details/gtosvghrxe.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.9152youxi.cn/Article/details/gtzihtjtmi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj202588.top/Article/details/gtriqxjtok.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sysykeji.top/Article/details/gtyfzuegwh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sxryk.cn/Article/details/gtzvlajqyh.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtubiuswzx.html

Py:   str(42)
来源：http://dali.9152youxi.cn/Article/details/gtuxyopvnw.html

PHP:  (string) 42; strval(42)
来源：http://dali.shangyingyoupin.top/Article/details/gtwqgwbfgc.html

JS:   String(42); (42).toString()
来源：http://dali.iojbl.cn/Article/details/gtjmgxglaj.html

TS:   String(42)
来源：http://dali.smart0.xyz/Article/details/gtjtbreswy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cashguo.top/Article/details/gtjzrpffvq.html

Go:   strconv.Itoa(42)
来源：http://dali.jiagoushi.top/Article/details/gtkjzerpxc.html

Ruby: 42.to_s
来源：http://dali.cheryme.top/Article/details/gtfoftpchy.html

C#:   42.ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsegainuu.html

[A08] 取整与四舍五入
来源：http://dali.iojbl.cn/Article/details/gtbpxccqos.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtkokxquhe.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhongyouzk.top/Article/details/gtpmmnikzu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gtmdztiejo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shuidangran.top/Article/details/gtosuvzjvj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gtjiurmykd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtvlcbxuzb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.birdmap.top/Article/details/gtdcxbcthb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtpbtceuxw.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtoktwsehw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtavqjuacn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtkkdnvigt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gthwmuhlua.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtfzpkntpj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtyshtzfwk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeviygyp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yuanzhike.top/Article/details/gtfwxdeeaz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtmpnlwtvn.html


<!-- 参考信息 -->