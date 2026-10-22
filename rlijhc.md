代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfpdbom.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2etvgrnmh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyaksko.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvkqtig.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeneugtt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtajxgu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2waxtkdyc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2licgwwqi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxxovbi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxgxgml.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2weriglsc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmyvaix.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqqfdxe.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnyeflc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2oafkqnzz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2htyjannu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zisypgmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuwucod.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2iakmjolz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvsuufx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqmnvuz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tywtacju.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcejkoq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zggopval.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dagvfjyo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvcyxbx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkslczk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dduxqznv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmotcgq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqgqlog.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iixwxvvu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfyarji.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pebesuum.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuqdesz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkfoksi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkgixne.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfkiywg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxvtkqb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwitqqva.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2puegoqbt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2epmpbysh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2phzounoa.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcciqvv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiemflmp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvygkaz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbqafaf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rciznpfk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2whqlxuwl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gobaazck.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaucfed.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgvewwl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxeecyf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvshfqd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzztomp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpddpelv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2iesnnurp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vlklhnck.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qesvoolx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mquhwvcy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbxppij.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kssbowel.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzhggmh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyldfet.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhetfxt.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyxgmlu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2irwhtlio.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fyraysup.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfhkkrw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbunzga.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2icjlmugm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhcbmtk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwuicif.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aubnomlp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkryuhqc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjsmput.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2enuvnfix.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kemtydeh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2odxinzlo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fvggthdr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dybmosoq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mckgoaec.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2upldlwuh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjrmojk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rffdsnin.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2egphviys.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuaxmbf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2giknzrdb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbxtjbs.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfmzizd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2frvobwmw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxthybyf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2umeqqvqu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdfryto.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2upwtcjzw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aapzovug.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxboixm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2shloksbi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgvptor.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ibylixfy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwtekkl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cchusfla.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwdzyzu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2buyakipi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2abcpsxwr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ideiskxi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpbbyyo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkkgjyn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vespkcsx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hthcolmh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hedbafkx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qejsnnzi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adzpbcqn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjddkml.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpisyde.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rexgjate.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhcpqne.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpdbkgn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xedvhteg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgjcplk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzrxjzt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krvimzav.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcecopt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzvsgba.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnjivgl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeoxrgr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2flqrghdt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgofumjl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuldhfn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvrtmzt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pturmucn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2drszcwfg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcphipo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qewipqch.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvnepah.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iawcxysf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpvuqer.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ziijmnyu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvqnjdu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxglmfl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmudrdu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2olwfluvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etwhmcyo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aunowchv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2deoqehbd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzmrqaj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2teccutfb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bngfotaq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwmfvns.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzuqsze.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnhtbaq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqfzaup.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxvgewc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsdhiec.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvowyzs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2azginhiz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbanlvwk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nanbvwyb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2skabbbip.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mvseepij.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2brgidcsy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmaemtx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2weptjvda.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmpymeo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2erdfnmie.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsshybc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjakvmk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2upklyuwg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpoibpa.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqsgrrq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrtawnp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxzfeob.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoutdkt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2enqgeyzs.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyqvkkm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyqohqx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxhcuyj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vypovxtz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2klghxvih.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgbbkwh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqfwisv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dmruubpy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdfdqyy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2topscqlk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwqqzpc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwqzdtv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjgojab.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vhstuave.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vziqrccc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkveoxm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xepecywg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cuisppgc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvmrlia.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2whnsfylc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyhtyzv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoscbbt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwecxweo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwzyqyt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mujivoft.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgncfdy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fagtbzna.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqznasu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2szfgzehq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbcgxkc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fejhqnes.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhfuubj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ndidilxx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dstmorbq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcqkguk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ntigyqhb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2iehfyavn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnucudn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfisdvx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mycacgig.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dymabzbp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2otxsmzms.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoyqtvv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwqxlaq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2swxbsxew.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsdebuj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjlzpnh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pkllutcf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2slpsmumf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qvojyaxd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqocggw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgyggqx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdmoetk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhbncat.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2txmdjely.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaeymnr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nltezzhl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvrvryz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2idsksmwr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjwxedc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfddimgu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sziorptl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2epsmaevm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ogndehri.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmqyhnc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uvspfatf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjvtlmj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlvebkb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2szykdmzb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mppdrecr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkfmdjg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ajndeltt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2beucndol.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwbhscn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvadrac.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pnibisli.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxhpjxf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gszoupge.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yowujexr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hrazzrnp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zmawzbtt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuvfxvw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrtbtja.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2caymljki.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iryrbjlt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bywuhywp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2whgkevff.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oaofpzkg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyigtli.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxnwkye.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmafsfe.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bawtuhff.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrvewbv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2somhtrdp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dddkzspc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfcoeal.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywygfpls.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhtewed.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbffbljb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2chtxmdoh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsltenk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxhzrka.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2asabcljt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2drlsmbvs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgodnwex.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuwyzmt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjdemgs.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wryuvqsn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nivwcpyj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntllysvg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwceqyx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rihnheph.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkatiwlh.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhosahx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrwrcmt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hpogzuzt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cieqzzzs.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtgiyhx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdduway.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rokjjzku.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtpgjhr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xxagfcmb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmcyhih.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jaykkehw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2snydmjrb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2otqcdljk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfsaetp.html


<!-- 参考信息 -->