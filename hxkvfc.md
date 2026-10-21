代发 wailian999

[U33] Py：打包发布
来源：http://dali.xinyue.icu/Article/details/gttfrtjrpv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hongshengwenyu.top/Article/details/gtzbqlqiaf.html

[U34] Py：判断编码
来源：http://dali.xuanzx.com/Article/details/gtjrrsgwle.html

chardet.detect(raw)
来源：http://dali.hysaishi.cn/Article/details/gtmyknvcom.html

[U35] Py：发送邮件
来源：http://dali.shuidangran.top/Article/details/gtvgrcazqw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sxryk.cn/Article/details/gtnqnztkfn.html

[U36] Py：定时任务
来源：http://dali.hysaishi.cn/Article/details/gtxbkmotpr.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhnfwkdu.html

[U37] Py：读写 Excel
来源：http://dali.gaohongyu789.top/Article/details/gtokngmowk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenjidiqi.icu/Article/details/gtwfyzcmuw.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gtjuulhnid.html

Path(__file__).resolve().parent
来源：http://dali.tian-w.cn/Article/details/gtwkpfinvn.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gtwuhejvka.html

sys.stdout.isatty()
来源：http://dali.pengpengdd.cyou/Article/details/gtttkrriqt.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwufplqf.html

print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyhzobpn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhongyouzk.top/Article/details/gtqcawwtnm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakcxrhwc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.svipenyu.cn/Article/details/gtjxzzbtcf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangdashe.top/Article/details/gtqvvvadgr.html

[U43] PHP：声明命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gtrexcctej.html

namespace App\Http;
来源：http://dali.yuxming.cn/Article/details/gtdliacysd.html

[U44] PHP：开启严格类型
来源：http://dali.hysaishi.cn/Article/details/gtemvrsxru.html

declare(strict_types=1);
来源：http://dali.wangdashe.top/Article/details/gthurfrikt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.wangshuangyany.cn/Article/details/gtdnxlpwsy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtfyiqiavd.html

[U46] PHP：可空类型
来源：http://dali.nanxuanxn.top/Article/details/gtlkmczrhn.html

?string $name = null
来源：http://dali.dashuyun.cn/Article/details/gtnxqqygbi.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtkplxnmxp.html

int|string $id
来源：http://dali.zhengqikj.top/Article/details/gtqmrprszo.html

[U48] PHP：纯枚举
来源：http://dali.fengsongda.top/Article/details/gttyohtozg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yonumen.top/Article/details/gtmgossrfc.html

[U49] PHP：只读属性
来源：http://dali.dianchejie.cn/Article/details/gtsfesdaql.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gtulzzykng.html

[U50] PHP：构造器属性提升
来源：http://dali.cqqwz.cn/Article/details/gtnjrihtuy.html

public function __construct(private int $id) {}
来源：http://dali.yj20258.top/Article/details/gtdkhwvzub.html

[U51] PHP：数组解构
来源：http://dali.aizwys.cn/Article/details/gtxnvpuupw.html

[$a, $b] = $arr;
来源：http://dali.bjfxy.top/Article/details/gthanfecrb.html

[U52] PHP：箭头函数
来源：http://dali.zycfv.cn/Article/details/gtwhtlciey.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258.top/Article/details/gtgtgkqrmh.html

[U53] PHP：空合并运算符
来源：http://dali.jiagoushi.top/Article/details/gtaiegcoze.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncjyocnn.html

[U54] PHP：空安全调用
来源：http://dali.dashuyun.cn/Article/details/gtrsgewfsg.html

$obj?->method()
来源：http://dali.jyoumei.cn/Article/details/gtrgonlrpf.html

[U55] PHP：match 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtinflvjnl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrthqmbtx.html

[U56] PHP：命名参数
来源：http://dali.yj20258888.top/Article/details/gtuwbytjdm.html

f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtlzpdssju.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtgsnmlbxw.html

"值: {$a}"
来源：http://dali.aizwys.cn/Article/details/gtoloervft.html

[U58] PHP：数组三件套
来源：http://dali.andypj.xyz/Article/details/gtsyyarqkw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sweek.top/Article/details/gtagcdtzrr.html

[U59] PHP：自定义排序
来源：http://dali.zhoulong.xyz/Article/details/gtyqzfdgao.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gtzymvxlos.html

[U60] PHP：JSON 编解码
来源：http://dali.cucudq.cn/Article/details/gthqdckjgl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuanzhike.top/Article/details/gttavtsyjv.html

[U61] PHP：正则
来源：http://dali.meibo888.top/Article/details/gtyvtfrwhm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdnpkinn.html

[U62] PHP：日期对象
来源：http://dali.ybcxt.top/Article/details/gthrlyjpao.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gotoacloud.top/Article/details/gtasevhgoy.html

[U63] PHP：文件读写
来源：http://dali.zhengqikj.top/Article/details/gtfojvdfej.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gtakmenpax.html

[U64] PHP：目录遍历
来源：http://dali.svipenyu.cn/Article/details/gtbfucfjpd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangdashe.top/Article/details/gtqnaoiewd.html

[U65] PHP：会话
来源：http://dali.yvedp.cn/Article/details/gtxulaedwh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtygkeshlm.html

[U66] PHP：设置 Cookie
来源：http://dali.sxryk.cn/Article/details/gtzibfemcx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuanzx.com/Article/details/gtajnbsclu.html

[U67] PHP：处理文件上传
来源：http://dali.yuanzhike.top/Article/details/gtfytuoeaf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.mhx1999.top/Article/details/gtngucjsqt.html

[U68] PHP：PDO 连接
来源：http://dali.tian-w.cn/Article/details/gtuktoejkt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhiwuduotai.top/Article/details/gtanhtitqe.html

[U69] PHP：PDO 预处理
来源：http://dali.hongshengwenyu.top/Article/details/gtycaxthfo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hysaishi.cn/Article/details/gtlthhmseg.html

[U70] PHP：PDO 事务
来源：http://dali.316326.xyz/Article/details/gtuatpnvtt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guannengcc.top/Article/details/gtgslctsxs.html

[U71] PHP：抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtsuvjhxuv.html

throw new RuntimeException("失败", 500);
来源：http://dali.yongpay.top/Article/details/gtqeumxyns.html

[U72] PHP：写错误日志
来源：http://dali.kuanghao11.cn/Article/details/gtupixzdkr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuetiantiany.cn/Article/details/gtwslzoakd.html

[U73] PHP：读取 ini 配置
来源：http://dali.vqdsnc.cn/Article/details/gtdsonclyj.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigfzy.top/Article/details/gtzwdwszvk.html

[U74] PHP：读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtcuhksemm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.feifeiyinyue.top/Article/details/gtofmhuylc.html

[U75] PHP：依赖注入
来源：http://dali.andypj.xyz/Article/details/gthqrnlqfp.html

composer require psr/container
来源：http://dali.sxryk.cn/Article/details/gtbdnuafps.html

[U76] PHP：简单路由
来源：http://dali.jqgufenzy.top/Article/details/gtpzpvrmmb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gaohongyu789.top/Article/details/gthwabduhr.html

[U77] PHP：模板渲染
来源：http://dali.gotoacloud.top/Article/details/gtmijdhsxh.html

composer require twig/twig
来源：http://dali.havefunace.top/Article/details/gtlsgqxyfx.html

[U78] PHP：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlnifjrj.html

composer require --dev phpunit/phpunit
来源：http://dali.quarkkingdee.top/Article/details/gtplamzuzs.html

[U79] PHP：静态分析
来源：http://dali.tianlin.xyz/Article/details/gtdeziapla.html

composer require --dev phpstan/phpstan
来源：http://dali.meibo888.top/Article/details/gtlewmxuix.html

[U80] PHP：代码规范修复
来源：http://dali.jianghu66.top/Article/details/gtqcygsjdl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.aizwys.cn/Article/details/gtaexnwqxk.html

[U81] JS：初始化项目
来源：http://dali.vqdsnc.cn/Article/details/gtrhbcbjrr.html

npm init -y;  npm i express
来源：http://dali.xylfe.cn/Article/details/gtiezkivkj.html

[U82] JS：package.json 脚本
来源：http://dali.mhx1999.top/Article/details/gtuqcjwahg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gogol.net.cn/Article/details/gtcmdzshtq.html

[U83] JS：ES Module 导入导出
来源：http://dali.sweek.top/Article/details/gtgumnccoh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gthonkmfes.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxinkj.top/Article/details/gtqdxhisyv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yangfankeji.com/Article/details/gtxcybrrll.html

[U85] JS：可选链
来源：http://dali.gotoacloud.top/Article/details/gtklvqztjx.html

a?.b?.c
来源：http://dali.ydzc1.top/Article/details/gtjyukwcqk.html

[U86] JS：空值合并
来源：http://dali.yonumen.top/Article/details/gtvqwamthz.html

a ?? b
来源：http://dali.tanke756.top/Article/details/gtgbczgzat.html

[U87] JS：解构默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuvgzkpv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sweek.top/Article/details/gtmrdrdptb.html

[U88] JS：对象展开合并
来源：http://dali.zhoulong.xyz/Article/details/gtztliyaeq.html

{ ...a, ...b }
来源：http://dali.yonumen.top/Article/details/gtrbayufnl.html

[U89] JS：数组去重
来源：http://dali.yuanzhike.top/Article/details/gtfbyyrxzq.html

[...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwbkpfaf.html

[U90] JS：数字数组排序
来源：http://dali.xuetiantiany.cn/Article/details/gtltrwfmuj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtkigelkal.html

[U91] JS：对象键值遍历
来源：http://dali.svipenyu.cn/Article/details/gtepbmgghw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tianlin.xyz/Article/details/gtalnyunjm.html

[U92] JS：深拷贝
来源：http://dali.sweek.top/Article/details/gtmzwjsdgs.html

structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gthiqwumfb.html

[U93] JS：模板字符串
来源：http://dali.yonumen.top/Article/details/gtlnqdahec.html

`共 ${n} 条`
来源：http://dali.wangshuangyany.cn/Article/details/gttcztzabv.html

[U94] JS：箭头函数
来源：http://dali.tanke756.top/Article/details/gtiaiafxcp.html

const double = x => x * 2;
来源：http://dali.tian-w.cn/Article/details/gttxhjlxpk.html

[U95] JS：Promise 包装
来源：http://dali.pengpengdd.cyou/Article/details/gtmvvbwmwd.html

new Promise((resolve, reject) => {})
来源：http://dali.yongpay.top/Article/details/gtwmxiqpmx.html

[U96] JS：async/await 与异常
来源：http://dali.fengsongda.top/Article/details/gtcjfvcfyq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtbniwmqkp.html

[U97] JS：并发请求
来源：http://dali.haohaochexian.top/Article/details/gttaadhpjd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtruegvmas.html

[U98] JS：fetch 带 JSON
来源：http://dali.yuanzhike.top/Article/details/gtvksocngp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangshuangyany.cn/Article/details/gtkijnnjmh.html

[U99] JS：事件监听
来源：http://dali.yonumen.top/Article/details/gtikksitrl.html

el.addEventListener("click", e => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkfnlhrh.html

[U100] JS：DOM 查询
来源：http://dali.yj20258.top/Article/details/gtdzzoznbx.html

document.querySelector(".item")
来源：http://dali.yonumen.top/Article/details/gtpgjnpeag.html

[U101] JS：classList 操作
来源：http://dali.yangfankeji.com/Article/details/gtivedkazo.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslssqgro.html

[U102] JS：本地存储
来源：http://dali.jqgfzy.top/Article/details/gtfvuvkmxc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gtcywlmjat.html

[U103] JS：定时器
来源：http://dali.guowangkeji.top/Article/details/gtiguwnome.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yuxming.cn/Article/details/gttkkxzxjn.html

[U104] JS：防抖
来源：http://dali.mhx1999.top/Article/details/gtztiqzipb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtlzrxyyqe.html

[U105] JS：节流
来源：http://dali.dianchejie.cn/Article/details/gtkdfafsps.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobkemfmp.html

[U106] JS：日期格式化
来源：http://dali.ybcxt.top/Article/details/gtyqgikjhg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gtvmrcsozl.html

[U107] JS：数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtevhwfxnr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tanke756.top/Article/details/gtqcoesdpc.html

[U108] JS：随机整数
来源：http://dali.gzhubu.top/Article/details/gtzonexvcv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.meibo888.top/Article/details/gtjacjrcnt.html

[U109] JS：数组分组
来源：http://dali.iojbl.cn/Article/details/gtcvuwifqd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteelwemcr.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gtqvptcvzx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.wangdashe.top/Article/details/gtyvagzntb.html

[U111] JS：对象转 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtztnigaha.html

new Map(Object.entries(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrddnkkp.html

[U112] JS：字符串补位
来源：http://dali.ivvv.top/Article/details/gtkbcepfvl.html

"7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtczqztrox.html

[U113] JS：正则替换全部
来源：http://dali.hysaishi.cn/Article/details/gtsfmfilmh.html

s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtefzeljgf.html

[U114] JS：JSON 深比较
来源：http://dali.guannengcc.top/Article/details/gtcnfaadvr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cheryme.top/Article/details/gtsbagbbwr.html

[U115] JS：生成 UUID
来源：http://dali.mhx1999.top/Article/details/gttosmysgi.html

crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtaltnbunn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.9152youxi.cn/Article/details/gtvjikybcf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhengqikj.top/Article/details/gtkozfaoan.html

[U117] JS：单元测试
来源：http://dali.yuanzhike.top/Article/details/gtsqtdohrj.html

npm i -D vitest;  npx vitest
来源：http://dali.daxiang520.top/Article/details/gtakmliypz.html

[U118] JS：开发服务器
来源：http://dali.haohaochexian.top/Article/details/gtvudbnfbp.html

npm i -D vite;  npx vite
来源：http://dali.cdnleiting.top/Article/details/gtsuavvynv.html

[U119] JS：生产构建
来源：http://dali.daria6918.cn/Article/details/gtcwxfoarw.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gthserjenh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yonumen.top/Article/details/gtqfvnrhoh.html

import.meta.env.VITE_API_URL
来源：http://dali.gotoacloud.top/Article/details/gtjgkuauxe.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtupvpkqmk.html

统计汇总
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlelablr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsilasxap.html

按语言统计（条）：
来源：http://dali.nanxuanxn.top/Article/details/gtnzqazcsp.html

Python ......... 252
来源：http://dali.gotoacloud.top/Article/details/gtgwekbvxl.html

PHP ............ 252
来源：http://dali.zdqjudy.top/Article/details/gtrylllncs.html

JavaScript ..... 252
来源：http://dali.shzxlz.cn/Article/details/gtzmwpbanp.html

TypeScript ..... 212
来源：http://dali.shuidangran.top/Article/details/gtktztvvot.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtjssmzpgz.html

Go ............. 212
来源：http://dali.xziqi.cn/Article/details/gtczqutxsc.html

Ruby ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtbkfkibbc.html

C# ............. 212
来源：http://dali.jqgfzy.top/Article/details/gtshpoatqd.html

C .............. 30
来源：http://dali.svipenyu.cn/Article/details/gtwnybedbw.html

C++ ............ 30
来源：http://dali.hysaishi.cn/Article/details/gtoewvnvjo.html

SQL ............ 90
来源：http://dali.nanxuanxn.top/Article/details/gtnahbilxy.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gtytcscjil.html

Kotlin ......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtvrqnvmvs.html

Swift .......... 15
来源：http://dali.jyoumei.cn/Article/details/gtevladexn.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gtuyzhuzwa.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtrlhhngfs.html

Scala .......... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabnvlhzs.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtwrhvtzlb.html

合计 ........... 2106 条
来源：http://dali.xuanzx.com/Article/details/gtlzlmtzkw.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gtgactefls.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gtqjfonsmj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yonumen.top/Article/details/gtgrqmsmgo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtsyhozgxc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtjduklrfu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jiagoushi.top/Article/details/gtlilsxomv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gttwnhozet.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtuabedooa.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gtvppxladm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtgjnhrckc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gtgzjrarty.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtpgagstdd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtnxztkqmd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtohztcgoj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gtvspcnfdm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.kuanghao11.cn/Article/details/gtvieanjrx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtsknsdlur.html

Q SQL 专题                              90
来源：http://dali.jinqigufen.top/Article/details/gteyqycpxs.html

R Bash 专题                             80
来源：http://dali.wangshuangyany.cn/Article/details/gtgsdzbkci.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfpwqmll.html

T 其他语言补充                          60
来源：http://dali.9152youxi.cn/Article/details/gtninuflhq.html

U 高频实用片段                         120
来源：http://dali.fzhhl.top/Article/details/gtitorssuy.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtdaducamx.html

合计                                  2106 条
来源：http://dali.chenjidiqi.icu/Article/details/gttulpqfco.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtilbwwkxv.html

使用提醒
来源：http://dali.xuanzx.com/Article/details/gtfsowcpei.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtayavrkma.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.bjfxy.top/Article/details/gtuqjxejul.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.wangshuangyany.cn/Article/details/gtfrtypkxw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yonumen.top/Article/details/gtpdfifzjj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jyoumei.cn/Article/details/gtcysfoxdu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cashguo.top/Article/details/gtmjzidqlz.html

—— 文件结束 ——
来源：http://dali.yonumen.top/Article/details/gttviewgkw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdwwuqty.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.9152youxi.cn/Article/details/gtygjuvdsk.html

Common Programming Examples Cheat Book
来源：http://dali.birdmap.top/Article/details/gtwtqvxlfn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmqykihqw.html

【收录内容】
来源：http://dali.zhongyouzk.top/Article/details/gtcbspayqy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cdnleiting.top/Article/details/gtohncraqs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuanzhike.top/Article/details/gthhwhboif.html

SQL · Bash · C · C++
来源：http://dali.c1oappe.top/Article/details/gtiakxwhxe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuanzx.com/Article/details/gthwnsszyj.html

【使用说明】
来源：http://dali.iojbl.cn/Article/details/gtxsblsiqx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.0kj1m.cn/Article/details/gtntgibbsh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.quarkkingdee.top/Article/details/gtwmvfinlr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pengpengdd.cyou/Article/details/gtsskamehs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuxming.cn/Article/details/gtxiwrlzpy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuanzhike.top/Article/details/gtmgjgkieh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.quarkkingdee.top/Article/details/gtyjdduxml.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuetiantiany.cn/Article/details/gtgzqwavig.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cqqwz.cn/Article/details/gtjjxbatuz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ybcxt.top/Article/details/gtjjlrftes.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yonumen.top/Article/details/gtavshwevq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gttczrctbm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shuidangran.top/Article/details/gtufrykkao.html

【文件统计】
来源：http://dali.jinqigufen.top/Article/details/gtcyeaiuma.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jyoumei.cn/Article/details/gtakejxftr.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtmzwchyzn.html

目  录
来源：http://dali.hywenlv.cn/Article/details/gtvkbktthk.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtimmmrrzt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gtuwmrcuzp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtweydkhpd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrljmroxx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gtasfjpvmy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zycfv.cn/Article/details/gtebgimdre.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gtskqavhxf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtikzzwstx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtatjjxxto.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtnyeceupd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gttgowyvuz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtyoacantl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtwxdhjygr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtpyjyumzh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.svipenyu.cn/Article/details/gtuwcrxgdg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.iojbl.cn/Article/details/gtbdguflcx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtymlqiolo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuielhlhg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fengsongda.top/Article/details/gtelqxkjto.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj20258.top/Article/details/gtbscpwojm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtvxblbvvp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gthpaumdyo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtexhtditx.html

A. 基础语法与类型
来源：http://dali.zycfv.cn/Article/details/gtvxphvblz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqtgwbwng.html

[A01] Hello World
来源：http://dali.smart0.xyz/Article/details/gtdbxilzly.html

Py:   print("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gtakggsfsi.html

PHP:  echo "Hello, World!";
来源：http://dali.ydzc1.top/Article/details/gtrckesrwl.html

JS:   console.log("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gthwztyjxn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangdashe.top/Article/details/gttfhpycqi.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtklkzvyxh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.dashuyun.cn/Article/details/gtcmszbsdb.html

Ruby: puts "Hello, World!"
来源：http://dali.jiagoushi.top/Article/details/gtsorfuuuw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtymsdsyfm.html

[A02] 变量声明与赋值
来源：http://dali.yongpay.top/Article/details/gtydfddmgn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.316326.xyz/Article/details/gtioqshqyw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258.top/Article/details/gtjmvjnbww.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.iojbl.cn/Article/details/gtsiikpttk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtipzojuht.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtwpcecqlj.html

Go:   name := "Alex"; age := 20
来源：http://dali.iojbl.cn/Article/details/gtnibpjvgp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangshuangyany.cn/Article/details/gtgfgdsvzc.html


<!-- 参考信息 -->