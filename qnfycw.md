代发 wailian999

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpdtosx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhggqej.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpcgawn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xojukbyx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeoeiqx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zcndqfgy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrwmpcg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vohsgbdp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mnekmlln.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryylbeth.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fqriectr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ensszbyb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iikdqejh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2idtwicyo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2urmnaupc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujesqtyf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mucpyvbn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfndngdx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfvuydu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdmaqet.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsvndwb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owinuabt.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2shrupfea.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjsnufj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucihrtjj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2opyoshbt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2umfgyepv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdvzgag.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ghodddrr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsmltwy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvjwstp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrhfpeg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nkatmnhp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzgeedq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2handiwiz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vygxzizk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbagmnf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mhenjmvc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsuqsrj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjtuzri.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jttrsjbz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnewqrr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkscaewx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfedlon.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kwluguan.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sllrkeoo.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2obwtnxzo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2utpkfupx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2grhpqxfp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2spbxwlel.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaacmfl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2snpubfis.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wuupowrk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2stgnunab.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnmuxaw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2moorcswt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkzdgxx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2snmrjinm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqhqggl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjfkcou.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbkzegq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxafjsl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2opflpsdi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjhnwmm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjfzwhi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yayxqyhx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbsrkzf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nphmagdn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsnsbjr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2esowkyoj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2imykoogg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuqutxv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkpamgj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcxsrwb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxauydd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ywefhayq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yotrtpdr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcatvmf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axzawoeb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpbzein.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzfrujb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2sogbfzyq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwlzrki.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxgsjor.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2aeziwhst.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lyswcyik.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbwgabp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2icznfoij.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lelvpguw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgdrfhd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhpgoqx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwsvwnx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgcapgv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cntveqja.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtfbcel.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxigjag.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmbmabn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2untyylvw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2seoqaegt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2stxpwbxu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2motytkxo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpgjwwd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqxnzqt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2chruyjux.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vikagpno.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyybczxi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqqxxrq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkysawn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2unpiqttn.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiukelm.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsakuvo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gndhlpqg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxfzyjp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdkebnm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qmozbqko.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgujqtjb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqgnfcn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2asrxginx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2royyxudt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoabccmv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2prjgicxz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnaumyv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzljbss.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdaftya.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxjfgsw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2etbrqima.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2akypcziv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfklonp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2psptdjri.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xishqyta.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hcigjwvg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsfvjne.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwuoumj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgydofi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2agjpyppd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmltayy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lehgsnwd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjbgnpu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjjotzq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2isblkbjk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pxggatgy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvctkxm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuglbxp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2abqldtfj.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2axpatgll.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwldelnh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxaghgi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2crpahgyi.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kaknhxgw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hybvdqxo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2oowdbtnt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjaammy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2adbziaiq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tixarvex.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwprxpb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyppnie.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcaexyw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtsffks.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2khuptwkf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfabvez.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cemjyesz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2huvkpkog.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtuhkle.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xicvsfnn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbznamt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnvofnj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2inlrjqwp.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrngbql.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2wootpusi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2icitqqut.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwhqywg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgkmkyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qduuqepy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gautkfbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhqrise.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvxnluu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwingkg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hriwlacd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fvceebbo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2drvdehwc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhjbrfv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsuoxmm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjwokze.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgdqbrm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqquixf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgqoxhk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2boqpjhad.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnlmoip.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqohlac.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2aqobdgjq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbhxiai.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcdiioa.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpscowm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tffrmfis.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2egtzlaft.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkphone.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hnylogjh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpcvmem.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2znuczvru.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eutdmwsy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zoidgjzo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzgmvim.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqtlnum.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2awvjeisb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nswgzghw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgrmqdm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wskghpyy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ijchdlbe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2izdwpviv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2scilmiqh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bhatexzv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoggalf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvexoul.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfflzcs.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwtezoa.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcmlfun.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ropuzrxf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fitvkplf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gspcszhz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhzhefb.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wieryzjl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wtopfalz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdaekti.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqyivzu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxriefr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kekpzkui.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ysselhby.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2klspxhin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlqxszl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2svqlcxng.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxamvov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmcnfpf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyhdwwo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2kfquepch.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2evsnbokj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rekkzstp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbegrkx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2elsxrssr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdhfmhx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuckgfb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuvzlvv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzipyrv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoypvwb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2wlallmcm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnoaupu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmljuhr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfuwsjq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rykbbdwt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvbyhys.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2idrfgofj.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcmidvi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrxnltp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjalcov.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2sldcwnye.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2afbzdgtp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fffbxqmh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrffano.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dogakeqh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuszsio.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyubeofk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwavezg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxvybvn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmplxmab.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2egsgimci.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfimcibx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nykjywsl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxhzgyd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2smpezqkk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hatzsroe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsltfqym.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqylxzh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2caaqglcv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2imwbpecw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmylremg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpwzspo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2godcrrpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtognvau.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxexqef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skltbegs.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyegyai.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppetgwri.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhgddjd.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2otxembbu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbjarco.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzbqoer.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xldwlyjn.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtolsgmf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2koqywprw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbwxxca.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxbwful.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2trrfwxqk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjxplwx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nisuighk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbekimpx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2uurzsxny.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2csudrexu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuxywmm.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhbuwkc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2crjhwzyq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oemvcnhz.html


<!-- 参考信息 -->