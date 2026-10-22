代发 wailian999

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuurlhq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2darritqb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiosfsg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkandbef.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvnjosp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxunskg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2upqalcfm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yftcyhsi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jazxwpwl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqscosto.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfarvvo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdjrvwn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zajqgzjw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sybrxlyg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbbyctl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzivqef.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvyibdu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gkimytxb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxaxgzi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdgbekc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaxzzxh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2czxiclmg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjkuguk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmhfeax.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mivkrqtq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuoubbf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2becuaoxy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyykdlr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zowgddjs.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zbymnyji.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiclwpt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdyxwgb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nopkhpps.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qddutjuk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzlhtua.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ivczxenv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyqxfyd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkydnre.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcczyfe.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xonhvmdl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdkkenw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2loufhxwd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbafbnu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2socjievw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jalxaxiu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gplwxsko.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxmoxga.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfeqnwv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fltqupvt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dibserdv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hslucwbk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewagjqlu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhllpxp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vxskyslr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkyojql.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gebhdfcu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiaumau.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyomlau.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kimtjhzd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgynnlk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2puwxnrgi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzbcbiq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vgonmhrk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuaicxo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ecptejkm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjawmht.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyiykta.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prizldnl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlvqlsq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2okjminnx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrraeih.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2niuvnfsc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nccdlahf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiguemx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqiuyzk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpxvdhl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ammjgiih.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gufquwaf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqtkshl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiiyxzi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaomsnu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbbynry.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqcvzsu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iszeowxx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiqjzvu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2onwzlgwu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtqhnzq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmysdxuk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2amzrslqh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhepetli.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdimeii.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmtvdlo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzcucvb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgeqblz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnzkkmw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2eansyjoz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvkwper.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wikqjsvm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uynmkzjk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgvedvt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2eakirrlj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxszfod.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2djaebzuq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2skutedyw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2szyqscej.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2javmguve.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zgirnvjn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lowkdseo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdtezwv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjmvqbx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2orrbcxmt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqwstxq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yfexcvbq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyppwxj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqyozgj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhqlnrg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2caezghav.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjjshlw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnryeyq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2liyfrtpi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjyszqc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqhylvs.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2okwbqxfg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2uealfpwn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpuxzbj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wibaxlax.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jrerpmaw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpooofh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ahklwcuo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmipekp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vumewusu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2aujqqerl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pdexbgvv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hucxlrul.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvonfec.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlbkoie.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2agrlppzb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmdfqjq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2maisfuia.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2obkfugft.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsnfepu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2viqiyise.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdwppzd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zavejrfz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2regmidam.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwapbfl.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxkkuhi.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kghekpxz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxnwugv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvlnykl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiekjla.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwtkzja.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2orytgcco.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dmypigjp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrocexi.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hueruqdh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyfkwwk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2klnvvwes.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqizhrn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxosobvj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2njdzdrhk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2raacgrje.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gcohjbuv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpberhlq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbpocay.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlxjwtw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjuydiz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuvjgrn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhapzxy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2skmrvikg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwqehjb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2omazmtew.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vktkvqvm.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2osxtohgy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2uunzsnqy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvfbyis.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xtysavba.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqaxrbv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlqihwe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gubtunzw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2skennbqb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2riobyjtx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nokgutdh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2itputwac.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2priqyuoo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ensagxid.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcwizvg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2udezfdux.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2miknjliq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfnhkyx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2iawctjzc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsxfwxs.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uojjkeub.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeoteap.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiwebhp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtcxqni.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvbjlde.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbepnntq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhfrqir.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsvswlf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2utitludi.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pffngixj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hulfmhyo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyorwpm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2owyrgzto.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pipbtymi.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqsvxqv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ralpssfx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmnruru.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdnipje.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2scpcmdpw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mcisesbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcoifkl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvstnyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsybrsc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vscgugdx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2deszldlb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bpidjozu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgfouwb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxhxtum.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tflmfhwq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oirfutkm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtdfztk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vemdglbg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rwotzhlv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzpacbd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ojknsdyo.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaxcpwm.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2skiatydt.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxnykpk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xitvlncs.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmtkbiy.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2surzwjnx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gztraysj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtcofpj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrpibbx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvwpour.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tybmiayf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cfujdsou.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbklzuj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2sadtgycm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fxryqzam.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgdvzbc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzlafzl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dnebtkbl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoimjpf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxhgmhr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsquegt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqysixa.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rfehyvce.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2amgyakfu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvmymlg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2flffiern.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vwibkcmw.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2distuwqo.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ldczbhdx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bvorhxbx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmncodi.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhrkotf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2drwryatw.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2cklieblt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhnkqsl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2cusxwsxo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpoprvo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2htqmtgvm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2okgbjjdb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2blpcsogq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2yzljpkwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kudkfmhb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmdgols.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkhejdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vskavbbb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsbkpat.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2whxmvwcd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2elswmvnn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2unwbxsrw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggijvwxe.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2adgamcyb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjvvywc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxgjuod.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwtcmwd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ghotwwvz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2blywhuae.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2afqraxsx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhneabs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2cswipygs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bzukwutq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2eizfirgp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gcybhbnk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2poylgaqx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtedrad.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhakoth.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vponkenv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2kimyombu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2olgvkylb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfhvwui.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tapnobfc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzegnjsi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gievernc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2muldqwjp.html


<!-- 参考信息 -->