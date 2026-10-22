代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwasxqh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcccbbxr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaryweu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znandwof.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfwsgjy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxuvdie.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkptnzz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obgnytxm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zyknmynw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pulldfhg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqxaohm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaybqtz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtnnznb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbkpilm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pykinltf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxgqklm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxnsffu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2csaiyafo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpwonmv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwufxsw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aikxyqqp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeuvfpk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaqbwrn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuvamcc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2texpxjiu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvmptht.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxfceab.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqylvby.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqanqbg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mprmfgeg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fonnatra.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwhehfz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2utpomyxs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jyysngfm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdixdvl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwllour.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wndpeocv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmahmmk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdrshhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfewgiox.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qnopgurt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bktzwbqc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efxwgwee.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2shjtujxc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkgwupd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dswxcecf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2grebudmt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2thpwoxwd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2njuzrqda.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcaowyx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2poszzact.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2srhpklqv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yofkvrov.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbvsiay.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvwdimy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfpmsrj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2simdgbuh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdfuoub.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2icgbvsyo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjrgriy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxcsrlb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2quvktpmb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjousyj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxqftif.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpcsddc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vamdzuzs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpgyxyb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2itilvgpc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2urjhozgo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgghuhs.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwfhgbo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrpcwvp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxupfau.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfcuwhs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdribgsy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoeojbd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsmqqup.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iycxsegs.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlvxxht.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgumqoy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sitwtqpu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2urovrntp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxdvbjw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnhxdrs.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nirqansb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kulaakye.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rumnucmi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rggmdzjx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdwxbyw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqdkwnm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gduojwga.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkclktns.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdqagup.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2czgegnmh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gozidrdz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2oravrtsf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tllnrgca.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsajvql.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2akbjkdup.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cslkmbzr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pinfmxnh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzbmrtw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbatfur.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmkttxb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sugoswwh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaktpua.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ervbubhg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgbophs.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2twcbgpbt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2psbrqvsj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfvpipz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rihkusny.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2efbafqln.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoijmme.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiuaeha.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ngytuzhb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ketmgcnt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqpegrb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2znvxulky.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnitpst.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvlcprx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgjmojs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqoluwn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nglmbtqk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oifahqnb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrgnjro.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2irnjpnze.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tunlxlfw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmswmsy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twvdnxcv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2egttuoth.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yshgpwmu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsxcnuv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cihqjzpq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybebrdro.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqntoyg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2liambgdm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsueoip.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onmqwcgw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbxakhu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yugceqii.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yxltrzle.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dptttxpf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvktwbe.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxximng.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbsuqrs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgodfrx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzxmsre.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oszjfckt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tgohebvb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjvexiv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2shpjprhn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwklmtam.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2najjkmui.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkfvakl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2coifnmoo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkhnbev.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2memzgila.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcmqwaf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pgedfgiv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2krsdxflk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gppxlgsf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdigoan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqsjbpa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pvahdfht.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2awrykiwf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmxtuql.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btyfqkjb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzrbeat.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2edbomgiq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jauwgdex.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvyrmyv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqxsukr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbgikzk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tljlvsgx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoswhni.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kktcjqfk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkdrpin.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqxcbol.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxodnnd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbppxae.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzercssl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2islsohum.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2msxhirwo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiqdtan.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2orvlappf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2igbpktnb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkatidhp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2epdcfcam.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2spjxmhoa.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rebjkuef.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2petwxpvv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnekoto.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmetszj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2epbypcuw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2upontsvr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2notbdawr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrvjrjk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lopmhzuf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzlpsxn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsllkgx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2deqvpzoo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqxxhxi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfsinql.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zkavsakt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ennodkht.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fqewxtie.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaqvjgv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfglmvbh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wdazojaf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cahfnxbe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqetiqb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2eudviatu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xffxdblp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzxtyum.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeenwsv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qepdcbhl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xiduhggi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2joghxiyo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrvxlqm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hijwqcng.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2iikrqdgh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvtalcn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpikhkzf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gooixupv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyffivy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jaznyibr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxtpcmw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvwxrxz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jarmqrmu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfkhgbm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiagcaz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiinvog.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sayoebhm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhpehtf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwonyvfs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2icxtjben.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcuhebd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tptuloyj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhkfvql.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jymqwyjk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ormffntp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kueyqqxs.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxirpvbl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2msqpwldf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxtanmp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2elwmlxyx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbgetvd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcwstpa.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaybmtyr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxnzupk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkjdtza.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyyokuz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frfxxybc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zczfgfuy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfpsyzs.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbovpxfj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2iloxnkmf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2utswalxe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbwtwvv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ydetzcqm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pdposrcg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzidjzp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcymtwj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fukqquzq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnuzuhm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdotglid.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qajmukze.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2loukvsvl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqxghya.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uhikfqni.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcfbjmk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kaljbliz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2augdxsrw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqxstty.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhnemfn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhnpmdm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtemuibv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zxubbxtp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxvkonq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmczcik.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jopmcfie.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2taafbzhr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2enxdffpu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrgwqrh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqqqeox.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhzyzbo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2memncffy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2onlqvrxb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtmkdyd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvdcmhh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzfvgsp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wegoyaob.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcfynov.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2irurkivo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2agcgtfbh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gimbeyrf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxroystv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzhguvq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2uklpnfws.html


<!-- 参考信息 -->