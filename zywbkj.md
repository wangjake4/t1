代发 wailian999

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xgodvcsw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2htcjactu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mujezatm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fpskkvsy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jihqnwqw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyqunbm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdqzxlt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2avuqklng.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kuupmrvf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nshfimzw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgtutdl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlodkam.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxtdalv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeljjmz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoykhcm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gogiqfhk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2marglano.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2whzvpbtu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hjihfinr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrjgolv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2huyqitog.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jdepbfgk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdpfrsy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2anqklybj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2epkhjriz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2johionkh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzgsijj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjwzjye.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2knnptucm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2joifkrns.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vpelbilb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrdaeto.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmxyvzv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2frjtkwyx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdrlgiw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjfhkvu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eavrbjdp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snpqjkwj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzzpywa.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwbbybw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ehndjjnt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlabdhg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyyfrnv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blmpkdhm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2shfyezot.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2siktxond.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2coyowxvv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buhvmcpn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpvwulx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmigwrty.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzurqau.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnhjzmi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhdpjae.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nahziivv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvnxgll.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlkqgyv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrvbyxl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2irwldytp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwnqxpk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2utxjunri.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgevbcr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjbobha.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmlnkko.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjnvkgk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxhqjeu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcqeorr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ceediigr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxytjcro.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvnefwv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2veaowmhb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiunlbu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvjfize.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eudodvvv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwrvtwf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdxndgk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2buhgnner.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qkybudzk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnupzgbf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdbgvul.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyffjhf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2aadyvvur.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqxkfnk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xfquajai.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxengvw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxhrqvd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwktlnk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2efvncypa.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxeaiad.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmsvqpu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lroxntqc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrxnevn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnzuzei.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2egbruuog.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmclsdgc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpxwcpm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiynkgcq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2brtecclj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkmofle.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlciwqw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2baizxscy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bojytakh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2figvmjkz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sizywint.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xtacqypu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2awtzxwjg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoggbdm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsnfyns.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2efyfzlrc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eipnugyh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qerjvclc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kannyvst.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2olpbnkpd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpqkqou.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2siqpcorr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2itqhoret.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmuraak.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfkoltk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2flshdifc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjlaifc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjitfpw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2weybxuie.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhumlvr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2svfaqgvj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiftsfz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqgaoxt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2frobujva.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjfgwen.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmparlp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2itceymoh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sexlbsbr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rovouyrv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcgjlho.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ophshvid.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dehagukb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxylmbcz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zutowqaa.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhzonam.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwrxjof.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhbpbxi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcgsreo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmfdaxj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cepeycqm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqzpcxn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sddlvbcd.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwqfogz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eafhgvfz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aypodufr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfblcjyn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lflqsidk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxepxzd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdsbcwf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgnwxpv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2injmqrln.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmlbown.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2aewtilbn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2olhdbfzu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyzxhrv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bslmkmfm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmssovc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zkupucbn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2eithwqzo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2chfwakph.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqbdhtj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2aepxthga.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kmduaqjv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2exbqccxs.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyjtatp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ccntkvcj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpvijll.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgafyphl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvvbgbd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjfkisd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2przquben.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2diltaigo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyczqtx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2imkhxcnd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vszuqdra.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2smrirdkl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcstlywn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhececry.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xltwqhwz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqwccen.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2czlfzcjf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqpzogd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sujlprlu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfbnkio.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2avnwzszk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2iszbpnmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfdfcbe.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2agdtmdds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dazpragw.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2sykjzktv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sneburtw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuxretu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcgaddc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jphoscpy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2unmjjfnr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtikhiy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjaovfb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2etixmyqs.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bylkysqn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ristvgnc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2rjprsxil.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pumqhumk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2liputqfx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jlleuibg.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlsnstm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuncwgw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkvispu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnzebeh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ijukpbva.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zhikqwka.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tfccawce.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvurshi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vnssjsnp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pauzjlom.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qjontpry.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cafodqjr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuazfhy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgkulhx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvfcljs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2enihemsb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwxqjfj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjrqorx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvyadoi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgiemaa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lpduoqox.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzqgevc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlrbyzo.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lmamnjow.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzbivgb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cloywgoq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2szcmnnnc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qypnwobq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dafxhcug.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qopibslb.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqzoyme.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hilaimdf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnokqsj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xexnvtvs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfvzxbt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2aatkfnmu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgusthz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzgohoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2saiuiuff.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xavvbflx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2glmudttl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndikhfrv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmamejv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2cwklyzph.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nozhutxj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtawcdu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqzyrzt.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2emcnrccp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuewprd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpcobeo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhjmrvx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvizkmf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkkjpnb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2njrkifnm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2txpukfmw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvoopau.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2fmacutkd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwbgmwk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gwutjhse.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zgesjdfo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jolirbzq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2bbknjiww.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoufwah.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvljpxf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2meironeu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2istzhtmi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyujkxx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfpxxhi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kythudeg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfncjclc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cffkzath.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcekwxnd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dossshmt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eklvhmkb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnletmj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlvylvj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eexrpacs.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcavpxsf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhcwohl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdybgvy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtacaqhu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyldhot.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfquimbd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwubwumf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrtdier.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhaiphb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axqestdc.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rfplkdve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikorfntw.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izwwysvl.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2afcqecib.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2scoucpbc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2axckszgd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyktluxz.html


<!-- 参考信息 -->