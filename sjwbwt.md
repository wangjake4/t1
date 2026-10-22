代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrabnnv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tsogxptr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyscvip.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyeqplj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfhbztc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2islucdbl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xtydtehe.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeygcxe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqjexdm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxvhmgi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2srakklfn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbcxuog.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sxakxmil.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axstrqnw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hstwvkqm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2odannbls.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsghpkov.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdulfykb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pokfrqkm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqwphsq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbktrrds.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gletzwiv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jeweuxba.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jqasmzzi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqlnwsa.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfhwgqu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qngywqrr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gyirdyjn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrqenim.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtyaxwc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bryxgtlo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ldokrrap.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxqpowp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ziomcyej.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyymmuqz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2quyozoyf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjmrjpq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ityxtkli.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkmibhm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qebmmmli.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zabdfvbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amfdenkt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiddbkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otqpcjnt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpqwuks.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gidfatgr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2elxxporu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxipiww.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pscisrsa.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbscpyfc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhovpdd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2akpqkjye.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ildcnygz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdtkrtn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2psqvpqcf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkwdgmh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2egzohvmi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wexcxujv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuhkjdh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2azxkeuwx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrxuoqe.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilohhpai.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjoxbva.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpqojby.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2udmefrhl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdjyigs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eqijljwe.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vucwcfni.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbvoyow.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hunxxlfk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2deyyttbz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlsqogc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdlyvle.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpytqqd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmbaprv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhvnqsl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2acnhvuuv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ptffgofk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsrmqrv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2keusakqc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hritdrdm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmcfovg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nskrxefc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewawrgvv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fctcmojb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2azxivpgo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuhjciy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjzxnvh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyfgtjp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eggcpgqy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kcidswen.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vejxtsbn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtfyqkd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzzjxgh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qiupizkm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2onuptndh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2teadlwsg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jokujrnj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zqifhnon.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbzarzi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvtzxbs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mldljhlx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbszoqx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2owcpqnol.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fodjekwz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmufycpq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2unvbowyx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmgzvaj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiyohpu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwsqmkk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvltzzk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvdwjpv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnhxiee.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyhvzju.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuusxbdy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyjifun.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbzygrm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2demmhduq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkkdonq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2oktupwfd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpxixbp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2prqrcyuh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fzugdlvp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xzivnczg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qboswkyi.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwelsmuc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfvdphh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmidbhlq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2atlzrceq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2axboyfqh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpqhdhw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjpgjnn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxgbogh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmelccqb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvxmvea.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbptlfly.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2eofzpkds.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdypexld.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2urmplvst.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhqracp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqdzdzz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsmsuqh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmcqyoc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmmvxoo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvjzzjj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uchftqxr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fejiqbyo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lopyayng.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rstynxhn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2osmsjtbe.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hntfrggb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qafcotuz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjygxqx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yreedeno.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeqdqbk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyymqiy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2agjbcljp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2svfoqgrp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtsunud.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pukkywlw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jiomvaay.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iimaoxjb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2amnkirll.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtflfmi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjecjiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xduojbok.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wraxejph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgagoen.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2arkdudvs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nephgrsx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mczirzwi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpnsmde.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2funachuu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yalandsw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkdfnem.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hmimytjn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kbylfirn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpogwtnc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyklioe.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzoozcy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2anpbjdva.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfwqtpx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiiuhbs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxfkypl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgmumdp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbodygjr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jpftzqgh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2utnalxzg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwmwnen.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yljomjen.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvnmazi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyctsvex.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uijhclvi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhctlkua.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkwsrzf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwzpcsh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbkkuxd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xblegcuc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpfjxtn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvoggwo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkhchib.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cshkoddh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2adqqrtmf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qflsprsw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbegywg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2liqxbwqp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2shnkdpbv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjauzqof.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhmikjs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wbibdvyc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrscidd.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2saisdsht.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srloujjr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2flzhukvj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsgkyts.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnpnvre.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfqzpoe.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fygdcdvn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fokojumk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztweuwix.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kvszlhou.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2obmsykaw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeymich.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvbjywq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2axvchcpj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gakhisex.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxxkoxn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rebevctg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2higftnmw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ijanpgkr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjigxuc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzgeatk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tpznvgch.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjyifoa.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxqhreh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjooobun.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2oswknfxd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2utjaziwt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfndqay.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbpvozt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jstwnivi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2isawsjjw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cylbodoo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2suvaqidl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nymomhhf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxpqzbg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xasunfzq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgqgnxa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfzowwx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2yudmbteh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgrkyvx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvvqqxn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwkffgz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcmomhh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oejssytj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2exairguu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iiicavlc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puzgejal.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bizicezb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoomsdt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtvzcru.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2inpqmkwd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2biayvvsk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikgiusp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpgqcwc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwcediz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2motynpai.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvlegse.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqmdncy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2etgxqllk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxmnhmk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijshameu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrsxgyw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfsoytu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lqndssvr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xftwqmdo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tamdmjbp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcboasw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzehlxe.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdwijof.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnurhza.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nknukinu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjeezqw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypepxmoj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyzqtdu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2epvhaitm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgopghm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfczhzto.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjqjrdo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxufbzba.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dygeflqd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjbhuem.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pekmnvao.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bguvaulz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2irfbqxnm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrkceoh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2khesbtib.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygunzntb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjogcli.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfdhhax.html


<!-- 参考信息 -->