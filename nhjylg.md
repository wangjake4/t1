代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdidlagm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcwipqy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2evvoludz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cckwacyi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeivtxa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeztafc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2askvaowg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2romgufyd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zdotyuzq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2smsrthfn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqlgrlu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcjgkfu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhvwxly.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnforesl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgnnzmj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfyjohi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mamtsgps.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbhbafm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wevogdif.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2flmtuapd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrdzlox.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rusifacy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2chixspyr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2baaaxrvt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpobvgh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gedeimoe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jiidjqlz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxqpcxb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnjioss.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqkaxnr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bohyheou.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gejlocni.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fytofotz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeezrmz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsvdtks.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2znqesvcl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfvthra.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2njkafvri.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjdlbad.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjmogwd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhnfyte.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjgiaeb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjcngxp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2shkzrktt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbpeise.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjoight.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yayozwin.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmqsdgj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2telogzuh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2eurgayvb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2atwbkajq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtrpjxi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrpxkkz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbrljhp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2icbbytfr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkftfczx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kkveinzl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvnfzzb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zqctnbao.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqfidpw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kfccpceh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2opaulxgg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ofudwnaa.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyhjfxt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2yejebgvx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2giqulcfg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eelpuefr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2uferirye.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2snapwsie.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpxzfue.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxnfgfb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cydnydzh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqwlpsz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfoncrp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqejsie.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnozsbjn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxopjck.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaoyfsg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2awmtnqby.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vjelqgmb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ojohwbfr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbawvgv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2misiwplj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbokougq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkyvfmd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyvggmq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2eazzcrdx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bflbikfh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzrymzs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2meqmikjs.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwntmsc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxzrmhu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uisxybag.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llgpbtvx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zcflwpws.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2skjyxkrk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jalckjpb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ythhlgrp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiqgjjs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvyvqpb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2okalajte.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2omqoyirq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzjgxmo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmayala.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sobitwka.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvibwwi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaqyxhh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2orxqovfe.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tebwpcbz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2osnggrky.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmigzgd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfrzczc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uaszdsow.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlmbydn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlvwirm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzydhhs.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxirqjs.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2btyimlhq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfydkpk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2drxgrwur.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlaxypp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2btzsxlxq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpuicix.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nooakpku.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjyuanc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhkjaal.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2prdaawat.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfykjgp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvpigli.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgpjgqs.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2myuzctwx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2zeadfslf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2euhhleld.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsciwyvj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dedisbql.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjtibtr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cecdbcsm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2geamxgll.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjacwjg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfzjkto.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2exvkteel.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrnvqkj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpshava.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xihthrbx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2twgyfdlp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lolwseqq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2poybtfka.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nklkrtgn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxkohqj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqzmasd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjjpndx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbgktww.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgvuysm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2sspjhtjj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2adpvgjpx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrmhrjr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2byktkfrz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpstltd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuzxpea.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhoejmh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2skoavdbr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2yujfdqrc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2uloyttvp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrfkikq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdletrp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pzldzdps.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgutvwq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtqkuqg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2eujysyaq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgqzpmd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hivlgaby.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tuplneip.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2darvhkke.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhvurhb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlxqsde.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpiykxe.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiojypb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeubikf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yhomquxj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2komvzcrk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaesxbh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzyarsw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcqsvnc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxjrvsx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgbznqg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxuaqrw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ntasgezw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzomeukk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yszzdsrn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwdzgxr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhatlxg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvzcpbk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2squhnmuk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrqiont.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2brcijcpn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrfweiu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zamgfbow.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iryxmrxg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2atrwperv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2viovxblj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxiacic.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2acmvwcyf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoutnss.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ektyvgqc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsarepx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlukxihd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpbwkgo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcsuskx.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2epkarfvh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pphsekvt.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kknwhyex.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoteabk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lrndfyeg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qiukwhmo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2huogcygg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2awkwfmfc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2byjtdnqv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mszdhcgw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfdwuvx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqancvz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsjxutr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2djaivlqo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiudvjr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vrexmahs.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhwncja.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpjxudd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2znryjksf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hanonaxr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfhoxnj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tayiijcu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mynpeamj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmxgfvl.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2foqzjbaj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuvgqpc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqdigom.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awrhchqx.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cljvribt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2szecvfct.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bcumywiw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ihekctng.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hjflhyvv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzonufy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvqdytd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ftstnsul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlsyjql.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2phgcunbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjugqgg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdvpamj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tybjadso.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2metoxqmm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2izzidvkr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qcliwssg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2brjtooth.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hbenzwgl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpvjgtu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mawjaoxa.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuswfhq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xrduogdj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxudxba.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lknozugz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2njlfqzzt.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmsxibe.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqmsjgf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nmisvilj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhvnyhz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhynkus.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2stbvdflf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiybutj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2okmdfpzb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zlafdndk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfjzfve.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnzwnzi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2kktlznkh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbbuefw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xzogtbxo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ydypeazu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fxciptal.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hnipuker.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbpjzis.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjcoevo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmplbtd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mslwryeh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkpxeoo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2owxyyncp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoxvrsg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bymrjxsi.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jeshczzd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqqvwwq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bhautkox.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jkibmwgl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2swhmqqut.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gibyznkm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvvgrop.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2prykygth.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxotonp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ucilnvja.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdoolcw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeveyns.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xggcxzyy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmvpmfi.html


<!-- 参考信息 -->