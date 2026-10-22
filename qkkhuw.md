代发 wailian999

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wykehbyz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2awbqjash.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiusyec.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iesaqpgm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrbvldy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rxenfqmx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkdcpdc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2szbzciud.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qttyotao.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2azrfihsr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxiaxdv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2aolwzxub.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpibctr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nopeuiqw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tmslusio.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqignnfm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxwqdyf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqwdbdp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oouzpvyv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cahfhlmi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhshqwn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alflkslt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvamcvsn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyorsiun.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eegzwzpv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2robizxsj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ztunhwlw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwdcrpb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mydylzgh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sngochbv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gjisbtoi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjubkag.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frclnmky.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mulbokql.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2igdkibzn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhvvwlo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuikifsq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2titvsxeb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyscbkm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xqisofxc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdbvdfs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2opuzksbm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmpqqtr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhlkqdr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqccqqex.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwgueha.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2inwkvbqc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dktktkqy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vieunetk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amwqbajg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxstfmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjqafoh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrxosqb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiykngq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnxcfjm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnlwbxp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2poievgoh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kczudcea.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2arkmpovh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tnduayjd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uaffgcir.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rjooliss.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnqhser.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfoyzbq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcadzbp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahomvrul.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcfekuy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaymokr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfurqtwm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrwplju.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiehfwm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmamnbh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tviwmmhx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeznjqqb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xtygxjwf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjtadqa.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqxweog.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgammkbb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxqbmgd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyhtddb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tzliyyve.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkojnwqn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbyvbll.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfqdubc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxfstsd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgupvnv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vukusyaz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwckkdb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbbwwpk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ripviwnd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2orxcwaby.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyzzqoj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmugrbv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqkzhqs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hvetpjah.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sannujdp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2spsqoyng.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrmngsg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dxowqapu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjqutik.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsirzco.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfufgtii.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjarmuu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2khhstnjb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2beamdmhb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vllwtotz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2msqhsjyg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2klvfafud.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjbqmnd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lliyepde.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqrgwee.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2igtnjeue.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxtgzkg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsipfbf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trzwvcte.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjqlriz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtmbwmp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrywfvo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpfqfyk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeiuhdt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqqbumb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfcbkje.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kawgsmgo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxjocrx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzgpopd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtlibms.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzjzcdw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdcrkbe.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuprxpv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdacxst.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2csmlqgsu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwumizx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tpekcsiu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qazxirft.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrcqqmj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltodxoca.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdksddq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoghbjb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tomplkol.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnxlphu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpibpry.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlwgaph.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2knqisiyz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpnhxsq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jgekmcof.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfliril.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbevfio.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfrxekv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlserkqy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxafufu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcscttx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgdqunx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcozldgt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gsopjygv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqcyyhr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oiorokuw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhewpev.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cvafwfrs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlevwmzz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2naevigkb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pemtyzrf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxmiooo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhnstkp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2sspugvne.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bayrifbm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2adbbjubi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvdrvmg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fhigiygn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jstocznr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuezxjw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2njrqqybd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwbzmbl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlffrxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2peemchsn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbvatnr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnttubmo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxmaqsl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2glexvnpc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bqplffyi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2argnrjgi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2omteeekc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2demsvkzy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wcayylxo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oymnkaoi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2aauozuwt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgzmvaj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzvhgbh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjkxhrl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xaekgpct.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rchkxlri.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpxirzy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hsufpuci.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmorioz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2altcvsal.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlpoadc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rucdlwxk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hjszlojg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzffqvfj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzlccfn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjzpxlv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdaswfo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbggygp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2govdwyga.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtueynzv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2juctctdi.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyzadye.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmfqzfx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrdyvck.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xwojvxss.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yujtduuk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcrtnjl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2chpwiicm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbdqkds.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jktvpetv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlzqrgq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjjidpy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqihfzw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zbayyriw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfaxbeb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2oubmonqr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drwfuqjl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zenqvyuj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnhjctl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sotzmhty.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvdzkpj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwcxdlf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2dckqfqhh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvghrsdi.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2shssibhm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgbxzjo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjyirzm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcfliin.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhueeoq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsmpyfg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwjuowh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwtswpt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlmypbi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdukohf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuxpvea.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdwtkxa.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdxqeyt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnntttdj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeovcxf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ircyxzwv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsildxzl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfumflj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfwgcgc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmegexjo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hyljbjwq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmyerxe.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnfyqpb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwchfou.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqememi.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjienvrf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrcuntx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrpuaax.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tygiqqun.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nipbfgss.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ueivjagk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aethawxi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrpzrni.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wscoldjt.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2krdqhucp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhkwuqz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aboktnjp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhesmvy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiwpkrc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2trlavzbr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfvunbf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwrqnez.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2toflxbdt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guedyuqm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hcconcue.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2woqdffxz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzqlqpn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtgoocz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2inlquuxy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuuswbd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsewpptx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2glrpaqbh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2otpbiorl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdekokow.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2txvofowo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sseakncp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lforwisi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2varvmaxa.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrqwyfd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbgrezi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmjuzst.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieocirxu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2khtvrdix.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uynmfygf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsvgisu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxjolen.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjeavyv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfivqiv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjprfpp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cufxbhcl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqudsot.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqozgld.html


<!-- 参考信息 -->