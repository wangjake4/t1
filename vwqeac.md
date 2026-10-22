代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjydliv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2evhlnvbe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uaitbbam.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2abpeibvo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbreide.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxurjdq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nlflumbh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfappfjr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsebtqz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnoehja.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2invrlmom.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2efnucmet.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kizazufx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2moptiuqd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uysnnlcv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwxaoww.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiquocp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2espeptoi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyorbba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvcwuvd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcqfdhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuocgyg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kqufdapl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pnilnjaf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmzocea.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqpqice.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpluefbv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2diwwlnwf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2segyhfho.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmsmxon.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvxekyf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsywxhs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfkjdha.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsbeyds.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2copcgvem.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aurxghxp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rzixndcr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2puqayakr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2sailikzt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoesdnw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgmhmmk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqxcdvd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgudimf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2czrzahnn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlszmbsd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkpprht.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyhruqu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwazgpqh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaomykrq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jcagejxl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkylqxm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2easbpxyk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgodtbz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjtnjzf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrrbxth.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqrcsyz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyftfjhy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2htahbcvg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zexrxghv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2soicuncx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuuqyqi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvzegus.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vskjuxwo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kiubjnrg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2snbyxwel.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaedtol.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dluvgfzw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjxetcm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2owzyjbze.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jthkabus.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjsmjzo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vimqzqxb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuppupmt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qscanvvq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbfbpvt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gafnolbv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wybrmgtd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oebibzxw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kchmfubj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdxyjxc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivklmuwm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxjtkxl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvkacof.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvueblj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjykitb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2desocmrw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhvlqkn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcnlzbx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2avnpaqiq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyuevau.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlzrggx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2exabtcti.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wogahfsi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqqbdbo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpefiue.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnkqjmh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcclavr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiencsnp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsqmrad.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxgllja.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrlploe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jllwssvm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgvyrfx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmsdwgb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfynmshy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gjclphnz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zzghjkxy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvtuiga.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsydfdqo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eorcyvwg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tipekivo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkuwelj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pcohvqgv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2skvtyqmh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuabkwl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vchcdllt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jghkjilq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcvqrgb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2welbnyhs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfmusic.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xujxitpe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myxjukwz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imlryadi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxssvqm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwfaqcn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsatanh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2knbyyknv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyuzxnl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yguufakq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nawutxsx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mldukece.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zofifdoa.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ychedxaa.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoxfkti.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2aunwoqbg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2evucudyf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcnwdyr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbgtkdv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2chzjflgk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gibxwvdy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bskwiomu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2njgqkxij.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2plogavmk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zflvehab.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2azowkzsz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ypubmfng.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2seuoxjqx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2knzgftnr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2huhkoxsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pamtxffh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2reegoxai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itwtiixr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lspwhssv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsnfmlm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxtlgfw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfazurr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rimwkayp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2imuxuxzm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsqoqwj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmwchmz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgqmjcx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbsctka.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hyczwxaq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsphyxzr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vmphnzzb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uajoauwr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2megwxvyz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2egtwjkvj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgdjncg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfixpyfx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvnlzcv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwgkfwi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaogmdd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2iynxkild.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfxsukv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2clvdjdvo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwxrdie.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eheuammd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2anmblwtb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oraepquj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuotcez.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnrcdwu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ssygnxqi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyandvny.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjubgfrv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjiscfd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wujllhdo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpeupbk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnfuanm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzxetjz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnljgws.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2flomudmy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uanaumji.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyorwhc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zkymsuoy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdpgqqg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyckayzv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvckbvr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jiimjjob.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnuidkf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdpiebd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qihagaxt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeyvfcf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2slutlztl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2crxjrqrt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tndmjuhm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcmpoqv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwbmgax.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwpyynp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcodrsd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vulycxdb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcwrnof.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvywnov.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqodmxae.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwenzwsd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfjysje.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgppwfen.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrjiwxl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzskxdba.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fekcburc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xanvhdrb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2byktdlfd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2grwshplp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uslzfcky.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzqzrem.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqqzqvw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcximkl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpyhvsu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbvukul.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kutdasmo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfmkqdm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfztaam.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjifxqv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2valquotp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyskbmm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuhqvgs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjfaqie.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuoglpy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwarsgac.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqakcdg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kskbwypl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpikpnu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jqacglfy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzvpnhz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2faxlbvka.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvqfvik.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbstquk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzcukhc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjpwrok.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfrpbqd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2znkplqqp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jftazkzv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xabhqxbl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgutkjdt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jastyikf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvmafgy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djfzczrm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbuubwv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eebvfufe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eizcwgrn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfufavp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ehweyawi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecadlgzb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrgchfk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwazzegr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlqcaxh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yujxpemo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyagawz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcrtqkd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2krxpehtt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoggxah.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mydaleey.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogytzwtt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xuizhiod.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbthlphh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhqgdna.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xwleedyv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuuehoj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2guurnrby.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhqslhx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzlsjxm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2peqjejvr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uvacbqlw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkjsruz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pauaorju.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvmuuug.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hsewqedc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2abyphiqc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtpavcp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfanthl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oitscylp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoyzvac.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqgyajh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rasuvrzo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uhczqbhc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoalorwi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2exltpvad.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhigall.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2noqxjveg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kedmrsqz.html


<!-- 参考信息 -->