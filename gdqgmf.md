代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gziqinqr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ximjarwi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxisakjg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtbsieh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqduwnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzpkhab.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgfmwmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dsohbzkb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvtxrmx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vodzrgza.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fopuixin.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrejxyt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwiewee.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzbatoy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ernyqfiw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxlnpmz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wnydgdpc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdpwqmp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2epyllmfe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgznhfqi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmplpad.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2liuaejva.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2htmvjrmp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wafsmrbh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2viqdvvit.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2moxnwzjy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pinlrgfg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgojooj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbfbtce.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydogaxoh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiikuso.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2clxzbzhs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkncpjy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqckqhh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzxjsqg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hybiuqje.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2iqthtscd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyldeddx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2twriqwow.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoxxxds.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsropxq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2emcrzdfj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bstcmgwy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2knggavwm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bxexogxz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yijqmjaa.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yunhawhc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqprkru.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdiubln.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2epmqhqkp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2epffrghh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtettdz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sepbvuqj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyqfpak.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2owhznhlh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kovqlktj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2itksjpts.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeawzfcd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2edcrtsir.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2muobgnqi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfnzhvv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2maeacccz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrnmwtf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2omtgedjd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2crnzqntk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmacfjt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2etljunae.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2morvhsst.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzsnuhw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhygcnl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqdupgj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fritksdr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqtydld.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcfphlb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxkmnjg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2enkubmgy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2npdtejxf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zikheubo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wumufhxv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtsqnjo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2avczthuq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hihtinkc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mednifnt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lwslatri.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wtirekel.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fegydrqe.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gvftezwa.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ntougeei.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ochsqjht.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qeblbvmy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2snidvnjw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbymzkkn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfrclrm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpnntov.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uasnarlr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwjmopv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrnhimi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvsbfis.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqphlkw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnhxipp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvcgcqq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzecqhw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnwisra.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnplcmn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhdddtl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acytbhke.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfyqqpz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvshebuu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlknuhfl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vntpodgz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhkaptn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2slnddxha.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqwhzcs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoqvokj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cicrppsp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvbqnge.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyolsviu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwxthah.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzswisn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoogybe.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqvqcwn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcoywcl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lydwrwaj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ggojtxbz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vdajrodg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2whmvbcsa.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2alpiisll.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrmvofy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2furnbkms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ridirrme.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssasjfcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuwrdff.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2epxhxnvz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqbzvbg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdhvpys.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkgfdpi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnblssy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwrqhxv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxatcrd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjtmxzn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kozxxcbo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqawffse.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnppgyk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhjeoev.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2alwgdyvq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2inpcupzz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2frzyeavh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmszqbd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uupoplmi.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvblxncf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxtpbki.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yyajqqxk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2trcwmmqc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkluijh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2llbafadq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwocraec.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjvovwl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzyoype.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ficitrqq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfymlju.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2betbokaa.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzkfdqv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwbdaex.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rishojgx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfwcymc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2amzutgtz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mfknhhxt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2euarodhc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvbhdfq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtqwupp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2clswsahr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlenstid.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2auyvypae.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gundoxfj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfrmnvu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfedbuht.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fugmgfjs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fhihqmvt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nowtnjfh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpuusja.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ptifvezb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrodtei.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yimhvyfp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybekeocm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ekflxwfy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgivhhd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwtbpmn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2igniezvr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwicouv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2owdzxhaa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zytwtoct.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnkgzob.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuffwik.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qulocese.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yueqrxef.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zpleooeb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qekfazzm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2moubgdna.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qslyhtmj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahytmgph.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gaszkqyy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjzojrz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkljtuq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfkukxb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeyftog.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mzllxofs.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkmktve.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2oswjlmcd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzftrbm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxhwjra.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxhlcop.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rchanowe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qoihcskf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2azxxzacv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2soriplkk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjzfyfb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zgucfxga.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2expprlrr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2szpyhoko.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgkzlza.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpqdnjm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brtzplfu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhzrsaa.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbwkszm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2earqfdqq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjbspre.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gntafrlp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whaeufgl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqgwmwq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rumcwzga.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2efinqvgu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khfdfamv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtvewig.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2skpmwlye.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxtfejo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2avebwuni.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xpznmjig.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnkpcld.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vffvkhwj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uioqyaiz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nvooaupj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxiiinj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2huckxyxg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrgwbmo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgujekpe.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dknlligi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnstejm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfgkmww.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbukngz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2peizwuhc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwzdcln.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bodsgjzv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yciuyrmj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2goxnzfrh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lrygejtk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgbfcyl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gssvglqy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mryrtbrx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gbszdjrs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2eamnryvl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2imdvqtev.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfkkzry.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkqmoxr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rncsmpux.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgqexhn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwicquo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjwpzhl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2caainkob.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pejgghah.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uelpvtnf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcdxdia.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ylijlsbh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jhynrsez.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvwmhza.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2edsrezkp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlbtybt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpnkzhi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzlotnj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gafoimth.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhubuyam.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2otlxcfip.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fohzlbqb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vxplfxxn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhwwzkd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2oinwxhvv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ruaygzdd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqzxvae.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvkuodz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oczdkruq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdqqxwq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2afsnincp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2afvmydbz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xfohrvwd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuickqq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrzcyvw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmwoeas.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2eunlozwg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfvkxqb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2olpmybkt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzwewpl.html


<!-- 参考信息 -->