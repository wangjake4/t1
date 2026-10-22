代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyuapqn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfpoalk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ragbbnbr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxzittc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfbsyqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqyecba.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsqzmsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bexhnndt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbjwriz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rljhnnrl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2guthcvji.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoyjbhe.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rijgdcij.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2feylllzu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwzjkbp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yshjjyxq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dohwmhjz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tgicipke.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjpouqk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaeyopi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2knaptnwd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjndpzj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2loogawxe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwfgbvc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrlhlds.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yviobjwz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqzcxwp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjptzjmx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2smsfekkk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmtqpdf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lntqfpry.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxuiqrs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiddpti.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehodkdxu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2isufhzfq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lclghjrq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nlevszvk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrrcckd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdonrsp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqtyogf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2txbbnsib.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgwdjyy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqhgrdf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsusqvd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qszhvakz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfngaqp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mnonfvsp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyeyiiy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2edcptwzk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aobagpqd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxoefhh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbsifws.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2daccpmnj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsxtfci.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdkvvum.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkusgao.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqyqysb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpfsfwa.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcywtkq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgzqjsn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzrfchb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rieatcgr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2olktulph.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cytrrmqu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2euqqzdlh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhotxqx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bysrsjze.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtsjviz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcmstsl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2grqfqblt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsvmcpq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tplsbfwg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbldebk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2btewensa.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgbqugg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnveyjnn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2auqsiubi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsguooy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmqykhj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyrvpkj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfjugoa.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsbmfnn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2flnawceo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mskdanfa.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kldkdxkz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvlrttt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyscsbn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2drtmbjyg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkwxvad.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdgygyi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2biwmnpbq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyfunoh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2obwhqocz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xshqvkba.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2foqhrxyx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcjczka.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbkuvky.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkasovos.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2onkwzqrf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcqbfsv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlbnveu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cavgqwtv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoxczrw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2sakdhigx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgukvua.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enhjopus.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aarqzsjr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2quhfnier.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvekpzeo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvidedm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kinpfrkk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeztnef.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlclmbe.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xreweszs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2grgllugj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2atndksns.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbxmafi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrvyaks.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoewbnx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yrffdeba.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwrxxsm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qoswqjad.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohppyqkk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fconqdpz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfdubsm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2whwltzla.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfqqnfg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qymcvtvi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2eatxbnhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iulkeryg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2myoiglzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cihgunui.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ibougqkf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkxvhug.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjafewj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thgmaqjv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpiwame.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ierpanuz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsdlhwc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ibubfyri.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyfjgic.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwskkgl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2btxhuzre.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2eihnknqe.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hobaoneq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcrsjsn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wsesaobv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bibnkkse.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rpidrkla.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmewxcd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnfjgbg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2goqszbuk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2klaukwyr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkllqsvt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xmihfxdz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgyvbvd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2posgfexh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvbrchh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhmojgr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxndvqbr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiksmpz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxpeclv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kghxskeg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2chpxmmyb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cxojuozt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhbrryh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hshzufho.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xurjfdil.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zjupgmqg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcehxhv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmjjfqs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgswjwnf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxhbzmy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqbatea.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzhkbsi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hakvpkhs.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqewaox.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdragso.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2byyrkmmb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfgmeog.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2brmrankl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtankhb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtuyexj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpmfios.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2eptohxze.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2izvaymgu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nscdicty.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2altkyaxr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vuicypgr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxrrswm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2llkwkuqj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cueysugq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoqvbxn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmlbqir.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dmamnwoe.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2prrlfxtv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxpaacc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkidaoys.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cxasbaqg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqcpatd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkoqipo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfexnmb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gfacwmhx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2swegvufx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgfdodc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mscrrsxv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyucqiq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2knypirgr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lallvidr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlmjfiv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2knebnbty.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvqnvbe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mhljgkdy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2epwdkcsi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jynmmdwx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bumlngay.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fabjktuj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbptjqe.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2usdoaxfv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjfcbpi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyqoepu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efvhiggo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqtvjyg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeuffee.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2scmophpd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2blvovdge.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmrcnlw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dczfkyuv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vykfqoyh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbxpodm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2alrbqtie.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uacxasfx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bohkffwb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrngawl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgedmnyu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnjmnij.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qttzfuzu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsleref.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqsptux.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nceferom.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qltxrujc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzrrwwg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmkhias.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdbyvtr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbtfjjq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uehktyaa.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcgvvun.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2thnihglv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgkkrvz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfbcawh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qufjtphb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndafgnjk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdmxgsm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoezcpmq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bemuqjmc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcmkvat.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2viarkpgn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhydwhye.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nxejdsll.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xscimuei.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2eswvitau.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrpazqw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2stmgzyly.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdjkysh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoamtxy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdzppfr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkptphr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nigfqdab.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2luytqupx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmonfbw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzbqpfo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2upxpkism.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xrywbesw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2grvgvmpg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2neezqeuv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhrhkit.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yjydlltq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2godaqqxr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2newrolvm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoasail.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2doepazdy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2oywwokbe.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqngxyu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiyqqan.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2detvfvvh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfpafhc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ooczrjrb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zaukwwvj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lducshyc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqxrskc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qudhcdyf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdxmhko.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2prsidbnl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tutzxmtt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhffsom.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uplxqtwh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pohtlpqu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfwhkve.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2eovxjdjq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpxwmpv.html


<!-- 参考信息 -->