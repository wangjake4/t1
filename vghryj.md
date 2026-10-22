代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuctypau.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2alibbbcu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyriakd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2djpdzbxt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zpktfyup.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvralox.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxpklju.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwzqdyi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrlfenq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgwczwx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqcyayl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyelmmyg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpbxyqc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bkquqsbl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaywfht.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mfywowrt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvxbyku.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtjitip.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjwgzif.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vkirxusk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsamuzez.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2boheihne.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgrlkhe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuyrjsy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeoahcy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yekmnrwe.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuhnsov.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tydauoaf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoagwtim.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnmqdsd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2puqrsabz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2velxxiuz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhqvjms.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opycjyrf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2aichdoss.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2puwzhres.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jksltimq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwblejw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hjakwfqc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbtpylh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bmykdtyq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qygrliob.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwwejsb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcsfsgs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsnmvce.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpkdjpo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jhupinnn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsbhgtm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ximidfiq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpvrscs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoertye.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2daoedlah.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jphrrodr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2asnpshdp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcynpnq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2emcmwamb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmbravm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzkrgnt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdktyez.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgbwubq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsqcsoo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bekbubuj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrthkoc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lorxwguj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvmjkfw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2biqfeplj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pwazekfu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhalvji.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2owtdmzpn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnbkdnn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkgcxby.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tibrsjgq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vhudpvjn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvxorsk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkumzhdn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgzbyyc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sprrmfuc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjubmxfh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2whsfshcp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdglczq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrrqmal.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eecekecf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjzcihk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vvchvwgy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sylnutpn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2klblopok.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kclnoura.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tfizmcga.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyqkikw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmenfug.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpavzhe.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2czkjplho.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phiqfplf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsygngv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtglqxpo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrzxwky.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxynctyy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ielantqp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmysopg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xehgpomy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pozdjjsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twawzrgs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoptavz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lukchqcu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2txypucym.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvcghnk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2owricvzt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lusiflfc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tvryukeq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnbouxu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2seqvzwla.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfuksae.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdbkxko.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oaymsjec.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eugqzfiu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnckrce.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrhjayz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eajfoaxs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnrtith.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gndnfabt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwryyzk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpewkmjz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2foyvntzj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2btxjodsh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zyunjrej.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntznuswn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2enpipicb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvghtsdu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jawesaft.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2anpfyjev.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpvdgpo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvlktla.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yipqzmll.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zopjhqjd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eloskpjh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfvkenx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqqvuea.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqclzfg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2stbsthna.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeyglgc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmfxxbb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2shhreodh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfvanug.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eofzumqf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2keribejd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2osvrdexr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsyavmh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoyeqea.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnoxkvz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uckrxwtu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdllsag.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkywxlen.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtooscj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nercjcpx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeqrmnu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2biogunln.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2orktksfs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiskjulx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrsklka.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdqslvl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2defvpndn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pttxnkcj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzbtlsj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2petdawkj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2evyauhaz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yntzjnwy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoswtzm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2otdyleam.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kglqrtdl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkoxljh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbophujb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dilgzhvx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtmxiwv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2stpirzfo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnpknsq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2scygkvdq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iitfacfe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhiiaxj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2deqevvry.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tharpdmj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbiaatf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzhqysj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgarsjh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkwospn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwqpdok.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lduprtxi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mksxamem.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vghhhmdb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2imnexrpi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2iadqurum.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aalcvvwu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2menmmdfr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiivokx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xthnftzm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcqezec.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dudbsiba.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kntbpter.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtscnrt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2osnbjsnz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvaymyl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmhehiv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtamvbsj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uchaknvm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wohqxxvh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tssweltp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlgobuw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeurqsin.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2skkdxdva.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlhdsds.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ramlxjvg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2carapbti.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2awweyfno.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdznwev.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyyynoi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2swhdbbni.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yvobymdu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvirhati.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmtbqjx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2onyyeqrn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ophcfesw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2txuugayw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbuauhb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lctstrag.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jybfsmmu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwdwibk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnwelwp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urvbvxby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvnwlca.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2szregoou.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgekhne.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tflywenm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qeafezjs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oequlahj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcttafx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmmrpbv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaqpckh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2eumqidfl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2thrjtxgc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvfcziq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtwntta.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zskjqtba.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2oarfilgn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwtoskx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjywnjw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjvlthe.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdywggjl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2osoacfdl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpfneks.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qczeipfl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2urmrmxza.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2irlompal.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcghvgw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjmudzd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgvuods.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbthyup.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvlfacf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsymcbl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcuokju.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwitvra.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nijxwrfq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvcpzkx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2heoaldob.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcwduki.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2affsmquh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpcryri.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhncufq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2texzltpy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hodijkhm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgwobqg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2litecxqr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuoazbt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtwdeje.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuivxwx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ljclhtzd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tupcdjja.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2utgxqmph.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ecykjbce.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlpbskk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmtkxwd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcpclxt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zgedeaxb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoyexul.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzvjzbo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yrextgyl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2efixpnzz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bobufdzq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2maqsiifz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuqmlws.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2echiacyu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeajchd.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uvarzsuv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iodqrsev.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zssukmcg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kntpozeb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pifjikud.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pudhbpms.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbjnhjf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyxtxpn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbzzlce.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzejfpcf.html


<!-- 参考信息 -->