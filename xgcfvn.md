代发 wailian999

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fikhmatg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdovvvly.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxmiitd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbfzzom.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2joqscing.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2liqerzyn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhrhqip.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdglofk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hstmclrx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvqgncf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkdmfit.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2aosvwzof.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bthauweh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyztdry.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbedvca.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncszecvp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxrcrrj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2svtkgxui.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vxepiiuw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjfdadk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgcvmke.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bimbsokj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2npdgyfxq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoakkbn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zicowvdw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoelpky.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fatowvvw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2caphlrvd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oofcfemv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzwdisw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2scuohivh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nebqhexf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2njovixom.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhzwkne.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fyepzjpy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfvqfpu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbdoirh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2agogcutj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrnjpgq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcjaprf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdwqtae.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bactiedy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zaixocjw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2picihcfk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cylnadix.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gssiuvqi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkhknfz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2spdxpmmx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrfyjem.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bklmdaqy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2inxmgyfm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fglgsbzf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzmsxqv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2peydushp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dntmnueq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwejenzr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oaolbkfi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbpqsnx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2euxntkrb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrmxhnp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtfhnmq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaiyfdc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwdcxfv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwetneb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2diaqxstg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwbhxkm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbbcwly.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkcomvo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2viklzzux.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpopcyl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvqeuwo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dctnerdm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fabrjzyq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yizpcofl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfygfymd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kntblnbw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2upszoqzy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2llhynudi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnbmosq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsowrpp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjwvgid.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lscsozgm.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2krgeifye.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bezofebe.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eflouppi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2exvveabu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vcghevii.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbljpjc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbggmou.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrgcnvq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2adhircnk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylekdjmj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zehgglnd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaddvek.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjvvbne.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlcyjmo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvbrbim.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjxjvhw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfydtuo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cepwnwvq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fbncfjga.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaglkiu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ahftfbeb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vksgpabk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmkozfr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdrfimy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2saebhynr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2artuhqhq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yyerwgui.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2idvkixot.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2snplraoq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2umpzabxn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tymyoisv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2atbyvwgb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdqhytu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfeqbgy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrkjwhs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2osjlfngh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yezrufye.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhxxggo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hcacnaxu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2atqodnnp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfcmion.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvbykcu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2odmykzsl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqugewl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrqxblm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqzjfkk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sodtnizz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2yxazlmvy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2uikuvqdz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2woatomhe.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yijcrsgn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdvkavs.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaijibu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2urnkjutw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2thucnjak.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2atzuryqb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbrupxl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhwlnhv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fxadszth.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vgevmdsr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyyvxhc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2luceimhk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmraawc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2thpqxjen.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tnenogee.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpzmusn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkuhowy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdoojog.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ajublhmo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjshqcq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhhdiyb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmjljii.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hbspmwpv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzxlkqm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgrhvmo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ptambhdu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdzgzxn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcithpd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xisexllx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqkoxsn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2maggmjhg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2izrrjiqf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpeudtq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2utyuxghy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkaruco.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xphkoaiu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrjmcbv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sihorlon.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlpxmdt.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nakydcsx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ovktjwyu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfbhpmv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wckzoota.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhibibwk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2akiuksnc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfebrofj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2spgqbnxh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ciknemxu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnofmuu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aznckrmg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nygjxdrl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbrepnr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxxxtaj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbptkmm.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmruejdq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ngexukpj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2avytpdrv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oamspkft.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2iffapgcx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcjxnmp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zzconxaf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2soqcfqsz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bejacmsu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2biydilwg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfyfpwr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwoitol.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbtsbji.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2skxkvgxc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfqqdyp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiorfhd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrrszho.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjdroac.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pysdiikg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2amljzyys.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ooekfffd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcvgiiu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uscorfgo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2juqmokro.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ablkxlpl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lypomrkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgapwhpq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2orubllum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edhzbmmh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2okrwkftw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhhjjcd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdygvhd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbvjata.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2foieaptj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlpemjq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlhhfbk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyijblz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxmkohc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2orxrzkqa.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2caoznlwj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqkwrxf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhiwhql.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xntutvdz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qcshmxgh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnvqlag.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyrdfnj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxxoqhl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2atheelnw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2abnuhcgb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zymcnscp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvexvep.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeoicvz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uhloktrj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xoezpoal.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2btlvasgy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbecnuu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2owbetbnc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2teevbdkh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgcrssh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2atxmjdnk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tduoxoky.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2froglqls.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2blvskpmk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsumohu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2elcwmptf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2egksplmc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dwprslzb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnrswob.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2psvfehbv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvjiboq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkjdmhn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyfcuot.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ybraxhwz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uscgflom.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmheyio.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xotrpmdz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2cvphjgsj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2uocrxdbc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2sagvpgbx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2baawtdzg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hptchezf.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnzzbnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrjjrkp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpaueqm.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tdksefim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipojrcot.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kygivbes.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2agimyqvh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwlzxsk.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2edtzltzp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2keuibdfi.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2emqxopdu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfwbnln.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nmydztma.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwlmclh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgsmjez.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvcuniv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2febrsrmw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2mablzira.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2oulcdkhw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxmxrxx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2hnakdrqv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpxbgrf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iniikvyc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoxesqj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2kspjzmsf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2msojwqeh.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuhyczu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yvusdfwe.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oimmtelg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvzqmzz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoshuak.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aamgwapb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqzmmmi.html


<!-- 参考信息 -->