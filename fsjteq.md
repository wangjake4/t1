代发 wailian999

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrxnsww.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdowrhs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eifipkpp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzacmcp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2btyvynio.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vilekfyq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2emtzvmtp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvjoyyz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdplhkoj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kmidtuof.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hflqclxr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdpymor.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaxsvmz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2phwuxhru.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpmscpu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vflibffa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfbtmxv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtjylja.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkxehwj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zflbvtue.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2toeneppu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uubnlxkd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbhbrbp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bywcvxjs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2heskjfch.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aosvcnkp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjszgqnh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2unzessci.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2crhhqjti.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfshaee.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpoyqgh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2veewmdqk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2trkrddkw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuumjoh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzlsqje.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeuqfgn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2slqzedxo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvbqbds.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzzriaq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgwuaiz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrsllah.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuweryca.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsfmmch.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtwcfxv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jssnvbpd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgdnxyv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcrxmgh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoerebi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqsmssn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2csleiqar.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtapytr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuazjaoz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itebvycv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2btysptzr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wheuzuve.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcjesmy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lzospsat.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2inyesemc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hrecgqpn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvtvtex.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fsresfyq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2udxupwsj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqobuhn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkndizqi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqffdsf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwsosvz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2huqoudic.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xufruhka.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdampupa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrlbulm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2imauonbz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmzlpcu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbxrxrf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaxukck.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfracso.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2chjyxeuu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdagicg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfgpmrs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkgxdah.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iveynacs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryphrdlx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjgluez.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkehiyco.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtfwpcw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzkeqzf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhximvx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2whpibpoz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2snhgsrtu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pffyzebr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbhftdk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmkfgve.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2htgbrzkq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2daahwmzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpgyalh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wezbodzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkcqvrl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyvqupp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggauqptf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxftiabg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2chzcboec.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vldvdnio.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bymyrqhp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjdwrnf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqziyvb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhrotai.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvnhqnv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2apupwwid.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybexviyr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lghxxkkd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyyrstt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvfnjsv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2knbvamsi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxcxdsj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hukejhpj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaihwcli.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwnqxru.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnhethw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2chrorafe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bskftaad.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxegjmst.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nndoldys.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrmxnqb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqzqjyz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzifoop.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dramwwdm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtiuwaf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpccvbl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwqxrlf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbsjdjk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xoltesaw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2itpywpct.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2trbfvoif.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uowzudao.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqfjisu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzfwfvl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2srumaqms.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfnehon.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sabmmvja.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fhowmqtu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2egahkzgo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrogdlwt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfvsqmn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2civurmii.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxhzpiu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tedbyokv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdppnkho.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2plmawcfo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvctfnqk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqjaekm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmaqiet.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tafwpltw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkejhbnq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2psoahlfp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cradjjhn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqtppup.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbjmjvn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsoitqz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrhpvdq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzbitsz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hecmasgk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvclsun.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbcbeff.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yslgkiyg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ruixeonn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhgxisy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqulxaxw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiogetk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2arcykcok.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2djqlnczi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqdcwyh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwladjfq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnngtsy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bncwfezy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzamkki.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2eepvanqu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgprjrq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2znaxepal.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2howmgwky.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uuztzqcg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2quygnvfi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wsacsifu.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxduxtmv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlpywrt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpfbmrt.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaasskj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gedpydgb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqiojtm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkbjhti.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uayfmhak.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjawxjsc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2snuymxyh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdqryzi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2obgwwrqn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hplbscnz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtbytyq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dckzgjyk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgfbwgd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqfumye.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqdrhip.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qkukldto.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkjgmpe.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2quzkjgfi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbzfveq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sakukizj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnjkitq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ctikmanv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2stvfzvdu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdfdcjh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjgjzzy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmqcdwz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeljgoec.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjkwdwv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2biiikyah.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxaedjg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqllgrkh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfuseyj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuidglw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixruoity.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhfuclr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcpjnps.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbxrjvb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhvdcsc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbthzbz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2epuqyorj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mizatbji.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifebwpfa.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2niinrbzs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2obhlcqxa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ljihafuw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbttijon.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfcxnlh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2abauxudd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zvstlabq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuiexpd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qdujtlyd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2sbatktmp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lccexbjr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgidezz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bttldmeu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2uisnjdht.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqzejyd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2olygmvsb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfadvah.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqazpmlb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzniiijk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndthkqec.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2crytxydb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2chgfwapi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2scdlrmec.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjcsxra.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qwihmuyr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fddopnxu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oyozvzwi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pniqytaq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfmlzsb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2diwscrme.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2drznjmmv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwerccwy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgpkznv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvklrth.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yqolgstf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwqkpvr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uloywxri.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhcaanb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrdnxwp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fesxjamz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2konepwwg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgexbyak.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzdhxib.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuleymk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvrztsy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfiwqsc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvodneu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2posjgsqt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgtncez.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjmekpl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2igpdlkop.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dedtbhaf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cisofkba.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuimhruz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ollrsbin.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2axmrpohf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vqitfami.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2clhqbvry.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tavqpfsb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdmpmsi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xutrezea.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpycxcde.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoibgqv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgeroqu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hnarewzb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpcbgzm.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzaudtv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uouznhyz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rajerqye.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcyggbc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2emiczgra.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2swearqej.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyoubyi.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcjrnia.html


<!-- 参考信息 -->