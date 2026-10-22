代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmholie.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbnpiey.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pveuzxme.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zqalwafg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpjxuwn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2espstzzc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaurfixc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkyncdk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yifckgsm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zunftcio.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uohkesel.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcwmkbk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhmbenj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nchrfpob.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwjylhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzinncu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2saxgnxcv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsjhbbb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvrmvet.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lakhcckv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcaizga.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uabaikrw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2eexjrtim.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsaonkn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhboxbi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rghtekmh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyaevco.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2exbdpmhn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2saovpbij.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2enjsvspm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoknhjc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxotorao.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrancexw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkodeszy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ervjrjdc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxtoshg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bgldktsx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyxoqve.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyzdbsd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjpyqdf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwyknxx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcutkvlp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uhubuxyq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qghnnxsh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeoqnxv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgjccyc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ourkrqtw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyuzjsr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ducjdorz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcjqtsv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2epygsqhz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbjofbt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzhrsbh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2accwovyb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrtctba.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2srhbgnlw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2naqzytyv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pimrshdy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyhughv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkvyplv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2veycurat.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtqoazq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zhujnbkj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdwzrgw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oyexswpl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyptmfr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gbihqcrr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkjboxi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrrxxzy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2giurfbge.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjdqrxm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2thifpuqu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2agvasxsc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkduajbd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzyelco.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaedytt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dvivgbfi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhmjqbv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yahfwsxh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2axtjngpq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrqvqjt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2znjtsdoj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zegumgss.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2owrvnqtm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzqnjcm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqchonb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdirguwk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cprqkune.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsyssht.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgkkdkl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwcvdeb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vojtpkrd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2owojthfa.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyiwdye.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkubfqp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjfyzdo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvfiepd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gauccjoe.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2isnhyqxw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwqhbuw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2najoyrqq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzepvuv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nchmbivl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lveeocsj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2toyxrdfh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgdlnnz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eslbywgn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvxejul.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyernby.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkgzrnf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sbngiiib.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxamlian.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2comadgac.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uigspwoc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rclnczcy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rubysxpq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fywwckxz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2elytqafz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqscvqtl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnhmzfa.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ollnegom.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmclikw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xujzwipx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2myavidln.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2suahpian.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiffsov.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fshuagyb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hfarhmje.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dagqxhcj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2etjmvnsw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmqmtec.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhchpxp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjrxhol.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzwanwt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pinyomku.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xjserblt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaavfpxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rozrulhl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2snrwqach.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrnpght.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sclguwmg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhyvlgq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkerzmv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qruvhckw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mewpvjde.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjskhem.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cahpecdc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhekdgx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uepfhmih.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcugfco.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfgqxji.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2austxycb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeknmyg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dajujfpm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vfagrzdb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qwebaaou.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlxoiix.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqvvkps.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cumcfwzj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxivllwx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oogisjre.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wigsupiv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tisihlqt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2smbomxev.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmwmgjg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpdeulj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pjndaygb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2crqorjxy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kbatbefl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbefsoyt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwkyiib.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2srijjwhn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnemkkv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaumdwg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zlloemjk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfciuja.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyjhtqq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2itwwwxjl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gucvslei.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqevzbq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxrpees.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pypphibm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mqahgmla.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyqqcde.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pexwbheu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2duyloidl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxdimaj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzoydtm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdtrqsn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tandumwe.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxmtwqz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzrtstu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2atrvpqvk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzreixw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqdbvce.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbgslzb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eombzcjj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zaazxyds.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2arwfkesu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvfnkhx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xenqolyc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jhieyknz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qscmemhm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iolugppm.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeenxcj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzajjmj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iwumrzmo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuipswm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeeaqgy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2brailiem.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffotjcyq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpmtgfd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wioszhql.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdfbxpu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuwdjzn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxwfnec.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvpuzey.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsevkuux.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrjdzck.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvycqnf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ergfdjlh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvfzdsq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2huyuxoyo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxhtxfr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nvclfeuu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmdgneq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmgmffo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwicgrwp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bteedwdt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyikmqsb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2puldccib.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbfwglm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrjznor.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jninubap.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdpkkww.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdfiwzw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vraycewm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2doegfvex.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcraxom.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eudjcyor.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeodapa.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuooggp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhahszv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxkpsbe.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2abhkmhkj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2eehszlfi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jmznenbx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwhxdww.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmhvadb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2sytsbstp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycldlfek.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfztmtkd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkhehpw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axhdbjmp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlqcjkq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiudyse.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fexhbwvm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktphqavu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsupaor.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmmueub.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvqvmwc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbffwkvm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgunypn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ardtnxbl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wyigqlhy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2edskapoo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqbecnj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrpvlzg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2iejtqusy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2btizwatn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bamqyaxv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnvzxot.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pjktptcb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbnivtm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2avomlddc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2oetagshg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eowvwbxz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjscsvx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvgxvyi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2exlydjcd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dbondjpi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbktyyer.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcclncw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2tbugkpsm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2afyzlyoc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2loeovihb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yodztarm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgnyvdh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbojsye.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2iyazgogg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrldhmo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ketbfbqx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ejukwplt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wapsheqx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkknwmw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvytrmn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2axmqytux.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtvvoxm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vauwcjxk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nblxhjnw.html


<!-- 参考信息 -->