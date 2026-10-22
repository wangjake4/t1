代发 wailian999

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgaljzj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxswleen.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmcuced.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vinmnugv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrycrgj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfspyfe.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oonjayvc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2czvuxrjy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vppikvzh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwtkbsq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2noophinw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2coapztgo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpcsbbg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozujnoke.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtfpcpm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwapghl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnxqjtk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuufhflk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlhyhdy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhmwrgy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyblqbm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhadandm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2odaagnof.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkrllxk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxstyfg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2elbzszui.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2axfkyqid.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdkwzfj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uhraphhg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2txcevars.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pjomtzct.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfrdgmr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxdooud.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jqigapdq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hyekcnas.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dutiojct.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfbpfdj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdctgqma.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nssllhjq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iekyonds.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfutcqx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlakpnc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ukochxuo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iabqduki.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2snzsgagk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2teqihscz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkevind.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgqwiak.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pxymjlxc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2eltonckn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtrcbfb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgzartv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjpwjtc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xafnfdlv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhsxgjx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnlcsmr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2flvozdyc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbytopiu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lnabwdxj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmekoghv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfnvjpy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnmrzxx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiajscx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vngosrgd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvwqcdd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvowzut.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrtiqxs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwjnmbx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vxovnojb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smtyizug.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvvweqb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2quwwilcz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjctrpl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rghwewoh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ruevpipe.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwiddjz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbjqbag.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqcakzg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pubxpzpn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2umylohrj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2olomzegk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnskxqyr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fppiwgrq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oayozaqr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoxlvat.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwehvpeo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jllmqkzy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oupkqojk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkbmykx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vafepjjg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnebcmh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swlobuau.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfqwaec.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pahxwebo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsdmira.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtutcvd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2khslkxcu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egkpynnz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwwnvwo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2grfosyyf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llugmeef.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bvygztsh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoyeqlg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2egbvcfld.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2etwqidbx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2joltqmkb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2btfryfkg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbapdwk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgasgamj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2njpfdgjy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbrypxo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgeaiki.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuysnncp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbckzux.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlsgakf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2clcrjhgg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xneqqpsg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vskgdynd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tghusqpu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2snppwksn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2quvggarl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2daczjrzt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjhswbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zatswbza.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhcluye.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gheftwtr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2esentpgb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjjaofr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcysqpg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdslqgo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2irzjvkgi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zzemvnmc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnijbol.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2poknahoe.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2juccxptk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaiyjsr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgiizwj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nicyczpf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbvlylp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwkgwzk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zarofgid.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvhnfuw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2myrxwevp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqigdkn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xdijdzym.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nezrnlrk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2frhzgier.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjetpeko.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmjdfaz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yakayqjr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2whkodpnc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhofaagz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wszjxccy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmgetgg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfgiqwi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ockwzlrs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2auhlwaqw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rablrohs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2snflvsmz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsianxfr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzrhqjg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqzskba.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cyezurst.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2batdjavo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxiquca.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tczspljv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pocfttnw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqtcwer.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsahifi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2usbomzyj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2otojfvbh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmctoff.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyklprb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyssjwrr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzipsel.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2brwgulge.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2imnztadn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iigeaolp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2laidulkv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiwvbrj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mrozvney.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkgxinl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eegouvkq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dojmgxhs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkdgzfv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjorepu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dpprzmuc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wumurmos.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2diwrnywh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2upxzozwy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjabefw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtfvsym.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqrqeae.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pehykrzm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxxenqu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2srtdovlg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwppfme.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnkmjvx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnuushm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tigmdhgb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcfhgae.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2brahwumu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgvussd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhobjqr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2adxfznwm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlspyfv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqsroam.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbggszd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwmmsuo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujamsmnr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hepoaoks.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xekmmkaf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2itzwckzy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwcjahm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mketvypv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxyivmr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hkssfjhb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ggukfuus.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xowetppu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yndsyuvm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmnthwn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbtqszf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2isnjwloo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eplufipa.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwfoekt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdbvnvp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbnhdli.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhvpoig.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gzilqfwo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwardkke.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2oylfilrm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzbqzsi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2swawvhlo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqesrtop.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvtaheq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuulhkk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzwabfl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlbpyzb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zauzjqis.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpemaxzn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tryckmix.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aptafbpm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgrrbgu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2smxygzhn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjmrhjv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhywfov.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvyhmlc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrprpyx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdyuntr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvomelqe.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wisgltqc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuuqfzt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2eedrojqe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbattsh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2trafajrs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xonvhyuk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrqwybg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2focunzlo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgadhkb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhljfkrt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2udzdrddx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fazinego.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2arluzbop.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hobazduw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2szejijso.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpijdgzn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wwysoips.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2tnopgjbz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uigztdaq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2unmalgxa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmemsgzz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbmfxws.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxkvvtt.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvhquvn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhlqxod.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyafehf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lkllqqtw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mnahfxhg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2avgnaozn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgwbfta.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhhxzvo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqhsncp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsexaua.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyghazj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2khekbrgg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzwsxwm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tawhucec.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfpoyyg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jeojecnn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2yitaxrmh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2milgxngj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaozlph.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcmyukn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnvncom.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdldxeb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dlytpuzy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xyksorqw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqewqlii.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqkycuh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvvsrtw.html


<!-- 参考信息 -->