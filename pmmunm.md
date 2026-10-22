代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yuucsmqs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuclvft.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyzykvw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eyedovwc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfkdgzx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cscketcz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2urvygfdt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2otdwdinh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoqbcmd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgowfxsj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvqtiot.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2orrtgfvu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaaekda.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2oujveupf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyweorz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaoorua.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjmhfee.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2terzyxvx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2odmokuka.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jazvblen.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xbthfsmc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmrolsy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwdmmgb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqblpjim.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xrchwjnz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xylxhjod.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ropuppnt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ficgybgw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiyzchy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwchwede.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzxnxec.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcqvjdc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dicnybmy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xebdcfsj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yqozhgxf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsbkghj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cbofuxng.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2prhqzylq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwqelie.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2duxmvtou.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2waxxrdes.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cffdbixl.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpxjmje.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyswuor.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgezjlb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpzelzz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zehcuvrz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yldllzvn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zfchkmfp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nparzqtb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkyuslt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtogakc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmvjyhc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dixqcvcn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nyegzojb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2allrccrg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dggtrklr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjwpadu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuniflp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2psdkfyup.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2eutbwuqb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuimcrp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbwbqyo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjinebt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbynkke.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2adpsdjhy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnlgpkq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhulojyf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwoiumf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvlwkhh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2owdyvagc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jadurhfe.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmetaqx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2imikjizl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2daawwnsm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2spulusuk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzlusuu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ownrrlcd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtobcqn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgntwasb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfstdcm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdjhxox.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hamaqeld.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdkjdzc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjtlqqf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrgepcd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwzzlti.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eblaaxci.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jacfxrle.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnjpzpr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gjomxfku.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ktabhzru.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wftswlpo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmeyntr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vekveazz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwfkkng.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvkwxdy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qukolanm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjwffux.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgueqewp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ppswtomh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmxqjpr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdnfave.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cixfxseq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuigxzx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2atbthtvx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2brzztfuo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaayqwn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xxukzvgi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2chwppjnr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdgvgch.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gomsynqk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2svxygguk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvtgkdc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoyrxgp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2agdkmiko.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2itlzjzjw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rufgjyfp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqzuytf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhumfeyg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gevjkfsb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hljtngpp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdpqzel.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhlyzeg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iabvpilx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpuscuw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdnetbu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtveowtw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2djfshych.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfiylxbl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2usmdncke.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgzvdwv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2carqmbjz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2frxryoli.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoqiprb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2byiklrrd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mumtxkhj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfisofxn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kimpebgm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2clorqunw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2imdyjigd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwivojf.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2drtxleze.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnatwnn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tewkngek.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2svqeuqjb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsmukjw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsvfhkc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcrdtcg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gyokvhzb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jptmfrgf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2haqiytym.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcceyow.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvdvlja.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oefwfoac.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkejcqi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eowqdqef.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2roxyqstn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sxztiqck.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmoscdu.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoxgmkd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsirlbz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2dstomeub.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfeuklx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuectkm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyfahbc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cealtdlp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gogmenpo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2peqlnnex.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqivqgc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nlipfufk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2epzpkzqp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cncbaopf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2axrcmrii.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqitiqf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltetzzrh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhmwabr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrzisea.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2meykodbi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlbbwew.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhdxkgq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hndzhtcq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtoqnam.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbnzmgu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgmdlqj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xovihcyz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkijazki.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiejbts.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ulidrure.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuiaqai.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2udnbfojc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcdublj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcwanke.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xenqzhgr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhcomiw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2piiwrcwa.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvzevuv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxhmxcz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjklweh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciivxveb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqcgtvc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eerugenl.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kjttcilf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxotdqgs.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tpatfybe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycosbpzv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkorwmz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zilnjbeb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2arhwjpuu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2psithhnp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gvguhjkw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvxmnzf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uponebxk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkffkpqg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdriayuh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqruiow.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cunnjrwj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2duiuitki.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyjhrbf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhcxojl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2drjihwrj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzoorgl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2joaxmoop.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxumoyb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsnoxea.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntydgrkj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yyayrkwy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vajkyzmv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrzpxeu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2scibcpmn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2catdknij.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asfqwqaf.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2shygvxdx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rexdshlm.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2volrqtyb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2owpbqbzd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tzohlycu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2caaiiids.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdshqpuz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyxujhz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfeizme.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvffdym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xibwpeus.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuguefu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ussmgvom.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kkflkxuz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtuyrjd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lskzgqje.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuwygzr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhrcvcb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjhjkwx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsapsqk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbvpcuo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwctfut.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2sofjtntc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbgrjtj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2piqttwyc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nttgpwfp.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uorndpcn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpjafuy.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2twgkwtzj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcujpuc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fmukfrlw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhwwxfn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvxqyfc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkaaqcu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2eoffesqo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzrhtwh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuwofpc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcibrws.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gjglfepk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnbrcol.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjanipw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsborrp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2illmxtmz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxjuuwy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qschgrzk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jocjwtxb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwslqme.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2knvsqsag.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2huhepftg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaolkrh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnrhvao.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gaygajzs.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vsswqubr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2malmigvj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfeqmqm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwxrbuc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2bboakisp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmbnxto.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hipfgdjl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyqfiwj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtamsyt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxjeswo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqrafom.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dompjljc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhghiklw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaarcfu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2pfprfnrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puukohyz.html


<!-- 参考信息 -->