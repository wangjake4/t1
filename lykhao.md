代发 wailian999

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2odbbuadh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgixwnmo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgodeniz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcniqjg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2guejxnbx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzzaejp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhynxxz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwsvwgp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcnqhhc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ornerxzz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gheepffj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqxennr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuplhke.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyxqtvm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2acggxzqb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhodcdlh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkpxrlr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kwweieni.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeiphil.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwfvpsg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zivxszum.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgntqxdz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfwxfcl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnuqvog.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xikklmby.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcnggik.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2invoijbe.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lazejsvh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2byejrapw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyfjdaw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2udrfikah.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhcyncd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zihznbft.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2oohrwtpt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zodjlnha.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xphizfar.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqciipoi.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zquwbvtt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aghsoind.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2olywatdz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnweorp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwhnlal.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfeyueb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnzrmry.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipogwmen.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcleqyr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfwlzdv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpswrmb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpynkwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyephphv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtmsnjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sttfupsp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2quzprsir.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fullmdyu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ynytksnm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qyukhfnr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtyrgzr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzbelal.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcqsokd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gnenjrej.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qofrbmkj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfwdkpg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kobryyjj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2blmblljt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2umtvvbaw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqnlguz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rogfscrj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdsdyeo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqcefmq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rizbilbk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxxrlbt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpzadjt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kybspgfq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cysvnqqj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2iucynmgf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjywkrd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvyzryt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrwpklw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xljweafu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtyshan.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfypovs.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnduckty.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqemrav.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxregumc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfotuzvh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmrebwb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyxyfdz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2eindtaah.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fslsnfab.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqfkrui.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kaexmhfp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nydzzddg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxmngbd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkilnkvq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wehtbrga.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdduyqu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iefoolrz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fddqwnan.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zoujktgz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2peexgspr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2friayqak.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqixeuzc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dieyumyf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lekzmwnw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oirryaxj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2htgsnkum.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgccwek.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2icolxddi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2agshowlm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjhbvpn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tipvkaao.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yilntvkf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwkudss.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmqqozg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2clxdjgyp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcbeyqo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwfvmgp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zmntnswb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hefybegz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeczsxa.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvhzber.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrmoksa.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxhnyor.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqeafle.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrprmjo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkobiprt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2quektbhs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdddeunl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qddertne.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iduqdxrs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfbyhso.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ajenwtoh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xreizsqq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2slizdsgb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrchaox.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2spjrjdjg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjpfxwe.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vegewchs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzjfdbq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luhzfjtb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwkakkw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzgpjfw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kgslurlw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pywvtjxr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2partlapr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sotpenwc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwcridv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkoblac.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaxfyjc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtesgfk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfuqsbs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrwqimg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnpvzws.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fltfnfdf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxkadpj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlxakbb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2prkjmdtd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmrulxo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnveook.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zxekblba.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuppeesb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eibiovyl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdeghba.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgaytun.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdwmamw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpvnczp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcczytlz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wphqaksr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbvypij.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cacplvvt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxoybmi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2juaneyjd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwikbcuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nylcmurl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgftvkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rghejrkx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oooofqca.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyudxjs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2drokawsf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2arhrcwwy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjjbbqg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpsjgzv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lywlzmwu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlfyigq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmfeijw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vltdbevd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpemujx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyvlyfw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxbfsxe.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqgoqmt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eguicjob.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxkxzds.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtmekkk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqsqwpa.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cltaksvh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrdcngc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqaiapy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofclpgpo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2imvienir.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbuaasn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2upbzidre.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2deqkelih.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ravxyqys.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kijdlmsr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbttlfm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhmktlr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2elanlvka.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqylhedw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrsulpa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hixzpyvx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjlowhy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jagibtpc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcubpbh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2onxgzdoz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2elwhsfjy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ditcybud.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2reerehzk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbveynr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyalghe.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfgtuuf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cutukutr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yadcyzjl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2luczzavs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pawrurqn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqpvbzm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuwjhad.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mgucovug.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyekriq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxktvlj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ubthvywh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ojajipay.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qzukbdoi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgqozwj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ostkwjtc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2alnnahka.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2twmmrhte.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxjqnvm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2inerznaw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyhidgz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwkpgfb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvnwham.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxduvdza.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wliqwhln.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkpgtwf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjxzzcv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwspkrxg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqftuxdw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wegeldkc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2msjrnzfu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gibzikuw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwpsnkp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkopqrl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnrqxck.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgxmymk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrqeslw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2chjscyvs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyxxqyj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmhuivj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfhptue.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqoffnm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzzqjng.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2evrystvi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdlyroz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qymuymao.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eemzomtf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwifxwia.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvausijb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlghoum.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrunvxv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yakthpvp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rilisxye.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svpwbjct.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qvojkqud.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbhbdhf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ztebwqyy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thsjtbtz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaxruzm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgfbpgv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkogxcy.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjdqube.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rddnfepx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmvxpke.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpjreze.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwenmpj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iprktlqc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwektty.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxujrmt.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2extxjhby.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhodbtm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awdvqjxu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2eozdltjj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyoizjo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nftmstsg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkihwwxo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ncubezie.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cippbtpt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjtfoui.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjwwbfv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoxrtlo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqvtvmm.html


<!-- 参考信息 -->