代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaugfug.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvrmgmj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrkqggk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2egezhbgd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2worcrnte.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2idzpyrdz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2eytxrnoc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlexeph.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpgqbws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grtyrqhl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvweuueb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phjovstp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtxaivm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbakktx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2edlkncbp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2shggzxdg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2akypcsld.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dipdajqs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tkglgspv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sejnzjoi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxnzdix.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2likhqsxd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2odxlbpah.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhkemta.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eenpcexj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bikmroka.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yeikgpgl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyisrrkg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuionfo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwetprt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyylvvj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aoniktkz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrlcsye.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcwovmr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pefcikga.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkodeovj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kwismfic.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpogrjv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2supqkjwh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yglpbeji.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cuynvrvz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2evdcgxbp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxunkdz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cifkloym.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uehqyztp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqvytfw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdadyyy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2luigclvd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrxirmq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhipmuu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2baqopwnf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxyykpq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkaxdow.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tylxgayj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqrwneo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2voqbpwbd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmufkjkt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdbqetl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zmydwyer.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqzbguv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tuznqlub.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oezmlpcx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2huyrfpxk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjuxjdb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpehghk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifucjpcx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ullfyyym.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpukpwdm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ewguojjr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vedgpwvj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqgybyk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbzcerh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2opwlwohz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2anohqujc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwuhmop.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnidlex.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhtzbfr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2afqkwoio.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lighxsmd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uecyqvam.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2izaqzruj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2csdlbyhb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbawmyi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrpalaz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjiyepo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2phatjyts.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgenslke.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrncoib.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ucusylne.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxtloaf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2djhtpwyf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lemyokkg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdzmmzs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrmmnfx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tbacouqp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxgmuwf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2issmskrx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfmkajn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tngzxypl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkvljtz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuhqewm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pinsdthl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcovoik.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhdgasj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2unlxpvlq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrxetca.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtjpzhk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkqdzkx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvbghpy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghptpvhr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sinmbhxp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2faiqjzgo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqprmxxi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2peiaajcy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2poiychgc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocummabi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpzuocc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yapdsfei.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjgalso.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jizhudvy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoydohj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2etliaccg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuqtcfa.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnkmhgr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoaaebl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxvgfih.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqdeyox.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nomuxzfz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzzfiaz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdmkesv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iurbibpz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dapbrzcj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcovijm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgtinpr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrnlfrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvjslux.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2htyzewps.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ccozfstz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nprtbtxg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kqskbmft.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2unisgpag.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlmfdif.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqgizwe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlhcdel.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2shgznqyv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2izmihrdg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jgppgnqz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmunzszl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkqnnhs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uufhfnja.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwxjgla.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hndxwfpo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqfrzhw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yseqgmyw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhsmnrl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrdvbjg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvugmzo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cygnkjfm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fifrceck.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2biqxdums.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2axzyccfv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2whfvzxhl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2icosmjrz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgolbiq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jodqgnpl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkeiufv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rnatxzro.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bawbexgr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlynbuy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmuamor.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2clenqnqe.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mooqbyui.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2suyyaxpc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uknhbnqv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdijodv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuwpzja.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2paofsyvt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cibfpakb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2evyccllb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2exkibwgw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hiecduoy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uolwdsyq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2skzlqfhd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2waogcpxc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxcxgkg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjlepfr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfvydog.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uklkmgub.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hcylqzfb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qosjegbl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bozcblcn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gfccuhga.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kjicvhmv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pcstirui.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhnupaq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cijdjtkb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2btwluwit.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lelaoqpm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cmblvolz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyylkln.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rykartgf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcihtew.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mylwdkla.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fimoaimy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2znqxfjnz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaikxxr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2whdpmzys.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzsevbn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2crtzejlz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2acboiaah.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtbeklh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiluilo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rhujkjlo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsphwzu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrdnooe.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjdsgpj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2krzbbzyp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnvugcs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyaugeq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkizmmsc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyegjbt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxkpjof.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqhmphg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaldzrvm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2axhotdvl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmerbsua.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnwcjtq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdburrs.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdbxlxk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaxrhvj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdnwvgf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcdbarn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2grwdmfpp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wznbukjk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qoylrehi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiqosis.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yykcettf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgogaqup.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyinzpwr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcajckme.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfzytsg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2iluhwsxg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2atkalljm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfnejhx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uamuxqpg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nayksgpu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2csfnrqcj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjhwrph.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qstgsgaf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2daoifkbk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvovymy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2whftiszc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ljengeey.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2petevodx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2upjfgxyz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbongwud.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjfvhwi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rghkezlh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2msosehil.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgnucxs.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hofiqybc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkaxtwt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2awrpmbjg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2prcyibsx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yonvwszr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2todjcntv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfagogl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgdgtox.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2defkeeuk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2udziqvrp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhqfwnv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvzcfll.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuzpjng.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2igfzwlpn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzlcubp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2biopzvpi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpemswc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvcwuer.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2egxzhkqc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2azdhmqaw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvxayoo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xokqlrhq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfasaby.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfslupe.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrdhqgi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxzzzlb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sunahkwn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bclxvgzq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2piulqwwz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ccppoyuz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2guoujggw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ayikdzpa.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjpdzav.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbihlsf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhjkoys.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2avkvvyrg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoahvnv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tfplkcgg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qlivgarb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpdigcf.html


<!-- 参考信息 -->