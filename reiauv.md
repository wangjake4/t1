代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvzlgxs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nofplcbh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjpfukh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbmsytk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2matanbru.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gczhiuws.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmitcxex.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uglprayx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xxihlwza.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqntxayr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvwerfd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtjvxfl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcpintg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiwkwtn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dgynqvzv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dshcggfj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cyemfjgm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzlmyhz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvbnizx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2shiezuzl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfkcgca.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khcxibcf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2liquizuc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ofukqtpz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiwpeuc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2krkakmta.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxsstuj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2knixvhww.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvzniev.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiseqlx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzpcfzb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pertparo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oriwdkxz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ewntfnpz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbryndem.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhcxsaj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbahdmi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfcnlcr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwhjtzb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpxksil.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeehqfwx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuxipvs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwmczip.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bksjymlc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2refarafd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sudnmzsl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjvumey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uabdkpuj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkwitca.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhwjnlt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbmntlb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cczrfedb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2scbntwho.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jeppqxie.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2obprltos.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2opecoqjv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2quxqpyti.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hwolacrv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2imkjhlns.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnmfgvf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvifblk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmymnsh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvgnghj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkdhvdk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvfchqe.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qccecazg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2umxuvsvy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ersxdjwo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wffekuyw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvcyrpg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dksvzlja.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cojabsqz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnadkpj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2midsqsfk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwbhlxv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yktebgnb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2glufvdsa.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzcboey.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqghony.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2phwhqbxq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iricbekr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zprqkknc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsjbmyf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhudnlpg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2miatptzq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxanasp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsalhqv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2siygnvsw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2huyltsil.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2egbnmzvr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfqibxs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjyajmr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxvtctl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2khblnmfa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hxozuwcy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcmfezk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjhjwqv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwozqqw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2appmlrus.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnduaqkv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjzuixj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tskrsmuw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpkldpt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhenxnao.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2knqbjaxn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlavadmi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsalwfe.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkbyirr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2genzsmxi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjryuogz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2afndixzw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jaelfbmt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ultixbpu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxuadae.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2njrtczqq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2edbdagyk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmmtwfx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtpglds.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imntsnaj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2icyyryld.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrvimgs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxxgmcl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnssoer.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqhiwym.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhbzrpl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2druefctr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2flcofcvh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cypmnmbg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvinkjy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjucjdw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2itgozncl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2llzywvho.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mcszuoau.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiyxtxy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pomwywnf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfpsgas.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aickriid.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvfgfay.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2psnxjjkm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvxkprv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyjoynn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxohqmlg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxwvogy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhimdabt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vesxtyal.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2harbyspp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuujbvsp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyezdxg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqbmkrw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kzspsgbh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbuonmq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jgebzcdw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhpqlxd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhtcefk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2otqvjant.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzmynvn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjzcktc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sitetueo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2guefmanj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqdtruv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijydomxa.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiwqmzo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yslfjvlt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xixtlyrf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kqruzyvz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nbncndbh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2omlaycec.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlerxea.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2csyxjifn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsrmnyq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbntvfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaxgxug.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lnekalhe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzqobby.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmhthkk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyfnmpd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlvmdyz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkywmvo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkzszsc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2frvulpif.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdyiqlu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxumtbpn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ququcktm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrprzzu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhmaimx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdzumnw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoijxck.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiuchaf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ambekolm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdyegys.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsxcbkf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2keyyomju.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhweabt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cozofdzd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rfegtytv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lobkcyru.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2depdvhbl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hthmvjui.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bnekqyui.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvuzydb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2oqprqfdx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhwnnpo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bagdnmtu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mspbupls.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjdhmpj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kavjtouc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fudfvwjg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtgfrcy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgwanel.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkwebdx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cipycdxl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlgghdh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwtteez.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfxgaaw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcdjwkn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2obffwchm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2attczgog.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrgicyj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzvmffx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iklmqsih.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2eboknqty.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyqzsky.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgcdtih.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2iijvsjos.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxxxzia.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgwklxw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmmvelj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhvqier.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfoiuoh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nytjjuuo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oatnaavx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdddhhgd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnwuvqj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrgzymc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2svccwmdm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrchflq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxgftqg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnovwibw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ddabcnef.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxhezwa.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2apmvgcow.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2oijnphza.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jilihods.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2aopfypsc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fsupyoub.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxnovsg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qxttontt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqxrsmh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrnlynj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqoziom.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2megrhjjh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqvpmll.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiplrun.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsaamug.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlisdqh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbutdxyz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxclhhl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhpqgbs.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzevqqf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tckckttv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwxsroj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtwzhon.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqybihf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzyckoy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iuckubjx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmsrvpi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzmdbaw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldowqpup.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2digimvjh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2czrgjsug.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlgdsdq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szrsgjns.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbwxiat.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2aezdpffc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoffwhf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dboprayo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqkwbvi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzfjluc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqfheyq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uypcoacm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eiipeeop.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmhiitg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2inqyhsgi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2smzwexfb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnqvidc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcvttwp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2klpjnjxz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ethgcfyp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrioiih.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkzthrj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jetqpxjh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbaismw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvpttvd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqstsew.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xolglmjt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpdtcob.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gnidbvep.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxecioyk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoeyrlm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwxhtml.html


<!-- 参考信息 -->