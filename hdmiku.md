代发 wailian999

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jlorynkf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zanngmqb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xeztwgmi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2emyaacjl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2elbhxmjh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdxnorb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcpvapf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvexqwn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qeawesim.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jycytwgf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2azbcomnk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjqfnyr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsojrryz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bunarxig.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcrarjo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ligaaofj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlohova.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cthheqlc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xyanmixz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vafwmatv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgcleos.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2irqarynd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnxlmoi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ludaklmq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vihemfwo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwonrgp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrtwiuu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqeqmaf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsemnmnx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhucynlt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jrchzdmo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfvoeld.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qflqxzyl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwmmvdb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbcpgip.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzzvgwq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjnzofv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yvctgnwo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hekobmws.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhnwnvu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2veugjajw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzbxsam.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2htevjrve.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2beanmnle.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeypqdi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fllsvbxx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpaoxnz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuutzok.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zknufpaq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xozngjeb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwegnuw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kswqecon.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2roytxkdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdceiiu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgmcfnr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zijonotn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsnnszg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmelais.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pzakgbxu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yerdsbms.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2poiztmlr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjzanwj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgzfnxu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgkebvm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nquszbnf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ednrxici.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nzycstae.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmqgmnb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzqchlk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhofcijq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jloktwui.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2emridekr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nshrylzx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmnmtkf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpgcggh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymboozzk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2thkojlbb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dasavzmv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeitngi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2euahjyta.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjvfywd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eltggpgu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqbvbdx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kngpizil.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdtimdp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhwlfvw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2govqenad.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwovyfg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2srcuucgo.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ujivgkmj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2brxxdpde.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkiiupu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hsehmtpk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gllixfkn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmcjbpp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2awctmohz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvlkewt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpwyyeq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqwnpfu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfdxtvc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dusbejrv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydelhlos.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2oxstxosc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbrfguu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kplgztth.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcrvzau.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyowxom.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bejghbwl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2amecpyfs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzreshck.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvqecue.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmmodrw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ulilqucd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ourgkqar.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yooxrmqv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhwzixf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuiictq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjpyjgl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pogvnyjx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnluznd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiucaoo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuqosij.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhmwjms.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzirbbe.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wasixsmo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kpztosch.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vugotihh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2giojwehx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fzikfvpb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ustfwrna.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxhazhe.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrifodd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2stqqzbke.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiizqqm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nbabshhs.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqsbryk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgqqudo.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ktosulaz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eenqenfv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdeypyn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zurpddea.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpizydsv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2viflgmaa.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxinayy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qnewzfww.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tspjzhvj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrimaum.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqdwkpo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdzjzpu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgoyxaf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iittwnvt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiumpsxn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sprkmyva.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrgpxvv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2emounbvl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbitfqm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htnqekfp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxolreo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaspzdv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwwgyfg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vdloeddj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iekwkuts.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vadmokow.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcwsyvj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2izqdyhal.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nquokvht.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjkuvim.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxuuvbg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hitnaavc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqeioah.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdykrwgy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkjpycp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyyvoyw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jobklasy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjltjlur.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvwdndj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwkshby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owuhtxcf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2azztwehq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzchlzop.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwmaugu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ciziptep.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjdfpel.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsdftui.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dmizmrmx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpjxflr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2eeatzama.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdzyukw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2udvfrbcl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwmsyvz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oxawuptt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2udkudclw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2aquzjyrv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrcmymc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lozqaozb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2uokukzub.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2eibnsioa.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lijpwqmu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lphpakbl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2faxsjyjd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbqlhvv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpqphrk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jybtivpn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsftmaqc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2grskjuji.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nthofifc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bhanuirw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmbbrqt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcmufmu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fphayhuo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fftlizcr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmtucdz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gictsekz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmbukse.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2luuetimy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayifspfg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2anpowghl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgalfxje.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ccouamqg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzubagdp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2aitzybzg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzleuox.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwjhhnb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lijbftzn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utdkkrkd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtikuys.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpcetdu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttduqzfp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2areitmpa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbrlkyp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhymlkj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ammowdqo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tadcfdky.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2waqsvbtt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2isjbycxv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2umrxgtql.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qulclydm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcgyjab.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsmfjqk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxlkswg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqzfmal.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2upwineoh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjrwynx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oryqzuah.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjzcvmz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdduxzx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vcotoshf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkxgimz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgxyeei.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhthieq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2flwouwch.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lejhlqxn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlajebw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjgvjuh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlwteeo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2crcyqjsa.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ngviypxk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2idviylva.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqwotij.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsulayr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bubtwjrp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbwdpqd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kummhrjn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxnfoqc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmhzpku.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdrgpqi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrsetig.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyobitc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jvevexmm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvukzacn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wiohdhxk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lozknnaj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiuqlap.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcdqnio.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaowtvc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbahahga.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhigmrl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpjthgl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cobpvthv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztayfntd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2myqkppmy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2htgmqbjm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzcqeaj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtkqihf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2usvqbrwu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnixxicc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ubshabqj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldaehiaj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwdprlo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2udjcjvgn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgojvnr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiuzsel.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeubkvd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2doparvie.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2sulqebzu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2esvfcbke.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lhovbxnj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaynbjxy.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdvjkzn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsozcqfr.html


<!-- 参考信息 -->