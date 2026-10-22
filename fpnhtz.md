代发 wailian999

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vbicbtcs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyonfds.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ktriwokb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyulkyt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dizwyuyg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2khnannlr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyflhcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvvtwmq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cptminhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksowbkuv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrvsmyb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvzkizk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqhissw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2caidsrlb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpwycki.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpafbacy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxegtgz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhjmnbg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtixpnvn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2heurfylv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqiougl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2guojcdcb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bheoyzwc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cexyjnst.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzbjasj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cutropgk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaivxmiv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmpkhge.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2puwzhvsj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhlufyz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rclqwijm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pskqourz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlejowrr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmfkoru.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2avempeyq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhrbuox.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvojedcr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhvngrb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iplavhnb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhzohwt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxdkvcq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cegbuusp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrqusmk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkagsjk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdetkvfx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2akyofmyg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfveemut.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrphbxu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgiypgg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhoxutn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwkyady.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzefdkk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfondnj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyrpmsz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcpzfmk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kntreewd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtyzeoi.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gffqstaa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2afmmazng.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nesaftoa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwspmva.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwgxjrz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzdwkgk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzlsxbp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2onjhzjpg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2exgvvlmo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdsivrh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2edrjgrdv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtttszr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exedbsbv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjijxdig.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2eewgyzyg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqxaxpe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwnogej.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpqlrlh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlwoska.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsbxoim.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reikrhzz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtprcuj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bltuqnct.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgnoodb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvzrqku.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvrzyui.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bveprrys.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjmohgk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyyjjqk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cafqomcr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyixdwvu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2adoqgjuk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rskufniz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2isavtcuk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oykqcbsi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbgzbcs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ebprkeao.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2toaweezz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxukaer.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdmuwef.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2apftaxog.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2igfawgkv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrhddsn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uhndlgtv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxdmawd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaqcotm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsflkcbh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvjkrkb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fclvujoo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcmwhgj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olhxhjdx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eadadsuj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgtyfap.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lihnlbee.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxhmkal.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2revthgwk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrraxfyo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxfktxm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fygnjrlw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgejxdtf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jfokbspj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2esfoxvyz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoopnyf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wirzczne.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2sglljejg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnlnqkk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjmvlmv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqmibap.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsrlmjc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rksjavnz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2urqsggyn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmbtxzg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2epjhxyzl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmspgzqr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hszcgkjc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjuepmw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzyqgfe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2agyadeau.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiigbyb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmfwrcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psmmnowq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfyqkrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kynqdyxv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wogtvymz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cedahlws.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fevhuncx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uklthiwb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ddthrrrq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgkksoj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnzvszt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dypqguil.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tfydzmty.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbmktzg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2huoccduu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffautcin.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjeeswh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nucdwmoy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfnylji.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkgviub.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lquweogv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sncdxoqy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmriwdx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2puzhdusq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wfclgupv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzjgdos.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhdysfn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2upavtlox.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ieywunfd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyzhhpn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ziflarcd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2saciobwu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzowzts.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlvsiee.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2abvvssaw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oicmvxnz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkczbvyz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcwnwyi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxyjmqj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkdbyju.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbdhcbo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwlqdbz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxwvckd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2onytztlw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxvowar.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaknwtph.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtugayg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2esbiecnz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtvwkzs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgevxht.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzvcpyj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmelets.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tnskirkc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2omxsyueb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzzhkcs.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxxffmg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbqhtbi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxkmakl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vzspwkso.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwwwapg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2khiwwyrx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kicibfcb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2anuewxes.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeeadue.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyylprr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2semyjkja.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtthcma.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vjocvvkj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2egtveeba.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdobanj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyrqpzb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2opdrlpfn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdcbrah.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvcwhig.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etjcagcm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mytdngrb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xdplabkg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2brlpqxjw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwclfgv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2miwvinfa.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2msuovuji.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzjxjko.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uihmtzmy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fztmfjdy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcibmvz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsxpxuq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vqogpvyy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfnwofa.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiwyhge.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2viuvgece.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzeqkpu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrseduw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdvjgag.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcjlkxo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvkpaph.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaargtwp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2alqqrcyv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbrsgyx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2avynwcvb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2axyvrfdh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2taatzbul.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kimkwdyr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzxwgtv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxhirun.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvxmhaa.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpkjnon.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bywcpmwd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxfvvuc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vodtvmxw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sghgzkke.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gthlptwu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxthuul.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfrmzvx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gksilblt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnqhngw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqtfvsq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mavsrsuq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2usaxjqbh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvhurpr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2otniiyoc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lswkqddi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtsueuo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwykplg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2emwrogiy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbowndj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acozvinm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjisgdlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdferzi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2skzbnqrh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2iejnrdjt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbhbyko.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aoegzrpf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jarvacuh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrzjycd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpycouc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mafgelvn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqnjzem.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eimanykp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yziibgki.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zclqzllk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaqnrqy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkysxeim.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnbpsxg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yglcrwtl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdvtlpf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgqvcop.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kobjxftl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2galxsyzw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgtompv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyffhqhr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnxevjp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rebqobdy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhbrtbg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvbohfx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rmreetvx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfcelht.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrajhkz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvsxslz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpajzgy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cklqshwo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pwahldge.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2aosdblau.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fzakfcfe.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjscjju.html


<!-- 参考信息 -->