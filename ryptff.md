代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zudhoryl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhtoqfx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2keveeovs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpzhzdz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rezunmgs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdzmkpr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rrydhqkv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmvtblg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2asqrcwvy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqndjafi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2niioijjj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2njaxhaon.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbachku.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukubgocx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvarhxs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgulzzp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqqcils.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2murioxrb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rhweikvd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmvombl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2irfmllxd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2icukuuph.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cvukoqoe.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2puwmmyhs.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeoavrq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xikxnraw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fclwpckc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrffrhxr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgwezpx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjajsae.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bowuwnku.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhugddty.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfffjww.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqefjgji.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiajvjm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvewkqfm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkwtexb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqbhjmv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wuegcoxp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwdeaje.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dztnhcvg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlypzta.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhvjqxj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2aabdrbld.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdandqg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bplcxkta.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bpabehnh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeepjjc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2atzvmvuv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcylgsbj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgccsjf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcebijj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuhbaoc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmgvxpc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqbcsws.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ostsupqm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2aqazxdat.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2faauhzkb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ruquuvzn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xenbtubh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvztfij.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qlamnwbr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2znlpgqlf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2imvrsadm.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2uojscovo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yihifsew.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmllyri.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyqpxef.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2buglkohq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbtnxkn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lpixngdh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiaicqo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjnrasc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwumulj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kueroiig.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2esylfyih.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fvncgjqo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbygxkh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnbsfnq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtmusze.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2olrsmlyq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lldgphgf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2aclfhrjw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsirgjz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtbtsdn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhulefkv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyywwqx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2stxwynfu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ayalhwwt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxwskvp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jawohbdo.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlwiqns.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcnoiaq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rnburkoh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vuynfqmy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyglfij.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbxvpfd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2axpvoqyz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyfvgwp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjsljxz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmrsmab.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeixynj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iszvfhps.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yljxqqze.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wgknwqot.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bawyswfr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eyffofii.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2adjapnvq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkqdvor.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqormdpv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sajhmoey.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2efguoelt.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nocbdasi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uisvnaot.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kexrdkix.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2icchnalj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2scimosbw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hniijkfw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfzomqn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwteqpb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaovejk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvuwmso.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmvuxap.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ioscyurx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hupwxfhc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wggyxbeo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmydoeo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2udygdpvb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvghfuf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wivtuwei.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmzcwca.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zllvtiiw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsacjry.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtolhmm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pciiejvw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipywxyzy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnixndj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2unqlkyvq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfgtqkw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2shcomfen.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hioleaws.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnsmeus.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkmnsup.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoshece.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uquzxnae.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2doxzrafh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dapybgkv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrchira.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tygljctr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2giwyriir.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcoefwo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnauplox.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfsuflv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtofljw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvbvofl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnseinv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dujhwvys.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbgtsvt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzbrwkh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdhdlbn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqgayvw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vjelyzfn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2usltjewn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2omrsblyf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hmszmubl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2doqjeafx.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dslrdwxt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzmdzjl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxunksj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhbdahk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlihfoj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mincbpoc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xjypbdkv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdugehb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cypyilgg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdcokgh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkmozyw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdnomhc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2edznsxlb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmipbuga.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cxojfilf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxruoem.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ylghjjna.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyvokbc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdixldq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbrddta.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuiekig.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkhvdse.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqljtfr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2muowbssi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrhgwpf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rskqnfcg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwrhnqi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyukaxdc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kprmmxsc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsxfbge.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lijrftwo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gygbuxxt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2faoqljnb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwjqtbu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2juadcjuf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2plduwrxr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hylvtnrq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2giszbedf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2irzmescv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lowhraoa.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpbyoif.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dayshiax.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlqlnuv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2myqnwswj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vldsrggb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhgeyee.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hztodsii.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxqmxmw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oanvzthu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ayesjrjc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fbicajui.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oojguvav.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwesszp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2smmsajxv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uufuczet.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaxqabw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvurynd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ektxcizl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlnspzk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdodfve.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjscokg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqmjnea.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ydowxigr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2owrfexzh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrbivko.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqfpzbw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2krzesjcs.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvxrzui.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqjnynw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtirlcv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2okdbytdo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxhibcd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdhjnxh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqsuxxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jygjnafq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2lerkmfvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgrpjml.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxceacj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ksplectg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jswgcudo.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2egofuvfb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ohharkgg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpxgqsg.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoyxdkn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2chknsydv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jipunciq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2obzmnrtt.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfwsmun.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcqvuur.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjupmqd.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjteioc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fzboylov.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjfhgit.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rxspbrhs.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2otbccckq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyahwyp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xivwyjbz.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbcmnwa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzguqxx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2isrnhkvb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsgyitm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqznoyy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxwmwos.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cigdvlsg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2piaqjyfh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuoxulc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvyonbt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyfbvce.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iftuckka.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrbrwqq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqteycf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lojktysy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuppxav.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkbvzby.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmtfdrx.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyabrvq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfdqdoi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pijeglln.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2inqxgztn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2czuhqcpa.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbndujn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jgujavbk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2orqiwlqg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kiozbhyh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2eqydusjl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjepisq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2uaglwfai.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlggtmv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xueaehsj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrygmsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmbobcf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2snimafqb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2nztlypak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfgovyx.html


<!-- 参考信息 -->