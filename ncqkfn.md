代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apkscpcq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzdbzej.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiuuitf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmfhtwz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceesoiil.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tfifsfjl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtrjbzn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2htjigvzg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyftvrea.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbjdegf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhudqlf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2twtccwxh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hnulmqbg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2spbndikk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2atdgzljl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtnapue.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtuuyyu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2azzvreea.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjtmlzi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyiqapn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkonrvp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qddsqsdy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdbvpwb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyolnfia.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqqptef.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hivdwwyr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrvphwe.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzgvoem.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlzcnpp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hefmoqum.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyyxhgg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2suewolmk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziccztsp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nprkremc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2usmamods.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2whtgrsor.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctehfmxi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uadbxisb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmenmzm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eushnepg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcpdizu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhjwydn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgunjxuw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jifgmlii.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfptkoy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrsgmkf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cthxpjad.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vevpmjnz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsnlzcq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uukbsgnh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vigvbhaf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2odxeqirw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcocvwfu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dimhervg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuftjlog.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyhxzha.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2puduvyjd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzvzmkl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgurlae.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ynncgzuw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2febgttgl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2heeizuhg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgbypht.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdrtiug.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwtvfuc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvymljtg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bktptmgv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqdkney.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fudwffnd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvzyhfh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2egogpmbt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxhwlpk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zucvakib.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmtgzuu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xohqtyma.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2awgnducv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjkyhqr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nplxyckk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsafmwe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2akiuzxoa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nglnpewz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwzrbdj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxhcuew.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqvidnc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpihpkkc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqugqxs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnebmrw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjelixo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkoocqn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmiikxe.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2stcrwzgr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfqysqp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvyumde.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pakrikcf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwrkymq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmbatgd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaqauti.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htlgkmqz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvorxkzx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnadpfs.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2slkxqwyl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvtlcvn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yaucvjwx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxmzefo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlpkalg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zorzbjcg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pewpagbc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcmbrtx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riuxfwkc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zfceixax.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhxaype.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyngrky.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaovtao.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2azbdivox.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2poehdlms.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmcbyzk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euyzmjjg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2loxxbrku.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gublfwkr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrlqaxz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpubuxtr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jxudluvo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcqftci.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lecwqnkf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eklupygt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rawyffkv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgmrepi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyafcpu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lccwplhy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnjqisn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbvvclt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrcxmaf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2akrrlloe.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqcrrjb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wwigmhax.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgwsllp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yexjghmg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiutxli.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsuaozo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2segrqohs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvrkguu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsszfwh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeyuztm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbceygm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2evsbqrwk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzxhxag.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnupgnii.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrkuiwo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2aajuwuor.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cispautw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmgvpgo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pczmsmpo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2njtmlfru.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjkocmw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfwzlwl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pidrperr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2anuqdgzq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfsjoik.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjiwhim.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyoeqak.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2czotvdwo.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ishiohzf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeifosh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwmxadg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2leronsvm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2djygsnjr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gatribpy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxvpurs.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mwveotld.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzkcsqs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxveszv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwdinsz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znnyfoas.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmeycjh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbgktvt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqnxxtv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mnspibrn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfjlbwy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvrgyff.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdrvdqa.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gylxnjzu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwzjrgr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmniipl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfntixf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2arobbnxu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiizmrk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnlehnf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2odflsqni.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsqjumt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrdavmg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrphgooo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qzztduxn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvijwng.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uthfboyo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fexjflif.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqldihj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrdwiae.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ljausjkt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opdzyywd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzrcfxs.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpuwuvs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2irxzuizk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpplnyet.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2flcgkhte.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eevhswba.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwbboek.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmmlizf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqvliox.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zaixmmho.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pssorezm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdvhcnf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2peurrooq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlmopxi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nszpjjcm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvhiwon.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2digjisfm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmkprnj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtloklke.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tauznlha.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pneuobcr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wznqfzeq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeuofor.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlabapzp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2htyslwvh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2knctuzwr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zehmgnhi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmslwudz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvpanbw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvklkmxe.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtthtrp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmvnyic.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnluunx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fgppmgrj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2chopjrln.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlezpbdw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ildannob.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvshroqu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ovejsfkt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aczpfder.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjcuozg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbnvrjv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2viawkwaj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqlsory.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjwledc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qajqjvdl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnoglhw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkmrdrg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zgumxenv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnatojmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvkibec.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbknytie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqddyxs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyecumw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2knjqsgbn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbxtpkl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vlafosrd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fvysuujy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfnclqb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrkeuau.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wdniulqv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvfcqds.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2phccepgd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyiheko.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2njdfcoil.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtkmuvo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhhxokl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhqexri.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mupweymn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ywciisoa.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpcpznb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kfurniku.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkkxqke.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxkixpm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2erehsfqv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjqlmgf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vslaynuk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2muwfbmhu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqpsgzi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iblciuhh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwxoatd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaakefq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2szfqhjsh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fltqiiee.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxsrqml.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2suttwedb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wumomqtt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcuplli.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvanvbhw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvacimc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xitzupxb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nzthoczx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2klkhswjg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2udnospjd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vosqdfbr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zouiwnab.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2brrsheaz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yebuatit.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgoaeye.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uddxbfid.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrgtdcp.html


<!-- 参考信息 -->