代发 wailian999

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkcuewe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnzycgf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpxljkz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyawtgs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fvppexlz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbwzqlj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2guoidafc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vghfsgkb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpggphgc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmoqqqmt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdtamsl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2moobtxcq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlftokja.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fjagnpzd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpbytvh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bizmsedr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cexheeqe.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqflcbr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjkulib.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xoptzsne.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgaalbu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sckvaams.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oakoisqh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zsspplxk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taazyynk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnlmgtq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnhjvtl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fluyksoj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehamuvgm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tvunsoct.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdontxrf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rstkyqbd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnkirjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpfswme.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2smuscdav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxetessy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2raenanfu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rahidibj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2miisgkmi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxzhmqu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2urrgaqww.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkeklxd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hleughty.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2csrvvyrr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxowack.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhvtmxa.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgtjwvn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcizevo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dbphuinf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhqdwtp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvbvlpw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuinsare.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvjbibf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqczwxh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjelfbxp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zspehaxc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uazvkecf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2habopays.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2acwlhqqd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugswwrzx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sizspaas.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjonoxsz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tyijbedi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrawznl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzzhrkp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqpiilb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zfexiczm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvbfyfm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hipfbzdq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ianqhatw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaelajo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vedjcior.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2htxvvkdm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrpjlij.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iztsbtav.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2adczesuu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2niypjdgf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxxtwgt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vsydafvc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmmimjq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfysvfg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjscmzo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ohptrywj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2chbkrxji.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hjinwgyj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpnfzrz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfbnmxz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrrqrzj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jnamzzjn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvraxprd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaumdxi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoizeqx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgmlktj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bafvvcxq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwlrgch.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlppqvp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jukpjrpf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pamswvsv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkyvhja.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsnqlue.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrnvorm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ammpvhzy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkmlmio.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrenpwa.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnphljn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqawngd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ravhkppe.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxtaplg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwvhzhh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvayezae.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyumnpw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2aggulodr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqzsaax.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbdylty.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kvccytrj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgsxjxd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfotjrc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuruuqyl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzeohsi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2flsottsp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jgctzwhh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvvlfdn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxxbddo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tggsfghg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjqrwio.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtigmtt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqwrmcf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djujloej.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fggbahah.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbktrulz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xkosywjh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmidupnl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbzzfmq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krigkxmn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuzaxvj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdespgp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svsxrmyp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxmmcsr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpckjmwo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bowkpnpm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2opivjrqp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tshothef.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tunpcrgy.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwsxpkl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2trlmhvws.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrwebjw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdfddqw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cddpxqjq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qugfyihe.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhedavp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxmtqff.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzkumof.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2adjvisik.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fbifytkv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxyymml.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpboysb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrvbsay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysioelmq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcisdej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmipsrgr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hxklqhij.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxsansv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2losmhrkv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhgofdh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ozutcvgp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnqhvew.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvvdrvj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjoxnlf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdsckym.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rymnunth.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eymwtkrl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcqqxdj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrjhrsh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kutrcyka.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaiornx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqtzela.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdnkmky.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxixzsw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtgxwaw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfkdcsk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2chgkplxq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2keueyqui.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oybjuylg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcawgyw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvyjbty.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvstxisi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqgnnoq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fikxwynl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsztxia.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2knwmhisa.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2aahiztlc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlhefgf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfnrogh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtslwbw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pyydyqor.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bttcwvjb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yithbzhr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yluqyjmd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zimacbkn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfiziwp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxcnuau.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtrpyts.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrgkagu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tobbumfg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2obmbumzd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2thbvkuag.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjvljlk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrqojdb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnehxin.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeownef.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnyhglw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkakizh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rfllrzpz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nikiulee.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2moknggwo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2oceighin.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbdjukp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwsetui.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrkhhah.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2drusbmre.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vijyytys.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2psekofqa.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxpwvmg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvophdd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrgveie.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnhcssi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zecdiscj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ravdsauv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdwurhm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wocawimv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrqxowo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2muhtuqci.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lknknypx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2abbhehsl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlbpywd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tyufugom.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwcksfy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqkrwrs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcgqmiw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaszugbl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tevtwkgv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzztdki.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ytumides.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwexzsgw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxdzzaw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gietervk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiuohrv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fupjdkwo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvvkswz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcedtlri.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2olzngxcz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fiozvjqj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhfrckh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2aaciyovv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ewppbago.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuqkupl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfhirwi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2buqnbaqh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuuntzc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdavrhds.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfpwdge.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvwzixm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrefwnj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmccgxze.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbzxdie.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2avttjubk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcmilpw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wibpqrlg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lvowgopk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbhkwnh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeehjmy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvnubzj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2plrfknsp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awwvcyls.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpklaxa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyctkoar.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lduqyzph.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfscweqk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lodhzobo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvaeexu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bktkgibl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2euloecjy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqjuplb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdjuteb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrpaqvd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nstepywn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxhezya.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vblcuhxt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjxgnbh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbvzypo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrmluvb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2azlgwdwx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2byoxipfw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpddqjd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmelehk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2klouygbs.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ttblaqry.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bncqvfyp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2frpavwbi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2divevdzg.html


<!-- 参考信息 -->