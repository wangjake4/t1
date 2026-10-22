代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqpdjnrm.html

namespace App\Http;
来源：http://dali.cqqwz.cn/Article/details/gt2lqxhilhv.html

[U44] PHP：开启严格类型
来源：http://dali.aibaodan.cn/Article/details/gt2lglfxoyr.html

declare(strict_types=1);
来源：http://dali.jiagoushi.top/Article/details/gt2jzkuvatg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqklisiz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2lmiyngoo.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gt2eekmooie.html

?string $name = null
来源：http://dali.iojbl.cn/Article/details/gt2hmzlwoav.html

[U47] PHP：联合类型
来源：http://dali.haohaochexian.top/Article/details/gt2zhlqvboy.html

int|string $id
来源：http://dali.daxiang520.top/Article/details/gt2acbywqtb.html

[U48] PHP：纯枚举
来源：http://dali.iojbl.cn/Article/details/gt2vkgqjkrm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cdnleiting.top/Article/details/gt2llqypzof.html

[U49] PHP：只读属性
来源：http://dali.xuanzx.com/Article/details/gt2mzjxymnw.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gt2gygsmpwn.html

[U50] PHP：构造器属性提升
来源：http://dali.hysaishi.cn/Article/details/gt2yiiadywg.html

public function __construct(private int $id) {}
来源：http://dali.yongpay.top/Article/details/gt2zzsqeamk.html

[U51] PHP：数组解构
来源：http://dali.ehwqpu.com/Article/details/gt2sbblcywk.html

[$a, $b] = $arr;
来源：http://dali.chenlongwang.top/Article/details/gt2xfzcyjhi.html

[U52] PHP：箭头函数
来源：http://dali.zdqjudy.top/Article/details/gt2tmnpdtqh.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gt2cmbqxksx.html

[U53] PHP：空合并运算符
来源：http://dali.yueranfly.top/Article/details/gt2rkfhhhvh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhongyouzk.top/Article/details/gt2pqtfebcc.html

[U54] PHP：空安全调用
来源：http://dali.yuxming.cn/Article/details/gt2lqjttmxb.html

$obj?->method()
来源：http://dali.yvedp.cn/Article/details/gt2wjtuhkss.html

[U55] PHP：match 表达式
来源：http://dali.sufxvd.cn/Article/details/gt2jtkjwewe.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gt2herubsvl.html

[U56] PHP：命名参数
来源：http://dali.yongpay.top/Article/details/gt2rqzlmqyd.html

f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfbvkohk.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2haxvnuie.html

"值: {$a}"
来源：http://dali.yj20258.top/Article/details/gt2pledautk.html

[U58] PHP：数组三件套
来源：http://dali.9152youxi.cn/Article/details/gt2ihknmyka.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2yudxmnps.html

[U59] PHP：自定义排序
来源：http://dali.cucudq.cn/Article/details/gt2sjojmrad.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2akrrdouu.html

[U60] PHP：JSON 编解码
来源：http://dali.gzhubu.top/Article/details/gt2lzcesbdc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258.top/Article/details/gt2uwncealv.html

[U61] PHP：正则
来源：http://dali.yvedp.cn/Article/details/gt2lryucqtz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wylroksl.html

[U62] PHP：日期对象
来源：http://dali.jiagoushi.top/Article/details/gt2ltaksmzb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258.top/Article/details/gt2ogedwush.html

[U63] PHP：文件读写
来源：http://dali.hywenlv.cn/Article/details/gt2fcoczptg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhengqikj.top/Article/details/gt2chqaloju.html

[U64] PHP：目录遍历
来源：http://dali.yj20258888.top/Article/details/gt2uquldhqc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fengsongda.top/Article/details/gt2ssduljle.html

[U65] PHP：会话
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqdwepkw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2tmbdvcmy.html

[U66] PHP：设置 Cookie
来源：http://dali.ydzc1.top/Article/details/gt2srrrtyuq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2szfndtrm.html

[U67] PHP：处理文件上传
来源：http://dali.gotoacloud.top/Article/details/gt2qlsrkufm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guowangkeji.top/Article/details/gt2ptaouads.html

[U68] PHP：PDO 连接
来源：http://dali.yvedp.cn/Article/details/gt2owujvdbq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.feifeiyinyue.top/Article/details/gt2egwizloc.html

[U69] PHP：PDO 预处理
来源：http://dali.kuanghao11.cn/Article/details/gt2nvngkchm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhengqikj.top/Article/details/gt2apegnezt.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gt2vyhxprdt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpmekcjh.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrfmtkgk.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkzpawpo.html

[U72] PHP：写错误日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwvxqola.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258.top/Article/details/gt2sqzwtmfj.html

[U73] PHP：读取 ini 配置
来源：http://dali.aibaodan.cn/Article/details/gt2gbiilqwc.html

parse_ini_file("config.ini", true)
来源：http://dali.andypj.xyz/Article/details/gt2amwjpbca.html

[U74] PHP：读取环境变量
来源：http://dali.yonumen.top/Article/details/gt2ccwijluh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iomawppd.html

[U75] PHP：依赖注入
来源：http://dali.pycfn.com/Article/details/gt2vskcxeyr.html

composer require psr/container
来源：http://dali.shzxlz.cn/Article/details/gt2oacjizdw.html

[U76] PHP：简单路由
来源：http://dali.dianchejie.cn/Article/details/gt2oypyyacy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.snrcjt.cn/Article/details/gt2fwgkewss.html

[U77] PHP：模板渲染
来源：http://dali.chenzaomai.com/Article/details/gt2pocgvnmp.html

composer require twig/twig
来源：http://dali.cqqwz.cn/Article/details/gt2vtdyxbdd.html

[U78] PHP：单元测试
来源：http://dali.jyoumei.cn/Article/details/gt2lzebtxrk.html

composer require --dev phpunit/phpunit
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2muhrtalo.html

[U79] PHP：静态分析
来源：http://dali.9152youxi.cn/Article/details/gt2hiuctxzi.html

composer require --dev phpstan/phpstan
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtxgyphk.html

[U80] PHP：代码规范修复
来源：http://dali.vqdsnc.cn/Article/details/gt2xdekmiyf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gt2qcpmpvgo.html

[U81] JS：初始化项目
来源：http://dali.chenjidiqi.icu/Article/details/gt2acshsmza.html

npm init -y;  npm i express
来源：http://dali.ydzc1.top/Article/details/gt2jlvegkie.html

[U82] JS：package.json 脚本
来源：http://dali.smart0.xyz/Article/details/gt2reytrwpd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnqzz.top/Article/details/gt2pegdbrjr.html

[U83] JS：ES Module 导入导出
来源：http://dali.nwbrower.top/Article/details/gt2uqcjzyxy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxpwupuk.html

[U84] JS：CommonJS 写法
来源：http://dali.wangshuangyany.cn/Article/details/gt2kczdhije.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cashguo.top/Article/details/gt2fyxkqysm.html

[U85] JS：可选链
来源：http://dali.nanxuanxn.top/Article/details/gt2lacjdqkw.html

a?.b?.c
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntvxsimq.html

[U86] JS：空值合并
来源：http://dali.chenzaomai.com/Article/details/gt2uliktlaz.html

a ?? b
来源：http://dali.chenlongwang.top/Article/details/gt2lngqfams.html

[U87] JS：解构默认值
来源：http://dali.ybcxt.top/Article/details/gt2iutvrnlp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenlongwang.top/Article/details/gt2ariwfpsl.html

[U88] JS：对象展开合并
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcsnkdyw.html

{ ...a, ...b }
来源：http://dali.jlsjyb.cn/Article/details/gt2zoflpnig.html

[U89] JS：数组去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnjwzudv.html

[...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2voqrxvoz.html

[U90] JS：数字数组排序
来源：http://dali.yvedp.cn/Article/details/gt2allciexq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2raldebss.html

[U91] JS：对象键值遍历
来源：http://dali.yj20258888.top/Article/details/gt2bqsmncob.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dashuyun.cn/Article/details/gt2oyjdgusj.html

[U92] JS：深拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzjwhzes.html

structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2otcionlb.html

[U93] JS：模板字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtqoknvi.html

`共 ${n} 条`
来源：http://dali.tanke756.top/Article/details/gt2hkucgngt.html

[U94] JS：箭头函数
来源：http://dali.andypj.xyz/Article/details/gt2phuswbno.html

const double = x => x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmtygcla.html

[U95] JS：Promise 包装
来源：http://dali.fzhhl.top/Article/details/gt2aeqahwpm.html

new Promise((resolve, reject) => {})
来源：http://dali.fzhhl.top/Article/details/gt2teccvirt.html

[U96] JS：async/await 与异常
来源：http://dali.yueranfly.top/Article/details/gt2xohdeahz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2ogblbfhu.html

[U97] JS：并发请求
来源：http://dali.yongpay.top/Article/details/gt2ywfhpnqc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2pfemsmqv.html

[U98] JS：fetch 带 JSON
来源：http://dali.0kj1m.cn/Article/details/gt2nlfvtggp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhixingplan.top/Article/details/gt2dgcurrgw.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gt2wrkezlkf.html

el.addEventListener("click", e => {})
来源：http://dali.nanxinkj.top/Article/details/gt2erugqqef.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxpundab.html

document.querySelector(".item")
来源：http://dali.havefunace.top/Article/details/gt2mpypeibf.html

[U101] JS：classList 操作
来源：http://dali.chenlongwang.top/Article/details/gt2hnzwsbvu.html

el.classList.toggle("active")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kuzrndgt.html

[U102] JS：本地存储
来源：http://dali.sufxvd.cn/Article/details/gt2bgkfwtwm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvteuikx.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gt2ymziixsg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tianlin.xyz/Article/details/gt2bmelhwwt.html

[U104] JS：防抖
来源：http://dali.c1oappe.top/Article/details/gt2vogmfzas.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2rnrqhuph.html

[U105] JS：节流
来源：http://dali.guowangkeji.top/Article/details/gt2kevxvwir.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2mwihyutg.html

[U106] JS：日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2avsiusmp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gt2emtohopp.html

[U107] JS：数字千分位
来源：http://dali.meibo888.top/Article/details/gt2evuscbzx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gt2obdlfmug.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gt2oxvxzaxb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwabanrz.html

[U109] JS：数组分组
来源：http://dali.daria6918.cn/Article/details/gt2lmaprgdm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gt2dsarocqb.html

[U110] JS：数组分块
来源：http://dali.sysykeji.top/Article/details/gt2xvewlaxd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.316326.xyz/Article/details/gt2tlwxmpml.html

[U111] JS：对象转 Map
来源：http://dali.jqgufenzy.top/Article/details/gt2dsqmiwbc.html

new Map(Object.entries(obj))
来源：http://dali.sweek.top/Article/details/gt2aslgrdfn.html

[U112] JS：字符串补位
来源：http://dali.dashuyun.cn/Article/details/gt2edwqzhfa.html

"7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwjxfmoz.html

[U113] JS：正则替换全部
来源：http://dali.tianlin.xyz/Article/details/gt2vozsuqbg.html

s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdpjdctb.html

[U114] JS：JSON 深比较
来源：http://dali.zycfv.cn/Article/details/gt2fmlzpexf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gt2vcobtbxh.html

[U115] JS：生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gt2dpvgexsu.html

crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tejulift.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xylfe.cn/Article/details/gt2psozxtpp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zycfv.cn/Article/details/gt2pgjpvgvh.html

[U117] JS：单元测试
来源：http://dali.cheryme.top/Article/details/gt2ppezlcpr.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gt2dbhvaxte.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbigxsv.html

npm i -D vite;  npx vite
来源：http://dali.cdnleiting.top/Article/details/gt2hfkhnoqg.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gt2edoyeuqw.html

npx vite build
来源：http://dali.zhengqikj.top/Article/details/gt2vdiakbjr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jyoumei.cn/Article/details/gt2edqoqecf.html

import.meta.env.VITE_API_URL
来源：http://dali.vqdsnc.cn/Article/details/gt2mvfbzxnn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2sknkncuw.html

统计汇总
来源：http://dali.birdmap.top/Article/details/gt2keierhpn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2jjgghiyx.html

按语言统计（条）：
来源：http://dali.hammf.cn/Article/details/gt2llhxkzjs.html

Python ......... 252
来源：http://dali.jqgfzy.top/Article/details/gt2xhrrggke.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gt2aejqmrip.html

JavaScript ..... 252
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxjlvckc.html

TypeScript ..... 212
来源：http://dali.jqgufenzy.top/Article/details/gt2smntyklk.html

Java ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omhdkybp.html

Go ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gt2wltksvdn.html

Ruby ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gt2ynlqszcn.html

C# ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxjtdzdb.html

C .............. 30
来源：http://dali.yueranfly.top/Article/details/gt2zablivkf.html

C++ ............ 30
来源：http://dali.cucudq.cn/Article/details/gt2lihqxasp.html

SQL ............ 90
来源：http://dali.daria6918.cn/Article/details/gt2rsqzdwxz.html

Bash ........... 80
来源：http://dali.c1oappe.top/Article/details/gt2ujjzdvqt.html

Kotlin ......... 15
来源：http://dali.daria6918.cn/Article/details/gt2dpymzlgc.html

Swift .......... 15
来源：http://dali.hnxiangtu.top/Article/details/gt2beejgsxa.html

Lua ............ 10
来源：http://dali.nanxinkj.top/Article/details/gt2tsvdsbpg.html

Perl ........... 10
来源：http://dali.316326.xyz/Article/details/gt2gqzqdmye.html

Scala .......... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcnelmkd.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gt2uppnabfm.html

合计 ........... 2106 条
来源：http://dali.nanxinkj.top/Article/details/gt2wrzwujac.html

按章节统计：
来源：http://dali.wangdashe.top/Article/details/gt2amqhfttr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gt2swhdsaow.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gt2feouhllc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spdbjcgh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gt2gnhzftpz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sxryk.cn/Article/details/gt2jpeowmix.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gt2kdxlowio.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gt2kjhuvqdm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gt2axxigucx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gt2bndhaehb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gt2ktzgvdoe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2gzbwbckp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2uzintauo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gt2quicxpgt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gt2fxbdvtsx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pengpengdd.cyou/Article/details/gt2pulnaxtb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2wihbszjo.html

Q SQL 专题                              90
来源：http://dali.xuanzx.com/Article/details/gt2cqwqzgll.html

R Bash 专题                             80
来源：http://dali.chenjidiqi.icu/Article/details/gt2oiihwfck.html

S C / C++ 专题                          60
来源：http://dali.jqgfzy.top/Article/details/gt2iupuxveh.html

T 其他语言补充                          60
来源：http://dali.redwolf501.top/Article/details/gt2pjvmkqxp.html

U 高频实用片段                         120
来源：http://dali.birdmap.top/Article/details/gt2ntuinyqp.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gt2gvgkfonv.html

合计                                  2106 条
来源：http://dali.jyoumei.cn/Article/details/gt2rkdyuvee.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2nigtbzlr.html

使用提醒
来源：http://dali.fengsongda.top/Article/details/gt2zxxcddvn.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gt2rowmwmya.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sufxvd.cn/Article/details/gt2blwhhlnq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.svipenyu.cn/Article/details/gt2nuvgyvpw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yanxiufei.cn/Article/details/gt2hmagmbtr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyzrildt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xinyue.icu/Article/details/gt2cqugzfhl.html

—— 文件结束 ——
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkchwgas.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2vmfrgbsp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jyoumei.cn/Article/details/gt2bhaczgks.html

Common Programming Examples Cheat Book
来源：http://dali.yuanzhike.top/Article/details/gt2bvruxapu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2lcmdpxii.html

【收录内容】
来源：http://dali.yuanzhike.top/Article/details/gt2ywzpswtx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yuxming.cn/Article/details/gt2oixgtrcx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hysaishi.cn/Article/details/gt2mlzlaafj.html

SQL · Bash · C · C++
来源：http://dali.xuetiantiany.cn/Article/details/gt2miiskthr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zycfv.cn/Article/details/gt2gtvlexjx.html

【使用说明】
来源：http://dali.shzxlz.cn/Article/details/gt2dqtpdfhg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258888.top/Article/details/gt2qbfyxfnv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cqqwz.cn/Article/details/gt2kozfovwb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hysaishi.cn/Article/details/gt2tcoqatav.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aizwys.cn/Article/details/gt2vylxgwtk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.havefunace.top/Article/details/gt2aneteuxk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yueranfly.top/Article/details/gt2kjjsdxxf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsocxdqb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhengqikj.top/Article/details/gt2ymptooqk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.daxiang520.top/Article/details/gt2sumckcnr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj202588.top/Article/details/gt2irrgxqdb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aizwys.cn/Article/details/gt2sxqbhtnf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.guowangkeji.top/Article/details/gt2vgowjwur.html

【文件统计】
来源：http://dali.xuanzx.com/Article/details/gt2vhvglrip.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.birdmap.top/Article/details/gt2sborcvqk.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2gbgdkkma.html

目  录
来源：http://dali.yuxming.cn/Article/details/gt2uzhixdqr.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gt2ihvatxrz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekhxkrsn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gt2rbidocji.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gt2hrvveyef.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tian-w.cn/Article/details/gt2sxvaxkiq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.9152youxi.cn/Article/details/gt2qvfjgovg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gt2xdqpunsa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urvrgpsd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnfczwny.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gt2nbrlyklb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cheryme.top/Article/details/gt2iqcxknyj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gt2ptaifyhr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gt2voczooyi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gt2cglllmsh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmhjkzif.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2vugnohyh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chzaisny.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.iojbl.cn/Article/details/gt2cytuitwq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gysxytqo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pycfn.com/Article/details/gt2phlgkmyp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gt2ywbfkkqs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvquwvea.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2miujfrez.html

A. 基础语法与类型
来源：http://dali.ybcxt.top/Article/details/gt2drvoptay.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2zycdudqu.html

[A01] Hello World
来源：http://dali.meibo888.top/Article/details/gt2vwmnrwwc.html

Py:   print("Hello, World!")
来源：http://dali.hywenlv.cn/Article/details/gt2efiqwuja.html

PHP:  echo "Hello, World!";
来源：http://dali.hnxiangtu.top/Article/details/gt2uaihebfx.html

JS:   console.log("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gt2jonixmwn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ybcxt.top/Article/details/gt2uvartneq.html

Java: System.out.println("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gt2fgcyyyvw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gt2iampmsvc.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gt2bskrdqkx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gt2vwphanps.html

[A02] 变量声明与赋值
来源：http://dali.cheryme.top/Article/details/gt2cajuapfg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258888.top/Article/details/gt2irwxihhk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hfpthk.cn/Article/details/gt2fjzwojrw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.meibo888.top/Article/details/gt2ybzjdptz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzmeeeqr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gt2rhpcsavk.html

Go:   name := "Alex"; age := 20
来源：http://dali.jianghu66.top/Article/details/gt2jnqykaip.html

Ruby: name = "Alex"; age = 20
来源：http://dali.guowangkeji.top/Article/details/gt2alfjvxzr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gt2podbnqgt.html

[A03] 常量定义
来源：http://dali.xylfe.cn/Article/details/gt2dxyenxzi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tian-w.cn/Article/details/gt2xaaeogfq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtrzzxes.html

JS:   const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2szxorxex.html

TS:   const PI: number = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2yskyyaxt.html

Java: static final double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2csonqpfy.html

Go:   const PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gt2mbrrnljz.html

Ruby: PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gt2imnzjpis.html

C#:   const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2sryqonjk.html

[A04] 判断变量类型
来源：http://dali.guannengcc.top/Article/details/gt2xarpnhes.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shuidangran.top/Article/details/gt2jlhidwdr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cdnleiting.top/Article/details/gt2jlabmdrm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fzhhl.top/Article/details/gt2qbzryhts.html

TS:   typeof x; x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gt2xaidqdhn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ybcxt.top/Article/details/gt2wjofkveq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhoulong.xyz/Article/details/gt2elikprvn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cucudq.cn/Article/details/gt2wnyvzczd.html

C#:   x.GetType().Name; x is int
来源：http://dali.shzxlz.cn/Article/details/gt2vrpwifrk.html

[A05] 整数除法与取模
来源：http://dali.ehwqpu.com/Article/details/gt2hydyrqqg.html


<!-- 参考信息 -->