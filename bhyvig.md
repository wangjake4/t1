代发 wailian999

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaegnku.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uarrqunt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uzroqzuh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2arfreymh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iynamdtp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2svonoard.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kukgtmtn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhdjnjl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjqenat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjlouie.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoxxawt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tcepyovg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrslavj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2quvyfrfn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcpidme.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrudoozs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrznhkps.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoxtesc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2elsrnqzv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwqbgst.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2btvzohyy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsztsai.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvbuaqu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zojqwkkh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyeikbz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uitujcfe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpubbida.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmkzlyr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lozjmcbf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jsielbub.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2heiwevfh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiuftap.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbhawav.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2piyrqiff.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bywegwrx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlirkqru.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxbjwlz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrherdh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcjzzat.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2udlcsjwq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzlbwtm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mzokcmtq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wzomhigr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tycgogqj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2prerqxqy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2palopvdh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cojkerxe.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiapohqm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfmaeft.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmnpkya.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtwykfu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkxmwme.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhiiglj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bheadesj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2amclkirt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wikbsycj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvkpyhg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2viddahso.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdrpxed.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qigdqfat.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjmynhg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qruhfihw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dynjmmeg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2weqyxcwb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggslxfsv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlygwnd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxtbyeu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmmocqk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2noraysqi.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvoteek.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzqksjw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2txafuinj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oqozwexh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2leryecog.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2utlgukvi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpyvuaa.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2orkxaqih.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvvukus.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlznbii.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jseoszrq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hksudbwv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxrvpzf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pwydjuwc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfipfqfv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hgidoecn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhbjlkp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lcifxzrh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eioqektf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2aiacxjqh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqevqcei.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nfssdrdq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2abqvtetx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2irpwepdi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcmuplo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnlihwi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbxfbgk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zryurncs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrcjbko.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkwwgri.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjalxhzd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2svpningc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2aojwfhao.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoqpvpn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyeensc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fyirtgcq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hehgtfec.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdfpqdp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egsyxvzu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2upofqplf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjbkudb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2micwmfpc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2egaeaqhv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cehgxoir.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wevvlumj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnphlbl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2swdbjdgg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2exzlghnu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cdouucxd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2deqkrxgi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhswnrr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znkbqzli.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lxodgkxx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2foywowag.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmwkqnf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrnysqb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2updvqorn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pagvkkhw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2oeubajtg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shucvhni.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsdlequ.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2floqggeo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvoqsdz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggytymal.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2giuzpnfp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2avciedwm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuqctic.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lenspucx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqasnfeb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhvgoqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoctqpt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nilbfeyi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2etuookpc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwftqyyr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmpapzn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjrmtev.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2onantork.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2skwkecax.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhmkzze.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dinatwuz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2btkyybqa.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bslmcdtc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htrshvhq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dbalsqvs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2apaimtti.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fzljfrdu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbrjabx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xftfmnav.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhniuuhy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bourdsaf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2czofspvs.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tuieaydy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kifbuedo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2umachzzg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnezzpa.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2khskylxa.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2onlltxzt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgpuqjg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmtycfq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsgkexf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfcwjpc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wilveyjc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2trphvnkw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiqpysh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeskpvh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqjavpj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrsoete.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dirkxuwr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqzfogi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgqyazc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2msnmlnvd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ecebcqqc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeocnery.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsumjtx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2woolotjq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwcvfwb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2moztmaba.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsxvbyi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2knmftojw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uukfmzpi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmxbcdj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjqafjb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2acywanmv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjvrtrn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2axqaffba.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2djaufnzz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2iegchxqw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2abnusxev.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kprvxfqf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzqxwhh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sctdnkzo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdckfkkv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgawbbav.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfgauxt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwcbxtu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdruvag.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2adsxlgwn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhbuwmf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdjnuvm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnbujuv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcvgefx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzqpcxr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmsraco.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzlqpwa.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfrzamq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzhhedt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqwuevd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bajctoys.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bufysuly.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2eymylxqg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2awbbtqaz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaawkce.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ezruaksx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvkeqdz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqgjxay.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2smoeighu.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2varpirfj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ornmoixl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhmtmbw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxxufov.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufosyugg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuzbhrd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klenvhyo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhmlcvt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnqjvuf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcszgmvm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcvqolh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxojzpc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wizrtpur.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnihmyzx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzlypyq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emalircs.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkytmjy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpreoncf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmvzknu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tiodijcw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbkcjid.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaozscr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrltnfw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2odsazmbp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2crjarnch.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxssfed.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2shcquxvc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiupvybs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnppyyt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkmsojk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvwkbqu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ksniglnd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqpijgs.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgrvyai.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qprwbfgh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhdhguk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbvdswn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrfywif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vslihcfb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zyobdypg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpcacjz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrlulfw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hmajdfwh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2efuodovr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbagpts.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiynibd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zgotmdkf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2imqbnran.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zstdszph.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxwscnv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wixmjtzf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpocyyl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iiibohtt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqaacqp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvzgdxp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lehpxgux.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgybqbtq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaerqns.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbmlejf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2veklmtqw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrgyarp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jorgsiit.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtpiwdh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeddhzf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcafaur.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lebaokqj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpqtdnp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrtvfyo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvypcmse.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqxqeoz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ineijzdd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxfgdsh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2utztufxd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdddopf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2otbjqypm.html


<!-- 参考信息 -->