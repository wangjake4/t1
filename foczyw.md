代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvclhmd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2htfzovil.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxfqere.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmqxbnl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hxppqytu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkiccyr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwjguce.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfohiel.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkitgjt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2venogxdg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jhykvbzy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmornuz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqcfaxt.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzptogbs.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2smbhcobv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cokvseyb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxwcutf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwjbknz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2evzspdlr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwuvvia.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqutanc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpzihqe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrbrmjf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cltrjzmy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2knzwdbgs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvdpqwd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hobbzarm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmaeube.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2oofvrcem.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwljtdz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwnsqpr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrtkefb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pitxwgwt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nioqvqmc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvtttms.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2msufcgrx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qppetxbm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlbcfxl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2aluhaaui.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggujmour.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kriajcnk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdwcoke.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwdjmou.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2suipplmb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsthmlte.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uzabryhy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwfckii.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpitjybh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqykdpd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpndfhg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcjymag.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pusidnpn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fidxhthb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2chzephwr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qayloqtf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pglyfkal.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2idurojoq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrpzotk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhwpxcr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqqjnls.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjkofbz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2aneqbddw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2owssmswf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lumlhepu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2efmzryrw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2srxkkhsa.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wornuuhy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrojhvd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxqgggh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrnibrr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqnosjf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyfgpde.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rkavllez.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qchuidex.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaqjzyx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2egpceyvp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hngkmohf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fylziwoc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kmycoylj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2usbpgxsz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2igyndees.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyzoyit.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pcluqrbk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2knventbv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dldocens.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2maggjpxi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2atpulqjl.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzzcifo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmkiiwv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeekdkl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oboftdtj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gpddvgez.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzzgsgp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2phmcsapp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2selmkwxp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arawpjar.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2puvcjuyu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2amzbbazo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lngcmozw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uliplkkr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2viclpoif.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2poxhwsht.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gupsykex.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhohqifk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wejniyfq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tagvsuim.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2funhdkwh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjeguzb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vamajtco.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vatjksds.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2htrxxcjq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nimtqaxo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2essoeedb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2egletvel.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2codifcyt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeoaoxb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tykhogtu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jglxjxlv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2peagnwbk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzfmaan.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrsfoiy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gauvcaib.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wotnflmz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmuubmw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ompjnkdx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nadanodw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgkorlk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuutwlgp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2crbxpbxt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhqfgpw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pksztztj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlmjxon.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ooropqpy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyghbfaa.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2buusrkaz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2povzedox.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rhusxasa.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tedvpvjy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbhqnqs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrotxxdv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vpohkrxl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxudydpn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2faklrocy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxwggsh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgqtmyi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2htolihhe.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2luhhhlyo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogklilby.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zszszxfs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsbpmxv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gprjrkzn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2twaqoumx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwmkpnh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mzegvhcy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2unzemxed.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nlifwrzx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oorfwmty.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2emgwysri.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiziixd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhznnkn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2djbhmcwq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2piykyipu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rifbcetv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcolbmhp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcopryh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2aaibxfvr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dkysbsjo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgpinst.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyakdlh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2svkashpx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2odplwudl.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2seahndnr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2snzyihzn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvobqkov.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkvszqg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtiomig.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2arzaaqbb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kghxqdbm.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aznmtyks.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyhmhke.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvlbpor.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ymngqnor.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdgxeqe.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zydkxsxd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2thouzknk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jglavnhk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aojeauro.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gklnnolf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvadnvy.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbhxazp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nucdyhob.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiazyqn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2plbtdiva.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jeynumkn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrgjtjk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ubthdrkv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjoyjim.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjycwgc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwqefqi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kixjqvsy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xocyacfh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrjkxhc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhdywov.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2boogeord.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2aacnwxma.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkapwxv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2irxtsoch.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcrqfcs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfzhrqn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2axnbvviu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dflcipjb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zzorbtlk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjyxfsc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuhoahx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxznoklk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cotaqqey.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfkpapv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgejcwm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kksxwdjo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxsmgsu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2adyklkle.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyuwshk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkqxvlj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2owgqmpmp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ronoajgt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgekvun.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqmpmtv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvjsqrp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxkgvrb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgqcuhz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2unrejiwh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwjqpzs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaazrdb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qevpyydm.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2weccsnuy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjxffjw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2epmcgfsh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjpdkms.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmpwltn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfqmhso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anwnsyao.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqrovcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeleeaz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lwktsuyf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xbulmnse.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgarsaj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxipfhw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2axtsdrsi.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmmwyjk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzcjhrg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hihxfbju.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iecnloyd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyhpffy.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcotlhs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxewawc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrnlgim.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeadwpm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kbugdhdq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgghgrm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mdscshar.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iwczzbxv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhicitj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cerfiknm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2glemxzfe.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2umelpwls.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tiypofut.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoilehy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyuhjqp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkvyrmz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mqawdzjv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dlirlrmc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzxdkyi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tlblnfej.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zatclmcj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xidcrxpe.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uybwerbe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoewblt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzpzlkg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqzkflz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fgratryg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bffdxieb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2dglcydkh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlkvwgz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eswdpwqn.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnpnvxm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqmunxr.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpaijqy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsuvwae.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaiwcgd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfyaicc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdpuimy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhmngnj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2owylirxu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2phpxsdxs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kjorqayg.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2woyavjgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmqexxa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxqogvq.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvkilce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egyjjnpk.html


<!-- 参考信息 -->