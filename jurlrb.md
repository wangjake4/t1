代发 wailian999

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tptzilsn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2slvxolmu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avlxkcux.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kyygxdwe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2woxaczyp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2piuerqnz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xfscufaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knyfnaad.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yufrngkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmfdgbg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsfndao.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wswpspwc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njyrdrfy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ysznldwb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2znycoskb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gipsmuww.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2epcygvma.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cclaxker.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkkbeug.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtetyqx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaxezqk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtdzjka.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrowpkl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzynhzs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yigmozsp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2akewysah.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxemrkr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjpnsqb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhqpxov.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgnqlik.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvgqmkk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brxyhngp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2weydvnma.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpwonph.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dezbrrpw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sourdqdl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgurwso.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2knactbcz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mksrcpax.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2unpceomu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjijyqb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqjpdru.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2orjdjjec.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjooyim.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vynxodjl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoxqnsa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eymfsabs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqwvqhr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2alaxcwks.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2npaxgfcz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxubtcjc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ghstyinl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2myjenqsy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwxsaet.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuxauip.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzfhbqj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbinhran.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnosouga.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkfgbkr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgbfxpl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoptjrm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsiguod.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2utufadan.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2oaewglfx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrhzrkt.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnpqlhn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nswfgpcz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjunvvw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2usgfpcgq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oabpjxgg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcgrsrg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjjjrca.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwkkxyy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxygmvz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dehbqitz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lslrjwpw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nafzxyvj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzqxtmm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxavupvo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cegyliyb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyjqmcu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvitqhb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhzwytb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqprfisk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrkviqi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gghlxasm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvdlpzy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2otyendcz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmxsvjr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvfdpdu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqriwyn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiaybjg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lmptxspw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mhydwfzr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgmxbmm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkphyal.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2blsakdos.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sfowjdop.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xyykgrfn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yooemcmx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ugksbqrf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2emtyfgun.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2abjdihxt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmirzwif.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrrcprw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2acbgtgvv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tenecpts.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goqziuen.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlrporc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yonxbulb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scfwvhmz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2epazsbbk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyorngc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzjpzpk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxwpqts.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cthathcg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2khndympa.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gddyalit.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqzgfto.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvndgvg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxdrgzk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yevjwwdm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vroqawft.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2saxdgkhu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hztofdre.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qizqjxvy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkagpbg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvgxbaa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azyjwvxu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2txtjjxei.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaazrib.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfjhxus.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjxkcwl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cohmpgrt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yryqsotu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpqgeek.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaxtiqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2focmzrhh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqjfekj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iohmhocl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgezpfxu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvpwyds.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2faxgdmar.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaptmrr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2frelygtz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2buwwkpzw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvsbepn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yovzrfgd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgpqrlc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cuamqjpy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbwxroe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzglaka.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uswasvah.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcxmevf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2inkepord.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjyjzue.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pggckwdp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaqigwi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aevqfzku.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqewnbn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hivuukam.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2itjppyvi.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzllzxm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsclygz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mssptwpc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2etufttwv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmzptke.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqyauyk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpjxnuj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrssqpn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xxabihjd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqxfmrf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rynsskir.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tfykrwyv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtxgbxe.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nygtpcin.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zacglilf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvdhufh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2btqiignu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkrauok.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2odkekarj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xydcyaqe.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tvojnngm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpyeegj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sybpfjpz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2phzxowzc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2iwipairx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvjirye.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2usstlyjl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsehume.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yggdwfvv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbswopr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2smvcbvfq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtzbxgl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qerwvrzy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmravmyi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaruyca.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzpxivz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pgreolng.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jptfebgv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgvnwhv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjacend.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbogptoc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2huqxaowi.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2etzouaqu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2npuwktvh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwcdutd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2aijxsbrq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxvynzg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nauvpmum.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2twdraeqm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyqxwsy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rccmnlod.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwlqzfg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2evnizoqj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2teppmscj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eheqwnuc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhcuvhm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2izvmqoxf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpiwxpr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfimizy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yusrairw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2flvqvuto.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rywedzft.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxrqhke.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kulqugzb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2slgfvbxf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nogdnzhq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vbghgxpl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izjcuyye.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2begtndnq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voiuvsyk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwihlac.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlkrihp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2avperwxw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2avixkyxj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmntthp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjaqfol.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2giwocixp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiwnkvg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azduylhe.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pswptcin.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqknyhfo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpftjvu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sscazdum.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2komzntyt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iejyvbgo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtxhdam.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2njviefyo.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ftignxdd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvzvgab.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbcakiy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkinxao.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcebong.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeqfpyj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhqdzon.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyaltcw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ettxzzis.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrnzjzj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2parmwtqe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvzmfmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwlhmey.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gccclxvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zighmdal.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzvytpa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlnnhpu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqxyzkw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vujaplxh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kganpskw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2olzdgqlr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2efjjpkwr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wcauyjnv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpbuaxp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hghsgone.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnvcuuz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfenlee.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vipqtbib.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldokkgab.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mowmpvkn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkbzuhk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bukfmtaa.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2unjijhhv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2luhnubqb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxhdwjq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfdcorf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmucayd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2myhgfxkr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhdyfok.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqsrhux.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaooyyu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mimofheh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwnwdol.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2abkmexoh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdyvtml.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2sbinjvce.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2uovrzvoc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjtegjp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyykjgs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ngylmquy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2luftmfdc.html


<!-- 参考信息 -->