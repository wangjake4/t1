代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eppjasce.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcqtqdw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjmcyxk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmmxygz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvqevlz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2oftyolhk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jcontxwp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utdkxgom.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdfzuml.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2icttzlyl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvkghtx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acqijlpv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqbhsnk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytokfvfa.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orxrmkmb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlrvezh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwhoxuv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvygotnf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rftsemwh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dscqtzzx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cduhfyxq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqxogxw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2flixzpus.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvzjvdo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsuhqgb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nffnjalq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwbooax.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhkjjdg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2smxpasfk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vycbvpnc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxobgfwi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2trimgqpo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eliwnawc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tmesodgr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqnozse.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgajyna.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjbscyd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cumrcqwj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgpacyn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2prwilsic.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwivrwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdhdwfx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2atjwnfye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlvzbjf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zospdfmu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxemyie.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcupdsuv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrysrww.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbznthb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzxuodk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kipwvqvh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2swfzxrqe.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ghihjugr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpfnidz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmnykkl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqtnuuq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxhnrte.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkzgbst.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnziqrg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvfdzmd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqcwcqw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdabtsa.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjduwll.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqahlwlw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2puxqfovn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2liemqieg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2syrgzunv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhzndql.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eytgrtzi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtargxq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxzuojd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfewihyn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjhtott.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oevdnoqa.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ntixirfr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgvibii.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwqktyi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qugoowsz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2itwhcpdn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2panphvda.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuomhqu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2thecfasn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtwofpu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2omhqnzxm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvqakhf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlcgvzw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyybrir.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2omovvmml.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyokvadh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzedzguv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyraisf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2woncwmfo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhuaofi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkpwwwv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjslocc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2odlkkmgr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxtwjlq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2adjaapdf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2szntqzty.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdiqgdf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgoqocy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeziqdmq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dsveysuu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2khsxpjew.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2icbqbhgk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbuddjc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnnhjiq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2shqctxji.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqopsde.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mufnmqjy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrhdvyg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyhqbnz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qlznczgo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzypefg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvebcbr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfqjmia.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcdtkdo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhuhkla.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2axsxkgid.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxnglaz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pczgrdgs.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddurxkhp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkgetjo.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2clqzbkqy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kyilqfsa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmiupwr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gulwnttl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ainpiesl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhmlykc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2geuaeakb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzezwqp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdkbgai.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2osfprjpz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msxcumrl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqzlyxp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzlnsot.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnlxzoi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtalsuat.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2duucykio.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zavbqnly.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaekyyx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzcwfnd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whihxinl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2elkoowtf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awwemoio.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iafltiyu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iveyxhzs.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rztmcsbo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ioumducb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2igdzqvfr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmutxzna.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qvseohup.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2blakkxgq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqhxwcz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpubxxfa.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2heemjlqt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsyrhlk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhmlozl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2scarvpfg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbkbyln.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2afiecliy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hycaledr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxfoevz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2afcqmbxh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2skjoxzon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxxaneq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzcorhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfqsyfi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2awbhehbt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkdaqxz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgbwxlq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yurigzlc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmuawvw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfjsxcs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mnotcfof.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uckzbukg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxhvoby.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2llximmpq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtedfhi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cydozkfr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yrihumdw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2arfvirsa.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbyqgds.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkegxuf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bqibkznr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypihoflo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2szonwmzs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxnxafg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgcwmvh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyawrvr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsdlbwo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzxbjvx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2txnocllo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2inbchsnk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2moqhicve.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2phjwjbzt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2alawncan.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyyrjap.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2aapuwwls.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmhzpmt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqylwsk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxelrsh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tayvzgrb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdteovmd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvwkplz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zspgmnyi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2foeitsgl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pszfravl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrjnytr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2stmtfqnp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2odooufeq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnwwnbe.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxvyzoo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zsltghvh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hzetlfgf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwgsuyc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2biqtcyph.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2teadbqax.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfnowpy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzfgwmm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyianfu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqxmucu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjgnarr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmzgzgs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqtqiuc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfhvkml.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2giofpuap.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuhupcu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2uapklufh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxouazy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnutwjt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2khpnvvtz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlfsdwl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2beewgadh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hnenyxyy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnmktui.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gezeyivx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uftpgigz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtjinmi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2naekxaqd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rfytorpr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bfukojxb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzgrobn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrqvmbk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqclprz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbunyne.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqwvcpm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swphtxyg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bleftlsc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaeihqb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2arbsfljo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvjbvoo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjjbmig.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kexddtrf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhciclr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dofctkgk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2flhbllmx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyasgcrm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoqglfq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tawyhlkq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ylacqjzn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2burqqofw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vrznkkzw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxtnisl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wzndwdge.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2luqpntdb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dmezogcj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbkqmkm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eakacclm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2likbjayn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2quwdsaze.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vopekdlb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrmfvks.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxofoai.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsvsusf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2lflpjvoi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2piskluro.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmnwbff.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qumpkatz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrckqogg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2upmsubdo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjqdntp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbritgo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzftrno.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqbwdyl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjlvjpl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmvvwig.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxcocff.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjuqaga.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfludtil.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvrhkao.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjwwqxn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xuggouqg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2odydrkgd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqvfkyb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvhstxs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2walexvhu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2degmhzvh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2utowkidz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qghjfcmx.html


<!-- 参考信息 -->