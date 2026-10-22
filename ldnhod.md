代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2evsktylj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2khvokump.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyteujla.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2deeyipxk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzblwvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sokjyorj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyizkfar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcjfowh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gbskrxzq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjjdvxc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxjrbms.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2odpdbshp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzsrqzd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bejgnnnw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yahedsma.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdhilao.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbhfppr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2edokrsrb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdjfwhr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjvpxky.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wucfaafe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypccpnyy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgxtybs.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2exivevyp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlbxayr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwiegqe.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2buxepmqb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogenpzqx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dbizlblr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2axujwgsy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrqqqmt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyasanew.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwhgrxn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfkiilr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ljljbata.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcuktkj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhdljec.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bshrwiab.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2usuusree.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrurwomv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsbxwzd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhewobm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmevlwut.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmpptjw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lydvmfkx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkipyzz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2omiczdul.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bayicwoo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lweuyaxg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jarccati.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqogmrn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpabjsv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rchfrgit.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2enzydrox.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hgckhegb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pldiiikr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zdumufki.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzdjyej.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vojkwhia.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfuirlw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzimcby.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuyidue.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhkwoqn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2puzavzac.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgwtytn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxiqfcl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tljofdnd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqowhex.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqczdtx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuuvuir.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpsncvj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvutdwy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jacivdny.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfslgrv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2iieqmtsq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkubrbt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfwlxqz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wducfxcj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeqotvw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sddzizbh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsofeml.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjajqtt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcpnnxd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2doqfhrvz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nzonskbf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuxlknr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2faowvxli.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vdujlbec.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvhpzcj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvzphwq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwobjek.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqlwpdy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrskcqt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdgpdvz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kugbyion.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuwuckl.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmcscqx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxyxccw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjupvlm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybswkekz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bonvanxq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrizjhrt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtsbxid.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvxijfc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsryanc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtferiwf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzogzgm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkjvnyr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvsbtuc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrtjwtl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eypoydlc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuyeokv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdoccqg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2htgxizyn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2latadnbu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlkfwvq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2utfmzpat.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkamstk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2loxjxsyn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tikpsewr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqgpubj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vagibjdo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2toawsyoh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2clgzqgnh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bhldacnn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnexzrb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcxgenp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeujbop.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rijxxwcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oijvhrzg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxebijn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbeifvi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsvvlko.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mknyikmv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjytizu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xehifpuv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sbojexzg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wstfxirs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2obctilit.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2atspyqjn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kiowmzjw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmpchty.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2horcazsj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2myawyvfw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gftjlzoi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uucoepjy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxtljvv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2alkmllty.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyjsamu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qntjuqtm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dndmybzg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfflbtcb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfobvey.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2byngbdwz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xeradzyg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uelddcsx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxxopzl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2trvxyvvr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gudymyds.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iufnjjnd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2svlvhqrq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tufkptzy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmrbleo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtggoql.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmoszkg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2izrrhxtg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2knblunks.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2romaqmfs.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdazvjl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2umcoajpp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hptlcpnu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhncsle.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lolusvgj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xerufqie.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2byinlyuz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcznqgm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iphhfipb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjxtxiy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dgywqqgf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhbjpel.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lcppxdbs.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpnvxsl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2knbugfhu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhicrkou.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeklast.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtwlpyi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2weuzfcel.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wexqekxf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlfhdov.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqkyzyd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtgfnkw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2okyxbvxc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrwxgyo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbaeloi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oijbtafo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2aokbwrbr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2shzexnga.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqckhcdp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmmomgl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqzlzzn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2okkskdeh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgofhea.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcmfpex.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxbxbpt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ksohtpeq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fglnecmm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtjijit.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mluhadnx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cokakgre.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nalgmmtp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ukntgldb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvutjsmf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmjyzch.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2awocjpzt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxidhfn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjrxame.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoigblf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdautuga.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tdauphqt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rskszmwf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgwrmpv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfckpmkn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2inbjeqsj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pguexyiu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqimyaar.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhmvgcf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvgtdiu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erhqwxly.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwtwmbx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmleicm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrzsfxk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzddhzjy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rassrjzq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2htexmzbk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjvlxoi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bptylsnz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vixvctrs.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfbegpw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxeaklb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2baxhqvzb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ncclxhll.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiutsji.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qelirmfg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuevbwpr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2obmzqphi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmxizea.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2shajrrug.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuugauwp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqsacjm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtovzsq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2usbrhpma.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxjnsxb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ocugtljx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hubksesm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2izxildza.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuenjdh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ieydmfaq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcuhtqr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kosrkkkz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaeicde.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpiotjn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzwszwg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2syrdqbuh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvimhyi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxdsfog.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjodhwm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmrxlef.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2etouplrg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rcordomi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfvworv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xotiferg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2evourdus.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcxrjqt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnllimc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nzywoztp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqroiqz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxvplio.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnokzqbn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpjgjwa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2uaywcyga.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wcefgwwu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjtqtjy.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ethraanz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxjcfii.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcektjt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnnadjq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqqfbxd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2opcmubqv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgmquez.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ihctdmhe.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtxlivc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtnyfke.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgngakr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fexrlzqy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2njwpjsoq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jthqvyqh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qpufbfjc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfqdguu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2luyomdaz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaejbco.html


<!-- 参考信息 -->