代发 wailian999

[U61] PHP：正则
来源：http://dali.hammf.cn/Article/details/gtogaiemws.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtvukevsyx.html

[U62] PHP：日期对象
来源：http://dali.yj202588.top/Article/details/gtvmgvexzd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenlongwang.top/Article/details/gttrdgzywa.html

[U63] PHP：文件读写
来源：http://dali.hysaishi.cn/Article/details/gtmocwelxg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwsyzvah.html

[U64] PHP：目录遍历
来源：http://dali.gogol.net.cn/Article/details/gttsgvyrht.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aibaodan.cn/Article/details/gtjwxmupeh.html

[U65] PHP：会话
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaqytkcw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtdmklscjk.html

[U66] PHP：设置 Cookie
来源：http://dali.svipenyu.cn/Article/details/gtrpcxtkmo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daxiang520.top/Article/details/gtnfgguzns.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gtynlpcnyt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.feifeiyinyue.top/Article/details/gtnzlkrvtp.html

[U68] PHP：PDO 连接
来源：http://dali.hongshengwenyu.top/Article/details/gtxqzfyuua.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenjidiqi.icu/Article/details/gtwzvtztbs.html

[U69] PHP：PDO 预处理
来源：http://dali.fengsongda.top/Article/details/gtpyamoans.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shuidangran.top/Article/details/gtndctdecz.html

[U70] PHP：PDO 事务
来源：http://dali.zhongyouzk.top/Article/details/gtphanoftj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gtqbhyjfad.html

[U71] PHP：抛出异常
来源：http://dali.ydzc1.top/Article/details/gtypdizrdh.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtrnwenlwa.html

[U72] PHP：写错误日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgvvjmxn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nanxinkj.top/Article/details/gtmzybszzr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zdqjudy.top/Article/details/gttbhcjqvz.html

parse_ini_file("config.ini", true)
来源：http://dali.ivvv.top/Article/details/gthhbspide.html

[U74] PHP：读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtwzrrqzzy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuxming.cn/Article/details/gtoneuldxd.html

[U75] PHP：依赖注入
来源：http://dali.xziqi.cn/Article/details/gttztpgltb.html

composer require psr/container
来源：http://dali.9152youxi.cn/Article/details/gttsntxmen.html

[U76] PHP：简单路由
来源：http://dali.jqgfzy.top/Article/details/gtkyqslemu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sysykeji.top/Article/details/gtbxgdzpcz.html

[U77] PHP：模板渲染
来源：http://dali.daxiang520.top/Article/details/gtbjqehqmj.html

composer require twig/twig
来源：http://dali.guowangkeji.top/Article/details/gtllyoupjg.html

[U78] PHP：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtfrvhypvu.html

composer require --dev phpunit/phpunit
来源：http://dali.redwolf501.top/Article/details/gtemmlolqs.html

[U79] PHP：静态分析
来源：http://dali.gaohongyu789.top/Article/details/gtishimyvc.html

composer require --dev phpstan/phpstan
来源：http://dali.cucudq.cn/Article/details/gtdgawfnyh.html

[U80] PHP：代码规范修复
来源：http://dali.vqdsnc.cn/Article/details/gtvfslosaw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigfzy.top/Article/details/gttekqxgik.html

[U81] JS：初始化项目
来源：http://dali.redwolf501.top/Article/details/gtioimcpob.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gtomrfrfke.html

[U82] JS：package.json 脚本
来源：http://dali.sysykeji.top/Article/details/gtwfgojuug.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.vqdsnc.cn/Article/details/gtklhfqkue.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gttztcbuxo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cheryme.top/Article/details/gtgvxvhpxh.html

[U84] JS：CommonJS 写法
来源：http://dali.xuanzx.com/Article/details/gtoxievxek.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yanxiufei.cn/Article/details/gtrfhqdzum.html

[U85] JS：可选链
来源：http://dali.tian-w.cn/Article/details/gtbpavjtox.html

a?.b?.c
来源：http://dali.andypj.xyz/Article/details/gtmqbjihwn.html

[U86] JS：空值合并
来源：http://dali.yonumen.top/Article/details/gtxfocmbkr.html

a ?? b
来源：http://dali.iojbl.cn/Article/details/gtcablcrti.html

[U87] JS：解构默认值
来源：http://dali.fzhhl.top/Article/details/gtlopuavbl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gaohongyu789.top/Article/details/gtkgiguxtu.html

[U88] JS：对象展开合并
来源：http://dali.cdnleiting.top/Article/details/gtrrucxolp.html

{ ...a, ...b }
来源：http://dali.0kj1m.cn/Article/details/gtrxeqaoxy.html

[U89] JS：数组去重
来源：http://dali.hysaishi.cn/Article/details/gtgjqhksqx.html

[...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtzcftwhjs.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtmthlogcb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtedeweanf.html

[U91] JS：对象键值遍历
来源：http://dali.xylfe.cn/Article/details/gtreysnmyn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgufenzy.top/Article/details/gtseytnyyd.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gthasrpeor.html

structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtbilqljyp.html

[U93] JS：模板字符串
来源：http://dali.sxryk.cn/Article/details/gtvxslgbso.html

`共 ${n} 条`
来源：http://dali.birdmap.top/Article/details/gtvnqetcud.html

[U94] JS：箭头函数
来源：http://dali.tian-w.cn/Article/details/gtyrmsxowq.html

const double = x => x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtfgwrakwy.html

[U95] JS：Promise 包装
来源：http://dali.havefunace.top/Article/details/gtnwdcslsf.html

new Promise((resolve, reject) => {})
来源：http://dali.smart0.xyz/Article/details/gtqbuxbgsr.html

[U96] JS：async/await 与异常
来源：http://dali.jiagoushi.top/Article/details/gtlgazevbd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtcgkuwayu.html

[U97] JS：并发请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuwkdhzd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtadgmhcjf.html

[U98] JS：fetch 带 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtrmxtdjkw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jiagoushi.top/Article/details/gtqvmgirjn.html

[U99] JS：事件监听
来源：http://dali.wangshuangyany.cn/Article/details/gtfyjsmdir.html

el.addEventListener("click", e => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxvqtlwk.html

[U100] JS：DOM 查询
来源：http://dali.tian-w.cn/Article/details/gtgibjndrm.html

document.querySelector(".item")
来源：http://dali.tian-w.cn/Article/details/gtpgwpohbx.html

[U101] JS：classList 操作
来源：http://dali.hfpthk.cn/Article/details/gtixqvlbtd.html

el.classList.toggle("active")
来源：http://dali.shuidangran.top/Article/details/gtotlaotwg.html

[U102] JS：本地存储
来源：http://dali.birdmap.top/Article/details/gtbvzbagdy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ybcxt.top/Article/details/gttmibfzyv.html

[U103] JS：定时器
来源：http://dali.cdnleiting.top/Article/details/gteezoxlgi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgfzy.top/Article/details/gttqojgiuc.html

[U104] JS：防抖
来源：http://dali.guowangkeji.top/Article/details/gttpjgkyko.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtdhwpamsk.html

[U105] JS：节流
来源：http://dali.jinqigfzy.top/Article/details/gtarkhirfo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtfqjtcisf.html

[U106] JS：日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtfpyupmjw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuanzhike.top/Article/details/gttgfcjvmu.html

[U107] JS：数字千分位
来源：http://dali.xuanzx.com/Article/details/gtsuoebzrz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtdywwvjjg.html

[U108] JS：随机整数
来源：http://dali.jinqigufen.top/Article/details/gthqcdjloa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.andypj.xyz/Article/details/gtsrmibasp.html

[U109] JS：数组分组
来源：http://dali.hammf.cn/Article/details/gtwiiljcci.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtrwdbolgx.html

[U110] JS：数组分块
来源：http://dali.xylfe.cn/Article/details/gtpplbzzse.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ehwqpu.com/Article/details/gtkzcgfith.html

[U111] JS：对象转 Map
来源：http://dali.zhengqikj.top/Article/details/gtrevjsoib.html

new Map(Object.entries(obj))
来源：http://dali.ivvv.top/Article/details/gtwlgdugwl.html

[U112] JS：字符串补位
来源：http://dali.redwolf501.top/Article/details/gtlsliivbd.html

"7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtkjvikohz.html

[U113] JS：正则替换全部
来源：http://dali.pycfn.com/Article/details/gtepkwequh.html

s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtmurzewgu.html

[U114] JS：JSON 深比较
来源：http://dali.wangdashe.top/Article/details/gturfwxggv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtfxmzzwlr.html

[U115] JS：生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtzbycrqla.html

crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtvdkqhemg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gtklqeqdcp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shzxlz.cn/Article/details/gtzpslyjnm.html

[U117] JS：单元测试
来源：http://dali.ybcxt.top/Article/details/gtbieebjqn.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258888.top/Article/details/gtxnsfxtze.html

[U118] JS：开发服务器
来源：http://dali.snrcjt.cn/Article/details/gtcqlyeqxd.html

npm i -D vite;  npx vite
来源：http://dali.redwolf501.top/Article/details/gtnzdfybye.html

[U119] JS：生产构建
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovzfqhtu.html

npx vite build
来源：http://dali.0kj1m.cn/Article/details/gtigddhvsz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daria6918.cn/Article/details/gtdjrnyyis.html

import.meta.env.VITE_API_URL
来源：http://dali.mhx1999.top/Article/details/gtvbcoysmq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtuursiwem.html

统计汇总
来源：http://dali.wangshuangyany.cn/Article/details/gtvlngmcvr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwptudvod.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gtrfaveiuc.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gtbdbexbkf.html

PHP ............ 252
来源：http://dali.guannengcc.top/Article/details/gtufubkhrp.html

JavaScript ..... 252
来源：http://dali.316326.xyz/Article/details/gtqjlquexh.html

TypeScript ..... 212
来源：http://dali.havefunace.top/Article/details/gtrhxnxvup.html

Java ........... 212
来源：http://dali.yonumen.top/Article/details/gtqytiuidw.html

Go ............. 212
来源：http://dali.sysykeji.top/Article/details/gtgtaisvlx.html

Ruby ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtmjlqmdoi.html

C# ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtgjphxiht.html

C .............. 30
来源：http://dali.zhoulong.xyz/Article/details/gtecslqgtx.html

C++ ............ 30
来源：http://dali.smart0.xyz/Article/details/gtipvdzfgy.html

SQL ............ 90
来源：http://dali.316326.xyz/Article/details/gtkzdinajg.html

Bash ........... 80
来源：http://dali.birdmap.top/Article/details/gtuwbwtwta.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gtnuiayvyy.html

Swift .......... 15
来源：http://dali.jinqigufen.top/Article/details/gtvfdnzcrl.html

Lua ............ 10
来源：http://dali.shuidangran.top/Article/details/gtillieibv.html

Perl ........... 10
来源：http://dali.xinyue.icu/Article/details/gtmlrqshag.html

Scala .......... 10
来源：http://dali.tianlin.xyz/Article/details/gtnpsnpbhk.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtvpuuvoum.html

合计 ........... 2106 条
来源：http://dali.tanke756.top/Article/details/gtvcnqtvqj.html

按章节统计：
来源：http://dali.jinghuilouyu.cn/Article/details/gteqbpyyrw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gtovuqgruv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtxrknbhni.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gtmqkuutfb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtbyawmahk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yuanzhike.top/Article/details/gtooovzstm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.meibo888.top/Article/details/gtxvmmbqaw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gtujdttuxr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.316326.xyz/Article/details/gtecwgndvh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtsbaqlksj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gtdqhdowix.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtpsdtkhrg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtosdzjolp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtciythuth.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtheqbrcus.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolsfjtza.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtqyqiwuti.html

Q SQL 专题                              90
来源：http://dali.cashguo.top/Article/details/gtkltbmjgk.html

R Bash 专题                             80
来源：http://dali.jianghu66.top/Article/details/gttshphsws.html

S C / C++ 专题                          60
来源：http://dali.cdnleiting.top/Article/details/gtepvhztne.html

T 其他语言补充                          60
来源：http://dali.sxryk.cn/Article/details/gtosnmnbbc.html

U 高频实用片段                         120
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhialzks.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtjsjbhayr.html

合计                                  2106 条
来源：http://dali.xinyue.icu/Article/details/gtdlcjozss.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtgzhioxrw.html

使用提醒
来源：http://dali.aibaodan.cn/Article/details/gtydthxhgm.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtoszkecqd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ybcxt.top/Article/details/gtlctrglgo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.redwolf501.top/Article/details/gtbdzxytru.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnxiangtu.top/Article/details/gtgqypsfzo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxuanxn.top/Article/details/gttzrazyfs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hammf.cn/Article/details/gtekmpqpax.html

—— 文件结束 ——
来源：http://dali.daria6918.cn/Article/details/gttrbnmcdn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtchkhdzfy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aibaodan.cn/Article/details/gtcyuvakiu.html

Common Programming Examples Cheat Book
来源：http://dali.daria6918.cn/Article/details/gtomcakagy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttrdzbjgl.html

【收录内容】
来源：http://dali.gzhubu.top/Article/details/gtrzudpxad.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhixingplan.top/Article/details/gttealvdqq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuanzhike.top/Article/details/gtzastrlha.html

SQL · Bash · C · C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuakopey.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gtsvryqrvo.html

【使用说明】
来源：http://dali.yangfankeji.com/Article/details/gtjtikfhqt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenjidiqi.icu/Article/details/gtydjfwhqw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cheryme.top/Article/details/gtvodvpafy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aizwys.cn/Article/details/gtwsetiiwa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cdnleiting.top/Article/details/gtwnczlley.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dianchejie.cn/Article/details/gtwgxywtql.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ivvv.top/Article/details/gtazfjhvsy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cqqwz.cn/Article/details/gtuaqpsmon.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gotoacloud.top/Article/details/gtsdftehcq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinqigfzy.top/Article/details/gtosboijnm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yueranfly.top/Article/details/gtqrdravep.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sxryk.cn/Article/details/gtxkhzuxfk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jianghu66.top/Article/details/gtqlqgfgwy.html

【文件统计】
来源：http://dali.yangfankeji.com/Article/details/gtdipjdfyt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.andypj.xyz/Article/details/gtpvuermyx.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtijgbucws.html

目  录
来源：http://dali.snrcjt.cn/Article/details/gtsuyzzrjj.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtfsdfvsll.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtizflvssd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtjncjzexv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gtekzkkdvd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shzxlz.cn/Article/details/gtcppgmfwg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.snrcjt.cn/Article/details/gtdcgsrmof.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gtzeupnecm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtxfxnthxa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gtzvgcixey.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtstacjcoo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtakmojdwf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gtgfwzxqtm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtdnnrlfke.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtddxkepzq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtdvvmjcyp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xylfe.cn/Article/details/gtaoahzife.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtaqmmoaib.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.quarkkingdee.top/Article/details/gtlpwsuxzd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtgstgfqsz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ybcxt.top/Article/details/gtbwcgvzqh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncuvsrbl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gtlhaftmbp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpvcfzwcd.html

A. 基础语法与类型
来源：http://dali.hongshengwenyu.top/Article/details/gtjxrxdntz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwziqvtbt.html

[A01] Hello World
来源：http://dali.chenzaomai.com/Article/details/gtrhcjnfez.html

Py:   print("Hello, World!")
来源：http://dali.chenlongwang.top/Article/details/gtxxgglvyj.html

PHP:  echo "Hello, World!";
来源：http://dali.cucudq.cn/Article/details/gtkzhbfzms.html

JS:   console.log("Hello, World!");
来源：http://dali.zhixingplan.top/Article/details/gtqlbmmsjc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.redwolf501.top/Article/details/gtsrofedah.html

Java: System.out.println("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gtyhquvtat.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zdqjudy.top/Article/details/gtyvnxzjen.html

Ruby: puts "Hello, World!"
来源：http://dali.jianghu66.top/Article/details/gtdyosyjmg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gotoacloud.top/Article/details/gtapwjzjjr.html

[A02] 变量声明与赋值
来源：http://dali.chenjidiqi.icu/Article/details/gtsoluekib.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.smart0.xyz/Article/details/gtdnspvwsq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtnmpqkdfa.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shuidangran.top/Article/details/gtoswknjal.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hammf.cn/Article/details/gtmrsgoicj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gtxaysurew.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgdovyou.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ppjwa.cn/Article/details/gtflenxuhn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtrlptjjnx.html

[A03] 常量定义
来源：http://dali.guowangkeji.top/Article/details/gtjpwvossq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hongshengwenyu.top/Article/details/gtgvntcsij.html

PHP:  const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtaxizqwzl.html

JS:   const PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtwtgqgved.html

TS:   const PI: number = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtismhpbyc.html

Java: static final double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtabzuccsj.html

Go:   const PI = 3.14159
来源：http://dali.aibaodan.cn/Article/details/gtfgmygowg.html

Ruby: PI = 3.14159
来源：http://dali.andypj.xyz/Article/details/gtrcustxya.html

C#:   const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtkmxiohxh.html

[A04] 判断变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtijdsnyeg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.svipenyu.cn/Article/details/gtftgbjlpp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shangyingyoupin.top/Article/details/gtboumllcg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jiagoushi.top/Article/details/gtplribgks.html

TS:   typeof x; x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gttezdeqxc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.redwolf501.top/Article/details/gtkwbwtigc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenlongwang.top/Article/details/gtncaxawav.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.aibaodan.cn/Article/details/gtixhnzosv.html

C#:   x.GetType().Name; x is int
来源：http://dali.pengpengdd.cyou/Article/details/gtdpvhuniq.html

[A05] 整数除法与取模
来源：http://dali.cashguo.top/Article/details/gtdyxztqxu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhongyouzk.top/Article/details/gtpsghxlyn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtvnfpcxpu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtypyzcqtw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwsnocjt.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtweoohbzl.html

Go:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtillpqxtl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtpszcepyo.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbwgryhm.html

[A06] 字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtnpnolfet.html

Py:   int("42"); float("3.14")
来源：http://dali.ivvv.top/Article/details/gtiekfneiu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnxiangtu.top/Article/details/gtwlgpttis.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinqigfzy.top/Article/details/gtqwhvznyk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.guannengcc.top/Article/details/gtysrkbfof.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtelnfnfwa.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.c1oappe.top/Article/details/gtcpxalnrz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cheryme.top/Article/details/gtzpxwooon.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.iojbl.cn/Article/details/gtbwrwihli.html

[A07] 数字转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtmmiqtiad.html

Py:   str(42)
来源：http://dali.xziqi.cn/Article/details/gtcnxrwqzc.html

PHP:  (string) 42; strval(42)
来源：http://dali.ydzc1.top/Article/details/gtogulifjc.html

JS:   String(42); (42).toString()
来源：http://dali.haohaochexian.top/Article/details/gtimxiuwrf.html

TS:   String(42)
来源：http://dali.guannengcc.top/Article/details/gtdttktavr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sysykeji.top/Article/details/gtwphjpjht.html

Go:   strconv.Itoa(42)
来源：http://dali.quarkkingdee.top/Article/details/gtthduceug.html

Ruby: 42.to_s
来源：http://dali.zdqjudy.top/Article/details/gtvtupxuvy.html

C#:   42.ToString()
来源：http://dali.aibaodan.cn/Article/details/gtebkprrix.html

[A08] 取整与四舍五入
来源：http://dali.dianchejie.cn/Article/details/gtrsqnstma.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtaudosdsf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cucudq.cn/Article/details/gtxjrynzxy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gtolkorllf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.daria6918.cn/Article/details/gtsjvymqaf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtmrslxyho.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtqfpuhldb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.smart0.xyz/Article/details/gttzwapjzr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gteiklkpem.html

[A09] 绝对值与最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuohahjj.html


<!-- 参考信息 -->