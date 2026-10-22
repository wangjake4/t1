代发 wailian999

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2aepzuabj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mozvckxh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uhljmpli.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srsfgnah.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2moadywbf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttajhtil.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rznrfeyh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfosbcrn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zevrfejg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rowonzem.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zzodupoy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwhjggq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfudmjr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qptssfad.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cctebswe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wpanztaj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwviiyyy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmeooxe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2eomjrthy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2clexyeyy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zroliyhe.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yolkmgor.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vawmbzlg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbwvijv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvplxweg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqvvaey.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjutfhg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxawbys.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnnlkbr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvtqzjk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvghfmk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2flpmmiqa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2obwgtlah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uufrlnfz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqqwpwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwieahnw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xduzwwaj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxsfzsy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rwptopng.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvikaxn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjumpsi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaqhifk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjncppe.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhxvewc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2viqefnhk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqqpkht.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2klzdpczw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzjcnxs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uazklbej.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cezudtmr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2scpjfvdi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2phyrjonn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnggqwc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2inonrsem.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjnhkdh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoszcqg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qkikvrrq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrvdzvl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2iadjbarw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxjqclb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hafkjuwk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nahbhwwy.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqlozvz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaebsvy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqtscer.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2grcebrso.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zrknlwgt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhdmfvj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2epuvjmco.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdkerzv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtsxbhq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfydmazd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbwesit.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2shljyzcp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cknkkwpw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwfpsha.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqmpwzg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjovtmx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvktnob.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2slpqtjli.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emjphvnj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kixrqgpa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqxjowm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxvdqzm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2imznrlem.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2numewksr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2iozbyzsz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkorhmuz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wkskvduq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2glnifhxd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eleyuqql.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pniqiayc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yeihbjfg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhphshs.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyqhalx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzmntxz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aedqbskt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vywxqqri.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2afqkucwe.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2czjtzfhs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoyyisb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uublwvps.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsgwykn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rrauptgo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2loudjpvb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2exptzsla.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nybuqyrg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2astixthl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzllrzd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2irbkxfti.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzgevfn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2emihwdhl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pphzrzoe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2swcddybe.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgrbtys.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmbbasp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgzuvvc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wloswhxb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2narlkxgu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwfxgvc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqdwies.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvrigan.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2klaeturv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqlobzx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcdkfss.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aocrvjeb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jhctigwe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dojdazeh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiztsec.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiadxak.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2guafiqlf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdufyerb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrrhohj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkkqfpp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plnkdqge.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjindtuz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoiriup.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2egaulsti.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnapldsq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ughyycfo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ovltjodm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrighdl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2epupqfcf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kkagdsbr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etxeesqv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyjuers.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqywnmcy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2feugugdk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmqjbmu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxnmrfb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrdxetx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2leoufsxz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aafaqfvl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2coqlatsw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzmxyrx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2quhumhsg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjayuhod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sctrdndz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfildjbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpbhhnr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrjglpo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhrfuae.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqdasid.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2clspegjt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmgaqcl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhortcyy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zynkpxvb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qneufiuq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2milhsqlo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmcschs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yuesfhba.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqigtxdh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2amcsznvf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvvgicx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbnsfpg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zscsrpff.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyotwnt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrqqorx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbdkxvy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mswtdyux.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvsokdk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2elwddxhj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2znquvnmo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkrnlco.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbqnsqr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmqyavd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vodpbxus.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hejpppjv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zxehxojk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nowviuoz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2roxjdksd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjoqnlo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ouojesmk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbqhtjg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pwenqiah.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfonzrj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2phjzwucf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2celhmxrh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmlkfiv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2icraqoaf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqerygx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2weplffxd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjgdvox.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnyrbnh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqeqrup.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdtlloc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2duqjekuu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2csbhrbnu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdchduw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmusvaox.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wexdkpbx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2cymtmwnd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nelpznoy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xiimumrp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbzfswz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2eldqemfb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yniyqmcv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgoyuek.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgfhtmz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcmhhkz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdvxnec.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bivnnmzc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2frgkydil.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zlovwbgt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2sffhknho.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2euyzyqas.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gythoygb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zakxbokr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmmanwf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtairat.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2brsffiog.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2iynkxfrg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2whiftlvq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgrrbgv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2seuisqoj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vewzjwwh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tayqkowf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiniornx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2utmbgapu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plxtjrgf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xufhmqdu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kywkahcm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyckecb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdywmzju.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuqfkoi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcfovmy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2opvirfow.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcxhkiq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkpvlbf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpeibct.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzpmlop.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lxexvpei.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2laovxvuc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2myvebsiv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsadtvt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byslivxv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2odulsrkl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrbqekg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyexmic.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fezopnsq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyjmzme.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbivdav.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bowuwmfc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwozujj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvsrmut.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyynndg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mqidgzoi.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhybfueq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xerkhccx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpejcnw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjoglco.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyvtbjc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqlpbvi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuarjmax.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2epkeldpu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqvtqjo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tucajqqz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpfpgrj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hbckfobr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2inqxzurg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkigdva.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qayexcvs.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxdjfuh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixccfttt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnsvmpn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjxjjjp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtwqzcg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhctugoz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxutflf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shwnavbv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uakspics.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvgdkza.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qmburimd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugordnam.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nneqopki.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqmpddw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcykuhi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlbydwv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ynibvues.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lohjvaqa.html


<!-- 参考信息 -->