代发 wailian999

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdpcpbe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcbcmgu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqgvxpy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kliilgsw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uutskqiy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2aynbbkpb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrqzpxz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2frvmtfpd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhzrzkr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2scekdpjv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ystmfrkr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zclxuhyw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rpklqlyu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bakhiisj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyypqyv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksblrswu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dknoaqkb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2atlklejx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuurmvk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmiguxk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mzigevsf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zamzgklm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mclacdsk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2iduhrdrl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlppupo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyduhjn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyklkhf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2epmcatrf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoskyhrz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2evvjbjij.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bymxwcyz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2owkoexiz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2limjweug.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2anahpcer.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeppxig.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmjohob.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqecptim.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqrqsgn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dimobvpj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlehsul.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sizaukcp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wptvnggx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmxrxno.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgmumtt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2skpsxlvl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2goougztg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dixqtkwn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pphmjhbo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzhlwbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfvhbui.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qedolphy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nuprsagf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cldbnmpx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhavymt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2caczvwev.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jidetmqr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xchdwfow.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdduwng.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdlyznu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcakcpz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lheeqlof.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvdzdnq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyklcdd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lthqfzbt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2csdbpnkt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzephjm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2naxahpor.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cffrrlpd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2twetqksd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsfrbqz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwphjrk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhwiagi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2umfcpwid.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxgwhkj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzsicrk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpovkvrz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2abbjxpif.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpcturm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ihknjndq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2akobjysn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtbqjlq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsnnycc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjcbsgq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsafvbz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vetzruna.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2flngieqy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2atxuzcex.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lflkzfxc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nviurqyv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgeohwi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfrbhve.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiourru.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqvgixu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvjiohu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjuiakn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgsidde.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2muraatgh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrogvuum.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2naavgyjr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iysyqzxj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2slagckhg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzhlpva.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrooief.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeaadsw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhyjhgu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2syjfntls.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ioksvaes.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoplahq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sioxjsmz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvkgkej.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkoljvr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpicbhec.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwqpqdy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzryybqt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2twopcrfk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2auwsstse.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzincev.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhnlvcx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxomhju.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeuhwoo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwhekun.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2typvumap.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnxfuez.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwnadrn.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2emmccpby.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdmuhxj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2unrtegxu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2imamzsdb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2coyybxeq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2crpassvy.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sswoujvv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qckojisd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nauidemy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2omfpyrpx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fodxinlh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2urpvlwuy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tjztzkne.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ushkunbn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaabnqp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnjyxhe.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcplpxa.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkttxuqy.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2btfsvvqz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpcgvuv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzcbcwv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkohuxqe.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2etbagujn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jffmaeph.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jctxzfpm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oplsxnhh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eadxhhyk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wycujexv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byuettge.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yruylttc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2igylvkde.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpozjqx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aczpxygb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrpabkd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfbxhjg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bfskacum.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2afuvyham.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2udhgjzeg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbejsfx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvnlzmj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtiscmo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yprrjozy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjrghtw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tktedoct.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wqivgsfc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkmdega.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vetapwhh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2syiwyrcq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wosfdljc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiderxu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqghpkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2relmkper.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzrctdt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xuddcwsa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfqguhj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ymggzjct.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbqoqez.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2skgaorzx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdvgijz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpeopto.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2apbfdwwc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrjngaj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxbsipr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvgjofo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2innupqdf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2avwnsfux.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mksrtlgj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2odivezuy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fiskizkk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvpkcqe.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hargbbpe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdandei.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpwatwo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdotqyhn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpmnpwc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdjhjte.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvogxup.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwnjwin.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xxniiqqe.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfyigfs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnhkehd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lllqtsaf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfgrmbv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2awuhqlat.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoicfsa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2japjfvcx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmzkypq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjycenk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tlogubgh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vncklytb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mojlyqzr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjnwwfw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2blyfonom.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fseiqvje.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmffnrs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2betnyyis.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2obtbtxsv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wvztgbwv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiqcduo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyznyiub.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qwihyghz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2immbmppu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cidjdnuz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2slsinivn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rruuizsy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdtpwsp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsdczpc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhwodpz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpjcvif.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nqduyeyh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hncbilna.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrgmpqt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2owlmvkit.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jstxtvbe.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtpxyoo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2brmcvbgz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2drllcplp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaevvuy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2svfftuzk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjgsnzs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtycicid.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2euunnyjt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnfeguj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dosiiboo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkzmgcl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrjovfb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyfxttm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2swpxrnez.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwkjdoi.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcukrkai.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fnygajek.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxotwgz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdrzaoy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2isgiszan.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgyatfe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqrvsof.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvydhzh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmkhwrz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtvsnsc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoukuuqp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eleyagdf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqoptbv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zacngmsg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2izogavbd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmbiovg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ljooirpl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtlswkn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdhovvf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrbndfz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpuysti.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmwknml.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlemekih.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmubikr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmirmdk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuocffq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2urllaltl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nligeqkr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2sscttdmf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaesijr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhnbupe.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhgqlyk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjzwlez.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhbthcp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2znbrlwod.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zclpvows.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtialnx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkjwqqa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcohdrj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwtzccs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjpruhy.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zoviyndi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zagertgh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xbczscxy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgadedtv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoyucse.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2imarydwc.html


<!-- 参考信息 -->