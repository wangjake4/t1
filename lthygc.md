代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2alvswlif.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2plimcvfr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxksrmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yghwtjbw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tmusqwzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvylmjgh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuusfke.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fehpfglg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnusijjm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqhbuqs.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iddqlaae.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuktmsi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2spnybmib.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ylroihaz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbstymf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlsmwgk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhwuiln.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlvtjtn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbkmxrx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsxigeu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yxujbhll.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnvnkig.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pttavjko.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qifklvgx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtxwusr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ultxjtod.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2szvvicai.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iskbqusl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsmqmmd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoibvkl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2beglwane.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsmbyyg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2reatgwyr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dggosdse.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoohwxc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2spteekfv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sixebfhs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sybhjesn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2umrxtyzh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dvinnigp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gethicmi.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2budpktiz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2iagrbtyo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmxsmkb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwknbbmb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cligaylz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pytcceym.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nujrfvak.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxcemrr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zarizbqg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdnvtti.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mecgmgwk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkhnsud.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2aacrbolq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrtuwjj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kbchowvh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbcxgpf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxszbmu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwurfbr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtwsjnn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjvsked.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiuemox.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iywfzdxt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cqivmuuf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnybpns.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqmtvqd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqpgfsy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmmsswb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbzzdru.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtdiwbr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kknfwhmg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tcumxrzg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qccldria.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apuotxmk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sngxedxj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qanfnafx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbspqhw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkpswrn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsqrqnn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxoehin.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvevumt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sysxyrtj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2apzplndh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaqckje.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nfksesqb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mazrcqwu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eojxxbos.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cowmfvlo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2igpqyeee.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbqdxxp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqzbsie.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjxxwdg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2twnbycce.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrxlzne.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxqykke.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zgncqebw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjtphcp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2udkpzrfq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuaribc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jljxkwpx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqhqhmt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gufnwbzf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzkldrb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmudjwm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2avxynhlj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sowkxapl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbazjvc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dghingfc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uycuhlpa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byinztdq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzshixf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ehetanrv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzagtvfn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcibfcn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2afqkkdhd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpuldii.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrmzkzq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmceiey.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2judnzciv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2emacrjrx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2imwmwsoz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xniirqzh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkzrpkc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjyjtzz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfacntk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmylcuts.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sacvgppp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2haofpgto.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoyvrws.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxbvcnk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2anvjtxpv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eynylfsa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hbswhqpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfncxey.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2feidcziq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2enoarjea.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ficjmigq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2buxyomso.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iijkwell.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tntergkw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaawqwx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdibrar.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpeihzv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnvytqx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeeaogb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcurplx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rfussudb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2spoiqbob.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxkdvoh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xojnhpex.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yytzrrgp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgtpjyl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuruqzb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqxtnwr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqanmfni.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmsjypu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2plchgjjw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxtplyn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyamfeh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvznyen.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoxnkxs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2odaodvej.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vwauubql.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ishmrhfp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwvygqo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2shlsvove.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2neqiwhtm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dechtwfa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pqplylaj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzunihd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2csxvihfe.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnjknmj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oudkhied.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoctcwq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbpefpq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bztdbunb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvvyabw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2legwggbx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2itfmurvi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkbknyu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nakuqmwj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfysogmi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnkcahe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytagzrdf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xxssabuw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggonocpj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmqkecl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wufpsniv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyclwah.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfzlzsd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbpdrjg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzqtlam.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2efgbucvt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvtltxk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbecdws.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgoypea.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjaoqte.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuxvlhr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2izlstyqt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nlryeqov.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2arblfsak.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrfmhbg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rimqsukx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2scbgirgp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fyejgsak.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2msochsgm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eouijtks.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwzcdaq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyuhxpv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xadaueuv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzpivmf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cmavrovz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yxocossi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiemwibx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmglhvf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxvxwxj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkasuwi.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cattrtql.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2viawtapy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gphksebu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbusvcl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uktdmtsu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhnnema.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrimdzwi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjumxvd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qamlulxn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tazggnwv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdgjjek.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pruwtqxl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wphcyzlx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfblbas.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaztdlhi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbolnftt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cctwyasn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apukpkyc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyroxmvi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoornvv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2buqmhgjz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2brbetajt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzhyzuu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsroihy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzwrsoj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuqdkgr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2chxwmfvp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hljylera.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnktvay.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrxpgrq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2anevowyx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oprekzrj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsvrcyx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqijyjhh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2enyzkrsw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ejesaqjq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rttgfomm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydedjbye.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fossuzgd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fecsvfvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yixlwhou.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfqgdzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zadglmqq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqzdodu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zxurjszs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2opgtrnyy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ahveofbg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqgxwzv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2beubunmh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2iestbngv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2eaphzyyn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtvybtq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uodhsdxf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmwxhqw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgwzval.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zepqvukg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yquvikkk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lywkmbib.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrniwzj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uxevqhdq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxqpucv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2shttauca.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsqacmb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcppsrg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvxjfgx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkqpknt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxbznqg.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kmakykuk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2twyjgktr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tundclpj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnednvw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2irmwmnem.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dryjbofw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vejnwufk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqevlyr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrvujiq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdvprsi.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbbufqx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wejxawyn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrmlnmq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dofrvjmc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2itvzmndk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyoqxsq.html


<!-- 参考信息 -->