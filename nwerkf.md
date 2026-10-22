代发 wailian999

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fwieeqay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqywkhao.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2patcfcna.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nginooca.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlbkhpn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtqvdfb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqncpwoa.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uglsdjnf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmzurse.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lngarknx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmbbqjq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hiljzwsj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2msgerbmb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvhdruo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrobnmk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nksxikhl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvznaul.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bbspnigo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsavqxi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2anidwbkp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwlqznr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgitagh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwolyox.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vadzzmve.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nenlrfnw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzksptiv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrkbuyr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnzswuq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nebxaopg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwfikhf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdjoszy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xedwhoiu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtjheir.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjtgxsp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvzkznm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkxpihj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrwwsto.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuppvab.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxqjppo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uknliiam.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmnwgct.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdygsrp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2guhczcrs.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiphzdr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkimwsoj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuyivje.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlokgrva.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlznvct.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbabfgtg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2phrblyzr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2balvfuhy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nazzxvsr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjjoigl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2znbhahmz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2evkippjy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2liivovih.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsftnnm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjneysu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hixnbajf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwhacwf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hieekokt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvfmqje.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdxwvlg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbqcrxt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pazpuolx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ggncwxww.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfxptji.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekawmtfi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2iudvdlvn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmopihj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wanweyzm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2axlvejqm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoonqxt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jidkapuy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uteahmqv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pujgiapz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tycztbcj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2snexsgfd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tpseueto.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdayozln.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iahqmcjy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmihuuo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jaycowvx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fevbtyfc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2latjtzlu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbobkiw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgdznrj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgkkjkh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlmrece.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2adaiinpv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idpfjrim.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwjjgwq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzjmcxu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lefumoot.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cgazdddp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfmkstm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbokvaa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hirapkhd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tlinbvzt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcircfc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mijqedmc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scxzxtdj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdccszcb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiszwqr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdobcbq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwqaqfs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nmankaqk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrjpfhf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyspueh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2llrbulfm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzsblri.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwbmgtu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiytfldt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bpptvyhi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2grlmigua.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zzojkvkn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2izccukob.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2usznhrro.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2znbryych.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rckiizmp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brzsqaqz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxpvzfx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2avttjvcb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qigpiifc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzmfgpv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jslfxxjr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2crrluhwz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxghmuzv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdautbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjncfid.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiiuqar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wolmpchq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmjplil.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2umfzsotx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmjjwtc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgfifdp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2togdrdrg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2puhqjlmc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdqclos.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yokuqizi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nfurrlco.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2icpewelo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqihnrj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeikzyf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaddghd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpzvttk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrysnpb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbqmhpb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lldalbho.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2azlxkmvz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2enfgdiwn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2swjzfelo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lmenjeaq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bycbyhdm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pquersnw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqipugza.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eglnctuj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tblirydy.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmyxmik.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvydkktz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzudocz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpavlpmd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fagrsrcq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aywlfrok.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtczbtvz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfrcqky.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvciexft.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmztvfe.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzkehgu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2blsvrzwx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoxiqzu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfimyzn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbdjhby.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rezeyxxm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2npkegaux.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2omzjtexm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgopnbo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2czvufycj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2arwqjfif.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2urgcrafj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2sumvmman.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrldilam.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2otnohrkx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgpkuua.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dvycyqom.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2guqpsvgn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iizwjrsx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmklpprk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xekgfbhp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgpnvep.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nndgzcvb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfykfws.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjnelre.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2moqcybty.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sgobgbrk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuxqkyc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2amtrrnur.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrmlbkr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2psbpwghq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pwllwjks.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgiyxbj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pagmjxbe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdokiwta.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bptypeed.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkjfbkv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2guibmlpb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnukgwwj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjpzijd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpanwrr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ythjubha.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2imqiofxt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fxabhgxq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2himnrefn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqinegr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwusrftm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwidypj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2macbtfas.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxtocsb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbauscw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewocmmjr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2huzraaok.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kixalbme.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gcghmgph.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vphbxkft.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2aujhpgsp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agdngsuv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvyxorr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lspqhitb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffreyieg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mowmtxnq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnsmuyd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtydbykw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhweakj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtbexxy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2evedqwud.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwonxsh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwqsgyo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfqiewr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzflleai.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nahkkdva.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqscejm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkadymd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjuoehk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlrpemq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdidjpa.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2htivjeqc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfxtfjs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zegazmna.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2budnjxfz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hpifbasm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzymutm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2isdgybvu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2oihzgkfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtxildg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jypgvlxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvtfxzg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaslnph.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gignwdsp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zazleoxr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxpybha.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2znvlfdpr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdexhbk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyiqtgq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2npjlaimk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2azywgtef.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiqwduy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxiltki.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcloqvd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2djhzcfco.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dignalms.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ouulzbbn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tmidtqfw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnqjwqk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpixulp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zcacmrtz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oelegowr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaklnug.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2olkkmnaw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfxwzny.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrutmgk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lmykffsw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvmnjmk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsuglpf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyblehwe.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2motncnhk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgviuhx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2obylmpno.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzeelqj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sefsilmx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fflnmztx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2khocgxnq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlekrzf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhqaliu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjxwttk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzeviyt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsblinnj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2laeucsod.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2frywribd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwmnals.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hourptyg.html


<!-- 参考信息 -->