代发 wailian999

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwtiepw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxilzyd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgzprod.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uxplgezn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2adsacaoe.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2umwilvyf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjpdcym.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2opemqzgh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zaanvnzm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnbyznq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mnynunzc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjkcnhm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eujygoei.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vskdpina.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sappcddy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpacmhhd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2auuxritn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrbxzzc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgcgmla.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2joyricpk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhckijj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjglobit.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oefujdta.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnghynp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2czfcpuna.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rflkwwps.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zjimkcgs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmlxtuv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2agawfszy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrwahoq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yspcwnix.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkeuvvs.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwzmrrj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmojanb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqylhsz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsveouy.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbrpzlw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kihsniwj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2irlnekva.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pexjpzkz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jnejuzzr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqamqncc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tewejrsy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2usxcduad.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2malegasy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzpnqev.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bsptmpuu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2adoqdjnz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2djfmcijj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkvtcyb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2obqhtkeq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkbiitt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcuhbls.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjnyemw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeumnqt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2roygahdm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsfuobm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2sehxckuj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxsblni.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmwqlms.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrrcbvr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfqoovg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzxephw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtknijq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfjwhjd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhrpino.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmcvfuc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkbgwzf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lfptiesw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkvhnue.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gltsmbmo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pslfilgo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2koutjsau.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhciorov.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfalwtwd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwvepcq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqjareh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qznynnld.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmxfive.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pauhlamo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owaovcrx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sirgbdez.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrvmpcg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2osmwlmbq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dciaobrw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2siztvuev.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqakior.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vldxxska.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsjflvq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cumkzihn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hopowrrw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elxlbmjp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjvsgdg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvtedtz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2czosvhse.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fncmcmfd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdcrlnb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfadhfzr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqizkkqt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtlyvab.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrebvuq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2psdxmvhs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxqlvoi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdobnhsv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeswtrm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqhngsf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oynjiikq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkciqmp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmznsmuf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hgudibyp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqswlsd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkhgtyd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdywtgoy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kbawnhci.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmheycr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wwerlsam.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhtrugt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtzjsdt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qthrvwrh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfinklg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfvhdec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwyifvp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awxwdwtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsacfdl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqeqbaq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2drclydjm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vovksyti.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2losmugfn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeakvmk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcgarfm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbechni.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxspepi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaysome.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2srieqtsv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxnsyov.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwqndoq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgkewua.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdohztl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaouoea.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmcprkq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gthcxuza.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoeilgi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkhfkyq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nghxsqex.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbffpxt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtkeayz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gseqosxi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zirzjecr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwkbwsz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpnsppr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlhksay.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bziytdkl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2duupoxba.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxezkedz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpayqfh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2eooyypso.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmgxuwh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpbkatc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gluoztyj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uubjfogk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtwvnco.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoscpmjs.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xyceugqc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yigxtgzc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdyqowf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrcrkti.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lbieqrdp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2eervuedk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfadqoo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoxyaof.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuyifqz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyeyofx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2awshfjje.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2chibdvpc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdbhzuy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2znvvluxb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxojynu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqjlbii.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzdtkuq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnzuope.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2riyokqiw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvcqlii.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ropeginj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhbhbbq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgpfsje.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpndkkv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyjmhkx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhogjka.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2edqdaymq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2csjwkcnq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qmekvjsi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrsiqyc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjsmock.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uifbowes.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2stejghfb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2poztfrhy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2etvammlx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqljlha.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcgouej.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2idolfgho.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pbokcfsy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2shxlhycz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqrzyin.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgiamee.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ocptbzgv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xugltame.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbxiuyc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qndwbull.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvdbejh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lejrcsgx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpexngk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnpcxhp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agmecpkh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wehoelqd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfjusap.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuxzdze.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdzbnxn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrmdutx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2afmgalqh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrlpodb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2btzdtgcu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fwntgyqj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2epbsaeig.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swgsggrk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbsodhf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyxophx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gekmmpcq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtakzwi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhedwos.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxagzbm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cgooqotq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyjkiml.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vvixekft.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtvmpqw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdavjyl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgawjcgu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqukmtn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbivqjdz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnuszit.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgmdnrb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2loaahiom.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2apxcbliz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2iodzktla.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtjmwxc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ageysphs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgopgjgl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtszswp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnycvhmw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcgwucr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2inbyncne.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiexlaq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcptyiyp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2onaifspe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mllapwja.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2davfyofy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmkodrr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmejcrp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2imylawkd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqcesvn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfkyica.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmwtpow.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzgqhme.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdlnzwp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdmfwlb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oxosltql.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fggpgrgn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcubroo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlltzvb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zutzqqaq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsuokgf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxztenk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqxvrnq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ceytfdih.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjfzsog.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2beousrjl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgzhlnw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2somqjula.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoqkrsr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsikkhe.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2waqsbuxp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiouryt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2eccvnrbg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjscvvn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cuahhmtl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoyated.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zaywpqnr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2szvyodtw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfyqvnn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxhbxai.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvejyrqj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjncaio.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtntego.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ladrhrgc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgofvxv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyzebnt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvzlxua.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fumzxocx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpzbots.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkakapp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcazhqtb.html


<!-- 参考信息 -->