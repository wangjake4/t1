代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ablyfxuj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rplgkftd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2alezblko.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ihybdxwt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtplwhco.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwllzpk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2oscwgcoc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfprbxa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2trfjtwqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjuibtc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wockniek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elcglqjt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwtgrmk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjumkbk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nezvuqia.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2whkyjoxb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsoaval.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2byhzuisc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpqzumg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2viclyzxz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aavcbdka.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwulyee.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cryuigpn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2arttikrr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ltledalp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqaqijc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lomywwes.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfavszyx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsibqzui.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgjaxrq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxjffuu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxljagh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhvxobp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhhzyav.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtlwtvu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfntvhii.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaniyqk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzgcvwa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2abddhgoi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sizrtgvz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wogfgmnt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtgqges.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2draesuws.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdpdmlv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yljdsdeb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ijngttfw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2acuyhosw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmcyjsn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhslrkv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jirnvdvo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2frdbktqr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgdykvg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2srxxmkjr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibarllrg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqvzoab.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dasekbrk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmthctdo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpwgtlg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiyxbwi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aulerdfa.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ejocfllm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fznkydcn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mciirbls.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2viomnqbk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xiolsjib.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sajbcmur.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2imaquorf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qggiqekf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2axednywu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcczdkl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyoqmyq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxhanbz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjfnjci.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnzwviq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2owvphfrt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqobewe.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvikxyyv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrubcfw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2aleyengx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbolzmm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zebhgjrg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgofyvn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vraygdto.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcdhfld.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwowzuw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2txwklawi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xulzldgj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnekdjl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtiqyct.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtcpzdb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2psprkhnk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqcgzvj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdwsjog.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hulqtueo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pljwpnxn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lubqerwh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2budhalkk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgnewnp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2igbadyok.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fomtyiqx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbpozfb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhuujhs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gapwkyjt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtjjljc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhvejnt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsfrmvo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvrqcub.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrnpgor.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbkrvhh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkmhrie.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2olebnncz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrfakck.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asnenfvf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvcmbdu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pydqpaqf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqubgfd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyootwm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2czbimaos.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbkqtki.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lhulgflc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtziaea.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2noybtvao.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eawbldco.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fztwputo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnsumkj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbwkfqp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjgbwzo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iajnqkab.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2crgwgwpx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2edeodqiq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2axponrot.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ekacipko.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyixkgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eitvsvmg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izodludv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrmhewr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoptwga.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaaragn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fhokjlex.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ilylucgs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfavawl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgnzclj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiteriw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kalkpoaj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bmukyzgk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbryciut.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uriinulc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeuumfn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrbpgok.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2aaauzjsh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkipzeu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzgcnsd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvqtimr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngswwaew.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmgpgjx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bonnmlwq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gvupmcvk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgnkuyw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qercdbfq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2frwqwavk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cknkbbie.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnkciir.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2egwhglkp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdsliug.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2eggkasyk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgsmtor.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lczcygfg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fryaayph.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxekdsl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbinpquh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vatsezeo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2raoosaov.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpwqclx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdumkgj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ngifznbv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbshzgt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yoacbdin.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jivukxox.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2epbfwrag.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2olcgckip.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isurlbmz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwqnhjb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxysqke.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpptgzly.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wulusdwr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmjpzgc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbobtwp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sorwrmrv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rztvqoom.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2daivdqlh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkvpkim.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwmqoht.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfxaqhd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcxedky.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ljztxhtx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lshlhipr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2krvyoyji.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiwaguo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vlafgmci.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvknuyx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxtmfij.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwufnzxh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2leiydexd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgypvsc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2utlygjnn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2eblkuewk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhriffq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2sngrqjyx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rzslletu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hyonkrxh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuxbxpc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cjntzxbf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sfolwuxr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqchjge.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oqolrivf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsoygzb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeqqsql.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qpupefgb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwxxzis.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpkehhi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2txvjmjow.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ignzcsfh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmqyfpu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhguvjad.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2peetgvtr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olmlkxar.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vovseddv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrntlas.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fviuibsa.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rsifynem.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2swgpdzog.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxfntwd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2butpkoau.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtqexoz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpxetqq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whdgxttx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcjvpcl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyljbmop.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxciwejl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkhwkzh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqsjytx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pamuiyxh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hygkhprj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxjjaup.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2scpxwylc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmzufrz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyqtouw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtnfial.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjblqgl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyfkvwv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsjxpdt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2khvnujnr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zfianizn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfgaamx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2eehlbrsy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhendyb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjxaidl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpayekp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvkklhz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2llkotcje.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nxykqbtz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxppehb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzhrova.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmkroxf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vslwwdmn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oatntgoz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzjumrn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2maiotajz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgufyvl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfrwinp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmantgs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdcnufr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qogbrptx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgwncfu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdahrli.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtxyegf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bhybfpxj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eznulmks.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rmctagkw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpqkjnk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdoumox.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vulablfr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhznlfrs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2guowbphr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2joffnogx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lybtycbu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xelthgfk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtjurjd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2alvfbjie.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2iltpujjp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2inkahncq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wvictusl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlkrxkb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2cstordrq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2afhmwldu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2buekjwzp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xailepjn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hhewkxqn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hibmurxe.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdihqqj.html


<!-- 参考信息 -->