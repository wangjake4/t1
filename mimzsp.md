代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.jinqigfzy.top/Article/details/gt2dwutpcrs.html

namespace App\Http;
来源：http://dali.andypj.xyz/Article/details/gt2nsfuszkb.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gt2ismcgzza.html

declare(strict_types=1);
来源：http://dali.aizwys.cn/Article/details/gt2uonlqdlv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2iozzuqsj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2ankqtcdn.html

[U46] PHP：可空类型
来源：http://dali.tanke756.top/Article/details/gt2pcmupekp.html

?string $name = null
来源：http://dali.birdmap.top/Article/details/gt2ywhjueqq.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gt2jykwesdy.html

int|string $id
来源：http://dali.xziqi.cn/Article/details/gt2yjpopscr.html

[U48] PHP：纯枚举
来源：http://dali.jqgfzy.top/Article/details/gt2jxsamuvz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dashuyun.cn/Article/details/gt2tiqaglgs.html

[U49] PHP：只读属性
来源：http://dali.yanxiufei.cn/Article/details/gt2xnzpczhv.html

public readonly string $name
来源：http://dali.snrcjt.cn/Article/details/gt2hvquixbg.html

[U50] PHP：构造器属性提升
来源：http://dali.gotoacloud.top/Article/details/gt2yyjzmqkd.html

public function __construct(private int $id) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgivdipe.html

[U51] PHP：数组解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2jimwvomu.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gt2lwrevvfq.html

[U52] PHP：箭头函数
来源：http://dali.xziqi.cn/Article/details/gt2hndlfsth.html

$double = fn($x) => $x * 2;
来源：http://dali.zdqjudy.top/Article/details/gt2hqbniefp.html

[U53] PHP：空合并运算符
来源：http://dali.xylfe.cn/Article/details/gt2hylehtip.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhiwuduotai.top/Article/details/gt2manhggbq.html

[U54] PHP：空安全调用
来源：http://dali.svipenyu.cn/Article/details/gt2wbhvpmxh.html

$obj?->method()
来源：http://dali.sxryk.cn/Article/details/gt2twqzbktz.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtthrupn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gt2rakxhvxq.html

[U56] PHP：命名参数
来源：http://dali.yuxming.cn/Article/details/gt2errkakmr.html

f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2ftjoxebl.html

[U57] PHP：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpchgflv.html

"值: {$a}"
来源：http://dali.cdnleiting.top/Article/details/gt2vyusnqdg.html

[U58] PHP：数组三件套
来源：http://dali.hfpthk.cn/Article/details/gt2qkxvdodg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2mvfiawqu.html

[U59] PHP：自定义排序
来源：http://dali.cheryme.top/Article/details/gt2vrzqinel.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gt2udjjhdei.html

[U60] PHP：JSON 编解码
来源：http://dali.fengsongda.top/Article/details/gt2haaflhar.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2btdhwoxa.html

[U61] PHP：正则
来源：http://dali.jqgufenzy.top/Article/details/gt2wthlkqzr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gt2ekpdniqk.html

[U62] PHP：日期对象
来源：http://dali.chenzaomai.com/Article/details/gt2nnlmmdui.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gt2yxzhijkq.html

[U63] PHP：文件读写
来源：http://dali.xylfe.cn/Article/details/gt2iwwrotpr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgfzy.top/Article/details/gt2wkrkgoxq.html

[U64] PHP：目录遍历
来源：http://dali.cucudq.cn/Article/details/gt2ugkarway.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jlsjyb.cn/Article/details/gt2awpqqfek.html

[U65] PHP：会话
来源：http://dali.quarkkingdee.top/Article/details/gt2wekxtype.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2lwgjorru.html

[U66] PHP：设置 Cookie
来源：http://dali.zhoulong.xyz/Article/details/gt2chsosswe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj20258.top/Article/details/gt2rdvfcguj.html

[U67] PHP：处理文件上传
来源：http://dali.gaohongyu789.top/Article/details/gt2sxjrlcic.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhixingplan.top/Article/details/gt2dgjurive.html

[U68] PHP：PDO 连接
来源：http://dali.meibo888.top/Article/details/gt2xctumtob.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hongshengwenyu.top/Article/details/gt2kyfvlopx.html

[U69] PHP：PDO 预处理
来源：http://dali.dashuyun.cn/Article/details/gt2cjybpqus.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgufenzy.top/Article/details/gt2towgomiv.html

[U70] PHP：PDO 事务
来源：http://dali.ydzc1.top/Article/details/gt2kwxokkhm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.c1oappe.top/Article/details/gt2fpxkbgrw.html

[U71] PHP：抛出异常
来源：http://dali.xylfe.cn/Article/details/gt2vpthtlbd.html

throw new RuntimeException("失败", 500);
来源：http://dali.birdmap.top/Article/details/gt2wtkmyyjm.html

[U72] PHP：写错误日志
来源：http://dali.yj20258888.top/Article/details/gt2gxegmftp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.bjfxy.top/Article/details/gt2zrpeyczf.html

[U73] PHP：读取 ini 配置
来源：http://dali.tanke756.top/Article/details/gt2xyurcdck.html

parse_ini_file("config.ini", true)
来源：http://dali.redwolf501.top/Article/details/gt2opvhntch.html

[U74] PHP：读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2sfbjfpne.html

getenv("APP_ENV") ?: "production"
来源：http://dali.iojbl.cn/Article/details/gt2brgygzde.html

[U75] PHP：依赖注入
来源：http://dali.c1oappe.top/Article/details/gt2tbtsaanj.html

composer require psr/container
来源：http://dali.andypj.xyz/Article/details/gt2nkrtomaf.html

[U76] PHP：简单路由
来源：http://dali.iojbl.cn/Article/details/gt2oqekkpmn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cityyuon.html

[U77] PHP：模板渲染
来源：http://dali.haohaochexian.top/Article/details/gt2smisnhom.html

composer require twig/twig
来源：http://dali.316326.xyz/Article/details/gt2uhfapbwk.html

[U78] PHP：单元测试
来源：http://dali.0kj1m.cn/Article/details/gt2lonsuajz.html

composer require --dev phpunit/phpunit
来源：http://dali.birdmap.top/Article/details/gt2bbgniwvq.html

[U79] PHP：静态分析
来源：http://dali.nanxuanxn.top/Article/details/gt2hgdfhtkh.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gt2kcuorwud.html

[U80] PHP：代码规范修复
来源：http://dali.ybcxt.top/Article/details/gt2vefsbsnh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhoulong.xyz/Article/details/gt2xulnrgsb.html

[U81] JS：初始化项目
来源：http://dali.birdmap.top/Article/details/gt2uuahbilp.html

npm init -y;  npm i express
来源：http://dali.tianlin.xyz/Article/details/gt2ohpuldbm.html

[U82] JS：package.json 脚本
来源：http://dali.nwbrower.top/Article/details/gt2rckucfsk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ybcxt.top/Article/details/gt2nvcvcicb.html

[U83] JS：ES Module 导入导出
来源：http://dali.cheryme.top/Article/details/gt2bettcnyp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gt2dipfjuxd.html

[U84] JS：CommonJS 写法
来源：http://dali.chenlongwang.top/Article/details/gt2flajocxj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgfzy.top/Article/details/gt2lhrbltqj.html

[U85] JS：可选链
来源：http://dali.cqqwz.cn/Article/details/gt2utwaxlow.html

a?.b?.c
来源：http://dali.snrcjt.cn/Article/details/gt2htqzsvkt.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gt2eqsvbrtc.html

a ?? b
来源：http://dali.birdmap.top/Article/details/gt2jgbhbolx.html

[U87] JS：解构默认值
来源：http://dali.hywenlv.cn/Article/details/gt2fmcctjtd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yueranfly.top/Article/details/gt2hrnqmufd.html

[U88] JS：对象展开合并
来源：http://dali.sxryk.cn/Article/details/gt2ghefwkvo.html

{ ...a, ...b }
来源：http://dali.jinqigufen.top/Article/details/gt2dtkifxfa.html

[U89] JS：数组去重
来源：http://dali.zhixingplan.top/Article/details/gt2voqainre.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2usvznbll.html

[U90] JS：数字数组排序
来源：http://dali.guannengcc.top/Article/details/gt2wnqlfeyp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gt2acevvlty.html

[U91] JS：对象键值遍历
来源：http://dali.fzhhl.top/Article/details/gt2ghdqkjug.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.haohaochexian.top/Article/details/gt2zyidlfha.html

[U92] JS：深拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxzsvkku.html

structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2netaayoe.html

[U93] JS：模板字符串
来源：http://dali.c1oappe.top/Article/details/gt2ohdjjlnr.html

`共 ${n} 条`
来源：http://dali.fzhhl.top/Article/details/gt2qyoxtchf.html

[U94] JS：箭头函数
来源：http://dali.andypj.xyz/Article/details/gt2dunrhimk.html

const double = x => x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gt2imviycht.html

[U95] JS：Promise 包装
来源：http://dali.yvedp.cn/Article/details/gt2rtqrawpg.html

new Promise((resolve, reject) => {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjjqiutn.html

[U96] JS：async/await 与异常
来源：http://dali.ivvv.top/Article/details/gt2sjmtfrkg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2pbbuxzga.html

[U97] JS：并发请求
来源：http://dali.xziqi.cn/Article/details/gt2erndklas.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2ivmelcez.html

[U98] JS：fetch 带 JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2pbuipwck.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgfzy.top/Article/details/gt2mfwrwlpr.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbdafeae.html

el.addEventListener("click", e => {})
来源：http://dali.zhiwuduotai.top/Article/details/gt2bafxzerg.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gt2mdzqvqdf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jflxfwwu.html

[U101] JS：classList 操作
来源：http://dali.chenlongwang.top/Article/details/gt2emgdinal.html

el.classList.toggle("active")
来源：http://dali.chenzaomai.com/Article/details/gt2cjxutdfr.html

[U102] JS：本地存储
来源：http://dali.yongpay.top/Article/details/gt2qxwdlwhi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.meibo888.top/Article/details/gt2oubfxieh.html

[U103] JS：定时器
来源：http://dali.zycfv.cn/Article/details/gt2owgoyklh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnqzz.top/Article/details/gt2tgjguxoj.html

[U104] JS：防抖
来源：http://dali.yangfankeji.com/Article/details/gt2rfhpnlhr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2jwvatcrk.html

[U105] JS：节流
来源：http://dali.chenlongwang.top/Article/details/gt2njvyswbk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.birdmap.top/Article/details/gt2iyhuiypd.html

[U106] JS：日期格式化
来源：http://dali.fengsongda.top/Article/details/gt2evjnbxqd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daria6918.cn/Article/details/gt2mqrscbqc.html

[U107] JS：数字千分位
来源：http://dali.snrcjt.cn/Article/details/gt2medbildg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gt2clwmnfrt.html

[U108] JS：随机整数
来源：http://dali.havefunace.top/Article/details/gt2cwtfqngv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shangyingyoupin.top/Article/details/gt2fovlxxgc.html

[U109] JS：数组分组
来源：http://dali.xinyue.icu/Article/details/gt2sjotvqoz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gt2savscjtn.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gt2dtffiwik.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gaohongyu789.top/Article/details/gt2qcntrkys.html

[U111] JS：对象转 Map
来源：http://dali.ehwqpu.com/Article/details/gt2mjrudvwu.html

new Map(Object.entries(obj))
来源：http://dali.aibaodan.cn/Article/details/gt2dprmaoct.html

[U112] JS：字符串补位
来源：http://dali.fzhhl.top/Article/details/gt2pllkoqtt.html

"7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gt2yhkkkndi.html

[U113] JS：正则替换全部
来源：http://dali.yueranfly.top/Article/details/gt2zlvwdkyo.html

s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2clwuaocf.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gt2vphwzzon.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2fjaaosrm.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gt2sbrwxhyb.html

crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxwpkbjf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hysaishi.cn/Article/details/gt2yubkrmeo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2yolkhnaz.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxkzpbhj.html

npm i -D vitest;  npx vitest
来源：http://dali.fzhhl.top/Article/details/gt2rtsesxis.html

[U118] JS：开发服务器
来源：http://dali.gzhubu.top/Article/details/gt2nqwkhxjb.html

npm i -D vite;  npx vite
来源：http://dali.ydzc1.top/Article/details/gt2gixbjwzi.html

[U119] JS：生产构建
来源：http://dali.havefunace.top/Article/details/gt2bwidbihy.html

npx vite build
来源：http://dali.chenzaomai.com/Article/details/gt2ttqavecs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tianlin.xyz/Article/details/gt2pqooggfo.html

import.meta.env.VITE_API_URL
来源：http://dali.yuxming.cn/Article/details/gt2tquzpvrg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2mqeyanac.html

统计汇总
来源：http://dali.guannengcc.top/Article/details/gt2ezqexvpx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2sbdrkqns.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gt2eaocgxdk.html

Python ......... 252
来源：http://dali.zycfv.cn/Article/details/gt2joibpjgw.html

PHP ............ 252
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phxltyjp.html

JavaScript ..... 252
来源：http://dali.shuidangran.top/Article/details/gt2xexmdant.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gt2rvufmrpm.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gt2ytrvbzvn.html

Go ............. 212
来源：http://dali.jqgfzy.top/Article/details/gt2nbyujyug.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gt2seusnwnk.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gt2ambaiiip.html

C .............. 30
来源：http://dali.zhengqikj.top/Article/details/gt2gtfkfana.html

C++ ............ 30
来源：http://dali.shzxlz.cn/Article/details/gt2nnwodwix.html

SQL ............ 90
来源：http://dali.zhongyouzk.top/Article/details/gt2zsgpenue.html

Bash ........... 80
来源：http://dali.bjfxy.top/Article/details/gt2kzwascpu.html

Kotlin ......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gt2vsmalzcj.html

Swift .......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gt2khzaldzc.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gt2bpmtthzm.html

Perl ........... 10
来源：http://dali.aizwys.cn/Article/details/gt2hnwajbru.html

Scala .......... 10
来源：http://dali.zdqjudy.top/Article/details/gt2dmkyecqz.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2mfkvgemd.html

合计 ........... 2106 条
来源：http://dali.jiagoushi.top/Article/details/gt2wsnvgiia.html

按章节统计：
来源：http://dali.tanke756.top/Article/details/gt2oikypwms.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gt2xuiqksrn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gt2xvtjnikb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gt2ccjgeboj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.pycfn.com/Article/details/gt2wnsryjby.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxinkj.top/Article/details/gt2vytaoqxj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gt2esjouilr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcbfprfq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gt2paoqebrq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2celggjrz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zycfv.cn/Article/details/gt2igpxtdfb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gt2wvsxwubw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2rczfocae.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2ztwbklxk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gt2uxptphbh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zdqjudy.top/Article/details/gt2psduxejy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2vjykzker.html

Q SQL 专题                              90
来源：http://dali.xylfe.cn/Article/details/gt2tehntyjn.html

R Bash 专题                             80
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwkbvfhg.html

S C / C++ 专题                          60
来源：http://dali.jianghu66.top/Article/details/gt2qqokoian.html

T 其他语言补充                          60
来源：http://dali.aibaodan.cn/Article/details/gt2usrhnxes.html

U 高频实用片段                         120
来源：http://dali.zhiwuduotai.top/Article/details/gt2boyexmqu.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2qzrnlcpj.html

合计                                  2106 条
来源：http://dali.zdqjudy.top/Article/details/gt2kprivozk.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2smanrjbb.html

使用提醒
来源：http://dali.dianchejie.cn/Article/details/gt2tfhdyldo.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpydhcky.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.vqdsnc.cn/Article/details/gt2laiatcej.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hammf.cn/Article/details/gt2ctcbbcmu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jyoumei.cn/Article/details/gt2gpozeycb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhengqikj.top/Article/details/gt2fwimaion.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gt2kbosylgh.html

—— 文件结束 ——
来源：http://dali.bjfxy.top/Article/details/gt2obvfvkzw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ooeegupg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hnqzz.top/Article/details/gt2bdjqkbmf.html

Common Programming Examples Cheat Book
来源：http://dali.shuidangran.top/Article/details/gt2dimrwkeo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2lxakycmp.html

【收录内容】
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejbcuuiw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuanzx.com/Article/details/gt2szywwbsm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.svipenyu.cn/Article/details/gt2jkonmmqb.html

SQL · Bash · C · C++
来源：http://dali.jinqigufen.top/Article/details/gt2gixhkake.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xziqi.cn/Article/details/gt2exhmiglw.html

【使用说明】
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2remhdxnd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tanke756.top/Article/details/gt2yevvckfm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shzxlz.cn/Article/details/gt2qtcqnwrg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pengpengdd.cyou/Article/details/gt2ryrgulub.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sxryk.cn/Article/details/gt2zijmoteg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.smart0.xyz/Article/details/gt2zvelmsvs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yongpay.top/Article/details/gt2fkdibiya.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.haohaochexian.top/Article/details/gt2xjbovieo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdnneoqd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rucqjsbs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yuxming.cn/Article/details/gt2fxekxlcg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ydzc1.top/Article/details/gt2ayukmpie.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shuidangran.top/Article/details/gt2mxymtrth.html

【文件统计】
来源：http://dali.xuanzx.com/Article/details/gt2sqvwpdhq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.vqdsnc.cn/Article/details/gt2jockluab.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2czjfqzso.html

目  录
来源：http://dali.yj20258.top/Article/details/gt2uahbemdy.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2ofpyufyx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2qlomxxfz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2kiwmmzmz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gt2zkrcporv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gt2rcuiyhlk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yonumen.top/Article/details/gt2fnxopkqw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gt2szlpzbnq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gt2vmntkynl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gt2uazgtntp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gt2ljpxnwew.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xinyue.icu/Article/details/gt2fijsrpld.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2romwwohl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gt2bwjzzuyp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gt2ckhuviud.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nwbrower.top/Article/details/gt2sarkzulh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzbksldu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gt2qeyicojc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ziyzuqjv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pycfn.com/Article/details/gt2yubuhimm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.0kj1m.cn/Article/details/gt2ofpkoiod.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gt2mgagcoqk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2dtipkjgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyewrnew.html

A. 基础语法与类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2pytztqlc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyfytfny.html

[A01] Hello World
来源：http://dali.cashguo.top/Article/details/gt2tmntilky.html

Py:   print("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gt2hvbspazi.html

PHP:  echo "Hello, World!";
来源：http://dali.gogol.net.cn/Article/details/gt2wyuluymp.html

JS:   console.log("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gt2orvwzvjz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.vqdsnc.cn/Article/details/gt2tbbgrurz.html

Java: System.out.println("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gt2jczfbova.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehaeteft.html

Ruby: puts "Hello, World!"
来源：http://dali.ppjwa.cn/Article/details/gt2jjhymzrt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gt2rgrwpdmn.html

[A02] 变量声明与赋值
来源：http://dali.zycfv.cn/Article/details/gt2asiwbyex.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jqgfzy.top/Article/details/gt2bfmommvr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2xczvwqxg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zdqjudy.top/Article/details/gt2plleoxbd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2pvstyjqg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.pycfn.com/Article/details/gt2qemwjhlm.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mriqcyjq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jlsjyb.cn/Article/details/gt2zdwwjnzo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cqqwz.cn/Article/details/gt2nmnmrujt.html

[A03] 常量定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukpkhqmw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hysaishi.cn/Article/details/gt2rlulvvut.html

PHP:  const PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cogcclny.html

JS:   const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2wcxgcvrw.html

TS:   const PI: number = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2mdhkhyke.html

Java: static final double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2grwlelmi.html

Go:   const PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gt2hpnbukpn.html

Ruby: PI = 3.14159
来源：http://dali.iojbl.cn/Article/details/gt2ffmcwphn.html

C#:   const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2xfdsorpr.html

[A04] 判断变量类型
来源：http://dali.zhongyouzk.top/Article/details/gt2naobyrgv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hfpthk.cn/Article/details/gt2bbkfkqdh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ivvv.top/Article/details/gt2cghvihlb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dashuyun.cn/Article/details/gt2aggaqabp.html

TS:   typeof x; x instanceof Date
来源：http://dali.hysaishi.cn/Article/details/gt2ttykafqi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnitcrtc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nanxuanxn.top/Article/details/gt2uxzgrwja.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhongyouzk.top/Article/details/gt2tjeqsszi.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsbivpgc.html

[A05] 整数除法与取模
来源：http://dali.aizwys.cn/Article/details/gt2bnggvdss.html


<!-- 参考信息 -->