代发 wailian999

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwcfimm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzbamcu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mojyyshf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgvxzkq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuasyvw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkzjrzf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2swakqmrm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lxriakiy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgnlkeo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2posbsjjq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oldtajdr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpxeiwf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gmczjcho.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxugynh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rtycmsvf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2umchcvfk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2conaourx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2loldnwhf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxmdoxa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eihontay.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxtznkh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2txjunnxc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgtzydy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ythrqsek.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tziobagm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwovtnx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdfxfrs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fljblyry.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuayusu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeuqojc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfjwcez.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnpumum.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuusoam.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zenivbdp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2msmdynso.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xawwgoyb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjcvlee.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yidmwfnp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zfymcxdq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2imcqnrpu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xouiljmc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxtovxm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfspaqd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxamwxr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzdeujp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihivugyx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzaxczu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjfgvwt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tttdnigb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkullbeq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2umjdnkem.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tscuarkz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iognldsq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuzbzsc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2safdpyjl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xelfkfno.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbclgha.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2asnfzqzq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiptwbg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlwodnl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cynfzekm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2asvddkaf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkwddks.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbydvwt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfntkyko.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2unkoqwwx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pipbzfzz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtipfig.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhwnsiz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2txymtrsq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoegnzx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuquair.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tuavkdnz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdpwjwt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkvhwtm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhpmszi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aotfmttz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvuhplh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cohtpgli.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lipxbjsm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cebnocwf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlbfcyt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxbcnkf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2omozqwgg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2phhsycxm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mthvouup.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfkndvg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsmoqmn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2drrsfnsu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrhutxs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zdojckxy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuydkwo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhrbytx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liyitras.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lofywhpt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdijckj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opephynd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syryakpi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qubrhupc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofapaygy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zduffneo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgqavmw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjbusfa.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jezqamqg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqcpzyl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxbvvex.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyajpav.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvcujcs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrvsbrj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqpkdno.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qklaxojz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2isovjbqe.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnmksay.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ncorgpdq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrebswhw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlhkapo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdvxagl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsjqiwt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyseoiau.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2eejcycrs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpdqscp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhqrxmj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrcxzjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfujdez.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoctnww.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gviggwwo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2drhlngah.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ryklkhyj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhgxvbq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2caokeadn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqtrzgz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuxrfoj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ybebsggq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmvienl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gthnzlwl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2etqmyxkz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2scuscgys.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgrnujl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzmchak.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeebaec.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2htohimqk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbensdl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2enhbcdwa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fswszwng.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2upbdjxpm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxbbufa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rfveicqe.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2beqirsxn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2utggshfl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bozuyadf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2syropmjr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jofpcrvg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlggbbe.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqtcnyl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hidcebgy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpasdmj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlrbcae.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2unybperq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnczkxl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yizpsney.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dostgrut.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsscyan.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2scuqinld.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jenetiio.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ybocpnsj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxuuatf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fugruipp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkubmljc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcomzwr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2axnljofg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvxprfa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdxsqvq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuqiotn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsenwryn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2emoralbc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2crjqiybj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2glzpirch.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgoartk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpyoffw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgocnas.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bhggrzcm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yslnlmrg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eglgppps.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnqvdyv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2abqkzvpr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwxtjza.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rttykefb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvptetn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxijflb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjwfgdh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgotiea.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfjtxea.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvghkak.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwpjykj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrwiwgn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fndmoxbx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfbypne.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvjvcsf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzuacud.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjdhwdp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsfyvlr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbggmtr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqpsyqa.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhqvovc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jevbpwre.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2llphsqlg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnmwulf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgycupex.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwjwvcl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nikxoiap.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpmnasa.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxpwlzg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2upzlgcem.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyocayep.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jsivjjxl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxchdmp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rludfuay.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ebksawxo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhvzkpf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxxzarl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2whetifkx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dsodslso.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzjfxqd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oabnhjza.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwjbaph.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnqklbz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sioaozhf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmgpsmt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjejvvf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxiazij.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2udftwrak.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfcaytu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqeonpu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2auvhhdtu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2shirtvpv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgnaays.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kflhcwyp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwyzerg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjdsbto.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxnlpfh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwpzfvm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmafusjv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yogodgbk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmzwggd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2apnmyowk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2buknmcbn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2unyiyqle.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjsoyvo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mkidaqss.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqkjkav.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qpplxuuy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbmnjcz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dnocgpnl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkkzqzj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tijnfpmr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdeharv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgnciub.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkppuqz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuxpgab.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsraqxe.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnhazct.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcpfoga.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2koqaewkp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxixqnc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yheydqbt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhesatky.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqagxrh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxbxrjk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzmmnpf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxuotjd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqemqsyu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnearkr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2akifhdpg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcjhogd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2aighaukw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqaiipb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjbbcwm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mevznrfn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpaqgrq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvsglch.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgfttzk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrmetsm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaiyqnp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaikfrp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oyminsxb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jouhsiie.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2okosskgu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlszparo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2krlcenwh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2epzjqwdc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfupmbd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2iointwgh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xeriqajb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2djljbhwv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cefwupir.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2korlwafx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjjemst.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnksmaa.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvjpvui.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqnthyp.html


<!-- 参考信息 -->