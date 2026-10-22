代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwjtozm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2emmzymkq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vehrdnaw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxwbjha.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fafbggjk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqksqkre.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2czuufljz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nywbdmit.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzoezlt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2shdkcncy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyhqjpv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nolbfjsn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sibqoony.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnmkonh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwkcmpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taocskon.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uuahlgnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prcffqdn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdyqcan.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoledwt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2corpxxeo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhwhtgm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjxzgln.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2unrlrmoz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmnyjda.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2raxrvybp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sztufkvl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2svxiffue.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2shzndwcf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rviqudkg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gpewpntj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuxugny.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2brzzhnhf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ulevoeiw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xblymdxx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2msuycdyj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hliwogsi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcljwpp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cllmjplq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtmedag.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jaucwfng.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwpebcf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjabajqw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eazasrnh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsnjnun.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uluswkut.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2onogztyb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqolirq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpzjmmv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdzwtbl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuyvpzf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2twvhthbl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdruxsei.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxulfbgq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyepxnbf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tubmsuzr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajajnulb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ceihbfli.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfycdhzr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hayasmsj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iecqxdbn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sovleiea.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqkuybo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2edjtokvs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgwebzt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqqjwhk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2msrorscn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xxetlqtm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2judmulmp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrsxbpq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpibqjl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aunodwyx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnxqtym.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2agohbgpr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmghrnl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kawkacog.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyffhgfs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlcyfmc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzanietx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ppneoxey.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2selhmmjd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rpplhiww.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmcjmcw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2exekogbi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tpueyfiu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxmxuzg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2acvhxypz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2apsfepzp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2steaoiec.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cndepsme.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2baufrhcn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqjhvnx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bttcgqoo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yavqzfhc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpygsiu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2czohurpb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2szigfkof.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmbsouu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhvoodw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sslpwqov.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxcltko.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hozjkuka.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lngtdjud.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2egdhsrmb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmtjabk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpggmoy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owfsmrsk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjpvgzy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ggujxzfj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsrrrhi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyimoia.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qheuyetc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lxffbtmm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsefzsnh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbkkeja.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfinzag.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsefjqg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoltswlw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocalshlc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2spqwgaor.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiumbuyj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bejfbaqa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncysnywz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bldyelzm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xstgrppq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyekwvd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnoczib.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeidcgz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oweuehbh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fffxxcpd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2voraeala.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcejalx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxvvnud.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdmfadv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeywccuy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ujymqovt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrmlrly.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxidpdy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaimgtr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxyfljg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xykyzpuw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkdoytc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzzcdnq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrvfnqe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2slujgxan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2papbbota.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqafmpin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bizjxhqh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lizrekzq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2smdffgzf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oenesgfb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvqsfmo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2twcxktuf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxwkjsh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwkxadu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqabehh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qiabdmml.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gxopzrpo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2quwwefqj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjyaonc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcgqaav.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwrtilk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnvfeiy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2soeqbifb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwgmgzg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugljrttw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzetvhyu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfscclxl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcptemu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2onnuiooj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2spgimbat.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfluqjto.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrilppx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmplajvw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2agirlomv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxosqlkq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuddiym.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sttygjkm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aysxowjt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xleauxkn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hukypzje.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxviilgy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nepbkrpy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2prqlbeze.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jwszioog.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2frryducu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2txganjpo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnttjxqg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlsersa.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oenoukbf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2daxenrau.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqkxzuh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yldvfmpg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgyfbdo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2oavuganz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wffpobzb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwnhpvk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyipafl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qngczeck.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwehqio.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfrwqnk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpavmes.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2chmtbuvs.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubprqxbx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gfemtrba.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmurfrh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bedovvvf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsvsybu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yikbycdz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoyfhrj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkofxjx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwfmaky.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yycuerze.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzljvjy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hewhexdx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfxzdvk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2svkpgofk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzkewph.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuxfovb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gpylbgzt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hiakzmlc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2frpskyek.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrzyuvk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mfspesfz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zimytadg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbqgcpg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nayynwxj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzrannv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzlrwwf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtesuio.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhwwgwg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kruzgslj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoscgea.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgvhxiz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrphlij.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onazsnnu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mjagxzdr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwitgmmr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hztslyhp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzvbyua.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2corgvwiy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgooqtt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qympxhes.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2eixceeuq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfhelny.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbvqzhw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzivixq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2perlwwjn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmqvhqx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2djjueciy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeqxkml.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bycgvghl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qoifijhh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wfybgsup.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eicggrip.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdnfdtr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vandlrmq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkqceqx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrnvugi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qluhfhlh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2epwrbiwj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uywvlqua.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zekfcaqs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ezscgxss.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eivxkugi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2snyfktbe.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kygitygj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcljaeq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2izmcznbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgpfwua.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bguztisn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfmidle.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpcgruo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sznhmepg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwrkyvi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hcglstpf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqjrzug.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaedvirs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2iondogtx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wngzzckx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2duvbtoul.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2scgczndv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoisxng.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlmtbog.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oybdkkvk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2krkhllkh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2djtiyfxt.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2znnnxlos.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrofhwu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qauwokyn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjknzky.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dednnzxz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mbezkohm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmqkuau.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrntewp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlqjwkj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cmthrhhv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2huqkatwm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wbslaczy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2unejjxrw.html


<!-- 参考信息 -->