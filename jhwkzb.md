代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlvaoer.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2immsbqjp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dteqmufc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrujczx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrohoot.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxggjsj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxxdvjd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuewana.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwbtmyb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dliifxgn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxoccvs.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2atcfgiqb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rldzcgnd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgsamfz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmkioqp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlkwkjb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mesovnri.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiqwfqj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mbubjosy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuyiftm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gojbzwlz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzhqocx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjjrjwv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfhvxxl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2txzqijwi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhsbtzy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kblwldmc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsckzmt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyvtgmf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzgjshi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiadcnb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiplbft.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2clxgskfs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2elzdzgoc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpdyrud.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnufuzj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgdccji.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uikejkxn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2borlpycw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyvqwbv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjvigju.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbekbjx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsfigyw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfchzwv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bunskczf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2orptmzdq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zbckqzwq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrdubch.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpncmsi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2basxwwfx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vwikhtrc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lezcougd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjyfkcw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfzmgrd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qleexmgx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xokqytxt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwraknk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2seyuiidw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efwyvalp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dldkaxgo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmunkcbt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjfeapd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2iipanexz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iacisftv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mnudnqfd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gkchvajt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dktsnryx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnoxjqk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qszybgyy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqosojo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2evjudaia.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2agdcnfos.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2imkbjqhi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kauokehg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vexxobnw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaxdgnf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjdapjd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoppihu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xukiltky.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yshwgbsa.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrdxcvg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dknhuthh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqtkijx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxckbzcd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2virkggzy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmfqwrg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzqobct.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnrflmn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xeckemhp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kalewqtn.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2siawokse.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2klyqmgxn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjugwks.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjavmvg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyareslh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jstowttt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmylfmnz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2phduxtvw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2diqumwng.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpqckxi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwhzvtx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlmjrdt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlxbfub.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtrsntj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnliuou.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tjciyqly.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdstdlzf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfluvkm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rteiffmv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyililq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpduqqh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2famqasww.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2oflaeuie.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lbylcmfq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnckjuq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxidodz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2khlpifdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnewlveb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruohpiud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnpgjyh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2npgdnhnf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ejymtjga.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yswixsnw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoizxhm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2plchsisz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wldnogya.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pooyahlu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzsfkdn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sscwlbga.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yoziiczi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fipqwpac.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qikgcuzk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeeubaz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ignmndmr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lprfkmdn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvetpotx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gkftidhv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvvdugh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cunvnvvs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2azfndxld.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdhqcit.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdoqsuy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwhmowa.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuounwq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkfmcbn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnlxykh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uakedwaa.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nheclbkv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2uojmezmm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzjarhs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2viwbbskj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzifbhof.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gitqkzph.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkhrbcl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfqifxq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxmyvcu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwxgcaw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttereitt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlxhfmh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2urousbfo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtmkbsu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmmzfvq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxqicgk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjocurag.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdaksey.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjefmim.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhlsnnv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfenlty.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cimhdguo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ormddnae.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmmwvbe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzfzfba.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcdhxtf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cmctbylt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjsykyv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcezjds.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmrvgyx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2orgzlwxs.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdhgeek.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2scihejjk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qdecblkg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtdjupd.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gaimulsy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bkebeccz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdopoql.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytofxxep.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jadukcqo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbohwrka.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofluernb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tigdogwk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcofsas.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhrjvcz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfffjfk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jcriikje.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoyabxm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxcftzy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvmifdw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mymbnnvn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aktombzg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmvodxd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iljufzuu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rijxijcg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2floyzpza.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxjeyye.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jpndxofz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zipfszdm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2utnynsge.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhhtwkj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lawievle.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeffayu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcbfrig.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2sepogeef.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qalcnwxt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2izpgbudh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2daboanpj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhmexrb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gwedyeqb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgftifl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bufvfxma.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmzhnse.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jiobrota.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfqfaqp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udydzxwi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcvvjoj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwhzbfx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjpwtpf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkioiqa.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2eacvytwz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kbngjfie.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2sdurffso.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vysfphaz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezguehew.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsyjmcu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrrgzqd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxhcmzg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmykxta.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjcvqww.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kukufpag.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2izxfects.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyntfih.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2utwtwjmy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hliotlcl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zemhuiyp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcthyord.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhjvjtx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2thapsdgt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ciypwzkd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsmsnlk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdblujp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rworqphh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxtyaos.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbaqkfb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2iifxuufk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2unpoojys.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhdptcz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2usdyarqc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aegpurgh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdejzeil.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uvadstpn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2abaeargy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqylxkq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfsvkms.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gimgjgpo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xuorejpq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjywxfs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjdmyqa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzdtvvm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzjpmgl.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhhnyfa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2acivxrbw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tyutszbk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqditmev.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlnxrxj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbdcnov.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ictcidxy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lirmssmf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2inkiznsf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2cthqdpyc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2okkzxsnk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpsogvl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyhzhwb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rwajouzg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2haqdvyhh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwglmcxk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsqssvi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkfzbhp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxabgug.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rezxbere.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2djbcsutf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhbdsih.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yposfetu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2efibdupo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxgxicp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyogtay.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xanbrutg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2docfemqd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kktrrjch.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dforctpk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2alaylsnm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwqrgzu.html


<!-- 参考信息 -->