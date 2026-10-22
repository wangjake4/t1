代发 wailian999

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjnltmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zopelorw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2alzmbhfe.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2waxqmcww.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsynumj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zmomxice.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mltihqgg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aswhftnn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdtwwdd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeffizn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjkefsp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiwiluk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyxmbfl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xixdoufi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgajpbv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2djsggdpu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pmconxpj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtvbjre.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxofsck.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2engbjhoy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2oempnbad.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2daxeevlq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhhambx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqybqnet.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqwvkhp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nntzenhp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaglpit.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfzzlua.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aakqssvw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tioqmeup.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkhmbsv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxbnkjg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pieywipn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvfcypd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcjmeuk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbjiaku.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2khxpheqq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuifzce.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2plgisnfj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwcyvjm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtjyjve.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rddrqztj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fljxsqqq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaouhxf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hylgulee.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkqatjn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bepeediy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2adffhcwj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxermfq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcizdvng.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjjxjnl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrznkph.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrndznwk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oraeaiar.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iccztats.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfwnwmn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2htlbqjde.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zundracq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrkbyky.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lihirgof.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzumxwkx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqcdiqe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwnxnpe.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zxehmrso.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ycffwtrm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2thpfthve.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kcemodqx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2peevwlkj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yhogikdy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnbrfyq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlburrf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2urvgfjxc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrzvksa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ensigppz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hjasylaw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvcrjnl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2snlxzpph.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwixbold.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2apmqcork.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2argkgvhv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwqgzzh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkbdrat.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnbqlkr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2drmbabov.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cubtqhiw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qyexsljt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fogrbnds.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulecxonk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hummgcyd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfcijbm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsymwsm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2crirljhy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zaieewnc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvbmdfs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wacfkuwy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxiicxz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fslqkhjt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyiaglm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuigjqb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdbgafm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pofnkcve.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkghzlbc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2geqgswvz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqhqwvd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gskbyhtn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylazqcdi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmstccjt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsxcypd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwganocg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwowufd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yihlfsmv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2efosdthd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqrgrym.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqgkrsu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdteljqc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdhwbyp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsnjmsf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyguxwd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltihdjxk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfxbbob.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrcqmkg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqasizy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2myqeneal.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyctibt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgyhcon.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgkuhkq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bagizrfe.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2loaaeizw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2txvvbhdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzehgtih.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmrnplq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhltrii.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uylpdtgt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqabxkx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgptbeel.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2besvxmkd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtpmadu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2owounluc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jjovbqaw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcfnflg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2myhsgvkt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwjrfwl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyjjpnj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtsxrec.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxhigob.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2upenvjuz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2izbfhbpy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fralvqxx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdcuqri.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfebesy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcngzvo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtjuqkd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2auxoxlmb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vivamhzq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbgqagx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziubelci.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aefwkqyh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgktucz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yoohizay.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyscndwl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfmgwkn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxxwqog.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzblcst.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgarfggh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2avugwitc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dztxywms.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyxculs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmaolqt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xysjkoqj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2biatolju.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwxhtpu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqvtvyo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxuufdi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzdhmgw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2magjdltn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiikyrz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgyucbs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iahqjxud.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnlehcq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oigtobwc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zchohkhh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2msqdrapm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnoycli.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2denprojp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uyitbepv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlwfeci.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxlaljo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrozajh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2irvakudq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2idayznad.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoygyul.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvhaump.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcqezqh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwypkzs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkjmrgs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeochto.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwquycqg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xvccsqta.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2tgieekts.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2sltslgqq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbvujok.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evgotdkh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyvinsb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwtaehg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rrshlsaz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwygbpo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfrxbwj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2erpxausw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2raszcoxq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuijlxa.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fllkdwon.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nwynvvaf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlufato.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wudvhhmr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzotjdh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuzzyic.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvqqvko.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoxbzyl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2homcpmvg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzanyjsk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkmvshj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnecoyl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsxjqnn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mubhiopu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rbonymjb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ariyuege.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmpciqb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjnlxzg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoekdyh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuujmnre.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfqqyvl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcromcgk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmujhxrv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqimhkc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoegjsg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjemuxw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2whawyrcz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhevzvl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gruiyqyp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbbvedh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2igjfphlu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2peuthkbp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzhmsvb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgnzcev.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwtrvzm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqlrlja.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjtqlya.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pezypxzq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bbathzhp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdfqojt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjlnwdt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrzhlna.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvohlgth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uspyurgq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuobaraa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhthjqc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2slrqlauv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2etehimss.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjbziuv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpjwtkz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkdmrbb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyripufh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2aabvekjg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbieadc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uuclprlv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2etwhanja.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gytwpuke.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnpvqew.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnvpuan.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbdqvkt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2shozjsec.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2odekelhh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfqrzwx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlhzocg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2axgdglmf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcunvnd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2njiemgei.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aevmlcvg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2knwaahwf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2actfhfdb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvxkmtl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgipjjrt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2koqxweny.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnouyrr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tanzkwwp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvznjwq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ragxijur.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2epenxwlo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fthdqcsd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2eovisyua.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnkeznj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlypxbb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbfliuj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yumrxkjo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsfkyex.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ninvwnhu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2usdzlfkq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwpcnay.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiaovyg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zaezdiiv.html


<!-- 参考信息 -->