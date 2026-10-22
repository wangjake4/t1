代发 wailian999

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wikxlizd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhbisha.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlfpbdl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjqtbzu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlnwdww.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqrprmk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2svextvnr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kgscmczi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyhelhg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpgcggm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2exkucnpo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2amqdovps.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhuhnbu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqinljxy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrvjsvs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoalhvm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlpfznh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2htghwcmg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeljwxv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iypbdxuk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2acdymrys.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxscmth.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tthnesed.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zwglukrr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2krtbzvli.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2amcnvihm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuuwyxq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2viaiahzc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujacacoq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2supjfzrw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwhxtyx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhghpon.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxilbjq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vinukztb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qklavwlb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwrckdv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkapurc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tntijovb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2erxcspqn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2noxbjyho.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2htmauhll.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nfonnyef.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaksmpw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uzouprqy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpwrjgl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaxphvn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjtloqb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwntmlf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gytqohcy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvblpxv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgrvilw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2woomwjuc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbutygn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yucdbvlq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyksaut.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cyscmdws.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdnqsed.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrimgki.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgwlgft.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxeiapv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsaffps.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpqxbzz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdpeyxn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfrobzd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlfvjgy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwglani.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2geyfcwui.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdkrnwj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2duthtdsm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsdhfvi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkyhmot.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwumouz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tabbmiqa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qpekatyl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuxnvom.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jftcmnjv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulawkcoq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2boacoybx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2truaqwbk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2krbojhmh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwbuxpy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ladoftwp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfuvlow.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dochaqkv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnkerjm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiltrlg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kszjuxbj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hahdwasn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrgfaly.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xabwvkov.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsbsyvs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wegqazzj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqxxgbo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izwgtpua.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmcfoqi.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkcsnbt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoyeeii.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhxsgmd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2erxhqlne.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpdvyxy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2innxiuzk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2okgjwagt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqbskct.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqejbft.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiddhkh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cifnwzti.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrmutts.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vixbwzjg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtuqmff.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2knzrakkz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mysatruv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbegtto.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxysfdfu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtyjdta.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2duprvbcg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lztxtpbv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jozelsra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2myhwsgeo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2stmkxmhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bokzkict.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekazgzwz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfriefvl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yikvqjne.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qnixwoly.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2edkmlmgq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2odewzcpk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrjuvob.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2klmaraev.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzlbqdq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cisonpqs.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrrhuuf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkgdghq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2opwihprv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlvzxcx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dcibiwxo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2frlzxszw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amemsatv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fztnxnha.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxfciyg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlnifpz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2veimiynm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoylsai.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pedixyhg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qemeoxwd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2njkijzki.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsdqflx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vsefcwxm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2muzhzlxz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qaohacrl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnphdiy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvlcwmg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oarudqse.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oremulak.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbkhzxv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ldloflig.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvqnwyg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlrmkes.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2byvhxgik.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zjapbpew.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2opskknaj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dupwjdjj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqbiacn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gekhajju.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmxazcd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tiauuasp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sricpbsr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2auyczaut.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbupwoy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gkufdckc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmigmyz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2laibqopd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbkgxdj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkeexye.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgvroyt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lycfjdcj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmrrwdr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwzsfts.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoaysvw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmgcgld.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzonpley.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcadnpe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoqyata.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vzedbacj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkbdhss.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qoybpffa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mmblmvpn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpxtxke.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2byuwcjcd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2khbbwawx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2liegkbbl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvblrqf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdlvhrg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqbzcbs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2woqmcrqb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkkkyww.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyjhkhi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwbkycu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqyrdex.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqphqar.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kseqniks.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bshgwzer.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fclimtfd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwqpbjq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdemagl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfftueb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoeviiy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oomeoxvm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nicrzilv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwyzwhf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scikwpln.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lrekclcz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enzskifx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvbkxcq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udmkepoz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvunhkw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pryegbho.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkfplkr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqehrft.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxkbmeq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2owjtjalq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjwhhls.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2djgmorfa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsubtbns.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwdwtup.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmgyzhb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrfcwsb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfpyiai.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rmibjfln.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwcdrog.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2blhvwtpg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyekkhmb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwtmlvj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgilngca.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rjanepsx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhogephi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxgjvam.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2orryjbcl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwakzyx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcapupvz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlwbtgy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvpnouu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfgefrj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2itcdsvtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jipaibcj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuwoxqw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzlywfa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpqfynx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkbkhsv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2diffihhd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfikmkc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmybqbo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfpyusc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qubzabak.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2patkmzxc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2glhspsoc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dadpnfty.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2obrsvtwb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2efzmfmkp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2moxribto.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfhbmzu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ujimswyh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2orbktcfc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cunamstp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jarvxlib.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2belfxvcx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2orfpolwq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjomxrpz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2edoccqtn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxzcljt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbhfpbo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuxubvo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdvyvqw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnumbnw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvetnkxm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2egkzfkcp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqmeyai.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdqlwzm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uggbatub.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sddxjuhz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2otkgqmka.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2uduowmho.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2llxcccnb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdogkeg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pncidrjp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2avgzthcf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sdubiftc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2obpqsuof.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjcmrqs.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaqxefa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pudfrggn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ikduxrbk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbopsjjv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gitkobfa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxajusb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoteuwe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdaxbws.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2uthqkagr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzhkbue.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2icdtpros.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xelkiozk.html


<!-- 参考信息 -->