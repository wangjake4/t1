代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wnducqzi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2athwquec.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoyrckw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkejwyl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjqsbwf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2airyfbcb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msgjeiah.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kgezvahc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbyubdl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2durrsipe.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2skpibkzf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvbtppf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rddtlccd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgvlbbi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyovozv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbygdrq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsfxbon.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyccbhud.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpxbtnc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2khevllwm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrdnyko.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yijvxvni.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxoklrd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2svhrtjfi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqmvssg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ietnfpny.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpflblg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbiluks.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjyxrxl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlitlqj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mozzrxzu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2moaeqydr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdrpjna.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xfekhmhf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddklqxme.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kosbzzaw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwvqeph.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwnihxv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2geqjhytj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpblfxc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2okguoibo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2svfeokhr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2sttprqyy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nzraipdt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwemzwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeiffrb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzlsfay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yaldlvhw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fikgopac.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbdqwsq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2execzmxj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bupdrstg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2buqbkamo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zccagajp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzkowmc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2upfgnlzb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnirdyi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uoigmtkz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eccakotd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lshegnym.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dbftwcjm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2upnflwxj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pdopnyys.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eppvbdqv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyauluy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcehxkb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzclprc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlppxwe.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xgorsjcs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxeqvbp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rygrddth.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcfxzyt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdjcwkk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzjnvsr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkjcjoi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmxgmyh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2smrsiyff.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uchycxzm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vksgghks.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkgzlkj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqfgoxc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hwylouxx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vblfxhdr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnkpsnm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbdfatr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyeqycx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sygixaxd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2meskqrgs.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ufixjbrr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhpefyd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2thbvevwl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fskferzp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjablcc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaxhynu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eqczhawe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uezijfsz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2caanguwz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgsclmh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cavcavht.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rccmzdgu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaulofl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwfkxdh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oumjthin.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmshuyth.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ygurvzet.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrduikt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmqbuvi.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbvlfkg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtvqaqe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrotkwv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmkvumi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjhwkbp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgeavnc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tpudllwe.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2atpikcix.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2womiynfi.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2crxnidjs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2slknrryg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpyzwfb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jghseorh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxbmizq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxivxtw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmccjfgo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfzhdxg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2threwqys.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvltbfk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2inobdwtu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wakdixhp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pousvocd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkfodum.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgqkrrw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmukluj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqzvlzv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2alczdylw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkecxpba.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2napmdnmp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbayhlg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnhrboj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyszfhm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mewwaihb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfdwefs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euvavkkm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2emeinuiu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcqpwvu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bloepbfh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkylior.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwpumnw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wejpkedv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdyyzkh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tsodlipt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdptavw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2frfakhil.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ijglxhvk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmseyzd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyojrzz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzydrig.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmthonbz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjgzitn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnypnix.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnfeiir.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fysgqvef.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gtidragi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2chsqwrtc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2acbsykii.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrnitba.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nfllfmle.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sugozbmj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkmcmym.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2chexkkfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thnpoiml.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxdcben.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brhlmtnp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2agabtudg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwoulpp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnezfqb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcdegje.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wauhcfmw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjznkes.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uympzgfo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfubned.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjncuga.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vthzainx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2heybvrok.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcpxwsv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nieaggep.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzxnzzj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqphopdq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnkonoo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkceobv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvwgylc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiyzbkb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoypflt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ddblidsh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2goxqozbq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqkcskb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnweiva.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgjffvf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2guxpomdj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hllxhbpn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpxnqai.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kczwxtma.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgamnwe.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2emmhlffj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfavpvut.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrwkvpk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yndwmtxv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbzbqgd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuclpty.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2spdpepht.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uedmloby.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2flvhgobb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhfvjge.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2teqeytwl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvrdfhb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2aamitryt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhlkjqy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgfwdvq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjxkqop.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2crqgackk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsxejvz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lghjlwyo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhvaemk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtnjzlj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfwvagc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nghlyyoy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fnapjtsw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfihtxw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnnyhyq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnecyfo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yozyysiq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpsqqxp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uukieyhy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjvrsvl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxqxcpq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tokenajq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vfplgtvt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2uugolagw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2atzmgiuq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgukmlf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeysidc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxsifsb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsyovvp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lvifcjae.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlxuqxi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfkrfgd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2szsmcmfc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjqhcue.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rdayxiuc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nsexvlrr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2icytzqne.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ussmuaga.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yywwxhrc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cehaqvzn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqqkmfr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hipximys.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozslfmda.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rmznpbna.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2umfihxya.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wccyjdxp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrjxyrz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2abtcswel.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjdxuff.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qexulipk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmtpskt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvqpiyt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fapheqwx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2deylgzfv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhogbzac.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvmgsjk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pendacpm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bffxrnem.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wiftvnni.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfbrfmu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqzsvep.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckprasvm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nllecnvd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtzbdoh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rayuqrgc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ptehbncr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2elojjhoe.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2htgpmwag.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjahnig.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzytjhy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qddavjji.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvuvnzw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2deaxwqvw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrowlpn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2guptaufd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrddeso.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyortenx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaacrvn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhipwlt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdcxild.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzutkcm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kstfejey.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kngdioue.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hxytmfsa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2edhtfdtj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaswlwc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtujony.html


<!-- 参考信息 -->