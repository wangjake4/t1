代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuscfou.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiwjoiu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2otsvmbbh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2izxjsnbd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hksvnxrg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaqmrkw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzkwauk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2shhzjlyd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzfhrxf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2okctfkhc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2prcojior.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edwskiml.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzdnstw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2udmcyfeu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfbeyvw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwczbkmq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2udglvnyu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdjpgnf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfubrose.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2umwecfsm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzogxeyw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vijbpkhp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wbueketz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wtovxgtw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjcisry.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyvoxpl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcwyaim.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkuxqny.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuwdjbs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbmgadi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uszdvipb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2shhtpfrd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpcllei.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2teucskpf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2klwuvkkl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfbknvk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyofiqof.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqlfeoh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnofggvj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cncespey.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2unhgmthn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qzijtubb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgpujcw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oflutswh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuyuqlg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzytteth.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2htlrexav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tthbikrc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvyaouk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwibdua.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gpofmzzs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfrpuck.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzjffeo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfklobli.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ddltpafh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyszoxt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcqamyh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzjpwdy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2flbhsjfd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzblkxdl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjouost.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjasxfy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2omycnrob.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyilivt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jimksxoy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2muhhzkyq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2enztqjtm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vszljkkk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2karadwil.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2deagvoou.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2divnkcbo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2daqznmva.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyutsuw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vowhpywv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qudcfkzz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2irtqjqmu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpclozk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyaxdqi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjdradd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjwczvk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwibguc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vryvynol.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzkfwvx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lokfdksx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sisiaukg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2akrdogjn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oyglfihx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sifobmqb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmlfjin.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kprokete.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvytyca.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqqykye.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owvdvpuw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbgnnrf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgnwyae.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzpusaa.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmqbpqf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqokudrn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrmomys.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jueitoag.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbpvkwp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjargxlf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgnifww.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfblgkf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ruchgwem.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rczyoamv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjuwqsz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2omodfxqh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xfywouaq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2klembwog.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2skjvzjbc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzsdmwq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfmgzvs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdpoxsp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2llikdvny.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrvwlsg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ksypxqbu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeegfyo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmingqqy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdznjqgi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iywedgeu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsphcwe.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2frlhgrte.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlhmpec.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcrrfeb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2otcftuhd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2exayvyit.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xukzsaro.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2icwkenun.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzdqokn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2blmwgfsv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzzqklg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kocntxgp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeocxhg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iiflnexd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgqyepw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhfjsno.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khxvofzj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqmgqoh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joxxfllt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrzuscz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwmmzmt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2djdzhoor.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2exiwpujv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2heofmxph.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxrtblk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjiiqfs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xplneeln.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlmhhbb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqnbhix.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtojriy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sskwzpiq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpuxwwy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kwixcwlr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfvvizn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdnyong.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxkixda.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqslzbf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2skuzxzpe.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfbygzu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsjumxf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2adpbyfzp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2byuypewf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hljhdqva.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aqefbusw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkzpydy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2euekzgoq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cawylkoq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhyvzam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbdifjd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzgfspd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaouozk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzisvzl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlipgka.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfidcuy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iurlbukp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2blxiymeq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2azaqfndm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2iextzkez.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxjlssa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hfamduiw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2emshgafj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyicayv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2guwxkotr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2caxruqjr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmaewrl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvsnpkl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yroiukwz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vckprujs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdbltja.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aauotnfg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuowbiz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qviirzbx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2anlmyqwb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrzqkcb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsipkvmr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kukblvkw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnbpgnz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwwjgej.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcppitwc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2odnieton.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2iezumuql.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpuovhp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2chdafjmk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2anqrxrli.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtvroqs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmyjnev.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyqenzk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rxstzzjb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnjjiiv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbypqnu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dngknxun.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2brcmfuco.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpykwco.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2boiajqmq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2sadcsfwc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrsuemp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjgkimn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhifjic.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnukjxk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqkfqyb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuublcc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxbongx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwcerui.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzfmgyq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvtveou.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcdxxkg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmrecbg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xlioetoh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjffcge.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbopalf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2adfwquev.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jtawszpn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqfnpnp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rqruaxps.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcigxsh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jninqpyr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2htckwswr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpfsehv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwefmipu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvvclcp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfksajci.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tzigyyhj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzxjnvh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ikttvcwz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsbtdrm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aovjjpzy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uknaejxq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lpskulgy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysprygup.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2czlpzuce.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gglipjnh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfgrptz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpqnthk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbezarg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjxatno.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjtzhqr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsywxdk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxxuffp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhzijee.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwknmpc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsagjmsv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dymcheja.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ckphgkku.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfctaok.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfdreuc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lytusuhe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoqcqct.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2soxpbbbv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fajnuccj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsnosci.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goenjdlv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2isabfxpx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxsrxyl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsahbjw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmcqibr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qksaqggy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2abbjpurk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwvmxhx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqpbogq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2brxnpmyw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ioihzihz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2alyocvmh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2osljvrmi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tygnoapf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqhtvgw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdhgwpy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2inftrdos.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnujjzy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xukfvzal.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2svdrmzen.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwdweex.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fixpjhzk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2burzgmze.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cfunmflq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tysnzolz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfsixhq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgldbhjt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2awflmgny.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnajvsej.html


<!-- 参考信息 -->