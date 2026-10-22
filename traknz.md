代发 wailian999

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2eekxivzc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tirazlrv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsbybdj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yeybjcbp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhupuxc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gspqcykm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kieddmrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fydffsea.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqbrawn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdusmcrw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2quubcbfn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdbxcif.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpstqwnc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bfftanjd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfsiofw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2begzmorc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgoganm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2miqqmxqj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxxurih.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iczpxmcy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2okwhvjom.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwxxsws.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmzndkv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmbcmha.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2btitqxre.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pfefkmkl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvascrjr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tkspvyhz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pruwzdey.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mboyjmij.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxeocvh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uuslwdor.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvzdyqe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqekarxp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2buyrqenf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2felpfyhw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2maaulguq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxzlcpv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2obnjamkk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfxturs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qlktucka.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2esaljbll.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjtkwfc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vctacciq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2njixxfjt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgkefgd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rejpzdnz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2myrwrsqy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2iufvkptm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmwlefq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2omyolulg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqdesdg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiavwhg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtwngxg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmtwakk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qvslykke.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhpozmz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2leqhcdbc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtorjsx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lrektuky.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tupfncfp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dodqhmgg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tccarmns.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfuezuw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpirpexq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkfatex.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuvjyon.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2twrynfqz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kumlrtlz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mghuefdt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbztnrft.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlxbjdj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcvfudk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2teauhbdr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcuorjy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhgbbkt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqxyfit.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgptsgt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2feuactjw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oabhrhio.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hjocodgk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uefookok.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxmyrdu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qknkvcem.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pneonjek.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2swnpojow.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nllgdtud.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfepyio.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2okjbvmbx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxldpjkg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuvnqfd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2efitcszp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pegtrqfy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mwznwfgj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2syidzntp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dshcbwef.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2twjwcpgx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpydbgs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2diykdfsd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2psnrqetw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxdsoqk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuazyrv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnsyncz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwutalah.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2esojxdfg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yixcqwkn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxbautl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtcaskw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kdozdqrg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdugjymw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2woyhkbwv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sunipbip.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yemmymcf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgesjvi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ofewmwdp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jqufrmvs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiugyjg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lyddkozm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2osdnlspj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2upgxybfb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpnxqvu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgplitx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyfuzit.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bhskgwez.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sccrtbww.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpjminx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgofwlis.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuwaquk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbbprsa.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuizimh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jffpoein.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaknpwa.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvjrxqu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhjjbcq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbsjkup.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzebxsf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdnleif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fiozglbp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvehcecy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbtfllx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2obquofsz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkanrgrn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gplzpirg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tchgjnll.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkbzxns.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ishoxeof.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqjqwcx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfyeigz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2figutimh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqmxwzr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cycckxiy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiukawpe.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wrykydpe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlztxkt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtgsppd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzttazop.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbowsto.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqwrngl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2whtdgjza.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltncbuky.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsqjwzw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajztdbme.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjmhjdu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuvfuua.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2finfsoyo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtaonzc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rowjezqn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxauyaj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ausfnnqn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2efnfupzm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ecezvkvm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaswmsp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2scyyywse.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bpixxrea.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ljplldjq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwcdhrx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiiddxt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zebmwhyl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgybtfq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2frnfjrvc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmpjicb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtxqusn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpzsbog.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2anvkbwoq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2acdurmys.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2awipmmha.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqqasie.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jexmszgs.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zctjxohw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbdpxfn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiomhlu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvoznwd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pamrymms.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpvkwmf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhtlnbg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsjnxcn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmcjpwl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjucgbpo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfnifhe.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogykvyte.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnlxpse.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dweppgyl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzmcizt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyldqxh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fukilrrl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiuqxjg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsqsnhq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfgwyry.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnbznxh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djvlujqs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dspnjvxq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkmqtny.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2keccbhyl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmogrgo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhcizov.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mlswgwgn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhxftio.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoezgqz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kxltqjqy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvjvalv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yalmpnix.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2afosxmzz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ssufvztu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpywwfry.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eibkkhcw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfjbmhj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2edziopxi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxduqvoo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2seppkzxz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtjyjbu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zghidshx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odxhjnee.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnekxaf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsthmul.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aldbtvlb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzwyqfz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrljlhtg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyyggcg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmpuwnk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqklcxmo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pridseif.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbncfdp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2deebyoug.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrnildp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mortzpan.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmmxcqs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mldnayei.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsaiozc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2szskjqbx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aomglahh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqqioph.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkydqtg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaethbd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwnjhsk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2amgxqkat.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yncgpsij.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkyczwo.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cilahomu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kndqigmw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyxglzv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceamzfrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uobkqhfo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2glhnkxsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhtazwi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhcmmcr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbdekxv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jtobhgct.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqnkcke.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yibqvlqx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdkhtpc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yznefrhe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2soeoazyb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkgurcw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzfcbls.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpokcfb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwqbsfx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2totzzxvb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2axhtxyuk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwnbccf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yihqcjjy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2miooofvi.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhgwekt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcbwdox.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaivnrm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnafjkt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jekeonar.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fykffhdj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffehqvrb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jewgrswz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaidmawv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xundnmxe.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsgslwx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2axecmeio.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwypzwrz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gbysdpkr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2iemsvqxv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnbohtl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtksvexw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcvuntn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlelgzx.html


<!-- 参考信息 -->