代发 wailian999

[U35] Py：发送邮件
来源：http://dali.dashuyun.cn/Article/details/gtbrhcgmcy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dianchejie.cn/Article/details/gtyfziudja.html

[U36] Py：定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtmdunlcvl.html

schedule.every(10).minutes.do(job)
来源：http://dali.hfpthk.cn/Article/details/gtfoxcghxf.html

[U37] Py：读写 Excel
来源：http://dali.gogol.net.cn/Article/details/gtnsdiqzew.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gtgmzsednv.html

[U38] Py：获取脚本所在目录
来源：http://dali.ehwqpu.com/Article/details/gtxjoujbne.html

Path(__file__).resolve().parent
来源：http://dali.birdmap.top/Article/details/gtpxqjtolx.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtfobwnroz.html

sys.stdout.isatty()
来源：http://dali.zhoulong.xyz/Article/details/gteascikol.html

[U40] Py：打印到标准错误
来源：http://dali.redwolf501.top/Article/details/gtxuqjtxav.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtuahbkznq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsvgsymm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.iojbl.cn/Article/details/gtygaqmtje.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hammf.cn/Article/details/gtaptiwwpr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jiagoushi.top/Article/details/gtmyjoaqvx.html

[U43] PHP：声明命名空间
来源：http://dali.zhixingplan.top/Article/details/gtmgytsrmb.html

namespace App\Http;
来源：http://dali.yanxiufei.cn/Article/details/gtktathhgm.html

[U44] PHP：开启严格类型
来源：http://dali.shzxlz.cn/Article/details/gtowfuookh.html

declare(strict_types=1);
来源：http://dali.gzhubu.top/Article/details/gtfhbhtdrc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.c1oappe.top/Article/details/gtjfntvxif.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtyjqwllnu.html

[U46] PHP：可空类型
来源：http://dali.jlsjyb.cn/Article/details/gthtmdxwok.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gtekuklqlk.html

[U47] PHP：联合类型
来源：http://dali.fzhhl.top/Article/details/gtpwprenor.html

int|string $id
来源：http://dali.chenzaomai.com/Article/details/gtilsoctuf.html

[U48] PHP：纯枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscorxruc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.kuanghao11.cn/Article/details/gtmkmjrmdu.html

[U49] PHP：只读属性
来源：http://dali.daxiang520.top/Article/details/gtyzrmmmto.html

public readonly string $name
来源：http://dali.ppjwa.cn/Article/details/gtmeqvedmr.html

[U50] PHP：构造器属性提升
来源：http://dali.xuanzx.com/Article/details/gtsyqsheja.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gtzzirliow.html

[U51] PHP：数组解构
来源：http://dali.sweek.top/Article/details/gtfzvrvurb.html

[$a, $b] = $arr;
来源：http://dali.gzhubu.top/Article/details/gtalpafkuc.html

[U52] PHP：箭头函数
来源：http://dali.shuidangran.top/Article/details/gtbyhhscdp.html

$double = fn($x) => $x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtojtakhnh.html

[U53] PHP：空合并运算符
来源：http://dali.daria6918.cn/Article/details/gtfvnveeob.html

$v = $a ?? $b ?? "default";
来源：http://dali.dianchejie.cn/Article/details/gtjmgxnxfj.html

[U54] PHP：空安全调用
来源：http://dali.ydzc1.top/Article/details/gtrkwkjkau.html

$obj?->method()
来源：http://dali.c1oappe.top/Article/details/gtdwgqqcsk.html

[U55] PHP：match 表达式
来源：http://dali.zdqjudy.top/Article/details/gtxyqahcvq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gtanlfmgpg.html

[U56] PHP：命名参数
来源：http://dali.daxiang520.top/Article/details/gtykfoerzq.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtobeksepm.html

[U57] PHP：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtxkvzucye.html

"值: {$a}"
来源：http://dali.zhongyouzk.top/Article/details/gtqfzcdmrw.html

[U58] PHP：数组三件套
来源：http://dali.pycfn.com/Article/details/gtpzxbrbsv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtjiyyyfmf.html

[U59] PHP：自定义排序
来源：http://dali.yangfankeji.com/Article/details/gtaxzafyhc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtexxpljws.html

[U60] PHP：JSON 编解码
来源：http://dali.zhengqikj.top/Article/details/gtvzbrimxr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.vqdsnc.cn/Article/details/gtzsyyypwb.html

[U61] PHP：正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfghphed.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtmqqahore.html

[U62] PHP：日期对象
来源：http://dali.hnxiangtu.top/Article/details/gtyljjxmoh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xylfe.cn/Article/details/gtwyzkrrvx.html

[U63] PHP：文件读写
来源：http://dali.chenzaomai.com/Article/details/gtfgyxrvku.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xziqi.cn/Article/details/gtiapgndtk.html

[U64] PHP：目录遍历
来源：http://dali.mhx1999.top/Article/details/gtlvjerycu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.haohaochexian.top/Article/details/gtqnaznllz.html

[U65] PHP：会话
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyltodze.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gttybvjqxw.html

[U66] PHP：设置 Cookie
来源：http://dali.smart0.xyz/Article/details/gtkejvbtpq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhongyouzk.top/Article/details/gtvzckrwgq.html

[U67] PHP：处理文件上传
来源：http://dali.birdmap.top/Article/details/gtkvinrfba.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yvedp.cn/Article/details/gtqxbmiubb.html

[U68] PHP：PDO 连接
来源：http://dali.hongshengwenyu.top/Article/details/gtwwbmxdmd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hywenlv.cn/Article/details/gtzpeqsdeq.html

[U69] PHP：PDO 预处理
来源：http://dali.ivvv.top/Article/details/gtzhpluhei.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhixingplan.top/Article/details/gtamdyjgdj.html

[U70] PHP：PDO 事务
来源：http://dali.sxryk.cn/Article/details/gtselvoofg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.kuanghao11.cn/Article/details/gtwliqfkgg.html

[U71] PHP：抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtcmbxfqkv.html

throw new RuntimeException("失败", 500);
来源：http://dali.hysaishi.cn/Article/details/gtbvodccca.html

[U72] PHP：写错误日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaiwqshju.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sweek.top/Article/details/gtqwevdkmj.html

[U73] PHP：读取 ini 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdosnyovb.html

parse_ini_file("config.ini", true)
来源：http://dali.nwbrower.top/Article/details/gtqogwhmgx.html

[U74] PHP：读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtdcimfsuc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gtvifxqhwy.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gtnnycvuzk.html

composer require psr/container
来源：http://dali.redwolf501.top/Article/details/gtxwbmhdle.html

[U76] PHP：简单路由
来源：http://dali.9152youxi.cn/Article/details/gtiujjdmlz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gttqslvpzv.html

[U77] PHP：模板渲染
来源：http://dali.pengpengdd.cyou/Article/details/gtxvwxhcyf.html

composer require twig/twig
来源：http://dali.hnxiangtu.top/Article/details/gtqmxcypfn.html

[U78] PHP：单元测试
来源：http://dali.yj202588.top/Article/details/gtuaaicxub.html

composer require --dev phpunit/phpunit
来源：http://dali.xuetiantiany.cn/Article/details/gtstbhoshc.html

[U79] PHP：静态分析
来源：http://dali.yongpay.top/Article/details/gtxvhcyymg.html

composer require --dev phpstan/phpstan
来源：http://dali.havefunace.top/Article/details/gtdtnajqbx.html

[U80] PHP：代码规范修复
来源：http://dali.pengpengdd.cyou/Article/details/gtgubyfvke.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.birdmap.top/Article/details/gtzewxfukp.html

[U81] JS：初始化项目
来源：http://dali.cheryme.top/Article/details/gthtbteqqh.html

npm init -y;  npm i express
来源：http://dali.yanxiufei.cn/Article/details/gtagzbslyg.html

[U82] JS：package.json 脚本
来源：http://dali.zdqjudy.top/Article/details/gtlejxeyrp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.andypj.xyz/Article/details/gtwodwalfo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhoulong.xyz/Article/details/gtyciifknf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gtacrjufyh.html

[U84] JS：CommonJS 写法
来源：http://dali.chenlongwang.top/Article/details/gtcshtywyp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ehwqpu.com/Article/details/gthijamtsn.html

[U85] JS：可选链
来源：http://dali.jinqigfzy.top/Article/details/gtwvueuyxb.html

a?.b?.c
来源：http://dali.sufxvd.cn/Article/details/gtszhmofwp.html

[U86] JS：空值合并
来源：http://dali.tianlin.xyz/Article/details/gtrqmtdlhw.html

a ?? b
来源：http://dali.ybcxt.top/Article/details/gthtbsqkbg.html

[U87] JS：解构默认值
来源：http://dali.kuanghao11.cn/Article/details/gtufbsbknl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hysaishi.cn/Article/details/gtlsbdmzkf.html

[U88] JS：对象展开合并
来源：http://dali.jlsjyb.cn/Article/details/gtahbjyplu.html

{ ...a, ...b }
来源：http://dali.zhiwuduotai.top/Article/details/gtammunyzo.html

[U89] JS：数组去重
来源：http://dali.cashguo.top/Article/details/gtuyjdnmca.html

[...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsrworop.html

[U90] JS：数字数组排序
来源：http://dali.guannengcc.top/Article/details/gtsqkujnrs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtaumgohcs.html

[U91] JS：对象键值遍历
来源：http://dali.quarkkingdee.top/Article/details/gtqfesvvip.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tanke756.top/Article/details/gtganytogw.html

[U92] JS：深拷贝
来源：http://dali.ybcxt.top/Article/details/gtuzxivvxq.html

structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtpywwrvuf.html

[U93] JS：模板字符串
来源：http://dali.birdmap.top/Article/details/gtnboyxgvq.html

`共 ${n} 条`
来源：http://dali.ivvv.top/Article/details/gtkwlpxmok.html

[U94] JS：箭头函数
来源：http://dali.bjfxy.top/Article/details/gtobkxembv.html

const double = x => x * 2;
来源：http://dali.shuidangran.top/Article/details/gthvgjtney.html

[U95] JS：Promise 包装
来源：http://dali.yongpay.top/Article/details/gtptjwudno.html

new Promise((resolve, reject) => {})
来源：http://dali.shzxlz.cn/Article/details/gtjpvixeqc.html

[U96] JS：async/await 与异常
来源：http://dali.tanke756.top/Article/details/gtsgpslafg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtxnmrrcxn.html

[U97] JS：并发请求
来源：http://dali.zhixingplan.top/Article/details/gthagojbpz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtercknrce.html

[U98] JS：fetch 带 JSON
来源：http://dali.9152youxi.cn/Article/details/gtnyugjgtd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hongshengwenyu.top/Article/details/gtgebstngt.html

[U99] JS：事件监听
来源：http://dali.gaohongyu789.top/Article/details/gthzbdvoui.html

el.addEventListener("click", e => {})
来源：http://dali.daria6918.cn/Article/details/gtuyiioiup.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxgoooas.html

document.querySelector(".item")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvoesvcr.html

[U101] JS：classList 操作
来源：http://dali.chenjidiqi.icu/Article/details/gtlhocyksh.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gttxxjbsxq.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gtowbhnssk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdalwnfr.html

[U103] JS：定时器
来源：http://dali.gzhubu.top/Article/details/gtgdgxdhyy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.dashuyun.cn/Article/details/gtariuvcah.html

[U104] JS：防抖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmblhuvp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtbkoxfaxj.html

[U105] JS：节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnldrvsm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.vqdsnc.cn/Article/details/gtcxzegrnl.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaqpyafc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnqzz.top/Article/details/gtantthoep.html

[U107] JS：数字千分位
来源：http://dali.aibaodan.cn/Article/details/gthkiyqvma.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtznvjgqaq.html

[U108] JS：随机整数
来源：http://dali.nanxinkj.top/Article/details/gtnxdwwwru.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhengqikj.top/Article/details/gtyfphtufu.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gtmjmsglpe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtcxaltyic.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gtbgxjpoly.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubthloqv.html

[U111] JS：对象转 Map
来源：http://dali.ppjwa.cn/Article/details/gtvwamjoyd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtftcaquvi.html

[U112] JS：字符串补位
来源：http://dali.dashuyun.cn/Article/details/gtghmwajzo.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtcfpkdomw.html

[U113] JS：正则替换全部
来源：http://dali.chenzaomai.com/Article/details/gteuupcaua.html

s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtejelgavr.html

[U114] JS：JSON 深比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqfneceb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtytdjdtwz.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtebbtwlbd.html

crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gttgqolmgk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.quarkkingdee.top/Article/details/gtosjmblpa.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gotoacloud.top/Article/details/gthhrfldqg.html

[U117] JS：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gtaaumfzez.html

npm i -D vitest;  npx vitest
来源：http://dali.guowangkeji.top/Article/details/gtruawhvpg.html

[U118] JS：开发服务器
来源：http://dali.hnqzz.top/Article/details/gtvuvaxusq.html

npm i -D vite;  npx vite
来源：http://dali.tian-w.cn/Article/details/gtzftceoob.html

[U119] JS：生产构建
来源：http://dali.pycfn.com/Article/details/gthjjbxipw.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gtbbvomjpw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnqzz.top/Article/details/gtqbnzoyxf.html

import.meta.env.VITE_API_URL
来源：http://dali.0kj1m.cn/Article/details/gtmihszqfc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldslxmnm.html

统计汇总
来源：http://dali.ybcxt.top/Article/details/gtrasasfco.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtallycqse.html

按语言统计（条）：
来源：http://dali.xinyue.icu/Article/details/gtaijstrzg.html

Python ......... 252
来源：http://dali.jiagoushi.top/Article/details/gtnqfrdmtm.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gtwwefgfmi.html

JavaScript ..... 252
来源：http://dali.quarkkingdee.top/Article/details/gtzgiybyal.html

TypeScript ..... 212
来源：http://dali.jinqigfzy.top/Article/details/gthoorbqsi.html

Java ........... 212
来源：http://dali.gogol.net.cn/Article/details/gthdxhxwdt.html

Go ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzbtdmif.html

Ruby ........... 212
来源：http://dali.cdnleiting.top/Article/details/gtiblqesda.html

C# ............. 212
来源：http://dali.wangdashe.top/Article/details/gtlxqckutc.html

C .............. 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudpuoakl.html

C++ ............ 30
来源：http://dali.ehwqpu.com/Article/details/gtbqnidfxj.html

SQL ............ 90
来源：http://dali.sufxvd.cn/Article/details/gtetbwofso.html

Bash ........... 80
来源：http://dali.cashguo.top/Article/details/gtcqxsnnom.html

Kotlin ......... 15
来源：http://dali.wangdashe.top/Article/details/gtjwblyjgg.html

Swift .......... 15
来源：http://dali.xylfe.cn/Article/details/gtvjgnvwkq.html

Lua ............ 10
来源：http://dali.zycfv.cn/Article/details/gtebmmsmiw.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gtgijluvdu.html

Scala .......... 10
来源：http://dali.iojbl.cn/Article/details/gtnvrfjbee.html

------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtrwgiapec.html

合计 ........... 2106 条
来源：http://dali.mhx1999.top/Article/details/gtlutyazun.html

按章节统计：
来源：http://dali.yj20258888.top/Article/details/gtufwcmldl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gthaeadvyb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtcevqzeiu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtenkgjjwj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dianchejie.cn/Article/details/gtnwbucudk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gtwkutpxwu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtxpmwxweq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtsmsfhuvb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjbnhnjp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtowdtkhvm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtobwalkui.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtuvetcvdl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtopkuaskq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtdqhmmees.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gtfvsgjrts.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jiagoushi.top/Article/details/gttwwamdoy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtozghkxtc.html

Q SQL 专题                              90
来源：http://dali.jiagoushi.top/Article/details/gtdjpzslmo.html

R Bash 专题                             80
来源：http://dali.redwolf501.top/Article/details/gtxhzklcug.html

S C / C++ 专题                          60
来源：http://dali.hnxiangtu.top/Article/details/gtpfjtryuk.html

T 其他语言补充                          60
来源：http://dali.quarkkingdee.top/Article/details/gtcccgtyyi.html

U 高频实用片段                         120
来源：http://dali.guannengcc.top/Article/details/gtwrxvovui.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtycdtyyja.html

合计                                  2106 条
来源：http://dali.yongpay.top/Article/details/gtiwobvxpn.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gttbeccvsu.html

使用提醒
来源：http://dali.dianchejie.cn/Article/details/gthkbvzosw.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtyiclnrle.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuxming.cn/Article/details/gtbiafmynb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.andypj.xyz/Article/details/gtunbuwyar.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ivvv.top/Article/details/gtwcspjruf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sxryk.cn/Article/details/gtacyncasa.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhoulong.xyz/Article/details/gtsexucurn.html

—— 文件结束 ——
来源：http://dali.yvedp.cn/Article/details/gtfvoayuwv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkkwhubge.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangtech.top/Article/details/gtaknuvpvx.html

Common Programming Examples Cheat Book
来源：http://dali.ybcxt.top/Article/details/gtidmmkeoy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylgsobaw.html

【收录内容】
来源：http://dali.yanxiufei.cn/Article/details/gtplxaprin.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhengqikj.top/Article/details/gtsufyxoyd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jyoumei.cn/Article/details/gtollxpfrj.html

SQL · Bash · C · C++
来源：http://dali.yj20258888.top/Article/details/gtveqdfuez.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aizwys.cn/Article/details/gtfknpauku.html

【使用说明】
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkthetngh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gaohongyu789.top/Article/details/gtztrnqlqr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxuanxn.top/Article/details/gtpykcpemx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.kuanghao11.cn/Article/details/gttmksemcz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.redwolf501.top/Article/details/gtejmywwji.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhixingplan.top/Article/details/gtzmduysuw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenzaomai.com/Article/details/gtdtksawyy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dashuyun.cn/Article/details/gtwgmhezpy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.9152youxi.cn/Article/details/gtjagwfujj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yuxming.cn/Article/details/gtdoqbepiz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yonumen.top/Article/details/gtrqyvqpgf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgfzy.top/Article/details/gtfadaract.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sysykeji.top/Article/details/gtxxqrgfet.html

【文件统计】
来源：http://dali.mhx1999.top/Article/details/gtajqpcagt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guannengcc.top/Article/details/gteykcwabi.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtickpsmdk.html

目  录
来源：http://dali.yj20258.top/Article/details/gtghzwwksd.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtuvyvykxq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gtmjklrldd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtnnkitrsb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gtpgxmsimk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sufxvd.cn/Article/details/gtwkkjdsjk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sufxvd.cn/Article/details/gtkfbefqhf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofyaqnmi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtsdbkcugs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gthmovylbt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtrjwjoiso.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hywenlv.cn/Article/details/gtgxzqyhcd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtufagqlee.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gticsxwzyi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtlhchohqw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ydzc1.top/Article/details/gtfbztnsew.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xziqi.cn/Article/details/gtzwzwjutb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtlfgiqugn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskzokvkf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtbyvovcoj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fengsongda.top/Article/details/gtmittysem.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gtnxvnrids.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtgeroajsl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbmotyfgf.html

A. 基础语法与类型
来源：http://dali.wangdashe.top/Article/details/gtqopkjmke.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnjgzxczj.html

[A01] Hello World
来源：http://dali.smart0.xyz/Article/details/gtkvwccucf.html

Py:   print("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gtmljmveug.html

PHP:  echo "Hello, World!";
来源：http://dali.xuetiantiany.cn/Article/details/gtilhgbucx.html

JS:   console.log("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gtuoeyblcn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hysaishi.cn/Article/details/gtauikpltc.html

Java: System.out.println("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzfktzop.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtekfadvjw.html

Ruby: puts "Hello, World!"
来源：http://dali.9152youxi.cn/Article/details/gtdqtzmnbs.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gtlbxskozw.html

[A02] 变量声明与赋值
来源：http://dali.yongpay.top/Article/details/gtvzarolsw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ydzc1.top/Article/details/gtyqdghrby.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.smart0.xyz/Article/details/gtxocxouzl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtmiciiszt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ydzc1.top/Article/details/gtzjwonjdd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gtplcifbzv.html

Go:   name := "Alex"; age := 20
来源：http://dali.jyoumei.cn/Article/details/gtznfytobc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinghuilouyu.cn/Article/details/gtiacpmthh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtvrvsgkra.html

[A03] 常量定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhmiscdh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tianlin.xyz/Article/details/gtitianssc.html

PHP:  const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtgyqogdxs.html


<!-- 参考信息 -->