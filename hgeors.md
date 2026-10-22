代发 wailian999

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqxkdux.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2txyhlfke.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ceepyffo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbfduij.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqmcfoi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2omdqvfbz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zacjdisb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2paxkhrey.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gezpibpy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2agsouwlo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2snaxztxn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2znndiakf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcevoso.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfyzhgv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2erjukitm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbjsfkg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsuqtfm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vshsjexa.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjeudxx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wahdpjiu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2blgaovbc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdfchvv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2odkiggbh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkisutvv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpcmqzz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbaskbp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbadsci.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wblccwia.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xonyauqn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfzqnon.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhgnonh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2twcbamya.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqwocuk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsqzdum.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbjasjd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2swrwxuqg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gngtyowf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2axnulcgc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2amhlqlll.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwzijny.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsrgcgv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ujofzjhk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2stzjxulb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqruvkc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ltztoroi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaynmdwm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gflofgut.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmovtkaz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzibbuln.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2frktzrgw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdpnxuo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyineqn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbwxggz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuxugvc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiqcrob.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2caludzdv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bxausbqh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfvgaxe.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdxtare.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddasrylb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xusbfteo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbybyeg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cdddpdgs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2umsxnsta.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrxdyzc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2cesvpvov.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzhqqhi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhvyqvw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fttdfvjm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdopyejb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qqupoich.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tjahffvq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mxczzljs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cggabdqm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oskylrmh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqelbuts.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkvkbwl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2eetjqahx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwcowwr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcooskw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nepacchr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2upunacdk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqzsoeg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqklrukz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mavoatwd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2djjxztda.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxavvtj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlvpbsq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfpdfyy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2omkvjcos.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gszqgykf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrfropf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwsgcpk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuooxos.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jnplklro.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2glfjmryg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaolpuc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nofxzmqg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuuezgg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmxnulz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ppemzzby.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrrjwmq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjapkhq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2skmyihrr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ddabdiyk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iopugytr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kthxllys.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxsinmg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaioymw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhyffkg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqqppeq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmaxzlu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ryadfvsd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2puivbexl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2elkrwtdt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwsmxba.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mypmyrap.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewicdwtv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uuswfeun.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fbohvnem.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2stdxdhet.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2muhjeiht.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2csfkfqls.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hpusxcbv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2azwapttq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdznssjg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvvisav.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsaboym.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2sotpfclp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkvbjqj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2riwfxwsd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwskzedw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbvbhih.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2roqtsluw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pyblfjqx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gkctmqok.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmlshia.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrxagww.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdicrvq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhutnek.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcagtqw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qufjceuj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ouixzpxu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcdxazh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cajeysjd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdmvmow.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gefmqkmp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmijntqz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaymdlo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ewijdxbs.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkyztia.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2udgdwrjp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsbyubs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkpbomg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkirlhz.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfiygoz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbmloih.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwrqija.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpromts.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkxgytn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rttfltxa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2psqwwmwn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpyfrsk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtnqtqe.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cczlnqmv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcskijs.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sedmedel.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnvxtum.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwevaln.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iauesxet.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpfhyxy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cinpbgme.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmsgqyd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzrhvqs.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xplxylpw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qilcxljf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2djzmshfh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjzfbon.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfopupa.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmylsfxg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qywqazov.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2neuaoswz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lncajlxv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvvzlos.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2axovzglb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2crwwmvrn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdexjgy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzctaoc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdslwle.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2azswshey.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rqowvlzj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2abnblbxz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jutmeksa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuynamp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtnivxq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxrfrma.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2embknjla.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbeyfvd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2sokuxvum.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pgahpwtb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nawcxdsq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nayqhlis.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kldugmuh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuqwbte.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ulegwjej.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2iofolszh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnosheq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqheclt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jdanxmet.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nidqkfbk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmwokkc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnonqil.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2edzesxkb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiovwvs.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2namrljqe.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsxabtv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2toayeoys.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2liyirsng.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cujjkvrk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xprcbfxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dktrrkyw.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyetfid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoddghm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuelsmt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rucyithm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2alozdckl.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrlzvva.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzphqxo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gslkwdth.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2flevudhi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlyyopa.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fzatzuxi.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrplhgf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsdumdf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hiexzqpu.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xjifhjuu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkarxan.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqulyjq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yehbkmwe.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2siysurph.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbkfasr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2imwdzyyr.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkqcdwp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbmgygf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2abbsoakz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkohxzi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fimvwqke.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2scrxcaar.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2dauokiqc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jkepwnoi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsbsniy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lowfjpgu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjwdpai.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpstzhd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzksphg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvluipq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sgghzpby.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2marqzofl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoslxnd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2digmcmyx.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2swdpjeux.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2abjrngib.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2liberbib.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2clzuaudu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkhqgpa.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jnedthnc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2coobbjdx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sewwyvyd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wzycqffy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2selkxzhq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jenvwcnp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nsavckxh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gqorfaoq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtuetrx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzrgfzl.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkwckpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stunxgbj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfgeswh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2twgfqdwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kynsjxtj.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2chqqeine.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpnmpki.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2haaidlqw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvfzkhq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqghebpg.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2eryokqqo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhkjafi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2vakwskir.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2foqskist.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jtytxtwr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdapyba.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2melggfjs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsxpmen.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtajtqo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhuawos.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2oxppcuij.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2poawzweb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrkwdwy.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxbzmrq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvqffnc.html


<!-- 参考信息 -->