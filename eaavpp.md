代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzmucmz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2htjfyyjp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyjccwf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hknwumyd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tciolexi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oweqttdl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiilyqc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xniukheu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgorjyue.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiccotkq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnewtkfw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxviaff.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2znveltpg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pyosucoj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgslzhr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgchbon.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmwdxbm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgzwcgl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2huhnbanh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2krsuhmsa.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ableaaez.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cprwqjko.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmujbjpi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwpvwdt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjcdpaf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyrxrwe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmeycxa.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2enbtdzbe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rztiybwz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxexyss.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bydjpqoo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrzlziq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnelqyrg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxvpivm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2phqhvtnb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrkgqih.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmwikal.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zviqsayy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2stegitrl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2piatdpho.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgehkyt.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvkhpoq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxvvfxr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2thvkzndv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkqgrpr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nauvwecx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnxjmpu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvdfqas.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eesjnnuj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zznhpkol.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jnawxtdv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2whcfpbwg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpfmevu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dytboakg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlblvwr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nezkjxkk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ddifivhu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlxpdic.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzkpefh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iejkmjqo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwzbjwz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwaqcux.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkslpaw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggstgmru.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zservagu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmmkixl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfyekqc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgzzxon.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyeyqhk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuzzdpk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqomkik.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcqsait.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smzhlnez.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnyiqmj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbzvvgw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ietzziof.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2trycvxez.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzsytor.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bqybyxiq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaejclt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpazbgo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fteqmfar.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2azzdvbvd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnenuvef.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wugmzugq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhanraty.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2assnwbsx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlwkjov.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpcvfgu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdzjgoc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tklwtded.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jeghzfim.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jblwyscd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hfalvryq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2znajddro.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kleharag.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psbmeamx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiogknh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyfzekf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2veteheow.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcehnob.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfoedgr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpscyzm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiafvvn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxotcpef.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2axaeyhkw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxyhinm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dmypgdrr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcheymxk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jusltinz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqakrmzs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2evgfuiui.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhrffke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzraaaj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrrlogy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvnjqeq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbmarxs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkrtaev.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmtvalb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyvjffb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdnyytz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbnroeb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xyabsqxq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2crrwriwu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sopaodjg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cypsuqrk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiyqgzt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jidefrxr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qffcykgm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpqrhbh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tomllxmy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksetowhi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsprhqb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvviyomb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihepdhwe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvlzxme.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wrssraoy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2svsafrle.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbtazpp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyyptwq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzaysvh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdommspk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmmgvje.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgadllq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tetzfodu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqkqfqp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wngfcbxz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkruasqg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nphgaljo.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aekgzhit.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hiapqvle.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwakzywv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbuuctg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gppfxvbf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2olbuoyyd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfonqki.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2awsonati.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwabebn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ihewvtxd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2urzveiaf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwulmty.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qngksztf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2becwhnhh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkirtmoi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzpcnzy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xknqkygt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzjpife.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnnvccm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnewhbd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzshqkzo.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iekboimx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxvklyr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kggzmhyl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vieyqfir.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzezsjn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmwxdsj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qygrfukg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaihjlzu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhqymio.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lqebaghi.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jivvipok.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlgvzvx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2whceicko.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xynkpvyq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxjxyeb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ioettkiz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qahpbsbr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2efvqjjtc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnnsdkw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lepctaru.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvyltem.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsggxyk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtxcage.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksivrqsy.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vdztakyy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2emadymho.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qjysdptk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqkzczl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qezbwxqx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqrxqvu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gngzxtpm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfldwupj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwvcuxw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcljhsz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdbkwds.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nleqhnmd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wglgqfwe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvonlekr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hznhtcbh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqciocc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2knvwfdwq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2biirgliw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2plxphwhs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wplkpqic.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zapwpevc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwdhjig.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhydhox.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqubhfj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ticcxumi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyljjpf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaybytw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcbfesa.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsycmzt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2njsneosu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2afauovyn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlebmee.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssixkpgj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2korddsnx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvufiugh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnpzkpf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmvozhz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ewguhahu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrtuhzi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2umeqtdlh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lailrdvp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvrbkcf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdahayd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acqhomos.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2owjxnvns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsckrac.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2havhsnso.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzvlwpo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ulonlcmj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbrutlp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpqroxn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2iclrofir.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrzawdb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yvihfhrf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsmhtqy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqdgglr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbcgvea.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrcvwwr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ogakksal.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gctbjnxz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnobtzjh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvgjuim.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cofgobmy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzdpdzv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpdclca.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2evrzwxzz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ruglgiea.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swwsepyi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cplevhpp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnppapi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ouybfanp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnstuqp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mclxllcq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwftrquf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvzzrzv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwwwrlr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvqhyxr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dysjucfl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oqizkezx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvfvvyz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hegkfrwd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeikhccf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqdxoyg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvihkev.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkgclgx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2snlxhhfl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwlurst.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjromux.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zffcwhff.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfgdbbf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2homymjra.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiaiwqq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pgilqwqt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjdbovc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeumrdz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlejmij.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cntnjqyy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbclmuu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsrojsv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2szmmxwug.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2prwnqwth.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeupino.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qczozywy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2adcipyvl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2daaztfzh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2efvqveim.html


<!-- 参考信息 -->