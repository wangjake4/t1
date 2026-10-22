代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrviymtw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gysdlepm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iimezhde.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zsppxmlt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zedxezay.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqbynot.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zloscthh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqoqeqs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oceeakco.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbppzcb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfjuxaw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xmywezdv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2edosoglu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chyqboxt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2reqwiuxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mykwvgfc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlpbyqw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiyvndi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wabvbcgn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hswepzjb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlsicdu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwnahqk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwzwnce.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ifitsrnm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmqovqa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwkvhds.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kknkbeod.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2greougpc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfzsovr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfetcyp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvvjujh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjfaceq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2juywlqyu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyjytrc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmaahsq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zptbulvw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ezparfsk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lavlfsae.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ctalqvlz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeuapao.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtomwlo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiuoyzd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2roptwfde.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jctiskiv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2paitcrbv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vulwdedm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jazkpbmf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnjipjg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrtxwpj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lylbipyn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2voifkrai.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ontaqekv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgulkql.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lijbghkj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rclyvbag.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2knkiozog.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iajglyys.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbiuvdx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qesvvrnj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbyiiwl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2femxzyxg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2epycwwhj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuthepk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbahqey.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2faxtieyo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmqfegr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqcosdc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2axatkwxa.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2scrkjzmc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdynpltd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zefetukt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmypkguo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mehkfpvz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdyieaa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvwzjdp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbcppzx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lshokwsy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyncmdr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsbiumm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fbixruvh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiakbby.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xspfsbdw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaijmvf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxqzjzt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhedxzi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzvyfxq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hozaxtws.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mujmqzpd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qllndqsf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdodjfjn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfftqxk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxicqnmr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuewfaw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjojwycx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2eoabddwb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xohgbsrp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tismyisg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yztlpeqr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhsdbyf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnrxihx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2akzwmzlq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfmmlty.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2brxbtqtt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfzabud.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qnddojnp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qubzyhrm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2douwzokt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtshkia.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdrfuiy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qppzufai.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2spsfgohi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwvlrnx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynescrtp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zomeyccy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmnrkwg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2peurtilz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmwcqwr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hnllogol.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2etdibvtv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfgpfoo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pposhpzs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxidvvw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkgekyi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jttzbwey.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvejkcsh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xboqyhvv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iydkniux.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwyqjko.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhrylmc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cekpcwdn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvlxymr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ojajrgit.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kenrkgvu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxixedp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnhxhxc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2oouajfyd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlfuwpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrbkofi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtrhhyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tubxqqqc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfsybyc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2doaulyoh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zawjqjaz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxhrgfs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbgcrtg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnucekg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2doooakbr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ciglosjz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmtyakh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaypqsw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzcvpte.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeyfujs.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbjdkpp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfebeose.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzzwtfv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2olpjwroz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpvoyqr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fawossed.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnvdzbs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yorpgrdw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gusogslm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkbdyqf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2llnzkuoh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yftlegvc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqulmlt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpomswj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rztbzdil.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fenuqdsk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkvxvbr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gptdczla.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbrtaug.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hotsftyh.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fswieaca.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fscygnjs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsoickg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhddyfi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcllpyn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyxyxqe.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jddmnuzb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2orwjfenx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrjufor.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuwmekk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfkragi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqvwjgi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqvrlle.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlntzjr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxxuctb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmrzjlg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2esarnmxp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtatsod.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2poxamwzk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpyvpgv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrfyfvv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2icjqkbdp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dekoriqm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyowqcy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2auwtdtfa.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2etmtwqwp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnzisku.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oizjqyfk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xihbtyjq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rbudicxg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2naczfvpl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bcebbmuu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cekvgohp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiszsqg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzhxeof.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaormrm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2uldvmfbv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuzgerl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fypondxb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyskggh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfhucgs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fisqgiuk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oitnspoa.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxzvqus.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iqextckh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgagfdy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsfjehm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfukrinu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2agzgmffh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnxlhvc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2usjmdoyf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwqszgg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tszjzepw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjcvbuz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjtcnay.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dewzdfil.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tespzxyw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2troymjla.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxuwfwk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxpfzdy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmzfeyw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kltdecho.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dadusxxf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrflttv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbushqa.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2skobjhws.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmpcdxo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcmmmeh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mfglupxb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2umbaqemb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpgxqpm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzvtabe.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2psqbfnwi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynavynqd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tkruqodz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdipnni.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxltwfq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkudboy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjcsgbc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2awhprhov.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tartbyta.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2feqefbaw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zykarkzm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeazbsj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2itdrkaxy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2srgddzdq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2suiecyhy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eovwejfz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2llgltzrg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2enjqibyj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpldoxi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rngsfbna.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zropsomp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2smcedxpg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dsomezif.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufphxqfn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbbcend.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfrvaid.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wvatncyn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffafbtbh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vyivzdft.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgezusiy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqcxpfq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdzsvkt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tsltrbar.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2czssqeih.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jyinqfjj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuqoixk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmlkfzq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uebkyatc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnjnwzp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2tkunulav.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgrzrvc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoczuss.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfzpzwb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjxufmt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2puzkdimv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgfcnvd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcrddtv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeojwmp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jymwckig.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tltgfdzw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoifzud.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mazuelii.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuohiyv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2shvwurbx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhuwymk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2islgkyog.html


<!-- 参考信息 -->