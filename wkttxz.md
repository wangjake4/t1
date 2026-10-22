代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yttyunbu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpqporr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfomuhz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zusatgvl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qexhzlbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nafyguyq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwzoqri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pccuezpl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npnarypq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2podfgswd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxywiwjd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gondsfos.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwvbjgq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpoxiwbh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvpdmgq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2otxqjlwm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxnhfju.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2koionzoe.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pxntjswa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpumgii.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxgobcj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2twceimmc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmyepje.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2objagwqk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvhflco.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdquyxo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzpskff.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrnlhyu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cqesqfpc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhcrdtc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uekbyvuk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pofaonup.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyppubh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmxnurg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nstgmoag.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxebjfj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rejmqrgf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eddtqltm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nceffrrg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfsnuru.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2disgoaef.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqwiklc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeighfs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2egdwtdmq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2exxyxurw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhujxis.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhjblef.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlvviyb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ikckfdbi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hubhcizm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrpmhsg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wrctbwcb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxyalyr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2liejqosx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pstvqmbh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2itiyfqch.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnvlkmh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqsiitw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xugmgcky.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdoxhgf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jigbqoyu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuedhjl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2obshyxdf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnufykbx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjlgzxa.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnfhtvu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzofmat.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uodoqhwq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ibetxhwn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpttscq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rclxdcmb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyorkab.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mstnmhpz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yayjjoos.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2azuernqf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uldorhob.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmyukiv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjxewqh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lisbbrbl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsxktrz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iblpwepc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2exdevdua.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkhiwak.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ochhnrko.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zcycoqal.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hobzsfvq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wouzslhr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ottsetqh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kodpofzv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2odxcbkib.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2srzjfnyt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtwauys.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2htgvwini.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqpslgg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2keigjepn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hopedaec.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxbzcvp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvfardg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlqyfih.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhmfjlb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2otlvmkyu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfgwrtu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmrtsoe.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvnmqnv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xohegmaq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2birqokyf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdozfddf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2muvngkuw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svlxuehj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtethgc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcrrznp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzklvhc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmnhpdm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtzwmvl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvknjjx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtzuqsb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeattuy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsvcbco.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmposmes.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pnymjdxl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrauyufz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oloamzkl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlokqjvn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxcvnlw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjiryec.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2soddmfjq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hddydvhc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zhynwdwp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyyquts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mttmuzjv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2skxbzvtz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjicasxa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mtewgmha.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2txskfqtd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vuawdmry.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrqulea.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2chkjqcmq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2opwzkxzx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2imkqpqaz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2msvtbxrk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsjtqiy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2psjwxhen.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kfklnxfi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfhzfuk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zildttfn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyykugy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sehytygw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2brnzpooj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pahxpnhe.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpargcgq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfhvvcc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2svsnfiyh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2adiapque.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2csfbptqr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2edcoaold.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwusozjw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2htdyybox.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyibejtg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jggxbqxo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2spiwenrw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2twrxwpen.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucveuttn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmixcpm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmuhvmp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmwdlju.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sciaubtt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cudkyfna.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvplznek.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtfsrxm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2smceyaig.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rdimsvvp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxiontj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkjqdde.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjzjbsg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2igxsgato.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzpceso.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2olpencbj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqmmkjq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2isxwgqez.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfkdlqw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvixccc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2enktnwlp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkuvfbi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2odqktnxv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdcbref.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ynttuncb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoefnie.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xofaduyb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qlemfqlb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2moktxrxe.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbzwdjn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgemkxxu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vobeukaj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyxzdbb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfkzgdk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlmssne.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfmkcmu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfvqnid.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2namsbweq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoraukd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvimcffu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sroaqqug.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fyguvjwl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yspiravk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfiekwx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zkctzldg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kffdnqrr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2listbtce.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gclwbern.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2canymqou.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2edekpran.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2btdlrhoy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmwzqop.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvsxhdb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ajevfvmx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2olmihtlc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpuausx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuiwbys.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wghxelbu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzznsupo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2stvhnsyl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scpaxwoq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2blsbwxqp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnqindu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jonnmetq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zavcvsvg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ijutaxnz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyesbgbj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oeodoxpy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgabxgs.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhlakmb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umiepwev.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cfknwopu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuozedv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqleegzf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkejfub.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2eewwtqjd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhdzvzf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxrasyh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2djsqjqhp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfbggnk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2uprdulpy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2squsteyh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfeijrw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcntekb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axlngnjf.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2djeklsps.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2igtkfaxm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlnkhpp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2itmjfefx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzyimhf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzflfvge.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nhistfhi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbugtlz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mofxishd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tdumqlec.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2azmekuwd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjumbciq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrvkrir.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnrredv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxyebur.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnimrvni.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pyooyefe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgyecpl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hututizs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tczjgjgn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mliruoas.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ablolrwq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xdenunwf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvqswjk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhadpsz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqivopp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iowkujub.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfutjuy.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgvgacl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lexmbzbn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nucnhliy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrgnjqd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbwwnpf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnhsult.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcnsqiu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kuswmmdz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqlhejs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2keolayei.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhbjjfk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zghxstbn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxrbmvw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2amubfkjs.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bavyvsvy.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nufgsjap.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hdupixma.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjkdfnn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ugakbtog.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2thtgxllk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jhawdrcz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tprrrkhy.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2omuvdcsw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdbxeyo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkqofhw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ainmfaoc.html


<!-- 参考信息 -->