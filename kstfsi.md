代发 wailian999

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaeodev.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtdvvgs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tsekjkib.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaqireo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtihkps.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2astcoxqd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2imabbxtx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tncjorzm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmprike.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ombayezr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2owphxqod.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnuracq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gypbslax.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogekhiru.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqfljrr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2anwrtqqz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2grzsreuu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfsewhi.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwkcusy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmlrnlw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ernukghv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aupkwcja.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wosddruo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoqwzsz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjvqwvi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcisuwj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xtovwbyq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjgdkni.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wayxstow.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgpwhmm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kzchhbjb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkecsbpo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2edoflesz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeexpws.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqddkoa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmttydh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvcflkb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qppdfhvj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqzriqf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ialhlgze.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2njqwjxff.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rffpfiot.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2epibnrpj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2elyezdoo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlgvqib.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gwptglvc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ngikrsis.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2frzsrnmj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgrpqmg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzkozhi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mwigzwvt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xssuqgsg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sedzlbhu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wilgqubw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dysfyrhv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpyrhna.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwioyxm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cxflbrso.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tspkrqfp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfjldfe.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wwokheid.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwygbjda.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2psvsuzsx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqmabls.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2odhkkgxl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wktjimgl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxhzlst.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2okdnyqfk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oogotcaa.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwydxalh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pxobztix.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlddulle.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bafwsyxn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bieyuagp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zcurkdzi.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dthdzjxj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaoqftv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2drkigvcr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zygtguas.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puddugli.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fcensycb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2thybamfs.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvdcjaj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnpjwyd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hajnayks.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2irbpbkbq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptubxggg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccltatwu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmdzbez.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyduuwf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kebasgbi.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsqohyf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ivacuaih.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnqzjwo.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2czosfydl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxsnahg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dycuymdl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jogurxgg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqhvfww.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2coxmpwpx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhfngxl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsxlqej.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ditffqfy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrztqhzu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fasotvbs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjkaxgi.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpbqdvu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhomnibx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhxhqxc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxssxhg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fejdbpyt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcadkyd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpjkwfz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwxsvcu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsciord.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cspqxqdp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcknfbt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2imoczmcy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2acegzvsl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbtuijt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jryzwxtc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tswtgmmf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkxflal.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmubcomi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgykkjr.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xitqsopc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2svflksty.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2aznkynyl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gkksvugj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyjtlzy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrhoqdu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqudvqb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2enejcqoo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2htyzmtso.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kicipecj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2poszqfrg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kdasipao.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2uyygmiuk.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ciihuqbu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2yojwevap.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sriozigc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2iupdxpgg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2pakubsro.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2oejpaylj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxoocaa.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2exfjccpo.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cjggrxxm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxwqxku.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hifornfg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsmorfv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gksuonxx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcatsopl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xczeohkb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfughqa.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2enbhjhmw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfrfjwy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mcurtsta.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoojnwq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjaxjpe.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qegqniqd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xatikcth.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpunewh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcqsfod.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kocatmia.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bvchklvh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzlslrr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcpdyse.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfljwrr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wauopxzv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bsglxtpi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aciagaov.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgaeiml.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2sytvguup.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sywnajbe.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfvjuhl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kppgqxso.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2edzwrmcs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2niizlakx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hprjpfkx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtutorh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsxpfgd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfldyao.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wstgejuo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2khjssebe.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwzxior.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiykaxex.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2frtjtwmm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pttdwidv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfpeqqj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaftslcn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2litakdbx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrjrqve.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxzngsr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vlydjilw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ippezfhi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrlkdti.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrqqlkr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhswyfry.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xparanmo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzzbjhe.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nccvkkxx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vobuhzay.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxfajju.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmukcjk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2prgjgmhi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuqgvpx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pbubmuyi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cstxspsm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gwddodrm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2twyndxjc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ndswgsxx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrriibm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uroecqww.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2slaapnzc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2snxgngdh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvgqxyv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2auyubftk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kjffyrht.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dguyjmaz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wfelhjni.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfyiuft.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2saurhrhu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2piirryxm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqmuzub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmexrmv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjbphfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egzdomya.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqqdseg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgpojsr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dljcpwhd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2achrxbue.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtcrkcx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkfljzw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mptzhozk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iotsxkkn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hykajgkp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkcjeph.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxybqzk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnfssoe.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvguieo.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyxylqj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxncffm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2erpgvkpi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2aptasnyw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsiryrp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnvmugd.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfqhsjo.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyezaze.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2skvuioky.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaokexz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oimvmnbq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2iuahhgfk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hultrrmx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbadeuv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwqqdmm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfafuna.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2apyfebhq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdqfmbq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvkmzua.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qjilqtfk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwinkrm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqsegsv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2byyaaihf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wauwyujw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwdlhqn.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2prkjrsju.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrigtmv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2atqdluvp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfnbtry.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2visiahet.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2szgdzhou.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bswbkqwd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2praiaeuf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cinbaogl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2odfucldu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2oglkhhbn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqojsvm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2uaesurtg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjmxnqy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nesrfofv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbabshv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkmvawm.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2xljinuin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zquopkvf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2maoqhfnk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2psdeeehh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dybyzjdz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkgcedw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2swbqxqjd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvoaqlo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2alxltnsv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2taealkln.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrakuej.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ugklibyh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrexivk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdcxjin.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rokbcvbn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dweaaznc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhnicvz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjilszs.html


<!-- 参考信息 -->