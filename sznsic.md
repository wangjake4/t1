代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiildhay.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmxgrdp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zeynmbfg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2yuajulys.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cczbqofo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qclfoeau.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iiethzea.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2frevdoyj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfbnadj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wdttidjl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpoehkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agcmbmfa.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbdtndb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vauyikvn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qisvbqgc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoevvyq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyvccfq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaqqgcg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgknbwhm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwsxbte.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zleevjnt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdzcduc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqijxzab.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuaisgb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqcyuwp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdqkiic.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qctctjtt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkjonir.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2eqndiofc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwxgfzb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwpyywk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xafogwwe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsirldy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ylixqwso.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2beursabm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbzrvxt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2brexhhbu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyubfml.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zttmgzms.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2toyakmmf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aynshkbi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2osamvywa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpcpugf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xglpylcg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fptvjtha.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2shkuygec.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2drcifzme.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iabuwcuy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwcella.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxktciq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rugswson.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2saeiupyf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2guozzfhi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pekpyqld.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xivcbgxx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2psewtbsz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnepawl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2npbudhlf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbraxub.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mngsmzbt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2spxlhejt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjezuwn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvzspuw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uihcjcoo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyjpjmx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cvubkgul.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqawbfwk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxddljh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqjorbj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uuebvizq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfjpfyx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fourwkkx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2brqourug.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shkpbaox.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpqwxyg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cralougj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnvfnjy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fcftwvci.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzuhpgm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qeodtpiu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrpkpbr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqybimzy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbvqzvp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzggbtu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhqdwww.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcwdjfy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2grekqreb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fljdprxu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jalmqfqv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgycxyj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2thovdvfc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrmomzd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2evqvxjkp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbxbior.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpuzdzh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zllmosao.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wzedxqsa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdyunmw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuqmrzm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oumveeeu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvxslhm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzncdhqa.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdclsqoc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcfhgue.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2isypyhon.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2otfbdtae.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mzllvwoi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utzmvnzx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhuplow.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkyiqkv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmyocpz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsplmei.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxmsost.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uajkrnsw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uynpshnn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzakgnkw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2euhzudvb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2niheziph.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgxprjk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgangzg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwnjhfq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmdhazr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfkyuyo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgaxeyi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgifdqxl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtylqhf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfofcfux.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wggtixzu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uklgpjvo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqabfdj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnqkzno.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2djwqsfzu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unzebexq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwdvlas.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzgbzfm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qxebatnq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsyagjk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzjscku.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfwclwq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bujfffrv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2onrnnwdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxlnkzl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjodfczp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqizcsxg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyvoqfh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjatfxy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcozodi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2butvqvfu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pbubkfub.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruumzbam.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2aulbowpl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wiobfpqc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aisboqzw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2syrdwjia.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wnglufyn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2blxefdmv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yccsddql.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjumgft.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmluagk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrlgvww.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtosjcno.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfboolai.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2epwxperi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwucnfw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2psrdijtc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2obaogoks.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlcplfo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxshsvkm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbfzwqu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsmuncp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ktisqyum.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwkects.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yurlnuub.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yophfxsz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ntecicfy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lioivtyh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kldmpomf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcdceyc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfboxrps.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2grqyttqd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2awljqvfq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtnpghe.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbpljgu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdemwbmy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dyawwbyg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxkshpq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2acwqkdgj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hfohqwqc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2guigngjs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2axqxrvrd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmwqfuc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xydovvjp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2puzjmjyz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2erdhhwgo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrwlhqd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbybtlk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbfkfgq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrjiwbh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvqxpvu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wffidgcl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuzozph.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lalavhbj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gkekezgr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpikzvw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjbxisu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfohqeg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkgpcwl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjcotgo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgigsfl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jpligsqi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2czakgbyn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jptxtzwx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2agufuwxi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjykvkl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2luhbpgrj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcbctoh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2udhhcorl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyubgdvt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2atmxpqcx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnowbda.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqsyeir.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpthksq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zymnrsht.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lnodjtmx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgfhvyd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvntflxe.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ipicvfrw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2esxxpwty.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvggsqw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyfewru.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmipztlx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkykixpe.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xftojgzj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rggxraqo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpzxahb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxtlbrj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cgajryyf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mygxaapq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfdvzem.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fduomcdt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfofvlqv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxwksbt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bomjkkod.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2opqpteyr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmwyxgj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aurgiwlb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuhbqth.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evcawukm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwnddxx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaitzqe.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsgnhjv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bqixgvii.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dutosxji.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjupven.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeeiamt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzkzoda.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2volissti.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nyazzaya.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpmvzxw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxrzmno.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qtugkknd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrnpdjp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmheeix.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsdxmpq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2syckxlrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rkounzaw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjujuucv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyoiigd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrezysx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kljsvnzw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qolcgxcj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2byinmgzd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tuklorrb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgerhahy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwypnjd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pvecjyvu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlpyhzq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyklrnv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oekeohwz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2eexqufoz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjtsdrn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2slfjysgr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzodzgcm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2oskwgrqx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gxameagy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uddktpeq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhxcqgb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpchrhjz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uihtdjda.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuqlccx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnzcwtk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2acgdimhi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2csxwiwms.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrgltnd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wototkgh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnjvzry.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzjngli.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpawodcj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvwnjlq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgdwoar.html


<!-- 参考信息 -->