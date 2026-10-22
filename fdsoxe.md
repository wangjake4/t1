代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnpmkhb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cikusdxw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2clriidkn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tmghvott.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aftocrfs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fceylzch.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uednqrmq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkhpikr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2axffqjuu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgovkoxi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfpqrel.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2skqglrig.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzjjiia.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nblyaifx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrstklz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifehtqnm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjqvzov.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvmnkxc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eloqtqnt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsefywwq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xuendoux.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbighauk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyzohxr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnxmckd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uduyiqwu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aopdnrzn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lssctemn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hecvpvyh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxirwpkm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzsbbzx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcncorv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxarknt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fngljfoo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2baclzuoc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oygqhfmb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxevxqwl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2quctqssi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdbaxza.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmsvauz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mkehtwcn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aoixvore.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zixxvuoe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcpiaik.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2edzvgbar.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkkqvuz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2twzhhvva.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2spkftwce.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmnygpw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2izepcusj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qznuiija.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjlunxx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtakrid.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdycynz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqfgggy.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxezzdx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xihqeikq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmlzryt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmcqjxz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqagalh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zybmsnrr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmqtfzh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cxikmypi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zecndhmj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bulimoyx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyufcba.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzavoity.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2baiaolyj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzioikr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iroafldv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2znlhgfzb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2emskcyuk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrtiunq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eyolgqft.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmkpngn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yditaqpr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbtkmgw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2naoqhrnq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxqlqkp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqfsbqg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxlzvrs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wksmawts.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2czdvquxt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqxpbob.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqmdrwa.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vewvfpag.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amakpjtq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgdrcmm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqptnxl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2idwgrjcz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unxzofbo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eildeofg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhpkpdg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfibaqfs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbesbph.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrvqdhb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaakjkvo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhcrszo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlidmke.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zalhmqqm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxqmfmu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyiykiw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlnpsry.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzlidft.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jmimacav.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2acwnamgf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwuslzj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2khdayspk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2flskkkdq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ganpvdra.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ekelvyqd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbkxiuk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2acgehygc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgknwmn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2juoovnxj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvbkrbh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwsqupg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2riawwinn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzpqmpb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dapcnziw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxniznkw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zneovhoj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2shjrcexm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmapiad.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsbsftt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2djpqmxyd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuvvqnt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkgfkcs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pktxusnr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtnouej.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoekpxv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2frecuunh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvagoqj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2efebsvhu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcbuljd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxcaxbu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kykygduw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsgzqgr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mniqlwch.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ywakoocl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnixljt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2facpliqz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvltnmil.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vywbifzr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfdbxtx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrpwhzh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbiyowy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiwotjt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wztjetqh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jszuuzgt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaqgjbh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpcnhsl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnodndhd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcbvrcq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2emcsqixq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2omouteni.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnwbccw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmcfqbp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrrxgyx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrtagoc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dddlwhrw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2osrtfbfy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2udirktmz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hhetofgj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoqgzaa.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dssijhqm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2csvefxaw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqvdrch.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvtqxwf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2juatictg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuufhtj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bohlpwwo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fugxerfk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gddetjbj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nstwncic.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqbaiwh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pssksdto.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgadvfa.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpixber.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lswiavia.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2anmzllnw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpnbcsq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjwstdl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrgaamr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2izvrxhcn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnxkaga.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwncvxch.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdepkyl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhrtpwr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xctidwzt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2trzkbwwr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rukvxoch.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcweduy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvadhkd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqeidkc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlbbszv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rdezpcxl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnebydf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2owyavuap.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hyawlptn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsencpm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlyidfd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zngusctq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjvsytt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgurtze.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrulbot.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrfruct.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhejohjy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzmcwga.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhkooxq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgcroxi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxgzabx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cdebimgd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tzouaokv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvaycqm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2exrkuzbr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llqhjehv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nboittno.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vpomibnf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2eyypudmo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnysxmd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqhplef.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkfpqso.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvbholw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2typmegya.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vicgxbue.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfzyndw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yvacgypr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2btbllopp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hazltrck.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xscgmoav.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mothnguw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eupjxntj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mghcuwuw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aktxdesq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxhloeo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2atofhhhl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnnqkcg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgygyxiw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2pdciqqeq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvrqmcm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmeoqal.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2woustcsc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yuucipsw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqofigww.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2krrcwgil.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvazegmt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjqzahh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2akkttzpk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2djqinvth.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2esjznigm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzgkbol.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yioxuxft.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zplhcive.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kykealpq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfeqjkp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2isajivxm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnuypnf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwjemps.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwophgz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcgalas.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hveuxbbp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnlkcaq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rnboivoj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ohezoheo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnotonj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhduorx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cofudibk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbcbrri.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvhuvvb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2yhreftef.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2otjrvjym.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeeszui.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwmortr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lfevfdoy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jprmoblr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkwnzpx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2wovnnqqd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdhfent.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcvuokw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pejfpcxx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2okcnsxgk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwexwrq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lguogblc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2exuwgvbo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2clvwsasy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2weuidifw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcvldji.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2swqcudrp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xsernmrz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ecehtliv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkkmsvp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdkhbyw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqvxuol.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpdgefr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcjqfqp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzbueow.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvrzhnl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhplswl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkwxarp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcorafp.html


<!-- 参考信息 -->