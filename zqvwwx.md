代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvwyuir.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhybneum.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkffarkl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pksbitud.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uatbwkux.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzprywsc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbkoxai.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkxxtpl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2krzffseq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjtjiri.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zxspvach.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuyljnj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zonhtyph.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcycdacj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyqeamu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkveajn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oipoxfjo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcrmcfz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoebisiy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2syxykazx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxvfqxr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzsqfmg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyecdmmt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vsndquea.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnnclgl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwsxjjl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqaqtgp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuypsmt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnztqqgz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgcyjay.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqisdrq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2turzbzpc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbebnir.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmiwsja.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwbraxr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mldvgltm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyhgmdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtsgcjj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhvzfwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sysjpmnb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xtevxfor.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uxygzfji.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhuhiyy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ukagiefd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2plyhdnoq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2khwllvkm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdhgtyr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hgufdmkv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2irarkrlc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkblvyqt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiyowtj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tspcwqgu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyydbrj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbjujbp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqkzobg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2oltdiqrq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2avbvyzvt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cekwkncy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtfcjgj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kowaffjy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbwhkyp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjidlswf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gkptupwo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aplqxikh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2egvcbywd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2srlggjqh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyivfmk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfziktle.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnbcgnv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vomelexc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcfpfla.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xulabbip.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzjjpzm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xthxevic.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmnjspp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeohebjx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaoaaun.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qokydfto.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbwhqax.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaktqfw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyxycso.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2veiahmup.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ftojmcqb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmqnlto.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcbkwuw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnthdbv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jasvnwog.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqagzxw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuftrsa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmmxxyf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyspnrn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2crgqnlwc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxaruml.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdcscvx.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ondkiisk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jklytuzi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xprfzvxt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqyxljv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfrdedz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrlpdgb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2iijloste.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vapeqybs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vuctfoey.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2whpicszp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmquagf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hapffpkp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bdctcbxv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjcsguc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2agucnfnh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2okystnax.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpaknpd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfrzvsz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqmwefb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkdoili.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2untsiown.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2axvvukoe.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zzepbwkt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hczktnlg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwzyqfj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzjumsb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjibdmx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2djnejzeu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmsrmow.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oikhruwt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwnkfcv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoifldc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vldblbem.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfadqunf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrecjjw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rczsynew.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtngulf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdyebuy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmcesai.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwpfyva.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sucnjejo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsfnjue.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eqstguad.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnpzolm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2krhsucch.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuzbwmh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kynqcbjb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiubwbj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqlgjvm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsgkkmn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vvitoakh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uahfrpwm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzpypmo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhvbkpm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eipwdlmp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgytwmz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2otcyqzzq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gemqmqyy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tjntnywi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tojskmwp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2coniuvis.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uktahqzp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wipkseat.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejteuvbl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2auxijagl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnovxnl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoftpsk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2apfakrae.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uckctzjp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxlubsg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcawnyz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoxnprw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzphnut.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzhdenl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcdyzkh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvbtpnv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqpjhla.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqsjxlv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2sflsxubj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywloumxq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxvbume.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gadwkthr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zustdwdy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kstfvumn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnupkur.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmvofex.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfbtrdo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbjfpur.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgasdds.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2naxzezjh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2toczbcjx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2chcsehjg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqikccdu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvucnwgw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ithidqsx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbblehz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yllkypim.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2djjiydis.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtpsjiy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxdhgth.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoilnpa.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2udoqzmsv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpxyqcq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zajgeijr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrdekgh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cwihegwd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqktspv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2aaleymes.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtmksfo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzajaar.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfuklul.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcghqmv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2robsmacc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2naledibx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvtniny.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ravoqjak.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gthsupeb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyvswew.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iltlhrdz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2czenygut.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqodond.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfskzls.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbcjdmf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqshgbui.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2orddtcni.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nubvjieb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2khodxjae.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcsvrav.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ophrcoux.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2arfazcza.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrdyfxz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2sekvimtl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urcqddsi.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjjxnah.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbskyzb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzsumvf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyybknj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oczrqixd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2slyzywnf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fndgnhle.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqxmdtz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2shhncdql.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuqjlup.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2omjfhkwv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaugcyq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtafcpok.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ppivakbc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2htgwsvdz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhpclvj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2krgblnvi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgezhaa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkpiozk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2opezimsb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuitpcj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqfjkah.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hsggkyuf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyptumj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ftejkesz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mvutnkls.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgjwkzv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2urbkdjqy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhcwhao.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2itsdvdad.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2btcgcufd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwfmozz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxgnidd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pcttprha.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiucbte.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvmbioc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvsvidu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmjowyn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbjhwoy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2twlfcwxx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqirnie.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgehfkf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tizblmtn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfxpeic.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tffywris.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qixpfvcp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2iuurrqoi.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdehcne.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nwweyjbs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbhoxoh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ktecrhbl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoslvux.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjfakmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxytrrj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2skgosyrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmozsuqy.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzhitzi.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nabyxubp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhcbjuy.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wcchfdxe.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjtslcf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfxojyq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nzthaeph.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2krkfxqnm.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvvnyvc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xmibefjz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dmflyphj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jauhigvu.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2axmxafvv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfevryb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtjxmow.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrretjb.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2irggsqgl.html


<!-- 参考信息 -->