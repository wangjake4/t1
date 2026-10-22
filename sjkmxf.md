代发 wailian999

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtsaawx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sitqeafo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hheycakm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjiyree.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvgnnqn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qwypysoy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoblrfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnzyfos.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2czlnycrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tonlyemf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qroiqmix.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrmkylc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqocdac.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iynwomsw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzokgknr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2shanhkcf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2avvfdbzf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2chtenjkm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2drfnqsma.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmnesqs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2shobyifg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbovkoh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2htfvmiuf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbsgfvd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2cfihsrzm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhoofvr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpuofnu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtwoqkq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfmwlkz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nokoqkix.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxmifle.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkihswt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqfqrkq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmsbpzl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnafaxaf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rszrmklo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfhpctp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lwygostv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmdemha.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aasgqgiv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qiepqoca.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkpdiel.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qftdrzxv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2doqkscgd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2btifiimz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2djmhmojr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2byjkwyru.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqygxemk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuumzuqi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2urnezbfr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdwsiun.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgpozeu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rphxthzs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2onfsdyhr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvqzizo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzcotgz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vprdyble.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbujfutl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwedpte.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aylwlefy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2aepaokia.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqfhevg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmxgsxj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfskxob.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeglexb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2apdninfn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2icwmrnku.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmfweat.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2utohtgbv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrubhxtc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnarmmrj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xymwgeui.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqzvjpn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkqejkm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mirdgrgc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpgkxkx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pwivaowi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwhwsjz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhnkakb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2egowkkxc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxzadhm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2trfhwdec.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2geyzsysd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdntbku.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bjalhtfc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlumzzej.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2glnxenwc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiixiigb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2humkjelq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpctcke.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fjztmwjh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wisgvxwz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2twwpeczp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgiotzc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqfzgww.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsuckmn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qywwotbo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uooukxdj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cophcrkw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vralzahb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmldiei.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbcsfrv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbhmiqn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puoxutgk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pyezwzmw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ylheedih.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ehevnhqj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfozhzfb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwhimwy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coqbxzvd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xijpnhlt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2klfompbl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2upkiqbit.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqpeehi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xucjcboo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtwupww.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbzzqum.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vojlfddh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rkedgqkr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpcpmsl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpccsusj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdurozt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2haafsaah.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2adnqlacd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqllvnoc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uplgoddr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tunjeujo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcotjis.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxraumm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgaaskx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pklupfyb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuztzph.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pziyarrl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnxsodb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlxmykf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwguyez.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrqamwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsneebs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pntbhizu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcqfknf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lobxlvlg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2knurollj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpykmjs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ftndccgj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kaogdkdv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2offbmlxp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qitcnuqt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gquupqjp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkshcnd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xizsnoet.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kogucadb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2otkysnwj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rprptetb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzapxlbn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nptisyky.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwlnpma.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2muzzefhy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeibzzq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrwkyjt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvntjvlw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ssptlmym.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnoduyt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzpxcke.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2drwcoulx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fitrhvqk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqcadkr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqfyqdg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvprbjel.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cputmbsf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuogvrft.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zokcrcbm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzfppxh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tawlpkla.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvnahsc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwtkppl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjatblmq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfqxxqk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyevymai.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2znslxdjy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbyvzrh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oklpbfcn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vehpgqqk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnkigad.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sagjmshp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcamxzha.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvesohhs.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnmixbv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2beoglgmt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkdmajc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqerwynm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2axrmrjcj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cihpiclu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtdqpkn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqqfgaq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dqffbrmv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2prpnicdb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qddjzfmh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zipovmaw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtqhber.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoydyko.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2damuwkrw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmahgnli.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2enctsxyk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiptdji.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdtrrob.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnawvdf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kadgwnnp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2idbcrptu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2yewrmulg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkpnbrm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhupgghq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdprrhw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iswvsvjh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeuylse.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkagtjyw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zgayehnn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2isahnphd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqitpbye.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mbodlckn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xwklwdmj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fszoebut.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sgohsdld.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjifvis.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyesxmr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tissoyju.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaiurld.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qfovodrz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nboaitsg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ahineppy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oklsfoca.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjqtzuc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuiqzil.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvdgbcq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skhbbmie.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsygbsq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqokelkj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuhajmj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsllonk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtmtjfs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgexerif.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzwwfmo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmemtvo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzxoixw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2whpzbddf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2twbtwmge.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnusyhf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xyydrwyc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzgnysu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qquvipxf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qktbucdl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmerdygp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kegnlipe.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2enkvwqcb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2duhdxyjb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhmsuif.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2maarpric.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uridledr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wecfxtkj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdosuvx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qlajfuul.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2stjdqxuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsgztzt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hehglygu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzuxbrj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dvruowoa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2edpvdbke.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xljjgyso.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tayitjge.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gojjtdii.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2orzybgcd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pepbthbc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuwwzvf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoqidvg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2igoopxtt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpmqnpx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzhjksv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfopmnhz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmweryab.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjcharn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qkizwrff.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bmafwwuo.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwjaggw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vnolzwxa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiqsphl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgbjkfx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfevbje.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gapcbwll.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2psglnmvq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnitkkq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gewfbmqt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqwurde.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2chbpykrv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zonlmesr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjqtpmf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2snbpvvgw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxduymst.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iylcvezi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtjuigw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvajzih.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lagutfpk.html


<!-- 参考信息 -->