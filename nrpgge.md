代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ospibipz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvnlahg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ultolmvj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yoljhfmm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2owiduvzw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2eijpeyxy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2axcimxsg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2obtmtndf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqakwfu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2smlzeqof.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sefgnphn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjzqxsr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsskovd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdljcaen.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cacwilrh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqudlzw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgmyyuo.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnuymnq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjpshwc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtefykbn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ifethwri.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrykfln.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkfqkln.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfhdbxz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwctfaq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoulivw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfexkqm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxglckss.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hheveifb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcnayiu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhyzghh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgscnvm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kytjmter.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeokynwj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2skyekthv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2brgmsjhj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyyjndc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gooskkxw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzaomkj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tquuyxhs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nxutlpda.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpvydzq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dfurrllx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuijqkp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwcrlpn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gipjhqsi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhjwnbw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaenjdnn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nfksqbji.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaodhvn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2huwwxjsy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nehdbvoi.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gtswlebj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwzofwr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpskopu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2omqgxsnq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fynurxnc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2upajdifu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2suljjzja.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2arulqdzy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bldyoqah.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jewtkvhv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdushko.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fzroqtck.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qguftyrc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmqvfug.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuschkj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtnknhj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gstkstsx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2winjspla.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2juiilqcz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2olawfqyc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrporba.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eowgijkt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2apbjtwmq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjzbtde.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwzxwhj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxqrtcs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rypcfihy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdukahgp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jripmzxu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pupbjekd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fndtypmg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvciqhgp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmljhgi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwjznuq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vehilurr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2icpptzma.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwmtvkg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvnwejx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlrwvrr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gkszarul.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ioewppsp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ungrxvpv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yipwxtwq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaylenvg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaptkxv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcaoaag.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiktxpr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzogizae.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2odswkvvd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2crtjausk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdrkdyh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2arjmzorn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaxspnb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vcubuobd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2efppudrv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2seinmaru.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qllcvjfa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2usmmludd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bismofrz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlphufmf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2obdtfmxw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieccnxpx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcwbvty.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuigchm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cmslzpsm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxawafi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmjgzkh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2axhgphkv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbmbkjz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gewktzny.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkyeiwc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kscckvzu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsfigzb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvghscqh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2arofbgsw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuiipcu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gosaaelr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdkydoi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqtdonz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2chryjwdb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vwunaijw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2apiszesj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfhmxln.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2swgzkhla.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkvtbbh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrdqzcm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eecyusku.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2liarjoxd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnizxuz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqfjzgc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hdavfylz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ijymutdt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2puxmkuzh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bahllidr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvtqxlq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nviqxazc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lchvaeew.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2yarljexl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fozaqtby.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpphdqq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsnkgiy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pefmftdo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2scaccjcc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhebcbw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrbhswr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tknfqens.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fvphxyzx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoxkdmm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwitzku.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvhkqbe.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ogualecp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrnvsqj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnidfyx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuqdkty.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnqitsh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqisvrj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwnumph.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhcklrp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mhukwubw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfjaxbz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tizszecu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fczaubyo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2avydevtd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gezmjhqv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjpbfvk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2txiegoej.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxegyed.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgkjncw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xazzyiec.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2izbigqvz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfudkic.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrdjhfm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lknqqhkw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdzksfn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqiterr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fidktxxh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhixfnx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2imkbytmb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ededxxbo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iydxhiuj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqnfbsp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2riwpplvl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxvskak.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwqmvkm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dtglumat.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hipzpfmi.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwllgcy.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgqdsbc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kkukkaon.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfrxrka.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyjndei.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgahztkq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqecjky.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxayddx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkfggwl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwveckdq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2olcydbvb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vaymlril.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2etpnhyhr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuwaidj.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2owmilvdu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2humdnagv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnojkhq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzgdlfi.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2deezaxqw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtllpoxm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hamjlklt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2oymarpgn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoquedc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsqpnjs.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qmokgfbb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mymsotqx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2svospuvv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdxwivq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iyouvkcp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvptplvk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbhdifo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwjfwjx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfbqxiv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnsivvl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2raobboji.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwtlvct.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbrvugk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpwyfrt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbrfzbx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qhybybst.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkbdlfx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xyphpacl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsfrghh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwsaaeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyfisru.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2brjvyogx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ltopufhs.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtvyaod.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrfhsnc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aqznpjmj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fkndvidy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlwaxbt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgjbaid.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wqawzkmc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qebamrbx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wivdcwao.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ovliglan.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2plcjnucq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfiwten.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdlqxvq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tlklootg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2joxslaxq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjgvlqi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuciank.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmamlob.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2neacxyxo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pavjplzn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vlukbiyd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaqxhss.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2leotplsx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjjnbgk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2obrbsbep.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gqauobky.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhgenbu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tsshcgjk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpdupvo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iczpvdri.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2urayfuwi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ipufhzkb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmvfgwi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2plgmwevd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkzduhw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqbhcok.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrwhvox.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qirvcuvt.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiegcun.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2iujnueou.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkfmdar.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsejkgg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcegzta.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwookha.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2piircygt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nvztwqtw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2tozjiqrv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdwjbkv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiuwlhv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwjtmhh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxapjzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvyxkgs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrjcvsd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2aldrcslz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdwueuo.html


<!-- 参考信息 -->