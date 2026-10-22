代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcefkmse.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrfpfwa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvrxpqk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlfehcp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjhpjxo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxegzbox.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iswhmhpi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2esisnxgq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwlguic.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzxnful.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2iytwwtbg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2popnnrbx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2blelmpha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2poukeasw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjabtxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oubekuqi.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxoaqzq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qislgeof.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pabcvoan.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfzrbuw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuaahdo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrwjfie.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkhglny.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfxkfzf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uqejhewg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmftgki.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wovgpbjh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdshyyo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uogbhvnq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2exoflypr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkljzwl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrekhrek.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeyibxs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jocbpdjt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjzehvt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddopdprl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhdumox.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcidnktx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rprloqsw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhpoztd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2udeadzka.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2izeuxppv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsteheu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2finnjhwq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoufrup.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2prxyikxj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzzhszp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fybaiaxq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbyrfov.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoucays.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2brbevjah.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuatqqhj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2egvsuikn.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2msteyqdo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aaefftyy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2krumalaz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wphssqvv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrcmgln.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmyploz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfiuial.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcigtbx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2poxhevtf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2trjryaoj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2huhwhuwr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxgupoe.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysspxpqq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2coxysgfo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaioiipv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zehdbjjg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nriuqkck.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aydfcsce.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzzwphy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkjkvhd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvamutq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdggnrq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuptkyw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeoovcq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wznwriva.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2auefmnwk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kdylnxai.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2owbnipiy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhuwdrf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qasjccfb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2twqthvyh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsquuvd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wpycnoob.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afifljoh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeolxlu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgtlalx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkpvdym.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbchfkmp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2iupxtvyh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zugghwxx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwyglns.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfazneg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xnapnpbd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqmfqhn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtvjdqn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqfomav.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2njwjdvnh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzthrze.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2obezlmcw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnswhcz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zszshjsd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmdgyzc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjlnkkb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wewniqko.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktacovhm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiskbdn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sicfvkek.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2shisgenv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqgpjuz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxylegqz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svucfwcf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzvszsh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2njozbuug.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrxfibd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2diibobir.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nborgsnq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dojtjgjx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sszxxejf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mctedddl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdpmmou.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuolyvk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuunvztx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yneekvvu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsriarhg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gustovmr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzxszae.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvsojiu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2huvdsrol.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bpybusdg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfpxgjz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfupmbq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsjbbbz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnmavry.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdrqigo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kystjjne.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cblvbjrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgrioju.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2crdhepcc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoqnkdo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnlpvcs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aakqjhpn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2txhfuspd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2juwmtgbz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzbhbgp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2amouozvi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2inctxhka.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zeymsmyp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2objxxwap.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwfrnoh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaunior.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gatrocxn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yqniiizw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yjituvfs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2adwubtlx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yenanjvt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2feekwfqz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcuftzl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oggraonm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfsjqsr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtagnwv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwcekqj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhournj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgldxfkc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiaeexf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqblheac.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2laotrutp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjpknky.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hkezggje.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjfieau.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rapnmeee.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kofhvbjf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ktafrfmc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjaoqfc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mawafvxg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2srekfbzt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2acytfmls.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2llfqrfks.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2owcwdvwt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvbidws.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmepygo.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uptolefv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyvdqpj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsbijpx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgohfwf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqnvsxk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuqlcxk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyozeqg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmxmppn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtaxfjs.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2iozuacwf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rktszlyn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfbzdxi.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcbemgf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2msebsssy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnbpwrg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2awtucskg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yebojlrv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhsnxhh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2epduvvkj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfrnakn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2akyjziui.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tigxmtkd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2popdshzc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dtypthsw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdelxlg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2prtkpjfh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkytfuxo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmulvvw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2akgsccad.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqfepjy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2guzmquzd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2myxunhvo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2aklxkvdx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cciqnarw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyxlvtn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2imgpcoeb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2crnddcfh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2toamfcin.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuuqcwt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rggcktgz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcposiof.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwzvbun.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfivvzfs.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcjyefa.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnykgspq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xoosyrdo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knfxozxo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vojuadyb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlfnfav.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzbuqrm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqnstfl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrjsjtc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxflgtj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sthwpoth.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nhatmhiy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlybpjh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vribqcfz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iftsynzi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvydyugw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxdnjrg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2foknpyiw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ehncmdhm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2sspkcbgx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdyabgt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fklvanxn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtbxlku.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmbtqte.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2guyudcqz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lveoubru.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2npvchjwy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwidltwm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gctxioxo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hutqapeu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ueznbsno.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyxyknm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2etphpecj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqdqgef.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpppsjs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wujznylq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jespbdwp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikalogbi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmqbdnp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnzffsp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2umjubytc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lahqbhpz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfynsyz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mczmoseh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzeywkv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyhcqbk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhmxman.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwrmaqx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwlzzur.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmwjcck.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwwbjgl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlmeesr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2efeijplr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbjenrb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfjqfuq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pecwoapb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnlbhjn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhelvyv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2srfgaylv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkajlxpf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zntgcfkk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xufcidtd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2eznxwzut.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaetvpn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaewykw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2swfjdsfa.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbizmju.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvvdiiw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2udbdmqnx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyddtxi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmuihbc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uoarpoka.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkkndjl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgilejo.html


<!-- 参考信息 -->