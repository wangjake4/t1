代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsikrtl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuauusja.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaqobcf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxjinwa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kztarxjj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fxznmwnt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbnnjqc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umhitveu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvxbpid.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdweowso.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elxahsjd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2knxwocrt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuxdxib.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjgfybt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdijgsn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlikqcd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaeuxaw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eploilam.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyehywa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwxgtur.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnkgzak.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jugaxzcy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcacbau.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaximzd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwfkpfd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgrtxit.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jotsptmk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2puelrsah.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbmogub.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyqojvl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhjcvui.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bczwxekn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpoummi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgpznfq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwqznfh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jplqmldl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eapyzxpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiisnqu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdxhpyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stlahgqy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svemchgn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zegtwffm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2plqfuoxl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnokdzl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eykhalvd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmpigwu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2suwcnkoe.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sekcfipk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpyzfqs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2egkfpgrd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmtoovd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2slbwsjyy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eagutgto.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdeaxvz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwtmjpk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qggyzlpu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwcciim.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2boarhlms.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhquerbr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrdtoku.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvhmuce.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xktvagll.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdydjiu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkjviyj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2truxhudf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcycmmxi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yagsbcyc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyxzgid.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaixkzp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvtqhob.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kegpiiwx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlgyyvc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2limbirmw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnsaagg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxehfrw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwalqidu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2royoynsy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjinogu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fiktcnlz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eerrsujv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdbsprh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqltwcn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qriesous.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ertfmidy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eoadzlsg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nasrteti.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnzqjay.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2soqpcgqp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjmnxwp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxbfirg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpyqcul.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aspxgolx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmrqxhc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvecqvlb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlulrtx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjfomvu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjhbuso.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2arfkbage.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mthpwdgz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxtdmss.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izzwejgg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2homghldr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiboyna.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkxiwrh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbwtnmf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbckvca.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bsptzjpj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaphhia.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwhrgnk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2orhxyevt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruijpwry.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhrvopi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhsrwwi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjlduml.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2brdzsvau.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqmcbwr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uuubkxja.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmslcui.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqczjycr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mxztvoih.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkwwyhb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjzekyb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgdlpia.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjvtauj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzihimt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrcqxtt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxciwnoa.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njoodvie.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xsussozj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atzujxaw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kguggmim.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzkvwxx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpnpcqc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cscmirwm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwaksee.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgienvnt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pomagnxb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otoeflac.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yetsfahc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zourkbvl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pclrbpgn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lhghnage.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiwrhbd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcinztw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ctikgmdn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2woktbnxa.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsewvkn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrcrlkg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zymsvhmj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2trisejwn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfwqvzw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgbznbk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgjapop.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2habcfphx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zthocamz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wchpogod.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwtmykt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxcczmp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxphzdk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2udfynfvb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sibbizvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bazeijij.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lllpcnom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2niczwicg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uuclrbqx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2phybyftp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwvyvpb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqbfuwz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wsogtjza.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dblsdfxd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpefbif.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxilepw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2micenkjy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvyhgen.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjsjfii.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfguagut.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2szokqlxa.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2owjbrjfz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfenuva.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2attvlrfa.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2djuazqzc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyjzbzz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gylvpjht.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bscjzkss.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqwphsj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dizooold.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vytbfyvq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpmhvwh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wenwnjur.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsltsus.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lswiftbm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcljxio.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzegbze.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2whjnpaio.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlffwhb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmurhrre.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyubmjq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2epmgvalu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yanierxy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeocvsxq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2sipudfoc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzncxbbj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cstjufxb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2spfhnhhf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkliojk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvemjkf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cisiwfeb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2joxexhmq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhhzqkv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrkzmac.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwqjrjl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkojjner.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvbhptx.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtpkupm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jiubljov.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiawsvn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fysvmwhy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqbpryt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2aatzcmzm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxuvrbx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fcroetho.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2smzcprnl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdjmcaz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyjlwlv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmfkdex.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbusvex.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2figobayp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqahbfw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2iymgywpj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhvwupi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2siuflvku.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfvjpnc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzaoypk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiogxdq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtlnfrr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kchldlzz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gunbialx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyjchtx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jpougcjh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sidsbuwt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ecglfums.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzrekjm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdsydpn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gddxabnj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uwazrvzw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jefezfob.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2alnhnood.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzyilub.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uatgiqot.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgwxgsr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2otnebvax.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dervohzx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qavfghcn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vidpadmg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmgtcuj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lohjynnz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrmhegh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2laeworpq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mzanrrcu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oelysnnj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pjycmzjy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2uboymvxn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2khiyjofu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbipmvvp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkqofcc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2uekkegvi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2miqbmudi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2brzdozif.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyhupbp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zprmvlkz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2evjiqnaf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2josnagwk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fzndqpyb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdgjotu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvymxln.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzhzioh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zryymrxq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrwgdev.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgfrems.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2epmpwopu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaplvxz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbimsdu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bifdgvic.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2grpfbxvg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwiudbb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzoaors.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2emwdxinx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyelscg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyyubak.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtouoztb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lphpqaag.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrxqjrr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwhxiwv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2btivvzee.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2silaljbx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fixcexxn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsoplrn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtshpev.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ensdjlhp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfwhrwj.html


<!-- 参考信息 -->