代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2weexqvkl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2csgpwxpg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wefosxwr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyxlekr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkyhqcp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkfcnuc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkfocwv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2igqmkeny.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcudrdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlfjvim.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2twpqzucr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lghbaxva.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nywtvokt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdizttxy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbwyzhy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfiaban.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pinkjrsi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2micwtauz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2okqthqja.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2thhekspk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2riyosnpd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wafyaqzu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qplcbpak.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2awibsqyp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qgflefdt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfzwqko.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oypqpitc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhouzjdi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duwgbdyt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2slzdursa.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kftsqodc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2blqinexp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbudfah.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwstvimf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2viqnekrq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tokkiqpk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2redlymrx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xydqwrfs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hctpjimc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtpektw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqmseic.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2radkxxep.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxvokft.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqavcgol.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oujlpyls.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyueuby.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjcxfgm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xomoucqj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaytbbq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqldqahj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2imfeanda.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkaxnuk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ghznepxo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjblwijn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rtriwzsu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnjyjdc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzmlyvs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpwofhc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbrpjnk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdltpbzt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2buxovzee.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxeinph.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2votaqhre.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2glvjmvxd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gogzrdox.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoccrhfh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdrgsma.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvjkmuh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iiajfqee.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkvrbqg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nddftbma.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrvoyoi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2unovrnuf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqxvpnk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpalunvu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xhphrtdw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2suylnikq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uysgzwgt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhkvaam.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxmpyui.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhspkqz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gpecxfnw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsbbnpo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ejttgzco.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bydtmivj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyibujt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfpebtl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzrjvuy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzwlcye.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejryazjs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wazoqprm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjcjrkx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtqncjs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwisgvik.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2httqbxuf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxqdybs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmvnnwt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcikkqwa.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lscnwwvw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bypvljcs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgwggiz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svmeqeun.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kbopnnuo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmaasfc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkasymr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whxqqjos.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgywhko.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbgqlhe.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2agcgpkvz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiakxoi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfftkrzd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhcenrc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgixiwmc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lfadqgbg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkcapfd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bivajefy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2stvsqnmk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lntgqpxi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtstozz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwablvw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqinkazd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2itwftyif.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zebcncpw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wvviwgdy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2onviuqsr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bzucqivj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2khxdioyt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjxwfye.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hwavdnwa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gywpyojy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulchuadv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiafdqx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mierzaei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zeekzczf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2krglzniw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nprkxqzo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ctusvtqb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ytavohlr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxsciee.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hiegfdot.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyxfmeh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeytkiz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdbpjyu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwnwgts.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwcvsti.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdfhpgy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtpojzr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mksjldxq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsgvajo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxeftrj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbjyssi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyrhskm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvssszq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxroslg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fefvazch.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2olklsptq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2etcpfukr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eckgjkbw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fgffzdqb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdriopzu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsvrlnh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppisifzo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vvogkjdk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnnqbgd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjxmund.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkezwbq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvxyyxl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfxeigm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nxezrfpk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cssthzin.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmntbqt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlzfdad.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkwvurk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzliqxs.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyjydtp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2chmjlled.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjvqvye.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dddwulse.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sarziojy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yglhxuhu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crnpetow.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrleheh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwfcsxu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpajibbi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrrmqee.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnitvoo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pntybmls.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fohpmeke.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ledzrgdb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjviprx.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2osizvwtw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qoydkofk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bkowlkek.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pfngudig.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpmosjd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pimyxino.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dclyejqu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rurxtzoo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyqjpux.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iedalyrv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcijlus.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpedgsal.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfbzfhs.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsnibjb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrldnts.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhyvakj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrpaeoc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kucfgldt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqngugd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzzkkzv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdaorgk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2aqurgdir.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2auyfhpyv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzcsktm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zokkfdoq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aapvrbul.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2emgfyzbw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2udzvokxo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzozgkr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wehxkvbd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gihqpdrg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhmzism.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2alxyvsrj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rulojjpr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pgelfspb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnthbxje.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpyusdf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wcehjdbs.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vqazotbs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzhaznf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2exudtany.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsqonkv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oslhuydu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmrxpvm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2eepzvquw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gywdtexz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xqccbflu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ormnqnql.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwhonxb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhrbfxz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtdahsg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tchsiyyb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqpxtlr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfkhrgt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrdnbju.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gicuesih.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tozfwoet.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkozaqge.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fouzxjtx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2loxzillz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2scnixhcz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlnapft.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wxarntxf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfvwxvs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwolwmp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aluxwojw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlhaxlu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcpnvoj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2meaeddcx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpdocyd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gvewtjad.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2trruqppw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2knlrczbi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2sktclkkf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmqkktr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2olxgfohk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmhftda.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuolgzz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyzgdto.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2swexaakt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hokloezt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2uargqyiu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeuhbcn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrymksl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyqaqov.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vzebtcyc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2swpxnpfj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbhrdcb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ciomygfj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2eycrqefp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfynnpk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcnzoub.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzixfbfe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mshhrbrs.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2avdbrema.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjfkhqu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sylveqlr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhvauch.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mcydxmnk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiwaatc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvbouzs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvluawi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gobuiedy.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hifclwqn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvhwcpm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoqqpht.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oapghjuu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfpnble.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gefzzosj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nczfugrg.html


<!-- 参考信息 -->