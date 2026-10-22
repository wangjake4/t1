代发 wailian999

[U65] PHP：会话
来源：http://dali.zdqjudy.top/Article/details/gtlusxuoxn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtyzydsyzu.html

[U66] PHP：设置 Cookie
来源：http://dali.hnxiangtu.top/Article/details/gtdkiohalz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowcsprsf.html

[U67] PHP：处理文件上传
来源：http://dali.yanxiufei.cn/Article/details/gtnxtdcsbi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhixingplan.top/Article/details/gtztttcyfs.html

[U68] PHP：PDO 连接
来源：http://dali.hywenlv.cn/Article/details/gttleedueg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuxming.cn/Article/details/gtslnzhnyb.html

[U69] PHP：PDO 预处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyaadqwl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nanxuanxn.top/Article/details/gtoouqzmdr.html

[U70] PHP：PDO 事务
来源：http://dali.hongshengwenyu.top/Article/details/gtjgcgruvi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gtxildztrp.html

[U71] PHP：抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtkkqdpnml.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gtniixfqkh.html

[U72] PHP：写错误日志
来源：http://dali.316326.xyz/Article/details/gtpquctmho.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hywenlv.cn/Article/details/gtitbkcgfh.html

[U73] PHP：读取 ini 配置
来源：http://dali.xziqi.cn/Article/details/gthjsmqpfv.html

parse_ini_file("config.ini", true)
来源：http://dali.zdqjudy.top/Article/details/gtyuwuicre.html

[U74] PHP：读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtbhpjmbjj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gtqpsdiqhi.html

[U75] PHP：依赖注入
来源：http://dali.ydzc1.top/Article/details/gtvppedkqi.html

composer require psr/container
来源：http://dali.jinqigfzy.top/Article/details/gtfqgpwxwk.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gtiusvztcu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangshuangyany.cn/Article/details/gtaaoyrqlo.html

[U77] PHP：模板渲染
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwichgtn.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gtbklaapaa.html

[U78] PHP：单元测试
来源：http://dali.fengsongda.top/Article/details/gthjqdhina.html

composer require --dev phpunit/phpunit
来源：http://dali.sxryk.cn/Article/details/gtqxjkcpkt.html

[U79] PHP：静态分析
来源：http://dali.hywenlv.cn/Article/details/gtvxopgqbz.html

composer require --dev phpstan/phpstan
来源：http://dali.yj20258.top/Article/details/gtdhvbhpeu.html

[U80] PHP：代码规范修复
来源：http://dali.sufxvd.cn/Article/details/gtesucuwdj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gtjqjvdkai.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gtzvzzswxz.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gthniyhnpz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gtibywhmmz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.c1oappe.top/Article/details/gtespqluyl.html

[U83] JS：ES Module 导入导出
来源：http://dali.daxiang520.top/Article/details/gtfmkfidap.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gthdczureg.html

[U84] JS：CommonJS 写法
来源：http://dali.cqqwz.cn/Article/details/gtsxhddpbf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhongyouzk.top/Article/details/gtpagpgtpa.html

[U85] JS：可选链
来源：http://dali.quarkkingdee.top/Article/details/gtuqqrcmbl.html

a?.b?.c
来源：http://dali.0kj1m.cn/Article/details/gtgkautjfx.html

[U86] JS：空值合并
来源：http://dali.hywenlv.cn/Article/details/gtvuzqjeay.html

a ?? b
来源：http://dali.316326.xyz/Article/details/gtcyycewaj.html

[U87] JS：解构默认值
来源：http://dali.shuidangran.top/Article/details/gtlqyovwgg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.quarkkingdee.top/Article/details/gtaalewano.html

[U88] JS：对象展开合并
来源：http://dali.zdqjudy.top/Article/details/gttcqgonsw.html

{ ...a, ...b }
来源：http://dali.redwolf501.top/Article/details/gteizyysll.html

[U89] JS：数组去重
来源：http://dali.dashuyun.cn/Article/details/gtxdvxwqof.html

[...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtevazvcka.html

[U90] JS：数字数组排序
来源：http://dali.316326.xyz/Article/details/gtwyyuamqb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtaylvsbwa.html

[U91] JS：对象键值遍历
来源：http://dali.xylfe.cn/Article/details/gthnnfpsvz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gtepwfdynl.html

[U92] JS：深拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyaasmcu.html

structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtsnkercbs.html

[U93] JS：模板字符串
来源：http://dali.aizwys.cn/Article/details/gtlnkitdzq.html

`共 ${n} 条`
来源：http://dali.dianchejie.cn/Article/details/gtaizjkxzk.html

[U94] JS：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gtmhggfbmg.html

const double = x => x * 2;
来源：http://dali.hysaishi.cn/Article/details/gtixrjqpnk.html

[U95] JS：Promise 包装
来源：http://dali.bjfxy.top/Article/details/gtagdnweyv.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgfzy.top/Article/details/gtxqjbmuev.html

[U96] JS：async/await 与异常
来源：http://dali.fzhhl.top/Article/details/gtyexabgci.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtxeurcesc.html

[U97] JS：并发请求
来源：http://dali.dianchejie.cn/Article/details/gtxgnwxlyy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtqvhizxfl.html

[U98] JS：fetch 带 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtvvnnyvvm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cheryme.top/Article/details/gthqgouifp.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvrbbjek.html

el.addEventListener("click", e => {})
来源：http://dali.zhongyouzk.top/Article/details/gtkbcxwzhw.html

[U100] JS：DOM 查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqflsngoa.html

document.querySelector(".item")
来源：http://dali.zdqjudy.top/Article/details/gtqazxgxme.html

[U101] JS：classList 操作
来源：http://dali.zhongyouzk.top/Article/details/gtwwywbqij.html

el.classList.toggle("active")
来源：http://dali.gogol.net.cn/Article/details/gtrehtfwvs.html

[U102] JS：本地存储
来源：http://dali.hongshengwenyu.top/Article/details/gtjzfyydeq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cucudq.cn/Article/details/gtvoivtxya.html

[U103] JS：定时器
来源：http://dali.feifeiyinyue.top/Article/details/gtpovvoxuu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yvedp.cn/Article/details/gtqrvvfnbg.html

[U104] JS：防抖
来源：http://dali.zhixingplan.top/Article/details/gtvpeqqqnj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtexukomrl.html

[U105] JS：节流
来源：http://dali.gaohongyu789.top/Article/details/gtaowppdwq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hfpthk.cn/Article/details/gtkjkacusr.html

[U106] JS：日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtkwdfvejn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hysaishi.cn/Article/details/gtgbvibdat.html

[U107] JS：数字千分位
来源：http://dali.guannengcc.top/Article/details/gtwgeewlnp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj202588.top/Article/details/gtukasnphh.html

[U108] JS：随机整数
来源：http://dali.zdqjudy.top/Article/details/gthgguxwmh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cdnleiting.top/Article/details/gtlwqvbnez.html

[U109] JS：数组分组
来源：http://dali.birdmap.top/Article/details/gtxpovpnmg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtugpavwja.html

[U110] JS：数组分块
来源：http://dali.svipenyu.cn/Article/details/gtpgjxoeai.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ehwqpu.com/Article/details/gtuwquqrrc.html

[U111] JS：对象转 Map
来源：http://dali.jlsjyb.cn/Article/details/gtjyogiwlg.html

new Map(Object.entries(obj))
来源：http://dali.dashuyun.cn/Article/details/gtfqmpbpru.html

[U112] JS：字符串补位
来源：http://dali.nwbrower.top/Article/details/gtqclzsqfk.html

"7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtoursnsle.html

[U113] JS：正则替换全部
来源：http://dali.xinyue.icu/Article/details/gtqfyreqhq.html

s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gthnarxdft.html

[U114] JS：JSON 深比较
来源：http://dali.9152youxi.cn/Article/details/gtemxigcum.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gtauwcfnuk.html

[U115] JS：生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gtthumchgv.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gttcbrsrqw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sweek.top/Article/details/gtqvzkeobo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.meibo888.top/Article/details/gtwrdyalaq.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtbcnobbgb.html

npm i -D vitest;  npx vitest
来源：http://dali.yuanzhike.top/Article/details/gtcdtxitzc.html

[U118] JS：开发服务器
来源：http://dali.xuanzx.com/Article/details/gtsyklalsr.html

npm i -D vite;  npx vite
来源：http://dali.pycfn.com/Article/details/gtbnuxcupw.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbisycwxp.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gtjnvxoxbu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xinyue.icu/Article/details/gtwvborgdk.html

import.meta.env.VITE_API_URL
来源：http://dali.yuanzhike.top/Article/details/gthlnfsibu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfismdote.html

统计汇总
来源：http://dali.yj20258.top/Article/details/gtsyqobarg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnzxyzexq.html

按语言统计（条）：
来源：http://dali.chenjidiqi.icu/Article/details/gtguvxpabr.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gtlsufidbz.html

PHP ............ 252
来源：http://dali.jqgfzy.top/Article/details/gtmbtnjiws.html

JavaScript ..... 252
来源：http://dali.haohaochexian.top/Article/details/gterryxhyp.html

TypeScript ..... 212
来源：http://dali.sufxvd.cn/Article/details/gtgvumgbqj.html

Java ........... 212
来源：http://dali.mhx1999.top/Article/details/gtqtudsmmj.html

Go ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtwkrzhine.html

Ruby ........... 212
来源：http://dali.c1oappe.top/Article/details/gtwznlhobv.html

C# ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gtcizjwyhp.html

C .............. 30
来源：http://dali.shuidangran.top/Article/details/gtwphmexcv.html

C++ ............ 30
来源：http://dali.nwbrower.top/Article/details/gteqohnpgf.html

SQL ............ 90
来源：http://dali.guannengcc.top/Article/details/gtnjzygfuh.html

Bash ........... 80
来源：http://dali.xziqi.cn/Article/details/gtaueyyqmk.html

Kotlin ......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtuxsmfsti.html

Swift .......... 15
来源：http://dali.cucudq.cn/Article/details/gtqmmrftqu.html

Lua ............ 10
来源：http://dali.vqdsnc.cn/Article/details/gtfydbnook.html

Perl ........... 10
来源：http://dali.zhixingplan.top/Article/details/gtnweymclh.html

Scala .......... 10
来源：http://dali.chenlongwang.top/Article/details/gtknpnnodq.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtgkaifklj.html

合计 ........... 2106 条
来源：http://dali.yvedp.cn/Article/details/gtvbjlttew.html

按章节统计：
来源：http://dali.xylfe.cn/Article/details/gttcyxtpxo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.birdmap.top/Article/details/gtmrpperbt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrmzzydq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtpxvzpxck.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gtvjviwdhb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.vqdsnc.cn/Article/details/gtdrmadiuq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gtspujipre.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtyltokjoz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gtosejqcqa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtrehbftfn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zdqjudy.top/Article/details/gtafpsgjxg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtqiothgvz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtvbrqikgg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtaxyywqmo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gtvxceqioi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258888.top/Article/details/gtyicquyle.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gthxfsfggp.html

Q SQL 专题                              90
来源：http://dali.cdnleiting.top/Article/details/gteaftclwd.html

R Bash 专题                             80
来源：http://dali.chenzaomai.com/Article/details/gtsybchjzq.html

S C / C++ 专题                          60
来源：http://dali.chenlongwang.top/Article/details/gtixsbbplt.html

T 其他语言补充                          60
来源：http://dali.zhongyouzk.top/Article/details/gtcitmjxgz.html

U 高频实用片段                         120
来源：http://dali.9152youxi.cn/Article/details/gtfxlfjnma.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtugtaidxp.html

合计                                  2106 条
来源：http://dali.sufxvd.cn/Article/details/gtenudvbcp.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtjjfjbqvf.html

使用提醒
来源：http://dali.ppjwa.cn/Article/details/gtkdshkygg.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtrlgiknmx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj20258888.top/Article/details/gtykjptogi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yuanzhike.top/Article/details/gtgencxjdj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tian-w.cn/Article/details/gtgowvqifz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gtguidembj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhoulong.xyz/Article/details/gtyauyvkha.html

—— 文件结束 ——
来源：http://dali.snrcjt.cn/Article/details/gtdfrwejle.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtftaskche.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jyoumei.cn/Article/details/gtycufoagz.html

Common Programming Examples Cheat Book
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzcrytuf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttoaktmmn.html

【收录内容】
来源：http://dali.cqqwz.cn/Article/details/gtiqwxzxfx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.kuanghao11.cn/Article/details/gtprqrgmpj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shangyingyoupin.top/Article/details/gtxvnqvwse.html

SQL · Bash · C · C++
来源：http://dali.smart0.xyz/Article/details/gtayvxqubs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zycfv.cn/Article/details/gtvxwdzqqr.html

【使用说明】
来源：http://dali.haohaochexian.top/Article/details/gttitrxjgm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnqzz.top/Article/details/gttgnbugcs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gzhubu.top/Article/details/gtamuogtgg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.tian-w.cn/Article/details/gtjfpwpzki.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cucudq.cn/Article/details/gtarcomhbv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnqzz.top/Article/details/gtdegxsobd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gaohongyu789.top/Article/details/gtucqbophr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xziqi.cn/Article/details/gtyqgdidie.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xziqi.cn/Article/details/gtxtjlejny.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shuidangran.top/Article/details/gtlbvekvaz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cqqwz.cn/Article/details/gtazgahsrz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aizwys.cn/Article/details/gtrgnlgvks.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ybcxt.top/Article/details/gtfwdgccgy.html

【文件统计】
来源：http://dali.daria6918.cn/Article/details/gtzldjolqu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zdqjudy.top/Article/details/gtiuuusvtm.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gteleeygnu.html

目  录
来源：http://dali.yangfankeji.com/Article/details/gtbqjxvgsb.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtahtrqpoq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sxryk.cn/Article/details/gtrodaqnxq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtwevpltsv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtjyvkigpz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.iojbl.cn/Article/details/gtaxpddeds.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jqgufenzy.top/Article/details/gtjsyxttyx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nwbrower.top/Article/details/gtbkifnhmq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gtmkokflml.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cqqwz.cn/Article/details/gthrtvtomw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gtcideflcj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gtvydxljfy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtoavkbkkz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtxdgojzft.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtucegvtmy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gtpnintnck.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.9152youxi.cn/Article/details/gtjrsztiwa.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtoylcfkii.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cucudq.cn/Article/details/gtjpijeuqz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtngvdgyqb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.dashuyun.cn/Article/details/gttrkyzqdw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtlrtfgxtt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gthpoeozal.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpthmftjw.html

A. 基础语法与类型
来源：http://dali.chenzaomai.com/Article/details/gtjgsnwkak.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtlhzgfavt.html

[A01] Hello World
来源：http://dali.guannengcc.top/Article/details/gtbjhndkil.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gtxzuxnfdz.html

PHP:  echo "Hello, World!";
来源：http://dali.hnqzz.top/Article/details/gtjxwejqwt.html

JS:   console.log("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtxrkjutca.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nanxuanxn.top/Article/details/gtnxjtdovq.html

Java: System.out.println("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gtozcyjrxy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gtivyzgdit.html

Ruby: puts "Hello, World!"
来源：http://dali.tanke756.top/Article/details/gtcizdvdrb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gtaqdsemrt.html

[A02] 变量声明与赋值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosrogjpp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.smart0.xyz/Article/details/gtbpexfveb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtfuwbckwg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shuidangran.top/Article/details/gttftpxozk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nanxinkj.top/Article/details/gttwigqgkg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtqtxjtfgy.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenjidiqi.icu/Article/details/gtvgtbvubc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hywenlv.cn/Article/details/gtmertnuzn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenlongwang.top/Article/details/gtzxypftca.html

[A03] 常量定义
来源：http://dali.fzhhl.top/Article/details/gtjznnammt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.iojbl.cn/Article/details/gtyydgtydi.html

PHP:  const PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gthsynwcyn.html

JS:   const PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtgakzoims.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtlddmqlce.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtsgkbkdst.html

Go:   const PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtkoubnxme.html

Ruby: PI = 3.14159
来源：http://dali.tian-w.cn/Article/details/gtrcndkffi.html

C#:   const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtkatpmwel.html

[A04] 判断变量类型
来源：http://dali.sweek.top/Article/details/gtiuszsyuu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenlongwang.top/Article/details/gtkqetrzqr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.0kj1m.cn/Article/details/gthcmyoxne.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gttwfuyzuk.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gtisbntwkj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhiwuduotai.top/Article/details/gtunkdazpq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cqqwz.cn/Article/details/gtedicednx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.9152youxi.cn/Article/details/gttugtxznt.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenzaomai.com/Article/details/gtjbhndmpu.html

[A05] 整数除法与取模
来源：http://dali.cqqwz.cn/Article/details/gtrauyyspd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhongyouzk.top/Article/details/gtpgffmyrn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtujhebkpq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gttzucvxel.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gteijezqzj.html

Java: 7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtiwicqoxr.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgruzsazl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtwlmyexsm.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdurguas.html

[A06] 字符串转数字
来源：http://dali.sweek.top/Article/details/gtfycejhou.html

Py:   int("42"); float("3.14")
来源：http://dali.cqqwz.cn/Article/details/gtijchwytm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cashguo.top/Article/details/gtsralnvin.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hammf.cn/Article/details/gtjbkhrnsd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xinyue.icu/Article/details/gtqcfcwmap.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258.top/Article/details/gtswwqupow.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gtzzjcbdwd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gtikqegjfw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtvghdjlcp.html

[A07] 数字转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtutqzkqqv.html

Py:   str(42)
来源：http://dali.xylfe.cn/Article/details/gtmqiwamna.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhoulong.xyz/Article/details/gtrterysro.html

JS:   String(42); (42).toString()
来源：http://dali.bjfxy.top/Article/details/gtwpkmxsnp.html

TS:   String(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhrfbvox.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhixingplan.top/Article/details/gtsnhxgtoc.html

Go:   strconv.Itoa(42)
来源：http://dali.ppjwa.cn/Article/details/gtwpezzduv.html

Ruby: 42.to_s
来源：http://dali.dianchejie.cn/Article/details/gtumgbharn.html

C#:   42.ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtcpcaxdck.html

[A08] 取整与四舍五入
来源：http://dali.jinqigufen.top/Article/details/gtugdhnnvx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gtolpbsugo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hywenlv.cn/Article/details/gtlqunsute.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtonqhzszc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangshuangyany.cn/Article/details/gttpvgnzld.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtpuqvgtki.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxghrojbs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.smart0.xyz/Article/details/gtmufymapy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtsczntzhd.html

[A09] 绝对值与最大最小值
来源：http://dali.shuidangran.top/Article/details/gthkxjymkz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyxwhglu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtltnegsob.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtxssvtaek.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtppzpbmnz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtntuuqwic.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dianchejie.cn/Article/details/gtpgpeejuo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yonumen.top/Article/details/gtfdutnoea.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gthhezbjtp.html


<!-- 参考信息 -->