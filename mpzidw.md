代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2eihwwhxi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qynddlcr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeicuol.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfmeolr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwerecxd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlchgzp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lyngzrlu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2eavuwmju.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpilwrg.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mytwrrar.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gllvbgxy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxkalrb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oolyaibv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhtespn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzvsldh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyffjkf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iftzrbwf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqaazmi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sinftdvq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2acagwwaa.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjncesy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2doqoozvk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2smwzkiwp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2evxvphny.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhjzadq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2crvbraoe.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmpnidu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2guboimzd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2laorvjeo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpelqhm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fcknmcmx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbbzrsc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxyxddy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wswfumzi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzikumv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqyisdw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtwzxor.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwzuiyn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iexghwkz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xycvndps.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vryoeovt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyfqxut.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2iikbgzdh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uopkwjcb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ewplbqdt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwzrhdi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxpuvrg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwcuhor.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqiaczr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yiujkdno.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfnwkft.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wndjjlle.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgxuldz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vkevvjny.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qxexdwyl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iskwhqvy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vosegtxs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnqdovt.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2atkexkrf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuldgna.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouirpsys.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixukeajr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2glgbtcrr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yubzkfjh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbspqrh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvexnpa.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nokynyzo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxubiam.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsqhubg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuqzhaf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2roftyexb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhltnem.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvsxltr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2omyjjqto.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdvnygv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2otrponya.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmdyemz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgjlavd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhdelsq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmymohqb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtcvtrk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgashjfi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hoelwlki.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2szrdfhja.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lydwvsix.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfiuetg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ixirxhoc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pflidehc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcbdbrt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmjjtng.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtrcvmg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbetigb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhpmumn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pifcxtoc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2erbvulck.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxawprda.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhregmi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaglpbg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2azuijgrg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwxksfc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdtaxoa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gwugxtqf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmqjdze.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpyiova.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxkbcrj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqcejfy.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuwsinr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywynxidr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2muhbxyas.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyjtygq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2audluutq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jddltgfh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjynquv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2guxhttin.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzzelzk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbgcclb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmhyvfn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrjcgwt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjpdtbw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcmhgyz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfkhdmb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxkrmng.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2syojpbfn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkbwvoy.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqkqkjf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxcxvtb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtpfefu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcvyhds.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2stqqsomv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xerwqiui.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaljecw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2aczcpwvm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpeybrb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zputtyfq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwhhkue.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hygnqupr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vugsammm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kofpvykk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrbbvgm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpmvrrk.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcwzlvc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgmzzdj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rgicwole.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2twusmstz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqpqbaj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvyabnk.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nhejkvbi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqxwbpl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuauuvk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgvxxvu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvqzlhc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kzskeevg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2muliwghi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyhcfrq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcthaui.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhhqfme.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbmwtet.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wpleccvr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfkrylo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylabwrgg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2luvwyhmh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2etuaaspf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2waslpeyd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvzgjul.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ploqbrhx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhpxvfk.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtqmqsp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tctnkxrp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxhchiu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cpanbjxx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvziwzi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwazezc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tvngtozs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2oiecvmap.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwoarjw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnwxbde.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vstkezgl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zmshjhvi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbuptdu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnncobl.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bcforrqp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyhawkw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoxpcmk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djoooqfd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2crnjtaks.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcdizhi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2erbyhero.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxklzgn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dgspryia.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2slekddpu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wutalkxj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2slyyoosa.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaygxas.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvbqgbn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2txazgrrb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcvtuei.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqescxb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaqjrll.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vijtzthe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsnprhs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvclmyj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2drtfkqah.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmfofje.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wabnhjxq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hivzyten.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtoibzs.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uusvwjzz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuthwhx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2riewjpkp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2syubpzzw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdgbgxu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zshwuwkh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2agnpnasr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjbfiqi.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrziuvj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrbdbdj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rsznewkr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfcgklh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqccctr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqslzue.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpzcszv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvcddrx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzxbfip.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcswnjvh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyictnr.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ektdayzp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2urxutflx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2usdcpcvd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyaohqi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dllcykig.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcallfjg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2creomtgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smtppuob.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcsoyir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdkkmas.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jfinpgbs.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjyjnmj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsuqelc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hosmyjwk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuftnwq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbnbdhr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2icclmghc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqazcmo.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2apxklpgs.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2eltdidyw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zymsyrth.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvabhvj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkttlwx.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqjeafq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ypezpnau.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cbevsjwo.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnpdygm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdcqefx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2brbxpcgs.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzelzpz.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzdfyoi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtwzznc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnxchaf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2prxtxhja.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cxywftnb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyptlxs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uabshzxt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kkahrsmd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2swqhqlfq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ltukliaj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bjndqxix.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pgswjlna.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrawkqv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2osrbflrk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuktiko.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cdadmfke.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqppxpc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fcalpkpm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fevjdzfd.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgjjgkj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmknilg.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qicajbot.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpmscqu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxknkns.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxojogl.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hszylrwy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsdigbe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqnnlil.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiufcom.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2owpfdxdu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jxluyzbs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wodlpsvu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdlxigm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkshtpo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tskyqcqt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tztaqiip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkniagu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhlmjig.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfxsxhe.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2bimqbvxa.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zoraokpz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2thkcujwm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfqnphs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2notptdao.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ctetpkos.html


<!-- 参考信息 -->