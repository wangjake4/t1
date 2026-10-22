代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyohvehg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlwhzln.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpthekgu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nnllpcby.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpaadub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdupofep.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyerkiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdofzhti.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2omvfgedd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsfjxbf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkpfyns.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtepsau.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lgehvhgf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcneiyqi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkuemzl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxhcdkh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjoalim.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhzmust.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtpcaxm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sldxgzdc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnwwerp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwpgilv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcflnva.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2scgcyndu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcywgbll.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnllklyt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpjlrja.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyltlydv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2khpnhlmx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhsuwmj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rekpviia.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oevodqpo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aaitevjr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyatequ.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2clflywul.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjcvwrf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqccvlz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngarsnhn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2szcjbgzv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvffvtri.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbthjek.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2urzwimkc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcxjvab.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsicczv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrfzrtf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uthhvtmi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bxovodxa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhtwnen.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2igcxnxxz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpfqohy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gzacdiql.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2taobystp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjokioh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxqhoob.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrvrtmj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2upupkten.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2solngdoe.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfwuwez.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qidizwtt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmusvngq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxricxp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaddfojs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrunxuo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2viikfbnz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnlhjkx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlzhhrs.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqqresg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xetnzxvi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgomypv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkgtksr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjyzasq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uznpncma.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnvubsl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2isogdgcg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2apzeaivr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaxmxtp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpxihpd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bsydfttd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvmradj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tggdkuvn.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2leaaqgwg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqfilpc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eiljvdhh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyyehpl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2knvujcrq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxzbwfz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqswaeqq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvwykaq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2usoizyrr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lejqrvno.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2equphgwa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxbsnaz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfttmqr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhlfnko.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaouuow.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxabkvjl.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dslqzmwn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkryrls.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeeykqu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bktmuvnf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2exwxwxoy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmzssvu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxouwrij.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipffwubp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzjnpms.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbrkwws.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqchvmx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbakuaat.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtomrwnq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdojilh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tavtvmfy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcwjzaw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qegccjeg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2snrixllr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vprpemcn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2awguhgnk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcbvcpl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gltjrmtd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsvnxvc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaysgcb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdghqtl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bqahjmqr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjkqjcg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fiifnoin.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdjeygn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbvkwlp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kburpylh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcwqook.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpaigzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2impwuiwb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dswumkzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dttedkoe.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbhabso.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyasfnq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvqxahc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzskzbl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwsnewt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqrkvxj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ahutugrw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjankuy.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2iklrezlp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2utacmvxf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2saphawjo.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdndxqhh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2exoecshi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmswosm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxmrpyk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2znxnvqmc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkojefn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sigfxnqa.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2krbobzpt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxakbym.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjbzyij.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxrcurl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2riaaafnh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xchnjitx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhasbcrh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhtfnwv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nrozfydx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfhomfz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ouztjpxe.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2auankvno.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2iinrvikm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2eohqouoj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2emxhvghd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wycoqsqc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2akhbqptg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpzlaal.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpnltlk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xokypwob.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfzhzmd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbztemi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2poqciflx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvxwzye.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2iygxcwwh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iozjavij.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2itaqfuyf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgxxvxw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpulujp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uedmpgkx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2warjkjod.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjniizz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdrmiiu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcjxiak.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvdaafb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nakjolzm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2eniqkify.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wijtcatb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nbycbgrw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tizduvku.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2inmdihlj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2licmkvga.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdpwzza.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2seypxkwu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zrztuegb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qnixypte.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjvjnmn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeoxfeu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmnkcqa.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcxyqxp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzemnzj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnljrzdk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bctjenll.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2omjykvve.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhgfdkn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oblngqbi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqcmagn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bpualfdt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cupyxwve.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvajovdg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dqftxdiq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzvogdq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjljlxe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xagcxdzf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfgfoqb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoxmkzc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjwkqpf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2etnmquni.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2brkxztiq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtximvi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnrglbh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqptdaws.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2flteoxka.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2avnoeorb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqosyub.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2figwfhge.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvpswkp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saktlwkl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xjehxipx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfnkrjc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuazifw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjpbtwa.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkaxgpe.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfymwbfg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oastopva.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmjbxfp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dkojnrsf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvpdicj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlejrqh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vetjfmxt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kjogauvf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdisftc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdmayfz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svtwdrle.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjwqjuy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvhshyl.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qrujopsd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2btmtkeho.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2geywkvqi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzzrmej.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jshwvzgu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwrnkdl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbhccxh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vplzeijd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ityquwrv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhhwgel.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiyugpl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnzgjly.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhhoqly.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2scogbktv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2edjmetii.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rojycyox.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qiruqdgk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2frtubxdr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlwbmbv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2edplovup.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdbojqd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmipurt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gldenywf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltitghuc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2izlmunje.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxzeorl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2meybrkkx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pojpiwaa.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zspjcbpq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2szhmlnzw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhzzvpo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2twclcbmi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctylfirz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifocznva.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmakegn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zotjfqez.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpoqoms.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpkarfo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2masutmev.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2irggruym.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zywcskgs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fizvdamp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyqhrcm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgiqqst.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjczgvy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yobfrcvd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjvsmbu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyeosxm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvifwez.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzigniv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2keorrasu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ompjsrzi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nyptvtnv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahykiofu.html


<!-- 参考信息 -->