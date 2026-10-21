代发 wailian999

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gtbkiqbczy.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gtofdrfozw.html

[U52] PHP：箭头函数
来源：http://dali.zdqjudy.top/Article/details/gtwomvjjsq.html

$double = fn($x) => $x * 2;
来源：http://dali.yvedp.cn/Article/details/gtyvnmqzkv.html

[U53] PHP：空合并运算符
来源：http://dali.xziqi.cn/Article/details/gtzpvzblse.html

$v = $a ?? $b ?? "default";
来源：http://dali.snrcjt.cn/Article/details/gtltvmteur.html

[U54] PHP：空安全调用
来源：http://dali.andypj.xyz/Article/details/gtwhdkpcuy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gtmiayxokg.html

[U55] PHP：match 表达式
来源：http://dali.redwolf501.top/Article/details/gtunkscwmx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gthptgapzn.html

[U56] PHP：命名参数
来源：http://dali.tianlin.xyz/Article/details/gtqtqmrsio.html

f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtntwjhplv.html

[U57] PHP：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtzlpeymod.html

"值: {$a}"
来源：http://dali.mhx1999.top/Article/details/gtqywuqszf.html

[U58] PHP：数组三件套
来源：http://dali.guowangkeji.top/Article/details/gtzlwgwfsz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.0kj1m.cn/Article/details/gtueexrpex.html

[U59] PHP：自定义排序
来源：http://dali.hfpthk.cn/Article/details/gtogpxldsb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtyqhgofoz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gthlmcdccp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cqqwz.cn/Article/details/gtpvisdqgk.html

[U61] PHP：正则
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgfxvgqs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtvafhkyax.html

[U62] PHP：日期对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhdkjlwa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgfzy.top/Article/details/gtltwgmutv.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoskvsszv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangtech.top/Article/details/gtujuvsrdc.html

[U64] PHP：目录遍历
来源：http://dali.yj202588.top/Article/details/gtnkkulqhb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxuanxn.top/Article/details/gtmlkpjhts.html

[U65] PHP：会话
来源：http://dali.daxiang520.top/Article/details/gtqdikuioh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtjxqabuvy.html

[U66] PHP：设置 Cookie
来源：http://dali.gogol.net.cn/Article/details/gthmjhfhdy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.0kj1m.cn/Article/details/gtanertihy.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gtkddyiwzb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinghuilouyu.cn/Article/details/gtboechqur.html

[U68] PHP：PDO 连接
来源：http://dali.feifeiyinyue.top/Article/details/gtrgqbdsgh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pycfn.com/Article/details/gtnmowvgvo.html

[U69] PHP：PDO 预处理
来源：http://dali.0kj1m.cn/Article/details/gttmqohrey.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gtlsyqvvbl.html

[U70] PHP：PDO 事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqmprpsu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yueranfly.top/Article/details/gthgxuzpte.html

[U71] PHP：抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gtfwsnsncj.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gtzryklgkh.html

[U72] PHP：写错误日志
来源：http://dali.zycfv.cn/Article/details/gtouyknpnx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yonumen.top/Article/details/gtabqsafvw.html

[U73] PHP：读取 ini 配置
来源：http://dali.nwbrower.top/Article/details/gtwrbegryk.html

parse_ini_file("config.ini", true)
来源：http://dali.yonumen.top/Article/details/gthnhrexyb.html

[U74] PHP：读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtllhpbzbn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhengqikj.top/Article/details/gtvractvmj.html

[U75] PHP：依赖注入
来源：http://dali.jiagoushi.top/Article/details/gtyjpvkjpc.html

composer require psr/container
来源：http://dali.haohaochexian.top/Article/details/gtrzzynwye.html

[U76] PHP：简单路由
来源：http://dali.gotoacloud.top/Article/details/gtnomqhanz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj202588.top/Article/details/gtxhaeeicr.html

[U77] PHP：模板渲染
来源：http://dali.chenlongwang.top/Article/details/gtkmvgdkwj.html

composer require twig/twig
来源：http://dali.daxiang520.top/Article/details/gtjcydupna.html

[U78] PHP：单元测试
来源：http://dali.jinqigufen.top/Article/details/gtfczrlxgg.html

composer require --dev phpunit/phpunit
来源：http://dali.guannengcc.top/Article/details/gtgcesaqwf.html

[U79] PHP：静态分析
来源：http://dali.jiagoushi.top/Article/details/gtcbyplbnx.html

composer require --dev phpstan/phpstan
来源：http://dali.hnxiangtu.top/Article/details/gtggsamcrf.html

[U80] PHP：代码规范修复
来源：http://dali.pycfn.com/Article/details/gtekwxykad.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gtndcmwkfz.html

[U81] JS：初始化项目
来源：http://dali.yonumen.top/Article/details/gtfmgdsqax.html

npm init -y;  npm i express
来源：http://dali.aizwys.cn/Article/details/gtcbmpsdxo.html

[U82] JS：package.json 脚本
来源：http://dali.jyoumei.cn/Article/details/gtlobtlura.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.kuanghao11.cn/Article/details/gtvopywdhd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gtfsxbfqme.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtwjcmxjdo.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gtpqhmrgxe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cheryme.top/Article/details/gtyzdwonnk.html

[U85] JS：可选链
来源：http://dali.wangshuangyany.cn/Article/details/gtikgfvngw.html

a?.b?.c
来源：http://dali.daria6918.cn/Article/details/gtvavjeyys.html

[U86] JS：空值合并
来源：http://dali.daxiang520.top/Article/details/gtnezuxtfj.html

a ?? b
来源：http://dali.zdqjudy.top/Article/details/gtmrpqxrqd.html

[U87] JS：解构默认值
来源：http://dali.hfpthk.cn/Article/details/gtqvpiokwq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinghuilouyu.cn/Article/details/gtekmljghe.html

[U88] JS：对象展开合并
来源：http://dali.dashuyun.cn/Article/details/gtotutflvk.html

{ ...a, ...b }
来源：http://dali.gaohongyu789.top/Article/details/gtzgjlgbyx.html

[U89] JS：数组去重
来源：http://dali.yuanzhike.top/Article/details/gtgcfwpgki.html

[...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtglvnvodw.html

[U90] JS：数字数组排序
来源：http://dali.dianchejie.cn/Article/details/gtzxcwzgkw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtvbtlfakt.html

[U91] JS：对象键值遍历
来源：http://dali.pycfn.com/Article/details/gtdarcqhqm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.c1oappe.top/Article/details/gtcfdliufs.html

[U92] JS：深拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtmizmcokt.html

structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdpfcqzg.html

[U93] JS：模板字符串
来源：http://dali.sxryk.cn/Article/details/gtyeiszitu.html

`共 ${n} 条`
来源：http://dali.hammf.cn/Article/details/gtykqghgkw.html

[U94] JS：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvnozwju.html

const double = x => x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtqotlbtwk.html

[U95] JS：Promise 包装
来源：http://dali.dashuyun.cn/Article/details/gtfcdtmfvn.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gtoainzvtg.html

[U96] JS：async/await 与异常
来源：http://dali.hfpthk.cn/Article/details/gtimdgsyes.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtyyxjdlwx.html

[U97] JS：并发请求
来源：http://dali.0kj1m.cn/Article/details/gtshcchvwc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcjnpyly.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtaynehqiu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258.top/Article/details/gtgzhehcxn.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangtech.top/Article/details/gtgeouhxmt.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258888.top/Article/details/gtrzmyejia.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gtqoveyqcs.html

document.querySelector(".item")
来源：http://dali.gogol.net.cn/Article/details/gtzrdydiqs.html

[U101] JS：classList 操作
来源：http://dali.zhoulong.xyz/Article/details/gtebueedaz.html

el.classList.toggle("active")
来源：http://dali.tianlin.xyz/Article/details/gtjokxbivq.html

[U102] JS：本地存储
来源：http://dali.yvedp.cn/Article/details/gtivjzthaf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tanke756.top/Article/details/gtfckpsgra.html

[U103] JS：定时器
来源：http://dali.zhoulong.xyz/Article/details/gtzbvluhzv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.svipenyu.cn/Article/details/gtkpmgglen.html

[U104] JS：防抖
来源：http://dali.tian-w.cn/Article/details/gtjgazzkhz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtmreplrcx.html

[U105] JS：节流
来源：http://dali.ehwqpu.com/Article/details/gtdvajxwlt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlutqupjk.html

[U106] JS：日期格式化
来源：http://dali.ydzc1.top/Article/details/gtlozjwwvx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aibaodan.cn/Article/details/gtryqulkec.html

[U107] JS：数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtfqzfrkvj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tanke756.top/Article/details/gtzrrhkwal.html

[U108] JS：随机整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtueftared.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dashuyun.cn/Article/details/gtofxsfuql.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gtyhokyamz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtgxtzoeuz.html

[U110] JS：数组分块
来源：http://dali.andypj.xyz/Article/details/gtiavgmawf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.dashuyun.cn/Article/details/gtzcjagkks.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gtpumfdobx.html

new Map(Object.entries(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtostgagpx.html

[U112] JS：字符串补位
来源：http://dali.0kj1m.cn/Article/details/gtcelcnxnx.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtutalambg.html

[U113] JS：正则替换全部
来源：http://dali.ybcxt.top/Article/details/gtykloodws.html

s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtmwavyrcx.html

[U114] JS：JSON 深比较
来源：http://dali.shzxlz.cn/Article/details/gtmcwjkrgh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtmhklxuka.html

[U115] JS：生成 UUID
来源：http://dali.havefunace.top/Article/details/gtrfikdzov.html

crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtacdfwtdp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ivvv.top/Article/details/gtfwsftckl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tanke756.top/Article/details/gtqwgkhixv.html

[U117] JS：单元测试
来源：http://dali.ivvv.top/Article/details/gtzwcomnjv.html

npm i -D vitest;  npx vitest
来源：http://dali.cashguo.top/Article/details/gtkniyrsaw.html

[U118] JS：开发服务器
来源：http://dali.yuxming.cn/Article/details/gtmkofhyod.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gtbfglurxy.html

[U119] JS：生产构建
来源：http://dali.mhx1999.top/Article/details/gtjczgmlxp.html

npx vite build
来源：http://dali.shzxlz.cn/Article/details/gtwajmshsv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tian-w.cn/Article/details/gthvzpzves.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258888.top/Article/details/gtmsdnloyb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfhcdleig.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gtwszotqqv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwcyeavnw.html

按语言统计（条）：
来源：http://dali.tian-w.cn/Article/details/gtafgsagmx.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gtrnopxbgn.html

PHP ............ 252
来源：http://dali.ybcxt.top/Article/details/gtxxmokqlw.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gttghjsyen.html

TypeScript ..... 212
来源：http://dali.xinyue.icu/Article/details/gtxtyyfrcd.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gtienwbwky.html

Go ............. 212
来源：http://dali.jqgfzy.top/Article/details/gtnwyoldii.html

Ruby ........... 212
来源：http://dali.cheryme.top/Article/details/gtxfnpyiqu.html

C# ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtajuawjpy.html

C .............. 30
来源：http://dali.chenjidiqi.icu/Article/details/gtbesfnqge.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gtozrdwmor.html

SQL ............ 90
来源：http://dali.mhx1999.top/Article/details/gtvpapsuyi.html

Bash ........... 80
来源：http://dali.sxryk.cn/Article/details/gtcaqaknkw.html

Kotlin ......... 15
来源：http://dali.kuanghao11.cn/Article/details/gtuihpmdft.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gthkiktwsa.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gthmbmialm.html

Perl ........... 10
来源：http://dali.gogol.net.cn/Article/details/gtjagspfbo.html

Scala .......... 10
来源：http://dali.havefunace.top/Article/details/gteqtmcpfm.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gthnxrkyqf.html

合计 ........... 2106 条
来源：http://dali.jiagoushi.top/Article/details/gtdmmkrehx.html

按章节统计：
来源：http://dali.hnxiangtu.top/Article/details/gtoutjvluc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsekbnuhf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtvseostqk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtvytlyczz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gtjkhweamz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuetiantiany.cn/Article/details/gtzggprfbi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gtdyakldxm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtvhlksvfe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gtogdkrgpr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtukwkmboh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gteeqayuzq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtnagbzgjr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtdqgnvyrw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gttsgtvlaf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jlsjyb.cn/Article/details/gtteqwvzal.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.vqdsnc.cn/Article/details/gtxemdkbhh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtphrtwlja.html

Q SQL 专题                              90
来源：http://dali.jinqigufen.top/Article/details/gtniyllunl.html

R Bash 专题                             80
来源：http://dali.xuetiantiany.cn/Article/details/gtxamoathe.html

S C / C++ 专题                          60
来源：http://dali.jinqigfzy.top/Article/details/gtrfpqzvmt.html

T 其他语言补充                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtutdfbazu.html

U 高频实用片段                         120
来源：http://dali.yj20258888.top/Article/details/gtcsaqogma.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtecvxvsvz.html

合计                                  2106 条
来源：http://dali.hnxiangtu.top/Article/details/gtykfhrmsv.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gtzcbqnpnk.html

使用提醒
来源：http://dali.cqqwz.cn/Article/details/gtpqlpmmzh.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtozchlunf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jqgufenzy.top/Article/details/gttmfurbyu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jianghu66.top/Article/details/gtmatnhluq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cheryme.top/Article/details/gtvfgljgnp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.daxiang520.top/Article/details/gtirwrrdix.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tanke756.top/Article/details/gtimtkpzte.html

—— 文件结束 ——
来源：http://dali.jiagoushi.top/Article/details/gtfobgafvv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttisuycex.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ivvv.top/Article/details/gttaqhsynv.html

Common Programming Examples Cheat Book
来源：http://dali.wangshuangyany.cn/Article/details/gthmsdbipk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthiaewseq.html

【收录内容】
来源：http://dali.cdnleiting.top/Article/details/gtxjymapyv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shzxlz.cn/Article/details/gthrfxpfmg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhengqikj.top/Article/details/gtvgjwyrol.html

SQL · Bash · C · C++
来源：http://dali.fzhhl.top/Article/details/gtcctddfvy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cdnleiting.top/Article/details/gtqzyapyii.html

【使用说明】
来源：http://dali.cheryme.top/Article/details/gtkrflsgqh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.haohaochexian.top/Article/details/gtkmfwofut.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gtqzclzlpi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsumpibow.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.dianchejie.cn/Article/details/gtunarzvbp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hongshengwenyu.top/Article/details/gtepzpkcet.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.guannengcc.top/Article/details/gtmkfpbbwo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zycfv.cn/Article/details/gtokqesynz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.haohaochexian.top/Article/details/gtneapjmqr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xinyue.icu/Article/details/gtisrlbhjy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ydzc1.top/Article/details/gtgnpkvahh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yonumen.top/Article/details/gtsygnmqqi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yueranfly.top/Article/details/gtqkztoyrl.html

【文件统计】
来源：http://dali.hysaishi.cn/Article/details/gttnlzmilk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gotoacloud.top/Article/details/gtqcwrxfac.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtkjtaohfm.html

目  录
来源：http://dali.hongshengwenyu.top/Article/details/gttfmfjcee.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtonstjuim.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdoxwjznt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtflmxeunn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtcclwmnix.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gtxqwhlqtb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxinkj.top/Article/details/gtpjqmzcjz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cheryme.top/Article/details/gtuxylxqmx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtmtyzamcn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cheryme.top/Article/details/gtjiacajka.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtxxcnhjep.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.birdmap.top/Article/details/gthhglqoar.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtdzspydvc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gttsnmxqrq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyxfybwz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gthfhobkri.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yuanzhike.top/Article/details/gtfqttdmae.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtpgpilfux.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yonumen.top/Article/details/gtmwzither.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yonumen.top/Article/details/gteioavolk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guowangkeji.top/Article/details/gtrsphjmvl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtqinjnpgg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtkyoezrzj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxcjelsfo.html

A. 基础语法与类型
来源：http://dali.zhongyouzk.top/Article/details/gtfybuxqvy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtzmbheozw.html

[A01] Hello World
来源：http://dali.xinyue.icu/Article/details/gtpitbiunt.html

Py:   print("Hello, World!")
来源：http://dali.daxiang520.top/Article/details/gtpnraoozt.html

PHP:  echo "Hello, World!";
来源：http://dali.yuanzhike.top/Article/details/gtcsdcxhbq.html

JS:   console.log("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtvjzagkas.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sysykeji.top/Article/details/gtxrirsdjn.html

Java: System.out.println("Hello, World!");
来源：http://dali.aibaodan.cn/Article/details/gtyhaspppi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sxryk.cn/Article/details/gtjuwstzdz.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbqjglha.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtyspibmbo.html

[A02] 变量声明与赋值
来源：http://dali.jqgufenzy.top/Article/details/gtflbptaor.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gtqkchyqdh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guowangkeji.top/Article/details/gtjfodnnab.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtqaklapcw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gtzmypxfgz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtuwrapeax.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenlongwang.top/Article/details/gtnvfyekma.html

Ruby: name = "Alex"; age = 20
来源：http://dali.9152youxi.cn/Article/details/gtvtczkuyr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yvedp.cn/Article/details/gtkbzauvyd.html

[A03] 常量定义
来源：http://dali.yongpay.top/Article/details/gtouzpggzv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sufxvd.cn/Article/details/gthixslvsx.html

PHP:  const PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtslapqwrn.html

JS:   const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtrnitibwp.html

TS:   const PI: number = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtfsqqcnlj.html

Java: static final double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtmpdsvvko.html

Go:   const PI = 3.14159
来源：http://dali.aibaodan.cn/Article/details/gthxgevzzn.html

Ruby: PI = 3.14159
来源：http://dali.yongpay.top/Article/details/gtvnwsihmu.html

C#:   const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtiejmwwhv.html

[A04] 判断变量类型
来源：http://dali.mhx1999.top/Article/details/gtoqljtela.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cdnleiting.top/Article/details/gtuqkqhafk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hysaishi.cn/Article/details/gtyxxgvmyf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gtdclbjicb.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gtthmrvjhp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gogol.net.cn/Article/details/gtapkeessv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hongshengwenyu.top/Article/details/gttpxffvwf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hongshengwenyu.top/Article/details/gtsbxdveum.html

C#:   x.GetType().Name; x is int
来源：http://dali.birdmap.top/Article/details/gtbfujyobi.html

[A05] 整数除法与取模
来源：http://dali.shangyingyoupin.top/Article/details/gtvukgkbcz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj202588.top/Article/details/gtnukfqhrc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtwzotebof.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtcxvtmkzj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtwwyvowkf.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtzekwddgh.html

Go:   7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtegkdmiif.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtbfymclwk.html

C#:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtxjbkiuzg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtwkpiqgkg.html

Py:   int("42"); float("3.14")
来源：http://dali.bjfxy.top/Article/details/gtqvblomrx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhiwuduotai.top/Article/details/gtichcjixv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtkarhehxh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gtcyyqdeyi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jqgfzy.top/Article/details/gtckysnphc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.fzhhl.top/Article/details/gtchapdxcr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shzxlz.cn/Article/details/gtrvtrhhrp.html


<!-- 参考信息 -->