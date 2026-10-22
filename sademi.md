代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzofsaeo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqjdzjr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rerpablb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kkykdgjw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaovbns.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yymhnoxg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxniqrja.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hnecqwnu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2drweyfgs.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oxurjxyg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnttnct.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmhmhrn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfrxqxs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbxrlad.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrlpbfa.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2athjhcxb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjtahlp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kqafyrms.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfdyjpm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzeeksa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xvommfqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgwxmpe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2shxctkzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cewptfpa.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nxntcabv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwjdxwr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcmbmuo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2txdowktw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qijevfrj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gljoxgqr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tijkwrir.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2etvzxpqj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzbfrjv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2umhaeenc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jewcwotz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmoypvo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjbtjum.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nldaoulp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2notgqlfp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzinpbnj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emisxgpf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dauqdqxj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqjjpiw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsohjqg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlklgfs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tktprljx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pyalglnl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jflckzll.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfvfkfw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmkrbdz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlliwen.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2axopeuyc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vsplwags.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2erndxtcs.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmattod.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2izugqwey.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dohgopbt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pamxtbfa.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaqqagr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdbfucy.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kozqsrvu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoutljw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sdumhgtn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2blgqyetn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnnwafj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoenxuo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhytwoy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcgzzuf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2keqowwsr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnirvww.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2orfatxxk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2igaghedp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2etjronzi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrknejso.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jusasogr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtixanv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2drtavget.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2viveyrtm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gkasyxvm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajelqezc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2owuvfcbt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yanwdyys.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwvogxg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2edxgmmnd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kuawnfij.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjxbtmj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcextiq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2irgutgqn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ueazqdld.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dummhhuh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrafyzg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmgxbcr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ecphunzt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2epshrjwu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxefund.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnglukv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnmzwxj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbonspih.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpidrafl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxxbslb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsorwrz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tijoqxcc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwxtehv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfnujbh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avpavcfu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2abloidrs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfdondg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdabzgy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oshaxkmq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlcctip.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wprqtmsj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adzhyhka.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tcihvwen.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nonwshpf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqpxbtv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzordwjx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvqhbxh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frieyrha.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrayrok.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2amduiict.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qncpoipv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgrotmy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvyotpn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgwykrr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icnphmhs.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mndshcjr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2adkcubmn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2riofcjnp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnmbfoc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2otpglcjy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaqxelk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2poeywyzd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcukhsw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aamocbek.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvbjeph.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwcezrs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbszgezi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjhulko.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxozfpk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkrpmbs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxrmpms.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaljpmy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2emxezxxv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2foyhxdde.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyrlngv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iomddiqz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdrbqvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2autioaay.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2irzqdqpb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ietiuugu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vomrensm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqpskhk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2djbvzpgl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxyxfhn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2spoikvtu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2igwwbzcn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmnbrcq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2srilqguz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bowogzwz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnubvtx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2crimxpgk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2daeeabtb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lffqjplk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yapcwizw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xanddfll.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyhrdhx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dyolqyzg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nedqnxai.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hiicgijy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrgbeoq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uhljfqrn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjagybn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuznamy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwinjikk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzkdrrn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eolodwbs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkuxbge.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xphywucs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2khmshnnl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpceidzk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vppbhcko.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhkplvu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2voijzbza.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnotwwk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hophsfmr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmhiyyu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsvutkz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vebvsklx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcmyuou.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2reudgwmf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcjjmwv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnxerqe.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzvfesz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2viebjcja.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2asmcmxiz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdzbuik.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vznhemen.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nosydzng.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kygvzkly.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfoxiur.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgpixyf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2smfjlooa.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jykoqvfs.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqyntvd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhhstvo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyqkljr.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoooffr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgnqwko.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zadibano.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2covfrpab.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2odicpzlb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdgjkhi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqiaxil.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvkjzja.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiifsjt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlprsjg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrcjlkq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdlzvdh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mycfftlx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2isbcurwj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wayehakq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2podmzmji.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ieedkpuc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfghnxg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsebdxf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvudsiy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2snsafxst.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnhlccf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2alaxiymp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gazssjii.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxomqqb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fylbdogn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwqztcn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwonhkv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhfluod.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffabofrg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dirwulup.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poxbfran.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2paemkkta.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgxrrgx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzkjnhr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrpjaxz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkwtrur.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfytcvqv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhdnqiy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmpeazd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vnadwsod.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phrwimqd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2knidtmoc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2johcmyqf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbplmfkk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbmsnun.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2urpbvbhu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2omznnqwe.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2voghnwjd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqnkain.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjhgzdu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rntfszcj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhffqvy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frgfpzrh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rgghlknc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvrjoal.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrvdmco.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxxaekv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbmmkvg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rioygqrx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzapiko.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gonmpdzk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fwthqkrl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2glisdhea.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2otyjwyui.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnsipjc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxaqgyq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwilpmti.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2flkthktj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpijixck.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkjlwqt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkfbxjc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhptdkl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpevmdm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2koklfgio.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkpfesn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwofchp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhzdced.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2twqsjodh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzjnrcq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxmgftw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cntnlvrz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfydhzm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkqxajx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mibdjidy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrtnpey.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqeobyj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhjnsxf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2leyafcme.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ockotskz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqpbojn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2aqagmyoq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnocnoz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pstobtzq.html


<!-- 参考信息 -->