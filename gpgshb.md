代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.yvedp.cn/Article/details/gtkamdqhna.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtxdttcvid.html

[U46] PHP：可空类型
来源：http://dali.ivvv.top/Article/details/gtjjuzeggf.html

?string $name = null
来源：http://dali.jinqigufen.top/Article/details/gtvhahokna.html

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gtxklpmunb.html

int|string $id
来源：http://dali.nanxuanxn.top/Article/details/gtlnndmyni.html

[U48] PHP：纯枚举
来源：http://dali.vqdsnc.cn/Article/details/gttiapkisd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cqqwz.cn/Article/details/gtaroqydjx.html

[U49] PHP：只读属性
来源：http://dali.snrcjt.cn/Article/details/gtmrfsowtk.html

public readonly string $name
来源：http://dali.zhengqikj.top/Article/details/gtqnqobkcd.html

[U50] PHP：构造器属性提升
来源：http://dali.9152youxi.cn/Article/details/gtgvmgqezz.html

public function __construct(private int $id) {}
来源：http://dali.jqgfzy.top/Article/details/gtdiarmbug.html

[U51] PHP：数组解构
来源：http://dali.chenjidiqi.icu/Article/details/gtdehvqpjd.html

[$a, $b] = $arr;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttunnjduc.html

[U52] PHP：箭头函数
来源：http://dali.iojbl.cn/Article/details/gtwninbnaz.html

$double = fn($x) => $x * 2;
来源：http://dali.redwolf501.top/Article/details/gtzpocguuc.html

[U53] PHP：空合并运算符
来源：http://dali.guowangkeji.top/Article/details/gtahzzotsh.html

$v = $a ?? $b ?? "default";
来源：http://dali.jianghu66.top/Article/details/gtaazzlcsg.html

[U54] PHP：空安全调用
来源：http://dali.feifeiyinyue.top/Article/details/gtdrgoafrm.html

$obj?->method()
来源：http://dali.ydzc1.top/Article/details/gtcqadojdz.html

[U55] PHP：match 表达式
来源：http://dali.yueranfly.top/Article/details/gtkurnojhx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gtyrygzsnv.html

[U56] PHP：命名参数
来源：http://dali.guannengcc.top/Article/details/gtwqebhkeb.html

f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtmwizeutp.html

[U57] PHP：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtemvamqui.html

"值: {$a}"
来源：http://dali.jyoumei.cn/Article/details/gtaajgiobe.html

[U58] PHP：数组三件套
来源：http://dali.fengsongda.top/Article/details/gtgpacsmae.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtgouwfgjr.html

[U59] PHP：自定义排序
来源：http://dali.ppjwa.cn/Article/details/gtbbdcnfew.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gtrohfuudm.html

[U60] PHP：JSON 编解码
来源：http://dali.pengpengdd.cyou/Article/details/gtbzwwuydr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gzhubu.top/Article/details/gtoyauqcwq.html

[U61] PHP：正则
来源：http://dali.guannengcc.top/Article/details/gtccxojmeg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gtnwplorqa.html

[U62] PHP：日期对象
来源：http://dali.meibo888.top/Article/details/gtbbkdpice.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.316326.xyz/Article/details/gtcvmgodvu.html

[U63] PHP：文件读写
来源：http://dali.ivvv.top/Article/details/gtfnjyyhed.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.aizwys.cn/Article/details/gtlqsgzjny.html

[U64] PHP：目录遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtwsxynhtl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jianghu66.top/Article/details/gtunjcknwz.html

[U65] PHP：会话
来源：http://dali.jqgufenzy.top/Article/details/gtmgexciea.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cheryme.top/Article/details/gtrqzjolgo.html

[U66] PHP：设置 Cookie
来源：http://dali.vqdsnc.cn/Article/details/gtotcsgbwa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhengqikj.top/Article/details/gtnnlfzjhb.html

[U67] PHP：处理文件上传
来源：http://dali.smart0.xyz/Article/details/gtdqkhlakz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ppjwa.cn/Article/details/gtmrfhphnd.html

[U68] PHP：PDO 连接
来源：http://dali.zycfv.cn/Article/details/gteuaoojag.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ybcxt.top/Article/details/gtssyewiev.html

[U69] PHP：PDO 预处理
来源：http://dali.cucudq.cn/Article/details/gtfpgfrmva.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.smart0.xyz/Article/details/gtzcsstcha.html

[U70] PHP：PDO 事务
来源：http://dali.aibaodan.cn/Article/details/gtpzogyaff.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gaohongyu789.top/Article/details/gtqqybihxi.html

[U71] PHP：抛出异常
来源：http://dali.shuidangran.top/Article/details/gtfxygkgjv.html

throw new RuntimeException("失败", 500);
来源：http://dali.fzhhl.top/Article/details/gtszmywlry.html

[U72] PHP：写错误日志
来源：http://dali.zhongyouzk.top/Article/details/gthhasrlrd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.smart0.xyz/Article/details/gtlxlcsdng.html

[U73] PHP：读取 ini 配置
来源：http://dali.tian-w.cn/Article/details/gtyfeazkdc.html

parse_ini_file("config.ini", true)
来源：http://dali.haohaochexian.top/Article/details/gtvoyhawpd.html

[U74] PHP：读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabqvxpes.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ybcxt.top/Article/details/gtoriyjeeo.html

[U75] PHP：依赖注入
来源：http://dali.chenlongwang.top/Article/details/gtpjdirpcd.html

composer require psr/container
来源：http://dali.wangdashe.top/Article/details/gtgajcsjta.html

[U76] PHP：简单路由
来源：http://dali.xuanzx.com/Article/details/gtqmwqsvsi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hammf.cn/Article/details/gtlmxgojgs.html

[U77] PHP：模板渲染
来源：http://dali.sysykeji.top/Article/details/gtjzjeekjb.html

composer require twig/twig
来源：http://dali.yuxming.cn/Article/details/gtvgsgzjni.html

[U78] PHP：单元测试
来源：http://dali.ehwqpu.com/Article/details/gtfwtwdzvq.html

composer require --dev phpunit/phpunit
来源：http://dali.hongshengwenyu.top/Article/details/gtrsefgpao.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmsdkgmi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmedczno.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigufen.top/Article/details/gtcvndeyfb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangdashe.top/Article/details/gtmzxnonsb.html

[U81] JS：初始化项目
来源：http://dali.gogol.net.cn/Article/details/gtjryzgacd.html

npm init -y;  npm i express
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzncstix.html

[U82] JS：package.json 脚本
来源：http://dali.xylfe.cn/Article/details/gtdxrrtwwi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hongshengwenyu.top/Article/details/gtussmtoor.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxinkj.top/Article/details/gtlxpqtpvo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gtoutgwwbu.html

[U84] JS：CommonJS 写法
来源：http://dali.xuetiantiany.cn/Article/details/gtacmbchor.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.havefunace.top/Article/details/gtohevklvc.html

[U85] JS：可选链
来源：http://dali.zdqjudy.top/Article/details/gtvembyktf.html

a?.b?.c
来源：http://dali.cucudq.cn/Article/details/gtvsxuuyfw.html

[U86] JS：空值合并
来源：http://dali.9152youxi.cn/Article/details/gtkhfyhcxk.html

a ?? b
来源：http://dali.birdmap.top/Article/details/gtxskrpctv.html

[U87] JS：解构默认值
来源：http://dali.jyoumei.cn/Article/details/gtwsjoucjx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.birdmap.top/Article/details/gtkxaykrci.html

[U88] JS：对象展开合并
来源：http://dali.tian-w.cn/Article/details/gtdfylhxjv.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehcsidsx.html

[U89] JS：数组去重
来源：http://dali.0kj1m.cn/Article/details/gtxdhdnmuu.html

[...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtmrktnlgv.html

[U90] JS：数字数组排序
来源：http://dali.aizwys.cn/Article/details/gtydfnksvv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtkehsdhpu.html

[U91] JS：对象键值遍历
来源：http://dali.yuanzhike.top/Article/details/gtcotibmbl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258888.top/Article/details/gtbkmpgvof.html

[U92] JS：深拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlslplfta.html

structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtssrgkokn.html

[U93] JS：模板字符串
来源：http://dali.xuanzx.com/Article/details/gtnsbtcxrf.html

`共 ${n} 条`
来源：http://dali.yj20258888.top/Article/details/gtaroofbni.html

[U94] JS：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gtjeabujnx.html

const double = x => x * 2;
来源：http://dali.bjfxy.top/Article/details/gtlytqybqr.html

[U95] JS：Promise 包装
来源：http://dali.zycfv.cn/Article/details/gtgqxxeoxv.html

new Promise((resolve, reject) => {})
来源：http://dali.dianchejie.cn/Article/details/gtyeijpdoh.html

[U96] JS：async/await 与异常
来源：http://dali.meibo888.top/Article/details/gtebqldpuv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtsfmrsqfp.html

[U97] JS：并发请求
来源：http://dali.guannengcc.top/Article/details/gtwajgazsn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtlqcpszzi.html

[U98] JS：fetch 带 JSON
来源：http://dali.yangfankeji.com/Article/details/gtxzavbikg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgufenzy.top/Article/details/gtsmktedag.html

[U99] JS：事件监听
来源：http://dali.wangshuangyany.cn/Article/details/gtjhomsbey.html

el.addEventListener("click", e => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjusxlby.html

[U100] JS：DOM 查询
来源：http://dali.yanxiufei.cn/Article/details/gtzhuefsar.html

document.querySelector(".item")
来源：http://dali.smart0.xyz/Article/details/gtotbgehye.html

[U101] JS：classList 操作
来源：http://dali.xylfe.cn/Article/details/gtoxydguaa.html

el.classList.toggle("active")
来源：http://dali.zhengqikj.top/Article/details/gtdowwuoyx.html

[U102] JS：本地存储
来源：http://dali.chenlongwang.top/Article/details/gtezcmqfdw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gtewfpziqo.html

[U103] JS：定时器
来源：http://dali.ivvv.top/Article/details/gtfdncziif.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.guowangkeji.top/Article/details/gtluxarlvd.html

[U104] JS：防抖
来源：http://dali.0kj1m.cn/Article/details/gtgejpqdhf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtiavzvtki.html

[U105] JS：节流
来源：http://dali.cucudq.cn/Article/details/gtzcdiwbft.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ehwqpu.com/Article/details/gtivbtedhq.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtuccexacn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jianghu66.top/Article/details/gtsuoojbmp.html

[U107] JS：数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtodxarhll.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gtoaqzhkwu.html

[U108] JS：随机整数
来源：http://dali.yuxming.cn/Article/details/gtmcthdlxx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gtnizceifi.html

[U109] JS：数组分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixwakzhu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtjlvzzxod.html

[U110] JS：数组分块
来源：http://dali.gzhubu.top/Article/details/gtpkkjfpaw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzyzowbu.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gtzzpwessg.html

new Map(Object.entries(obj))
来源：http://dali.yj202588.top/Article/details/gtigcoqyih.html

[U112] JS：字符串补位
来源：http://dali.hysaishi.cn/Article/details/gtgowbpyfj.html

"7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtrkdmpzql.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gtyffjlstk.html

s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtovcbbrlf.html

[U114] JS：JSON 深比较
来源：http://dali.guowangkeji.top/Article/details/gttihvrrtq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqhusqlm.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtwtcmopcj.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtmsdyjwol.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aibaodan.cn/Article/details/gtaqnndiao.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cqqwz.cn/Article/details/gtvfcjxmrc.html

[U117] JS：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtslayfizi.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gtljipnmnm.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gtzfsbgpvo.html

npm i -D vite;  npx vite
来源：http://dali.sufxvd.cn/Article/details/gtsxbylmkd.html

[U119] JS：生产构建
来源：http://dali.xylfe.cn/Article/details/gtcjgjhjmd.html

npx vite build
来源：http://dali.gzhubu.top/Article/details/gtjiokzzms.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shzxlz.cn/Article/details/gtxfnqzfnq.html

import.meta.env.VITE_API_URL
来源：http://dali.svipenyu.cn/Article/details/gtvmcamvnf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwrsmslya.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gtefspeike.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtncdaxyow.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gtwnvlhxkn.html

Python ......... 252
来源：http://dali.jyoumei.cn/Article/details/gtjuyluqgp.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtedhlrwaa.html

JavaScript ..... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtduoiehge.html

TypeScript ..... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtmxregzec.html

Java ........... 212
来源：http://dali.hysaishi.cn/Article/details/gtmmasfwzw.html

Go ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gtusqgdhsq.html

Ruby ........... 212
来源：http://dali.yongpay.top/Article/details/gtmyrhgtpw.html

C# ............. 212
来源：http://dali.ehwqpu.com/Article/details/gtwqwjbdmg.html

C .............. 30
来源：http://dali.nanxuanxn.top/Article/details/gtgovqokno.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gtzootrpbr.html

SQL ............ 90
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpsrwiee.html

Bash ........... 80
来源：http://dali.shuidangran.top/Article/details/gtnzdpfgea.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gtqwkqkwug.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gtgkpxndcz.html

Lua ............ 10
来源：http://dali.sysykeji.top/Article/details/gtcozzphjj.html

Perl ........... 10
来源：http://dali.jinqigufen.top/Article/details/gtnglqgemv.html

Scala .......... 10
来源：http://dali.ivvv.top/Article/details/gtskpanoqs.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gtilxpsuly.html

合计 ........... 2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmhmaquq.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtzmsrjmhb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gtqkzlviie.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtlubidksr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gtscnnylkw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gthwkfdgsy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.birdmap.top/Article/details/gtapqafnux.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinqigufen.top/Article/details/gtqcrhwdlp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtvuyqygqg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtenezkrwe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtmjodxaeq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtfwhaoqro.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtwiebvagk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtwsqvvxtu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtaeszlceb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nwbrower.top/Article/details/gteciwknvu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xziqi.cn/Article/details/gtrfsrmrrp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtdgvjfink.html

Q SQL 专题                              90
来源：http://dali.gzhubu.top/Article/details/gtpsytkbqn.html

R Bash 专题                             80
来源：http://dali.iojbl.cn/Article/details/gtbtsnstbe.html

S C / C++ 专题                          60
来源：http://dali.aizwys.cn/Article/details/gthxznvaxd.html

T 其他语言补充                          60
来源：http://dali.jiagoushi.top/Article/details/gthzuyuzgt.html

U 高频实用片段                         120
来源：http://dali.zhengqikj.top/Article/details/gtaoaforvo.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtqklelbxp.html

合计                                  2106 条
来源：http://dali.dianchejie.cn/Article/details/gtpttnpduu.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtbnnwkbbf.html

使用提醒
来源：http://dali.quarkkingdee.top/Article/details/gtgalrmxcr.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtyijmywoc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dashuyun.cn/Article/details/gtngowegxj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yj202588.top/Article/details/gtxjlqpmmw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cucudq.cn/Article/details/gtxivaqzzt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.svipenyu.cn/Article/details/gtyyhgbcsq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shangyingyoupin.top/Article/details/gtewaefkua.html

—— 文件结束 ——
来源：http://dali.shangyingyoupin.top/Article/details/gtisommvfq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrmspzimn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.snrcjt.cn/Article/details/gttkzhkwlv.html

Common Programming Examples Cheat Book
来源：http://dali.aizwys.cn/Article/details/gtznilsedv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwljoifkb.html

【收录内容】
来源：http://dali.zhixingplan.top/Article/details/gtrkofqjcx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqugmowk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gtngcdnfeh.html

SQL · Bash · C · C++
来源：http://dali.guowangkeji.top/Article/details/gtjjrrsnud.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jyoumei.cn/Article/details/gthibiceqe.html

【使用说明】
来源：http://dali.nwbrower.top/Article/details/gtxjwbjada.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccpsontq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ehwqpu.com/Article/details/gtwjlblvxm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinqigfzy.top/Article/details/gtpdxcxeaq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aibaodan.cn/Article/details/gttxyqdyun.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnqzz.top/Article/details/gtxrfpdrum.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.9152youxi.cn/Article/details/gtebsmnrth.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xziqi.cn/Article/details/gtgjevltks.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tanke756.top/Article/details/gtnxeggemq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sysykeji.top/Article/details/gtmkfklpex.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jyoumei.cn/Article/details/gtsqxyxlbn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sweek.top/Article/details/gtsyfjugow.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gzhubu.top/Article/details/gtymebcyxs.html

【文件统计】
来源：http://dali.jinqigfzy.top/Article/details/gtszxkbvpu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.snrcjt.cn/Article/details/gtjfkhwfxb.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtsostubnh.html

目  录
来源：http://dali.havefunace.top/Article/details/gtdqqqxqsz.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtfcrznswv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sxryk.cn/Article/details/gtrpyxeoci.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gtnwspypch.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtefmqhxfz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gtojmxliet.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.iojbl.cn/Article/details/gtuifzwgyq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gtsuuvjsgh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtkxboynml.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaeycoau.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtfcwfqjwf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gtauurzoau.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtcwpmsicy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtoyokivmk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtaysfyslj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gtunwojtdc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.mhx1999.top/Article/details/gtjqznoxvb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gttuqvmani.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmpmsplz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pycfn.com/Article/details/gtsvzoeiuy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.quarkkingdee.top/Article/details/gtikxwqtzw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gtgjesklxd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtxdkvfvhd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtuybducgt.html

A. 基础语法与类型
来源：http://dali.chenjidiqi.icu/Article/details/gtjbvblghg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdelkztmz.html

[A01] Hello World
来源：http://dali.zhixingplan.top/Article/details/gthkdcjler.html

Py:   print("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtzvrlfqpq.html

PHP:  echo "Hello, World!";
来源：http://dali.svipenyu.cn/Article/details/gtvnfwhrbo.html

JS:   console.log("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gtrekbnzxg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.fzhhl.top/Article/details/gtnorexpfd.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdulxuoe.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gtvacglqjs.html

Ruby: puts "Hello, World!"
来源：http://dali.haohaochexian.top/Article/details/gtxpknqqrh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gtakjdwejv.html

[A02] 变量声明与赋值
来源：http://dali.zhiwuduotai.top/Article/details/gtizjmocai.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.vqdsnc.cn/Article/details/gtlcumlcmz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zycfv.cn/Article/details/gtlbkvldbq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.wangdashe.top/Article/details/gttlzencep.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.aizwys.cn/Article/details/gtznlmzipx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtkcxboczs.html

Go:   name := "Alex"; age := 20
来源：http://dali.yonumen.top/Article/details/gtstsuxqls.html

Ruby: name = "Alex"; age = 20
来源：http://dali.iojbl.cn/Article/details/gtznpxojax.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtxftjxfud.html

[A03] 常量定义
来源：http://dali.guowangkeji.top/Article/details/gthjxdqyzu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hywenlv.cn/Article/details/gtiwvesgpk.html

PHP:  const PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtizlhjxil.html

JS:   const PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtdivwkrlp.html

TS:   const PI: number = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtkslgxyle.html

Java: static final double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtjvurytqj.html

Go:   const PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gtdnxfttwm.html

Ruby: PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gtapqjoixi.html

C#:   const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtmqtqkvqx.html

[A04] 判断变量类型
来源：http://dali.pycfn.com/Article/details/gtjdprkoge.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hongshengwenyu.top/Article/details/gtuzblafki.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzedxaaio.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gtftvwxtbe.html

TS:   typeof x; x instanceof Date
来源：http://dali.316326.xyz/Article/details/gtecdmjgfz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yanxiufei.cn/Article/details/gtlxxrrcah.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuanzx.com/Article/details/gtqsydwnxt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guannengcc.top/Article/details/gtxexyrvfa.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhiwuduotai.top/Article/details/gtolduaohs.html

[A05] 整数除法与取模
来源：http://dali.jqgfzy.top/Article/details/gtwyhagpwl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yueranfly.top/Article/details/gtusczkoyb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcwarugj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gttszbtfbu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtwywpsnuc.html


<!-- 参考信息 -->