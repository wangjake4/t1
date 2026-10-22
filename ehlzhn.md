代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qjliiahs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxzgsid.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtezrewz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyejogzx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeeyxef.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiyhbox.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2suhnsnul.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fkozvxau.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwgpciq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pssaxvqn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mwojngoh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvznrbx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luzhosof.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zklxqqnl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmfmpbh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hydxuefk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuumxed.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxqiahb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkddwwa.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bketivpy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycftcnje.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlwtbje.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgwanvz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ribitfmz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmvfuur.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcbpqer.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvenpgbd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsuvzsy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlmklih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnfpiyb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hatdfvdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfmogpm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvmpjlo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzxtqkz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyctqptl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vubyqtoo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2otfqoxqj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ossgvwpp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjfhxbf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxizgff.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2urhykumr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgbdxkk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyurgns.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaqhnaq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2emaeidfv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhxfcjk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mempibpm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2veisgyci.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxatgndy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhobakvx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggygyhrs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhojesv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2anwxkmef.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpiysch.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2exxyecgk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vukvkufj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qiolegpc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlnfzes.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvbgusd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmpneim.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgvjgdw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjmcekr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtcjgmq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwloufe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oocobkqu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2snpghrxs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoltrsk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2folxcpip.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2crcbljyb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrxsaub.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2odegexxw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzgaumt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2prcvasxd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqvjzie.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsaivfp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xywagsum.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uveaevmc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hutwqyrr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpthlld.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrlxnbm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2biohfjzz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ircfnqus.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2igbkavfo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dywhdtud.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fukeutyv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pikudzxa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kifcxnqi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqfkntr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zqswkttd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wepifbdn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqjttpq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzwehoi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sommpgia.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcefhiyt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qannwipw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtdaavf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2peykvwzh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dczhwrff.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2psxfarnq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdowbalf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2espvlxoj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2asbxygxb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjxwngn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvqqnwd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uljpkfyt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxpaphc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaktsuk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2eekwlnbu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2prwrsylu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2agoreyoe.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyyjucp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkwudmy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrqdqzw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxiqdpx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hojlxdcz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2whbyztya.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mudmemkb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihneobro.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfykhdn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhynhbl.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaaoncg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdxiytr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hiurhucl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nveytqfu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsvzuxj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhytgazh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpffegi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioradcaw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oforwbus.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjjfyip.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jommxwhi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2juyjqlsi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aseukeag.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmwumpv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzlbmgg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvqvkba.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sacdkeqm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqftvzpc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtuqyhd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sijztapd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2degwgawo.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdduoww.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmmvuqb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mzripowb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fodvhlhi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wmppaghb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnnziih.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uddizfgi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcruixc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdbrxgf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhjfyed.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbyoqlv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2djfivnin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oczmedmm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qiinpsog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlchiva.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqlfrsw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcdqbto.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2itduccwo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wugfgopv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqfoldp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvevkkmg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbcxiwu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjfiztq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoonpxt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiuzbrv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uzalkrer.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfvefxl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2upgpmxtw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrewpsib.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oabwhwfk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsmlbww.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2iydowyzg.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ladyjagb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zwayuipm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ikerlpgj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2onuufnmd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qugtannk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jibjrsuk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2chsnirbw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2atrhxaoo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzqxwdy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dtomhksw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdunrqig.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyczxqn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyswmoy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ankvaohv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqprhxy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sndeqwvy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiovvppg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fydibjil.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpudoxdu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yftpodvf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxpzvee.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsftula.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rohefgvt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyonjwn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ugksgvef.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmgdkoz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpvqcgb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnfnwfv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2txtctwnl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmurtyb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2egnvocsa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sythaxbv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nisfnnfp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2siwfdguv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrckeba.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2grbgfesu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hdinqzfd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmlyapu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xahwwoip.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gscmmwfo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuqdkci.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsxyxep.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkslclv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvwccvf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jmocxbas.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtazzet.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdobzzv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2adbpamho.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwniuhgp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfawwfw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzuipnn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyilntg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jprxxyjr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvsawjx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmaegpd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxktrwa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fueuojkr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdzkpgi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gcorleux.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zuegpihu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2biiuqbxc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjbfgon.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpkvyqo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaefyex.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzorduf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2owzyngog.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaysxfo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2svfhkhwp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nepogode.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqfydvc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvygepa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjlarmv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2antviifo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcwjbsq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pjebkzus.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzdvciy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdseefi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlshjoo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omoltzkf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdstqwq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pewdplrb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yeexnwgc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apybmcgp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkwvhih.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcyznez.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdhuczi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfnxkwx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hruihxvm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2aaamdexq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vddjaigs.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdmrbhr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iowhkfnp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjyvdnn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2emsvfsef.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcvbsce.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwqzjvd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvatttv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpwvegt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhuwxbn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsmdnnt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsotilkf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfmjppi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzectko.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2znxnwosb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2duvrpnps.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaisbbz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zudzevmh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqsmghe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvwttzf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzigdgx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvommui.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2szbohqul.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2faowxabz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtquqjv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnberza.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ehujlaad.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsfswdu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yswvxujc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmxrcck.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fraknnhy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qytbvpad.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xxktcwyg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jerzwfdo.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uxytsalx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbschtya.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjmtzra.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbmwhxq.html


<!-- 参考信息 -->