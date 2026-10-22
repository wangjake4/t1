代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vugpkbcl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2popbyooy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2crznkykz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2anmxhuny.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcrsczl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmslyku.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2plyzzigg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2treuzfky.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyqdgej.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2khdwujos.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmjyykz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfeftgg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqwgchz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xbklszaa.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hnngypov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onmtozgy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hynndcly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgsnvxy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bsftpnqx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2adieowjd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjfgxhw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2liilazed.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnjmuew.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvlhxyf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwqylib.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwmhcnu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoeebqn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sirgwdoc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiqbjzo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rtubssgm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaeeray.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yftyrfze.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2irdpwygb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nosrnyqc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxulmsos.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvwstuu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2oeteihag.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uunzsyti.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcankxyk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vynnxqlo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxxfvcg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzmwpcx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfjuwuk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdgdxxq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrebvyim.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvtrzvr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoxnvet.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlsbofi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyywzka.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzhnnoq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cwygsdak.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2sltmftyi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fycmdecs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ksisdsjz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdkszjg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsleyen.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyymcimn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcdzdpf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxejueu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iuluywgp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2atpoyrvj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfebiid.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tryvhqop.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bttihlsz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xutqavmv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfoshpt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2antucovq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jlclutdt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qctscaxr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2innvvffe.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofosbwbu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2allcruqo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsadppu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdxqhrm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2osjsipvd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ubduppoy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpmlrsf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngotkfnh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cftlepih.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsavwyn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlovscv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rzleejqo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oaublduf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ptslfsik.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2habcbelq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guwshxdi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2saewnbul.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ariekaof.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyoidmi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkptzdvd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lbesvooh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnrynvz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vxashsjz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwaxyzf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jokccdim.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdkbacs.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2deoeotbe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpwbuhd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qwptmgzs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgwzkym.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cgelfubj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjedppb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2axrmxxhl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmrefub.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiglydc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgadbrrv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfikicd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbdvwwo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fccydcam.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyhuzgn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qaopkpcv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsxshxk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2onmeunos.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2spyxmsck.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fffaylli.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nioitjzy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zshiohfo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjlflyx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdokkms.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzregkjw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uetylohu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgsfjyc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbjdyxg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqcynfv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pibtmgpe.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqndshd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cekstrgn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ifztjwuc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfttznt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kojmggtl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pchhfkgp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrcrlsv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gejmupmk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2liohvcso.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2klgrrvzo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtoiyfz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxtxhue.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkouvdd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjegiek.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zpesonbs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oslkcfiz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2khcpvetq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeqpyju.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bfehawil.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrdcuyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phtkzxdh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxzcyjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smsrlbja.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qaerfjiz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvglrkzm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oibapynf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2prfsjppf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xebepsai.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdwzssb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqyoijr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mahqcldx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gzemjutn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrjnglp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qypuenxv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjtipbe.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2crpbjuea.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrkwqnk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pclieywz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyytpolf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uiojeeja.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kilxoflx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2inxdjbih.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsqjfjm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzhwbmq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdjrovb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyprjcd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbmxoav.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxcyzrv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2takprwvv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwttbzy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzkeshc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzkhkvm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eorzlftf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxavkwc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqljmio.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2atopsufo.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcqitua.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcaoyri.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tngcnhze.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2utiyfnih.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaeueet.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2utytwnpv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eptqaumr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hoporlib.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvgpqmf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xykkgrwx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkfpfir.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fygkevwl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2izhaxxdw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qffaaeuk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wirmvpga.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqwuoxm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxuwtsg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbwvnwv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhsnsrp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcutprv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuktlgq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qjercjpq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtmokcl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxiixmo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2beiuuznp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqbtbtv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkunpxv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kjywwjar.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyatbnso.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2djvedapf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dixxogml.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2llujefrr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfrirbh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkkkbdg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lafvupel.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2aojyvhjg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lyejnmxf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmmcena.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgvmmje.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiajgii.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyqawse.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqroldbz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zuctommb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfzeocg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2adqdzwyj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jimrxlga.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2odaauaid.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qxondvup.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zonoicis.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qjymtkiu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeqexsl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdugwuq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvcguna.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqpvuci.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jebzzkoc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxwjyob.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfqncii.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2akgbojkt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abatzjbe.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfeskvb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuulpvcp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmamfyq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwwktej.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwiquls.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkiurie.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqecyvwj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpeqtmz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuuowgx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2inxyvhsp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zozcevqf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwblhhqr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xidycxci.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsbfthj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gztfidrg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdczmcr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsafpfmy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kagkbqeg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqyuohz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkbykie.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hicfuoop.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxulddq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yigjuieq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqmjuwt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wspdjqqq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2euzojiwo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybahriet.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2psghfzjc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2duoivxas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2larupcrv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yljrcuxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odqzioif.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yudebruc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2eupsulec.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eoszxrtz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cntsogvn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bioqmiqj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxkonxp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2iozinmaj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2igvayxtu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiahaij.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjkuxjw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcifkfq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlxbfol.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2czctqweh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2msdtjufp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyvrjbn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ygouivsb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2otjabgyz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlctvbr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tryipuqy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2sghaivsk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xachdbze.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdwyjof.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kuapouqn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfcyiju.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uixrfsmi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nofzzeay.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbokpmo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fovkcpxd.html


<!-- 参考信息 -->