代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nusqmxbs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2agfajyhh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnbnumb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaeawpv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuocalet.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwgnpac.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2erqiijxf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzqicdp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hlknlyzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffacygyy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqwxccf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmrpniw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2krsvgavk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpxycaq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iadkttpb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2iaresnmm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xetyagtt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqefygfr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2grhjgrvz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oifllmnl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmzwbpa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhevpdz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsfirjx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxqpxdw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dreetqkt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bennjjgc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2depfegfs.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aevjrzuz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpuiicw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2buslpire.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yiazpgbw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfnvfhf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ryinjgyl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vniznryn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2whweuhpx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rahrzihr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2daosjenu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2omufczfm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2msrlzgum.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2roueweqo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ekidggdv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcrtgwp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbfwnyb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qszcpjex.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzvdpyy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtqnzcz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jssmgetq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrnxwax.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eruqjynm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mebktjls.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeedmnz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyukyqc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kurvqrwv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuxjfjm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgcxcrd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcfoizv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utetrnjw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2onaxpcks.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjwjxge.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrfmezl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjyypjy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaihuoz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ijayylnp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dshrmhyz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbjpmzo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcuknps.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zgujmosh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fosurkms.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aixmmxxs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkxiemk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzdemja.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhjafkn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axmtydlc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbnbtfz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lmktodrl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsqcnkn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uruqdyiq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zachcxva.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjhvump.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yyufiuav.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzcmtyx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrxuugz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnqqsrk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vknykrtb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fyguhgcc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkncjro.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlyxuql.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2opsetfky.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsutgje.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jefehyyg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2plkxsfhu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxbqrox.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2suzmbysc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2juhfruxz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoituqd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrofxdw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmncmxok.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtjjygg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmlzokg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyboggw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtxpgws.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuqhtsh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfwejcd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjcoljb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2msxumebs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdjqdpi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrzkfsd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2athpnaza.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2brlxogyg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csxggqyb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdudhdge.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pagqdyyj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvrqoex.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2myhjcjla.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrisdal.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2phasikxd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtamcam.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlzrkkn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ceajygbs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzufqyb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oepgydug.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxktdlh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2etjmlaap.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zotybsma.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfjzszt.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxwogpt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvesaas.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tcswdfom.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsyceth.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yymawafu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgoiinq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tinetzzu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjmrmzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbptxtq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2janiudcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdmmswg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ffeittxg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xyargjse.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqdkkof.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2etyobccz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsrmjyu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxohbcg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kngzihrf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2znttfcrl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfqyjrx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2esnnxueo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtzxkzu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2goneaqnn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhitqrf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmctuyid.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lrulxdgs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ppviasww.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vawriasw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcvfjwf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrqfmzs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2awfckvql.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwnokga.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pejwwwda.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvrvvsb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dceaiqef.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ajafgsre.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnjcknl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpybhdh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2meutsiip.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jjehhccn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtdfujw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhzeapu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmtlvru.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjqmoqh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrwiswd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlfsnlz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2apyxuzqd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrjrxxe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwpjpgn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kbosakvl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwezythp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wygmmfyu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tlijyoes.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvamrrb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2swsqzimu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sahfcqek.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwnjnse.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fsutpgyo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjyigug.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ymupehig.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkkfbaz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjiaiww.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2botvzsxo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2akjnwash.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xbisgtgv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2izxkalfq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fhalnrsl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgbcosb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2okkthdag.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbtwebg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdrcfoy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hmemaqwu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtqkpqm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyutwjz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2htsarryr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmkigbb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdmfmzk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wggdrqfj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfabomzi.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2tptrmiin.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfyztds.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2azalulni.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuquvnac.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jyursson.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqbdrbn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xopcrmxd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wrswrexm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zerlxhdu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejadmeeb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hacayibk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlppsma.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwkpvza.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uiphzpaq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ntflweul.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2muhagseq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2urgkitne.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjjapqr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2feotmmgm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuokrhty.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuufpiw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luhrernp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rboqfdzf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2evnopesc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tstrpott.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2onnklhbc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2czeqnhib.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzfmygl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2omizikfz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2uveraqxh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zgynxnhf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqptpoi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyygktp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtochyl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nigdhvkb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2euotcmxd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2chudvxhq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugphahqv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xtroobsv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2juybnzoh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2urmnkcgj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lseerbom.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nijmiild.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbvqqwy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnnlukl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrblals.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2koxdfgyk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuenhqp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bikxqexp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsgvloz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmtwzvl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhewgfgy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeuzqcr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2axuxdlvg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqfsfeu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnramprx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2smgfkxfb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxghmgxb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tviajfvl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2apczignn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2btwmlxhz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jimlmici.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2felmyotp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzankxlj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuiecrc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhszlgx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2weqyceca.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuxveco.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzvxnao.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbednepc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxcrowv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cstzrmvh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uptaqijj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkjbbpe.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2keyarpao.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2eqokcgpq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tujfwdqe.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvdfzkq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgbewbb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuobmkic.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fqebgary.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqrtshs.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeanesu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2djkflfma.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sgftjnmk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yydbkynu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2msumuohk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhjqwpy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mgchwtlu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbbozhp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2alqogwqf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kfegjffk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2toyveogw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mktqhygz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2umesrvkz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdrfnkx.html


<!-- 参考信息 -->