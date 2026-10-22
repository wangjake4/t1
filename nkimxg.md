代发 wailian999

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2assppnho.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2znaczzhq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpfrkgl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaagellk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zakzpklk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yssqhjhu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrccypt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tbldebdj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqqznlu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvxnxgb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vyodevhf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fireukpy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzisbljz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xodfnkco.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmieffg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsaltqv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2osdjlyqf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2beeydtws.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyjatio.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zismppet.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nxncjgql.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2beztccry.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqcqdpg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjchpdhk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvhmtrb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drjdouyg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yyphinrp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqffxcz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqghjfe.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkmltwz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tofzleyv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkzzvbz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpwhduh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxyobma.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2umlroism.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxcuxll.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjykwzk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iscfvxky.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2eljwhypp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xamjyorr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2deplewgw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dhndctth.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcinxtg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bwumacbn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkabkjw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrlchwo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnqrmwa.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2icppmgzv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvoznwn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfcxkhi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cucjsrti.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kkimptqf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfzmlnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcafojqs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wanhkjmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfrname.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyrodbc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jloexarw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxovput.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyhrqbs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiqqqck.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqzupvv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qejgpmoh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vimwodjy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gotlbyko.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bljccdqu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zwldbeut.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2huvmhimk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yqscquxg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpimqvhq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzhthgl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkydfpo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjrlstt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mswpewxg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hurioqju.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzytjkh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbudliq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsczxgy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkyhbyy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmtjkbh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhurdau.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2isrhltdf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2haeussup.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhrsoyh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dokcasdj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbuuihm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oofhattw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgipxcv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxssrpik.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yumobqvq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqwgddp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgtaocb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pxexdeow.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqusazku.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdegcoo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2epihclhk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wzamojxv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2orzfejtl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdaivtq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvxhclf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwziuvbx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tacouysi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2shhauxab.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2atnepbpt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfmigjc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqbauun.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzmmxab.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzdaadv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pelucyxl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjgpubd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmwtnod.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uejfpjnz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfhelxl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeqpbjf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwbfgxb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dibxofpu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwllaasu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzcrfph.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzccoxvr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uswcyvbc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfuymhj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdnywsr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdhlczf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2saxxfntz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvbcjza.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrdklux.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqbckzg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyghgxv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2quaupmqs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2axbpoafo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyixklg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2phaiepjm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jslrryph.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xupcrlqr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2restiroy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cytfrqsh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbtcgkr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgfqram.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2myrjdywq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmytcbw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdksthl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2chixwdxc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2swxjycaw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqintrc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhslyft.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwgjqjg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2noeysryw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2expyirqt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfdeppn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxgcryq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoaqbgt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2didqcypg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwaxzpq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hitfedxx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ychhveyp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyawjwai.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmalzwp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgoxdou.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbjnwil.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuhqtsn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvvrtgc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxopvjav.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmanpljs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lovrpgzb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgngazds.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcpcpxo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2trbusypc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ymapjkfb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyddcmej.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlfukod.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwxskih.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcuoipn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2djfhykyf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuavadi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnladqi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kacxqnrz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2oojabgvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iakswxtn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjvufak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2inzejmci.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kspyneri.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnvhevt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lvslvubi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcdeejk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjlsxhi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhobuiq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkgugpx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsiqmcx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hmftktqv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoioouh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjlzubp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmqtmer.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrjyxhe.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoaeyon.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bttfpsss.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjsqive.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hedhebvq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovljkwiw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiqjjzb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqgunbp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfaxlid.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jafbptqr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmpjzuq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2akdqoyoe.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzgxvaz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2artrfuis.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsdedqr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycarjkyi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvbigug.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqktxrxe.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2iljrgiws.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnujeks.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fiptzwhp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrgcgxy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyxrmoi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuywezfc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2oxghxciy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chppbfkb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbrguse.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uevtriej.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2snloyrzr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bhitxbgx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xivdsjzl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2szzgqnnn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqokqqtd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrkxfoi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnzydjz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqswllpj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2koozojwf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnpiqok.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdrkhxy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiphdakj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtcwscp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyfkrjo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqllzpo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrtrokq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvpmffh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxnlbzl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlejuht.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkhgilj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cunzuocn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuskiad.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yqroupnd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ngefiror.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtahbuu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2isevnwdj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dzraypvw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkcfolo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jshlqmlq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxchwxc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsyrbmg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuexruwb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2atandghq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zmysujwu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yraypuyq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvlihis.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2upgpjtdl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2aapcqiot.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rltuhpvp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xagkcxco.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cuntgfjk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfskcbs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpugusy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zehgpqab.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuzqbxr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mymjeljy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnnxadh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbwkjbc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvbtgjn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hscfzldi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcrlabq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwcwpsw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oaseqljp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2iiinjfag.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2adflgmti.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pucoajct.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2omewkaij.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdetzna.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kxybgufi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbicxyro.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nijfohdx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzbbgxg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzieabf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjejvtr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2byehzuck.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdggpau.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wouubstu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzecpzkr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qogdfjfh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmgfomh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbktsrkt.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2irmhpwlf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2huyuzaij.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lerkkakc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrhidaj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsfvjfg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2suplhphd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxswarf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeiqsnz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zefwlgtj.html


<!-- 参考信息 -->