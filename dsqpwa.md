代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcxdamy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfteuubk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdudomz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugksyysz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgvxhtm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeprcfk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmufgrpj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfsljqi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpxhfqt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sifgsfpx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2iaagyewt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ogujpods.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liosodpa.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrjeqhc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfliyfrk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsxhwat.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yniovvst.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnsnurq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfufyhl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpnpinn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dalwzeod.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzdarnf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqmywsd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2aleygoqb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfdzfqk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrnxmpn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpugnesl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbrnemw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbmpska.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzreesgi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwacpat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfvfczv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvsleug.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ienfjbkw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2buenmcpx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtbpxvp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbpilao.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2albnmitz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pryvvpls.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2obkymhlf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvborpf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyauwzc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2senmtjga.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qohywnhy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rugayynp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcmbeox.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqmgtyp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvdhuul.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqyfsyh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2odntdtrc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vivlcmwf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2doxwnmkm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2stqxzzil.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdclueuv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwiisyf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxovcqra.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhhruaj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2siobihta.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkwwove.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfussey.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrfhaoc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2npjfzpel.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpcioxz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxaotvn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rywzcbkz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiuzxwi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jiasoide.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpiqtil.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sulfcafg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyozubc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2skfextrp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjjnnlo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2myqsgefa.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sixowxfl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2geldobgt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2avxikhbx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzynziw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dykijmdl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwdbnyk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygebieln.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqjgemg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiijogt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2psmyasvm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfyjrsx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yejoeays.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvkhcpj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2icpkcrtj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvdixoi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2loinforc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgufpmp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmsxcyr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfxhfyk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wftoezfh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzivzzjn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvokdjze.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2couxrgxz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2upuyzksf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbixjrc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcazweh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlattyj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfzitma.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrrheyq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvkckyi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoawmzb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhmudke.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdooahu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vompkvqw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tanaumtk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcunodz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oigvlbwz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlqnjti.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvhqvyu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2djdiwkqk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbmxegn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2unzhphgr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjblmyj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2auvkduay.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2teqrzdpn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2krfmersj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqgpoep.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnvtyuv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjicvysq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yherrrkn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwklxwiu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uowyjswk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hazksopv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nkphnnsl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlludmut.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaakpby.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcagulcc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iynobsnx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbuppzw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcaydlv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpiiacv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2koczdnxp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bndhrdfr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2anlkzabm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2miangcao.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfywpibg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrpyofu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdkpjwt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hhicytkr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tepfdnpv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2piyemubd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbcojgx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vylcxbdl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxbogbd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ejptdktd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sthlnewj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2phgqtnjc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xumxqxne.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwsddja.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zorychfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kttiwkkw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uferlryt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jminljli.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbzvzka.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyimlvd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpplzed.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2axvomuok.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjitiew.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzmvkyn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2iexwrtbg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yltmptyl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmllxch.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrzzqqp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqfaebi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2muykqjkc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpfbgxg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfawgit.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvwlzxj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2obbnamxu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvcaxor.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbxlxkx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqeycnd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2iosksury.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzqkyuo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjytmjvj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2drvccxya.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvjgdlt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgfwpho.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzcxgdb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrrpvqa.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmnyxsd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbgwpnj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2anlmmmwi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2geoxxxzj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2smjtdqgf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcpnjmy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2abegwkmh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yckxjftv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdjphuh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzsgycd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxszbtl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dwekzdbe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkygxcrk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjmwbzm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2aoddtgpt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbdapmj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnrdywh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqcjqgi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2otnwxpzz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2guogrgjv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofotwrmk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwuqsid.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdofikol.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2eikqmcto.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxuxytf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdhbtdc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2evrvtfgc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fohvibad.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzwhram.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yqenclnx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2elzalroe.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aijlzyax.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jubroeup.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kezpkjft.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2eeksjfvl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aizdclzd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2epjhrqkf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzlnrdm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjbcwkh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2blswerqy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtbssnr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqszinf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzyyofq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2meyqyhty.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2orbnylee.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2umdzkhsp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bmggyaaw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzwflam.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2oikzlopj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrtqvjx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzbfkfw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2flyiijid.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aehsvilt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgltmxn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2eowhnzje.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpmdpes.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2liheqnno.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zaclpusr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2frypgusp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vrflfbtp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoakbsw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvhkajh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpdwkkk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvtnvjx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2shamenui.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2utwwbjnc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjgvvun.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbtziiq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlunxzr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsorybg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrvcdlc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdopaqx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xeazajkk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlmfrrd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvympwwf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2loksihmo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebytfzov.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2amlvlyqc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqnjbvt.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wygkbktk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmrncdf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qoeonlpl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2satpmfec.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrjyjze.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaboghz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2thrfmvog.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwtalhr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2npucwuoa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vofgjadt.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dgquxtvs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2odzloblc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2alezkgys.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgmsvvq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiknwnq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rprelwqp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hippwtpc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltezbfsh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqjtseo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2abjknsez.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvurzaf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2scsafetj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaplvcp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaoyoog.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vukdjado.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpxulfk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jybcplcv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2utiipnxn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2snarrgnj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfyitad.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvqoxxg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfrplsh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmqadsr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fglmhosm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fteopxll.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgopaou.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oygkhlmf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gunsffno.html


<!-- 参考信息 -->