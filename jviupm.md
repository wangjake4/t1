代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uroahges.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcamamw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwhnewk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2moitdamh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dffvqdzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vygmunhm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfghjdva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lralrzxj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vnavgape.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aogxfpev.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ygehaoez.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2knjjbazv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrhacgb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyovvkha.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uycdupfg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhwxnfs.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2exfuxwfn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmydimac.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqqfwcx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqnjihr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oglcavoy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnjzgyj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2duphotwe.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2htpybyog.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwoeiyf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzisnzc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rcknbpft.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqxdarx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pygjsuli.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2krfcezxp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uticyrpo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2guzfqjei.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvjhide.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbprucmr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xkugqurq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2snmazlam.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwkpvhn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqtblob.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jseussgf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyvvbgb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xwujtknv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpliemwp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gblastkf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2reatnddy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnxgazd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfwfmts.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2inhjudep.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggopkmtd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgyknxl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vehwznfr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzpqxfp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2brsqkdhy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opdocboh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcmmupz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2keaswmqc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2htpldfen.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2eltuwxfd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmygobql.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeuikgp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2whamvdao.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2msonnvzw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2gamzlsof.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvkgwnx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2agxnkovm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uuropgny.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2aanowkuq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyvmcqa.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2upnxwvpx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2picllmgz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzpasxl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2abyllwgk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkuprpl.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qesyyimi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvvzdiy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2txsfnrgi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlppquv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzotfkl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjscxmza.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oforrjyw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2csbpvbcc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jobjiqgj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjokewn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdlkkxc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wdudxkhd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2geyrmoxj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mftzcmab.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjgizxm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlqqekh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxywfas.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jskuhxwo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gewqjknp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgcgreh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxuhgnp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2eggltsyo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2svnlwflx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwwnsnr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlcftrb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpeyjfu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2brnfewqj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyhacou.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvycerd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjyvykt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ueajzqjf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzovsay.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2msxqsilv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhfqvmc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkojjuc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otzyneqj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2szoqfrka.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rotgxzdg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmoamhi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2roykxtph.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bdybxinc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2frdmvfwm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkmsamc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2skdfdisi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2odrmpdvl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrzbefz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2srfhncue.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbmvmbo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiqvlxm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrrdmst.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmrjpnd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcfjoed.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsdlpaq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsshofz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhjqpps.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlekhwk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmsthoc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxfjkxl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmtyppu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsuzkrc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2khkcfkrp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2atffvfap.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpztppf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsklpps.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2khrgdhgc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjykycq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2izvlejcf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdmtjpx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbzbpvk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcogirmu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdokrmx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2binqwtha.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlegwyy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pydyhbyy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhaxqij.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpjxmlk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2keszgzkx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2deoedjdk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkxygnf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qfadksaq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwsbaap.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ribghzbw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkanukn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2boktvetq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbosdqm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2funtyzec.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrzmesc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrzmojy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2otwrtxaf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ksubikcn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2euptfavq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkqalbj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2aghtayft.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmbbipu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwqjyav.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbklxfp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2abcnqokw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2smemtuiw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxzhgqi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzqrfha.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhqdmmi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2evsqssix.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmwjtpo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kijyuols.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2skqouexm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2iitlzrwo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrbrimj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkdbtin.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhapistm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pshpyepv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcgdlhh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiummsy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2onkdqglk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvwlubm.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qsintgzg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdewukl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2expvqvmr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtxgwkm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyyuuzm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2djfgtxjp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2blhgwuqo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hvluyvqo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nehusbqf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nleeukjz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2oakcneju.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2owlgswtx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqngchp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzedmcdw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qocnvlnf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqgjhuq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zzigtniw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hmixxlfa.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jziexwyb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbxsqfa.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrtuoic.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyrziyd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyguqmw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2waqrpmhu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2venndjwg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjunfopi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjsyzlw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wazxpjxd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qilpulof.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2swmwhrxc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzbnser.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvruhiid.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyfybow.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvruzwa.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnynjod.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxajyzw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsglyev.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoktgwp.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sovoeldl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqemgujc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2okdbzubt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsgqrhv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qccyojwd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxhjglz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2facgaeti.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyyfwxa.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xcujngdz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxdvptn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkakygp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eukkiyxt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zgamscge.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpipwrxh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvenyrk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdrwrzj.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ckktsazo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xbehyqmk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvcdavx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxllmyg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uilqaxnt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ktibsszc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdklexb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrdxedf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgneqtz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yggpclvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjlrkfi.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xodfgzmm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rwixagnf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcqahyp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzxpxaw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mavbldgp.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbtrfwj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wgojhebw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kicobgsu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhzwdri.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xthcmxmd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ssutkpmm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2svsxypxh.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hxswqtze.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzldgmc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwntfsk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ktilzdti.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2odpyogud.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lekghybq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqegogy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dqddwbml.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwkvpqj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvnqdrt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkujoqf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrdqjpc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxievlo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2juxszoas.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxnitka.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwxyhet.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bsifhhlr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkfjovm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2buhercyk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjuymoh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqurnxs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqdkxpe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2poggqwgn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjyxvuo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nizbqkvw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2amcxalmp.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2svhzbjsq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nywckozo.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcwravo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrtxkcz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vdawmavk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjfzyar.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wlojslbc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ryijiauj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2myobfvdq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqwtapo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rgapfhrx.html


<!-- 参考信息 -->