代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.kuanghao11.cn/Article/details/gtrxkhzvih.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtwyzbwwhj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gtotmyvfae.html

?string $name = null
来源：http://dali.yueranfly.top/Article/details/gtbwuggzli.html

[U47] PHP：联合类型
来源：http://dali.dashuyun.cn/Article/details/gtbiyrmypa.html

int|string $id
来源：http://dali.xuetiantiany.cn/Article/details/gtjfyegpzs.html

[U48] PHP：纯枚举
来源：http://dali.dashuyun.cn/Article/details/gtdferpaxo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zdqjudy.top/Article/details/gtpjxbtwkr.html

[U49] PHP：只读属性
来源：http://dali.gaohongyu789.top/Article/details/gtcfhloobt.html

public readonly string $name
来源：http://dali.zhiwuduotai.top/Article/details/gtjfqbnctj.html

[U50] PHP：构造器属性提升
来源：http://dali.sweek.top/Article/details/gtbdkwpium.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gthdgsfhwo.html

[U51] PHP：数组解构
来源：http://dali.cashguo.top/Article/details/gtpjrxptpb.html

[$a, $b] = $arr;
来源：http://dali.sufxvd.cn/Article/details/gtbiznztdc.html

[U52] PHP：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gteoghtmum.html

$double = fn($x) => $x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtjlgxpmzi.html

[U53] PHP：空合并运算符
来源：http://dali.zdqjudy.top/Article/details/gtoavwesjj.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gtvlxfoebq.html

[U54] PHP：空安全调用
来源：http://dali.xinyue.icu/Article/details/gtjwwnvapm.html

$obj?->method()
来源：http://dali.yueranfly.top/Article/details/gtgquwdejp.html

[U55] PHP：match 表达式
来源：http://dali.yueranfly.top/Article/details/gteihtvfcm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zycfv.cn/Article/details/gtkmfjaedf.html

[U56] PHP：命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gtmamrkwok.html

f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtbkhvnzme.html

[U57] PHP：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtfjeseqvq.html

"值: {$a}"
来源：http://dali.tian-w.cn/Article/details/gtaqtzhsbh.html

[U58] PHP：数组三件套
来源：http://dali.yvedp.cn/Article/details/gtmnbfbmaz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.redwolf501.top/Article/details/gtdacxsfud.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gtjrjyrtzy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtorzvudis.html

[U60] PHP：JSON 编解码
来源：http://dali.yuanzhike.top/Article/details/gtmnrxyxfn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fzhhl.top/Article/details/gttkfczlib.html

[U61] PHP：正则
来源：http://dali.zhongyouzk.top/Article/details/gtpsstxesx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gtcdanzbtn.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gtccsehiop.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gtamfqvrrp.html

[U63] PHP：文件读写
来源：http://dali.yonumen.top/Article/details/gtcpvakxsx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.vqdsnc.cn/Article/details/gtzypekanx.html

[U64] PHP：目录遍历
来源：http://dali.dashuyun.cn/Article/details/gtnmooqozy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xinyue.icu/Article/details/gtwxtxxwta.html

[U65] PHP：会话
来源：http://dali.cqqwz.cn/Article/details/gtcnjpoffm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtjdgaalhj.html

[U66] PHP：设置 Cookie
来源：http://dali.yuxming.cn/Article/details/gtedltqejj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daria6918.cn/Article/details/gtjupglatn.html

[U67] PHP：处理文件上传
来源：http://dali.hywenlv.cn/Article/details/gtmtswdylz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hysaishi.cn/Article/details/gtmlfwcjrj.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangtech.top/Article/details/gthbbwdczi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuilfqaf.html

[U69] PHP：PDO 预处理
来源：http://dali.hammf.cn/Article/details/gtdrsqefcj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gzhubu.top/Article/details/gtmqhbnovw.html

[U70] PHP：PDO 事务
来源：http://dali.kuanghao11.cn/Article/details/gtxwavsinb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gthhqrhrum.html

[U71] PHP：抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtpmbrztxl.html

throw new RuntimeException("失败", 500);
来源：http://dali.9152youxi.cn/Article/details/gtagfvbpfl.html

[U72] PHP：写错误日志
来源：http://dali.0kj1m.cn/Article/details/gtwlegvvcc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuetiantiany.cn/Article/details/gtrkyrlxxc.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258888.top/Article/details/gtgrrtxges.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gtdigrwwit.html

[U74] PHP：读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtrtscmvxn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhoulong.xyz/Article/details/gtnvaynrza.html

[U75] PHP：依赖注入
来源：http://dali.zhoulong.xyz/Article/details/gtyxcdqamt.html

composer require psr/container
来源：http://dali.wangshuangyany.cn/Article/details/gtvjnbkiyj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gtikpwscvz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zdqjudy.top/Article/details/gthnifryqs.html

[U77] PHP：模板渲染
来源：http://dali.yj20258.top/Article/details/gtfhdbcvom.html

composer require twig/twig
来源：http://dali.zhengqikj.top/Article/details/gtvnlbaogl.html

[U78] PHP：单元测试
来源：http://dali.yj20258888.top/Article/details/gteqmpgeqi.html

composer require --dev phpunit/phpunit
来源：http://dali.cashguo.top/Article/details/gtdpkmhqho.html

[U79] PHP：静态分析
来源：http://dali.shuidangran.top/Article/details/gtysgqlbaq.html

composer require --dev phpstan/phpstan
来源：http://dali.pengpengdd.cyou/Article/details/gtxmuoifmu.html

[U80] PHP：代码规范修复
来源：http://dali.yuanzhike.top/Article/details/gtktuuhgwg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj202588.top/Article/details/gtofanrmgs.html

[U81] JS：初始化项目
来源：http://dali.cashguo.top/Article/details/gtpgdoqvpe.html

npm init -y;  npm i express
来源：http://dali.nanxuanxn.top/Article/details/gtnprptujo.html

[U82] JS：package.json 脚本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqptflbxz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.c1oappe.top/Article/details/gtyjqmydoa.html

[U83] JS：ES Module 导入导出
来源：http://dali.tian-w.cn/Article/details/gtaqlwothq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtnktuuaga.html

[U84] JS：CommonJS 写法
来源：http://dali.cdnleiting.top/Article/details/gtjrevyjnn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sxryk.cn/Article/details/gtjxsufqic.html

[U85] JS：可选链
来源：http://dali.smart0.xyz/Article/details/gtcjjjelrd.html

a?.b?.c
来源：http://dali.zhiwuduotai.top/Article/details/gtkpmbhocy.html

[U86] JS：空值合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupeviehc.html

a ?? b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvleshooj.html

[U87] JS：解构默认值
来源：http://dali.jyoumei.cn/Article/details/gtlgyqytml.html

const { a = 1, b = 2 } = obj;
来源：http://dali.daria6918.cn/Article/details/gtwatjzbvc.html

[U88] JS：对象展开合并
来源：http://dali.yvedp.cn/Article/details/gtykeyxkbs.html

{ ...a, ...b }
来源：http://dali.redwolf501.top/Article/details/gtdygosyzh.html

[U89] JS：数组去重
来源：http://dali.ivvv.top/Article/details/gtzkzrevqd.html

[...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtsynefhht.html

[U90] JS：数字数组排序
来源：http://dali.haohaochexian.top/Article/details/gttjrfiyhg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtsnctfjtx.html

[U91] JS：对象键值遍历
来源：http://dali.xylfe.cn/Article/details/gtpwzpjlfg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenlongwang.top/Article/details/gtryqemayn.html

[U92] JS：深拷贝
来源：http://dali.ivvv.top/Article/details/gtixvcmwma.html

structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtvuzpsuvg.html

[U93] JS：模板字符串
来源：http://dali.vqdsnc.cn/Article/details/gtvfjhjrfb.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gtcabnmqkt.html

[U94] JS：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gtvwrlpmhl.html

const double = x => x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtusypotos.html

[U95] JS：Promise 包装
来源：http://dali.cashguo.top/Article/details/gtfodyorbr.html

new Promise((resolve, reject) => {})
来源：http://dali.cucudq.cn/Article/details/gtxvxmbujf.html

[U96] JS：async/await 与异常
来源：http://dali.cashguo.top/Article/details/gtzrwvdxbb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gttezybyxz.html

[U97] JS：并发请求
来源：http://dali.yuanzhike.top/Article/details/gtzbhrnzym.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gttqgymult.html

[U98] JS：fetch 带 JSON
来源：http://dali.vqdsnc.cn/Article/details/gtajpzdxqq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.9152youxi.cn/Article/details/gtsydkqfkg.html

[U99] JS：事件监听
来源：http://dali.ivvv.top/Article/details/gtmgrrzadp.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gtakkyrvdq.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gtgkutckyg.html

document.querySelector(".item")
来源：http://dali.ehwqpu.com/Article/details/gtmbbfouna.html

[U101] JS：classList 操作
来源：http://dali.9152youxi.cn/Article/details/gtlwwmqqrr.html

el.classList.toggle("active")
来源：http://dali.yj20258.top/Article/details/gtdyabdhth.html

[U102] JS：本地存储
来源：http://dali.redwolf501.top/Article/details/gtvfkgibvt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj202588.top/Article/details/gtxqwackul.html

[U103] JS：定时器
来源：http://dali.hongshengwenyu.top/Article/details/gttjhdiblr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxinkj.top/Article/details/gtnobnpdcm.html

[U104] JS：防抖
来源：http://dali.ybcxt.top/Article/details/gtgkjwobxj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlwbruvu.html

[U105] JS：节流
来源：http://dali.c1oappe.top/Article/details/gtoayaverv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpccxxhfr.html

[U106] JS：日期格式化
来源：http://dali.pycfn.com/Article/details/gtzpdlxfbf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yanxiufei.cn/Article/details/gtcbjuparb.html

[U107] JS：数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtopwdgesi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtfvvrvknz.html

[U108] JS：随机整数
来源：http://dali.cqqwz.cn/Article/details/gtutjposfq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gtaxjuckbj.html

[U109] JS：数组分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbcrtegv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gtdhbvvume.html

[U110] JS：数组分块
来源：http://dali.shangyingyoupin.top/Article/details/gtztwbtrrn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shuidangran.top/Article/details/gtjqhivdmr.html

[U111] JS：对象转 Map
来源：http://dali.zhoulong.xyz/Article/details/gtxitslmvk.html

new Map(Object.entries(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtmparsobv.html

[U112] JS：字符串补位
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjerqnhe.html

"7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtowmfbvcv.html

[U113] JS：正则替换全部
来源：http://dali.9152youxi.cn/Article/details/gtdqijknqv.html

s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtigcvlwll.html

[U114] JS：JSON 深比较
来源：http://dali.ppjwa.cn/Article/details/gtypobrneo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtfgsjibqv.html

[U115] JS：生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gtlrsvugjr.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtmiitpgvu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yvedp.cn/Article/details/gtpyygmtba.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gtctgaebuf.html

[U117] JS：单元测试
来源：http://dali.ydzc1.top/Article/details/gtebjjjcga.html

npm i -D vitest;  npx vitest
来源：http://dali.xuanzx.com/Article/details/gtjqclogzb.html

[U118] JS：开发服务器
来源：http://dali.jqgufenzy.top/Article/details/gtabffopri.html

npm i -D vite;  npx vite
来源：http://dali.cqqwz.cn/Article/details/gticjxtbei.html

[U119] JS：生产构建
来源：http://dali.hongshengwenyu.top/Article/details/gtljffcjub.html

npx vite build
来源：http://dali.hnqzz.top/Article/details/gtpxgxykob.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pengpengdd.cyou/Article/details/gtiupzvyqi.html

import.meta.env.VITE_API_URL
来源：http://dali.havefunace.top/Article/details/gtogtoivtl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmhkrdjbo.html

统计汇总
来源：http://dali.tian-w.cn/Article/details/gtjgodyahb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtkwegnaaf.html

按语言统计（条）：
来源：http://dali.cdnleiting.top/Article/details/gtpzglpffr.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gtmnaxbuit.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gteuckdmvi.html

JavaScript ..... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavlyckbx.html

TypeScript ..... 212
来源：http://dali.shuidangran.top/Article/details/gtzwobrsop.html

Java ........... 212
来源：http://dali.hammf.cn/Article/details/gtsmuskbei.html

Go ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtiucjtviw.html

Ruby ........... 212
来源：http://dali.svipenyu.cn/Article/details/gtvqdfcplj.html

C# ............. 212
来源：http://dali.haohaochexian.top/Article/details/gttcocnnus.html

C .............. 30
来源：http://dali.cashguo.top/Article/details/gtnevgbhmy.html

C++ ............ 30
来源：http://dali.sxryk.cn/Article/details/gtayntmnvt.html

SQL ............ 90
来源：http://dali.ehwqpu.com/Article/details/gtsujfmxkt.html

Bash ........... 80
来源：http://dali.zhixingplan.top/Article/details/gtytmdtmmz.html

Kotlin ......... 15
来源：http://dali.nwbrower.top/Article/details/gtrkyctjyc.html

Swift .......... 15
来源：http://dali.dashuyun.cn/Article/details/gtuasmdapo.html

Lua ............ 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyccsgfd.html

Perl ........... 10
来源：http://dali.yonumen.top/Article/details/gtqzzefdsd.html

Scala .......... 10
来源：http://dali.guowangkeji.top/Article/details/gtcggfbrwt.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtsvsdwykk.html

合计 ........... 2106 条
来源：http://dali.zhengqikj.top/Article/details/gtqykieokj.html

按章节统计：
来源：http://dali.zhixingplan.top/Article/details/gtdbacvsvw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsswgbbom.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtglwlrnqq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtsnokekxy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.pengpengdd.cyou/Article/details/gtghmhujrc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tanke756.top/Article/details/gtgkjcffrt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtqnsikbcs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gttqzbofhf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gtjohdccuo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtbcoqrpzl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gtxeeqrltw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtwzvxclsk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gteuuuomvj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtfcwywwyv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gtxhwgugzv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.andypj.xyz/Article/details/gtjhleiyrh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtxsjasewo.html

Q SQL 专题                              90
来源：http://dali.yongpay.top/Article/details/gtdlhiifek.html

R Bash 专题                             80
来源：http://dali.yj20258888.top/Article/details/gtnqlpmdyz.html

S C / C++ 专题                          60
来源：http://dali.wangdashe.top/Article/details/gtapkivoft.html

T 其他语言补充                          60
来源：http://dali.nwbrower.top/Article/details/gtvoxyoggt.html

U 高频实用片段                         120
来源：http://dali.meibo888.top/Article/details/gtvdcnjaes.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtyvieswpr.html

合计                                  2106 条
来源：http://dali.nwbrower.top/Article/details/gtrgyogwsf.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtwwkwvnex.html

使用提醒
来源：http://dali.xziqi.cn/Article/details/gtzryaweyw.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtzfocnmxx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuanzx.com/Article/details/gtccphvncq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.chenjidiqi.icu/Article/details/gtznhjyuma.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxmzerrb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hongshengwenyu.top/Article/details/gtsumwislv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gtshogqfbm.html

—— 文件结束 ——
来源：http://dali.9152youxi.cn/Article/details/gtqyhmywhh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtgpmkxkot.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258888.top/Article/details/gttiibcsgp.html

Common Programming Examples Cheat Book
来源：http://dali.daria6918.cn/Article/details/gtmbzzhtss.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxsjqchf.html

【收录内容】
来源：http://dali.jiagoushi.top/Article/details/gthlziicho.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.havefunace.top/Article/details/gtkgtypspt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guowangkeji.top/Article/details/gtsyeaidgq.html

SQL · Bash · C · C++
来源：http://dali.snrcjt.cn/Article/details/gtlqzuutnm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aizwys.cn/Article/details/gtluaxkwsq.html

【使用说明】
来源：http://dali.yvedp.cn/Article/details/gtdwpnjjda.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.dashuyun.cn/Article/details/gtmdwkahlu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ybcxt.top/Article/details/gtvmbhxyow.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.andypj.xyz/Article/details/gtkfztcvxh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shuidangran.top/Article/details/gtrwzhaprj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.smart0.xyz/Article/details/gtrdpnllpc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.iojbl.cn/Article/details/gtfgqmebsh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj20258888.top/Article/details/gtnebzfdoy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fzhhl.top/Article/details/gtnpqqgema.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.birdmap.top/Article/details/gtibbarogc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.feifeiyinyue.top/Article/details/gtoidjrkeh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yueranfly.top/Article/details/gtrwwiumtz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.daxiang520.top/Article/details/gtdnhzdmbx.html

【文件统计】
来源：http://dali.jqgfzy.top/Article/details/gtmbmfrgme.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gogol.net.cn/Article/details/gtlacccgpu.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtoicycnvz.html

目  录
来源：http://dali.nwbrower.top/Article/details/gtzdlxoaeg.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyamfuyr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jqgufenzy.top/Article/details/gtcsmipyfh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtvegaenbj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yangfankeji.com/Article/details/gtaccizwdv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gtguhxacqs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xziqi.cn/Article/details/gtdeoqrfpt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtrjybqczx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkznqlest.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtlprevhjm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gtzwapfarm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtccupsrod.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtskbrtbao.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtcitfmqhy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gthtzffrcv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sweek.top/Article/details/gtcwuuqsnd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.quarkkingdee.top/Article/details/gtyjlblugm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtfoibbvbs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gaohongyu789.top/Article/details/gtilusayzp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gtvxzagyfn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj202588.top/Article/details/gtaswbfktq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gtkruomnuh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtjhgzkhtl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmunowqsc.html

A. 基础语法与类型
来源：http://dali.wangdashe.top/Article/details/gtykgvomnp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxducquti.html

[A01] Hello World
来源：http://dali.cdnleiting.top/Article/details/gtdqinmgzb.html

Py:   print("Hello, World!")
来源：http://dali.yanxiufei.cn/Article/details/gtmuzthprn.html

PHP:  echo "Hello, World!";
来源：http://dali.redwolf501.top/Article/details/gtqbqzzgdh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtfivdeysy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangshuangyany.cn/Article/details/gtjdthnbjx.html

Java: System.out.println("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gtfsobdgcs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gtacebkchy.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gthykpzbzl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtadsnuqaf.html

[A02] 变量声明与赋值
来源：http://dali.cashguo.top/Article/details/gtdjhfyghg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.9152youxi.cn/Article/details/gtoattwvwv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcmtvasv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuanzhike.top/Article/details/gtnhmnmtxa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258888.top/Article/details/gtrrevgata.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtjbpqrprb.html

Go:   name := "Alex"; age := 20
来源：http://dali.meibo888.top/Article/details/gtnhjftznl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daxiang520.top/Article/details/gtbkyywtxx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtrdaqhduf.html

[A03] 常量定义
来源：http://dali.svipenyu.cn/Article/details/gttkvpjiiw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxuanxn.top/Article/details/gtoxauptqo.html

PHP:  const PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtcutzvpyo.html

JS:   const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtrhilpjhn.html

TS:   const PI: number = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtiwcvoakk.html

Java: static final double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtddsaajoi.html

Go:   const PI = 3.14159
来源：http://dali.nwbrower.top/Article/details/gthtvlncbi.html

Ruby: PI = 3.14159
来源：http://dali.tanke756.top/Article/details/gtbplekhnu.html

C#:   const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtbymzwmpz.html

[A04] 判断变量类型
来源：http://dali.ybcxt.top/Article/details/gtdfmxbalk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.aibaodan.cn/Article/details/gtrbtpcvyc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenzaomai.com/Article/details/gtwgfocayq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gtzdoknidx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gtnjpamiqo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ivvv.top/Article/details/gtrtzcykgn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenlongwang.top/Article/details/gtpyjyraba.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinghuilouyu.cn/Article/details/gtneqijmmi.html

C#:   x.GetType().Name; x is int
来源：http://dali.havefunace.top/Article/details/gttzumdnug.html

[A05] 整数除法与取模
来源：http://dali.gogol.net.cn/Article/details/gtwiqsqjib.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hnqzz.top/Article/details/gtzejkbpws.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtqmnjroep.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtlbzvogtn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtqbzheyfz.html


<!-- 参考信息 -->