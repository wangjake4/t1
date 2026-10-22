代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.sweek.top/Article/details/gt2djlehain.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xinyue.icu/Article/details/gt2wcpgltez.html

[U38] Py：获取脚本所在目录
来源：http://dali.hysaishi.cn/Article/details/gt2qsycztcf.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gt2pobjcewn.html

[U39] Py：判断是否在交互环境
来源：http://dali.pycfn.com/Article/details/gt2hfkgxcoz.html

sys.stdout.isatty()
来源：http://dali.guowangkeji.top/Article/details/gt2hhfpdasu.html

[U40] Py：打印到标准错误
来源：http://dali.zhongyouzk.top/Article/details/gt2navctied.html

print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gt2cbpziyiw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.mhx1999.top/Article/details/gt2oxlolqqs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.meibo888.top/Article/details/gt2uzgplpbp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.c1oappe.top/Article/details/gt2ctaatfwc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hfpthk.cn/Article/details/gt2dlszwipi.html

[U43] PHP：声明命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gt2youcnmdv.html

namespace App\Http;
来源：http://dali.gaohongyu789.top/Article/details/gt2uvelzsnc.html

[U44] PHP：开启严格类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrxafuea.html

declare(strict_types=1);
来源：http://dali.jiagoushi.top/Article/details/gt2uuzioohz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.smart0.xyz/Article/details/gt2boulaims.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2epatncqn.html

[U46] PHP：可空类型
来源：http://dali.zdqjudy.top/Article/details/gt2icoqerop.html

?string $name = null
来源：http://dali.sxryk.cn/Article/details/gt2qvvgphtv.html

[U47] PHP：联合类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxpqwgot.html

int|string $id
来源：http://dali.gaohongyu789.top/Article/details/gt2ylryefjk.html

[U48] PHP：纯枚举
来源：http://dali.chenlongwang.top/Article/details/gt2esmkgngz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mwazoaud.html

[U49] PHP：只读属性
来源：http://dali.iojbl.cn/Article/details/gt2ffraxucz.html

public readonly string $name
来源：http://dali.jinqigufen.top/Article/details/gt2pophnzle.html

[U50] PHP：构造器属性提升
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tueeqqmf.html

public function __construct(private int $id) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2zxhvzeaw.html

[U51] PHP：数组解构
来源：http://dali.pycfn.com/Article/details/gt2tiotatfv.html

[$a, $b] = $arr;
来源：http://dali.ppjwa.cn/Article/details/gt2fasjacpx.html

[U52] PHP：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gt2gnqrafeo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhengqikj.top/Article/details/gt2ccgzwvuw.html

[U53] PHP：空合并运算符
来源：http://dali.0kj1m.cn/Article/details/gt2owdjtrhi.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuanzhike.top/Article/details/gt2revngfrh.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gt2conklzdj.html

$obj?->method()
来源：http://dali.yj202588.top/Article/details/gt2cynodcvr.html

[U55] PHP：match 表达式
来源：http://dali.hnqzz.top/Article/details/gt2znompefb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2moucmnfb.html

[U56] PHP：命名参数
来源：http://dali.jyoumei.cn/Article/details/gt2fmuskbed.html

f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2mobzvbto.html

[U57] PHP：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2wnhzaecd.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gt2shonhthc.html

[U58] PHP：数组三件套
来源：http://dali.shangyingyoupin.top/Article/details/gt2eaimloat.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sysykeji.top/Article/details/gt2pcziialg.html

[U59] PHP：自定义排序
来源：http://dali.sysykeji.top/Article/details/gt2vbchiadg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbwduzdo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfdfijkj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.mhx1999.top/Article/details/gt2meirptmf.html

[U61] PHP：正则
来源：http://dali.jianghu66.top/Article/details/gt2inujmixm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owambspf.html

[U62] PHP：日期对象
来源：http://dali.andypj.xyz/Article/details/gt2yeuxwlcd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.iojbl.cn/Article/details/gt2igaprwfn.html

[U63] PHP：文件读写
来源：http://dali.fengsongda.top/Article/details/gt2hxfrwqtm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.c1oappe.top/Article/details/gt2xczhcswv.html

[U64] PHP：目录遍历
来源：http://dali.haohaochexian.top/Article/details/gt2zdmmimge.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.meibo888.top/Article/details/gt2xhxncfwd.html

[U65] PHP：会话
来源：http://dali.yonumen.top/Article/details/gt2qzbrhqxd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2kvrnfqjg.html

[U66] PHP：设置 Cookie
来源：http://dali.jiagoushi.top/Article/details/gt2snrgtpvb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.havefunace.top/Article/details/gt2glvfkwwt.html

[U67] PHP：处理文件上传
来源：http://dali.gogol.net.cn/Article/details/gt2vopvbptb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gaohongyu789.top/Article/details/gt2tqoxgvvz.html

[U68] PHP：PDO 连接
来源：http://dali.zdqjudy.top/Article/details/gt2isoajexe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gppaoopz.html

[U69] PHP：PDO 预处理
来源：http://dali.xziqi.cn/Article/details/gt2dcalsnwh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.smart0.xyz/Article/details/gt2qbqioowl.html

[U70] PHP：PDO 事务
来源：http://dali.0kj1m.cn/Article/details/gt2oyymmpub.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigfzy.top/Article/details/gt2ralxatta.html

[U71] PHP：抛出异常
来源：http://dali.hnqzz.top/Article/details/gt2xvyfjaio.html

throw new RuntimeException("失败", 500);
来源：http://dali.andypj.xyz/Article/details/gt2brgrejms.html

[U72] PHP：写错误日志
来源：http://dali.jiagoushi.top/Article/details/gt2mctyspeo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.0kj1m.cn/Article/details/gt2anuovlji.html

[U73] PHP：读取 ini 配置
来源：http://dali.yanxiufei.cn/Article/details/gt2kexrafph.html

parse_ini_file("config.ini", true)
来源：http://dali.chenjidiqi.icu/Article/details/gt2upgivsjp.html

[U74] PHP：读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gt2iwwhnpsm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzjcmfpc.html

[U75] PHP：依赖注入
来源：http://dali.zycfv.cn/Article/details/gt2jvxkcoep.html

composer require psr/container
来源：http://dali.yuxming.cn/Article/details/gt2kyjtzqmw.html

[U76] PHP：简单路由
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tryhozrw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cashguo.top/Article/details/gt2gvuoopiy.html

[U77] PHP：模板渲染
来源：http://dali.nwbrower.top/Article/details/gt2dsrgjbwa.html

composer require twig/twig
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxnqkvnj.html

[U78] PHP：单元测试
来源：http://dali.zdqjudy.top/Article/details/gt2zqmflddz.html

composer require --dev phpunit/phpunit
来源：http://dali.vqdsnc.cn/Article/details/gt2ygwxmjws.html

[U79] PHP：静态分析
来源：http://dali.daxiang520.top/Article/details/gt2fsfdeods.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxuanxn.top/Article/details/gt2htikplif.html

[U80] PHP：代码规范修复
来源：http://dali.tianlin.xyz/Article/details/gt2hdpqvkfb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cdnleiting.top/Article/details/gt2iaeskpjd.html

[U81] JS：初始化项目
来源：http://dali.ydzc1.top/Article/details/gt2iewfgqda.html

npm init -y;  npm i express
来源：http://dali.zhiwuduotai.top/Article/details/gt2kacszowx.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gt2nnxgahng.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yueranfly.top/Article/details/gt2uznladgq.html

[U83] JS：ES Module 导入导出
来源：http://dali.cheryme.top/Article/details/gt2zfgfuphz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gt2dzxihnwc.html

[U84] JS：CommonJS 写法
来源：http://dali.316326.xyz/Article/details/gt2stqgxywt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ybcxt.top/Article/details/gt2hvnwaqbn.html

[U85] JS：可选链
来源：http://dali.ehwqpu.com/Article/details/gt2aosdpqod.html

a?.b?.c
来源：http://dali.wangdashe.top/Article/details/gt2veytvoyd.html

[U86] JS：空值合并
来源：http://dali.gaohongyu789.top/Article/details/gt2zwfldjdw.html

a ?? b
来源：http://dali.zhixingplan.top/Article/details/gt2tildfhjf.html

[U87] JS：解构默认值
来源：http://dali.yvedp.cn/Article/details/gt2wyihtvyu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.mhx1999.top/Article/details/gt2bknqrsmz.html

[U88] JS：对象展开合并
来源：http://dali.fzhhl.top/Article/details/gt2fzbhclwj.html

{ ...a, ...b }
来源：http://dali.xylfe.cn/Article/details/gt2sopkjqgh.html

[U89] JS：数组去重
来源：http://dali.hammf.cn/Article/details/gt2jgbakxmz.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2lgdkotwp.html

[U90] JS：数字数组排序
来源：http://dali.hammf.cn/Article/details/gt2crychepw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2kzjhtrzx.html

[U91] JS：对象键值遍历
来源：http://dali.ydzc1.top/Article/details/gt2qdfrxqgp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2goiyqqip.html

[U92] JS：深拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2ecrafyqd.html

structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oznkqeyr.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpmkapcu.html

`共 ${n} 条`
来源：http://dali.yj20258888.top/Article/details/gt2jnajawaz.html

[U94] JS：箭头函数
来源：http://dali.yj20258888.top/Article/details/gt2lpvpbhpi.html

const double = x => x * 2;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcexjrki.html

[U95] JS：Promise 包装
来源：http://dali.ppjwa.cn/Article/details/gt2rkdyehjy.html

new Promise((resolve, reject) => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydhzvsqi.html

[U96] JS：async/await 与异常
来源：http://dali.pycfn.com/Article/details/gt2adashdjb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2mdjiesof.html

[U97] JS：并发请求
来源：http://dali.guowangkeji.top/Article/details/gt2eeewshhy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2gayytjsz.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2neaeqfxv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dashuyun.cn/Article/details/gt2bfsuolkc.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gt2hkmaszlp.html

el.addEventListener("click", e => {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjteskfz.html

[U100] JS：DOM 查询
来源：http://dali.cashguo.top/Article/details/gt2pasladuo.html

document.querySelector(".item")
来源：http://dali.jqgfzy.top/Article/details/gt2onoivbcp.html

[U101] JS：classList 操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffxixsaf.html

el.classList.toggle("active")
来源：http://dali.quarkkingdee.top/Article/details/gt2dsnkwcst.html

[U102] JS：本地存储
来源：http://dali.gaohongyu789.top/Article/details/gt2dqvlxjhf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.mhx1999.top/Article/details/gt2becsxouh.html

[U103] JS：定时器
来源：http://dali.pycfn.com/Article/details/gt2yvgodlyc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.birdmap.top/Article/details/gt2tyziiidu.html

[U104] JS：防抖
来源：http://dali.jianghu66.top/Article/details/gt2umbsywqx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2laifdigh.html

[U105] JS：节流
来源：http://dali.hongshengwenyu.top/Article/details/gt2gycxvmzp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenzaomai.com/Article/details/gt2jefzddwd.html

[U106] JS：日期格式化
来源：http://dali.hammf.cn/Article/details/gt2tlfodzdb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guannengcc.top/Article/details/gt2iwckeirt.html

[U107] JS：数字千分位
来源：http://dali.yj20258888.top/Article/details/gt2secahrzf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuanzx.com/Article/details/gt2klthvimf.html

[U108] JS：随机整数
来源：http://dali.gotoacloud.top/Article/details/gt2audijxwg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpxlrtub.html

[U109] JS：数组分组
来源：http://dali.hysaishi.cn/Article/details/gt2otnrvqik.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gt2hkenhval.html

[U110] JS：数组分块
来源：http://dali.cdnleiting.top/Article/details/gt2zutomtfw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yvedp.cn/Article/details/gt2tmbemjxd.html

[U111] JS：对象转 Map
来源：http://dali.aizwys.cn/Article/details/gt2ekxmlqzd.html

new Map(Object.entries(obj))
来源：http://dali.ydzc1.top/Article/details/gt2psdlctpp.html

[U112] JS：字符串补位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlosvtgc.html

"7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2fseiboxp.html

[U113] JS：正则替换全部
来源：http://dali.wangshuangyany.cn/Article/details/gt2otdmgxcr.html

s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2ryoyoqyz.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gt2tkhmuwqu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gt2gtnnedvw.html

[U115] JS：生成 UUID
来源：http://dali.aizwys.cn/Article/details/gt2hvkfpnuk.html

crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gt2ajgxiyuh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gt2vpzjohsn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daxiang520.top/Article/details/gt2zdtqhbzr.html

[U117] JS：单元测试
来源：http://dali.yvedp.cn/Article/details/gt2gzozztax.html

npm i -D vitest;  npx vitest
来源：http://dali.316326.xyz/Article/details/gt2igudumah.html

[U118] JS：开发服务器
来源：http://dali.bjfxy.top/Article/details/gt2erqxrpvw.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gt2nhudcjke.html

[U119] JS：生产构建
来源：http://dali.yvedp.cn/Article/details/gt2xsptqxfu.html

npx vite build
来源：http://dali.hammf.cn/Article/details/gt2qbrimbww.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.mhx1999.top/Article/details/gt2oyrxebni.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gt2icagqzyx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2imluystr.html

统计汇总
来源：http://dali.chenlongwang.top/Article/details/gt2lrlbvoyh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2lkteemxo.html

按语言统计（条）：
来源：http://dali.vqdsnc.cn/Article/details/gt2dtsyugwr.html

Python ......... 252
来源：http://dali.iojbl.cn/Article/details/gt2cqxjvfym.html

PHP ............ 252
来源：http://dali.hywenlv.cn/Article/details/gt2shmslfnb.html

JavaScript ..... 252
来源：http://dali.gaohongyu789.top/Article/details/gt2arywilod.html

TypeScript ..... 212
来源：http://dali.yongpay.top/Article/details/gt2qzvqtkcx.html

Java ........... 212
来源：http://dali.xinyue.icu/Article/details/gt2rroxffeh.html

Go ............. 212
来源：http://dali.yj20258.top/Article/details/gt2ntwvybpi.html

Ruby ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzbkzrde.html

C# ............. 212
来源：http://dali.jiagoushi.top/Article/details/gt2uqlizlvd.html

C .............. 30
来源：http://dali.zycfv.cn/Article/details/gt2ilophnum.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gt2zpwxweiq.html

SQL ............ 90
来源：http://dali.cucudq.cn/Article/details/gt2trzcorzg.html

Bash ........... 80
来源：http://dali.cqqwz.cn/Article/details/gt2uootfxbw.html

Kotlin ......... 15
来源：http://dali.yangfankeji.com/Article/details/gt2ylqbvxuq.html

Swift .......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gt2ysjbjukn.html

Lua ............ 10
来源：http://dali.xziqi.cn/Article/details/gt2fdlolkot.html

Perl ........... 10
来源：http://dali.zycfv.cn/Article/details/gt2qvknwydq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2phtwkyjj.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyyttpyu.html

合计 ........... 2106 条
来源：http://dali.iojbl.cn/Article/details/gt2tepbtotz.html

按章节统计：
来源：http://dali.hnxiangtu.top/Article/details/gt2uiimgtdu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gt2iwygxbxu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gt2qbinvuuj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gt2vffkzxai.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gt2dtlqcvqf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yuxming.cn/Article/details/gt2ddcdmvji.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gt2ljirsvvv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gt2djvofwvl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ydzc1.top/Article/details/gt2bsprsrja.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2qddfxwep.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gt2othwfwgx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2atybrdeh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2kwnqxkzz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2axgrreqr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gt2qbghsjov.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.smart0.xyz/Article/details/gt2cpopsujz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gt2gzobjcfw.html

Q SQL 专题                              90
来源：http://dali.bjfxy.top/Article/details/gt2cudnbaee.html

R Bash 专题                             80
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnxbxdoh.html

S C / C++ 专题                          60
来源：http://dali.sxryk.cn/Article/details/gt2uuolacjw.html

T 其他语言补充                          60
来源：http://dali.guannengcc.top/Article/details/gt2nfoycakf.html

U 高频实用片段                         120
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qthihwdx.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gt2gmreaawn.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gt2ehdoyzyv.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2zapwozon.html

使用提醒
来源：http://dali.shuidangran.top/Article/details/gt2dyujfqec.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2cnpzzxid.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hfpthk.cn/Article/details/gt2xvazbijv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.feifeiyinyue.top/Article/details/gt2iafyowdd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.haohaochexian.top/Article/details/gt2aiesmkbt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hammf.cn/Article/details/gt2ucdsjeue.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.haohaochexian.top/Article/details/gt2mrytdoeo.html

—— 文件结束 ——
来源：http://dali.sysykeji.top/Article/details/gt2yocupsjs.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2fnyxlunz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqehfjec.html

Common Programming Examples Cheat Book
来源：http://dali.guannengcc.top/Article/details/gt2ojjffztn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2caosoenu.html

【收录内容】
来源：http://dali.jqgufenzy.top/Article/details/gt2gcstrqtn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrgmylku.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hammf.cn/Article/details/gt2ltzpsayj.html

SQL · Bash · C · C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awdswkqm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gzhubu.top/Article/details/gt2gmynihhl.html

【使用说明】
来源：http://dali.meibo888.top/Article/details/gt2irinugds.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ppjwa.cn/Article/details/gt2joblhcon.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hysaishi.cn/Article/details/gt2jwgnqlmu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ppjwa.cn/Article/details/gt2scphoojk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yongpay.top/Article/details/gt2fkdvggnk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigfzy.top/Article/details/gt2aayxzopf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgufenzy.top/Article/details/gt2pqtjthjw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.guowangkeji.top/Article/details/gt2mqjxpsmi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejzofghe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sxryk.cn/Article/details/gt2ujkdudxx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.bjfxy.top/Article/details/gt2rlbdijuk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cqqwz.cn/Article/details/gt2ankabggn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhixingplan.top/Article/details/gt2twrjnuiy.html

【文件统计】
来源：http://dali.shuidangran.top/Article/details/gt2zzdrgvzj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shzxlz.cn/Article/details/gt2vrysdkjy.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2prrgwxuk.html

目  录
来源：http://dali.yonumen.top/Article/details/gt2vkannpoa.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2cliakzsh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.wangdashe.top/Article/details/gt2wftglxkh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tianlin.xyz/Article/details/gt2zqwkyxlk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gt2ngawqmwk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2btnbizco.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yvedp.cn/Article/details/gt2padwhwdx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daxiang520.top/Article/details/gt2shfotrrz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gt2iqzttqvl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aibaodan.cn/Article/details/gt2ylzqugzp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gt2kftipoyo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gt2cidkhety.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2aijrthdo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gt2mtbnukgl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2wfccxvmy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gt2wzzxvnrb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yongpay.top/Article/details/gt2dftymbiw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gt2aiyjjtgk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yvedp.cn/Article/details/gt2sfnadhfs.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zdqjudy.top/Article/details/gt2seomwgag.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnlachzg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gt2vrzkxitz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.0kj1m.cn/Article/details/gt2alznnrwh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwoflszt.html

A. 基础语法与类型
来源：http://dali.kuanghao11.cn/Article/details/gt2rcfxxllk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bqbpplsw.html

[A01] Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2xolwrbol.html

Py:   print("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gt2iawgvshj.html

PHP:  echo "Hello, World!";
来源：http://dali.wangdashe.top/Article/details/gt2dgglwoxj.html

JS:   console.log("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okhyeupp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jlsjyb.cn/Article/details/gt2esiedfns.html

Java: System.out.println("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gt2iqbccouh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gt2xonaulpm.html

Ruby: puts "Hello, World!"
来源：http://dali.nwbrower.top/Article/details/gt2mvxkmxmf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwflgdrm.html

[A02] 变量声明与赋值
来源：http://dali.zhoulong.xyz/Article/details/gt2mbkjpclr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xziqi.cn/Article/details/gt2yglysdly.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xivqhjkq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dashuyun.cn/Article/details/gt2vuqfsjby.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xinyue.icu/Article/details/gt2uvarymas.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gt2hmiibpmo.html

Go:   name := "Alex"; age := 20
来源：http://dali.pycfn.com/Article/details/gt2xqyddumq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqxcbcsp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.316326.xyz/Article/details/gt2xlxfwnzq.html

[A03] 常量定义
来源：http://dali.xinyue.icu/Article/details/gt2wnaqjvve.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnqzz.top/Article/details/gt2altubzic.html

PHP:  const PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2ngsmeqap.html

JS:   const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2hgbsoomv.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmhpeuth.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbyqxutx.html

Go:   const PI = 3.14159
来源：http://dali.gzhubu.top/Article/details/gt2hotehhlr.html


<!-- 参考信息 -->