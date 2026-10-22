代发 wailian999

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2riogfzuv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gytnfbxp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2maioagup.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmxkdfc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bniopquw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wacwhuaw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tfatabza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2molupjwq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qtidhpxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhnpvmq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2scfkxluf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pncvodum.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwccugfx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2elabsmzh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjeuszv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mupiuykn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvimtktm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfnhozd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wziygaqk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmtaful.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeqmnlf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mubisfhl.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uohuidcs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzjypev.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdkhroq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwsifuj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjzsape.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mfofjvas.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2figurjnl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dwljpujr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oltvoiyn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btzoleot.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfmgfcv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ochlawdv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmkpdap.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tadnkkcy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhylyivs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zimqkvcs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybljjajr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsvekqe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmswakr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2utjestbd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnhbddx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlpdfde.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgommhin.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsroaxy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcckmuk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxpaoqj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2aunklbke.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2chlmjtcp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gisykwbh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qpolhvxh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkinyaq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxryioy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwvrpgt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tysgpsql.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmkzndd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2njmveoep.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqnimrf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xagbummx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpziwti.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dtogjfxy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbntzwjd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvimbtf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhpjbwa.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrjbwrm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfiukqi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgczoqi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jojlxfax.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znqyriwb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kksebxpx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmerwcj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2krzxhghg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlyimyr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2teenvsbp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxqhfxq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsfnbfq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vblivnzz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcfqcoa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqsosww.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuvyblk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlairorv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pozpodvw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xokvawob.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ipghawzm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kblgxogq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdgjqbh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyvorsn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkkotly.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2isylwhzn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yylteguz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lrogonow.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsuupuq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2roslkioy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmynnci.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gukjsslv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txxodkjt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzusuhk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyoxcef.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvicymy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeontwn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyzqfpf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2onotcvjo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdvgmom.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjeuqer.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcmapsc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ceawxkyv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqikpba.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wnblatnj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsyxgfq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qergomar.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2aopixntb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bemcvnmn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysljfodt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgxnqmg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2buyuyiph.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2utabvslp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkkvlwb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqiwhqh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vncginxu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrsuefx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2whpejash.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2idmqqwqx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gnagzaif.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2egcswwnu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2llpcvgkv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxabbkqv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xezyosja.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqbfcjv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cblwztmz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vycqqdhs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjhejoo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2enbrtqnz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaujbjd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtymykb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsnssex.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdfdxce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwphtiv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2spcrxonv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xngrqhtc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxxmkzc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwhnyjk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvudhns.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjfffnk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnacsst.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ergzvjdh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wbivwqzs.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeubuvo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sobqttsn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpiltbd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrmqkxl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwmxjby.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dptwqouq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2omterfon.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iurviswg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbjksbk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njvllrne.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgctsrsf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbmvsas.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzskffyp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ovikakoi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfpypof.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2shuatoyy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqivqtba.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbhnwuy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkloysvn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oabirpwh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaswrcca.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2eywvtaok.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzmoika.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxmqtde.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zktcbjqx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkrgqgg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoaptgg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjumbsd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2armzuuch.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mmunnczj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2auxfghoh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsvcplx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjpksbz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkjulvt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fniuqhve.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fqooiicg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzkyfdj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfidgfgm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pswlehvq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zcelfjvj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqokwuv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2riygmgmx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvizjkk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2teqqdutb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfgeysi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2peqqxohn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2naoiaryq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2drkohkcm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzvexgm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jlryjxkn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2krufhmme.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbrgrsi.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpchofmk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nxirstok.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2csoxzwbn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkykbpz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fakvwqcu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bowddgmq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2okhnarfz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkzyvdj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoxciog.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uevzjvlq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuouvoa.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2erinztet.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2npfcajfv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zyemldcr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiecyxn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fisiyjqd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2edufyuqa.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zusxdpli.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpexwxgq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2doreykzt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lytsczrp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsobqxo.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2muzkscxr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eqigefof.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzphvmz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdatwsrm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcpngxd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgderui.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvygmuvn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zltmnzww.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyffemyw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fwabjcyu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqeqczb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzxxgpb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rduxkmqg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2odjkssda.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrseyafr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxardpjb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vivhkszt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgawsatn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhctwchf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjnyxuf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgixwql.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgddilkd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaqflou.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxhhvbq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2haugotmm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyrogvj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdfmwmv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2teasqalw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2okqpmzcc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdhqocr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgqqnkf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyixtecx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bfabdjwm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2afrqqxfb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmsjshh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsdojne.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fynbiexg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ithbzuzi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2prvrvogg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2reixdrqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kspnmkfr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxrnmhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqqruqb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bekkmnbw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kruvjjvw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwahycf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbjuozr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjmzbpr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2znylzzdt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzhwhua.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2erptwxix.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sropefwz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2acibixoq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kduqlwkl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqkjggt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnltklo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2citlueax.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmhfczr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvjvcoe.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2taehuqfq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdwdvqj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yekhuihd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyevafvq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpjijjl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoemzhj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeweccb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfhgzmh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnrkbho.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvfpqwx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlagwbpz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbadnne.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gqatsfqh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxruamlv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wucdaowa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzkfibn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aoodwdql.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pblxbcui.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcacxeq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkehckr.html


<!-- 参考信息 -->