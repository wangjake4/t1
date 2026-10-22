代发 wailian999

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jbomohtg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jymaakxy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpcmsat.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvpbsfg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmecvji.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfsknxj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgyxjcu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxomoxq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bosntkul.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkzrouw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvtdwtq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjcibqm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lacmioiq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjonpkph.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnbjoso.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kstwdxtk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkgfdim.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxyfnri.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sufgrkif.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnttcxj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eccpppdm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uygwzzyb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epwzsspc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbyrfsb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiikjya.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdgljbv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pzisutpz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zgytudyr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwqvabt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eiibbskw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2trfycwgr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkuzern.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjosgggq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qticuryr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wltdaqsx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiljmsm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjeraiw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsliqow.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaxfhek.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjnjbok.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxbtddd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtlpqaf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmliegn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyyksgs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvxuddu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2byxnouys.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjhbzut.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lrakzznu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtdvpbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvusqdvm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyecljo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgjkhrd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvdzrbj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxfxpkt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fegplmzk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gbspidto.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xntvjcsu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2spggmvby.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kalyxmkk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2enlrzcca.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyrinfe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbclkdq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgqdhac.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wictyqeq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lafeufsf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dalayegp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgkejvl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeqcldx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bekkgegy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxelznr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2czybocwp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwjfoxh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxkaqdj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxiyllx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzdamzs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxkthwa.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmkduzq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2scvvpeoz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtjvlhd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wruwlziy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzpucmn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeutaht.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gupuammp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzsaqll.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2koxegili.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyyzaio.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aahotyua.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdbwzff.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeopvcq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqiahoo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsjbjdt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mftrcpnd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2srcmajrn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfqiaaw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oryhbawn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qjihbvbg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgegtgl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcolwmm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlgwxkm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rycmeeet.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcuxhxu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzdivid.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rpytbkxf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oahjonjf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyyznal.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyytluhm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uctkhdym.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lidgwtmn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2annptizp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2irllqwro.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vubwgzev.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuzpiwj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhofypnf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbsgnwb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqwhvsq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wldtvkdo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2itmnktnn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtvmsbu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyvmktt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjzihmx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2umtbtmkk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhynjfs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgqujxm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zepnpvcq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2twsyrdav.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfblmjzd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfvuxsg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cuotstsj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2teptypbr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbakbzkr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vebsdbrx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2klpygoyu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwydgux.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmrnfoi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2obxheaps.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhlqtgn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2doyvvwyh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnfhqst.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2raakpvqn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtdppur.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjasfrb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzralpgn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoqciwf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ousbrmpa.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2eczsphdd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmiewsh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bajffpql.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqhwbdu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qchttkuf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apibbgem.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlujldl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvxgbsg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhrbgms.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgpcoig.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jthroudo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2obpocmdn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2icpikrjj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhwxlgs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpsywpl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zktiquab.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dalfmbdu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2prajdpnl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhnjkrr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2chnbkcgc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgixfivg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xipqulsq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlcsgwp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eqglyobg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqpstij.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfdgfjw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgqyued.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fkysgflo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhziugde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwopjek.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvobepop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amavxnjw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ogexylvk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yorzzesd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfucyxk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aljwomwi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fbftjsgn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2iglfkamw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nsionewp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoevgvx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ckridujl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpncwncd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzqpueg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnxbjst.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2liybkxgt.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2axcqcyip.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aybhzqrt.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxpfbgu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoioouo.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyonooav.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwcpjgq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfezkcp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hopabaik.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjphzsm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkveovh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiisvre.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyrbwnu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wimpjjfo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ityukewh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwdgcou.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxakamh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2shgejwvv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xepitaeb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuzekyj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnzamrs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmrvzhe.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2byuhlnjk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlbyotv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiblgtv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkldjdms.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmqnuzk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fglmcpgi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wcasvecf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2izdxitkm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cevbiyka.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2maanzfvy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsllzdp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuofjtr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwkiyjt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmyerog.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pxweqtst.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2blsuuqug.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkdesti.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2alhatgdg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cshgjylw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcxjgnd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwfngzm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2socwcxyp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbryaqs.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxiugjm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjfyrcq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfivkyrb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuxsseo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ltejhvdl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yzupcqca.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dhojfxtj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nrljdvjj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmnqums.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qnahbwqs.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cotjthcw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysextymg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmytewo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfbrdtb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjflvdkl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eljckirc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tertffhu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jvazibfg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xhugsmkg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiwsujd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kviklnkh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnycexz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfouvhx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fvclrvik.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqrybxo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zakojbux.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tedkhkrl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ojufwzhm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2cilesqok.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcotmnqr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltysxikh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzsqrtj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grrxecgz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwkqobp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgxtifo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdwtfvn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ttilkebq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2grekzuff.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlnbvhr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2elyxvqgw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2shvbbvsm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pulphagg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyrlhcz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tjasxntt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqoqtow.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbbbyqr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcfvjvl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcuxmcr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwrqbom.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2anewpmuw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdvyxwr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2erlniwfp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2phcsanjx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vildsxdi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2itqqwbvx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrmdbfz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwczjqgy.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2amkcbfmx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmilnoum.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lljfagso.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cunogtie.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ididkrjt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2intdgjsl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vjotcvtm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xenkqcqh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2flcocski.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktadguml.html


<!-- 参考信息 -->