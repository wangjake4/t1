代发 wailian999

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2syqzgxij.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2figoqbre.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxfxffs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sfebjvfx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pjikbfjy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uaewadfw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jougmrvu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aobzzbjp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udrxkzvb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2muhjzfqm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmqixak.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhudzils.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2klemxtns.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sshwskvs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pefwltie.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyyzhwj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kymmdzfo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zczmvmzv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyifggh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chzykiul.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaqbxzt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmedzro.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcpvcdg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wojydicz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqposhjx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynregtak.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cyytscle.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsbebgj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvipgnel.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jfouopne.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cshlrvom.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwpqvuf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxamudf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqgiyfd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkayhnph.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkzkztl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pypkzdgf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yuafejds.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehshdvgz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuhtdrq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvczmnq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sypeucaq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oatfdpwv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkeztxj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2waycenug.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wckbfdai.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2oshgrvdo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vsifazcq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjmftrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czuwejvl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxcxofj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gystryfx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbprxjt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxepxsk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuxdsfr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2axoakeih.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eahbpauu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwskckzl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsmpokt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2emojncso.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pymqkpyv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jkelkuuh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsmvvqo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bklnxbca.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2burzsyif.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2euwkpsni.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fizwwhgr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2updwwwzl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2leexhxst.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2chhnazmv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qoriqdra.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqyvjcn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2efiimgis.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyxoblb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2euhxmpph.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edahruny.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpynuqa.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnnqisx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fiypfrtl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkulxncf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2idyroier.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2foxfvwuw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lhezhuyo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2stfcfrpb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2joyjnwrj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpakkjp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aynmdvdk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2anorxuvb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2opqulvmg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2czppluxx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtjjuwe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuypery.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyjuzsz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxvzwhs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmnrquj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dghbjebp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udwfhaez.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxmrjbz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzdcenu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2empckjcb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbswkpz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qterpcda.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2uvemwaol.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zytsqylo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bshkrtxq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdmzlmi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhevzii.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nthhcepn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bmibagom.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdirgnks.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpjevmu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfayoeoh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmtbqhx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrvfwgt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2neveasdv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdlfbhj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2edlyrhie.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpjjcbc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vohznevt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mreeidma.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2abppzjni.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpfuqvt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkfuoyt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpenxmoi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mazyfvix.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bghonney.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2deroygwp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hccbfxwm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2emedjokj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fquqzlrw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2caoesyqw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2anifxuou.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uabauyes.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qklwqyuv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dfepenut.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgalgin.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2phaskqad.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkuomuy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxmhvpm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwgomfu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aotpztoi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieywqhhp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxsxkjb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcezlzjh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kksfxwqn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eesxhixk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2prfprrsi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuiarvq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iemcilnv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adqslriq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ravoklwc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfjqrzf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzryrtkn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeresje.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gloluyau.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqaiovy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sfisvtvx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkewzsf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2unwbmsmg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgwrihj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhifmlpi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nizninza.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkebibyi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2grohqkol.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2midggunm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzrpwsp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvavvba.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iyibswid.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuvdkkv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgmplqy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aptbqupw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2efavkfac.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvywjuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlfmwau.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpozvkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2defmrvfi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmxbbgg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaagjpg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qklexpvv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2onwljwdm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2actdvtqf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhszmdb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tljckubp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgfklbx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgygnhe.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkakmve.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvpuoes.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xunmpbqg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyrzask.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rknlmxze.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zocvftkj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2usprxdkl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2owmywcvr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nidobqrx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2apxjbyje.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiidhoe.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrbxlhg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2koscnjtt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjpscdl.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsaxctz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2haftfben.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2srfvvtlt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2duofefjn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ounmxubn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhkqlvo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2oizlfdsq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wyegbrsz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2psrrpxgb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pktyexfg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpmfrhs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoopxhi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbosdcpo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoxdwtv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfpjsbj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cqccqfob.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpdnfwc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qjembpts.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2aohsrzht.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcvqkcn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iotiznfk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txbdtyxw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hutogbri.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfbdkqk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2phqemugl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2iduqvwep.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2stdeijyn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2smmtwxox.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxpoyag.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vfecrqjl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dhinkpjy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2grbiwrdb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2updjpqgk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcolayq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hucqxlpj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vziqssqu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2edonjmcb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqoralx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qceytkfb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gtarsggt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnmwmhj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yiydfjnr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dovxqqtd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaxwzuo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvhvilf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wspqncem.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dokjvguk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rqegbaik.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyvykun.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvabqwc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2djagebzh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcsnavs.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2glqbccmq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgyhiiu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvnqpzk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sliprmfv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwidcep.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxolnnf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvxenll.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvixomw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzbbesv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sykncpvt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rangjhhd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hihicfba.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfhpkle.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfzkldp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkbcpws.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrpbbkv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsfwgkh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvyytjf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2heaitvir.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlnxwnl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxdxpud.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jclxnrbt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrnlofp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gorylnpm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuksvow.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bytqmxwi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2myrqqmok.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsmqici.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrlpsds.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rcebaezn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmawulqp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dzerhxkr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzqtifh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxvuhbv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nixbzsyv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhebqbst.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxzjthc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xulanjnv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjxlesg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lmszkoig.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfymhgj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcmwmpv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhydgdes.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2quumaosx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xafpiedu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwlelvb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqkpxug.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhcahsu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvpnftw.html


<!-- 参考信息 -->