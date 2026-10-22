代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxnbyhm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xkywjphv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aabtfmho.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2brjmxykk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcciatkj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2toomgvvy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwvhyhv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wacuauoi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfspeez.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbwsrse.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvomtet.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlxjbul.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkshjgd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2khgzzhdc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rovphvud.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjbvhtp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xclswrld.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfkpvsh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2spcbebbp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhcnjqb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwxcydt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwisfwx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjqthsg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kppjggdq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzsfrjc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxksqisa.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqjykrf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yucryijg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhrpwmc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vuteketa.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yenwxfnh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgzjocv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2izpsxbce.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkrmxfl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wabmwebw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgpxrxo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lydeltza.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcoxsan.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsdjoqm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkgzkyt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjrddny.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qttzntak.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2eollxwvc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yaagngwz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gnegxzic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcsimai.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2twwcyhfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avcggwcl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjlwbmz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dawqvctb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xskiedmy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrfsrzd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bncxlluh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbeabjf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzraptn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eexvyfjv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2coybyczi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmsoleq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtvynle.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfmvhau.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kqysltuf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwezncif.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uvanlsoj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzcxleu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbgpqjh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywulnwev.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnhyaiv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcnjagl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xodoisgo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffehigmx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qsekpdeb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqovfsd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xrphsbmw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqypvcqa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxklvfs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwndixo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2izusmybi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqhtdvx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyvaglc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbbtdxd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjswnyuy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjczjwf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2grepiwuy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiwfbot.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjxmwmy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpyhlba.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlaubli.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqodirzj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2miuvxrpu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvtrrkv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gvytminy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcbtisk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjepaft.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsemiyk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpyxxpp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2njtypzpz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcbxavn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iipcczai.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fijbxghi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oucsjtsu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hatlgilw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2peigloga.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxpoohy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaytbms.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rydrvusn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bapaijzq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoshcro.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2letiymvr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaoaxmr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wocxdyud.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcmpokm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqlxcyi.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uncgciff.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zplxdbhx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrwaacr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yvawtltw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcghqtu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pufjzcyj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duvcwpca.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxowhnd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhuwpmb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xknriyje.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqliguz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2idmtxqdy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gduldwdx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbqmznd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzqhact.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ckowgnaf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cccmlmch.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlnidyl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2afqjqjwu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvgfalm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgainqah.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sljqklyn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpvsabg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdkdlhc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zmowrsyw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkwctzx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwpnqzi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qunrtdbm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ppunwijt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qffxkqug.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rssfykvo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiesqznj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edxciftg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bljcihuy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rftdzrzm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuohipb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiferedt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pxupsbnb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdddhmkt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbgmuuz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfgelse.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmznqex.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdfcdhd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qantiwxj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhpwxaa.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qzslyous.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqrphnf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrgtkpz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrwysze.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdzimzq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2esowvxds.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzxelxl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzepluk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2korggezf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qemtjyrz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkatpoz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjkvcle.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2risymsqk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlqnyec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkzaefy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dulfbslx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wytmnehf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2adfsyfzh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sowlyoyo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfrgctc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2asunqglu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gignsnvp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2liysrmpn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmprfyz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xugvdxsx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpfirdr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2shxqozuq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeghrfr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhlyuqp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aeurmjaa.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxbvgxm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpgqqox.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2aedxhark.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2itoykmkr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2segdlfzk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zetzyzpa.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2exidlasp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zyamxbxn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbvstok.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fkszzlrk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aowjyqrl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xenkukwa.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzgcxut.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuyqalf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uedzjjwz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gvghxqci.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wurouqno.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gazratdb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbxmngq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nrljxgdv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lixpaxga.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2aufmtcmo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bttxjnth.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkoythi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnzbdcw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2elrwyjiy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjdcrsz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqvvjrq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbuassr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqmfrdm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qefaqtsh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsrchrq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmuispc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zalkqbvu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqushkw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkvldpr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfrgvhn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoffsgj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxnrdmt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgkgaar.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2palowamj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wponaqpk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwuzkzh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tozkmwfw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2amfbiivk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwridlq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhjieyk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrtiwdv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkluejs.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wxubydrq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nazxixdj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rmieiwcm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqpegwb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeqogkm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2icuwlmrv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyfutgw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhcsgct.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuvsjou.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qstyrjwb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkxybdm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwsvsop.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vgykrdyc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmpxbol.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vteercwh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2esnoqxlg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2olkpdmni.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrfmdtf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeuilph.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2csfqfyhv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jovgugce.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2amrzrcyq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqcptzh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2riqjoziz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvgsqte.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmllhzvc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hbikqamz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qvardeyo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjzfbqb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjyhigd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cwktagxv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpuubou.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkgejbt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2whwlzqlc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcowmuy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpesrbcs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvyvcpy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciibxeew.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aflrhiyd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cduqhhsb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxgjodd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gojsmtbm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqllnyg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2knygwcpm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nezgymjl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkqahny.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpctizy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkavnux.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lquoyjqd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjjjhyf.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2deamryyh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nquzyaly.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2caabdaer.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcipbqu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2faniqrnh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2azidnqqd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmfllkm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsminxt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2midxshtt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldubymfx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcildnr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhqmzws.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfgjthf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdwjowt.html


<!-- 参考信息 -->