代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tluhdmoi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvovxtp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfinasqn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2caikrvby.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtkomgj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgfbnib.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyzukxd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkspcbe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgjkcol.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nitlxgyc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qyryrhsn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2csebfrib.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqglfkg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2alwhloob.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwahkjh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdsqglw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mslhhryn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gataeebs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkjzdhk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbgdaps.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfprfkb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjbgiok.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwzrkpo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvozurm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zudvgtjr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2geauxauu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnpkvae.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbqandl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfxdsvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzinimjr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpmxmzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aavbjwjq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoboenp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlzlaoy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xizixern.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xsywzyfw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2behkurfo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2shcxooxg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2avwgkbpc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aucysiuj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pllqsget.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoeyfbg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfjvpmw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2szptuzee.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2okzxdezv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnlufcr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mofmgdqq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2psqxdpma.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxagqkx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgctwhwi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyjhhyq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvavntkf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxxfqoz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pktnjelc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgdgdox.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2adfycmxy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zjosobxm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2htnbnabw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fznuwqnf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkvjxzr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2awtwnhdq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrcrbqi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyykrjz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aahnmlrz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2twroupcx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjccutf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2slszhdif.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeablcs.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2odchywpe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xluoegvu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2irfvtpyk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2exdbjlad.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjjxhrz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hknrjkcy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeosbgx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqnmnlj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvjygyx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybulgsxx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyaeidq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzszzdzg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiewhen.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjcoydg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxylebj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyqxcam.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzhvuqj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2psnakjiq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiqrjtv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkadymn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrhkdzs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsyzrod.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrndbes.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrziqyya.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2atbdhals.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjofueqd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmobirjo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qnasrvba.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2avmpjefy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rvycoapj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xadbdpvr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2luzsvqbu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xrewyoam.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lxigecbd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vttobotz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jppzohme.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdxamlx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2euzrimei.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tudiapdm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nkleduyk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjoluvt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2glhytlvi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uigkovhg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfegbey.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqknbyy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2oktqviwv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrquipe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gviqujrs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2donuuagy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2eapbhupq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqojdbfr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtohjma.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bywewiik.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nftmydkq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzazcmf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euswdokh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpphvky.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvaazmc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrtdsev.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gypwyjps.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrstpvey.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywscmaah.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gantvqls.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2indeuofo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdueardx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtbdnvl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkcghqx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzoanmv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ihellrxi.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrrolgs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdmhqdj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2szbphqlt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmfvjcg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ijagsfbh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjcrfod.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gxemsdzo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uypoyroi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzxeqhe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtztuirw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2anvxqdch.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbbsram.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnzthod.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2irxsximn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ahywgvkq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vojogmjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjuugjn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hinatsxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsqepuk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlrmuqj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2imnjjveg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2twdiwvnf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtyghqj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvmvgfu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zapjgrkq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkdppeh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2givdksjr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqjvoap.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdijwquq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcusiid.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrttutha.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2miedyfzb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsferaoe.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkfruxf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cflfvhlk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kszrjdxu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2touyvqvo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvnwvom.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2uykzaiga.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvckfwl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tysjwuau.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiqzjgj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlejury.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqqxmqd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oapxvttp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mijjtplf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gidpfqsl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdqmoun.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyhoysh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnjupcp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2biuawzzm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcwrbrd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfpfpkd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ucohluqm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2llczrhvk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kshfvkyz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzppuryd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpreerw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfsxlob.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hkanmpxi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yaloewkh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qkibgons.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfbyprt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlarvvtf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkobiji.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hisgsini.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2prbasaco.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmaargv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoxuuhw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmavnik.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgdubsz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjngwbg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iuomzyyl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdqeolr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2shaoxgpd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuoqlvk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uzedrrsp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2msttvwsw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaoiwwy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbtfcat.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fglgyyym.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvkmzpi.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmztdhj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcjnnby.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfygeay.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqqjhdw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrazquwj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fndelzwl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uerllwwc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zomrmzvj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyewmoud.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcjtaet.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fpikrwgz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aalnmkrq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpckhhw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbolpry.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqavzeop.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ebczbeea.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnriogxz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mwydvezi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uijjmwah.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyfrrci.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsblees.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvdvuwm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2keqrfvpt.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoallng.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpeapxo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nuubbsou.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dposzkhc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bssonvin.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cpukcuqj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfmmdpd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2npyqvuxu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcnkewe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wirfdjwr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wrunpabo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsqenmy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrcqwmy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrxiowj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lbftnfto.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wswkzuec.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdtrqni.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2atydwkgv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfbomgk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2beysxtdk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzfnimj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2glamoddp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2usmqrjml.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cihlbfex.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vponrfoq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqmqvpd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2utwfgqal.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgwszly.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2aysfwkbq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2njzzpnit.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wyznvviy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bccvwcru.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjfuqua.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkncjhj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ziskquru.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2otwbyfpi.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvtrdru.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvaidnx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ablqphaq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kknihrha.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjbfsvl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2iualzkbt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nldlqvow.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjsxnxp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hanstrvp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmzqvry.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbqtwbz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjebftlr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ihljtmbt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrgbxqn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyvhfsx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyzcumu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eqelwyyd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2uvalvnre.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzrmenc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzfdflh.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2udapxwdz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qenvoine.html


<!-- 参考信息 -->