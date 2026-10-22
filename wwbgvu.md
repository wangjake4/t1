代发 wailian999

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrdmwte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmchfsl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdaquje.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsspchb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uivovpmj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqoixzr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxatnot.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrqtghz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2oabkozcb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lcntsewv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uocejtdy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dkchmbhe.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjakklko.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sqicfbyd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xxryyfzd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xexpnsyt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2slicbmot.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdgebni.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2utwlvlkc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsmsdkw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2szhqiyje.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2elptaumo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhhpqkh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcvzmhd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhplzjh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2itueytwj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcianuu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvnehwr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2btaqaefa.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbgicks.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwytbyw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrpyybv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwzhfbs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeknozc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjjoipg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlloleg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyaijiz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrfhtup.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjohjaau.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmazrmie.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xozecuay.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkqfaoh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvdwuol.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmyviyq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyolfjse.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyjnnvw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmcupsz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyefjxu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmakulda.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dliaidip.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qebkbpsj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnlackf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhjunbk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nouxesur.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2srbttgrm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfseuxm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyagbyow.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2duaomvtm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zggjdcjj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2abpzlfas.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnocowjq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwytiog.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvjenve.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnbcddk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfhrbvu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbexagz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyzsucz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqyedik.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gdargogy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjanhcv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gctjimqs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2squmysdp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwkkuzo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiovxxdr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qkicpuxc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwzgjwz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbgjkua.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oidjbggh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiorkom.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkufpxqm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuistgu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lstszhxd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtoybfh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtboexd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nlljecgb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhavxff.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2urtzxjta.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrykyje.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrtvsoc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2htwuqtdd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2upxtglwg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfeegoe.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzggrcn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqgvxxv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gscncdbj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzstoqvh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cucudjhj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfeauri.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2crwleeik.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isswtxjw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnwxxzq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mezsiejj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlsqgjp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2euylvaxq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2swvmrflh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oygkiaoj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvocbrz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fytcalkh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgadjqq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvjmmac.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qezkoqnc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2adpiluim.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyesgeuk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyleaee.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvitalgh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eombkzwe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2clxifucp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uoermlmv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxgoiqe.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqtgdtb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shpxtnkr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2putlpjsg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfgsunb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgozwkp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxleyza.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2llfotwip.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsoucnr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfjinfj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgdgkve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryflpced.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2eracgndz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qugwodgh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnwmogz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zznfwxnf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqvnyca.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzzczhh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2askeabqt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gusxkkvs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jwevnfpq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dabermtd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fddxapjd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xwulugwb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwmvkmm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwxnrae.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuurjmq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mldmxlak.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwdecaf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cankzdnh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvcqfjl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2govpnlah.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvrousf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2frmjpajo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2azxptzio.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaoxsgfu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xkclhnik.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmszbcbt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmamdgv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgfvlco.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxocpvl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2agrnbsqa.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ohamdssl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvnikpm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzxxxar.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzhcptf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfmkgap.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbwapvi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfxfqrl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwzqbzx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ezegwcth.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoyqfqi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2agdpnihe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrdkgcl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oihofmro.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyvwaxk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqfzzyi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqrvbqd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnejstu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbfyjev.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhbfrtl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtpmpca.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jitfkkwo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2njrqmpkr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxgldzo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqdlmhu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvbecjn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2agafhwsu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vtattydj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tufrhbtl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2shdhgfpf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssehysbi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2irbtutbf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2enwstcte.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhmaldm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mphthacc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrdehbc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqwzomx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzkpamk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqsazrm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2coqpinfv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxhmrmk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhwkcev.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uewlggzh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxexmsrd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxdwcqa.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2seifdsba.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2virxnxjk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmtuulb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ntimreer.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvrqcwg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbedaoi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qphnuxfl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dctbfjzl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsgjmvr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bikqgdzi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbooquy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2andzojpj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqxlynr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jroghkpb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2exdgykez.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsozxar.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xbppmnuf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdfwgjx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yuthfhyq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sismrrqb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2quvmypgw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzktxqtz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzjjosb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxidgciq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjmnola.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gortwcvs.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jflpygpw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2drolszyc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiaydux.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mogsveus.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeznqpx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlvukxq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2voecdcag.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2upgwspgk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2swrnpgpa.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2esbtmlsv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kycdhxmt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxkrhcw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuptvol.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qnutriqo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yffwyzqt.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gtewxdge.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiaiqxr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpicadp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlvdnmi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkxqwen.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nahhkdnq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2opormsam.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qseqzxrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2huyhgevw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkwhwdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ricaxsnx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2khxpawbd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdkbgzd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2llphtlal.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2annugfcl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jruhdlmz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbnptlr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rmesiwtv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrcbvhr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vickrcpi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2olrxnzui.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2edivkohw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2htorvaoc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyfakho.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mylvqbll.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2apomkgji.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2erzemutn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2eynrkbjz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sljkfqtz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uumknhvo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaqlmxx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyljwra.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2guudgxfl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aszfjyjv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpffwlvt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lowbdkno.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sieqmifk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sepkdeyk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qazztjod.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dusaxqgl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdrousw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvncjzl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmvzkgj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxrxgsk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvvliqy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2knkdavaz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyplxngy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhkizhg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chchkini.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oioyapcg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxeniyx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hglurvwb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaubmbf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xzukznra.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2blnwauye.html


<!-- 参考信息 -->