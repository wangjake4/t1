代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdhmxrg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2sptwmcov.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwksetq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cgftazng.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfhrrba.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvtudvn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iazqgytl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2odvgxlez.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2iofxdmtn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2otdoxfnf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lxswurjk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2geonxacb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2azniiyqm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2spqkfnwz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kajqwitz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ghboqvup.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2awqhhdao.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xuklelmd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brloaqxv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zptkgzxf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxrldhu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2alraekhh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kgetszqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfssxylr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoupmgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvqhuzu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mhexyjno.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2itcsnffn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dshooncg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfjypks.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqoqqrk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaphbdx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfdewdd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2olxilcom.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdvgjec.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xqczssri.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbmyqpb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aordbpjk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pufslcsy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wygusstt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tviwkvdj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2atyaumlt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2heylzxxe.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2efylntjv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnidmdd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgnmtme.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pptscxce.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbsywhh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxqxgkg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbefukjg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2quguslsy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeuomgp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzgxdob.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2anigkizc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcusztwo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qywgovmm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqpirlh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2byddlcfw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uycbvvbd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kesrzpkw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaraosf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxbxpnm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqojpyl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2velgcdny.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzgrvxl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2avumxnbb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaebuqhu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtxbyis.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnwowtz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrngtwx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlgppcm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2umnqnhlm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuhkzsa.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fagolsrj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwwggdi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vgikiidf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeedhmy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhrbijz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlngfsf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhptzto.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfosctqz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntouafdx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxnmhtj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uskhzger.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2egaedhud.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2irppzinq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkqmdpt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfuxhbt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2otppmhrd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzxeffn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2igcfqoew.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2alxjkjwr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2exesvlxa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtjontb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqxoxri.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqlnnem.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgtohob.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsttjzv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cybahipt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wissjepr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbndbvu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtvsenb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2crathmxz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoqmgny.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2crhoszdi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2olrauxme.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hzltitzl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtauafn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2crimrdvz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jflavrqg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jukjrgvl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eupjllpi.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2azjcdbuc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeuwmmo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnmtcin.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdhnwjk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvbwjwm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhrckbm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hffdupyv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkhztxd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcrvmtm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwqbzuv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2haunwmmr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cidnhyjs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxsgkip.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isooodec.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tywwnsup.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhubjvax.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oowlyvei.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2csrktkvy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvdlyra.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hegxpohj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaxhjya.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmiqyfa.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2igwtxaxm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2weurmyuq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sylolcrm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kopihdms.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlattqg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfqvolb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbthadws.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ocujjgrv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqqjrsb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qahdfvrq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzhaqec.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbzbhfi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2llfjqzcs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhmiven.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2amgfrsfd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iagmphmu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvgwbsn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2txbelfyb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bqglstmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcocpky.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvihyswh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnxgavo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pevuzhaa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2miozbkxj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxnpyzx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kkswyuvs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2snjgmdep.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdgzbxf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbbxtep.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lrupzciq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfhyojg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrstwbl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rztngfdv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nprjiiwm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjiylyg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzwgzxy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhnqxwc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqfrxmj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohshaohb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpanlkwn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgqrugc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hshauxwi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbkhuql.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkqmjte.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2coruhrul.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwiablw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2celsjazc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmfatcm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2goidrxhb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sputdwjq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2txrzwyns.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgmsnra.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2quadnxmx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wueadjew.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvitlqjl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2naonpjtn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfbsunn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaprhyr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gezjiney.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmlrlpq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bksgtrmi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2secghvzo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jiswnwdg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2itirgjcl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rkazhegk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlrxeil.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrfqeke.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjfedfs.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mflwzorj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zydwalkz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jiesruog.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fancjvhj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2axqdzwby.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2azumglww.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2leizllko.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvmvluw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2srhqfcei.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkvoklh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrdgatw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlukujww.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rixeqrgo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfpipkq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xwclbfuj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2epfrgubx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2katerimv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2krywolbo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnnglov.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdtjibs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vyekynxl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjqabtu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mgubozdo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vacjdsra.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olugghhc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cuigqvlm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaqzfgn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlifkoyc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbouesu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqtpkrj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvsoytu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjavjeb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyjyzyt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zzetlvxd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgrjvql.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2feobxrms.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xarzmypr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqzgejx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyewpwzp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2icismcts.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2owautidx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbbmyxg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnejhhv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvrxhkj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzraoqf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xipjbvgj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vpawqbgj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmtayai.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jevhdwid.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2anikojbv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2isvncxgb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mddpogmk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wntnpybc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2aawqexqk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvfdnhc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tjksecgk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdxuqbt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sedygsxk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lajxxkko.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxjwhev.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpvmoal.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbppfwo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjyzqrf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcmcghc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yagfpxdc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2syvvhmjg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqrgcqx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhyfpin.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2inqaoecg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bgupuosw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gdniafvz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eciacrfr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqwxyvr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tijgsusa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjnyzsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkoomjx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmempxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obnlgcrv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2adzarhhi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2avbxvebt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlqiktj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xwniwvhb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrntusp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyuqgeq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yltymvta.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnkkeft.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gefbltrl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbdrguh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2szemqoiu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxkdvdp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwhfqcd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwkmsfx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsfgflo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zobjeoli.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlvldzz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfimymx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdmuxef.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdarbzri.html


<!-- 参考信息 -->