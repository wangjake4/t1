代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcliksl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzblxfs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yifexeyf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuolmrnx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfgalkp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2scvqoics.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxvlbof.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zveqwnds.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2reiionht.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwfjvbk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaomhiz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpymmyv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqpdwgo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2czbzfnar.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2adtgpxob.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmcowww.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlfbvua.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2duybotgt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2iswopvhl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gqowmntu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzutavlt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdptvpn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmjtbxa.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdiwmzq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nddrtaox.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbolpqk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlldskar.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsqjuoc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pysyihkm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgcubgi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqahuzq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfwvtjo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvxytmp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaqaneu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdbfhvl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzzpxlk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wneujokn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dopjdlkr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2asfymdge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvvpwrf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2scrxmzpj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2seiqznbg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsucqln.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2njvcdmzt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qkepatop.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfquumh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2agiewele.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tofmvayx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zolcogji.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtevyly.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyxmuim.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sakzqwxb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xblxdmdj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrsszcf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pabrlhva.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2awraxgcd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2obgmlojt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlwybdc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2btusnlat.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2irnqiaex.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dczfjpvp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2irvbqzhc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fggewxdz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2omjldnas.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yuohkygg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaturonm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxeqssk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdlqihn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2frhudaph.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwqynxs.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkigzzhe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ounjmhmf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhelvqm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcotkor.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvzmkby.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dblwylol.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2olflqssg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcbuipi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdgsing.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2roeogpav.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bkemekvd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqirvdzg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvavntu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjvnnuc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtslrqeu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkrultg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqjlpca.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rypnraqh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ikroumly.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqezxsif.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zglacecy.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsnsctu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2agxgbice.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrwdjku.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xthxdnrk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2whyehjzx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtmuudr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaljejff.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaftivs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhpftvt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iopdnewq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2spmdfwfs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2toumglog.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnzkgif.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcvircl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yiokrumi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yedksbwl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hszxplcw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2khoiuzck.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxucotm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dncpvkzw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tylygroa.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eizkdicx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrrqzhk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aasqmpte.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvtidgl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fltgmnkv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ainhooms.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyopvmt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcshiqp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2poadbvrl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfwobhg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpuahpt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbbmoar.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbgqjwo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmisrntt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zixunvnd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iurulsfg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iqylosya.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvprxxnk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nmawljbq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmvrqrq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvdjgat.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uacepmlr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtojgkg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2okorgkuv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2orbodfzg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxudrfl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhehiwik.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2germfuly.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaripua.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpdrvnb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2apdwurzs.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlysawzx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wanhblsb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vryldzfh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2slqzovuj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2atcxwpyh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkknauue.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdhgqhl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsenzsr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyrgmdw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsytotfl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvwkixl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyatasll.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tofoiodt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xugkbbux.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdjxnls.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2blyglict.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbscjqz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfjhvhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyflcqhi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmirjlqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqovjuiw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mewbxlot.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxlvuko.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaywngn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcecshk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjyzlxi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsncaen.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xuapwpzu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jekrllym.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kzctpcfk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrsbtvh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wwptayeu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhaxyqk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyjrvno.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcphkcgm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2agcivsic.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwrdjfc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2accshkhv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzicdfx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2crzkzvpf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtqtuqz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2phikatvf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mldxtjki.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2exvunzfd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzkomsq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkvqjap.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aibyztpt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hqetyzen.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqidxzwh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwczttx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjkrsee.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbgenvc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdnwghe.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2goxqzwxv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2broqksvu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjiqnfr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldienwaa.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqsfkto.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrypwrw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eblcxttu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgsgjxl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoqqjzi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qryywadv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cnalrory.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkijzskr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzngpqa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2khxbcfgt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqwfjic.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2epcokicy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ljonriiy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqwhyge.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvgzscr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2geivbsmo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2delhbqzd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2geaezxpb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqjqfpx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2brvublbj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhhanur.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmvclcd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2byxtnhaw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qafgfyzc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlbjjkl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrxshsp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkvpnnj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyyjgzx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwjkodz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyshhqu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgxfifg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2iagnyblr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhdcftk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mogeufqf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfiscqr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2awmfdsue.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuzhqns.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vfupgctr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtlprep.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbrfcdr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvnqfaw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfztgcb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yauomfqx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gavxonyr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kwynobie.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2aadtlxcy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfwkpwj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeaetov.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fizcbufy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhjyfhl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fubfresc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgkwuhh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqkrvap.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpptzng.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlqrjcn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbqxelw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpgujxs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2obwrsxie.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiojqni.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdvkjst.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkhcerw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwhqadp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bmioghpw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhdhrpg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmolccv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdpnpco.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sveowdow.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsjvznc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fwupiomg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrnvdkz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lpndloui.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cetpctpx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzppket.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2aewpnigj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2orqjwqbo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vytvqpcg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxtrqkr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkinmkhp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnxvvqw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwrapyw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uewilokw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsuwawe.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2geerpiba.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lionznec.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwbulqg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdohhel.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdgqqff.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejekslee.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxpastx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbphpid.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhqkymt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyximkhn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeyjlfz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyvxsip.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pywolvzz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2czsvqyir.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2upeqlbdo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfkvsrd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rebwdrby.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qysfqmim.html


<!-- 参考信息 -->