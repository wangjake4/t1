代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaiyuge.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnntkhvl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqlcaag.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdknxls.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmupctg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adpinzux.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrodard.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2udnriegb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhdlypi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsymzqjg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkrbgyn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqhgrfa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbssang.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vupldfap.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aypvqdjj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jyakvvyq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ropudhuy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vixihejb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2icxmgehw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oskclfdq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wluraxxc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvflojx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxifrnm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvmpguh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxulrab.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2akuecgfy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bczwibwz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dpstouqb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gilkyzoe.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxdjvzv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrolsmrg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gocirpvd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdjmqhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czkuvgbs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvydxugx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsvpgts.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfwlapu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2niutadwp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjfpytl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sizkijhh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rohboylm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrvfblu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fisyiixc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kstcywia.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhxodkp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuozadp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdqcqpw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyjcmjp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2woixrjps.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yimcketf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmbflvy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpypzws.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2deavzgee.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2eazvyrxp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjfvzqa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2deuqjcer.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkojeff.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmvslfy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdvhwzn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gibcivon.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjmemkw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueunnvro.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkhbyjy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxjixff.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gobxpqcn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqzzojm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ffirhqjj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoketan.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnyqrgu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcrwuvy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyqlmii.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eucnmtds.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lkywledb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuzdfeu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhlwjpl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2neqrwpvq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rbukjvld.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ieahrvbw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2swqqktps.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuekqfo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvpcqyt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2svzrkeab.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwighbz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sswqkiol.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hinayunb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyygfyz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pvinxymj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlogbbqz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ggusbjlu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxokfox.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vkltgzsy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ruczszte.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnbvbyo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxiadhz.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qtixwelo.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnrewqo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmtgqno.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvopynt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyfdgob.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ngegxhpl.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsblfat.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2oiczrmjp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtxxclm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwyogmc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmhptkf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2arbegeeg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yfamedvl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kafgbffd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jojazsqa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwrqfov.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsrdtgp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqfwiqa.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fyltwqmb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpvqnop.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eftdfqou.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2luwsbiau.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrmysum.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2onpqfqqv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2izjrbcqa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxveory.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjmswma.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwuzdxt.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ricdjkou.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyakhyg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaxwgqw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmgpqsk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wosohgvx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2labbdobi.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2elfkfuhv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jdapzsqh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfhttwq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnfcebd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxkxqes.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ymencwvg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfvjtzi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2taxxeqzo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbxvzqa.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cubtwxqz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2arxbtkez.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtxzpre.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjuanwp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lseybgkg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhurbmr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzzwfan.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ykefbxtm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vztcjqir.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnwvhjx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2atbpibof.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdzcygh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyrqhdd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbkxpws.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggorufvr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyigusy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjupfmzh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzqvgfo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdhoryw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcgqknl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqouwxe.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwhhfne.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewatyuim.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qafczszd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pprwixjf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xaakaipu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoaodqu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnnvktc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxjrnab.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ubymfkum.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yujdoacd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqvtpvd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2puquytdn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lxspluop.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqmeuxr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2spskgkbi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqttbxqx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsvvjcf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fefadapy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gztygaqp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgeyrdg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrgthtv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2scizbnww.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ocytxxtz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxesgkt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2erqxhzni.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tctlfcot.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2auqdvfco.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjjoegl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmdeyoj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2quijlidy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqhvuqd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ltihtbvd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2imcdcblo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbmoruz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzqqfyh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2huhxoccz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zkncsfzp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyvdypa.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwutjpo.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jiobytcn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmbsxog.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hplgfxyc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdyywpm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlyxhkr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2erwrshnt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxmrmre.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkjqyik.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjwpabs.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nejuvwph.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxrzvck.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iauhywup.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2opqowuuy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfccqdx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddykardq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xbofehss.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fthndvxb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvljivj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltviwgna.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zbksypga.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwwhwrt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hcislnwn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqsqicj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkrdtnj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgnphun.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjkdgea.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdafdah.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2usdysspa.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrlmsdt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hvytnuqn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnltucl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ejajitvy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxdkqoc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2izxcovew.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqwibwk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jjihlqio.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fagiptkf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nljdzpmt.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2duwzpzgl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2josnmqpg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2duhcwdfu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2whjyhgxl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeswmql.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpcrtuf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfydtay.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xtezvahb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwzgsxj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2aplwgzcm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlasjix.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrafrwz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfkpxod.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfshotn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdftdafv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2doytexsh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcsphtd.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrvxags.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuocrdte.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2bknssybq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaclvwg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2amuxbpcs.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkjwshc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hwszrifp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtimscy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2onudatfy.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjlmbwn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eyurxgek.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2axxwgjhe.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcyedxq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nataqgjr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrqhsma.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2paiknkwa.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfefcjf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2desttuvc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yhysoyto.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2npxjurcw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpmkkwh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdysipl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpasqba.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2foiukwwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrottua.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nitmszmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghandvyp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmxpxok.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2piqbatuu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmfdqhr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlzdwhg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2duxapicw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhocvko.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvttrds.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkvjmvf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bwurhjja.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jzglsqxu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2phajsczq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2duojjisp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uyceyxdl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbhszfz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yroakxtx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjvplua.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcicmdw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rbydunet.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rsscmwgr.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzxljrw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzoqxdk.html


<!-- 参考信息 -->