代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuipsmn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpurabb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzflintv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsohbbn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrscvciy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcsgmqy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqzfjvi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2siaekszf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeeeaxk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ysksbjxc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrezqtf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2esvnbgim.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcorbmx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2itnwqkzy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvciopp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqgogpw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvssvvsx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwvewob.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2szpklbqs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcuthnt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgufssdh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbnhgut.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2leueqbld.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2shyyhjaj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvgmweo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vsamqohn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwflyzv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwgnpzn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kavzlhrr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvwhfeg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxaozes.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2joblfcsq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjzcopl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mvksuhpt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeajtwe.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2viqrluur.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ommdfsja.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwowoem.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxaqcyr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsdgcfi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwyycto.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2upcntazf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnjjydj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnerack.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmitcyg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aptsujkn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2umlwahuo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uiofuazt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziinzuqp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgzuwxm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2egftasse.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2plpmsghs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxemajsu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvltqtg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrhlqhc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwyfhed.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pulstrxw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hmysoywa.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lpikllpx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jozwtfxr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yeinzqsj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmwiusb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwwvcpk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lspxrzfr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwaqxfo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2khqyixwk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yivekukg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2titccqyi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2itzmojnw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcnmnlz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2levikvpg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfqhgea.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpcdgch.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2atdtybat.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2emmrsbya.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeyjzmy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmxkjam.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwtjsqo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpgmuvm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfjfbax.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsakmoz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdgxejg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiyyyfo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2amclpwwv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsxbhts.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbdocrq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmxjzxc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mayysooy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfqwuwj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2foehgbgw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrcfhvd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkojevar.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpxfxsl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2satwyvio.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2veowveox.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2muueoqhu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeecoxs.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elbkeugm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2daxgpbga.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eynbscdc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmwrkax.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxrcler.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaliaqy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ervzbfcc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjynuyur.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2woyukicd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2waaripof.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2onsqbohc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwykjno.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aginsubu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjekeqhk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfdhjpy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtuuvza.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uaclajhw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2odohpdeu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gentbeoc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjwkpvg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vsttpany.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwtvbdp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsckmbo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxyqbnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gktqnvor.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoyhnkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmauzgr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlmusss.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxrvnaf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2irbrbiqu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tlakouaf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnhmpfo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvtyphf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwebuir.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ictslrjl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvtfisg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhdzknx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmgnjxq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxelikbh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2matdlnwm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqfxscz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxexunv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfjjjyg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuyiauk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgnraze.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzimqjgm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuykrkdf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqmrkyg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sciqfscm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bbimyqtm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hudthxje.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hejtxcut.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrasgbid.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pcisezde.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhvuhib.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yocokkxc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtljpjff.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zekjnjiq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kefrhkwa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nnweetsf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lroafsfa.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiebton.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhxsnna.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgmljcj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgmskaf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eglphxql.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcflmce.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpepjbx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzfzkpi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zamvwthx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlsclrs.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvqcmti.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2opmxyrtv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mthuvsjz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzndxtnz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfwrnhr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpfmcan.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fedmcryf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2offtuccw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2epgmefyr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lapkuovp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2asqtflgt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjitbssv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2slpmsbfm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqmdgdi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbgwacw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzmbawu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmyflzp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmbtncx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2smnlvwyv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tkodkhbt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2phyqxidc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhnosri.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyxoyyq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pakvhzmk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdmnnsu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2spatgjne.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsqmyxj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2onltnuwv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nywihlzn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2evtscqgm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xyprlpef.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2oelsqmrj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuiikwg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqszccx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeixqpr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdevovo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxywbjq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hawqxdpw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2arkaldup.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bssnbhsb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cahvmupl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dglcvytu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfwsmnd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqvcorz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcefgmb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzhwrpn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fttjybnb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flrcnuem.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaytemw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmculjy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2elqucdyx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oetwqawp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmqyyrz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoukpdy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vepkzvql.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmehgvv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhhqdbu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tyunprjv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhloqagy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqsrxmv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2noksbbcb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxvyqky.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjwqtvr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvuvnhd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iylzlnqs.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yifcmxmg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgahiyrm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgpmvlv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzmafnq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmxyrec.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jumljpyo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmnvhti.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyeishn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zshsfllc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2txhlekkp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcqxitb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gblqjshi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ciryuldq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2svzjvzvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqttcnqf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fadpjbxz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2owesrlml.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxkwhye.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmcuzjy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqfjaja.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdthowan.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhhrhrg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oyerciuj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2insmnjwa.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxuhcqf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpsebxd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxcmddc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2agkgqrid.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtqvhjp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaviwoo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2iduetlaj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tggotefw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2insnmnyi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdfwofj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfxdlge.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgkekku.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxzdojx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbzjzlj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylomsmab.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtzexys.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcxvpzf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ssamexxo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aicrggff.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaevzpc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhnqsgk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgcclhj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fioykqsf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzikcai.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgcpsix.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxqappy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qirxkiiw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuktsdi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xihkaldk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvfaxmy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktintbqr.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwulsgy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2igjpialy.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpnusze.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbizqeai.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyfhssh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeljgrh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2enkcqyas.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjldnzib.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmcyaot.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtryzns.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiujebp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjnlszp.html


<!-- 参考信息 -->