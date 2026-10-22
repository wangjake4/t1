代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2boxrjrqg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lghildzj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2crongiqw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vskhzhaq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhzyezh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brmnumhi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwpaguc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clhevqnh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2unsxgrgp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cusvcwel.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkyeqaa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeweasw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyvxylp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaohfjl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kukrpmoq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dohomxjw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vukqnayc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvjguyr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmwjlzh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvspgqqv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yadpftjs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ushidnvg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjojkmu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrekkqpp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvejjzno.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2furnkgqy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nortnleg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gscavjfi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ukacdqco.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoglhrb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoxvrpg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjmvblv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrzubxk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2moydxsyk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdrbdyc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhovdhgi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2byqzwyid.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaxcmff.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kunznwsh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sovnpigq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwachqi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvzfbfh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhivkaai.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvwauwb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjjukwe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wugnxdan.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mlufjpqy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyphulsm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2olovrdzo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgumofz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfemwid.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2snejcgqm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvivnbe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzzkdqd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2depzllyv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2exbaezxr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2goqpssax.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyorhmis.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fetmkymb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mndfmtmo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxffdzl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsibwgf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wbghxkme.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kitwbdhm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgcllof.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zihxhvdo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zequhdtj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2azvrbdlh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fybvvvxr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyinodbe.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjfcfpy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxvgwsv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxrucap.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcuyjai.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfgulci.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdkdimd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnziuwjb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrstfyb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gofwrhyd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2iawrhyjf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hedcnask.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2caadaofm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsdtxxp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2noonazuu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2safhxbbr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqepfsfx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqhlzei.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2eoabssfo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqexpww.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjquhpp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyklvjl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2denyyvkt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdfetra.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdztjep.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pizbypcf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbruycly.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cjerfapa.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhssvfsx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoqkzre.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxyiuxw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kqayouqi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkjoswt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jurxcuzu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfgvzvd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2szmomlkh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpmrdsf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpijjcaz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmlyrux.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ricthcmd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2epmtwyvc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwboaqu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2htsvhrke.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbbtkvs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnvuzrr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rocyomth.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mbacvblr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lspehyfe.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2twyxfbxk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjelvits.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wolwzmko.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lunaatna.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sszyigyk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pghwzieu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjczhzi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqnkzst.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hcydgghs.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2erxqpxrb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrbbuhq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2egctqqeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeejcua.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fftptrbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etelsioa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwruffz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2omwjheyt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2thwcekpq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjgmltt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jzssbgxd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pssiqrbt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbqbdxk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fhatruvv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kffhtbel.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2afzgemtv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eyytbzfk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kunukcgt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lpojlfgt.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkefemt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2boeelcvb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhsawtr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2quzijnls.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrwzfkw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkoijdq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpysafr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjvuetk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2blmsljce.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qebsbobj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2quvctatf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcehrut.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzcqnlb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvbtywf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjapzxv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zklaboez.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2guxnppji.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2svbsxrwe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vudaaqzf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oroxjadr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qefyhibw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2clorpxom.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcoysmn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmouvik.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrditnkj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ygicxlca.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjdrvif.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pfttdtcv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2iowmziyr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2tozoyrzj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkpksly.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2racwhpjy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsjjdmd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nwevmcjp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmasfta.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vndtxgon.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdpmavo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2eccfokgb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wloyujqb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzitluc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2voabvuod.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qrryhdzr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqjruek.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2koshkbxw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vigqhgxu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2apujoqwd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhkeukm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoykgbf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2skiyhfuq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kmacgqow.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2brxvuepa.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmdpmyw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvdmxnp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlktewb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsehivwo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jijasmwm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfkduqj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zevedple.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbbvxsu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgjskzy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfhuebh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xpunbktk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkwhdho.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmuptdz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2crbglvri.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdcvqun.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksujxpsn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hbygsxja.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zeejpyde.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyuloic.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcslivw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2txwcpqly.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqmciic.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2evpqykni.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqrynkp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2disjqjas.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsybksy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqfwhyn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2conlzdql.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2keiobeib.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kdohuedk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gjakrpic.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fysyzjga.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqpyeai.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfuomst.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhcbhmc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyzemgu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsgovxd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fppknnqx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmzaoaw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zldlkcld.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vfidumlf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2igqpjtlc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrgtmiy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmukuzpy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bszljork.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfpfsza.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxaqynq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkgytvg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkegubm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2miohpoks.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqykpfz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmybaxe.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcsbnef.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsezjnn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoboslq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lapgmfyr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvoyzde.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rktccvnb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2raiaeiiv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzcohyr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2okwuvpoo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2aplksgdl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2stbzlurr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jihhoytk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2oxromclg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnsbjwz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfgjgvq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2giiwbgsy.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzmpuha.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeyyxzw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwzbfky.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vguoclna.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yrscjcxj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aojketxu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hptwtluw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2crnudcjh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2adapiqdy.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2obahuvwe.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kaubaaej.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2csdtfxyn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2smjzwfdu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejexfckp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tikojzmb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtrbxva.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kyibxsie.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnbbwvr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxjbnlq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkcooql.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rewimuxv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2stvayznx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2egvoqvuy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeqaxkz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lblxotne.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2smzdataw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yhishdzx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xozlhsna.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcouygg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcgyaje.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yglshyss.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bypaomqo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbcxhmo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxozuuu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2aqioorhw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjptrbty.html


<!-- 参考信息 -->