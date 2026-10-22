代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2heqomwve.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeyoebm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dfppsfbk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdhitgy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xpobfqna.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2adfiymxu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rckvmdcq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2sowhhcgl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvhysby.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2oxivdwsf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ivylhjqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osazkrno.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwkttho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iumbtjvf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwkxxdw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxytpxv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeaecqj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqkqlmd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwommvp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxznilki.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiugyuop.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxfobqw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbxtgsy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tivmwdyv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzdcdxv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cngjovij.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rogzietd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyiuxdj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcocwmm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlvqwqv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzwpxpq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjxoqrs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaaxeyo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xxftunia.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmsjbxc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2coyssyzg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2illypszm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2drpkwium.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwsyabu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2favubmmd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpleifct.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeqynhy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjmenpz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tckalwyu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2eeznayml.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yknbheqr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zontjgdv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hotslnco.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsqyaoe.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mcapbeng.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aivojitp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dssbusft.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngksixip.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2etrifwrr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2afiimtjl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbkeksj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcwzskh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuxznem.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdyigqq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sixuuxbr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uigiffqt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kthzztyk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqxhhmy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wvutumqi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2idwmdxbf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hfikdjzw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrrgkvm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fixifqtb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2grkxkvvp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2szjidzab.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2urjcewcx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfkmvpp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbcvits.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoywkbl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnofaxt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gewkxfui.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2alicqboc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtgbidk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2waucaani.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2waxmrjfk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlwzkbn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcmrrih.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2azkrzucv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kbszqwlo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpckprs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2muvznili.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyyzwvw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbjuzgm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdzoyhd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcooxnme.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2unyzbhvh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcuansl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ospjbcgx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rizsfsdn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2chudcbfl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuxqxfk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpsqtzv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvjffvw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzutqcx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yibrzhax.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlekpno.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2smvigcdi.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqyxzdv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kcocqqfu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbznvdt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jljzkdze.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qarfvfbk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbihlch.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qksehxom.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmdrhxv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxrsneu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccudyqqa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qyouvkou.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcjncov.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2soliixdn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kteiwsex.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sinqvodp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wesmngmy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkamivz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cputrzqt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2skkdcdmn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvjharu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgrxxkd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2stxwhcbt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exorgyik.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkvyyrl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fczfaibw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrtbpoc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkwxpst.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2clhzsnuj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2legmcovh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2igjujpmy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wypkupfa.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yxodvmuu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdwnbpb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqkpeto.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2diieubqo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2anpnpbtb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxehbusw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vjawfgac.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ithpreib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrnlfvj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2trrankpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjluzev.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yzehbgtf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlztifff.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfwlywf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkbunzd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpfjkpo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxhgayk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2peuunnkr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqkzosy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2munevowf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjmozht.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpvjmuu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxohtgip.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnvmipg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtvwnic.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aypgeyny.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcsaljc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aeevuscj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgurccj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hawwkapk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdvuwiq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcjcnjh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppttdcva.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2efeegoxr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qropwbnr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jloxeims.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcllnwu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhkbguk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iieqojcy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mzihgeqc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2piuclomc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etdymyls.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjosiaci.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2anbrmuli.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2imyccxvy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhbrrjd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2azdypqgj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vvucftrz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqkwaif.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeqxrrw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoqicwx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2urlsvjww.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbffeeeu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiqrigt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zymlnkzg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cowzusjs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hulnaigl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzlkmzi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvfuurn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kizlymfl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnixnfhu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmtnijd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjbinrw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2erlewebv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcfzkvo.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jvojdwyj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwrsfcz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2elmlcfob.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrszqym.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpnwgbc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2muhuucqs.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfheoea.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnropfi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajocfqob.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2clznilmg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxclhdf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkhppim.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2amoczyeb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2asgbtczd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqgqhyd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2veuoxrks.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzaotjr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cylmgomc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2affpipes.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnqtblp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtldhsw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtokdgw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsaluye.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsakwqlz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vugbyunc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dassabxy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzwpwhm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnpjwkf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2afsqgtxh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbxtwgg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxqzddm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2offgxvhs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2huvhihep.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atuwsotb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yudyatem.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyjskdh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zumjszgc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lccfkbmh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcrtmnm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxfazbp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2icgooyol.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2orbnskmi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnqphbf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrcgbod.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyopnhf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpcdfmn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnrnxvl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vxigtaaa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2otvinuuh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyocdvb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwwjnop.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkgzwpr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxogxouj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bjirjlpk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbloqvk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpboktt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2deinykvc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxzswzj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfgnamj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqaanqa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oikkjzmf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zppzpkin.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgshkgs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2likmlxtn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcxxghc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzlnopy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wavkuysk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeaivel.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ektedojy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcyolnj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnlahze.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzeeqhg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvteiku.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpiwepp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pnskxhrz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mphevymv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdopgup.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ljimrrdc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcqjkly.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwahuvh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cjizrzui.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmengmbr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvmfixn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsfligx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlikdeg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vrljpvet.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnpixkb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpwyqrx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xybauzhu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2aplhpetb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmoarjx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgzbbcw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhivfub.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwzgtef.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2skrjxmtd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjoimnf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qsccpbvl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eieaahrm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbzpljg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukndavjm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vazzudri.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yppvdzhq.html


<!-- 参考信息 -->