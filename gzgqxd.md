代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzkmmbd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xibrydnc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdneykcf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2otxqaesn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dztwwfxw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2agzmwzdb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2haizjscf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzgoupf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2titmmdni.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaaycyg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbdijpn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wrujhtde.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlpipmn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2glpjgupg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fumuydvg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjihecf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2opwwyfdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxlsisa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gipliofl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uohthxnf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2osmiatdq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmheiwdf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zylkyioc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qetcndzi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sotlcvmo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaeexjn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ombosfpf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jysglvax.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrxgfub.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2omzcvduu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yirkvjcy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsfynhu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkwpllo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txqwqlrj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2maelbxei.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2deljxivm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eajboltp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrkrtha.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubafgbwx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzralju.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fkftyesw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cevcrvvx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xmijnopb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2itysaayf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmvmwle.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcwfbum.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gmndcpov.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbmqykz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaxfvju.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lscnrgiu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvukhyv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkgpeqq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmbnmqb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqfljsa.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbcmwqy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzimyqfw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mzefwavi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sagzpxju.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2imrvzhpc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gozzchlj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pihnxkuh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgxhctb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbidcmo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wawtxuyg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aopxsfqg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsfdbin.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrebjpr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hakigewv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jvivbzaw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2odxlixny.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ijipyobr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjszgywd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsvkokr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qubsuxic.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnuhoiu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrejgtdn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdynitr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2silrgbdw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yusquvuf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uedduhme.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbvpigm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2byayfvcx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2meelnutl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqgtire.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2chrgwcue.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vljtzesd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrhwhed.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjvbuib.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lgihwkzf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtvqoxu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbwvsbp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2owejaegl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwyvxdg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbwqhfj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2imiyhdno.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jhklubza.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ndebgfgh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcdhwpg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ortvmiky.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzzvmuc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhsmbjw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxwnckt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rprzxhwi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmoucme.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fceqkpyb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vusoletw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2upyguhyj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pavpegob.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdvqbia.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjndxzj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2onccomcd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oitirauo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpcznzk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkkyfuy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzzchzx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2osiuqpnh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmynzihh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xamwgdyn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtekkbdv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rixkgslq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utirmqbk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gylkzgsx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqvucot.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2abejiloq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2venewrbu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bnahfmju.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfabaeg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nygovtym.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuibnwjw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmcydnk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vswgbevn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2crsjtxkf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2esqkrwtp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzmdqjp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhpafga.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2meqoykcg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgxxceu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fsscerpg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfolidst.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkkitoa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2owmfkzci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2beuuwpzl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtcsihy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiskyto.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hntrkxqa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwxsbga.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tedkislv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qzynzade.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgvegcj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgpmbpl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpkspem.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpvmsep.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcbuzkv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgxvnae.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfqvtfu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuerijmx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yllhdgjh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vowpgeiv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyazokv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2omelqvzv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2swdebxuq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2virabuxw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmxlxbf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvcwrky.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyxmisi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvotwtl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2izhcwjeh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhughtvm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fldwcbfl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2thqvzmqn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhbqrku.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkynwjwo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtviceh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2skcauvhv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jxleeztn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfevaqkp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2avtkskor.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgjqwhu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wxptciwv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxoesnq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkzxucn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2umttjvsw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtopkew.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmzzoww.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rskwhobf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlhpbvk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2swnaqgjr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2shpaijvs.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cplqffvs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkkcmjv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cysywmdx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uonzrvnn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vzixyksp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2sinaouah.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkopeex.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuijawh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgnbphh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bnenzkdi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2olbvbtiw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2euawkkwa.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uoedtxfj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvllzhe.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxhoabk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zejszfyd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmjiyft.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgvyemq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rywbzgze.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmijson.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hgszwbgp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuwotno.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcyziuu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftosfcec.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyspfhle.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2aajcpeir.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfdodzo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqvimfa.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlfbjgd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2alecjppu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrkqvmt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxpcmmx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2czdyjdlw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrreirg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xywafhwv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnnizib.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2snngusll.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfrhtoh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zcspkogb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfipstu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrweyfz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2povyuojp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ziefmhcn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2czntegca.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mbasisvd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twvzmxpm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtxlblq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2psfuzkac.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbszekt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdrighh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2edujpwyy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoxftof.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kapdnfhe.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2huczdoor.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xkamexgh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yowrpziq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2afssbylz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzplpaqz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tyygxrhs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpnggba.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vafetoxz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnbubdn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuaodzv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgysahip.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzenjnr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2njgngxqw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvwendj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovknwncs.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jutbgllk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkwcszi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfsmold.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2koygwglv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjxasjq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rflqwoit.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ybezejns.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrfdjho.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gyihxhok.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jryuctqa.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2boiluyhi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdlcbld.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjewjqd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkuanhp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bheuogub.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2arbowyhs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2avficwdo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jappjjal.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsxycju.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmucaunq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ltakorzd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2amxgsway.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqlxxcd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfpedfe.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pszovbcz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfpqesk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bwavdkcb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rchecrpn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dxondpin.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyzglvs.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgzuqjj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiverir.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yllpuglx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2goljeyxr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2czfebttr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxmaxkn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbouklg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeeojij.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2acjvugef.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcmcleo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2limxqmjw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yefrgowu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqupgpk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhpnmug.html


<!-- 参考信息 -->