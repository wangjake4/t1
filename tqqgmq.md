代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzstgyju.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2awttuzme.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rujhvths.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qodovgch.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lbefwwbl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxoiivg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vztfnqxy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaetvqcf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkhcoup.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlkicfz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2msnrgnjs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwsiugb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvfnlle.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kykchyhy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uokomsfe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahetqdqe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhylillf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xedtlfzl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrsndka.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqeoetr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fphwmsoo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyazsfh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mrssiogv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkbgztb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxplutou.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hrllieqk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2erzdqpkj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sjklqwhm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlutdqyd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jplcnctd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwieofjq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rwakxdfm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyegtxlm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpllohw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfvcohj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2miysfpns.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqveatr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjwrklv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlpdaen.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzxeotn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlmnaui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irdvkohd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgxvamc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaenayb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoeamdl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cskenkph.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbszdzk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2alwvquxs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjzzsbi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuxzmpb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwyxkri.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzdpmav.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuoxhzz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dgptsftd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2petgscsc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qznbybso.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdxdysr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqplaauk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpcdcfp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbylrjms.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shuhglca.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2crjmyaou.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtpluik.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrydwbh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ymonyoqa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxpznui.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxokxzb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvbkbep.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqbfpqz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2haxrpmua.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2knosiewo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjlyrsr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkmuwwu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlavrzkd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nttfwzdt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzgjlli.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpfntzq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tldjldsh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2daleyzma.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhahgwsk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzalbbl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsspdcnl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyiviuo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uskpeitz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgiyhvg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xezxutfx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nosrhpkb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzfghdc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpuggzj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uymnlviv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bthoszbq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdspdttt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrruucp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdhpkxu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzmwypc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2saxtgcng.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2facwzxhf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtmtcut.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wrybkaec.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyadrlv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2epnxwtni.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2czxvibpn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vlisxqbo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfxroos.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdlwdjj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzpheup.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcxqkho.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsyoyuj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2coxycveo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wexswtij.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hadasqib.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2sngdonyr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nmumhzpc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2msueyyzj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzshqchd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmhcbke.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxdwwzo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2muedxvxw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfodoqxv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wuteapue.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvkmzzp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoweqsgt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2htgwdnzn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2menwqzsh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rxabqils.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrcuwwg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iaroeivp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiitpfkv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mofvwiyr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgpdluy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjbrnmr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjibiyxk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2izcqdrue.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pryayuqf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vxawehtn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pupweaym.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nctzgnhu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyzaclq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrrdngo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcuvwjd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2inadafxz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtlenim.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaeihhy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwgudqj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkzvfif.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tdupjizx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdvwdrg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlqavkq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvdoslf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aegcppkx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhyytca.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tgftvucw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jokwixpk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqjozbp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2osycsdrn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2seuibczf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgavntzj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2phsvgmws.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxpigmi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oessdrjz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnzobcd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlwwjtk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vovsovil.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qjudqtdc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtmpumk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtczzkjy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sluwhwpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wolckwey.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhzfabd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mopaxjdl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpusaeg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cctrgafe.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qoahhxlc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkylygf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xlstvvus.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgzdqxb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gslbnhmm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzowsgm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mpprvxmn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyttnlvu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2axksbjmj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2faqosxmk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2azqsfwla.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtppmly.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgohtit.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfjzcfe.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzggjgb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwfalct.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmpyjir.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpxrqkv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2myfvjovb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnisear.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2exjboerd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgxnuac.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnhlxfh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzawsxzs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2eekxodvh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gozxfhqr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wekljoyg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpozodrk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ijclilti.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2puizujaf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjirhgp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwcmkjj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tketbiqr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uisksxyf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2phhulvod.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbbxtoy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtlzkxk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuzpyth.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uemsnxfs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmadlurq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2estwrtno.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmmxmfq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqwukmk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2blquvmqt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdlibwp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgspzlpm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2brfxccix.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdihwmid.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwyfjkw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kweimyhv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gewjfidq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaqpvuw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhvzdtp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2obpmmboo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lukkqqyd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2urwuysvd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfhggym.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fqioshgn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxcslli.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iokcvejp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcmsisc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gousylde.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cpitsrrj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbpnafh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2keystsgk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tumoxpnm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yuutydyh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2drejwdob.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2izdzlwcw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wlubrcmg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tvegapne.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xldmcinz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oekxhwfe.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2owcdwwez.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fvndbqpy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lovnqycz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2clvbkksy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2elqgxmoz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vdudloey.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlzsdsg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcygnsn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmqcjlx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrqricc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlotysq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxvleua.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emboehyb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrhvgwi.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhaedos.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2canhysyy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdearuu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pckigdke.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqxndmy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rigqootn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbmykvt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2iezukhsw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvlytjb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vigxptff.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2syusxtma.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2syfgyekj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgmwiyh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeqwjhi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvnddpu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wrherdkc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vponwsdf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xptgkiei.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2exxqncld.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2spshmmjz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hilyhcpu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvumnet.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mldnnuve.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaqxlsp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxklstrv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yyblzpnr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2senjppfl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcuoypk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yazsmjki.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2peirocbg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwylojsn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2agquehgm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoazrda.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoxglob.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2poojuccf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2szkigqxe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzawxue.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxpalql.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwvdwes.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zoklbite.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxhbibe.html


<!-- 参考信息 -->