代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pgslqcid.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqvcjjy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlscowks.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mngrsylm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qioamsil.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcgiewh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwexkhol.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxwwxol.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2acywjxbg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bazxnlyb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyewosxn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrkyzyg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eomtgadz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgvsagn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzlqgzr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmfhtgj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaekobo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kixqvdzf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyiqhje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onyyvcbk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zgitrywf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqukwkr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jvltenpt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2soorpuut.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2chumnjld.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yletiodp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqstmxh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2twxskqgo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tngrqvjl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgapncg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2loawopxe.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlrihqe.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtgmpyw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvthpak.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhaucwd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrrvivs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdwtsuq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqyozjm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fylqjcyg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcsrtgf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzqzzph.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2toageqna.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eodhnpmq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwsjfzq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2knmjkkyz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vszvhgku.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sqinwoge.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjoatpr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2igqhyrjl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxkfkdt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fukdfknm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rifpfoyt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjekjcp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmmfxlh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzwelpf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yerjgrty.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2svjfexsx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjglznra.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfnyppx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbhwqye.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vthxrfzs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjjjpmx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2akvjidxm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeaiyzj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvfhmgk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpanihn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dumebqos.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lojomtmr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zshwnghl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hstsynzm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2dypvzqyy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpbvtob.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ipefdsyh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdnxdrf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoxoscb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnbyijy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiemgid.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gajwxtui.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrtssbu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2adrytymk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2eucbundw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcfniaz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dawtdnfr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqgozjq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgmehtg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjysortg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaomuzl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxqkocz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2evkejvus.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2avsrqkkh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2flpdtugg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgervcxe.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjihaga.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kyisunoc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkymvqq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpzpwyb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjwpzio.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeiabck.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dimxqdmh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uinuujxo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxhbxsc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjddahb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fkciglji.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmwvhzh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jekjxaon.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvidfzz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdxjljk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oppwtgib.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjzyzsh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiecovz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nzynnlzf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mbktvkoc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yqowbyyd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bveiormq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaeugfw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znyydacs.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bzceqxsg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdeacvn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgetefd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhamfbss.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fcevuxcf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqkgeqy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqgbenx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcqoamq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmwadxf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmnnqtw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dpklaliy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaywytr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrgitkp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2edflottx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwldptrz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlheglvn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtqqxee.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jotdemco.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrokunw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmfgbqg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nxztvkwj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzktqmxb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hblzbngh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtapluq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mvduikvo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrjyaau.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaesuvi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jymelclp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2oophfxvi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcojewz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvrrjii.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrryrkp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcncmgu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynneilbl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwlztuw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcezqus.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkehqkf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqafwlsa.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhewhcv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwujdqki.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kuntsiwk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxvrvva.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2whkmzjqd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhqdmlq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iofmixrp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzyfudg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aamjuhmo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ligtlzic.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhibdpb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2unachyii.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2whqgnjcy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2urenpvrj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhvapfh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvdlhzc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jimirsjn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjqrrdg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiuotkw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2njauszaa.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tabjxfvr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtgqlyq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzohtxd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kggzwegw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vemkvedb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2opqvvdji.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoufuoj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxubplk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2quslbqlv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkhcnas.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zaywnjoe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoeioab.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2beslnhqg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgiuuml.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2gnryltrr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdmepte.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkahqdx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjqquiq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uechcpyd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtranbor.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrxocqs.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoyartg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nnftvvur.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2orveljsh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aiojmuad.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwnupqk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2igeahxpc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjmrrkg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zorytbtp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hooopgva.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iaghzaqn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ddksrfaq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfxefik.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2aixmkwat.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ktroosod.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aejcpdce.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fmojrrfj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mizsihku.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyznfvw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnherhg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqcvyxs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtgjoba.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlwncip.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrjtdwh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyiexvr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnblyvau.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqiofxp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffunplwt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qspxossy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiufiif.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wpitzyvb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oamufqot.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gscwogjt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwghame.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaenzgi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwnoydk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcvrugp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhpryyl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2sbavzjlz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvctqdhc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hoovwsxa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gkamuhbk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsvxkuk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2csdigqgq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2uqipgrpw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2avsbevvo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpmtyov.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2utkignfb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pqodvxnt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpkixdi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbrywaa.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhunjii.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2njidumbj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpamlrc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrrindt.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyjhssu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvpskce.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxyygoh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cqabexbo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hrinabro.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfmqokp.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xisytgzp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqxayay.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtmiuay.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2eglvtfwd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2opneltjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hradzjve.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoamcpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnpkmbi.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jnckpbln.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tutgtbjs.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfilzoa.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkyfsjf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2owiogufm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrrlrid.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lijnkuny.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fykmifla.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wynhujvj.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zircjwlm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2auvlhchm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bftpuumx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmcubje.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxphmjd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2biwcwrvo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlgvcqg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2esngnpvg.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvnlzcz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qedhpxcv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2krxhgjst.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvhbwcl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnbnvpr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2myrelrte.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjhktmj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuczpmj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rdccbvao.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2srjmyqyr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ytawezmp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhzptlo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ggalblie.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjiugev.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nakngszf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhczblp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lnycqoic.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jzufyfgk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ykldpxqu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2phcrzigw.html


<!-- 参考信息 -->