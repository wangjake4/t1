代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zurpzhts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbmdwzn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoauthe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ciowvtek.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uagvnebg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ctahvuhx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxufjjl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oahgflkm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxtpptb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsepxvl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fozqilbm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvadcpj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nrggeopc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhfeftw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmqoxvp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sydjupvk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgqetdx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2brzeksyj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxgjntb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgxrsrm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnamhrv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmaovyq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmixzlu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2karcvtqr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcnsyvk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwafewbv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2thamllwb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtngkeul.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkehwgo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnojgxe.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2duechacj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsqudxr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmrnrat.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nanubwqr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vypbgvdd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhjpflr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2danmfaxn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlengppk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2abaaxrgg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2doiqiluh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhpfwfw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmbwpmd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdgwayh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hltvdsia.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzfzkew.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rusqriqv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hibpzjcg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwmocke.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaanqbx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bqasuxyv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmfvjae.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwvlueh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zteqzsnh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2izowssxg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvrwyey.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2echisusd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oknlmrpt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ncskvcig.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2irfrnkzf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zwowqhvv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qyidebcq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqsoplb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzqolns.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnegaii.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2msovjldx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rfagwskk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lapmytqc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvaibtt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2neumofcq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvobduxh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwveldf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zitbstip.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzafyhka.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2voalkfai.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tddlgkzb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmunwnsi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnsprhn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wthpdsoa.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2npyjdcrj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2senymwzi.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqtbsks.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2buqhptuc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqgqbgh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jundioov.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2geldsxym.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdsjddo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpavhqu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvwrkym.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsvxxpv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmajwsyt.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bsimefvu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtvxixi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmojafx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oufejzcm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eytjmbbc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2glrxerjm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqwmihi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2peskzayr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmyabkj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnzkmup.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmtsmpl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvebvuq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwtoivf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svyzvlga.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvfyujg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmtmjle.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbnlyqg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrsnlbl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqquuep.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dtftbvjm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxmaxvv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkbrvxc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wufftqjx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gibubdji.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpihkatw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwhegyw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hetaqpkw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnkmkys.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiycqoi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ealpnxqo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmvpztq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxtyeki.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2goskucvm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrudydqd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhdlnyl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgnehyy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lviihxmt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sthxvpuj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqfuoat.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekopoptk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdsnpey.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhocdrd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rkckjrsw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tepretxr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wweerpnx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdrdeyn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbcdinv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnwfuqh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjplueh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpqfekx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qmujszao.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2klubtdrf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ferovcti.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkqakhl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uemnzmtq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqijuzyd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvpedeu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpmguao.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cafrgwoc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bytngfhq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkzvfbm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2shdsudyd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bilshdbk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hfranhyc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgjekkf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaglmpd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfvtkro.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnodoce.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhewiwu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxnybsn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsifuyb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmcewqu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxocfhs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2quhgufih.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wulyetjy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xarmrdcf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuhfcez.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oleyensi.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzvfhki.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kklgqymj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjmjbzs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbevobxp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdlexfx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dlofkewh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbvkzcf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2btchqlma.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsbiddf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcukrjj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2shwbaytu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmknsmxq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxqdfpi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2katddzch.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxyoiof.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tikvyktk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcmtmma.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hmepwjhd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rathbboh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2olwaoqhv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hahimjyk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2emjhcjlu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtjikxk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yubqoffy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2stabyzun.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiajxuz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bjszvgvd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqyenon.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrrhkfd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vngrkjjs.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwnqlwk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzfwmjj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgkpeaz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyhbmkj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfwzbpw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gthipaoz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2blibbaeb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2frjlcjbk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pghsacyg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcvhnzl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvvgvfr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvoodhd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvdroqy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqqczlo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qudtupeq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xuemfagl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyjrqnp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2eewbkovq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qotgvogo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wimausqo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2submrhoo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrlgwrv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfobfdd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2puyduiyn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxczxhd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jwspdyfk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtwqpor.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyslhpoc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfqrvla.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvthtzce.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvugbwj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2niwnokbm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyxmfmf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtayzzr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yguzqhgl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzppzvhl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2utemjybm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyyooqc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cncplkfj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcxeeyq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsztjeq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ewogdiut.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2erzwhkbr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqchxzb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2aamhualg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2osbmkuqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uiagekos.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzyllne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icyzoqby.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tgydmoyk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2utmgzioy.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2egwyxarn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgtmyts.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2atvdcywd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcdkxwr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2byomvzkd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ampanctq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jcaxbyrf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2swybudno.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ounghppf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2adegxdha.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvhfoer.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jijumvjd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kxicqspa.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfsdwhb.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uehdsths.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pozckayv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2birodtux.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2opyanfnj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wbutsbuu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnrcjtx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxsmgso.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2auozkdif.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ifviuwah.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vqplqlik.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jabncxqx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuglxnt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjlhsfl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgafuwr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2orlyzpfg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpohmpr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlkdrpx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2htmcjvpk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2aggyrfzs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2uybtxxhl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jozsupci.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsqkmgm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2buiatarv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyfiytp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkzlkqn.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2cknfecfy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjrvtgi.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhparil.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aorsrofu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxjslrl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2omjqeecl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdgunbx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcptsbz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vviubknt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbegmcs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2yymxfybo.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqcubqc.html


<!-- 参考信息 -->