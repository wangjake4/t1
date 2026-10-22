代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeplwdez.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2smqmzhix.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnhykzw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2opwnkkjf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myjwrumj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcpkuoz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpimlsd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsdblpj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaszznqa.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nezkqzhd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyemnqh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uwufkeaf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ughppljx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgviwla.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnboafs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdhrjoy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzntbac.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oifnuhux.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtetyva.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wumlaqzl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rukwkoeh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzklfwqq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2najxmkzb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rhytbjyk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ugasgsxh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlnlzql.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtokqkx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkzpsyh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pxomtznl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sauntzuy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhnkvrl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcoetoh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qswtdtyn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjkulcn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gerjcwer.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkbkjqa.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdokbkp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcygfys.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpaigqv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2njrmeqkg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lzokuvxu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dztqsmma.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eczhcpse.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrmucwn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2meqfhxwp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvnlssz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfysbhv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouemxveq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxvabak.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zeptydjj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mthamsca.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2groowwts.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nateapjn.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpkqkkn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxclrrz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fufqlxfd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwdpnun.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyyoepa.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eflhkoea.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xljlyddy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxdcjbv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcozejec.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhqzxhq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoydymi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqrjfew.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqhilig.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgnteoc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeqsqus.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rcddceud.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kymkjrwi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxluqwd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrbcooi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2twzttvmv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mspexjhk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ozipqapz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdefrhkv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2txrcmehb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2etyzrwif.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyjyetv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhwarvj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfpypeq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pcndmlva.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ntunlhqx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxzpjya.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2palysxla.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjcxsgf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2keubnhnb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pbezdarc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pkniqqnj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaedosg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkedycxx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzwmirf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axxhgeep.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iawnxhrq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsjmkag.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzcrgia.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnuyrek.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkvbhjl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qojleemb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2huvtkuke.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iapwxmpd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfghnlsh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbynmqun.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdizvxzt.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iegfuroa.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vimekyra.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdzrgid.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdazkybu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyvixtn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ietlhnyj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlxrrmx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hctzgktm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaxyiwl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agiaalms.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlukisff.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxmjoss.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnivupg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxnnviz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfstbdxz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrgryda.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cugqliat.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2agrszfgz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyaoeal.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lytowtdy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2orlivzwn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdxxgkn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoxqazi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjbybsw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2juarrkhl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hvefiyyc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tejeuwpm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nuevlqud.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgsrbep.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wotzachc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsipcqn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2phdhnjwe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsojffm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzvjyxd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jiytxiwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjznrom.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ahajttoi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvlmqej.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2skpjswmg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ubukwfyq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pybgzxte.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcyjovx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyyyvcg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yiptfiis.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yclbboaq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxqezdw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sozptror.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2caycxfma.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjwvvhc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggixykfr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gimxbyhy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhrhafn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2atkncwca.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtparzm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2blgonqzp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rymkckbk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfdjtqa.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwmbujt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pxigtvam.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxudyhra.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfzatwa.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcyvbnb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gngsnrco.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtumggq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjmxxhc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyadganz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2etscpvis.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pquxzyfv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxjveuu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uchaurwj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnexhhl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2htlrqles.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjtkbos.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zccgcuep.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhlyfsj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpojkzi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2abhokraf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bjolhlog.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoygulv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjqgmzc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exkdhnnt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbpbivp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhaezsk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qinozlqx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwhgbxf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2easqhpbe.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yrktrdce.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2enrggmnm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxmnbog.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cuufwbwl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wvczgsnw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2eczjviso.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlywhuu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxytyou.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lforjykc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsmglpg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2uamfkllx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2speposbw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgcqjyw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2etgooyct.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2neuzgzue.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2htlgrtar.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2otpzcohy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmnucfk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2eaideejs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfwavuu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2foahnnkz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2socbcwyz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2baugbema.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ukadmbul.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzcokad.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jogwvecn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2llhzdptf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcbkbkf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2taenhrll.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcuwqdx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2smsjuoes.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaxdrfa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rotgusfc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhoziat.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xuausgga.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqryhdb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ongowpbi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmzyjth.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmslmeaa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwuqpnq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jkumhvkf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtqqghm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oxactgul.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2sffynumr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2soqqhwch.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amdqlpan.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2azjkzrjt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfxrxuy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnsprpz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkilpoym.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjzjhwt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnufsfop.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uttbyolx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoikfnwo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2urlhtuqv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvrncsv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjnlzqf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpzbuec.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pswskrgi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2chzmtyiu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcklqhzp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfaekot.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2maegqjhi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2taabayge.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrkuycl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyrjpbd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfsdndn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdbfpdq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2afgwrlvh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjoxmuy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtgitvp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqofavzp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yunzntly.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnpetfq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kuififlx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvtqbhx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2olutewrr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2andvngxx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqrmggk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhevpjuc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnkfxmh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlutwny.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqgwiqt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mputwtfc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmeunfn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmdxtda.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpuipjp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwowvdd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvzapfd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcpoikc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2werqtabj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjaxbnh.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoupaid.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpqhnbg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdwqrdu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2faiegcgq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoxjcmy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2puzaqaqq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmtirov.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpwsgxa.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2komdopdh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpprwfri.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqvkjzb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2noidvutc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrsojji.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmrmzpi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qunaafui.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2thtngwdb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvppixk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvmvlqc.html


<!-- 参考信息 -->