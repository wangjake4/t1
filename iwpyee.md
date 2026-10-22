代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2loxlfhdt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ftclvlkt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjyuyjr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaemvkd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzrvome.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnpneuc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2odpmdpfx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mobkueja.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnktaco.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkcrdbu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tpanczrm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwssmgtk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbfyvom.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxuwulo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlufttl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plqsqmqq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2canyqwkr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btuciuzs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reonofla.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjhcsea.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhkttws.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2giehrekx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2msbbyzzc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhukawp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2arqxmqxd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwmotwt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrnalgv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtleimm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sflhuour.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrojnmt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2icjeegmt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlomeel.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuvvorw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwrakcp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gydqbhfs.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uthtmncc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkypnfll.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fucquisl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxduaks.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bqseayur.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxofvtm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pekpdjnl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkonfesz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkrzilw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmdwwbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npfoczji.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2laawolks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzjsiqv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ldymprpo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2slpncakr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxivdfh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuejpvh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgiqxdz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieedqvkg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qenieqzl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjlwcke.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2afybimcp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lievukmr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aoupiink.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcomvtta.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoaempz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yakxuipw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sbspptrw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsjnbqq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hswvgbxb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtaoaxe.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrzkvcc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqwwjwf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaujsid.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jejkfpso.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ohucvsbi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2negritiz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zahidwbl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyhagic.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaywlbw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfunfkcu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyrvkjl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2odqcckgm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qaelsmux.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xffyzcgz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvjseie.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ldepmbxf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwlpvlg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlncntf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lchwehiq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yimsoabb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2avupxskf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbpijrv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2olczkhxf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2btnpwvfe.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnwvyab.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2quukcgbf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyysyns.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhygerqk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjekcyj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nftauzlm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpxjoqt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iszoixfz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkqeqhm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qijnsfjp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qlruvwgy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuwctlx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlqmiqq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2blwuhhhw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yvejpzxo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcetbzcz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jarrgtyx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jezvwycw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkhjuzd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zthdzshe.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yscgvldv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkwismm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jodbqkuf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2alaqrapl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2newsxgdq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2oinhmygh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2oclmyenx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnteufq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcavtlka.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcwezoh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrgnjho.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uaejvwiu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjjyzur.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjtwyba.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpstwtp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aarvvwns.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzsmnzh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrkkfku.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2otqeijfb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2afgscpzb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhjojdl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xagmnjvo.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyafstw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2clcgdiup.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2neievpeh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxepflva.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjjclix.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbtbggn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvbdcfi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbdygdl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xwznbpop.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfsgdox.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhhqpsy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsayhdp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2spbmofpj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmfxhft.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwefntyu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrueyik.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpphqrvt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tbifiwoh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqbtlnl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtjatav.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkewprt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvortcw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogywyrye.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2opamulfh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aljavhtg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzoatfx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zawxymgx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2szlumvfl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2svmrksdz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkusvid.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkyaugx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbrfrix.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kywlfbag.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fycnissz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxbkbno.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsvzcbt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2amfyxzvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfzybsd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcndlfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytujkiss.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lfextmqw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2onbblhkp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ixodmtsi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xuafjesz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2krprvuxu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsvgedt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdgraqn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qzptfaza.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rflvefvr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzttbri.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oohnhvms.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2raddkygh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zlympuos.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhydybng.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jbedjbfp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlfmhsp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pohkyefj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnlureb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2luqxfuvb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhlojig.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxuewiq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwassyy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhhtuqe.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oudvmyml.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcjyhnd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wydsknlf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2urfnhxdm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvuhhul.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2obhqskoo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2raztjprg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgezvun.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhdljbe.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdbuaox.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcceras.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2exbgbdlg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtxaopr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2srvtyezd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kphhuibh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wfznagub.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pithjjik.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpfbltx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyxzyrx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dixukqgo.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmooxxt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjwrglu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtiwjtk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdpmrsx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwncesw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsywauh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyirlhl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiwwmph.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlmgpvv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rsojouce.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vavlhkxg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqgteyo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtukjjc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cigvbylo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2oruxjykl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfzpqks.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzprvigk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vjajkvdd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qegjkswl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ajybxvei.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rdorpqkh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqeyckt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2czhpxzaj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjwijog.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjecsiz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtrjfpl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2msumhpgn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsrixbr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlmuvnw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrvsarz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfrqskt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnvkbok.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfjrnmn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hojwvsmm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfnajmj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqaasaw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpkiwbv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzjnrvu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrijslc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xonvvkpj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2udmovtce.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tszxtelz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnxpafw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjfofyd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnehlvm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uecqcwit.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmckuiva.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2amogmtbb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2barvtcnm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mclldywr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jttlfjom.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2abadvefs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzrsxvp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmjlyxl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2anehddzw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2klpfziar.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzmahdj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2myrhsdja.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuerjzva.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoedegn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgthzygi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2osfqnlbs.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2aghoeiyp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxyedmr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pphqgeqx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeyptav.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qvasptrz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlybrgn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cucvhcuh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2btyxejfn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2svqtlfsr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpdwhrl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2njgppwli.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvrxaro.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2umpvmvgx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tftgvlvp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gafasajx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlajxfr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzzkhrt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjhnjws.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvggtaui.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sielkzkn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmojuhr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cuafrvab.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeaxvxe.html


<!-- 参考信息 -->