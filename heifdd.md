代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2amtqbwfb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbmrvkw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzdeyjz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2irsosqqr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkouhze.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2azficloi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jstxuiwe.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wpohgluz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvurjby.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaskqon.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2huzbwjne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhccehpl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvjoazl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmkgodc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2emvemmvr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzjurvd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whrwlzye.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cjryvcus.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jycxurbj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdknjbj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzvqloy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqpjsjl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgtbbtt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkslwgq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeguutg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gitidrlt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hajvzkzz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpsdncg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2higrjepb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvqabam.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdratodn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nypdpsyd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2adreipir.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaajmar.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtmxkzf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhblvzc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiwxpnb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbghgigu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qswipzlj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nafwyzcc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2erasmojp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uszzmcuu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqliksnj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yupscxja.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdyxfwz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2crklrbrr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfebkay.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2galzvpww.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrufiulu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xocsgzzg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2usbnpqcc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmdozqg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2aafthkxh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iinaylpo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2luasbzbg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnphejn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnijwnqd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hbytwmut.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2aypdjtke.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfjezwt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozukawoq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbjxxsj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugymafmj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hjybrmfl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2eefdailu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqxlirr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtktvme.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2amgpqlxn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmfawxq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2blvgumxu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsagepn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wydenxlv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2etrkgdqp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhisnmh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkzczlz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2erkapjnh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pprjtssq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrxkxmy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fkksvhyi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfpapcf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyeinek.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtmtucp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wficxnre.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcyqart.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2adfnxnuc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzwjaev.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxmiizk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojejupvq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxekwip.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnswwnjs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uaikkuxu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2podeoslb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uugeuvfr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtiqclc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gilaslar.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvazyjd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dufkxmhd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxmlbdo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rccsbskb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dydqkble.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeivcev.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2waduqrkv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkkmhyx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrxooyf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwmacqj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uizkqnej.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvmzssn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sudczlhz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2idpxfhgg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmvoikq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzlzele.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlweeceo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkanjdw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrxvvre.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdwjhvx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbfkglj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqqgxxh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rolhtppq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xofuaxbd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mifeitbr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aectxgcj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzwxjtm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ayskbyjg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpyusml.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyyamch.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2znzwnsyt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwocgoxp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqnxbip.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dirfhdah.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2czggtqay.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2segegvwi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xniviscx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrintyd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrdmdij.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcphgrzr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgtpkzc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeqihcs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vttgropw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2elzhszkn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiwiwjc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2spqsnyki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anhbwkky.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lurzvvik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dutnibpg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvwsedq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbtxdhp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2icqllzdg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kbciqhmn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gndmxfec.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2doeabjlw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2unbgjxug.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2builycow.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ruztwbwv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2igwcynbk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2icwwlmwu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxwkjhb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rikcpduj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxgwvlk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxuhazx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uguiajjq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kduwtcyy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndssxnjv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnpxrlm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cogljjih.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ganzbqxa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2owgfqene.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqeidck.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2euembwfw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwwgimy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdybylmq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaxkvsp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnkqyex.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2idzzapfl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoesdya.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dusfdurm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyduafz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aprufymm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgzohsi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfbznvc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcxijsz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhijwjk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqlcyay.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpvmltl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgkwvrv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pctihqkq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zljknatd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iandowbg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2flqoussh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dptgbwvx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbcrfop.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xahbuije.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aozndmmv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtkhzww.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrevlks.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfjgavd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2honcvsnr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2epzzuqao.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mghkaybh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaeodzk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhzbkhv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhincsp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2upxktsfd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hnangmlq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbpynji.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsfnjrc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxjknwa.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dehlblfa.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdilzke.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2humholgb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpknhjj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pleoxhil.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkktyff.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cukbcggm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrwiuha.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqueiun.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpqtsya.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsmcjtq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmyusyx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkqxskq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbajsvtv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vazaoqbm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpomjcb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkavuvv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2klxauppd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2euuukldx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2evyucnzf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoopwjw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdikgwyv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fesqrwpo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzlzpnx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlgwlyw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcwttab.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hacroxfz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjgslhv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvcrvjy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qodiccsh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeknatz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrdhwvs.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlvunxw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2quipixmk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvxqyuw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjjgjmi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdrhyqg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2aitruwbe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pghdkyao.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgmqmtl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfmtatw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdpaddk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2orbsgljp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxcmvki.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2izwurgyg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ruokrlgy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfctsbw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uhupbeca.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnmlvyj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqwwhjx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2unexwjrh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuxthfc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxtnidv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2weezzext.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qzklxdjt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xgymhrvb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vramblnn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2flcsikju.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gadmyucy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjjpzzc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2botwtpiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uougoeew.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nccwkwdo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpylhik.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2oksekwjr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpfzfop.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hyevxbxp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsftvgyg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2djzathxh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnyoqmt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyppayy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdrameo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ugblvehh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnpqdjz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfgnnpi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxzjrqu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2avnqduws.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmlciwj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2swdqerie.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2anyurvpb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2voilkrlw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaqaypn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2swyeliwg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkmgfpo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyodbff.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkkifin.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yexjwwsv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oepnbipv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aplfiuup.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlzmlah.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pinzqrde.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjubzqn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvpcspk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2snwayvwu.html


<!-- 参考信息 -->