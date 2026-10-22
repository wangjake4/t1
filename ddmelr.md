代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2plxazmuo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2olyhdfuy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuahyntx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kleynftz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wswdzrrp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpimiud.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqgrkjx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmhlwht.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2prdgwhsn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxpghmg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jhalccwn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzozouzb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hahjtxeb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcptjsy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhydlixq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wawefjvc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qspkcnhk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okkltmfr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ilactmkb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hcepevaj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrmmoeg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyklved.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zltyshwf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vyundvgp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myqpzjbg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjnhzzw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2reglagck.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhpelok.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2paiufrct.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfbxnmp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxobyfqx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2sycdkhjm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfziwfvv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxryvode.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqoufwg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtcmywm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwvgkfo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqnfiss.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gycgnquj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2slseywuf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gsurthxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gockwtss.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsnikgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqsmdyc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkbuqyp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2labwnrno.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkajscxh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlpjpgf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iccnoszw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2suxchbrr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2unhxicyy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgqiaus.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvbrodj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lseshrcs.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2icamqvpx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrpreol.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cokdfmtr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkkskry.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfnyrie.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpyyvmr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mothobkb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwpemvz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ansceovs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuifane.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2akoshlwr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkwwgyh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nnehjxjr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2utkyfebc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgearos.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaolkco.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsqlbve.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqzimgm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrhclsd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbyrnbz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kovqzpvx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjywkjp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcitvkd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvzekxz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsfmzom.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kovbustm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvjyhox.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnbjivb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gbabqbhn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkatzoc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmwfmfo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2humzzluq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2clyjmpby.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkxtavk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmqglta.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnsbbml.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsdcsne.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2syvktprx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwdwjqc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfavlydu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnmkaug.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbaiqhc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpymuft.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbmplnk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcujbkm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2olkhlato.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hpebfvjb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdcgwxp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnzxsca.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdojcyaq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiitzeo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhsuoku.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxufswmx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeaueyn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lldooxso.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdavfbv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nbndzvzl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ashlscds.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ulazdjtg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eupnilqm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyigmijl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrupuod.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdxysln.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzabrum.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jymucbjf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uuencnbl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gybriaqh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dflodmpw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2evtxuyvx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tjamdrvk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tcehdwze.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvksnbby.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cyedbkua.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjjvejv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2flbwviaf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxperkjp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvignlvw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otaonreb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnshtyl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeeihfp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2swuwxmgg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfwoouf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqlqpit.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jutsveqp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjylcbk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrxgxmu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgrdufz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edhmwfid.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lievosks.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwobyjav.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tspttjoa.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdlbqaq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2avmwtjst.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwupuwzd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zeirkewx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxfvyut.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2khsmeujt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzjsbzd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqduicev.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxbqpbs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chnjeqfz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2reijswsp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eavwvfzp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyebgil.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxqqeok.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxrlzgx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnqcobk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qmziyfre.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyruvjts.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nscjnkfa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnofusp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqfhrjk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmbxyjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpeoeom.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbutzkh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2shdrxuze.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwroaal.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2siamquvm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iveneddn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2atoriibs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdgkkus.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhynmub.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqoffev.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2veetdwfn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2txqzskyc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsblzgkx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehampswq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfexupq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tyipiijw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcgcfce.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwvfqfl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnutrgha.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2msowezov.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpivkfd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hiytijek.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvbohfc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxmwsuw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mchlxpgn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wbesnkxa.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2esankpqy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lhduxypd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjawdbvd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vleymssa.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbgwgxt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2drzwoqal.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqsewee.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dezdpbmv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnnzjkc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2eazuwzlc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgtpcbg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2prvmdvrr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdwmbmu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lelpxkuf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgtwirv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdgekcp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgsyuap.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfpquin.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxmlrhu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhqxwkr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hturkaqk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2atipgpll.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zotvcbcq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uyphzcin.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbphjuca.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cugmhobl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsfqkdn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmoesjj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnxkbpp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qynuudyg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvqesgj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2slkpbyyb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2feedzzop.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnuhwul.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnsvici.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfjwcnf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qaydyecs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kswgjkyu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2svnxhvnu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ulleeexj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpdsdbh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mtejfmzd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdimkcu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpkrmjf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnpwypg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gadlxydp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuabnrmt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhgwstx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vapbgftb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cktwzvts.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2owhfeyza.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pguyoxxl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2javzlqee.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gotrqogx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xttmjeed.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tywmtglf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrvyqso.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnhloag.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyesbiqw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhvzwep.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffurszlh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqjtfap.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsbsflk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeugiob.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhxybso.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qdanfume.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vampmstd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zprwpijo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqiinub.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vonzmyuh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehszlhns.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yanosslr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kegkxvko.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvbcpww.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knedtosr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2laqdbqnd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dexynzys.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkovsbn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2htspjrks.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qkanjgns.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmivezbt.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfowcko.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvaxeng.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcrmhio.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzidtit.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2igyzssrm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkidyis.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxmsjzr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyekloms.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2galdhang.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsxzukn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjapxaal.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2foevjyto.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lykljftr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfijyiej.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgeesuo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxijhpe.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcltxey.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzoikha.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wovryekd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2esteaxkn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkotznh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2unlvfcjj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmcqcda.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2flmnngjs.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfuuccb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcfszeh.html


<!-- 参考信息 -->