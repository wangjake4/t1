代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jblpkrze.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpflzbe.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdaxsxk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgyrhgh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvcwqbv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeznwxk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2otfuahsz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmgynvo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hddhoffu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbcuzfb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrfpxso.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2omvdchik.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sntubbin.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2syybecya.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxexigmy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkljbfjw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2itjvrpsl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2acbcfnof.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2igcfkvnl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gctmprqb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiypqwyw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgbsxia.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhzmcii.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yiimfspk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvfujsz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlupksep.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmmgwqn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyapecj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhwumqt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwwuvnr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpkqjur.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxqqnbk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtymipu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvekvuq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gllmekdn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqxsisk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmitnps.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkziepzi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsopzal.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrbuqof.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjgnppl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsagdbv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcltfyp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hclpkzvh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2umerwoby.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxjybbq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzloctc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqynqmy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lcixofak.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsauoprh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvunefr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsvrzli.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwniuud.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmenjnf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbndhpe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjesxpkw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhwmjiq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mquyzetf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2avjjstlz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfeomeq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qpotabli.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqhxmav.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2llqbtoia.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2amstbxni.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcgxgzd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnsbomh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2okcspbnk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrpjoco.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2usuxepjm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwlmjzf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyrjxxo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etmtmikz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2luxjrpdc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzkyslh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fjglhrwe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziziulbb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrapahb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkeirbu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayityafb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lefdppxm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpunevxd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2inddmskh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qdozlrrs.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2icdnpafs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyvojih.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2djhnhaow.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jutpjyee.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfyhcnb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyguzpf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyueawz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoxbdli.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iufferpk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqbirrd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuokwwn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbkrjvx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdtpekz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoaeazf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdonsmv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzlqigt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcbvesz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tysnmsck.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpdhqtb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2unxuigsb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2prjyolpc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmgukfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcgymht.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbvxftk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uinfgjpq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2msfvqryq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrotxsd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2udxlostq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jitzehpe.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpdftne.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbczkeg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyrzzvz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgyuace.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqxxpjr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuxxpqk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vddpcatq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhmcpza.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2trqfbvjy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vazkymlg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rxndzezt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2otjrtpal.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ingkrxqm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fznydftq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzndmjnl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjrxkxg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2alwlvuad.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2shmmqtyv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2udwhodiw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eamkirul.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmnccxd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dheghexv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2daesrnyd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwgoksj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiboaxi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcxcnlk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yobdttpg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbfwrxo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkpfkkz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yljrlrwf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nitkaufd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyovdenl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvtkplz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkffhte.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mddjyocq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2idqlshmb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnqffae.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvngjhtx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqhljqs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyryxso.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tssmrdef.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkywwcn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xcptyjqf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2twcwnizd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkpnkxt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtkutoi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2swveveio.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2smbhibkf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhjjadi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjqngbb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpnlsqs.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzmpblt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hteywkah.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdringfu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgwjshr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvrnurw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkllook.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wncmpbnm.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hderlgjm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwiybck.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfkqobz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ocabmtic.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2niwnswhx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2njgsjmwq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mxukfvsm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuhbmxx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cowjvbnf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbxkjbx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuuhvwt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzoxdlx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgvxtkk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vnimspcv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdzpwmq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnglxpn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmxazgs.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lqocpmvz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvggrba.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqmgoji.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kmormchm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2surqjewj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lleiwibx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dguxqrtk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pypotmls.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tekelddv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaeepjx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcimfuqj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnltjuh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqudmair.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2srzggpji.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxwtepx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrytumb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuamryn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjdckru.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plvhoumj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clehbkud.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzqdyzv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvdlybl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ismaihxk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzylzyga.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2urhtmwfb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wubflehy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwxamor.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqwflor.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xztpkqmx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2haqmlyqw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jsryajxw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjrdxaz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2baakvlrk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgulrukt.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcvfluy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2phidldgm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhoxmbn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqfsqsj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzzqdpt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgoqmez.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gupttnlg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfknxqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whzieyqy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtzmzhr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxzfjln.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjxuaxn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlixrit.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzhksur.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wyofcnua.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsthnnh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbjyrmz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hckfvysm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhaxzzs.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fllmgmjb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdccegvl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrivyjn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zirbttcr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgmtlfd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mafjaqzt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqabgbm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzeuwxn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2swwmkahf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzhnacl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvopzbm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdnjzzh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrqphaw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyfckej.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcahkfz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvepxlgm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvmappd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvowqsg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmweqoq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoivhch.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxgbkfz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnvrtui.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdmmwkz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpeawbu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dtefqqou.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2chqoeqsh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bucedijp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgtwyld.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rsflkese.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2osniylik.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsxbwge.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwlarei.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkfwmcs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hziknbbn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bipxdahs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrygfhbf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhakiykh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2eklnrcck.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2crbiwvjp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvnjsmy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2eccqwihl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmresjk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bynhisjm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2atficaby.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2akzvjptk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2taiwelfg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2eiunzxpk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2trwcpfrc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxvdijf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdtwkqv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2geqnmirh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwinllz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zhocfjed.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvwjgnp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcmmxrh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ljscnone.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vhibygde.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2echnoyiw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwiumoy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcmagbw.html


<!-- 参考信息 -->