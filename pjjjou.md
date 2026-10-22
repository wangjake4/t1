代发 wailian999

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bilwhspw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxcdipt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbckqtdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiwsvgk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fquyqovo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2voupicys.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xephmojx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ifblsmuk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjjcpuc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uogxcbzu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ixewsfan.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kufzndlk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mryupykl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlvvjhg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ubznisng.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkglztp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2myhezteg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2esozlaeh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lzodesdb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsqlbfo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zajiyzeh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dctkkssv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfeklsfn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kworykih.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2duzfkazr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqharyx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2occwjvqz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2shtjupwq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2baardiyt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmockhq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwtaqyw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvertuga.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2akjlbtht.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbxstep.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwmagpf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhriihav.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aanijiri.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lndylyaz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmafufzl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2znpnlxyf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmiitkc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnrxtyu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxfvvpu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuvfdxo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnarupt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2udmqyfkb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cerzgjjb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzizsoi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnevwks.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2furpumnb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2iagtmmix.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvnzleq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmejemy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2evomasls.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsdgtto.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaleqka.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2faqwoaev.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdqwotb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2evpldstp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgfjynn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2quiafuar.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmqfgfw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmsmpbq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfdxagw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjcprmw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxjwpmz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2whhdhyja.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dzukaobq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpfxige.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfjvabt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xizizwgg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvutevfr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ibezxfbq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bhosqdzi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmwdrxm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2izjycgyw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2salwwmzc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2doxsscef.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpnvlvf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2swfmuzws.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pwryzwsx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zufymtcy.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zykmjbbu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwksbnq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ddomnwpu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zfngklgx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2snjyqpvf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2adfvoiht.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fpraptjl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2coaixlza.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rknoechx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khnddayb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kczhpvab.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elhdeqra.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsjtygk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwedvcy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrkwoox.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwkavsc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qijzzrum.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pljrwtvz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkvtdrh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjplftq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmoywdv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkoxcvgh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uidiixhh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2typvtazx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eulouyfu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdmbnzh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgrpffe.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oipaqhxi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezssnqsj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2droxwycu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2damksiaz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dusxhhcx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmnndou.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2topskrnd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oibqrlst.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfwwmpi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvhcwhj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aokgqits.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlwqmrm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dknxnvrf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqupuiww.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrczovv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2aguzmsmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evswxlxe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbradxkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwbuuyp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rschhkno.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2unvbdxru.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzkunjw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2duvysfst.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2meagyhbw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkttjrs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ziinwxxl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2petovhxz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jocxopxw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxadhhk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqcdqjw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zroxixue.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqfoerf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaktriv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gruxpxfq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofubvvcg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gsivdkqb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgmvgmu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2exlrtveb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2amdtrbnd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuzfgbt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpyxnid.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2miofdxlf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqrmyys.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcrvlmh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wglfmqeh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2byqsbbai.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbddtsa.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xopbeacu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2foxaazbl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qyeosgwy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2munkntyt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2knhzfzfv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2raejunxh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ydonzrja.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggckqswu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbwragu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzbeutw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjxyxib.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yomoissj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2snftwqzm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtawhja.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzoztvx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqanlpph.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqriaau.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2edxokabu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxbmzua.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvezgaph.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2smfzsbxi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrwvmqy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnzxhhy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaewlfqt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mozdwpxf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjkzifc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbbaudd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hclcolzl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpylrvp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nybrokoz.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbwlyli.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uutrjnpn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvegvsb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoiqmcw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vprcbgcv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pimtlqeo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xusdtovm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtpugdm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fpollyxn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqwskwg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzurscin.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvknfvh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtfwtob.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2elsojjva.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzmxqnh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2etsavxck.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqdyeyz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkocynj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tvowhafs.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2swerugpi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pyziwkhz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwjtuei.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2flenfmib.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2crehscid.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfifuiv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpullca.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cknzthtj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2uclbgwoj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxwpmtw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cisvzrzi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbymjqh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkeofdt.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2irujmmjh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wrctbtwv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2txrxmhuy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2riuyaozq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yutytpjl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcdlcrk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqvnenb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2adbayzji.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgmtuml.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzmmzmm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfwwwxi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2grmnngyd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfqjjkb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjifnrfl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgypung.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjcfobw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbkrgvz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyphsnrn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wqetuviy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfpihfd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiufzxfo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqcruvj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2klvfeqry.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmreycke.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfsinqp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfpwwri.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxulhiv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ostlegbp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtuqade.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nazvtqtj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kohfvxrr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoimdwuk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jsixhuzq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2whdagzaf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uchnekvj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgrmcbm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sovyfnwu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cchlyvrd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmxicfb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqxrbwd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyrafku.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2icepawdj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnziscz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfagnkn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zxknzlpx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtqxprd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kmomiymy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2omkbobwn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2quvklvpf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuxebwf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lecabath.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zabjsoxu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxmxjyr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2padypckr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzdbuih.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnsqnek.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrorfei.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqfiofr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2togkvlhu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2niescbkq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqsieno.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bubuikwv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2outalord.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zifrukrv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqqnwww.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2noiswkkh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdhzvaj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2eypwgkkv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vucxenek.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmpmymn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kucmglde.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lkivrxjj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjfdjnp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuurkio.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mavutgow.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iisrhtdt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2snbarzwt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvcyoaq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpbhckf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qopqmlqe.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iwttbetd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjyfxmd.html


<!-- 参考信息 -->