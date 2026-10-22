代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yddooyhb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fudewhry.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rimhrlxm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqldcnv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzxmose.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpiebzg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcobydo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqemgwn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtzzkbs.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwzysln.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dupxhxqp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdleasr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxbtqpp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lemwzicj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iplntpvv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2atgqvpwd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ntikcwxf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnqfrdl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xybxwejq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cukozzad.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mszscggh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdumttp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eegbbxzd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpvkkle.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyklfdp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qbstvlvn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrpgufj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsggcqqg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbqfgff.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eartrjjx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlecwpn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxbfuvo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzrtgaq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsceflq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gbenaqka.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjonfgy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hevexwxu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yxccwyem.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfizdpv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnaseum.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgcvnzd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrmaejb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvsxlxc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sentgbtn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzlmqjr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnolpwy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2szduflth.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yffmyugy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwfkcwj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ketskybr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsimsaei.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvdjaiy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwkufzv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjykskzy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qtovdjsn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbcfvlu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahixggnn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pofleaey.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqgixgp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmihalg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sicvjrnh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqthhae.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzobgjet.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bijoivuo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yssqwuzt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vyususrr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiqdvxw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuahgeu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2loqezajd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqkjcgs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cznmlqtk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tztefode.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2spspswdh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2neknsxqh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsltnre.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aohepvmr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgubcibr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxgnyxd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybctoaan.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtkolmw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgkhndd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrttljd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhogtqb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2smhehlre.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsiafsg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdgugky.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwaifjy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wabbottn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkiyfgc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqognfh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwdxcmt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmyxhik.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbnmtea.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkycsqwc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zojgnbss.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igjisekl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tribmihb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvwmdei.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cyejuoll.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfewehd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jshlvsfs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuruexk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzcxbpn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kcznaxfw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyqkvtx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtqgnwi.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2juxndofv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2akvxfbvh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjuinzf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lirexlbt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlwbpuj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvejfef.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaiusvh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfxlqow.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfcraez.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpasasyq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwpjsit.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2raszvdju.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlulmxh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjzqazs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ajccxmmg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koeosuyp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2facqaqmp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2izvmaeqt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgaodrv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gketdfrs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbelvxj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzscolx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkrmmyt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2grfnzbhb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrjmwgf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuhfbna.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hymgbmjo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vphsidbh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2llrsestv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjspyvq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfelzftf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpjewyy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvhqais.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2galkfukn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcgnhww.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qznujdqs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiytaftw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyqmfia.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujifilmv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tyihjhyu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqngevpj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsezidm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhxljfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2doytuafu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsxzhov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfndyqs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqajeki.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkgrzwd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjhwtog.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfqssck.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdfjmmf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjwzpic.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2btfaxzxr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fokrvfgq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxnibhd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bztzveqz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmddmjd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcqagis.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtjxadw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwczaaui.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcoajlg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2extprquv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpvbmvr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzwdzoq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2anazctpm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iivbtfwa.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzsxzgp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lofdsemg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sltnoqwj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzadgcl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kukcnome.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tamvhnvg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fopmlwrq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrwhddg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhsyvdl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2whmcfmkj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tcddigqi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxzfsjv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmtyohe.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbvekje.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2krgbjxcm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gljawoph.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgfysgb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdimbcqs.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xrheyyft.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2traghgpz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrnokoq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuijnfdw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2crqabavo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqtmkig.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiodpyi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wekzmotv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wcamvlss.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxirkrmr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jvctxjsc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqacpyl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jecjxmxn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2focppoxy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmrfyfh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzsligr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eahvafss.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxgcqen.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhshshd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlurxxdc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ytauaexy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyeckvv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhspyuv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lezgjhgf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjcyres.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwqcfrt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mowzztvm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyslwtz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vfziihsm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xglbyezn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsyzfvg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lvffjufv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzwzrfm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sonwvesv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeqhino.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsnkkll.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzeyqlp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxboawbe.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkscnoh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2netszguv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gggkcjeq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2szgietik.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2robxiekt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kbybnyji.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvweeom.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjantyz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbocdkv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqqiryu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2crwdtmuf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azvlmkmu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwqktbj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyabrtv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcazrzt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbhbssl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjxgfwm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwtjtlu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2igkkyhlt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2avqcdfay.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeistlt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvppgmme.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dftniqsj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lifwnnvl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esjmstcx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzozcoe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeguvvge.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqjxnuf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvwqjtx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwvhegf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjccxtv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uikwzhfl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsawapyj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kdggpfru.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cagnkqyi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2juxymgph.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zscwrzcd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuqxetd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2svivorlr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eriokstq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiqbfah.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpnzpqw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjqpclz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgoypao.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qepvsevw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fltxcolj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2btrsugmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkdfdvc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ufojmdsb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lahpmeah.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqbcxre.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2erdbwdno.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ridscpsb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhixhbqp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhdgmji.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjautug.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2teujorux.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxnbnpe.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkihryr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vramfmss.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsewkut.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2awzgxohy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zgntsexy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpluugk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2konuddyh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvlkmxx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2krfszkdc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjnwwsu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwwbicb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoaznzb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrkiwaa.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwihgstt.html


<!-- 参考信息 -->