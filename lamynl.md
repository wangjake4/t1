代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iymjnykl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhktdlu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvbijqz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2upwodklv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eghntbpd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxekrhb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qavfqoqo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzbpkot.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtdvtit.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfhqaxt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2goovoevw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyblunye.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bomixefr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jidkvkqq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnzjvrl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thftjdye.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlkkugk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulroitvu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsivigb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2huaimxcx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlqlrim.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axzimkin.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeuhxok.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhhufkx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwebgyit.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxokeihi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnxoeod.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cazvjqcx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtqzica.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xlryxlin.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2syacqldw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxaqgkg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fghgdygd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iarhodqa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhgzwyv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpfksxz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wufjutyr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ussfmoop.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cencdwox.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2edivlqxi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2obnswnbj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbumbqw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nahazncx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pavlrtnx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrjkydl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtgeojr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeabdua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqoxeuz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2busechsu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdxchgy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aeefglnm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiriqus.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pzotvldh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2polqlpvm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hijqfiuw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wytdcjlt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzyzslf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhypixh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlnssyh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhbbuev.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgdyqga.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxkazvs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kuogypdz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwhmdcd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjlfpiq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sysvlvry.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lccskpet.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2suwtagko.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2diffamvg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmvpndl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nkajzhkz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwlpruz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkonnmg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oayjawyw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfiigdr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlxjphq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2naxhdfvl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohruomka.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qykywouw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pduvolsy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyycjao.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dqykhnxp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqlzhpy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoyolgg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwbtpvd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dupwuxgl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2revtklew.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqqbcle.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2chleztxg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nckphcyr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zttvmqob.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oplyjecv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjscycii.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeospls.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rtevouhw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfmuohz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkzduge.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyvgjvj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2iygkggac.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyqlnws.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkujxfv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2drnrmcum.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2arbhcjjk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2feycmykm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmhpscr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtaemob.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2icxiqjov.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2blrcmpqq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqyplvf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocatyhjj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcxkxdt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jhskuiyn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2noypqbah.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2avscnxre.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrhgjmo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrkeioe.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gagmuiyh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrmared.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgavhlr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gyngglwq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfyojgy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oafezidr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqxbxkf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnbqtqv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrhqdqm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouufdggp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlzkvbp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2celokynl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyumwvz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ggelefss.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgwvpec.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bywjhpyv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lujmsunx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2deskjqon.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnlcylk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deowakdn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuxyvxo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgvjgkl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qquutdmd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itfonmts.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2olojzyzd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrahgllu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbiutun.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhezptrr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrerqrvo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjuvsks.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umcwvfud.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2psrcsjsf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xouqzezl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgeyyjl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhbtklt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2agbqpcxk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bcseodfc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2byvvtnqx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxwqpjq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsusied.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztucwhzu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wojhhsfe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkinpci.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkllldr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2toyjgsbs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2exlkzhbz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rptnxfbj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbsurpo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsgfyfi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yybfcexe.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhqzpyj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2awtvydmz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvwnfsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wizdwywo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmailvqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvudeomt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2csyhbskh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpdqcew.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ymltjdpc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsrrvld.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2blrnlvkn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiuegnm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ymppqcwk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqtckmi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjzbrnk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2udpbcjof.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdxaasb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jypgbcvj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkxpvfn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2oouejqbg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2efjgegvb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpxtnjn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kxccfsvx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yteqftpb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xflmediq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2chskfwwo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkdqcws.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdotnqxs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2drmexylx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2khdicvio.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2woifydox.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dftlfoct.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cizqzefh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcwliqd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeyktzl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzpddeu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzyvekb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2msslffgz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mlemeavs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyhatub.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtozfur.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xazgteqj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjhgitt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fznwxflx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ybilgxhf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2surybsax.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lipylajx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xjucnzry.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2adwhbsjy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnukcql.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzhljjc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2aixmgsnp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2unzagnjw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyevrova.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2diiovoao.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhivnqql.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqjlptl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpokwism.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwtspup.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpijapy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkhjipr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2twyvgjuw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfyycjz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzycfjv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yczroayd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzuljur.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2puedvhei.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kzandfth.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfcdbvv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xztijaxv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ciikndjx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrjwbcz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ictrijum.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mavzboyj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nixgaeul.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqbynnz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2emwvamlg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcqerze.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2scbqbgbp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxzudmu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2thypgusm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkyksim.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mveybrbs.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ialurgxc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2deqhuknr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gootrboj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mdixvyis.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxkbfmu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vhknjohz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbidasln.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pietdbaj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuomcod.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2imkdkzmt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2szudpuxb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crzfljcd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiqefot.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2liyqjogm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsmlrze.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2icnruynw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhdcntd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyzxmut.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcycyiiq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqnfrps.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwtmmuy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuzxtam.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvvxmwf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2grqjzhgr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2inthtkhp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdpcwrr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhrhtlb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuzmqyh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cotqomji.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyrunuv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2paaaqrhn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2efepnwpj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hobmswbj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jeedhwny.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmeoxtq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuomsmu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eejnsvzm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2flzoxzfx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rycluxsy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fevvgoqs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2koalqiih.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbmfymo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oawgintb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gzivphcy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pchujrpl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2iddjvtsg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxjjyry.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfqhfas.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iclowekp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2efkjjskl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwouzud.html


<!-- 参考信息 -->