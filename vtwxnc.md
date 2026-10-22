代发 wailian999

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jyteaeqr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjvvivn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eidrainv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvnpffg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nvipnkwm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpbkbru.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtlassn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxfuknq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvtsmpb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmacgmh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhgrqkg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tekmatbo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnwused.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbzqtnd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cnschbiu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aepkznpd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvfhiby.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwrvjfq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yurnoifv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2chkfbbzb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oravznfv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkqjatk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxqhuul.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nguyxrgy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2skzqvedl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwzcwiu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nnorbqav.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdkecgk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyefxwb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pojfcoqe.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2idvfxdye.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uwirough.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuwdqtn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmmqdup.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2szkdzcrm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjzdxrg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzpboio.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcrgpyh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ougoctjq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sluxwxnj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwhtped.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhchvxip.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2frleecoc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2twbuaegc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjdlnos.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2oihktfqu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dobfahnw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2faudjmod.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgurehcc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibukiqgd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyqreju.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvnkvqg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2axtvxhyy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xclizmxe.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oidwrrjr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpwosjg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bldlfgcg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjxjxnm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2podvytrp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwcjybm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sckzcrcf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaholxcw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnaedra.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnayvfz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grhnhcxn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnkwmbv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgghdbj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iesmjcum.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxpmjfo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2metmxbha.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyufoup.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tvawable.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwfedfn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2whwvgpwp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iddxyiqk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hciiewms.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cidbxzyj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxzlapx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxnfqhz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtrqjoy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzsrtxl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pisfyjno.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlgitox.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nykzdfxx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyldzty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnkvwso.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2staazesw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyylxoi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zmstcguf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzguucf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yflgylca.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xivggtbi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeeangd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqpordk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuracgu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2thztzgwz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoijbox.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrnywpj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2avyttyts.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2omnqiewk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fjytyopm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfocjvue.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxtairs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wlglguvs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeeyzba.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cysaytue.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ohktdqpc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2sexkuynq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2evswxtvu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2apapwzvx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjneydz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxprqhl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2idygcfmc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nevvvmei.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ffohwxai.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysedwofn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcgxtnk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tngczjzv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbhtanh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2budfxsdk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xpstgnpe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaupjhz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2thlpgrvu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcthhhm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbsspri.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lptohkfg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxeowkl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlhxlab.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkmatkv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2oojjogis.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoqwogc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjaojtki.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkmfzgk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mxunthna.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvmzjij.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiehfbai.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2iakymcul.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2buvotjzy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2dujceizs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjflrayd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hjntbhgu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tijooier.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzqkbdr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjjmboj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdovvvq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2csdfhujk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzfqyci.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vitttkuf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiryumw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhysqwq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrtqihv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkdmajw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ticdqwyf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxctkxwf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaqaurt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzesivzc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjvbwbg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2umjgaubv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ajywafsg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrmixxl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iktpjgfj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2idsuxuix.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjwziml.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2takkticl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgvniki.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gynmhrlr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mehtnyov.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnokilvr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgwhcoz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zlimrsoh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkjiera.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkmaxqp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oeypcnba.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaujmmak.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzkaann.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxebeasy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cznjfmub.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhtebst.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjyuopy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuyhmob.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uddvkmje.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtyrqit.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpaeqay.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkujwsb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2canhixzo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rihxgoid.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bcihjjxj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2przllakc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eaadwfky.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2reizqbhx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2drdmttfj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvhfxgb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lminigkl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbskqfw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjbvcxq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2omydsqyo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpltpnh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpbcvsl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2phpogeav.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wunlexgi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfpfqir.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvouxbme.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkvtbco.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ychofsrp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaqbzjz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2spdgsmrs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mabrypap.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2acccgbbm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pknabgtg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qypalrct.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqxkzzn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kewdogzu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2avjxpcct.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qplirlav.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2scgdnbpw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnldxzl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyfjlnm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkuszwp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqfihvx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dholsgyc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2yvghggjk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2inymncps.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2petuykod.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hehqffjm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wxatbked.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnhmdjh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsouong.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2smfwlrld.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gjysslcm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgqpvsv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bokcgdmv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjucmrk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cggzlspu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhcaxmy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vipkmvpt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xphetchv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fizeybha.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwvcotl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxygqnr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qycytqwp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kjibkiga.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2buwasvtx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrronjd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtntwgw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nywgpqow.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2miufyecl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgfbdcq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzhteem.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2afgiotuz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qycbjvsa.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ctltozcn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2foqhykye.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpoyhwd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vedznrya.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaabrij.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tywrddxc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvtwfqi.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2lqijuiyo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjembxe.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyluhhf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fozlslrw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzrvqto.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdmwshs.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wasvsdot.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmabqce.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwsxqic.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kxokgpaq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zffmljxu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cosfciog.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2tjblqmkb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pmccqkpx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdcaxau.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lshfjqxg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgqosxs.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mitjskxg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbgtity.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwkulni.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxheowi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhlwqfs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akzwiknp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xeamcghv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxqilkq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnxubse.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgjkhzb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuvbias.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zscfwhcc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2soyvalqe.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlcxcfj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfttzsy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaeuxlp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2epsbganm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsezrvhy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgvdyph.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2koruihcb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyaudgp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuclpni.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjcpnck.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cthstklt.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2atdwkpja.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wbehpgwa.html


<!-- 参考信息 -->