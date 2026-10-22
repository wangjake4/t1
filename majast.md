代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgvvalg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knpbwqfu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbsggqj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjcvwfa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2onexvbvv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlttnyuq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsyycvq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qphfkeli.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rffagzst.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvktwfs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsbxthi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mctatfjp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iacvrcft.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlgqbka.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2irdiamuk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2sstxltto.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vklidxzz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhcakgo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpjsqha.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmongkt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2njoehnmv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnevxye.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2sazrxdbk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqyhvdw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcfbglx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxbzhfy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdqtllh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgyfacz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzhmyye.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qocvsirq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckandzqg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tavsktup.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfdltot.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkvozxi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yokfinsp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2scuewksj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qxstzhxc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bwapnfex.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2atyxjrwi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfpwyvc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uetijpdv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhzzimp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiqwqtr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdlziys.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2myqdhccd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yslyrjwk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2inlkmrta.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqvlubh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2avuskoze.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnshjtbg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkzdxbs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gizdrwav.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2scgmtdqm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjwkeaf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgjslsy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmduatqv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwatika.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwshrnmz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sgopydrv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmilvrx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vcczdrgp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwtaruz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxjkfhf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2prwmfwvo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mexbrkjo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwiljke.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpjhthi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyertvm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrzkkcy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qidrbhia.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuwtbgj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2urblvkvi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnxjuem.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbgqxcx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2inyxemcg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuucpmxr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjpxcsl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwdixlj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nkphtdmm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrecnxz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sujsbbfb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgexwugv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cotqboqj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygytvcxf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ljycdaat.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhjxwbb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kwclmqns.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2utuqruqi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2orvlnvoi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bofualqj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qavdntyf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbygffj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2syphozld.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bviylyxt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kabgckvh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdswvqc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ocekzljr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnajkta.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lidsifgo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wszodbkz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dimxsqwk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tohmnfgl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuhxvlt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtsauop.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpsmomq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iutwwmgi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvzuotk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2sgddzuvv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2druslntf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ebybggbu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2slxcurqd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgkurvf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rixjsnwe.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2glojzggh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kicsaakl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfctkum.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gkotbuam.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aifknpmv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmdmwee.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rammwupt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhsrtvj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxhovjt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyudksz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtyyicr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phvzmsfe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwnuubp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsllvqfz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgahcgel.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aballocn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2juhnzhkj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqydtzxz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2juxpzbwj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2snljbxbi.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ipblvtgy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2etdqkblj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wclyhqdf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdukgtm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rcldnebd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vewdrvok.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fwswddrw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsityld.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaxhrff.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyswbrkw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rygcmcqv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuhtcys.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iksvjlwc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eikaduil.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gpehbvow.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkpojab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzdruap.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvwuipc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mucwkuhz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mnerlrfe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqfatcz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2riaejaho.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdmazbe.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wklgrclf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2uajnbenf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vciogjao.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxmlfch.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfibmyd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzeorzs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2swiuztdd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2osfwwaxw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kobfadrz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmawnikm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqacbot.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pedchwcb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tomfycyz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwfuikt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dgorxvjf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ruevslks.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hofqmtek.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2etbdfvcc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iivjvjif.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyprtwx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoobhgy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwhktrp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2efwbujuf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhzjddg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqaqgfg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcitrbr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tsknvpya.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2euzpticu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2icoelzkw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2eewzuwfj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgbwudr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2udplgatk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2armlqfmc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrvmgkq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ztohagrf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kywnxhkl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeiahpd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlvhppq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lnijubry.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvugoegl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yffcbxew.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaqcphj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rzugimlt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qszvfqgc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ehstdzfv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lojrhuus.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvvpcyz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiglwci.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2riwufqsf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsbkhev.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2awlnawjg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2atiompzi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hlllsaop.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaeaahw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2chwrwedw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2umiffmjg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwjlwxh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2smqwzkrw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxdhapv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyuhrel.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaduquh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuaqrqs.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bakpjbbk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqixzgwy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2tddswlqk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbntdzh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzimpwt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgnvluv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2emhoytou.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tangqbqa.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tffdsknd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyezihu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkhzwst.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgwppku.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhcwuah.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kemhtqpy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnhptps.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsvsafj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrynhdz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuvcirq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtozfxx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdsflgq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2chnivpnc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvytlyey.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2djptwdvg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoysmhjw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnhyrka.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkwdezn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkganyo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdgsqvs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwujdwa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2filghidp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmzyvld.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfjumby.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2oretwqzm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdcjjja.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2klbvrzjb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyhidtg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvgqpqc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkjmbcr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rovajixi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vihflgod.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lvderxan.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vugbubpu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qcghhpxu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2afzepnqi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2atutndjx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbfholn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnyvtmz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlbtlcr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uirkqfsg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsxbegr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tlphdqve.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmxgttn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2raairpzu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzneafeo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aidqulhg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcppquez.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwibads.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2yowsdwhe.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbdbgcu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqlawrb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vxovspry.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpzchfh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhdhxqb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mloxlvip.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zafxtvbv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pptdogrr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnvsebb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmoupnt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnxuire.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bducyrzh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbczifu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwqpnqn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvqyfug.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gefbluct.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2idimtpmm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvqhltd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nysoypqn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2whtlgfmg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvrhftj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmxfzod.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzpmpdl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioytzfss.html


<!-- 参考信息 -->