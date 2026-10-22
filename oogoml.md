代发 wailian999

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ewabkmaf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rumdhxvt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sbagqnqa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdyapvw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2behmjbng.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwawisk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xepfwnqz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsbmdbb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2equdxnuk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2aptnulff.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2elcuzywv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2unvtsexz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pojwdrve.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwtacye.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqmuyub.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2trhmhvda.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bniochbv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2akhgtdrq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsnanax.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfltmez.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzxtyxv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrvblff.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqwgljq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zomoadin.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wzagwdmr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbesyjr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzbhadq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbysmnl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fncslrvt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmrjeti.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhfzrvh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2veeieyeu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjygprs.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xjauwazw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtnhosk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dwajbikx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nddzvmvr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsruczr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsgzozz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jybdnoox.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcgccqg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxxjypo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnxeiqj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jrawdbcu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czenivsw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyjjjlt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdrjdbd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgupwvt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tffctrow.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2htuqyreu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xosblkrg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxizezc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aewzjltm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqoqrdb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzfpirc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpodubgi.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmdhkky.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfxnfku.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxocbvhz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hpafllty.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfmiznp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aougrbxj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kruaythk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kcigeyyv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xajcswmh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pekkgvys.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmospeg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoydxvm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdwenig.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqsjsls.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kgljrtjq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wudecspu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrhmbrz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqpcqpk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2knbzwwke.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qesezazz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2plnhcvpr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2elshqwcy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xewmvenq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyqacvj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzzwaff.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjpzzft.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmyocsl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeivbbwb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nuukumhi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcveaxun.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqebrum.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uivktnst.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbrggwx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuvkuir.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aomvmxrx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2oayveajq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrkzvgu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcwdlug.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zgelmakx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfydnjwy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2owrieidm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkawkvf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2afsymlqe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qitniwdp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnnzdtr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvogrld.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmtejsd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuryzdl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kobfovkg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbmhfdx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xafzoasw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfozhhrh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2npniwdmt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bugwzjrr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zlivlsve.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pziycgtr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqbposn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpcptrm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xurcqqtu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvjsbfd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbfbldq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhoatkl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhytlgo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjbwmpb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzejeuh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhvvplo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jddgwfqj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2igoarapq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvlxmtd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjnfgho.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2botldkbz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlmxvss.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhdrnez.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvairccl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gypprywf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2psjusmqf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlypaxc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgyomdw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pulllbpy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uxibdqme.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhfwtsb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2adaujilt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pekzhotw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjjtdlc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvwgllm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkkuaoy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoqfvyh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvrzoei.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wjobuawf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acrtdbxm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rklytlbc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnqefvv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2omzatidh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkluqtm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbxftgd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vecyfkxl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtiudku.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oavosept.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqsuxyh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrszohkr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imktlyau.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrxygtx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoblcwv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuahvus.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrajvxu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gotkfmqs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpursqqr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2exgtmvzj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nprqgrnx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fogzbhea.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2psmznjwz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2easivdvx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2waycsrfx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gefbzijn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsmhllm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhcuawc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyohsmt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrtgxty.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2opgbvnlw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qireilxo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lexoupul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snjbmkcf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xziigqas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzxzvrp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnjfasi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfshbdu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgvsttm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fohaskav.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2einzvatb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzlbgoq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2balqotps.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsyccmu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2opauqwop.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtnxakf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mlehiado.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjdsssz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2cprebtne.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2imouavio.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkxhgwr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfernlu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvadois.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vddjsufb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xavdncvj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsoieaa.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxdawte.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uupszqew.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2okmvtahh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vivkanzi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgonbgwm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlkrrdq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhgxpmh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zffwwzvb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2aylowjke.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxfwywn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2omvqfkce.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jowoyghd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eflhmlpv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyxoiit.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxqkdxe.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2chkcbero.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2uspgopch.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwbhqfi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzdfaaq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2madfikeq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2teumtqzr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbnzcrb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mjypkbga.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlkwjqh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcagaiyt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfogtik.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjfqlqe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhaoaan.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvhvjvt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkofbubi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tbulehol.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2klyxejhj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2swqyzzeu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2elgxmrsj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbgrzqa.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zundsyfe.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xobfkfph.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcmqisx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gjphnseu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdklaqqp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbnvdtc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdjxprt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxqftgt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrboink.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqvajax.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxaghzo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2comvqfie.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bckpofwa.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqabfalq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2chnwlwzs.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fofuqier.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgauefpe.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2thtctuju.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhyxugn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kuesxfxw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpyzzmr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmakfjz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnfezyu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sslxywxj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcivunv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wzotdznb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pysxgwty.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tsavhnob.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnxxjxo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2szvrdqrm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2iohrvxsh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zykvjbyj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhksyqd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hijhhdbp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nncjxefa.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2quqwbprh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jbymoqea.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oawzsozc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkuyvej.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oapbwomc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hosxkhnz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlztauj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pcescojg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmytpvo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orzjyepq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2muxpngbu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkivwjf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoqlmzf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2llqtovej.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2axuwjiho.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeaehki.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzmsrhv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqgdnyy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkvtsrl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxqwsyy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wouvqoqk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2doeerlcu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2duwuogpn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2urzqpmmh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmjhzah.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqbttkp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2elrqvmmi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdnatia.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvclote.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2grsuvlqz.html


<!-- 参考信息 -->