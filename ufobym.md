代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkvkbvv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cupesjvf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2peqzqimc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpfhhqo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsnzbdu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxufoauq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnowswwn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2krhbafwf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcyttnv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lghdgbve.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2erczauns.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoiifhf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsaluga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxawjlwp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpwpqah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnhwgaj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2milgfyrc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aphxstxo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqonsxo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2flyzfuma.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzimyfj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2miudhrjn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ftugcycu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbbevel.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pheclole.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnewydk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxnsrzy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2agwrynot.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ykstxkmq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyfptnc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuaagji.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2znshfjkm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2piplljem.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2julsxirw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2obtyerqm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnqlwij.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbwxrmo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgsjnms.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2afrohbjf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxnmjak.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnvfxln.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbgwzzq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuftnaw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hubpnqav.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpgwupr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uljjqmaq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cugwskig.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsfcfah.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2thlbeloj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2emroatwe.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2afnmkxnr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkxovou.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuqkiqf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uioauqyp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgysfqq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gscuxxlt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiuaxcc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tviuqggf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pfybktwb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqfttsz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axrdoyeg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jslqdbok.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxmshdd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqabowq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ktggzryv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkvybbe.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsprokj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxnigyx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zqengtjj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpjbyxu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbrzlof.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrzlqfc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwnfzqs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqrcido.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fawawchy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqzvljz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aidaawpu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwbkims.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlugvyc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mapvxkti.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2oncrsdwp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzsjeza.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2thxfjfrn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mthujsbu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpevwpd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyzxbbf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfsciyw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tmghnlve.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kjutwroz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpzafjt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwvitni.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wshmfxuc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kcllnobw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oehuxpzz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ooncbutd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2yrddrgda.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsmylft.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iivejaqu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wawejvpz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkffywie.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkhnmzj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcekklgp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aybumurm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwihjpmk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwcahiv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zelraghc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qjokhzkk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpufgnvd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2luknilpg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnywpoa.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpridzt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gegvhzcg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cctfwjnv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjrrmoj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aiujclos.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiopurh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qduparzs.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vitdkeoe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bthdtvch.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2redcxjbx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sckfdfdr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuulidq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcrfucl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuwrvmm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bchkevdb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxhjccn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ampnpols.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkmxoki.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqqyflj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2afcxpryz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgheyjkd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjghpax.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2piyvvdog.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dshmcoic.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aljksrez.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2narqnxzh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwumvmiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxchdcyx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaxfqgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfxkiwy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mjezzlfw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vtncnwws.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2alzbeznv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ctruxrdr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2npepaxgo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2njhbmdiq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2omkbysat.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iiawahdi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgquczv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkarrftr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sleywvbk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2olnrfvux.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfhlfbp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2adqvdiyh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxxvfla.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ablwqssd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2eduqygmv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrfsjwu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2boioamsn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2afdwkiek.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwxmeou.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueszqvgt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeqmdtm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpequlyn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvijzud.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvogwzx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ropeqmxz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lermhtsy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dzavofxb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbgffsy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fnickgyq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpuidcc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mojwyald.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gamvtwai.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzyjtyb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lideomuh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tulbnwjd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcjreun.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmtzmtk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2orbpovkt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtlrvph.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlojqgi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbkcecx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcbiygt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocniebqi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xftcjadt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2agfxxssm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qylnqhpo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2alhdgiso.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcqtebv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqazesp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcquhygv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqtjpom.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjpmtns.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqblikc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgywile.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcpwkec.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2eeruuxvu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrygdra.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhebsmu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwidhce.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtudjno.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwbellv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyesmav.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtzafxg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2guqjuffq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwaqydf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfreppds.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kefpczwk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2riuhrfck.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuucxfm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wygzuuba.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wuooqgtm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mesuehem.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rpupqbix.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hscnrski.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkmrjxe.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyylynl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2spzakjnw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2malxgqlw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2paobdbqd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2meyetqtt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2worpdbmb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuwgupc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbypuvz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhoumvj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxbazpn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuolzox.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwmbljg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpfnmxr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kscgpyph.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlrqnty.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zauzrxqz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2oznhzaxc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkhwtdl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axpizgpz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyflqxq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcmoarv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tldpwodw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgayeyt.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yivusbyl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkymeun.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwveymqk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvyzcnp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2leltklvf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2semanhkd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2aktjflom.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyomswfm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qszzhubk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zchvklwi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aatgglwq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfwdnmr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hozqhpye.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjpzuxj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnvefwa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbjotwi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2okzghuxe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcgyyld.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jluiupfi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qizmlddf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bbznugre.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqdgioa.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hduhkjxv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdgcvba.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiyzupr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaqscco.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2opvnbdrv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2iavwkbjp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nemgedtm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnymtrog.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2snnyiwzu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2karhdtda.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dqblckyj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jexfvbtg.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2octmnvsm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nokfzezn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrioxwd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnuetgk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlfypsl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdpfxlx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpoerbc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcdorvl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkvnjud.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lubpyowy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpkzvzb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2risrmkgi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtezpise.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gliczaow.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vxotgcfn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtukfve.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyqjehp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hceozcwo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfszysl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjzeezh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gngzbxqr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpumnag.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uduvjfoe.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfjnrch.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yojfovwm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcuizia.html


<!-- 参考信息 -->