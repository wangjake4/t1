代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnezjmei.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xjflxsjr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvzdklh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pyswdprk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kizeugla.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkaeaja.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdskhqcv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcxlrpv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vplkeluw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzgmfpm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2svupgotu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lmihbfdo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qelfklnz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ttexazlg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgczielx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgrjxdf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcidvli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmlliqj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbassius.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2geohqhvf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pitvkmbc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajarjjxx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoxcqkr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgfrwlv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvylwzs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2byhpblls.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvqncuf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qfybpahf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2suaswdyl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrxlqvr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmafiat.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfwbjtb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbhilaq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmzklbd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsqkvqf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2exytwacy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvlsbyi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2adcehbbk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2itzrcqpg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2frpdjxdp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2znyhlmld.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vabpgwgz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vymgaxkl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgatbqxu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpzjctb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwldhhh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2odqwlwnd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvimolti.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvvoxfb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpremtw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dljqyufp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqpoxsm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtnnrow.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rewczmrm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2twhsdwjo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zghnkram.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sesmzdvz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2taiyuxao.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjtvjov.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzvbfro.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2elkobuxp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwareov.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yudhmufo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlcmhfi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2leqeihtd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsevbmb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyrjmap.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhpneci.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvgywvg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmzumer.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qucqzfeb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxwdxgw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrdnkzf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2udyqvohd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmouqyg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmdujcv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2amwtkrgf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyefsodu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2aixdlokb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeumybg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgssglyf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgqosdt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2okwofmtm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkyjqdq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqrdudt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2maxssqyo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfmnnmj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdomzbob.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bivnjuow.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgeotfc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aarjkjgs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldphwkus.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaafgce.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeozfyb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfabmfk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dsctznxy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzlnagv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2smnbjbqq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqlbjkk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2baofzuno.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uekbzkkp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkxcgiq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2payivyfp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkghnuul.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2trmaayrg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbhoylr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsewlmk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdsozza.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrghdbg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuggzuc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkshvjj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnreyrza.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nqufvrtf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aetinhsi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2erfrtzal.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jagfxlar.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnyskty.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srdsgean.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2slkimqcn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcpkxro.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2watvcljw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tiewsdbk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecanbyjf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2opshzkcu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzxyzsw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtlznbc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwpixnw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cieodcwz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvshavnu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiolkvo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2anzxpzlq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yoivecrh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoengas.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqnzuen.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkqbunx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2phspqyrb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2huchpged.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qbosdsnr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rebhmrvg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sydrrxnw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2touuqkbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgxpotn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fahfagos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhfsloe.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpdphqd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2omtxxjzk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wasgltnj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjnjddy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dibrjbyc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2raoppcck.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vunovinl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcbnhdn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sqogziwd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtbaejh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgjjgsg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhcxcqm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnbsmfx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtizakb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rczstgyh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrtycdb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxypymf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2oevqrznj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvadsaj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2slwgpdab.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjczxma.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdquexlr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmnntrx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjrbamx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbinlda.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubddkepo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmaqobe.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tslnnshb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2maldusyv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2aypmmpyb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgfyreu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcatgkos.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiqazeu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzwzwsj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uitnircn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyupizxa.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gueyxfnj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggybkjey.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tqezcfrs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bngtivvj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlxqsmw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqydjxq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfnvpdk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqsfklq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqghlccw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2noqcnnjb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwuexrf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rndgrodr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaboebo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxbtulv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yvldaszr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2belppayf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrhwyzl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2gujdjjsf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwvdqwc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vypwegku.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vhskgvcu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2eoadtalm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cyicvnze.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibepvqkb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2irqdawam.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpyrcnw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qzynpwsp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iaygciem.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2aswhcltf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tistoxwd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cghjklpv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfavotb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgrzfrd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bycsamzh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aonnjqes.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjeygtc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uexwupzy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwillwk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lalxyfyu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kwurrntd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdmsqwu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2couyvljr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrhmqog.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2syopjsnx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhyoqgi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2iexxqotm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qjafwqln.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpravgt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2duwuxsnv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwxafmu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxdpbvj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwuccjg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hfilwgzk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iydglwid.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgksrit.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hsetymgo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vqertpeh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmdapzw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ejprbsrh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnmdbzx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuozray.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdevvbz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqxprpf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnesbcpk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmvbabo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxgzyzm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqszkstz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yifehfkv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vswwfoba.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2atgmgiam.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2anxfcwpu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cajgujqw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmoyswd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzrjgmt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbwedmb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etvvjkly.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyquyfh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbquxuh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsmgghf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bucsrelb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzvuusj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbzhhyl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwtrmet.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvctytnf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfcnnkx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqczdhw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dalofyia.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlovlmhq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2otihtyrr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyppyma.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkfbrem.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xojvzizm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2frynytdc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2djtmhnin.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hduajqdq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2merkxxhu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfzetfz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2booxygjy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rukspxyu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyslygw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cczettcw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgrpxlk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nnazcpby.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bihvlwgc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgvmtku.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2agpbwovv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hgebclpy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzbxozx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gaflffxh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdczgyyr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnbigvy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjqurrs.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhvjfrj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2yamcviya.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yggzroll.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2isjxkmvg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdxnefl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2atpmoeku.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgpksqo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2oybgjmxa.html


<!-- 参考信息 -->