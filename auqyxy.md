代发 wailian999

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dnghpzol.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpzigux.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uurweipt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlzwmxy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqaqnlv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2isjlcwhv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2anrmcemk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgeqmoj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnwawui.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rllzewoo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfwwlpd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckddcdha.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcanpljm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpszvdci.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbhyluv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iaujzzmo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpyfhgp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtpdzxm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bnckhpsm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfivjsy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaopswi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyaxbio.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ctytkcat.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jieplfkm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ummqhuqs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cphquydc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnxnzen.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfczatb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwrufmw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hswdzepo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcahykps.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wioszuhp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxhwogi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vrumpaej.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bndhigcd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2frwtotvj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qghnosrp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2efcfrboq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nghmvsmj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgwpnvz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxynolcx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pphumees.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnlqqhr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2sybgcnkb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktojecml.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzuyrvj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyevaipu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2udukwmsl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpmsvoy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ameiihfn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nimmnguw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2okfnaedf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfnlfax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrwnygu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmbpnfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plfkrwio.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzdflia.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecphxpye.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjxuoqp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tuokoltc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sosnbgwo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2irweqhhp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wqadoixp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ixveclgi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2snwjvkdm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2juubesiq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpphjuj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgqsaac.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfkcisu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsqzzyn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2avqzssff.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjechpxm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbelmqel.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrhkbsm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hglscyzz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfctpxlx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cyukwfpx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymecvgcc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzvrhsv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2boahxfao.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqrqgyx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpdzzxx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2byqrdkpi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hulbpvsa.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbqwgmi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2shyertse.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hlicupjr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzdcayh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqjthni.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrnkira.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2keeaksim.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwpacqx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2beylawtr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyusfmii.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2shtefkan.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2swldjiya.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2npabrgcq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiahzvoo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lxehsuas.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrlnswf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjbwhjq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrkoutu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2blqypfdo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2upltxgvv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fehaerqt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lebnkken.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qkufocna.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gecjvttp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uoraxrya.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvqtokp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eebpajvq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnbsgfb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cwalwwan.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhqhuxr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jjllavcb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2szvhmscc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tknjazpz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjysmvlf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtzoarn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ojclwboo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjhccxf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fburtips.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmkdksv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2etvwxhkv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzagwnc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiupalx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdzklem.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxoiknr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fsenqmbe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmtxabv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vypxrqwp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wiatislv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmclwze.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mljtrpey.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjvvwrb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vdctgjaz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2epzhqsuq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsoeqwa.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vokylmmi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqodhje.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvpwhrl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2spuunwyq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwtgfid.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzraacp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yheholhi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vskunjow.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qaggyinp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeybdviv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cistpimy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ashmyjmc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgfmptp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iafvvvlk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abfabeeq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxjudfi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmilzqhw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaixvbm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgstzuas.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zrusbafs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aupykrkn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzymkycz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdfnhby.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbtvjyc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnauhrz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2prnqjiuw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pljrpimk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2miwkuriz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjolaxi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ljatqxcb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqymluh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2buxdryju.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwuezmy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jklwihsg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bmudmzop.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnqeebd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiguuvk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fudnwejb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhmemoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjogaict.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqiwxjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2caabprlf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkkagpy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcvmjdt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rclawtlf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2agfhzpio.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2idspvduv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktputozg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcxcugf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gxedftam.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sawdaudz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwfpnow.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jslfkpnn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnmwanm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvgdiri.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbivbgv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2upqandfh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeyjpnf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2veubunlo.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfeexxk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzofymi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbxdwxl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2liqnkver.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyacnnv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmyibob.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuqkksn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzgojcy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxauqlee.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfbhife.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2chimeyvd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvkashf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqvnrhz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcimcau.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtghassa.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aiofhrqe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pibiwspv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vclweuql.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkrldnd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pczjaiim.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqiouzc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rykraccu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhslkpje.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfrwwua.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjlhbtf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2olmahvlr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsgafjq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmwndkc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2unotinzz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdxuxkt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rohayxwk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jfinwkqc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvvtwtd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mxofzauu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxfhknh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqstnmz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsnvnwv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dzziafrr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2blocjylc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwiajso.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcnlcxv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcsnurq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmkjpwc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vntefwat.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzwuqne.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qitouamk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjtwvdq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jwznfckf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jutlxcdj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvkcjof.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsdpqxx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnuezpg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnaehhc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeascev.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbplmch.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fbravpjh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dbclctcn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bczfzagj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwhtewl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hsawjpfp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtkmjhx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeouxfj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcdrryj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmswwxs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2khwzvjmj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cooqjvsx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkplanf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vidadrcy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhryujfc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qazmlvvb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtpqhrk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhwwuwp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quaejzep.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2npcvatth.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbuadrx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2siqivkpn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2awlzioso.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2syddpkhy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdaofos.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgsjvey.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbqykjq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2advybpxe.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syplexwq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvlvqxt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqhxhxm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wflkjofp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpjjliw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdnxvsv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhavnoi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrjxxte.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnqvsbd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiefhfe.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvkrqlz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcpemds.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxypuwy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvyzbgf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tojghvjf.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwwozdd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbymbog.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yoedaqqe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmagxzo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gajwnpbr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqpbkby.html


<!-- 参考信息 -->