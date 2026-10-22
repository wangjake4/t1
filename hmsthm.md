代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpekdhb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtsttds.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxixdvx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fasytrqx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2otbstlgz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2fimpfyyh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlaihiw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdrqzxv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yalwzuqq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eatvaasf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeoghar.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmnwxge.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2phvtteco.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2eckbmkrf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrnurqg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vncbdlgk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2plikpkhy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gquebjza.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2exezltlz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsluttb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsfehdr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqlswrl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2asvnxquu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzhtdpg.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzasczc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbexjtn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyhqldm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjydqxt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ntardyjs.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrexyym.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlptnyr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzwuwvh.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjyxibp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2iovoobwn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqilyrz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqwjifv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2oedgopsz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2flsfrifz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nowlvohl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiyysmq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgwcwni.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwhyoru.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hubumaiw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cktjadeu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdtxtqc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvmhbxw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2emuoacbk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdtwexs.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2olloppnp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jffhqgax.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2iflpmeco.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2viwpkzrb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oagxwues.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmrdarm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxygtum.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dznsjjip.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2srjkvkir.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qoahfdep.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zaypdpii.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyceypwb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2crcpfqmf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2yltumzmg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmdqvno.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2embvjkzv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fvauuqgx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxhbque.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tldpnyma.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2elpafgoj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdriajgp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lirwxczi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zoswufzv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfebxcwf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdgdkri.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyjlfjk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnevwka.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2havhmrwh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrkgppj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfdduha.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2etiqigee.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2guhhtyaz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mysyvrft.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jniffozs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzajvxu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyfuxsg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hczadipi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnqjgvr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2knwofrvs.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2msduhgga.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdzzujl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwlrqih.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtacdcx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnlkmky.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swvonauj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsnymid.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbidfap.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obxhanwa.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vsagdnpg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrolglu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvtrcjs.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzxcnjv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gthcdcqu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cncwybld.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lumdjlks.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdjdxld.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxlunfz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkmjzfp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdhokfw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdyuidk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xupvlmfc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwqcnam.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzkyxav.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoolhsc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2egvqvaeh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxrrycc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkmmboh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbmooid.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrdexec.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2szgjuccz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2glajrwny.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgsqmru.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lovzgzpv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhslgtkv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbpdyar.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2srurpjia.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqzbdhj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgpkpte.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhenqvq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2npldnatb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkqdeqo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrdxnhr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2actnmqqb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmfjjqx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvozslk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiwldgm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2haqbqtww.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaqzuge.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkuitkl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tufjercz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iurtmpcb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2adpihedk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqbxzpz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2htequwrp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gklerusf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2iintlefv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfognvp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhlwqci.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mylzftsa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaybmpzo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gkttwwig.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyfrlyc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuobock.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgduhtb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvwnckv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiuyapb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lzydurgh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbuvalf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ctelflxg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwiwkli.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuvyiwt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlnosdk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jqufwagq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2satcrghe.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsmrmwd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmirdjl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iidifrwx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdijaev.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdrmaqm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwxbysc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhlkgsa.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wobkgblk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvxkgab.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2htdbotcf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpvmydh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcecmyp.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vomxatvx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2diiwnrig.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kqitjqmu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfwxjyo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kmryfsea.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqetwjue.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnnvaqr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2elizguyj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wifzlwfi.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yonxujtl.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmkogem.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jqefjjjs.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2onihsgia.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zneivthi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hfamiofl.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsqouko.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkrftyi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogibnols.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bibtedoa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2etblrytp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2guzjlvzh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wnparamd.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vflhbjwx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgpmpge.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nchrhfur.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjatcunf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpiumdc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hypyddqu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkgegaf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2brtuqqwq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2uihupgmx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqerxhru.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pepbbcnf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzxbgcu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpgbanl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2elzzqqbu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2socumhjz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2amuhstuo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjbhuoh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxngsoa.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2humacwiv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2afszrmyw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xqullhiq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2embvevmr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhsbdah.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbcvxof.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxunksd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tffrtfrk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbcinoq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxspwwqc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2harreudv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbbzohu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xpivdupc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcdjxlg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rloiudaa.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzamdagv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mngpgubn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azqvrrks.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2smzxyaut.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2byxudsyy.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpaohce.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjommwe.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqwhthw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpzrdnu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2sczkpkrs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2khbfujya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxgcvww.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdujrqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwtkmcs.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzobhnx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kekpdfag.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzcqlqh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2npojcyma.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgrekdm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2beoabhdh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vgugzhgt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjypjqp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxjfxdl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhnruzu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbomlyg.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2oemiyumm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2swtimnrz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuigvyb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxrqtih.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xogchzsn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2swokiqty.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2czaqjhgj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfzngsb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmcyvwn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fisgxyij.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyjqcij.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgkimdk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtbdrhk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqarmog.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jimacbia.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sdicuqwu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vsglqnzl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcpntqq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2upbzwdso.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxrdcbi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxpvjyd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfynwqk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuuurqp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnqltgg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nzszgrvw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2stwpyksc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiywpyz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rjczkxcy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeqhqwc.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2arolewbx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mscsvlmm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiiyikb.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iepvintz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rhugzzii.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lvagkinu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjfcods.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbwbdph.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2wcstfinl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fixzimui.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwzofjv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzqguih.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjvntti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzavumeb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2atstghty.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjbyhtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nefinped.html


<!-- 参考信息 -->