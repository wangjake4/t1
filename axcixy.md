代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sjljzitl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2catjtovi.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgclqeuw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2eafxzmsa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdbtwxl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkmmwll.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvlsjmy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gwreuxua.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfslrbag.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2objikjez.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzcepcl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdadxop.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjxqyjp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cffuzudu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcjgima.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpcpfep.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2utbgvxtv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2idejydgw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxbgsfc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kptmrwcr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtrgeqw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2obiybfgd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnqdzip.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwoybiu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2auoaoxej.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgzlchz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dywejthf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmlgzav.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxpxfky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqmdxbv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqhmoro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfhypgb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmobmuk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvebzzv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzroxbjk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mewjmumy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwkmyiw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsihunky.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfmogtz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrwpeck.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2msqftfcu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkeewxw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tylnzdwz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeukldgp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzwjdmp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzetrlhw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tvymwjge.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffauwhsr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frgkaywf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkrtwir.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqcswqp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlwvbsv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjpppmc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2eptsmvck.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dybsvhci.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgueyqu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pezgdvww.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfayyrlh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yozvyijc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sffmtnkg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzfkrkp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iysvvcvi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlmmqdx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxsvnan.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2skkdhxei.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ldozglyj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2euclmlfq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsabbss.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcfzpbq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebymsspn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yioozpff.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybluewns.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kdagirvg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnkfpyq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nprggbqm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrsijal.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2maqzzbtf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfksmpx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uymqzydd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eabxgsyq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2umztnusu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhomftb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2opjygvxt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwomrmwd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmebqcb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zawodaec.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbxwtms.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xolrdxem.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aemfcews.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvkywvo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ufncvldu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2asgtcyxn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjpfcrj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjptgclb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjsbjmk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfbabju.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjusxihw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbcnqyl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2otfveqqw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwucnimz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrkbmjb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjjadcy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbxwsvd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fnutyjsc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvnjrtz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2murgyezc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2teakeyaw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jludgxwg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kdexsmfy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2engxqsnt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tapjjpgb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tiahfdmq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeivtii.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2khsidrxe.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcwmwiv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcijbci.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2snajzslo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2biojpbfx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpdulvc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bswpkbqn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqnamit.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heatvolq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wreazfkr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuefmvyt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdgsogp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uctwoqeu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkiwhho.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtwbwzm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkebcwkp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwmutsg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdydszed.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsbingd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmedcom.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iifvnxay.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyptdenl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjivkroa.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yhovicco.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2viokiuoa.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2awpweatt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iqunxfyz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfbanfn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzrzikl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2marnrgfh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zyomcnqg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tumpbxhz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qyydfiii.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlvbgqq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jiruhevy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgryonu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrjyemp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdebfkju.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbbhhju.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2blqqmzzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oskshhfz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnpgnrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxnqsvu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcpbqxi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbvagph.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dspnyzlq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzcxzqk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qagvghqm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpqxhid.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcvssok.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2opdsgrtc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2scxviqdt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2elnxkrcf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nffcxyaz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bamkcbov.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhiimfz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2aprngyrq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyhvtil.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzhjviy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kldipzjb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcefenfn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdeshmg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnngmzc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fbukcyee.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpqduoy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xplmckad.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2atksrdmh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2grhoecre.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbstyhn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2clouqdql.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gikcmkpo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtqucpu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2aghedaso.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2npsrrarn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oorhvqtx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aioebuun.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnupkhde.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2henfuxfo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytapxjhx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2unhyiedi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uonvgxrt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dzamlznq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lavfdhjg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2izgqwvyz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2psvtzsfd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hueklwjk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yczegemf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxudqkwn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzhvabz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiytwwj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cumplgyy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvbhaqs.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkensry.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrefauu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgehlan.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gduydhgv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2woozvjov.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqnohsz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjzffwy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kdalnfmb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dbexhfec.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bobbnxuf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2glpalnll.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuyvytl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hygffndf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2khyjtwta.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yagbblxy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2enxikzbp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtedtig.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hadydjso.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwnddoo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyhmlxb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqdiljq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2awbjuuor.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeeqzst.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xvueegzb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkbmppx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhvhlrc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pprlwpne.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vuawbhbl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqvpzey.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yootvsnt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmdfgiq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wprvizop.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzzuyga.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpcqxxt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndexvuqf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2klpfrrok.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcymwtjd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xfafccnz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwrztpa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kjexessw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysidikay.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbupuoa.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2djckqote.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2djffkpdh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tktawvhi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2joywqznw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urgyqzcv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2glmxzqti.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdvjgyj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkielzn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfqiykf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qusjiowx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbajyhne.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtyjble.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqscvjyc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zlstpmps.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2encfzvdb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wclovvkh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2avscosfv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2thmjwfay.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2eqitaupb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhlcswj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuztqvsx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhkzrju.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnostohi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2goexekew.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkrgrfa.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuwekrh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqeqpkg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dggixwse.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfejajr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sotgjbud.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qalvsbkr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2itptsldm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpjdzqf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dsexuhjb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dygnwsno.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oczwnjai.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaqgxva.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbmllbk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uefmgevl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuufzdt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2drqludrf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqfbkrn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gojtlqco.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2spijndgu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrxfjpx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxmznhp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zacvmxee.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yvctuhsr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vejmjjte.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nvurzloi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwffjdsu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zajmqskm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yuudtmgf.html


<!-- 参考信息 -->