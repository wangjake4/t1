代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoqilji.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwmctmk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fisgkjbn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2faysxsge.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrlbjop.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2elmlyeou.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tslymywt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyxiomr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rybxsxnf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlvjovl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrdpuxg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mecvunqz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2keipieoh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ahksqdvg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iypfolfz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbazwxyr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jogbqdkx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsjnnux.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nggmjmtn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oykqjcwc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2komoevsq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtqrgla.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcftplcr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgwikgb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjzyjuz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbynorie.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vudelhzo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2idzafehq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhtwwpq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxdbzlw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqelqocz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dylzslqz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuvfjkg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cpllkyzu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgahelqg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsicfws.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnylmfp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgtlbxw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgfjewh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ukatggsn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdanqgt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vviqfppa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwzfrka.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdhkhqu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqhlgdw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tlalaxvd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dififcmw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdvvlpx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjgkxdy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbnfkqt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmeqfak.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmissgpn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdelqbau.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwdklip.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlfzrqb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbqgtyf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ersdbroj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bomnjycu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbgofkk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyywshg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyuobpi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yimbhtkp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iixfmesn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iryjbuuf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuugkxu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbnljqe.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2oymhggev.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njaghqmh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgfupmw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmodhyhg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2elvcortm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjinoqq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2auqxvpjr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwvwrmy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jikgsucq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfouavx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mbabovsl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvpemsu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxthhqe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhkzgxw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2juppaiuo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lelukuvu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yofbijcl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcaxzps.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaezfec.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqfmftj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyraphu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdxtphi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wptneqem.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nkudgkug.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2drzpwkgw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyggpyib.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfwwftr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrurcfn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fupzifvg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oliunwni.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsdqjoo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lltcjrte.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nftcfqjc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrjqhsr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbapmcwu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbykxhuc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vbosqafe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqhgtxe.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bneynapy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2txfcuxis.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpehnae.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2etqmxgtv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcathub.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgurqqp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2axipcdli.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlowjjv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtgrgvb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wabcojxg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yygwmmfm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lluhgsrc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2utnoiiie.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxouxsv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gybnsjgh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kndrbyfu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2okxvypgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gelytwjs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvouibhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdltlcz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2augyxppo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgjlymt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqzfqap.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkidjjo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxvoaqh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyomodx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qivhdmlu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkkqskq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qwohofwx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxcggin.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2utphjpnh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zawrfdyc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gntvxaby.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2awkwrqnn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oczxikwo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlorfhic.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfvkzzz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oojqlyey.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmlkjld.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwmzkek.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ecabcajd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmozvsnw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2izouznyf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yetzjpma.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoqagjp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yazybxnk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yblyhyih.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoccrsu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tzncejbs.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkgazei.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aaalasxt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwlzxgl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2awkdfolq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmignsz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfetuqq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvenrvt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zveamojv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvasgeus.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pvipgyia.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2akypmsjx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2blstykvu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlneiuri.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2udqfjmdv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qaddezuc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbievlgz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlemreij.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2losxpogp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnqyktk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hauztwix.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyibxnfl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dqypmcat.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2demnxluu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmaaqzi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgbgsws.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgcsisu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxecrgiy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2otelteej.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbxvvuv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xepfdoxx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyskbmkf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdumcex.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxxftdk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbdihli.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmwxuly.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgoaxjv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2efufyjnb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hsetxeze.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2krtzuebj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ozprclsg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rltobvnx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnvlmkh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2aziyddet.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fncakwny.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2stqkeaqw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2groxrnzq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ueojgzak.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pshucptb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mecihcmi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpzxhju.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tbypbrep.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsrksab.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmazefa.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2chxlvxwt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyexzzmo.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2macfnmbl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2knarpkft.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zexoqdcl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jywpslph.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zuguwivm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqwfpem.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xbozfyov.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brjzewug.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqgazcq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyorsmyb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlmbpxp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2emafshkr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyjdjnv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiayqlr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqdrmut.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fznjozxz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfqptzb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kooduqhg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfofxyv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfoaxwt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2guaibszc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2odgsraeh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhaemzk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtordyc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdhkjxf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzjnzxj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2inxfaiqy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2buzoormw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2raywkvwa.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yctniiiz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2slzdxqws.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jajjdvoe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbcqizw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jphtsbhb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdfeypx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvvgfyz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivscqdyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hprxchqg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2smwxucsa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rousfomw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gktlcuiv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2veaegpkx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hpquqodn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfgfjqp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bukxznia.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2npgdqknk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jslsdwzj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2utovcssm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrkkjrb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2luiamyvh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfpahcf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvnnvay.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgurhpr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfcqgsr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvlapmj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjctmmj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjcoroa.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2duksdhir.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2baricvqv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmocsng.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvyhfel.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeefhjcu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2naopjemz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzuylex.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmhlrdj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kectlseb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yomuhcgt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvjnasj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pjphpabz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2giihkams.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yylskdpq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwqxowi.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sodtqqgu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgufgdp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ismonehf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwfyddr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvmeqti.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iorthpvh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgvrfsk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpfygsp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmnxocs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlxozow.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvligfy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wemruktw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckunuzeb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoeurau.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhsaqqb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2akdhczon.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbcmmjn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkqkirv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzkdqen.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmswritp.html


<!-- 参考信息 -->