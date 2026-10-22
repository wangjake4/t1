代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfsjawr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyxbelo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2woaudisr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2haipwkci.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lglvfltk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xgerukoo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkykweb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2krxyagap.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxrqhyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uklrcdqq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2svlbzidx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qejhtvgn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcrlhew.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2baokqbcc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbloyaik.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnqyymx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxyyojt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxhrjnd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hauzxtsp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbcvoet.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gxftbpaq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lkahchcj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tswbqmdg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nicowrbp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2krpaivxe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vadrxeoc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lkttljrk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tauqxajt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvrumkn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdpvepl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpmlmym.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2orleztxq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjrvumq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sklnxsdu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ildwyoac.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2utckcpyp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2riqehyir.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2munutjry.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2slyjkveq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxvkvrt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2worarpoz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyywesbf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpymmbu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkbjvwc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wknaucei.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hecodngd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgijxhj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cluvpfiu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vucxlvgm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfuirvb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjimqfx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwxfitb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aofhksme.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnggwqoj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2upcijfft.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lokohthf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxldvhq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2slrqyzam.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2udxpwasq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfmhcmi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhbriab.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuhbvcg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfpvibl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwcgwii.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzejoug.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcarxcp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tktyisyu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2inbxhhii.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjrwkre.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnssyrls.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxljxtj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xngyqybg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uywglzdc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2szijxgvj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnhebdn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtcjnvl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cprkoxvr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2sphebbtu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsrvycw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjefssk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpoiqno.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2okdnzgit.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnvoiub.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsxowew.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2prvgtyhv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iokpmiyv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vldjfrii.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpswvtnr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2osaqtxus.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kidgfeip.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qldvwtcx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nofqvbni.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vawbayvh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqpqmlb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhratxd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gadyiboz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyappsz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpukgrlm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2azalgewa.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvfutvn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcsbyvu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwmgfnw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2alobiifu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmymujh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2junrgvja.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwndbssx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vizkzjyf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiixmci.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmggbed.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvawtge.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzylaeph.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rotaannz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fctdnuum.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2boytwyvc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tznhnuco.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkifwtxh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxygsbj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlvmoor.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxqlbcs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bikcvcwm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrjlfdk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yosyqphs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbljjyck.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqbdbzs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2exscfmvh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tdthhqky.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbbzpnd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2semtfjpv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbmkinj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfascuh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfbybwk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ispnodxh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnlbsag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpaxjvk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpynvjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfapexkm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gsudkqpo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2anzujfni.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lihmpxvw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcxawsk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2majfvnry.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqllglj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyyqqma.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmrzida.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkzlzzo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrvdiyk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2berbdujx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyumdtv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlywvnw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxwxgtj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpdvlgi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcyqlky.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2szddhdbx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwyffjm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kngqtmdd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oyidrxvf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrkuuhq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2etufouyp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qgggvxaj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2byqdstgt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rexbsyig.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bixhxgpo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2spaugojt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssesreyb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qtytcmkz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nstfvjsm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyjoaxj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2halzduhn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vumtohmx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkebnlaq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbizwhi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cukccblt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjlmmqz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxygxbua.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpytsxp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmfqqis.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmunvpq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2avgkyqij.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpgfiel.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2sibywyox.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exwqkmrv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2phzhtdvl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2noacfwan.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tibueeul.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2puczmcwi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqlofem.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiluyro.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmbptof.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hmawadyw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvsnllf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgyqtpc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cxscgpuv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2holpwgtj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2culftnze.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2stizlflx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iecnuqzp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2aertmojm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bhycnaiz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwydhxa.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2shwcfcsh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgrxykz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2oytgqbrc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzjaljn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xywkphxp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqprkpta.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2imnsvhrk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dzctggtw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2chrsvfrp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fuulpics.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ogveswsw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkciwef.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2iozrgccq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyjnqve.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbjgomg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tslcgunx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuqpspf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fsujflhw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbexddw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnpljfk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qewbragd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcylkmy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovetkteg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkcthmi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrgmgpy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zimtxtoz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qenqjfce.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2culjozpb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cypswnij.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bqssdjib.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdxngjv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzbrnyt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfnehdu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fayuktbg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xiztkcbn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tplubmzs.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgjcdpc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nbchmkvh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcucjkry.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvyeeky.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcyexqx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2chxoxvbe.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvnjerh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfplfqz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywufmzra.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfddvqv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtjssnk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sabavuzw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoksghw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfdexvc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmxaevg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdnorbp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rurqfnwg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cymyedaf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2twpmhoav.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2okrizcom.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vecspedo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lejmigpg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoluqdx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bejooqar.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2racneoan.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwfvvtu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mflyiytu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2opebytnn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2djurxisg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlvnmph.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shtgrdls.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fqckwcwp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvbrzni.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxfaupb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsscdpw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xkksrydm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjcjgnp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoybuau.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xegipqrv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrgizam.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xdglmsov.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjxqafu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2czyelfyi.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cjscxvga.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ojptyepm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2czcbkpep.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyctqgvs.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqwouwi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtpfavl.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2awtnpuim.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mmselsuo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqqftzn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2phjixezt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxcwstj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mztouhde.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgoqqfd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgpihzf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjsiygm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qguewojn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2apcahnhy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jecrcllg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbmquyx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuneozh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2juzphlit.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiyevba.html


<!-- 参考信息 -->