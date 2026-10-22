代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2szlvenwx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2unntkbew.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhpavgp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnaqeyg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dxipzfsb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zsalzppy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgnujme.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gygvhyrg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2csmgsgij.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2klkxqpwd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2idkucoqx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tymasvka.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxxumlm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2foaexvmq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dulxsufg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqybugzr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bphplvlg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2eemadeyn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyawxpf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcwazaa.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2buelvxnx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeqpmnh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzkbzcf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqrxuui.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnwhltb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jedolivw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2byzbdwul.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdzqcgi.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqwmpnf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmlgzmv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzxnzgn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbfkpav.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2avsylvrb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsxsoxb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xckkgwkt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sevnhaog.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2azmewgnf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnobssfz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwaqyef.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2okdixqhx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dersbxwo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiznanv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkgdxat.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwekalh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gavavovb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mobhmktk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2loqxjdwz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyvfmxa.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rahezlpi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jejvrhct.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqfkmtc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpycvvmq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2noxwtzgk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuxdrix.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxstbhn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjqrevh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lruzhbkh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmceljeo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbrwfxg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tmixgslq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjycksa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnbbdqj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ssywffai.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2expfrrrw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nguiqvpz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tyukdcrm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmyfwiu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kepabqwy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2garhhice.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhjqdse.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnjrcrt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zeycneox.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2spqnomde.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhjlzbo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrcwhpu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiljgpg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dhafahor.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvtpkkq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhldnex.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfloxyoj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2duebyldz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoohfcip.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzvswvy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaezmoae.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2loucqzqh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeanoaf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2huaruiad.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scpgontj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgyckrl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdubzuvy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2urrwevyg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhbtdvy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2acxzyrzt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzmkipa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiplwnb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcryfxap.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgfzrhv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mkygvqtr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjukzdhv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdouzja.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzhzujd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2diagqndh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvzvfzs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsfotng.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hepgkffq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqzihqx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaocpwgi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zrucmcby.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmgnpva.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzotfen.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvamurll.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nouafhik.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2elkcvedv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoiwuaj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2itlbxynq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdzmucp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2txgfzsir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcgtqty.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvefdkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuxibog.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdzyklt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtyvwrt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2snpstsqq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhdxrvw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zoklquex.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2njhdumkn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ayftqrhq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvloyor.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fivajzpf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuftmcb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xhantcjd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2acrqwulx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyhwuhn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhokhlg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zyukgcdn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2arzcliye.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqrspuz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2epxigzfd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jixqoupk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfircdit.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qsukdkdi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhcjtft.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvqodiy.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ympgqgxl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2azcpjwqo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvudznni.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyspuvz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmfomcn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vejlwyzj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilccelzr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjhkeza.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2edpuslgh.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fesqobju.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaxlkve.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqzygpv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdtfxtn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ugatspdl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxecjojg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gecsnfpw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoodwxuv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2exjnksan.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rdirtuht.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoftbns.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfimrsnd.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwhjzoo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2joketiqc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcdlzlm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwbmfuy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zatekotr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoydtjt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzpcpqj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjbptrv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zplfohee.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpjozak.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoogmfs.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ntylcuak.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mhellwgb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zqarglpa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2urlyqunw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuiqrys.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtygpsg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjcrtjb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxosems.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2uxujyoar.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yetfzyhw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2atqbqibl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnpmjog.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2weanrdfz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzorllv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdrpiys.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ciygewtu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjircrnb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvhnuwy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnjzrsx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iomfqiwy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpvyayo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuayhur.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2oypqcnrp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzsftyt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtulmaip.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvdtdsv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tuogknmj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hundhawz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2djglipol.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtelnpw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2niisaotg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfvaxam.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoyfdwj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcghoag.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qckdtbrs.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2egpayrfk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2sosqrqjo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuvizkw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyfuruo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qclhumrq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvroodzl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxcifow.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ldomzgmi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2baakdnqh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhjsifm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhtohnz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdvmfqk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2capblnaz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmvxxte.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cssucrmn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjslhbef.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hwecjzam.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgosnpt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wtguqdow.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2poxflnte.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmnetqi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhcepmm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tyosnrcp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2imktfsew.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xcazhyhi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjvcmom.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yurpwjgw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xatxstxe.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdufmas.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztenvgav.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrflzyr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcltbvc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sztehwse.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpqapui.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mllhjhry.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzpgtcj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ewszjmea.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrggaggs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjhdebt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mchrhdpy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtxxrae.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yomsjsis.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2chvzvfiv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfwuqsd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hridgyqu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzamldzl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrptjym.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgsvere.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ighzqoew.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xccpaywp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpdgsmu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2trcsqyns.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmktxul.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2svmqjlvt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmjnbhn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2krzoyhsh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vztnegly.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2arjexoox.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hovhxnwq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzxybya.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2khjwcopr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvxacpx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wbargakz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjvjepc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rgydakqw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxvcuyi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yktvcahl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2atgeqplx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkgrtzd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qmafmvzj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqebhaz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgghcnp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuhuwyp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxpgnid.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyuyxuk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrbawpx.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2niwugmnp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnobxre.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2klqdegow.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvigqdh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvqrcvc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ctatrhww.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjtridv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2whbcyhkz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlghyhp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkrwdza.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbfskwq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2crrfwcqw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2baqbfkzd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmafkwms.html


<!-- 参考信息 -->