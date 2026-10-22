代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.daria6918.cn/Article/details/gt2ttovduqe.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigfzy.top/Article/details/gt2tpioyegn.html

[U54] PHP：空安全调用
来源：http://dali.yj20258.top/Article/details/gt2dpqrjgwf.html

$obj?->method()
来源：http://dali.shzxlz.cn/Article/details/gt2kbvnytkq.html

[U55] PHP：match 表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2nrlynyot.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gt2zuxokmhu.html

[U56] PHP：命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmfqvrul.html

f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2luaonauz.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2kvxrlgtg.html

"值: {$a}"
来源：http://dali.yvedp.cn/Article/details/gt2akozbybf.html

[U58] PHP：数组三件套
来源：http://dali.wangdashe.top/Article/details/gt2hhbcusxb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daxiang520.top/Article/details/gt2mrpeczqu.html

[U59] PHP：自定义排序
来源：http://dali.nwbrower.top/Article/details/gt2prkwlnau.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gt2owidorly.html

[U60] PHP：JSON 编解码
来源：http://dali.yvedp.cn/Article/details/gt2dicpytjj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yangfankeji.com/Article/details/gt2avszjjtf.html

[U61] PHP：正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2syzpaihp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2nphsdlja.html

[U62] PHP：日期对象
来源：http://dali.chenlongwang.top/Article/details/gt2ufhkjwka.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jyoumei.cn/Article/details/gt2ttduezox.html

[U63] PHP：文件读写
来源：http://dali.hammf.cn/Article/details/gt2aewqjgqp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.iojbl.cn/Article/details/gt2xsxlhrmc.html

[U64] PHP：目录遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2xcmntpuf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sysykeji.top/Article/details/gt2rmlacind.html

[U65] PHP：会话
来源：http://dali.nanxinkj.top/Article/details/gt2cqqleler.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2yxepcmct.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkopsyno.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nwbrower.top/Article/details/gt2raejpkzk.html

[U67] PHP：处理文件上传
来源：http://dali.vqdsnc.cn/Article/details/gt2eqkzpefh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjabxezd.html

[U68] PHP：PDO 连接
来源：http://dali.quarkkingdee.top/Article/details/gt2qwrcvxcr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tianlin.xyz/Article/details/gt2ecbkhecy.html

[U69] PHP：PDO 预处理
来源：http://dali.yj202588.top/Article/details/gt2gogmmhkx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cdnleiting.top/Article/details/gt2avahnxmi.html

[U70] PHP：PDO 事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puapxtvh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxuanxn.top/Article/details/gt2agixjuos.html

[U71] PHP：抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2urlvtvjz.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gt2mhjeiqax.html

[U72] PHP：写错误日志
来源：http://dali.gzhubu.top/Article/details/gt2efioeghi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dashuyun.cn/Article/details/gt2sdphsuan.html

[U73] PHP：读取 ini 配置
来源：http://dali.dashuyun.cn/Article/details/gt2itrkvkik.html

parse_ini_file("config.ini", true)
来源：http://dali.guowangkeji.top/Article/details/gt2gacwithu.html

[U74] PHP：读取环境变量
来源：http://dali.sysykeji.top/Article/details/gt2bcbrbvwq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.nwbrower.top/Article/details/gt2widvsqmb.html

[U75] PHP：依赖注入
来源：http://dali.sufxvd.cn/Article/details/gt2kknobyks.html

composer require psr/container
来源：http://dali.hywenlv.cn/Article/details/gt2qdxbqdeo.html

[U76] PHP：简单路由
来源：http://dali.0kj1m.cn/Article/details/gt2glovrikg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fzhhl.top/Article/details/gt2bjsrsnzt.html

[U77] PHP：模板渲染
来源：http://dali.zhiwuduotai.top/Article/details/gt2dsdvoljs.html

composer require twig/twig
来源：http://dali.svipenyu.cn/Article/details/gt2agakbldk.html

[U78] PHP：单元测试
来源：http://dali.daria6918.cn/Article/details/gt2teohusog.html

composer require --dev phpunit/phpunit
来源：http://dali.tian-w.cn/Article/details/gt2fmblxwed.html

[U79] PHP：静态分析
来源：http://dali.dianchejie.cn/Article/details/gt2twdsgjqc.html

composer require --dev phpstan/phpstan
来源：http://dali.jyoumei.cn/Article/details/gt2epsbtqes.html

[U80] PHP：代码规范修复
来源：http://dali.chenzaomai.com/Article/details/gt2ihxllgxo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhongyouzk.top/Article/details/gt2xxyxpaud.html

[U81] JS：初始化项目
来源：http://dali.chenlongwang.top/Article/details/gt2kqnziqtp.html

npm init -y;  npm i express
来源：http://dali.mhx1999.top/Article/details/gt2eqmfjabc.html

[U82] JS：package.json 脚本
来源：http://dali.jqgufenzy.top/Article/details/gt2dxztrnek.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gt2tyravoux.html

[U83] JS：ES Module 导入导出
来源：http://dali.birdmap.top/Article/details/gt2umdsujgw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gt2txbkdtwg.html

[U84] JS：CommonJS 写法
来源：http://dali.sxryk.cn/Article/details/gt2zaegdjjl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yvedp.cn/Article/details/gt2tqdcaaet.html

[U85] JS：可选链
来源：http://dali.zycfv.cn/Article/details/gt2rubkvzih.html

a?.b?.c
来源：http://dali.yueranfly.top/Article/details/gt2iukgbloe.html

[U86] JS：空值合并
来源：http://dali.zdqjudy.top/Article/details/gt2bxxigsuj.html

a ?? b
来源：http://dali.jiagoushi.top/Article/details/gt2obpnpnhe.html

[U87] JS：解构默认值
来源：http://dali.yonumen.top/Article/details/gt2qjkrbvlr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gotoacloud.top/Article/details/gt2drqxlmkl.html

[U88] JS：对象展开合并
来源：http://dali.zhengqikj.top/Article/details/gt2ohhubjoj.html

{ ...a, ...b }
来源：http://dali.jinqigfzy.top/Article/details/gt2wlrxxigp.html

[U89] JS：数组去重
来源：http://dali.yongpay.top/Article/details/gt2xjlejqnl.html

[...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gt2ohyevtxq.html

[U90] JS：数字数组排序
来源：http://dali.c1oappe.top/Article/details/gt2vovveqwb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhaezqgo.html

[U91] JS：对象键值遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpvwfdps.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gaohongyu789.top/Article/details/gt2eblbzvps.html

[U92] JS：深拷贝
来源：http://dali.xylfe.cn/Article/details/gt2gtypgmgn.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2oyuntopn.html

[U93] JS：模板字符串
来源：http://dali.zdqjudy.top/Article/details/gt2eyrgvaln.html

`共 ${n} 条`
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imdrlodn.html

[U94] JS：箭头函数
来源：http://dali.hnqzz.top/Article/details/gt2fpvarhyj.html

const double = x => x * 2;
来源：http://dali.yj20258888.top/Article/details/gt2jxppagkl.html

[U95] JS：Promise 包装
来源：http://dali.9152youxi.cn/Article/details/gt2wswlznbu.html

new Promise((resolve, reject) => {})
来源：http://dali.yanxiufei.cn/Article/details/gt2pmwlgypg.html

[U96] JS：async/await 与异常
来源：http://dali.c1oappe.top/Article/details/gt2sgozxauy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2uedidiwz.html

[U97] JS：并发请求
来源：http://dali.smart0.xyz/Article/details/gt2ufdolsjn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2fmxzxqne.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2iolhnwpl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgfzy.top/Article/details/gt2lphwyjyj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgvmwes.html

el.addEventListener("click", e => {})
来源：http://dali.nwbrower.top/Article/details/gt2nnwccqyz.html

[U100] JS：DOM 查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytpujufg.html

document.querySelector(".item")
来源：http://dali.gzhubu.top/Article/details/gt2klknbvte.html

[U101] JS：classList 操作
来源：http://dali.shzxlz.cn/Article/details/gt2imxydgwh.html

el.classList.toggle("active")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjumfqnx.html

[U102] JS：本地存储
来源：http://dali.ivvv.top/Article/details/gt2pgypeboc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.havefunace.top/Article/details/gt2mufaxjmw.html

[U103] JS：定时器
来源：http://dali.xuanzx.com/Article/details/gt2ufeeicxg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xylfe.cn/Article/details/gt2nrbwfocs.html

[U104] JS：防抖
来源：http://dali.andypj.xyz/Article/details/gt2pmojuvaw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gt2fdvjczbk.html

[U105] JS：节流
来源：http://dali.ybcxt.top/Article/details/gt2wfvvkore.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sysykeji.top/Article/details/gt2mrlizbxq.html

[U106] JS：日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2ajrlxnsn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258888.top/Article/details/gt2tnjbylbl.html

[U107] JS：数字千分位
来源：http://dali.zdqjudy.top/Article/details/gt2kysurhtz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yueranfly.top/Article/details/gt2zzifhmtu.html

[U108] JS：随机整数
来源：http://dali.havefunace.top/Article/details/gt2jytyrccy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ybcxt.top/Article/details/gt2uzbgqgzh.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gt2hiluvzkj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2ngznjjsg.html

[U110] JS：数组分块
来源：http://dali.jyoumei.cn/Article/details/gt2gojprayz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.iojbl.cn/Article/details/gt2qwxwdnbv.html

[U111] JS：对象转 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ttqtlcdl.html

new Map(Object.entries(obj))
来源：http://dali.hywenlv.cn/Article/details/gt2tgynlizk.html

[U112] JS：字符串补位
来源：http://dali.feifeiyinyue.top/Article/details/gt2ourddivy.html

"7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gt2zdsfvwja.html

[U113] JS：正则替换全部
来源：http://dali.jinqigufen.top/Article/details/gt2dujqztvz.html

s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2cwdxpjni.html

[U114] JS：JSON 深比较
来源：http://dali.sufxvd.cn/Article/details/gt2bkcdwscx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gt2dnwfqmpd.html

[U115] JS：生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2dfjpmuzo.html

crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2dhogvpfh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2yloenwwq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmohndnn.html

[U117] JS：单元测试
来源：http://dali.redwolf501.top/Article/details/gt2pcxzhkbe.html

npm i -D vitest;  npx vitest
来源：http://dali.gogol.net.cn/Article/details/gt2kgcndyzw.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gt2fenwpoul.html

npm i -D vite;  npx vite
来源：http://dali.fengsongda.top/Article/details/gt2bwjffbgc.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gt2kjjrwcsy.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvfgjlwd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxuanxn.top/Article/details/gt2bffhnxuu.html

import.meta.env.VITE_API_URL
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzgojtvk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2pbcevidm.html

统计汇总
来源：http://dali.daria6918.cn/Article/details/gt2aiecxqgg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2tqeikewe.html

按语言统计（条）：
来源：http://dali.aibaodan.cn/Article/details/gt2rgmovrct.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gt2klrlgocy.html

PHP ............ 252
来源：http://dali.meibo888.top/Article/details/gt2ayklojvd.html

JavaScript ..... 252
来源：http://dali.havefunace.top/Article/details/gt2lrqlbeee.html

TypeScript ..... 212
来源：http://dali.hysaishi.cn/Article/details/gt2wegnqbfz.html

Java ........... 212
来源：http://dali.sxryk.cn/Article/details/gt2lpwqeevd.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imvesbmi.html

Ruby ........... 212
来源：http://dali.smart0.xyz/Article/details/gt2cwpyrdgt.html

C# ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gt2zowiqffa.html

C .............. 30
来源：http://dali.0kj1m.cn/Article/details/gt2frcujxgl.html

C++ ............ 30
来源：http://dali.hnxiangtu.top/Article/details/gt2xuiriwpo.html

SQL ............ 90
来源：http://dali.chenzaomai.com/Article/details/gt2jllwvlge.html

Bash ........... 80
来源：http://dali.haohaochexian.top/Article/details/gt2hebavnvc.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wglshlmy.html

Swift .......... 15
来源：http://dali.cheryme.top/Article/details/gt2ktcqidsf.html

Lua ............ 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmibsqvb.html

Perl ........... 10
来源：http://dali.aibaodan.cn/Article/details/gt2nvaxggwt.html

Scala .......... 10
来源：http://dali.jinqigufen.top/Article/details/gt2zlrditky.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2xfxkyfzs.html

合计 ........... 2106 条
来源：http://dali.gzhubu.top/Article/details/gt2iyepntmx.html

按章节统计：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvhuzrec.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.snrcjt.cn/Article/details/gt2zrwjcuzm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gt2cbwxdbxv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtxitzz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gt2tfyagctn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2miifrpch.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gt2ouesnnez.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gt2rowqtmmj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gt2qtrgtqmc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gt2simospaq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gt2ausrlevf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2qvchakuy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2hdqhnlsv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2ojtzyysy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gt2vavtvrgh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxinkj.top/Article/details/gt2uxrkltvr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gt2zyfmmfbb.html

Q SQL 专题                              90
来源：http://dali.shzxlz.cn/Article/details/gt2cekqjgfh.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gt2imisbaam.html

S C / C++ 专题                          60
来源：http://dali.daxiang520.top/Article/details/gt2wasenvcj.html

T 其他语言补充                          60
来源：http://dali.cucudq.cn/Article/details/gt2ftukqvpr.html

U 高频实用片段                         120
来源：http://dali.zhongyouzk.top/Article/details/gt2fysvtxys.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2eqqsxeml.html

合计                                  2106 条
来源：http://dali.gzhubu.top/Article/details/gt2ojyjuszt.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gt2scykxlnl.html

使用提醒
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdldving.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2pycymreo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zdqjudy.top/Article/details/gt2jsfbfxqi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.vqdsnc.cn/Article/details/gt2urjjcaqf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhongyouzk.top/Article/details/gt2bffytchw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.wangdashe.top/Article/details/gt2sgzdjolk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hammf.cn/Article/details/gt2nkmunfgz.html

—— 文件结束 ——
来源：http://dali.cashguo.top/Article/details/gt2dgrddpts.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2wenlzkof.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmzxitbl.html

Common Programming Examples Cheat Book
来源：http://dali.bjfxy.top/Article/details/gt2pheotlzx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2lvyewvqn.html

【收录内容】
来源：http://dali.zycfv.cn/Article/details/gt2nyejteub.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.fengsongda.top/Article/details/gt2fgcrvsms.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzynpbhd.html

SQL · Bash · C · C++
来源：http://dali.jyoumei.cn/Article/details/gt2zrkgkcur.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sweek.top/Article/details/gt2jaxianot.html

【使用说明】
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cabeesmw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gogol.net.cn/Article/details/gt2jqvicxxy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gt2tftjwzlh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenzaomai.com/Article/details/gt2eysygdpf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aizwys.cn/Article/details/gt2huvrjkyv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gt2rmnfvycz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cdnleiting.top/Article/details/gt2yimyqfyg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.mhx1999.top/Article/details/gt2pdhhpoke.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ehwqpu.com/Article/details/gt2ohcpurkw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.svipenyu.cn/Article/details/gt2vwcxbruo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.redwolf501.top/Article/details/gt2bchcnxrq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.guannengcc.top/Article/details/gt2lhsjqnkv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuanzx.com/Article/details/gt2klqnlyot.html

【文件统计】
来源：http://dali.chenjidiqi.icu/Article/details/gt2cehvhzqe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.wangshuangyany.cn/Article/details/gt2oldrimvr.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2cnnrvwxn.html

目  录
来源：http://dali.bjfxy.top/Article/details/gt2nmalinhw.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gt2smffyuil.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gt2nnikicqf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gt2uaeupqth.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gt2uukqdnjm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gt2yzmpytwj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sweek.top/Article/details/gt2oirufows.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2jppuaeok.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2dygxwker.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj202588.top/Article/details/gt2wctyubrb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqguuxnm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2wadhkhqd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2cifirpbw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2igzwpsbw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gt2dgbucmip.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tian-w.cn/Article/details/gt2chhskylr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zycfv.cn/Article/details/gt2aqamiowp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gt2rcdylubl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.daria6918.cn/Article/details/gt2voxvmmxn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jyoumei.cn/Article/details/gt2vecknnkb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hfpthk.cn/Article/details/gt2tgshcczq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gt2iktrurky.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2msevwuvl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2pvgtrzxm.html

A. 基础语法与类型
来源：http://dali.vqdsnc.cn/Article/details/gt2beiytdky.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lmbnqnti.html

[A01] Hello World
来源：http://dali.cucudq.cn/Article/details/gt2lpodgafm.html

Py:   print("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gt2qaboqaeg.html

PHP:  echo "Hello, World!";
来源：http://dali.xinyue.icu/Article/details/gt2xzqhcvxq.html

JS:   console.log("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gt2dwzhkzwt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ivvv.top/Article/details/gt2dtzkqadk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gt2taroyqzs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.quarkkingdee.top/Article/details/gt2vzqkonbt.html

Ruby: puts "Hello, World!"
来源：http://dali.smart0.xyz/Article/details/gt2rievqvkh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gt2kpujcosh.html

[A02] 变量声明与赋值
来源：http://dali.aibaodan.cn/Article/details/gt2qwydence.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.wangdashe.top/Article/details/gt2xnjwpcmp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ppjwa.cn/Article/details/gt2estkqvaz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cucudq.cn/Article/details/gt2juhvpvtn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.svipenyu.cn/Article/details/gt2lngzpnvl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenzaomai.com/Article/details/gt2pfmszmvo.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenzaomai.com/Article/details/gt2fhqgzpbm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.haohaochexian.top/Article/details/gt2qkiimcxj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj202588.top/Article/details/gt2slsrcnsr.html

[A03] 常量定义
来源：http://dali.ydzc1.top/Article/details/gt2ymeldtmx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fiebklhw.html

PHP:  const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2heklstfj.html

JS:   const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ttshvvyy.html

TS:   const PI: number = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2hspukhtd.html

Java: static final double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2wcjvjliz.html

Go:   const PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gt2kgfendlf.html

Ruby: PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gt2wljthchl.html

C#:   const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2rsfegddi.html

[A04] 判断变量类型
来源：http://dali.hysaishi.cn/Article/details/gt2iaitklvj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zdqjudy.top/Article/details/gt2hogucpax.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlftodpv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sysykeji.top/Article/details/gt2iixswtvu.html

TS:   typeof x; x instanceof Date
来源：http://dali.0kj1m.cn/Article/details/gt2akyvdytc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.daxiang520.top/Article/details/gt2qcxfhwpn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yangfankeji.com/Article/details/gt2feosusuz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gt2xiuhmozh.html

C#:   x.GetType().Name; x is int
来源：http://dali.zycfv.cn/Article/details/gt2tuevakze.html

[A05] 整数除法与取模
来源：http://dali.sufxvd.cn/Article/details/gt2byglzwac.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tianlin.xyz/Article/details/gt2zbqxpshe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2upeklron.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqciowjt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2jexijlji.html

Java: 7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2njbcsfbd.html

Go:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2mhowdfxb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gt2zcffrdek.html

C#:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2futwqhhq.html

[A06] 字符串转数字
来源：http://dali.yj20258.top/Article/details/gt2qqxvstpx.html

Py:   int("42"); float("3.14")
来源：http://dali.yueranfly.top/Article/details/gt2hhnohexz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shzxlz.cn/Article/details/gt2tshqcypn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.birdmap.top/Article/details/gt2zbrollif.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.vqdsnc.cn/Article/details/gt2qopandmv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.0kj1m.cn/Article/details/gt2bprerdlg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sweek.top/Article/details/gt2jovahoqr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenlongwang.top/Article/details/gt2sfxdtseb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gt2hsnbpinx.html

[A07] 数字转字符串
来源：http://dali.mhx1999.top/Article/details/gt2opwntcjg.html

Py:   str(42)
来源：http://dali.birdmap.top/Article/details/gt2qtdqncyy.html

PHP:  (string) 42; strval(42)
来源：http://dali.gzhubu.top/Article/details/gt2zrkbskmc.html


<!-- 参考信息 -->