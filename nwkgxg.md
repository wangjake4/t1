代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.ppjwa.cn/Article/details/gt2oomsoora.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jyoumei.cn/Article/details/gt2nkcklmot.html

[U38] Py：获取脚本所在目录
来源：http://dali.0kj1m.cn/Article/details/gt2xaoplqvb.html

Path(__file__).resolve().parent
来源：http://dali.gogol.net.cn/Article/details/gt2izkeljyw.html

[U39] Py：判断是否在交互环境
来源：http://dali.yvedp.cn/Article/details/gt2nuyhubna.html

sys.stdout.isatty()
来源：http://dali.daxiang520.top/Article/details/gt2gfmrczze.html

[U40] Py：打印到标准错误
来源：http://dali.ivvv.top/Article/details/gt2mqwidpba.html

print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gt2htxxmegl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guowangkeji.top/Article/details/gt2earvgwad.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.bjfxy.top/Article/details/gt2ycdtlcpm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yvedp.cn/Article/details/gt2ydetetms.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dianchejie.cn/Article/details/gt2itytnkbt.html

[U43] PHP：声明命名空间
来源：http://dali.yueranfly.top/Article/details/gt2pnkjifkt.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnecqnhc.html

[U44] PHP：开启严格类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrexmidm.html

declare(strict_types=1);
来源：http://dali.jiagoushi.top/Article/details/gt2cwdwscrx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhoulong.xyz/Article/details/gt2zrxlovct.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2ctvuottw.html

[U46] PHP：可空类型
来源：http://dali.aizwys.cn/Article/details/gt2gjitopde.html

?string $name = null
来源：http://dali.xinyue.icu/Article/details/gt2skyqbelz.html

[U47] PHP：联合类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxarpfbc.html

int|string $id
来源：http://dali.haohaochexian.top/Article/details/gt2mohehuyb.html

[U48] PHP：纯枚举
来源：http://dali.meibo888.top/Article/details/gt2glpuqvvo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jiagoushi.top/Article/details/gt2aynvxwht.html

[U49] PHP：只读属性
来源：http://dali.tian-w.cn/Article/details/gt2jdwxtgma.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gt2tdmxkbsr.html

[U50] PHP：构造器属性提升
来源：http://dali.jiagoushi.top/Article/details/gt2clmspcqg.html

public function __construct(private int $id) {}
来源：http://dali.cucudq.cn/Article/details/gt2nthokxfe.html

[U51] PHP：数组解构
来源：http://dali.ydzc1.top/Article/details/gt2oriorqss.html

[$a, $b] = $arr;
来源：http://dali.zhoulong.xyz/Article/details/gt2pqnqecey.html

[U52] PHP：箭头函数
来源：http://dali.yuanzhike.top/Article/details/gt2hqwphawq.html

$double = fn($x) => $x * 2;
来源：http://dali.ppjwa.cn/Article/details/gt2xenajkko.html

[U53] PHP：空合并运算符
来源：http://dali.zhixingplan.top/Article/details/gt2myzwznwv.html

$v = $a ?? $b ?? "default";
来源：http://dali.aibaodan.cn/Article/details/gt2cdszknxr.html

[U54] PHP：空安全调用
来源：http://dali.daria6918.cn/Article/details/gt2gtrovutp.html

$obj?->method()
来源：http://dali.yonumen.top/Article/details/gt2dptcmbgf.html

[U55] PHP：match 表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2mkdcprmx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwcwkque.html

[U56] PHP：命名参数
来源：http://dali.cqqwz.cn/Article/details/gt2txptqnqw.html

f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2ulqylrmx.html

[U57] PHP：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2dhsnywyt.html

"值: {$a}"
来源：http://dali.gaohongyu789.top/Article/details/gt2ohsosoah.html

[U58] PHP：数组三件套
来源：http://dali.hnqzz.top/Article/details/gt2qesfqbxv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqaimlxn.html

[U59] PHP：自定义排序
来源：http://dali.ivvv.top/Article/details/gt2xfdmlzzm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gt2ylbueimh.html

[U60] PHP：JSON 编解码
来源：http://dali.sysykeji.top/Article/details/gt2vbdarvoo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenlongwang.top/Article/details/gt2iircdyrg.html

[U61] PHP：正则
来源：http://dali.aibaodan.cn/Article/details/gt2klcukywk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gt2vtrenklu.html

[U62] PHP：日期对象
来源：http://dali.yonumen.top/Article/details/gt2mpgdnuqy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2glosvxby.html

[U63] PHP：文件读写
来源：http://dali.haohaochexian.top/Article/details/gt2ulrzbnct.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hfpthk.cn/Article/details/gt2lrjeyhjj.html

[U64] PHP：目录遍历
来源：http://dali.jyoumei.cn/Article/details/gt2afbvfhly.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsnjdtrt.html

[U65] PHP：会话
来源：http://dali.haohaochexian.top/Article/details/gt2sqgtgjin.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2qqwbwgyc.html

[U66] PHP：设置 Cookie
来源：http://dali.chenzaomai.com/Article/details/gt2owafucny.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cdnleiting.top/Article/details/gt2xjfzbkqe.html

[U67] PHP：处理文件上传
来源：http://dali.tian-w.cn/Article/details/gt2vaoltkee.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hongshengwenyu.top/Article/details/gt2msyuogoy.html

[U68] PHP：PDO 连接
来源：http://dali.jianghu66.top/Article/details/gt2bjikflhg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.quarkkingdee.top/Article/details/gt2kwxchtcd.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gt2qibtcoge.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgufenzy.top/Article/details/gt2ezscrxyq.html

[U70] PHP：PDO 事务
来源：http://dali.jyoumei.cn/Article/details/gt2bpkbvqpg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gt2rovbiqxs.html

[U71] PHP：抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2udaqecqx.html

throw new RuntimeException("失败", 500);
来源：http://dali.yonumen.top/Article/details/gt2qelmvfqk.html

[U72] PHP：写错误日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kyydfjei.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cucudq.cn/Article/details/gt2vlohhbln.html

[U73] PHP：读取 ini 配置
来源：http://dali.meibo888.top/Article/details/gt2lgljdunb.html

parse_ini_file("config.ini", true)
来源：http://dali.chenlongwang.top/Article/details/gt2phahlpjc.html

[U74] PHP：读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2rskurtex.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pycfn.com/Article/details/gt2pockfwfw.html

[U75] PHP：依赖注入
来源：http://dali.fengsongda.top/Article/details/gt2rlodjufv.html

composer require psr/container
来源：http://dali.yueranfly.top/Article/details/gt2fnsoorvr.html

[U76] PHP：简单路由
来源：http://dali.nanxuanxn.top/Article/details/gt2mcsyxxsy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.meibo888.top/Article/details/gt2yrhcnoal.html

[U77] PHP：模板渲染
来源：http://dali.xuanzx.com/Article/details/gt2osubfmqp.html

composer require twig/twig
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfjbasqk.html

[U78] PHP：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gt2wdhzrwno.html

composer require --dev phpunit/phpunit
来源：http://dali.yj202588.top/Article/details/gt2cfrdsnpn.html

[U79] PHP：静态分析
来源：http://dali.sufxvd.cn/Article/details/gt2nofjrjxr.html

composer require --dev phpstan/phpstan
来源：http://dali.ybcxt.top/Article/details/gt2reyejmxk.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigfzy.top/Article/details/gt2bdoqiusj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jlsjyb.cn/Article/details/gt2izdgfizo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2myeknkub.html

npm init -y;  npm i express
来源：http://dali.jinqigfzy.top/Article/details/gt2llpsrzcn.html

[U82] JS：package.json 脚本
来源：http://dali.gotoacloud.top/Article/details/gt2sbcfhrmc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yueranfly.top/Article/details/gt2wnfkevgo.html

[U83] JS：ES Module 导入导出
来源：http://dali.hfpthk.cn/Article/details/gt2vaasrnal.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gt2yrrrzbcw.html

[U84] JS：CommonJS 写法
来源：http://dali.yanxiufei.cn/Article/details/gt2rihxkbug.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jiagoushi.top/Article/details/gt2nbdvyxyr.html

[U85] JS：可选链
来源：http://dali.meibo888.top/Article/details/gt2ismgphir.html

a?.b?.c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ainagyvd.html

[U86] JS：空值合并
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecndgpbe.html

a ?? b
来源：http://dali.yongpay.top/Article/details/gt2eezmpadv.html

[U87] JS：解构默认值
来源：http://dali.shzxlz.cn/Article/details/gt2kebhhdxj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gzhubu.top/Article/details/gt2qbibttmm.html

[U88] JS：对象展开合并
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwirjelp.html

{ ...a, ...b }
来源：http://dali.hfpthk.cn/Article/details/gt2yhrffuwr.html

[U89] JS：数组去重
来源：http://dali.wangdashe.top/Article/details/gt2luygjfkd.html

[...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2dhaypqmq.html

[U90] JS：数字数组排序
来源：http://dali.gotoacloud.top/Article/details/gt2ykwhorqw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwycumjl.html

[U91] JS：对象键值遍历
来源：http://dali.yvedp.cn/Article/details/gt2eddiiyiv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigfzy.top/Article/details/gt2mxvryhzi.html

[U92] JS：深拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2unvrkbeb.html

structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2lekybylp.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gt2lhjzgoqu.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gt2wwnegjxo.html

[U94] JS：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gt2idxoskgd.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mihksupx.html

[U95] JS：Promise 包装
来源：http://dali.yongpay.top/Article/details/gt2gobioggk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjaezjrv.html

[U96] JS：async/await 与异常
来源：http://dali.yueranfly.top/Article/details/gt2bhrexyzj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdsczpyp.html

[U97] JS：并发请求
来源：http://dali.hammf.cn/Article/details/gt2uozwcjtn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2jusvatya.html

[U98] JS：fetch 带 JSON
来源：http://dali.pycfn.com/Article/details/gt2ysrejshc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sxryk.cn/Article/details/gt2rxcavcnp.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gt2egdachmt.html

el.addEventListener("click", e => {})
来源：http://dali.yangfankeji.com/Article/details/gt2kbzdcmyy.html

[U100] JS：DOM 查询
来源：http://dali.tian-w.cn/Article/details/gt2qxeimywd.html

document.querySelector(".item")
来源：http://dali.birdmap.top/Article/details/gt2fzwpcpdv.html

[U101] JS：classList 操作
来源：http://dali.ivvv.top/Article/details/gt2cgxxzqru.html

el.classList.toggle("active")
来源：http://dali.gzhubu.top/Article/details/gt2qwdtppsi.html

[U102] JS：本地存储
来源：http://dali.jqgfzy.top/Article/details/gt2nplviuoq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.redwolf501.top/Article/details/gt2wqnzmtxa.html

[U103] JS：定时器
来源：http://dali.yj20258888.top/Article/details/gt2ujsivbhi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gogol.net.cn/Article/details/gt2mtfrjokp.html

[U104] JS：防抖
来源：http://dali.cucudq.cn/Article/details/gt2qdwwfdhb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gt2sjyxifkb.html

[U105] JS：节流
来源：http://dali.hnqzz.top/Article/details/gt2gckgpbfa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwuzrtzh.html

[U106] JS：日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drmixxwp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xziqi.cn/Article/details/gt2rpnbzkpu.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gt2emwpdzkp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdygfrbr.html

[U108] JS：随机整数
来源：http://dali.cqqwz.cn/Article/details/gt2risgwaxw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkgoopos.html

[U109] JS：数组分组
来源：http://dali.shzxlz.cn/Article/details/gt2dffylrro.html

Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gt2abrkzxkz.html

[U110] JS：数组分块
来源：http://dali.jianghu66.top/Article/details/gt2dytmhdeq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yueranfly.top/Article/details/gt2ayhhhjqo.html

[U111] JS：对象转 Map
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrpgopes.html

new Map(Object.entries(obj))
来源：http://dali.andypj.xyz/Article/details/gt2aqlctkcl.html

[U112] JS：字符串补位
来源：http://dali.chenzaomai.com/Article/details/gt2ugwhfcyx.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2ndxyzvcy.html

[U113] JS：正则替换全部
来源：http://dali.daria6918.cn/Article/details/gt2zcwhfcri.html

s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2llhcwuwc.html

[U114] JS：JSON 深比较
来源：http://dali.zdqjudy.top/Article/details/gt2evunmyuv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2npwdipxo.html

[U115] JS：生成 UUID
来源：http://dali.zycfv.cn/Article/details/gt2rylpaxuw.html

crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bitnshce.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.haohaochexian.top/Article/details/gt2echzueop.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xinyue.icu/Article/details/gt2hcydbaik.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gt2nglgagnj.html

npm i -D vitest;  npx vitest
来源：http://dali.chenlongwang.top/Article/details/gt2nhzabqba.html

[U118] JS：开发服务器
来源：http://dali.0kj1m.cn/Article/details/gt2qyjizfxt.html

npm i -D vite;  npx vite
来源：http://dali.sufxvd.cn/Article/details/gt2tsefbcwa.html

[U119] JS：生产构建
来源：http://dali.zhengqikj.top/Article/details/gt2rirdakkn.html

npx vite build
来源：http://dali.yangfankeji.com/Article/details/gt2taoxdzfx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.quarkkingdee.top/Article/details/gt2smopmjdm.html

import.meta.env.VITE_API_URL
来源：http://dali.smart0.xyz/Article/details/gt2nrjvpeod.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2qvbvtkvs.html

统计汇总
来源：http://dali.aibaodan.cn/Article/details/gt2copsbfsm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2xomtjetr.html

按语言统计（条）：
来源：http://dali.sysykeji.top/Article/details/gt2eahojjct.html

Python ......... 252
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqeuyauz.html

PHP ............ 252
来源：http://dali.ybcxt.top/Article/details/gt2nnluwcai.html

JavaScript ..... 252
来源：http://dali.yj20258.top/Article/details/gt2cunwczvt.html

TypeScript ..... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygegymkp.html

Java ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfgsebyn.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gt2idcqmohr.html

Ruby ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gt2otzzjotr.html

C# ............. 212
来源：http://dali.hfpthk.cn/Article/details/gt2brqgdzly.html

C .............. 30
来源：http://dali.haohaochexian.top/Article/details/gt2gotrwdie.html

C++ ............ 30
来源：http://dali.wangdashe.top/Article/details/gt2vmnrfluk.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gt2arzfvdeg.html

Bash ........... 80
来源：http://dali.sweek.top/Article/details/gt2iwviainl.html

Kotlin ......... 15
来源：http://dali.hfpthk.cn/Article/details/gt2oyjhwgsw.html

Swift .......... 15
来源：http://dali.smart0.xyz/Article/details/gt2kuqdavdf.html

Lua ............ 10
来源：http://dali.hnxiangtu.top/Article/details/gt2wnmqjmos.html

Perl ........... 10
来源：http://dali.zdqjudy.top/Article/details/gt2orcsrenw.html

Scala .......... 10
来源：http://dali.sysykeji.top/Article/details/gt2chpvcbbp.html

------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gt2uqrlhway.html

合计 ........... 2106 条
来源：http://dali.ppjwa.cn/Article/details/gt2kwlywspc.html

按章节统计：
来源：http://dali.xinyue.icu/Article/details/gt2tloinqjj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenlongwang.top/Article/details/gt2kpudjnpm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gt2ondfwpxz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gt2ektobswc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daxiang520.top/Article/details/gt2vdymbiru.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xziqi.cn/Article/details/gt2htettqfh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gt2bloecaaa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gt2oagiugpd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gt2qrkushff.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2oxrggplh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gt2oqbyeurc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gt2zhrvbtua.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2lydayawa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2qpuvpdvi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gt2vxzmnxbj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xinyue.icu/Article/details/gt2hecrclml.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2rxvgupcn.html

Q SQL 专题                              90
来源：http://dali.chenzaomai.com/Article/details/gt2iywdrcng.html

R Bash 专题                             80
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhltxpkd.html

S C / C++ 专题                          60
来源：http://dali.zycfv.cn/Article/details/gt2nomtuduu.html

T 其他语言补充                          60
来源：http://dali.cheryme.top/Article/details/gt2llcqgkkk.html

U 高频实用片段                         120
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmasmkhq.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2agokdkjt.html

合计                                  2106 条
来源：http://dali.ydzc1.top/Article/details/gt2dkzuawox.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2jnsndudm.html

使用提醒
来源：http://dali.gotoacloud.top/Article/details/gt2hlbjwctn.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2mdoshxix.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghuxhutp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cdnleiting.top/Article/details/gt2gyvncczp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ybcxt.top/Article/details/gt2lorfyjtu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuanzx.com/Article/details/gt2ethnoptb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvaiiizs.html

—— 文件结束 ——
来源：http://dali.guannengcc.top/Article/details/gt2twdlhsep.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2lbkdsaeg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cdnleiting.top/Article/details/gt2tjwjsjzz.html

Common Programming Examples Cheat Book
来源：http://dali.yueranfly.top/Article/details/gt2mczeilbp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2sbirleii.html

【收录内容】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqpytyjl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hywenlv.cn/Article/details/gt2vzukpuaa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gzhubu.top/Article/details/gt2pqsaiahu.html

SQL · Bash · C · C++
来源：http://dali.smart0.xyz/Article/details/gt2gxcfdaji.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tian-w.cn/Article/details/gt2hjfeddrv.html

【使用说明】
来源：http://dali.xinyue.icu/Article/details/gt2orwlqjpk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhoulong.xyz/Article/details/gt2zsetoecx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangshuangyany.cn/Article/details/gt2oysgyjnb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.svipenyu.cn/Article/details/gt2xommdlco.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jlsjyb.cn/Article/details/gt2isqjzfzm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigfzy.top/Article/details/gt2oskwhbfp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.iojbl.cn/Article/details/gt2snwpxaps.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.havefunace.top/Article/details/gt2cnfrtwuu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvburpke.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.aibaodan.cn/Article/details/gt2tiuqjbdb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.fzhhl.top/Article/details/gt2kltykgzs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gt2bwqfpkbq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.nwbrower.top/Article/details/gt2nxpfmsww.html

【文件统计】
来源：http://dali.nanxinkj.top/Article/details/gt2dafkdrjl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.fzhhl.top/Article/details/gt2fnitfxmh.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gt2xlbxvrqf.html

目  录
来源：http://dali.shzxlz.cn/Article/details/gt2tojffulr.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gt2gdebttsx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sysykeji.top/Article/details/gt2cobpmrtg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2prjyzqrm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gt2xtpenvge.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2fzwjrmlt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2isvhvcva.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2zgidrmiz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gt2yufomhzn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gt2ipxizpmy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gt2trizgwvh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2xlmsryjh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gt2xcposzft.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fcjjisdl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gt2ycwrnbgg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clvvjxgy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.svipenyu.cn/Article/details/gt2omvbnzby.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2gpyzfgvq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2mergixoi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvjuvpze.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.iojbl.cn/Article/details/gt2eqlsfsir.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gt2nkvppcqv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gt2xtoytsmc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2gdmuzlzd.html

A. 基础语法与类型
来源：http://dali.vqdsnc.cn/Article/details/gt2jlahnycm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkzjqsmb.html

[A01] Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2jmownbuu.html

Py:   print("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gt2dirgtwrs.html

PHP:  echo "Hello, World!";
来源：http://dali.sxryk.cn/Article/details/gt2hdqzgntk.html

JS:   console.log("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gt2viyflohr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.snrcjt.cn/Article/details/gt2yetukcqw.html

Java: System.out.println("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gt2urecoryo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sweek.top/Article/details/gt2zyvdmmrt.html

Ruby: puts "Hello, World!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejgipdkw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gt2uutifvoi.html

[A02] 变量声明与赋值
来源：http://dali.xylfe.cn/Article/details/gt2vpmtcgfq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ydzc1.top/Article/details/gt2ietsmixy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.bjfxy.top/Article/details/gt2mvbnlift.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkrttooq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2ojhpxlzn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gt2etzbgwzd.html

Go:   name := "Alex"; age := 20
来源：http://dali.meibo888.top/Article/details/gt2egegbawu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.andypj.xyz/Article/details/gt2eoqnmapv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2eznjarcd.html

[A03] 常量定义
来源：http://dali.jiagoushi.top/Article/details/gt2hjqzxwvh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hywenlv.cn/Article/details/gt2plkryqxm.html

PHP:  const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2dpycotet.html

JS:   const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2hjnegjbz.html

TS:   const PI: number = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2epwyooff.html

Java: static final double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmjwtpgu.html

Go:   const PI = 3.14159
来源：http://dali.xylfe.cn/Article/details/gt2mmvkcwvy.html


<!-- 参考信息 -->