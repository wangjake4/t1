代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2avfejbtv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwzaysp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2joesnoys.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhrimlo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqyhfuu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2utmdcigs.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaurqkb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbxudke.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuwqzns.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhzqvsk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2naqbwboi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzclrrin.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkkmsda.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgbvwut.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuwmnks.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2prbbwytt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qeopcoau.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzcycdr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzecvwk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcjwstq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyraogz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydruhlky.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhurviv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2piegliyj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2asiboark.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oolbysgw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mouhiidy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2osndvhid.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2laeddyhn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pfugftqr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hevroclx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnjgmyt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfarxfe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ashcrrlg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2laufekvb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmundyo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2urpinxqc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgeakbq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtlotam.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2spmistfk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvspsqtx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2quqwpaif.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlvuver.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzogdrf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qrptusfr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dikqharu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgidsdj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzynoih.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gitqhgjq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbokjhzl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvjdpta.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaxnlyz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtbnfgl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvtybrz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrvegca.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkqxtfo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fllkqzqv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eejpyahr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2prpsdgix.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvriypr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2oifiwauk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2geiogdai.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmkamfm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqtgtea.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfrgpay.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbptfir.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfycdfgm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuoevqx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjwnjjo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmzaicm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtthfve.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2feniaact.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cuipspni.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxskeewu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrqfoiv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2aliwxpdc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtkgpnz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfhtiki.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jytjblkg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzrhqpz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2potizsmw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfrtnff.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aybjhwzx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoogisq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2twcclsjd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guwxtfvd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wepafooe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiopdcw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlyfzcv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrdpjgn.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2blnbyqbv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiakmwbi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urtcrnbr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlgtnzv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urddimsp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cszeklqm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2maqfhiic.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2daejlrhq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2olmqyptv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2noxjprrr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhwhdys.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2khdbetux.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdgaapp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdmksnr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2boipzqlx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yzadgjrr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlezcsy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2neopqheu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfxyxvj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbccpaj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsleufm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2epwwznul.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wyijgcpb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2npcorfib.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eggduaxk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2evgapchf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxhrpmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szhevjqv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrxcrki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbqrxpu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxcisgy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2htuzqdlk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bootlpyv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2csqpfxat.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vidspcbx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2umfjmpmf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmiumuj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjkmffm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbhfnvh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjtmqug.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsrmbsn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyyqrif.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nugzxwkx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jumpcseq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrpazbt.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqrxneh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwmmkfv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqownbnd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wmppfslg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyyiftc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vghjvesu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjfwiul.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkijkss.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqmmesi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvhzqlz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdsenlq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tyilowpa.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynggksxv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvumdri.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nukuwpgq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjiudmd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2obwhojtp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hncurayt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2asqruwkt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdmfjwx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jilfpuov.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyjlylm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2btxvnode.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjhxysw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2sblwettj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2tssexqzx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cfddceeq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2agopcywy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlfcubo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmsnfdi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ndprfezw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsmbunf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjpvfab.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wbumqybj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2faphpzzo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nfetuezg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyzytul.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuvpztc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xdatiahl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqwxrmo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qknzupgu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wugtchuc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tygduymr.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvswoip.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfeyrjt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ojigsjuh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfctcgh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wqazgjyd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lqubspze.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnqvkzf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2iikhjggc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eohwvkqm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydejlbea.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcayakzn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuyoraq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pvamsbkx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfbvfxn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxrchpr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqrsjiz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2poikfzfe.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nferyksl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfhlgon.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2eatshugy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eknihxze.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lizvbulb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2afxhfygr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqvavwe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsoxcxi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zanukkbd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpvuumk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgpyuqo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2msrawwlx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wukcxymw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuwptle.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmbvpet.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtugveh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeosotb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yptcidyg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cezpmcvq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2onoamist.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bottymmw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2duwmyogm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpvymdf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2oiycjqhr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mupowroi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wilkeajy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhbcawl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phmdkjnm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uenxlchb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tspsklyq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nihzbwac.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvehsdd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2shxhikva.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxwpxae.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzxkeld.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2klmxrmfy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlcbgbk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzqufif.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiqjrvg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzcfnia.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynisujlq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yubovjdr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxkdjph.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qanvcawq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwhcqgy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lazicfsa.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyecmjqz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fckxtshd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnifvkbj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeouawk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cekgogyt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2srgudjij.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hboldfba.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpbxpfd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfwnzlg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuwmsfp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcdlboj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mipkcldm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2utdbjyor.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxbklfo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeeuaqk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfokfqh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxxilol.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2djvrmyez.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzhwtao.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iepahsrd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjkjwkw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cwggmiso.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nclnkaox.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dagewdpw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdijrsxw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uirwiyxe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxsqxbe.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnvtafg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zcftaysc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bngqphth.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbipxpkq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2upmelwql.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ypacsbtb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwuojls.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ggurbngi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeqzujx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vafopjga.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhtpxrr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pggnjges.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wndllosh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2entypwcm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgvcung.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrwldlz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qryhfylv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbhcgui.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2emauxdxg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivphvbkf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpmezgp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pahijecp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqeagsj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lilihthd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2inyyirmu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cktnmkfm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2klgzrpvv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gasbqbac.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvcyhbp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xumhvwga.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgibeanr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2awksaefn.html


<!-- 参考信息 -->