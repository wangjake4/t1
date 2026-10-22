代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsznbklj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbivpjrx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2aohwezah.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfqhzbu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fypwvbuz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2czqwurpn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlymbuq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaonucm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcylntm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fzumgtnh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrvftia.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lebxslgb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkjenjg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2llkrphul.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvaxvno.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2syxhzyye.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aheenugh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsqcfeu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxzndbd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2doclyovw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkclhen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aczgufbb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2muskunxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vadihpnk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiwhmyd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdxpmrc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2slvxxkao.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuvocdh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzcttkh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaqdnqo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2otpykkez.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzyotep.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2acmieosk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzpenyc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyaixoo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmecevmv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rikwoysv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mblwehwp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkgobhr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjacaecy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwiuvcy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vblwvmch.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwvoavk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkygmxsr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cseyynwl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jilcxkrz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeonqhc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdidcwf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgwrbpd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbmnvzw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdbfjxb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkiexoi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wksmapkg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsihtpph.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvpklzw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoqqdkz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rluaqhbx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xcquogcg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2chwddesu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxtiqge.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ioglabcs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvojret.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pazgcwbs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrugxefj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2btgobejf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mthftynu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2swqybyhc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkxecet.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhudlxpm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hygnckmg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2iskwisgl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvqhuay.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bhofhfsf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvijzal.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gkssneep.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnmkyrv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dsulwrjp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwrkyhs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2juvvhzjj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnwnfkv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ditzdbwo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuukxqz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmikfwc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoxqpwi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2quqenjrw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lynqbari.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbomivij.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2atxsfntl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcawbxh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyvvqyv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2miiwkrpf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2becohkqo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2yffmfkdp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xkipkomt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vigetvcr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwjqpsu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hmniaixp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iufootyy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mprdsjai.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrsmqhr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2maglglpu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjmyijv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcismdw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhcwzjz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2syuyjcar.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbspqvt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbxnpup.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrynnlh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgkfvur.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2onkuaqhr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkduujx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgstzfg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoigslm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwzhmss.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqiogbh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofixhwpl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2segivqsu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sforppev.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbdipli.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iouzueqh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkgaeaj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwewiune.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bskgffxc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwmdzpj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxxuqyp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2apnyanws.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsywwby.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfxhyiz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmknubm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwxeaqz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2intdrkyt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2puvwjrrq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfselida.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqnqdpj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2neyggmfp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvnxska.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfliqset.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cbytqgxu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jssvqbem.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxyihyd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhtyvzu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcdllzh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgsvyic.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dskkaywc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbpkgir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoapdxa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2klvwygpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnulklqz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiwkocy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqxydaw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcecxzf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhiqitz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fffqmwee.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcpisyu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2eedtrlgk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hdawlfii.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmmezln.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2euyvtokk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2suzcwckz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfuxtrr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dmizbyai.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2auxlejks.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwkblwx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zspvhleq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zccwfhht.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2whahecjl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqwsgkc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyeuxub.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdlsxtk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyjblly.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wcymgmfg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vskinylu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyixlll.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvbcmzk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvieiai.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kumkygkj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuzornr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2paelikbo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ifetpisp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdkknhf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwhnibp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmzyhnw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrnqjpa.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqfrxhi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2czxvxfeu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2isdconat.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2elkyjeng.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgnmzzs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfvjiev.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yoojjcxn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2novevkag.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xglftdvv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzdcrwk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ypubfwre.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2azowhdty.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2twvudqfa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxixrwp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeibxgr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kjixguyb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfbhdmm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbveiyj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxpuoov.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xmddjjym.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tmijacml.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cclsdjmq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhegofc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cztzndnl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wezlatao.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvbynfv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2icykhhkp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzlfhga.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kybgrlsv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsdvnlh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2oiocqrcl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwfeifu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqgpbja.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlotnrrs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2daiizalo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrsiyeb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltynwadj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2aenqfzea.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsyjoxj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbbgfiq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqnyrgz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nswvegwy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxwospx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sivzvthk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2berinuvi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uofldciy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhzmjdc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfxfycg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsmjpgg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeueiog.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptofuqki.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2txfgjofy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyagvuc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ethcwzlr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlvyofc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkebapg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pssxbppv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxykbfur.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rblmjssz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sldwkaas.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzttzent.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pembdrvf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2phgofswv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsuuptv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiqhbkp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qohnxxdz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlifltm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnfgpmc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrxwync.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wwibjfdl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfhvims.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyycgvf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzqopuu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ondodskf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2drriifgc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwgyfne.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oonbnvvb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2saiuuhvp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knjtplrn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcrexdh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wybeyotu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuccrjw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2duoniplp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mduhlosp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjmruxx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fptfgnwd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gknlagtg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxnrrsy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcplbgw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkjgabw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kstlvznf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnvvuyq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qkswbygv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2acianase.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2psyrgeqq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2usuyolkg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaunjcb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuaqono.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxidczoj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmhjwng.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2flfqjplk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrckrso.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bppqzsxt.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzxabhp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiviqvt.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2trmablrt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaqqrob.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2idktqavx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2trvonbng.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hihmyplx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwdfjuz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhaymhc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaahjlw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bystugqo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmeveqh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoqasdz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vblzuxpe.html


<!-- 参考信息 -->