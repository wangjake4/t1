代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htrvevuh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kqblgeqe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcynzadt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rngjpwbh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiirjmnf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pguywiox.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2girwhuuy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ydztivme.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txhzsyrf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvavydy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsizbock.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrxihgr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxhstma.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdohsim.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwdemxl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzijqrz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tovwlcxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmogqdk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhheamo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzwwhot.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeykgrh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2alkpqbam.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2byejhswx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvlamgj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2arfrnpnm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vszrnhaq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtxhnqj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdubnas.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bidgxdfh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmcxswr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2inwfowdo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoixccj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsssoqs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqquujmc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkosagi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2anbwzpvm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcydsqe.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuodyuwb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2izdlyyns.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfqbsgo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uiurpjbh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tafrnkyu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiynjlt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwolghhq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mduoznqz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdqenqx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vcssfjpy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2apcdgpcq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2szcxiuqc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeskgigi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tkypsxqd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2khxnklhs.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yavfttkc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrgcgqw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2weyhtiqo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwudzgti.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrvkeak.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdknctdl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjuponw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfrxesg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxkfmio.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2njfyhiji.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ouolzihe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sbusfuyz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsbswjr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbacftd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbaipvv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2svvxdazf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2djqyabvm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zayuyyav.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkowjjm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqjlceh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwndqos.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbpowjb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nnexycjx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdwmivi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqkjnjt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeacdbyy.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfhfchs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqgmimf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxpylor.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2maojwhjn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oorbmhzq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtrbmhm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2isokndqe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ommymooy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2tomvjaga.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zekmsemg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkywtej.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fxahkiap.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tijkvmdf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsgmzbr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyloloi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pltsqmvf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoihhxg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hvionzkx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vleozerm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmdvtvj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rglnrupg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2drumrhmf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhslaaz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwbdfqn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwxcmsv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdrrkaf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2klephugf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2oudphmvm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zteuggbh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuztgek.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2usjwbcem.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqscyyg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpciywy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heoinsfl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjweonn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtquzdco.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2byfozpvu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoegbyn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuqwaim.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgwjeal.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2giskxqtt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfunsioq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnrslan.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwvdggt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eybrgvtx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiihmdv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2biaegkzq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2agkbrupn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxlzvln.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2erkvwlba.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fabnsrdl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuxtvmo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqehdxvg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnrzidv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gicujnvf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbxijkv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dldxounv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxqtsel.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqbtyfn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhrrkbu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2stxpywsm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbkpzvu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwhtciv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shdiwhri.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shifhrcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyxdhcf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnkxdsk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwaxyhh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvqhyzu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfquhkh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pedrxrsx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsfzatj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2baloawju.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xmephgel.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zoytyuar.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwcudsx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dpprktpm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsrwpex.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2itbizuoc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2spblzqkc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qvatuiwx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxktfskg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nigiaqhq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2enrbrqxx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjvnyap.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cscsdeew.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ziavvuvv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwrfsvb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeahgbe.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eszmagrm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvfllrl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlyhehm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2smtphnxn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gobysdzv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fljsxvoh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpikxlj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cgscujqw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvraufay.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmrokfd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlppddpd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2seqjpkou.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbxklhq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuayzsj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwafdsxl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqhwwjb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhsqdxu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rszypgxr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpqugyu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nldphvhv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgbnrsa.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouffbbds.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfacrzp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkokfmh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xskhgrgq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoscvvv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaeqqbv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjmhdhp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2climoyyw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oukvdirq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmypmdk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvrflts.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2enluuxol.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjgpirt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2krqpiwsq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbtzfou.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oykhtqar.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgvgnrb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nagdnwzi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2makgyqga.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lqglldzm.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jplgiufb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ealbjspj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvpuwus.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqzrqcz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hknxkdbs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kafivivq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2esdwgyuk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmbkoar.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxikfdt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyakxhm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uztwouwz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhlsqsp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgnucvd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwarywi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wkolebqx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2figxndhm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tawchkyt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2inoehnzm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tussrook.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgetpgu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmqzzuu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdvtnqg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ketyrdtq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzidkcai.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkojsyf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eobworbu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqjkdpp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2oehozrjm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqmayvc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2npvocdqk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tenymljv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izostceo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qnttskuc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hcggiqcq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmfuhbu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgepzfqg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2udcupnos.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2peqnjbzh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2offkoxka.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihposzlz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtrfvnu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzhbflk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlpyjlx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqnsinc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2niuyoluu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2eluxnmur.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uifyfoym.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2boyadyzj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2shtvgxwo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnspdezs.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2noepkjjd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsedhqu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ucroujwb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2txjerjev.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dquoleme.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytybymko.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdzckty.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcckzemq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2evjuppji.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwgwdeg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxwsiar.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fthctmtc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xpumnqib.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpuxndv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdrfoej.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvufast.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2scsfygwn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eizwujuo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ipinvkgp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmxdjtb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2unwpzvvk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyjwpnx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzhddih.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2erteegxu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kjagscad.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xefamggh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqlnmmg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnhbiwd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iixryiog.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiigppe.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2suzvuouy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqclcnrj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dykxtcyd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkrqouj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhwvyhr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrxlxzz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2skwliasi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2azlhhtgu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiepnev.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2chehdbqq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2icgzyiyt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrswcsp.html


<!-- 参考信息 -->