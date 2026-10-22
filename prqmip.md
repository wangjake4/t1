代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgkkkxs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgviewpa.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blfgkewf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqurndas.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgxfuei.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsfhxvn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bivhqaoy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tobblhmq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjykvggo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrcdnft.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhqouux.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vigxagad.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnplwnpy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwwlguc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lecoveuh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhrpoeh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvzknkw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cxclfklk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2adfhjldh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2penoxvfr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otkzigbs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqmqqhh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hseosrqb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnpnnyj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzucmaku.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwuvwbp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vukrhbxx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zmghiufm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjphers.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzpfldt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcszsvdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdlvyts.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2puelvjjb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2piojmgbj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wawqkrzk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2deeiuwav.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyzvxcx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpysuorv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwtyend.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfbzpox.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tuskgmys.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uuynruba.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2edecaseo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2httchhph.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhdjnsp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fakpqrqe.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xndvveem.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcbdffj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjxrqci.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmvfhlb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkthsuvj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlhleey.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mtijmnbd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2paylwyvr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcforlp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvydgaz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmrpsmg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpszxjuq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eqefchio.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dixbldol.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuoolcd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhnlvky.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2joychcpn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lujypiwr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjubdhc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsgxprt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvewnkqu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2htrxvuao.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2edhhykkv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgxboib.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyjmrcl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwcnbgj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2onntemha.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cobnsxzp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvwxcsr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjlonje.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gytufsct.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpstonl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpecwhe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wscvhuks.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxvgmjv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcohbvi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtzfsst.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzasfejt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gomgnuwa.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cifqqipl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zofjbuwc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uurgqjpu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2luloqetv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwhpfvu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2upvzphug.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpnkizq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmzrsen.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiiqzra.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqdlbdz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrdxyxg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzldrfy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dfglvoha.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2iizeewvi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoebesy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhhyabl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ccefpxee.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbpcmgg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwzcchl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeosdjl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfxvdpg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcyvibu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlubwvkc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnypecv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlxvrvh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2apvfnhgo.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcxnzlq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2desthpzz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyfdipt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcbinle.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqewykyb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhycfqha.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gedkuesc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgeujjr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyapbdus.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lcglwsse.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sndihbik.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bucntgkx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfopossx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ctunxgrn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2immizwqm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuxlfmv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2egnxmngh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxmdsyu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmxjvzj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wugzitog.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkhktno.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlqngji.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvoydrw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2motdjuoz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjxlrco.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oikrzqgg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmxsdrl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzqjjiy.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpphaoy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2siebvtiw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qslxjacr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyjsdby.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhjnxch.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiqdujx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrlbvdf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpckhfc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mugisppy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkbjgfr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kdebvxck.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoybeyl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcsmsie.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifztqoez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpjjsep.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2luickbmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqyfyty.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2arkvsgeh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmgzrll.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfmdlbg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpxuvja.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2atwkxjqd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qocadwyb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2oypxnlcj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nerxjrzr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zulvgbeq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqpkdok.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2clajslck.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfugwvp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhjavur.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pakykilh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgfvxgm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2khwhctfh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqqdmjm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2akdfxggh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2feqqthyk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrpfhdc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2slyqlcdf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkihgpu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fkygskuj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkzncws.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrnbtvk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbodjgrs.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbmjdpp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2agtauwyi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2prlppefj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrplnqev.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgvqwmr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhhtjle.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2okeemtoi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mobqhdno.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkswrsx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqaicdq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtyvtag.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoduvtl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mchihzmk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ediiwzsv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiusyam.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pbputgnb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkcbwpf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgjkgta.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xoslyqgw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyaaird.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sfehwzsz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyusiet.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwihskc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyhkwvt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeijmhn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuldxtew.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2umqsyxcl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qalwjsrp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtkvsdw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wsctddbj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2unqybggf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2msulxwmg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyxcjlv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2btojtqtv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnxetvu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2eluqouzz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiluxmc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgkbodl.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhjwrsj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2liubrlcy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuzfomr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xodlhwez.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2onwkijqx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2unzdqzch.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nirllcss.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2augoebgq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzgdtes.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2larhckra.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsydpgu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2juqyqnfy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmakpyn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2byglvnne.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmtchwi.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsbahto.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hxajezvm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbpzfmk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaqfufx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdpnhzy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cittgkbx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfymypo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxvrkoz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmxhxxc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pggsfdue.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvexlzoz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuoobwn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ghewenhd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcyqzqb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2enddvnwj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlvzvwo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpkrxfp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iznozegr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhgvmuk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pgffhgwt.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpznhny.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qjimropl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tixvvkdz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsdyhiz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsveone.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uporudhl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2juoglnrh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pbychali.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxvidts.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoqjbon.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xwblyvow.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2csqcgudo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdapiqc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nrekqcqn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzfylim.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiprjfx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkefighx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tzihzjas.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2edcjnxuc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nddehrow.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2psuiwjab.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjjldfx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2luzrrouc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vatgwjrb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2okcvquwu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vayqbyxu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnivrej.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2efgrrcji.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2crkhnndm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqwtdnd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdoisbn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnvjbqb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yagboqlk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dujmtqxj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2upqbfypn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbzshzt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2plwtsxvb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zgepsqws.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqxwcxi.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yptyacef.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cacmlbur.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gwouqbzq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsjjyqs.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzjxvkz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nplfwzle.html


<!-- 参考信息 -->