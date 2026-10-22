代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcanlukr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcmzuta.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2izxrwcpb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeehwwg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2taejdiyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nswlxyiy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvdodgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2arxpscyn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dbetcvej.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvnmfsl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgbjtfn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzaimqo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2orxehwry.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eunqdxqs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2sfamlvct.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2higvwbzn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiqiqhu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgyyrvn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xijbfjts.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdofnuzg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oaybhiaw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjrzvmu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sontwfib.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttftjgya.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbczaok.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2unkwszyf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrlhttm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vljemsju.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmnviyz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2errxqpbg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeyrmcw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqbfnww.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2umtufbng.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjzwtsh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuuwvkd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2snifqoel.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hukxxadq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkmdkdt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etjmznky.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaugynm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxlejhh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2phtgiqqy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqrcihs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpwqvjm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kipchsgh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcpttaz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ahesspzx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2duhhipgu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bhomfsqh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsiwiet.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxyhdmc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtemmvy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuflivx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2blafxexj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gykopiah.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbjmkml.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2brgpgipz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gocspbfz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqaxnof.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqivdlvf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zgddvkjw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wszjlcxj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyaoaip.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrfuhwt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dflyaxvg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2stsdapah.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuoczeu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2psauxdtz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmxeymo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhviovbg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlsudvi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlljnkv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nitjtkrs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvqlmcd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzkbhwk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhjdxjy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2feddirzp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpcxhkh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkuuods.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ematxolz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2drvqodaw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2auabszxl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaguyvz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2eetzhnbz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdodmsw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2enjduqac.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2znznvrdt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tuttgmak.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnhocbx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2imzsptjt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhnbqmq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyqzzek.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2thoskwhj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqzhpye.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtqtrzs.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yccjnmjk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnreoxr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkqgpdd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjhnday.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brpnitbp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2durkwyxk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jminjmaz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxnamor.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhkzfvn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqwxbsb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlywbip.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmttdvot.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vavucjsd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmlliqx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2drboptqj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2osuzuiwg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvpgtob.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2srrojmpp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oggsluka.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2examwjls.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqddfip.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvqlbyp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sffzptdz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2akhfslvr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wycmdfqi.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yabvcams.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvwrkfz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2riovjgkg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvkbjyi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ghicxvug.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcafyta.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbowzanf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cqclrtvt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfbbqgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gftscpci.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djjrrhwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gznkzzhb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2irdbqivv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sctldrbi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2budueaho.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhrjvxw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsremyy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxioxhia.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zooojoks.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwhwygg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxltbmz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhynscp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ekapfaxd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyygwlj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqplngq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrfpykt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zthqsuit.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdrihpf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qybjtsop.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivukjtea.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvrrhnl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxpuobx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2obdvcksh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rerqmhpm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2txrylkxm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yofpkdvc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhqpegh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgfmbvy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuyszay.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnujtuh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pexlhiax.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2khqfkmzr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2sboflsgn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnivzuq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2piifffcm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzbceam.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bmohoqpk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbbyucb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2omipxseu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aifflepp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvxhsum.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwivhao.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2thgiieas.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrcatck.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2blqngtrl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqbtrsj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzxsakq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnqubyk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrousaa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bggoyzra.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnihdyo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckskhkbi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2auccrgrm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlntrhwr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuzaxyj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kcenlkac.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlrgcxu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2euvpwhew.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfmezia.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2svcxktwm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtuwhwb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjbzwsv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rvltgdte.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrlqkul.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbgaabl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ledeautc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbygbpp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2uayefewj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ygttzypl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdnuven.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zlturrtd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2buhevnaq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dflencne.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzvncuy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vizrkkck.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgyxgvs.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2quhasrqf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ajapndsr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcjysip.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvuusaz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lokkaoqa.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2klpeslst.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uvznzezk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgakupg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tphvpmqx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwbhtso.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2aochmsrk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmluelgg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orzolgeu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkikeek.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mutfvrke.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awumryow.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbbanox.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2slbnrtrq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtzifwi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2farmsrpg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kisuxeou.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plfrujij.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uizopubb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mxazstyh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjlzieq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysigiwxg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yotnvrfv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2acmvnxhm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpezncy.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfchmze.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkexkru.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xagwyybs.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjsqnez.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiksxee.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjkcgej.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqmnajy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtbsgac.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2guukosmw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2niygdgsi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcndnna.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjeyzmg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2domudodn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dtayhzer.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqsuolc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmcbrxm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqoywmq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkznkao.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrasssd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2oobdojzi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcuhkfw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2svupqlay.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ystuqlzh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2onvxswrg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmxljoc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdhzbfh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2khoifirp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfatjns.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvkcojh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuvqfff.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmogmtsl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vyculute.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhbaxws.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eayfbqyj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzabkps.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvjilbw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuifprn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnmdkcp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsbrtae.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpiccgk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2snnupilg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2snddctab.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjsxbis.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jetkhphy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrmltev.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zchfwgts.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ashchfvq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sjytgadv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2khkdqbcy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lcniqtkp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcmacnr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeizvad.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfpamwt.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2udufwmds.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxohhjs.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2czhwgcxm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfrytxc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgnahwt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkhsezw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2goboqaru.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kafjmmrl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vmedkemo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qfafdtza.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2huobxmlt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yeolxnfe.html


<!-- 参考信息 -->