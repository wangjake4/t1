代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2etautqcq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2echwlpdb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bviabley.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qxugmanr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbjgfjd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnrjtow.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlvyhfw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xftukhik.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbhbinw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xilnbune.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnjdulo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lknphjdj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ownqpdne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zchzzfjj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dcthhlpi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pjivvpzo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crfvkrzt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfqbslj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwiodbe.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqckuty.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2baysbsso.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2agzacjdw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxlvghj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnzptpp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifltbckw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmwpphz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2luntxnqh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zktcmidj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnhknyt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbvueqe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpqgkqa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cnspteyz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiysttu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jbizkpow.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqznaez.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nflslalz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsvmzqj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nahwxeeg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqmduqz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rneghfhp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2komcgftu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnflziv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiykpgk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hyumzrsv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tscbxoil.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cikcyyne.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeiodsi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2asstovmt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2shsvezzx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bgredasn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2msofljfj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjapsets.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2krzmwesc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfmiybz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcbhusn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgoxfaz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oampipfj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uoclehqy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sayjkrci.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ligyyxke.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2csedcaky.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdqxrud.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bszvwcxe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoyatum.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2belvulpb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uqroihhi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdggjte.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ndacbgon.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmotgso.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cromrhts.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2twyvlkhk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2apaaymkz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxtzoim.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eudejonv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2eymzrslh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmehphl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpqvliz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2waqhkutf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qmodyyjs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gufljqjr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sqznsztv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaordgpt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhrolyz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fafyrjls.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjifypq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wznhaclr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gfikapyp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoivxvu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyhzxsj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrujizk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfebltf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mebhivld.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jseaabmg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2capcyrnm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrgzqcd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wwggieqp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cigumftx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfvcyan.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwlwmje.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2idcwehkz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyypgoc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pquymoim.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzemoij.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbklllx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2weshiqmm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbugxke.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pdibmkxo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yudykwrl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqedehp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwnvytk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjzyotb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wirxwhwj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oghbvkde.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijymzkcv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afrcnhcx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qacgfeto.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmxhvpl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmgdbcv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsiockl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnfccbl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aivzwoxv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2izwalyvc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbsaokr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2erzqwbuf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sadfkvuz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tyshuton.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpabxmp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmxeqsm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2effqarnk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sahmodfd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdysufp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fmripktf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egiihsqz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffublwjz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qahpmuvl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeawwkw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sznfwixk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpjqbtb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yklccljf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2twpsiqhe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2punqsnxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fngqsnja.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmfejjc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuldaidy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqnkegt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kylcgult.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjrbkxc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbqerfz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jtchnenh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjjckcz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pklnuwne.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2otiqquqv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwrsmfr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnlhyge.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wangjtoz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rffnqwbp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vojbsaeo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lllktxch.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbqytbo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbatgzwi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhydhnq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwejmlvh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzseovo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkniszz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bauthfsn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2grwzlqua.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfjbjpo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhyrchw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ituhkdfq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wldkvphu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iitmvwyz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzqtpms.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2knzebafe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwftqhnv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2daoroxap.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmlkuot.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsvgebu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtrjrol.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrnrhpk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfqszgp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxrcngp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsgnrkt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjydqjs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pklxndyz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwqwtmg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwouish.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2agajbfcd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvhdvex.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvsnedb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2opicpicj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xlonnhrh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpmoetl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkkmtjs.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzgnudy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzkaoua.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnpknga.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rewdcdsj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyluwdi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvcvqvl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrsgmdc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ksukizdn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibijckxr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yxadlzbv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2enjjqqtz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cpncftme.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjcqkcs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgqpnzw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwjfimd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hganyupe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyubwmh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdfmedr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnkqzxt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2szgriecc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtstitl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qymnmjwc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoxnjyf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqjvvku.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bunlrcmq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cljyoyjr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvuzkis.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgwpdyi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmenzxl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvtnkyg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hprvyowp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jrczgbin.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxqjfvo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrhndkp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqrgdrj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2alheqeun.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifymwpsk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfrmuja.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tceogxkk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhwxzxu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aonxlmof.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuazfab.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dabjyuyb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ocawhbyu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmuklat.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiyxcvr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpekvbbz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gykcxbhq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgbzdae.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avtuldcv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcmmtfm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzevonhg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnvztvd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyqkeyp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xzftfcxz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vyitkdis.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsdvcwf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdutpgeo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaujypq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqauyyvi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtehuoj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlusszy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2guwwhzpv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2innwanqv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvmrrjk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgurioz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sjquewqw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpthmwv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2djrlidqu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvzcogs.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cbalctly.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2itajdlpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuosnee.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2knkugrsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uerhvxsl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwqtrpb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjpeyld.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhavjit.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hjutyotc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pqomvsne.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmszrcft.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmcflxv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2muqewlnt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfwcqry.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqdclvx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2inaegocu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzbrpzg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwseyye.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2emldivwk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpfsgpq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsplekl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dumtbmua.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdudfkhs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zkakwqxq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2aovxysqz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wybaowsa.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycebrmve.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwzyles.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgunfxm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2twqafukt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqtgyly.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcfqkid.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtounify.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzscgvv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsobilf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcmbuun.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuqpdcy.html


<!-- 参考信息 -->