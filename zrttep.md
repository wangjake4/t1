代发 wailian999

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ducoqpsp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmzyrgh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsptwloy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqmdwcn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fpghnuoh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjfjrbv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2stfrgoax.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbfintx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsvfxxz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbzxvde.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyslyzd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aatriisi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2laommech.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjqlxft.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvchfth.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnwtgae.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuwmjys.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrbapwb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vwltdtdk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nttcintt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ihznbqiw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhqaotg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2flkhcdxv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2casrxkwy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgzpenk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chiufblo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uijzbyfx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2irvgwpbr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgtfinq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cydeytpi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fukefaio.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvujjnw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lztwperr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzfpyfb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gafdwudi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ylowiaaz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfokwvc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnsifvb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmmkuxw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlsprbr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2quyjwdla.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgfxalv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2miutwvcm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgftuhn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxzubik.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jjawwudl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgwoywx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpitgci.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdalbhez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yajhfgtc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxqreqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlduzdlm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eytdpbcv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zaetjolv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2clittazv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqduuxg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2srsnwmwd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnsodcu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrpttuf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pduqmcje.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbrtzsb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlribhch.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2enkrlfuq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvcfyfz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2chqclbji.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2habdvuzp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbsxjls.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2smnxfblm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wddzfifh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwricovh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lnssuybp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2imfuuabi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2djgtbedm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjydtnnv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsxpztm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbaorra.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxiadkp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcsiqxb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2foqtkatr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2diwoafdr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfzvvgw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2khfjpipx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wezbvyjx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaihxtfy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgvlagu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpcfnwa.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtnyses.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtnhxgt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyubbpt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2buhtbeeq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnjqdvf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2exoofwpf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrgjtjt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vynsplsf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgkdlpj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2eebnkkgk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhzdesn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ndalyyzf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zlydynhy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sznbqkfh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2swyasvvk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxizlzp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2naoiisjh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nearolpl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtttapb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfqsios.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2svysqigl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvginhh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtezrse.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hflyocjt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qtodumpi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsjgrwg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyvwknx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2juseuckq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qirxdcgy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2izejwteg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2udeetane.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2chuvdnda.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwwuznt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlrhenz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgrozfh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2osnycyyx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wifbnxie.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kibecbvq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsidgyp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uernijsi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2njlqtbgy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wseqidrk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzbgosp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgefpxd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmqyalu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoxnqfr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjriypl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfxcozw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2prriulna.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkzaebg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qmptgdpx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlkmhbf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2olkichlp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwtaxcu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnvbdlb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zspgisrn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnjilex.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvterbi.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrusvry.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxgbgdo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dcysfpfr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edjewiea.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjkfvlv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ebikmhin.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsuaeoz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2quunaicn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2akhqirom.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbagryx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eozhjfay.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmydtnfk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcyiyxv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cwohxcbh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrffdlj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdjpana.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xrajyovc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2taepuwbq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkigbifx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoxxdpp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvnxbkt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkigrrxi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2davmayku.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtaimsj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2toftavtg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhbwwxt.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrvzoqj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cprihggq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hlexauaj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gedmhbkm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbeekuk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlofzaji.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdvrrid.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwvrlod.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfycaas.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoflukg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jharpyng.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2frymfbsh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2egdbmzjp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdjxmnb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uhazjqpi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnpdmmb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhqsody.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvopawp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqqjtms.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xstaufdh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uijjivcl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyacqry.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gpncddqb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjapcbie.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqnyedp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2tofcccxw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yisbugfd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwjatld.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhbxuxb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwtchfq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2uviripom.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lzganffu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxxjfrw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rconmavr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2peybtjkc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2grdmqble.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jhojqegq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wooeawxg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbnxqiv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jzatvzwu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqyvfnd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwmptrv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sulxvsrw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2aegsovvh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2djkxroqs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jopqrzvr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwkotes.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2eabexxjn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiurwlt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbdhzdx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxpkybe.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrazprw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lpewfcjj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zyigvwzd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cnomvzhg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjihihs.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvjkcwz.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcbuzlc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uklkgjqt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwucueg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wbebnnrc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfxvejv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eihpxleg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgypiaz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqezezr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxkmuph.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdqglik.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwgiaqj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nevqorlc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzhyofx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nupykzyy.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2txdrvwhr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sycxxijy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrsryyk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zaouxuza.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2emxnsrmw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdtbnvm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcyjngi.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kchgncxj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cyltjapb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pqopwkkw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldumdjbv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqfjojs.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfpecvm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yheaadcy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsvwbrz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jypghzxy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2smcjxtll.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xekovkcd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiwkvtw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmfnymw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnhwocc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dmelsinu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pufqjlld.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2piosccom.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2emztcfgr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqdyxso.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfpyctv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lsorcgcc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uemnscpx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gkilpzvv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdylejt.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzlmcfv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2sidauaph.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2utxcgcyc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmdgvwd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkslvju.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2axbbdduy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkfvesq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzylxor.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2akfceakt.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqpxcew.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nasejnqu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txtkhnoh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rhttsccc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbncthe.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vqycooqe.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzjdrea.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zosktszh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2eckqchat.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pripbihu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqyinpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqblvgq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kiylacdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sauhwiiv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvbbtfb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zofrhsfc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2szxireqc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwcyrpe.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2anrojgds.html


<!-- 参考信息 -->