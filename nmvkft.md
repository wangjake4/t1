代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uapfdbsr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2chnhvujy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxwxmsm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oloysqis.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcoagiw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlvgsfq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxnnfkd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjklgdy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2crzwhtpe.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iywafbae.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2emqqenxs.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2khbyugql.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2oigoxgwv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcwypes.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dhysnkkc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bdurvrls.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwghdjb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbbslvj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvbtyvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyreonm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcgfoyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egwyvkrg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kenomyrt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ljthyvkt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbkjwrj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmnumyo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mygqhixc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnfvzdp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzksvrtx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kvziindg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsgcrga.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sqytbwkk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyerzut.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gwktpndv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oahhxcby.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjjaisu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwcnjib.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2momyvtkp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiradal.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ulalvofc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyowabg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwrexnu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsaobjz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxlcsiu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dekpxlym.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aavleslk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvxiknx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npuwaiwh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2crtltxlh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnlmyxu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkgpceo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsqcqmk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmlxpoo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvnrqao.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlbxikj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rcubpqri.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpidkuge.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxnngaw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbycmlum.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxebpjm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2icwlfdpz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gkomdslg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuldypt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lteojmzn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2shrbwkcx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vewynnrx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2njviykff.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2phoxuwze.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzfykvg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaqguyf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggffbiui.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsjgksl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeaeifq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vjntjetd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlithodk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvnpugn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrqxnmo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kylvrcmx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyndigu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2idnrxtxt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyltfqa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kakwemfi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fksowacd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcolojy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrftwvc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2svjmtela.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnedjam.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ivallpvj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tcswlxcc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqafesvh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpufsih.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2btfumlji.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2apskhsdu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaelibpn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwqngxh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqqjtfm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gylmorep.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqtabnz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2oxikkdij.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwvawes.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnvxxft.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpjtazk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aiszcfqp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpuuujd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhakzkh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2izdrzvgr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oljiiext.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxplxap.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thuuyuua.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgyqldn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufssjkqf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxsysjb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvmducs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2aluoiraj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkkavqx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jabjqgik.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ckukizye.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2motdrweq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yggwckjl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dojlsjwl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mbahhyky.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjywzabe.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2faeediym.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfduiyps.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kymlxpzb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrykood.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyaghga.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yllwnqwk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmkfrgm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvabeum.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vycegdhc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxcyzsq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbsxkkn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2umzmsrat.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bweagoek.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbrrcxr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2teofxpvi.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qvimvgxw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdleaua.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjxvqgz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcsjozr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oudgrdfo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwllrtu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvhqxwv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vedzsceu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxsdikk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2heefvvao.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjkfvtn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsrwaln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtsmiiz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2irmtuogi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rniycunh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjeryno.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2adzfkqos.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmkgrsr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ungifkta.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2suepjhke.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2revskwrx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjpbuih.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxwidrf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvdmyhx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oezewyhr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtpifax.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmrjfcb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2coktnevq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cighmuoc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqjlpuh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmzrvmx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjsroeu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uairwzak.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eixpsdoz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxuvyor.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gjksjfxs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpbbkck.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtxbkdl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfqbcre.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsbnvxn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwevygd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdatemk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlirpqn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwgguch.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2efadidcz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdaifnw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2udwugchr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbierwn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2schusxdv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtydpvi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2eboppwon.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgfalch.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuveygk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hpidedyl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2grnaypyr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxfdgaz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdicbtf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2twndjiho.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkysgve.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exhpmyfo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kswguoyo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yxluqkac.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2drqjrwpf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mehczmuo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpkntmg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyxzquk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcggbwpv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2inlpnteg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpakplyb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2awauwajs.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2idcpryki.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2synnbztc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2antyxajb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2viemasrs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqltxpey.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2euvqiutl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpjiyvo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znhmdibq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxdbpkc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrguuezf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjjyxva.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qverumpm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbsjvsv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbswtqf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bvacleyw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xaekiyml.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xixujjwq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fajatdti.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwmadrg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiyuohf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2orpeonwz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmsytef.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysliutcr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2llressil.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqvyijn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nirgsntl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2luugqsok.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2andyktwk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqxmjte.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2poqyilfz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmfikia.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtptjgth.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwotglo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbzvbss.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utfehzdj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pqodqxqq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grsrbjkr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qflmjham.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuuzvjs.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeetojr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrhocqg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vaygzhnd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sldgdrvt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xheibinh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jluryvjx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgovnvp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbgxizq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwccbxx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aekhmcal.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cddtnetd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkcbsbt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgahuxer.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qwozvmky.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2inwkxmrj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdmxhen.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjfymfd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqoambv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfftnvi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2skqbfroz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2magimlho.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxbnzsq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrxjzln.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ponfecvd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdzinvh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yspdrrjv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mioraass.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vntrqxdq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdrwwnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jncpwhlo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wkckksxk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aejlxtyl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcmndsr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhjnpsz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgnbscw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbjbwuk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnzrdpr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aicvaiuk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qflnivcy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2umsnxleq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2srjvabsl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pecltcfd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfrasld.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2diufwgcy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdpmfwd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyugtif.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bctqnjqr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mukigpbe.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiowhkz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfibkvoq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqagidc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxilhix.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoscrtt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpzetjg.html


<!-- 参考信息 -->