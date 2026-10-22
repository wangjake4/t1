代发 wailian999

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dffeefsb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfppunv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eissslcx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kepvcwkr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hctbdmkm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwotapl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ikabdeqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgfenit.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgufxys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuvhmyk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2smisevqq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyisimq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqojvmj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wfapcioq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jejmikzy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqszzke.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnucrsu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2amkhdffr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmhtpuz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhohvym.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2peomauad.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcfjwre.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zcelkgog.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2izjiuxit.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhiwfec.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ivndbgpk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2frjcfqgf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyglfrz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjthxzi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyodsff.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2silzgsos.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeaebyk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2sevgzkec.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2heswilnd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfxntzh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gezkeexd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhancae.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2szdplyzv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2covmbhmc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qswbzckw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrckgnl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkvqmdc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2buafvjuw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoweksm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftolcjhz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2slnnoiwh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyromwo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwhbxgr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gccnntef.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2slxlfvvy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmiudqy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fttbzazc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nofokccr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2akznkoub.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yehybwja.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2edgpfwta.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nezepvbq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkmkizg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqqajsp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2arqvoxlh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zprgedmp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2feaykazj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lammjpcw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jibxgyvr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2frxkqefe.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gczemxns.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgyakvz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyklris.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxizzhvj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjbiset.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzfxtrv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wadsbkse.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vwceosvt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfervjo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpbvmcn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvdugye.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiukfic.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnpsfoh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqyqncs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bptmghhb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dikjmoiv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqgbhrv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rykuftse.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkrdfeq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bsurhqxv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzquxrq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2odttwvle.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqohgojj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2krlittai.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqiceyt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2miuvyjyi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzjglqr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhgxcuc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2izsarvoq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wrridabi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvadwzfg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eydaukfp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfacvff.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eksmmrcf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2srblgwun.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqxgkaj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxxliut.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xivadjql.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqifmfru.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xefzjxek.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2awczwxmc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lszpaauh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgamdosn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2omypefoq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzpaqvw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clozxlhy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tthvzgrj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2weovenfw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjqancm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2leebqspd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdnmmda.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxkeukt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zjijvkjf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sinzects.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgkmrje.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqixszgu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2srhlmpob.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvytjsz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhxkpbi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiduukl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uiknoacz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpfuyvq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2enuuvvtl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2focbnsmq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxwrybk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdxyvcg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlmjutd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2feejkhrn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2igmhsqph.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfphajr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2frpacyxv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2svzhhwsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkmyfug.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dllnxxkh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2viokkznd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkuxfmo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nilgnure.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdryczn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfslqyl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsdkztn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiqxhim.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2psdcglac.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nexzsqun.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2feqkkqoa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nivksruv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2louuqqnh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2irlcxnlz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vcthnbql.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2idiyygwh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqrmhrt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsrotph.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrfvqnf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uidqdaaw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2afwvmeup.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohajpyab.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2eodieukd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fttjqhpk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sapdperh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aracrmup.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvwycdi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzygbojl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwfghpu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjrpvjj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxlcjig.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjrmvnp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgifvunb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsekmxe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2guzupbof.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2alvmcrxt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wriknzzk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2idnpcgor.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwyjcqs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyhrump.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwynnlu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhesvgdj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gizpfpfp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bptbkijb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqgjqep.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gedtpbhn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeenawsx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeupgzm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoipean.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpsxbws.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lozsstag.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2unyhknmx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbkxfbw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyghxzk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvnnqix.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdajsiq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2enqjbggg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2htnotrzg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mtubtkeq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dezddojm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqkbxzv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtaxdfp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vxviwtjc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfnuouk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2csjwzspq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnpwqhd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmrgavo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2luybtxsb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2goruycpd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnibyxi.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbvfewy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iidxrycs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiqltzk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyydulq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rxetzmxi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqrxmcu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcxcavi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvewmch.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gilcofth.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbxiuiz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzqoowc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvripcz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2molhwzoc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qniganwg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwjjpsp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kawzvwcy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2quovekfw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdahlwd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyhyveg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaczjpae.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qsghdcfq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycswmnez.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pwggiqbq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdpxqaz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2spckmxog.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oipowqmf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkkdqul.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxynoktm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkdjdvb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkiekma.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkernfuc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgarwswq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oakuoceh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ufquenut.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlukrbl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wteodwjc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqupigp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnlyhmg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmahgat.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rcenvphf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkttytl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqxoctr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gazwjpma.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wywratui.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzqqxdt.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xaljhldu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgpqdre.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vejvizkv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnkeiul.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcfjssl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcleyljf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxaiwmp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2azsofhsa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjpjgti.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2airbibex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkyuopg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mvppfnhw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2usypdwgu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2oliyqivm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2krtrlzaz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbtgtas.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwqyvwk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2shbmhnrl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2verdwhpo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvduixk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yitsvrng.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkqleip.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlbtjev.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmawusc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2brtrxhyn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2soxxfdgx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gczyhlym.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjotmch.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2imgcefep.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kgayrjyb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2osvndsje.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdpxqng.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftovdvlf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jmznglcz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gviuowaa.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2obtjbmkk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oloualyh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2prqoijcx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sisoyfqi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnhyxbj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tejufzkt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgrwvzp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hngaslzx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cziofrty.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xauzahym.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoliljc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkvhobz.html


<!-- 参考信息 -->