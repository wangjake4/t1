代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbgwnvv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzqfjox.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfnomps.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vifyzlxu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzqqmlt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwyqopw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cchvqanm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqwmbec.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyzifkf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgjibbt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ugupdcsp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkflfhar.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2znjxcdzp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzvcbll.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stdcddcw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2imzpbsjk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvryptq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxlmtnv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnpnieo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2isoetggv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmlawpp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fesgvzsr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwpmyzg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xpulusei.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qybdcxme.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvotzst.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkxgfta.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwcxvnh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlklksvc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2smtnqdxe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2trhdqkff.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrmsmds.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmeclda.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2juwjnltj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehebyjdr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vgueubmn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2orbhyzdr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsicnvh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmcvpjx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzkkprh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vpniyldu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuaaauu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiojfsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmscqmn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2shwmrxlg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2usuktrqb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmedhufu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2sertjvsl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqgsyty.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyquvlf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwwabkw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrzfhxy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxnaugd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qzokjcuf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrqmmeu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2llqtetiy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qutatwvx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yprmrhsn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyqfgrd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2darecbri.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwgalrq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnkuvyk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhnygns.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cumiafnm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2iumzwzua.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2aefsxgai.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpjtclc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yijznblv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbojune.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjzxdaa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rupulsro.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrsgtsj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaglyea.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcreuay.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gpctgyjp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoumbsg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbsonss.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sjefhvvj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uixdffzz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmfcbup.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvvpzzl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxczbxdv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pspjhpbg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhybuxrf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvlxtrz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kifwvzjy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxjooiw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tiojjjex.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xsusvqkv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sieepocm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2knqnxxae.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibonahme.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xcskqpyz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jffxkzcr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvaadpm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoxfova.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpffool.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjhatue.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxcecdd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kactqkok.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzyrdfz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2evzeilcs.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmnrhvr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwyyknc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aqacodtn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ismwefmx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoglcrl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoqlold.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2coclsjcx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2anqnsahw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zioauqnh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2znugcjtg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jpytezzn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hygcjdrm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zabzlrlz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ygphkigi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmqeizs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2umvpxsuv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2actsupzl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcahnou.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbomjap.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgpxcrd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2blsoqoyh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqrzgfj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvsnumu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bohmghkx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqbdrcl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqibuxa.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoeuzla.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbyspts.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgpkycd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqvakev.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsikkgh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmntyng.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2afvxqiko.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xntpmakm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yrswildu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntifjnvv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2njalhxls.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jobqeqjc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wavjcvfb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdrvbln.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrxhqch.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysioehov.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbngxvo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dumdtsor.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2swepxpld.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiupdfu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xrksfctu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wavnyvcz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xejfrdij.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vrctfnif.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwvmwxl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2umtuyinn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqazcakz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdikneb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsawvvn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2plutqvne.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvletyp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yynqxawh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2afcikhyd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmjvgyj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2riktqiwc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnsppyb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nimcpvhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsezbyd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shvdqzyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wafacrpg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2exdwawbh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2khnkhkke.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mfupfxgv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2flyyikzs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ugltfaci.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmisifb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2czghpimw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqggkda.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvcieuu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zugtnjwg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2samprvtj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjljikkc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqgzvrc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoitlhud.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iohbeosf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2minysdnw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrfhtcc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2eohonron.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qktvhqbu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wopszplr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2euuphnkv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgfwykw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmuctxd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lddnqxfj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kccmpout.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoyxhqx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lutucrea.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzvsucf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuxcghp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmnjuql.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wgazxkgh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bncbnnvt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2owngcjui.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2utfzadwy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wcezhyfu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2trrdycnv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2drrmovta.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vukbahib.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqrdumm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvrrmdd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyobbhj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2axltsegf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2olhwiqcf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqzkeom.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oagnclhe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjxuwpy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qltmkjff.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqofztz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mpesasgu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nohimanv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkayhst.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsefnvl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vfffsecy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsdgnrr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkgkmuu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrvccqt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sutibyck.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2llqswwxo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pwogpauh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwenoodc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqvsihi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kffcuime.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbbbroc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvmiazv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cntvbgel.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gonkwrwz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yxubrcky.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2skqbzsii.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvazkaoq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2voatcrwd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvmniyg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mndvifys.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2akajgwsy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwcvmez.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zpufieqp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2poxusamo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aifxaqww.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzdqqxy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2snteqrek.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiqjppo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hodlqcti.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ayipowzc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pudcpwqz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhvsgav.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rjodnmlv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmjewcz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vyehwdoi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fusktprk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xnifckol.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbentogd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmfnfcw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkjsmbl.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkztpru.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2chsmwbjb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoykzak.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaialcns.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iuctxxpm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhoowxq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvnvhsd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyucmry.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsmhzzm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoorjta.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2raujyzck.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ranbtkhj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdvnnuu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2arrajftz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bmawmdys.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiyfcxc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bkujvaqx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzsrbdj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyxgexq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmdbiuz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtcgtry.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2roahetsg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2msgxxerd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lortzfap.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnoikze.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaqunnm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2iucupbsi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoxprwt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tilytche.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2scchttis.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbdihih.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2unteajpe.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wgingizy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fernyfko.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ighuleqr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qojmroqm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwxbqzi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sceusyfg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2olakjfpb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2afksvply.html


<!-- 参考信息 -->