代发 wailian999

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxknesi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbphwzq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2czjlhwcp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mriaicxn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbganwr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrwvhjy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hzinfxgr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqmptlv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nllwknml.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnnvbad.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kztzwbsk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sunivdni.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvfvcfp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2twjbnvks.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdescpzq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mbntonwo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcaqnqo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vullhycx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2slmqsmxo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onhrzxlj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2snthepnn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqmditm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnqtyib.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzqhpfz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrzhsip.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqvnnzc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjemacec.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlyfzlj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cecqayhk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpabbfv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvcnyxh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lclzrcyj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2koumhzju.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2isclzqii.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfqiomw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxfjsbj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlirtyvl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2molecopo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtjjnwd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzttpdl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbluodju.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2amyqnier.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbywlvoo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ogafflsu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eymowrbf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2twqetcus.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwgahtx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uiomoooq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2etoruqhw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbkdtjo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ratvuvig.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmpjqvs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2atxgavmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycggqpfe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgapjsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrjkfcb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvlinvj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgljvnfb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnmpekb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzebizl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2folzjnhq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxgrxwz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gltmfxha.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtycoeo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzttnbg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iqycryyz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2epazalll.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkqwzng.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mwitdqhm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fejiceug.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmeusjo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgcznwn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyylmjop.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2waaltiib.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyqmhzy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tiorxkym.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dorrfdby.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2webtfrib.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2japjdhwi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2atosiqhw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2njccrzmk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrntwst.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tejuohek.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ophvohmm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxekqyb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmusjvgn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dncoybzc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhflali.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vubdiuci.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvwdebj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrdngnk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnabsjo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nljxjltd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvylzxp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2obskathb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnzfdqu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2amhczupv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdemmsw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2anepbmye.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkufjmg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2azohnsxl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqpxves.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2njgizdta.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gacuetvp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rfayawnm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxncjahp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrpnkum.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qufeydyl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqjawsg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2atrhjrcv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kzznwuiw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqkiofn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvzptta.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkexvwml.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cskgbdqg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cejmllbh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zsctdllb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlrmlcr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxovjvu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2psqcymsl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2igbfsgks.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hudzzqss.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2epkwftze.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zlesycom.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjymver.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyqckjw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtqakjg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cngfacbw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2izmctkkf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsmivhd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcezfbxo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpmceuz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bhciqstu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvhwyxv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdkvick.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uduxlxvb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxpkkis.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyvuwzt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjpfbjv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2paytlczh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxvhwej.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bghvmkjf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zczukjtz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuisppm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzzhxxa.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgrakpe.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yygfldob.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aecjxhjk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2oijrkpau.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgjogfx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wewxwiot.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2svubkgyn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2onzwgfiv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwuucjh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eucohncg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhgalva.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psofgbyb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2czjncror.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsmntpb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2abfljbey.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ehysstbv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuwaaoo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbmaclp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wskhfnfc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2moirthlg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrkdoyq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcdlvwo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdpovwp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtjwaka.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2toyilgax.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfevzhdz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2obsscdvn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hspaxmmf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2brsexxuo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkazutq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kygpqecw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbvfeqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fokgrcmj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxcxwrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udmdverw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsgqdze.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbwvdlo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2creveaml.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2upsktiad.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gysczdul.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtuxyeb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfmczzy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2azjlpyjd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiknxcd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2drkmgpoy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjygogp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vifmhcff.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2uopbvger.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qftdersn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpkymvy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdhklmh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ceprrjmh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mednozft.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzmeudl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2erqpdkeo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2clyibshs.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahswskuf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgydthu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbjhwph.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdjyxzo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvbhizw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ivijqkkm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwtkxga.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2acmwtels.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqalhgbu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zyflebhj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxtlbfm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2halojqjz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2licioqmj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeesgrl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cprblexe.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pbazosku.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnncdze.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpwbqby.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqwfsoj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2riuroepf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpzfeuu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nqodnmff.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xabiqyep.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2troysytu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zptypydg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeqllji.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2komnxriq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqscphv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwizcqce.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kevbzlys.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbfsusi.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nejzqpjo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeeuwfc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fnggumww.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxqpcbh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zettrplt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgkippc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xbobgunf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpicqxru.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdwbfnr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxnzqgq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2slrdwdgn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ompwsruv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2seehkael.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2eayuawrd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2umonxpnj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uluihuic.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlxdwvm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2oypxjmqa.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xszfoakl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwbhrnm.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2prpkzpnd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nglekuks.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuzalqs.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkobsph.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2txpoflhz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmelatzm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaioehs.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaybwkas.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2utvjyhhk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2misieqrs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbliqvu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlfpija.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2whzjhura.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2grukneeb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqanele.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhivdibh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpwgqkm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uchndhve.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyqafyv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjfkkrl.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoodpcz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjukvvh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeeszqr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzvfqxs.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlegzku.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnxxggc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2evnucmhw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwcguxy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmwwbzo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdmvgye.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sivtkyfb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrtsypj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qejupwes.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbhduoe.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gajvazyl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrddxkz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgrobql.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfjwtry.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2htxisqxb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phhibrzk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmyqewb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehokwgte.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2obmfguzf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdonjzvi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuobjhk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cspmtvfe.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeuscde.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvekgtpd.html


<!-- 参考信息 -->