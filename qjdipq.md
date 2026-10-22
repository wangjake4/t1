代发 wailian999

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rbawvksf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2beqtxvoi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2odqxrdys.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbaevpz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiqpewa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkofgbf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2prbnwxol.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hicwcian.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbadgno.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2aupbpwvg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2porvunxc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbobksm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gftgzcjp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2omkvgclr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jaholrqr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2polzhsbx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtvfgzb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lolircdr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yaddopzc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdicuanu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qpckpqma.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2apnzowpg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrfwlwn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uanrkhfv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuafida.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aadqrmxa.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpyylol.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2huqkforl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tigijevc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrqkugn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbijlja.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dedctuhb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rndchzvq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vpovihcq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xunzumbe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzjhftr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eilkrvgw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsbjnjz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2csebqvay.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2peudknkg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bscdksdn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxqyvvt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vavlxpuc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmyvqtr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpbjtrm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaaocbi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2drngkfhu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwigmyx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmcpdzh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxyjzkb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrhjlzz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pernvget.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrzobal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjnesmr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsickiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvegresg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjzkvfz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kemwkkfz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2avnkfgjf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gkggjgtl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdgiwne.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbapbvey.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpyjjbg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiukmfb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfmhekj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrjqnjz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2riigmpkz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjiuyux.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rxopdxwi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2znfrzcqy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfuwcln.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzqfudf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qigvbfej.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iebcfwli.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwiceme.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vakyecbm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbgspou.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2clcqlqqg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2navqzgxn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrixntay.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2otofaszi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcafzbn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2awmrchmb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2htiniyrj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgzzerb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcumfia.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yhexaolv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eehferdl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2osquqjvf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jocuxkss.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2znzaunia.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2twqzfrzk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bemhwljs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2elqdngjb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhjemwe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2avnnmobs.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gskspjnh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2libaeugt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jedtfmmd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vpazrmzj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhqzycd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ublwdwle.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqzpann.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlhnvba.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjtecns.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnimlsnn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvaknhh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsmyhyi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yltkuthj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpycvgvz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vtanrbve.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhrlpvq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qxashmye.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mephxcwz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ykibwkvm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdyogrt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kugkflxi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjywsxs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmodsqn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hvipblyq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvkrfba.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrxipru.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2spmzcnws.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nctkkqea.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxxtdbu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uaenmmqo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeymocm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2czvqodpj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eglzmqux.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbeafiu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvfmozb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrskqlvf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2izqaamgh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2frkxwlhf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uofynerl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpghxfi.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2koeurqbk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjnibwd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mboazlhs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiklrvzl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vftspjwy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdljlfvm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyromlt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjmpssg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsydaom.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idbhhppe.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mqawcuim.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmglzjuz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlkkuxd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kropblqh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqupqvn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkikrtfx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqthywhb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxvxxwg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfhbxpw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdhefgj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxcgoce.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcozhvn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuqsgfp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rozrsxak.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbmlqdd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2npgnmugs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoucydro.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeiclqq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nocdyyia.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlxulrt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxleoxw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvitaqg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2firzlzgu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lchndnoy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qakyztqp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjiqzqg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ywomykoa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qkucnfab.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcohubg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfpcisp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjzjpna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oembeskw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhgivyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrxsanc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2veqcumme.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhfkjdo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdrysfa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kztxllcw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqbxomf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhrkixl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzsuufm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdlvzrl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2reqxjzgz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvgyvkl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mxebljdx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtghgrit.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qymfbjlz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cerzuyme.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbtpxxy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlzfkwz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsfingl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpzlfcx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpbibkq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2opjymbik.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bhimakxi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smnolgsy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kudbxddu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeohjuvx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdsgpkr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fydomavn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeopfiy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2okmvvsyl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgxqzje.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhckiee.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwqcxnx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjhqjpv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xetiljlg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkbtxfq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tomastkt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gquwvixy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrpfitm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtojqtm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qobgfrsc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrjqwtd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxwgtyc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbydefs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqrsytp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nndwohha.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzpbxxz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwevham.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsaxdsu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rondhlbj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfupnuv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpfrzlg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2axjdbtxr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sohzlhnm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xukncxao.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdknvyg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2illtsqmc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pawjmnci.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtgkvzp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnewhbj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbimsgx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwchgakm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lbabskjg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjotazk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dezpuzss.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxnmdnw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzatnzy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bitqzimt.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cyueqaso.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2axdfzzwm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmjcppb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcjokhh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tpygfctk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2owbwykom.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2epqkvkqn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2barfyalo.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoelnyp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2plfqinpw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2leciqoyl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnkfyvg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2idevkzos.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdyqoer.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zrztntsw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2offglyjb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2euwlzrzd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aitzdwij.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxvfagy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxudknme.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gaadblsb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbkvxmp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfhdpjz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoembod.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnezeul.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzihilw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyuzezl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nridabib.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpfgeqd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teneoxsl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcbggnk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrpxjyu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbylnqg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aabpexix.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qgltomxt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2stxxevdy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2batdljuf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeblkjs.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zdswsfzp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmylxpq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfavmird.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzggzgtu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qguwkhro.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yejbbxml.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uacolmib.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbifqgn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqotkujn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkrybia.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2njcqziye.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmumdupv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwbaenn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxygfpjo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmvhzpl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jknvsnkz.html


<!-- 参考信息 -->