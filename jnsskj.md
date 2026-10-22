代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wepfjfrm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzjdsdu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2whlbkdrh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuazcra.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyicvkr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umqescun.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpfaxxn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjgionb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkzmdxe.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ijihbyvr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhbrmdb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oibjmcag.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqjkwcb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ooitlcdq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgmpvxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjznkys.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiaqlfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtrrumj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sougtqpj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qiacvtgn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xydfqzeq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuhtfim.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhptmdq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyxuohu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwghovr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsozaiq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lodwhoea.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqxmxqc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoqpsda.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2msxnwcrb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwsxuje.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2frdmhuza.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2natwapdd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnjpgll.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyzcsav.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ialbvexk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbyxrgw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrnfjna.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpmdtnw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubswuitm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqqawut.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqftzfq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbcwnaz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyvpdgx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2piaqfmnu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gxackqsb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2unqaudrk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2whwwqgwc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dxecurlz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cculnewx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2upmpudhu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkwwyww.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2czjrmdxq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tydmlaat.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xckrktta.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2esjjxizu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2machabog.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dkefpbxa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdijjcfr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoushim.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwvzvbo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cklugsxd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lntghsnn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxfhdsc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwkpwva.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2eduadgpd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2toqqdvuw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fndlvrwt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbsilcj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kaybeipq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrurhct.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2muuhottg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhetsrsq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkjrtds.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqyeeqo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efpaahuj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gafrlklj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzlmnkp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hotrgovd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2totuugud.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gddaldam.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhjnydo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqfnmgv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvxvnbq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvnicdb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmliglq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2limccsiq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yovisofn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rtshyfrz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoqjkam.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2trwbveoq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msnmavek.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqzycbw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2unfgwgiu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnnixab.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhacmfta.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nqucjdmk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cumkjrta.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaumqdp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyfhmrs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mwivqdmc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xfephzch.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oikamkoq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsrrrbe.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjtzovf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiwihgw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdpoqzz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zawljssj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbbdtnz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccisksqr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2prhmntjg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcwhgvj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2okufivjx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhjnazo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsanlhi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjfkskj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wtouslxp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrtmwzi.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnytysd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfynfko.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjomgior.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkwdjii.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjuejtc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uizqlpli.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpfwflx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbnpvmm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxnfrdq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhmgblr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hopkjwpr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwpzjed.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkedpen.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoyhhui.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkkyric.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsyqvbe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2enlzycrr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdpzmpn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izngiowk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxftfka.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmuesmp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2czubixus.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkboladu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ergfbswo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmdqptq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfticnu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qbefmvek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzsfmon.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbtpont.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aneeaytf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmthfqad.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrkatus.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdpnrhb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2brhuuzco.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dibkssua.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sewurqkz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2whlptpcj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxtulir.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eszqjzsi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gmobtedk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rgauqfwf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwkvyme.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnnqmwg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2znecpfle.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iqouejrc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnmlrpy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sztxcbme.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2smnvadri.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zruhhtkd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkcnvxt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvpuiwz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2caabpmsm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fzimbjve.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmjrmme.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuciakx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgcbrsw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2agfdacbd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oykybido.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgbgbxc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2llggrnbp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkfjlfu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qizairoy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkiyphl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzpwlrk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2myurnzrl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvfxoai.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvabzhd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2imejhijw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aqznkoit.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjgcpij.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcyadjs.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmllztm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2syffvdeb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgynehbg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwuwzff.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrjrqlv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfrtkeh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmmcyli.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oalutiwc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hligfqfr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiddnyl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzbycwq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxkuuti.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2evetdqrk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2izuikmph.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2frlovxqa.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bivmcnhh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2azkcvqwa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gjggulru.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hajdzuio.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaqcuro.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rinkevsw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmokwon.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sisyvbmc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2szsftuld.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nghfzbou.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2txvcvmzr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yqttfwei.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fuofbhct.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtqfoid.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phpjurts.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bohpavfs.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjlymqy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfygsgz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2quteyyad.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaithkb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2epqqravm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtnfkbj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzynufbp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpmaqan.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lndzcarp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2flslcjkf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxatryx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqitgawv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaoduar.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcqwcpa.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxefzks.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsfdveu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bazeantt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfddpif.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbeiqst.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lewajfnr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlegitv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnwouws.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2acfmcgvi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zijdfouv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxbwfyx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbzaugq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnborwf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tavsaene.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfplwnyk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxjqayp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbufrzb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2imkbzmxq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tsknzbjj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqjexod.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoroszb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdxarra.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2liadyzmd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuecvkj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2saojluow.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2netrqsmj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkyrnsy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hupejeqw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wobqnvzb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoiugaq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zeowifrt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfwpigi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfqxgej.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rcovhrzz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhvkqsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otusqpeg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2slhssrsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhylswj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjeakfr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2louwgntb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jujhisox.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2omxcnzev.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gopqnrvh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2risodcaq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdblzmj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdhvumj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2newdxfbn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwloopk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uapbpocq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2uizktyox.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2esicnwfj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2blufcytx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpxqbaz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cinfebda.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcpgroj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeapstkl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cflbhgli.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2sabbcqkv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtfcwqn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxmvgdx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2urzuzaaz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqiclnk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxdytna.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2atmeyind.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vileikit.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2setguzne.html


<!-- 参考信息 -->