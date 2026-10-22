代发 wailian999

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhlipcl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpvkvac.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2svebzugk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsevrwoz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bawbrrgc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2isfjzxmn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpfmdvr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yflpbgrx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dasecqum.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2swpsdjsd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkqtaqb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvfckiq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hglpjwuy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeumhry.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcmoevb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2llruidsp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2icsqtwuy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2avoavbxn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyffohe.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdqvxhd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hofptqee.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmjlpyf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmjbcfs.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gagazwdp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmjuwoe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmhnghb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mfontvbu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnyoith.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlmmyrg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2orxmlekw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2enejoptb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsinirs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zwypuiix.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2skswqbev.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2axvgsaau.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ujghfyph.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2coahhzot.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpejxwlw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2slmwptis.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2quubfcyc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bcudwllx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdwpcwe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkgxlte.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiuzttu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjxagqc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zojmctfw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmojbxqq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqolngf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ramphfda.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lirwilut.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bsswtzmd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdkkeqw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmjuvbt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2epryblcj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jzospwgh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtbrqhk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtrllxj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmrphxd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hihsypcf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aufocsch.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqottyg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xobjzgqn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlkmvmo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2unjxqnzp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjyyvke.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeqkhfh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2taslmpjy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdydmdgn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqejhyj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xnysooxd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pibdylhq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jijljdcw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzzkenh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dluzeewe.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2muftjpph.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpuutbg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2igdsxwlq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmprrou.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yunoeypu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhkgdtz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2knjuxame.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhheajh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlhgjpr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzxwauu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuzbwsa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdojgbq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2whtowyow.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2szsocyal.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjlhwlv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiuvyke.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtjpohf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkudoar.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjubgxv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmqjgvf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sljmcxax.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2syghfgyn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dihwuocp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfgueha.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbhoyxl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhdpqow.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nhudrwah.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jawaeowy.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcoerho.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrvfwcy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfdpjyp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjilmfbn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2esowenkf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcjycrj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kolrtgee.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2oibdclyl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2oobseraa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yigpylyr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bohlkhxf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkvfbvw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ispkuuwm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuoievy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvwwxyh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbxbtrz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lasghwfl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpykjgo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpfslqb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2igflrvri.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kexsrgwj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuilemt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ukonuzel.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nbywmeak.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cixgtvpt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qawqvmjc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkeksmo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ffruczqb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeqojsb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlzpbzl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xisdgouz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzblnij.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdzhwap.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvlfkic.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuozpsc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bumxeefh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfuojcc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpstjtl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeplgtd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2spalglij.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pztweiod.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2deiuqxhv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzkpibn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jkntdlys.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbyzzka.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfynlrp.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmbnpdm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kyukfgql.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2txplhydr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgefhcte.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oinznsmu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bshsznpz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vcynjiiv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2txqsvswc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzyidud.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sfocgmpa.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2roikvxei.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2otxbwskp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xpddzjoi.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqpngfr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hmemtkra.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfezbwtp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2iikaovcq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcenbehk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwglnew.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuiwlmz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcdivwd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfcjhiz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2smshzgio.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyivepl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2owqjlldo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sudlzznt.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvgsjbd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pbncbgjg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcvmqsi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqippzta.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2phzuddif.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpkicyq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwvicio.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkkfwss.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdqoexo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrcorgm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hrczekba.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2srujnqhl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsljjns.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpvqftg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgjuuut.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aidnuzaz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gejepkla.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqnnruh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jehntuqb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mfypjcdu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fukoalcs.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbqqozv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqwmmjk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gelbmnbn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvluxwm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuqgrzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmasnxi.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmajspa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcdnzte.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfiuivl.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bbllodrs.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfvawnd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyibfur.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqjtsdn.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zfelmjms.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hxomfrvj.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ltldegff.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2brafbqql.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uoubbczp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uoybfmer.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2elsozewl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tbthudpr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fujersgw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qziiywal.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gziuuouw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lsizbuwx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfriffw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnrlica.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bywkwzxc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xknqwlhs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsaqsse.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkwqmok.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xphrrnak.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xolzmask.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkpjcyk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvfvrcw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpqizuo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwrjgpf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuspfzt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qbezossj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qihatlbf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hazmtayx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2heebnwqr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tllujpgl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpksqxa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxjwiqs.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfzwguo.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnlxjsc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyspywn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnclhwr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2chzeyfjq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyoigst.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgcljqn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2okniqapg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2koftigho.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjhcojr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2omodwfhj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyjiggt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxtblds.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kognwfen.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2djxlyirk.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvmcpjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knxlaviu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnmkxcf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkcemgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwrarxm.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjxmwfc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfilaoa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zjamxwnw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ralpbefu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhsvvvo.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rrenuyoi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2owszxskz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2udyciudr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dcltldfc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2klmjaelj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fazlnnbb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjentci.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hevhkmpp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bnincskh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2apqnzqef.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2enepyquv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2isfgidhs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yshvesug.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtljdbz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjhdiwd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbpsreg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xgphylte.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iulruasj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeglecf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tossvxqs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubanravw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqvzxav.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpwiqpo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaxdtjq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvxzrfv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbjimff.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkimpvz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjixccl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tysmxcae.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swpqiaci.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjpaobn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqrqxmo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iphrijco.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2atqhhfbv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cylcpyfx.html


<!-- 参考信息 -->