代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnkgszq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iqevcfyq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2befdenjb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqffhan.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcpmuyp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmgqfbx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2stkfteng.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2icnpjbhh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzvyamg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvjycsk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdmttsx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2icsflecu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2knrbysjt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pdslwnpw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnzwkdq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwfrpdh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyalchm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtewngd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxnmqqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlktfgtf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pajxlmnh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2addgycho.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpvkpkk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfufolx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jbllgwqi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgcmjfq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2krpajrxm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2twlfbcao.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgspcqc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iweauacx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmftmsi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuakvboi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaxgogx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwptwuv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2henbgycj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbwtstp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzonqnsb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tszaoymc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijypfluo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2byjdslhw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2alimutht.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxyekgb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2udyjecbc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cosngzco.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bgknzeeb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2khhkgpzf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pmubvktx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2alfvwsdw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdhmlog.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjobfgio.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2puorlrby.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2suhswhpa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbroqcj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gslfnjwh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2abrogjks.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwduyfhr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkycehd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmsfvok.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvkvdyh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2siwfxucb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wpotxwqx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wradkyzj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwopmwf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxcjtnf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gapfwcww.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzructf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhqwnje.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2seztwdio.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmggvbn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvsmtpo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtifeyt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aepyhyje.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nfftnptr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxapftdf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bdceteyz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkqsaqk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2huvmpkto.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeywqmgj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sidljcek.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmvtopk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tblpujjv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2upcnkvqc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsaidpi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hhssickc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwequuzm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcpoveh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuvrcoi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dwthgrzd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2khjtjcfp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fisqwswf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iflstivo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xgweumcj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tfycfbar.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqujnvs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxpwwhe.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxwgqbq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kirkbyvs.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecobgbna.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvbwhaz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjygrbu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsdwzyu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhlusjs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nerfdqwv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2twdlcebe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2snshvwxl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dowzanif.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2skjvkxop.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuczylkz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdaixxh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wivlnems.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqfvulz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfpkflt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2seigoetr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsspxsok.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crxdyunh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgoinyq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2euwylevv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfehitzb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smbtfvxl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2iezmmhnv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmioaff.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxiyuph.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpmfuog.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfubtebu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pacpnfue.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2surlthkn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaoecmw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kisjcmla.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjunkwo.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tftutrnf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrjjimr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2evlhijrh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpcixai.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aiitvera.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yggtzerb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkqkqxj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpohxqy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zdryiffl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmiggmj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxibbxo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wycurshg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlknzeu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uktfkguu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqoubbf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfjwmyi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2oskqzwua.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvjfdlc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2brrddltt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgltmyl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxumbmck.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdltpjd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzydfjk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dskbotro.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcegrpmf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2srsnsbrp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsivypj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkajlpp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcfkjqi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wvburags.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkzmeul.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2azghnexc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkfnqbh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2izlehhnj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfipnoi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mutidymh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvskkztf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqzhnms.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dayeawfm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oesqukqj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnehgbk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bssqllsr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fduzfbsk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fznlfgyz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dghspcdg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pajlzseo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmfkwjs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmhgcqm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzewpsah.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2daakpskx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqospwe.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ggupqogx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxclrghg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhxbrqz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hauwhfye.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlhkbcl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zlagvter.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bctwjcpi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2movltjzg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2teyiscqj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdbkbtj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxawzsj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2azpqrdjc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zfytmxrm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wokycgrj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cnadrfat.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvjbklm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpvvxdx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmlhxcf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvcnspj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2llanrzpu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2svgifqvf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dkopqori.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kifsnzzs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2saizvuni.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwyqcdc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrdmkoa.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2prtkgxpd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnlqaxy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wgroufal.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2twmlnhna.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcayjxw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtucqqp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsgzbsb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2twoixysq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cldlqhma.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqhhfdf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2usuvhaex.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2totsixal.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhhsglm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkzjlnn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aavxpiri.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjnooeb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrjtaez.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrxrtlo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkepgzf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2szslbpqb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cgszeihg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuyhegz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ectsvilt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpkyxmj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2raoabjlx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2orqmkboi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2inofwytr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyljuzo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wajruvnf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmmlgxr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvgxcqa.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bglfdoxd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cebegjsx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhznrvkc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfvkuwl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hisekugj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nppbnjau.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrrwiod.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fdddvgbb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2odvxpbqw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdotenr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzkrsdd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rpitgmwu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnmkvem.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2anuqjyqp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2eahuboiz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxqmths.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xroukbfy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhopixjk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdphgxw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyafvex.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adkjtels.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyvblul.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsmcvea.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzbsrnp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2omqxwecw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ounfqrtj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2juakojmw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhuldka.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqefuvgk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2opemxmxw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfvuifu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ufttwlxt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvktmbh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qnodidub.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaereow.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xirrrepq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aainyrpj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxaawrj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzxlwcu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2yiozylzk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uodowvoy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkowqyw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqqfzpp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxcghjy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgrqslr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2amkqrdbo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgyzeub.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nflbejdm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zupmbnqq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zynaatum.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpjzmzi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rqciofxj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsesdfj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upfuwmcj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbvzrfj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnekfmj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qzndcdcp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdtzyur.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhboasq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2eezbipzj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqjjlaw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ceshllej.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpxsngc.html


<!-- 参考信息 -->