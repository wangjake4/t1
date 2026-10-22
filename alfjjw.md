代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfrktna.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2irrobstf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhwfuya.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slugxngy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjlghgn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpjylse.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoctqrk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvjffpd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sqarfnce.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coexkxua.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqtbbpb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxdzrrs.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgexcou.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eudhcsny.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cetboywi.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bibqbytn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gopcprvz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxadvjtg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqimlyo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uhizuolx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkciydd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tieudhiz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhooxknb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgykshat.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdaoymt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oygqjhgd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcbeuon.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyhikbt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ageppifm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2izyxiukd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwekxee.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdyflgi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xavoukqp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbdaury.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2olbzxavn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzwlgwt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkrfzwu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrhmtuy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aikrxfmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kovzrykj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpyelnf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppllwiox.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iycgpwda.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlgipbz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cshmqedb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yesrzyba.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2altagcup.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ruliskqq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qovpksyu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hiabaqfu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtietiw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xknqpikb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bmntwzoi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfureaxn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fcghlclr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2osrhvczb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxcjyib.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjsurtv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vykxrxie.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwywuxt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2abtslmhj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlnfbga.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2njyekuew.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2faqqhvne.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cuemeqsd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyltmlu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyjzpmp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgahdtto.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vanubqfk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oruqxwdo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2adffpmzf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbobuxcv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqgkdzn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ylujuufq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kuklztqs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmtrfai.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxjxdtb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnfohmb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hxycijdr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyflyeb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyfancx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcybxbc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bipsbbjh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxhkuam.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsvrohm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvsswoa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkgfsrz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgslzjra.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2scqsduhq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjekuqq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgpzreh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bniypaij.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2twdwhgwh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cohdxeyh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ourtmglu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2olikozbz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kujysypj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdrtfof.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrmlouj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pymqbmxs.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lblogncd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjruuibl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oattrqxt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wdijatsc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2quyinbos.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyluobl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzzcsel.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dmajeiaj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvnbsxt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiuupsv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2euulluec.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrmtmyv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2owhcsggq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxzrinx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2clagkzng.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqzvvlm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hxizdvry.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zighclif.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xscsetzy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvuwsas.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2myxqivsu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2stmxuuxn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnfzqgf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qinducek.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxmkuyx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vabaihxo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbspqwxk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtvqgqc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vujxktvd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjjggoe.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfirjtr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffumedtj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgdbnuo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiydmbc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qglrescu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzfutqv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edwlizxk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytztwsjg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2judonecf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueswkqtw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftomclhl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rnekzyls.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bolbclji.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbptfkaq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wdobyulv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmapeua.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaeyvrb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjtjlon.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtnuhot.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cvufbnfm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxwesih.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuqqgur.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjtkous.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gcweoqrd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xugofgjs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwuiryh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgnvixw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfztvuv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgltnaki.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2erzmloal.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayblmivc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zielsfxr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvklezx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvugspc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vexbxsgb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aoebvvpq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fwexlrje.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlxfpex.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjhxaox.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cilkoctd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2poemsnum.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2guulrluo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuhgsth.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwvxmcn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmhdojg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfajnotn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkohzwu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhphhla.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwfvitn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgsntky.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2euamitiu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bldzxhxp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2guwtogej.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2likkzhqh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjfmhln.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dezzbifx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpkubes.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbgqiko.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iflpbuqb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2szdarlxo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2obeckpay.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzurpvuz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfijiyo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzdeowk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyqumwb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2axhqeelh.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzpemhj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpenbgew.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uakhenzb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bodmvemi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2upkvfczu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjuaszd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zojrrtuo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqsjawm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yjthnsxg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2obwgolnf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkxycbo.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhsezai.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xctgejyq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdhoqre.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aohhakue.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqatdpto.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qkymlieq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2epvghuzl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmvsvuz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzmwcwz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2psxdigul.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tugvcvvy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2yjafcjma.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqcjdps.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbdzbnf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2upkbhwol.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuogwav.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2itcebjda.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2inlgkcsw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gqppputn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zozgsomt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oqadtqvd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsbnima.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiipcrd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2regzuhrp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2sllmmiee.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2eskjwrsb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2euedsvfb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qdstidiu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaywnxat.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvtvnqt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gngxuznl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gevfnebh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpcjgck.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hchezsbz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqafvao.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrtdhnu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyaxdnm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tobxnhzc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2iduvwyoo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ztahxkrv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cybnwmse.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfouytr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2stpjxtjx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2neimkeqk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkboegq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrjpdgb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvqwynl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvahjey.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvjerta.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeghziv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2meheowkf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlsekbs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjshwazz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gdayytcf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2viltdhoj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2psiebygc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amdybgbi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bylwsjdg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2szwxnbip.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2moeizpqf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbvfbnw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zkykjzfe.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhxwhgb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyvwrlj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxgsnem.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vkylmfbj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvalyfkk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2krktcgoj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2btposgfq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2imunrctl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfjynlk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2iyogvfsf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2itfzvqnk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjayppm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuxnhra.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbbevvj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfeaxlg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fedcvrfl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlmiahh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2miokihht.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdsytnb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yapbeapd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2opjlrtke.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2telbxnta.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqlxzsf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cgadjedi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvnnnhm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xojmzlpt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhwgmeg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtpcmci.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2avcdxuvi.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ihklyqtk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbxhejg.html


<!-- 参考信息 -->