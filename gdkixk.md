代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2enczrupi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnfznun.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfipiqe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgppbjk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvddsiv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wqneowxw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxskdeft.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wjopvoib.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwosnjk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcveqxy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sldpbqtg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2muhdlyui.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzywzmt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2msptytbx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvybfydl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mddbokyt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqzjofk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2flfnjdhw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqixeqm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpvjyue.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2komfxgbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlqojrd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoanxir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvshcflv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yitkneys.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2onxptmen.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bruhpbkf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcchayz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxfujde.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jauzpymm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvnukur.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2codzqcdb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aqygfyzd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qyunmect.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aozhmpim.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbaqplf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqqtywm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqeatdx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkrfptq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkidmir.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usfkvngs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoizxngg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfoxclz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvissnq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fefyybou.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyumvfzm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vawrqdge.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yftxhhlx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzmhtkl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2syzgdesc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2emajrmco.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrourbje.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyluvio.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2soswatsf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvruzpm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueypzuiw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iacphymh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdveuin.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wruiqzub.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvfwwsl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2arrilkia.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2najghzfg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2krjeoiij.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2brozwmlw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yowjwsuh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cegwskuk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhlilxv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsixbui.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yitqiryd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrimwhsc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wslurzcy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jblpvdeh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkhdrjq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdgpvky.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqexjkp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsiuqpj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2osybsdda.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgrgnjr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiyemnt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2atbiwzdc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnqarzj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrsjjwq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlesktb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jobfejrm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2silsjbll.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxblfww.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwzsjce.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kyorgybk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfadtgsp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkjqapw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoypvkf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nstjfchn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyexcpi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmvddpp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xazarxeh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mvexqrjl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jeewzmmr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdzniff.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnondtrw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxbvsix.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnitevr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdflqvae.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jttvrnyr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2snautqyt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnulnhu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uaghjxzs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfobkrk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bukmjfcn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2evrnrvuy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeqqmye.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnsehgi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpllalam.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmwydni.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdejkrv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2adfbmgwq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxdyzrc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2diiqoehu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiuhggb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2akicwdyn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dirgaleq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smogbznz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbkccsp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzlaoqs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpiebya.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smjhxlva.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hbymhefs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbnjruh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wqayertc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2imhksvkn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaeokud.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zicpcxjd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oufbdmfp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2grrfbuvt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dhycwjfx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcchpsv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfahetj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrxpwwh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtqnwer.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdapxugy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjrxddj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwalbqs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ehndqxjw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmikioc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2uefrktlo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdoprbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwlcwvt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgzrlea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lohfwzwg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ousmcetc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zunelmny.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rssiqtgc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fivdnqjj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkkzkth.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuowcdq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrgghsj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyukobw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yblmsowc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2enzcrfbg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qudlphrr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcawsgyk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqsaxcr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgqulfn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqukghxu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2exrywftd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsrzcmk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xivrjjfp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgyxcnr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdhqknw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jcygzeav.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsyrqxc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpegmoi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgpxkga.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gxconxwe.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixazrstf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbfkfak.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaulbps.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgirezj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfknxsi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdosjrr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqufcny.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lscnkiei.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzinucw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2grgcnvbm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cswhfeyt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rbctfags.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dannpgqf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkchsdu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2busiasjf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2tnovkrhx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqsphvz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjgqyuc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2krpvmeds.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axijdkco.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkmhpdy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzfkmoa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tihfnlyj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qenlwayx.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjikhgq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lznzqoow.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpbjzxx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ufikmozq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzggvco.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmleikh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgcwiuv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ryejutbq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2frllqjzn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2afvzgywg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aksqsuoq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2adjaacnz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2loeeaain.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoqcosl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcmfvlp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mwppgjyq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2odnrpbdg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwiqeiw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoxwnjh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaubygz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwkmves.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xretmhjy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdtezte.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nwciykbg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mvivlqds.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkgzvcy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2euhhdxxl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2imowwqnw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjktneok.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfgmrnu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoqgaab.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjqruwa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2cyatkfci.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2velfaykv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxnitld.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ffieljnp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhklskjf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwxjhwi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2itazxcow.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2toawygkf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fevkeywv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2feizvydv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkrlhay.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qlysnqbf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rclcjgqo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wbswqknz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bilosadu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2alkwimsi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2espesvbm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqhrkrc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqddenn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyqbhxl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvoxvlw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2umuxxnnm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwyphfz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvumota.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqvokae.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2trqnupcu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2puxrxwfb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmcugyh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2msokmlun.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrpfolu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2remrikjk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqngnzh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2indbqjex.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoteapy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhxmcxp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kayrvmsn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrrxugx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bebwafwu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsjrbgy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdhkpdv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bggaktsz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2spcldrxp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2quhzybtc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdfdqch.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhnvdfd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2inlzalwk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2luhpmrsf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2puzssybm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrkcesi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjeybxk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jslkujat.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqailhp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pudtpweb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2edhvuqwo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbtlgzq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jitakglc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuoofxc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sifmfxaz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsdzrdu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyvyrpk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gffryigt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ooorkimh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cahmmbhb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tndvgyqp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvukpelw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzemjdj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2thxmeyjv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnifwqg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2tisoyoxf.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlnbofs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2trvyagcy.html


<!-- 参考信息 -->