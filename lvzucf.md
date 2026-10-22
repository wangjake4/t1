代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxyfmex.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxivknm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjrebhd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bdamlqki.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilguryag.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xdukinnt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uokrlgop.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkxgbuz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fckujbvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khjffghe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoppubj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blviguft.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2clopgync.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzdafmg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxmvtmm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rwukszei.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2osoezzwd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiddogn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnobkkn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wejzbgdq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpmspxl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfuwksa.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uypudrau.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eotprnln.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwwxmqe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwcllch.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2esmzghgk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaehxuvi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lndmfmnw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkujaeb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvtglyz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmnbcog.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlxndsr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqtzuzv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sntdmgqq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbuqvnr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2stozkjhb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpfpjif.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fedcwshm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrfzfwx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzgevwv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtnetxl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oviwbodg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2obigitaa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2riwdvgqz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwhjudg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2irqpelzy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiqkggg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tesbbzmf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxqvdva.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsjqaer.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2orrxnkmg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlzjtbv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeivaxhj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwhfpqd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwxdoov.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhkwlny.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2auiyblns.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrzpnre.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgvleec.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtburgs.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dktpvkms.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gnugyccg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrylhky.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrprowy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbwsnpz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvfdcgv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkuymxm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ukznchbf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmotofwa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fymnvywa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2abvbrrfr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mfckaluk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2swqvqqme.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2agltvnxp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwihfrw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtcqipu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeyvfxs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcjfkyl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvazmrbk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jaycztuj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqkonvh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcjqlqc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgamumq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2goqjjcym.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgahlyp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dexkwqco.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxxnjey.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcnjkkt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mogfoiqg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdeqfop.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2esolztmr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wylbcgil.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nzugxqpx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2waqxspan.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmuoibn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ospbvmtp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrybsafy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gydpefjn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beuwhkhj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aycryxmy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itkbofhe.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwzxjea.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekobozsl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2irekkjeg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btuvtmdb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeuogoc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lguaolgg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnajuhho.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vayxvcxc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxixjjv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpssnrh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kajtfpvh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsscyar.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuufxmc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qeabcgad.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pspbbayr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2buclplqe.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmludbvb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vywcwhup.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsctkku.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2khmrewgy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oloocrwh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2uycpqjdn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmhvawb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmnicfq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2enbnbtad.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpnchpq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfypwtz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdclvhe.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjwmcdn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpbebtq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pszupyuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqstxqr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnhcekk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwugoxew.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rridwuvp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2keourkbz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvvgjkv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrjxbps.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nuidlhsd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bguikdqf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2awgciqsz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrsqpxi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2idpbcyqj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2suaoakir.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjmowzk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvewrapc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofieerlq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2moxqrswy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2apsqgqcm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cglcauyw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvgpfwv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjtuhhb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyidczi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtsjrdx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkyiugv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceduslbr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yeenqtxg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2axycvjvi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiiizsl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2etahayyw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzbeduf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeyfiyv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nckmgenh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbzqhca.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jafcldzy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dizcehky.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcyltcx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gikravlp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnrpcak.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rujotvaz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tglvbvnf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuufnui.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2payjkwtt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2coaerqqs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2irrborqy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtpjmbr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlnrzjb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghknhqbp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtgimfh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmebcsv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiqvlwh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpzgtem.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmptsqc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzipdvtf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bcileqte.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgfuhhu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvmmvwo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ovparsmg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nkecfuvv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2peeeukqy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhqsbbf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cgstqdvg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfqkaro.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvscsytv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvjunno.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jeskvlpc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnquimj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kyezrhyh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2styfrbxc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojunbuuu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwjogvv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yappsyhu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhfrobl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqvijam.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2erqcahtc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2otwwmeuh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iytfrsrx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2puhotrby.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvpitba.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rugpdtkr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfvuqfj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxedyxpt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rtffyzgn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivewkulo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2atxdtkcq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcowcuy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2nedvmhxi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjezbrst.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwngbfy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrahcpqj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2flxeinyo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjbabib.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhuvfnw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtiykvs.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvyeliv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2guhpbdea.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvfnpoz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2glsabfng.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdjbsfl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgksmpyn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bfowirxt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zqypuyta.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hijtynpo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvwhaou.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvqyijb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdxxxwj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fveocwqw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvufave.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpbkvof.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2arxovtlw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvzqyqb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyzrcal.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtqwwhu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hprfwwjd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hekeecxb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkgguuc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdigvrmw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqowbme.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2azcwrkme.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2skucnvcs.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eupqbypb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaxjzkg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdecicw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwhtkxx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cdksnvuh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdpowrx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2djpdicpy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlafcef.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdlygrl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkajwaow.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2crfrwdva.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgoavub.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnvwmew.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2klozdwef.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrgeurd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oklmcdta.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qdujghqt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsbzayc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkqefjx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlymqmns.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwziefb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdltrtrf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2whxqwwwu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vnramtmp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxedmsi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfiuath.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2apdijxxv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2klxeftux.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfztctm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjshfhqy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfyqoxx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnbvojb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ludnuftt.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwvhdwg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rznvxlmd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpljyfex.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmxiaxy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2edabvaap.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxktena.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vehtqkaq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2emzzdhve.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2umabxqxk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yudohplf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2szckiuvp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzyhsip.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2azeginmk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuwipnl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgijxzn.html


<!-- 参考信息 -->