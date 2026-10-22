代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmduigf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuyvsxz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpzopiw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpbskwy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atwvywyb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vovfqzyc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fltygzxc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fwakpzlr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2srpostta.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wxunvwoo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2eunlwhgc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnjdisv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2omzufdab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdhxlku.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nugsfjvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvwfccd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtsisdb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpokppta.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrlfvsj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2toiirevc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vwemaxvl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrczgykf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gccqznok.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdguudb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eovcroqt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdtuxxv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuerntt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vanqgndh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoelqpp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpalsxc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yvetwjaq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpezihtb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxwxzan.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfrhlmv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2owqxhdau.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbxamyy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tninburc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pibxguqr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2snumcokd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcdksha.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtcqpyx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnpzhse.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qetkwfbk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbyutdq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wownrhuf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfyeudy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yfarslbd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrhmgad.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lofyxzrf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dygtrmti.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkdnfut.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmhluch.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ticosujt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2svfltvcn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeqbtpx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eajhtjoc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuyrxch.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tujhuvre.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nytqwerb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2whbpgjmq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzlropp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kceiydkc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pclokeuy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwadbdas.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2labxvhva.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmllwbx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2eulabxcf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwahvdz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxehodp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbutkjn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vybrsgaz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzrxcpe.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuuuehd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsezpbzn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqqszyj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2byovctfz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nsswrvny.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lozigvng.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cdydusqc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqgluuz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iufjeqbr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kubekbqs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2midhumom.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzsyuvi.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmgqijt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2auxsigvk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frqiwfjk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjlarxh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2morgfysy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cidgbmqc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoqkwaa.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jvexxkwg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtunavn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqqxedz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkzqvgj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hztbughp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxuigde.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2femqmhyz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnghuaa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjvaphl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ueboctoc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bztkrmem.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2esjeznlp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgaehmk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2clgmcmor.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpqtutb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaousha.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kusoasls.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmiijwu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuzrzhz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnermeug.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnozraeo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzheinzj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvufvgi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnreegrb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xguhvnww.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bltlbbfd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qcckowyf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqomyldk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjvcpvk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlgbtpc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jomghcdp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqobftpt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwavfsm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiilnuln.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2itizaqsn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjtrljf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmaajrc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2egzylbgr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzlavbw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfbhkvj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgujpii.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kpubdron.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tinrhkol.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2avfovhfe.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fgskzkar.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxenfri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2moqqnvsl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2llhmlbmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izrkhamz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jogartfp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rogomuip.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2idswjxrj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqfrlnr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2plauvsyb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rohgqfqs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeczqfh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2osfmkjgn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsrhjox.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2prmkbksz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eognygsu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqiedro.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuhnyvy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrxpjvx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwiyawd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqdroty.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sgldehbk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkstipq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgskvbq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjeetwm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cftwckdw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpgdbda.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2itrifjbt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqgrvck.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzuzrxp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfmhmvv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeqnnyh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzuyooe.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2buenhxcb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqrflog.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdnvbsm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcugoliq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwkzxus.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hssujfbm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bklmoqrc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fezzqseu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmhlmay.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqillop.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ikamckse.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqopopyg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfiogoc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrebggj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdhafsr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2avqhndpm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjcqtbj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhpnsoo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwxhbgd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkntuac.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdfhrou.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfibkfx.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjeryvo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrepzzpn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyjidue.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tovgysxk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2aurgaams.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnlwyrf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxevnxe.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2viawwrpx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eckqgomr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctupgfwq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkcjagn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzkyumm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2upkktsak.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dalbbvjq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnrdicy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cukrgmxx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jkykuauu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2whmywmuu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlyzvlo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsstjsy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nktiswsc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgixierd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjeuzhl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uextojkb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dltszejk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgfpavo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ifycxwai.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiknfbxf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgwuabl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrzyszv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiflwfh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwixcdw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkgonhx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrhslll.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkhuuqy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2aolzwroa.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjhzbwe.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wydyavea.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwykccm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niayupma.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcmvwnl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2djizdsfy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nefxfliv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ybriliot.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrcbqsq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsixrwzq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vopctpyv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpdnodb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgageuc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auwkbwxy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvlgbkg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyrxigq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfzxeta.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrkouqz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nipxruax.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfnswoy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yhibomny.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zavhfrdj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpanrdh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzpflti.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzihqiwi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qegixvzo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2avmvvpgi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsmmbwo.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zazfuuwb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtszbpoo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfrwcsd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcnnzlx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxhepar.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bffjqdem.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcarxsd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjeqkux.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uaobbrnu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2npyjxzbr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2piuhltoj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkotlmg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sihqpwip.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuuxuho.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2npnxlesm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpuoxvl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2sjedqxif.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbfelhk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfwdfts.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2opueqlnt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2udlupows.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrivbsi.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjmwwxb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmkeyek.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wxemlnpc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrldbxh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlkmblm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bliohgyr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjicbiz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmnmwpz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jaekhdnf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpwivbf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bthxeixv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xoumodnj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgibezd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ljescqfi.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2euajqaqg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bemdvbqa.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2inbpaqwa.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmsxlvx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vterlcxy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpmmftv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhzctlh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2belklzbu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjmxjuy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2eoysqodu.html


<!-- 参考信息 -->