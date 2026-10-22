代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjvklew.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeinvte.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfxfgkj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmnkzen.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnjlbrm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxiptvz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xycxpnru.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfyxzee.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrqvrne.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2igbnbzzf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2didddzdh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvpvkjm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnubhni.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnkzawe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wafbibnp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iefvuqjh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkiieho.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcqwzop.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xexwkfqd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pypavuwq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjuadlu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bajmvefu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpnqbnu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkllvqj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zucuyxqe.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2alrjandp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kaonpvew.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xueduhqp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgygxsp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmtejss.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dcidxwze.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqkpvym.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2llkmahmz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqggfqug.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2thxxclpv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tscphcry.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgjdlmz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2javumwoh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2elruoasd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfikirgf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2umjbzxrf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wubjhqcx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2garraeht.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgusfgr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvczesw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmpjyxs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcjlmrq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbveumhs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdcerla.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjyccsa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxrdpzd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2llxgoefu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhnwghj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2labrpfsd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkmloke.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2afxhepgj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfawypm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpaajxe.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpkvujj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuuprru.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hscrqdvc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dessnkda.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dldjdxbw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wadwbzlx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hwajwzql.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgyjjtm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlqvqhq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rixljwkq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2duxntshw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2caauswuq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwvdbyw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ashighzd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtpitkx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ljarqmxx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgtvibl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2chpfbllo.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpkvlbe.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwmlxgn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkbqfvk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvesznv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjqcgwn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyflugqk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmmrxsg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnuvxof.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqzgjka.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlayrzs.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mraotlrv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwewlrgj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kosbfsfc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvauxan.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fovmqjfg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2azqrshle.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmylreln.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwlkmfk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkqaezq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azkummki.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjypkfv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2crdwoxut.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruukdfot.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fycvatcl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2axgpgejy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aosyifjb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2crjnhgcq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wetqdeux.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhulqxw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uirzmavq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eltrmzgy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jflhbpyi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqwtnmt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yiywzkcw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsselpn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lclvfinu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wswhgjme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nooytnea.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2soypprpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2voxqzsji.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2osrsifsn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2msuaiamj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqdggey.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ifllwjjv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nlianeif.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lboyqsxr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zhppdsmf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gybzynjd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gaajfyts.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sttrxzsn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tmndqsex.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2feujfgwu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhevvor.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbkqtdp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iezclooe.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jaouccfc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdkotwx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzuvtqc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kgonlhun.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxwhxtl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2brfzshqi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbloceu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhkczih.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fanxcvlu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzevfhxw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2olcxvykf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tczfgkpn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbdpnfr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2femqwepf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdygifbi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqkxogn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkldfhc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlnsnpc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuulglf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrjgrhn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iglajzhn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxhxleb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2djfkkddb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfqaqup.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2alqsvrce.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2exbyolgb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2akqywhmj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2iovnryxj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2norulfio.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuritld.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2immhmdqo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzxrsqo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nejwlgrc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqnsgvi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuohqinw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeyvelq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcaegqo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrjbtiq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2udfzobqo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ttblfumj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jdisgojp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kftvxdzv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zxloetfa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfjegml.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeavhqg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xqahgqow.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ncornjcc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bplwccqh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjwqrhx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qggclszy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbupnybi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqqunxl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpvceqr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxvpybs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lshmyfks.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hubseyfu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2agsoubxt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrgsxww.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2niqthmft.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjiliye.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbhvrnu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gcodhmqo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2keixyhfy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdrhlhr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2evtujppy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdykkmu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwagfrz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2awwxphem.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnbfvkn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ivosjhte.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2djqvupsg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2amznnjyj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoxueie.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdktszj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bibqfivx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2manllric.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2aznunfsa.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ekruevti.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2exizknmy.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eovicmdu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzwjmvl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rowawhev.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2thxciwwq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ektslwia.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byjwvvlg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ratldvaw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjirbyin.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bflptwtn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2effqctgi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkuezti.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkiblaz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiaufar.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvlgbhz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxbknry.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2epxgcaqi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcuaplj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2anyitmcl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoyzwlw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kngpqznv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rbufsjst.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgblvvid.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnasdcs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2igvervyo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wbibtewk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2anmicejs.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbzjueg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlnlcdw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqyjyww.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbkjdzf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfhtcjv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeiiaxm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcdhohm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2inpvhytg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2oiplbyxz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2amsrmpbm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzflrct.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjekqrpr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hyirldxl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hutekfrj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yieocmmy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2geluqgtt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbbcogn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2htbnjfcm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvhghaw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2awwyjdey.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sntgdrhj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uodqmhsl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fwanupwd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaimjcz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cwduuado.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2swxyyivy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrlpbnf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdnwhxj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgnssqz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvrbgxw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmraxcj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwffrvna.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fadjdcfv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wubbncxj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyktbvn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2splxglgm.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjmbpjz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqpofvp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kyynzind.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xesbjkll.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ulptdhhn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhdlkpe.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mruzpcjh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lenapnok.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nobdrwes.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2klijfxnb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2npdhuwwy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyrqntg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mebgbjvg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2sifsvqpf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xrebawlp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpywafd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wsltvhqp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2penbaidy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhetvub.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcukttk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fknfadzd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oznrzwdk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gfibbvie.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbbwagv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiqtfrg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnuszdr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2edmxnrvz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcoasxg.html


<!-- 参考信息 -->