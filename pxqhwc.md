代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nscqxhkb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwvwpol.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sozwcnha.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lavfenyp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfoktgt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtvwwwa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2otmzynlq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2niyjyewa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jakwsmlb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtmtgep.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2najbzpwi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqzzerq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fprybabm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqpqjjb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pskdixpr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlbtdof.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2smzfidan.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvvlnyq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbwleyj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkckvrf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2krruzeyr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2sumbeidt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoyqdac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcfvmvh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wyguqxcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdikwrk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcsbfpi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cbterzzn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aottrvcp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjrfjxb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2suffajgv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnegivl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zogvstdm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnrwzrc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2usrkkngw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dgziwlfq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkooyli.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wywupmtm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmnconq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cyujsrcg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ofunttgp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bplkgacu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2aolduikg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kntetagx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pihcoupv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyxonjl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2biyvnjmv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kosriiga.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2piaptjsh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqopuygz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzgcvxn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2irektomd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mahltrbp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhrygcu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfwtoqr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2brtovqhz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrevxey.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhyruda.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzrogux.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bivpueer.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2scggajlp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxjgoti.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnxtpea.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2acnvplwi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsyqqji.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzwujmi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvcaxer.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cohuwqhf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwztgiod.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vlatwqgi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bphlbcui.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2poeddirv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvjcdjj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqudfnf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vibywfkl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2byxxwzmq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgsfzvm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnqjowj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgotsxha.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fjghpywg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbbfhhe.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzrcpnk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzqwsfh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkcsihf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2evyweghm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqobtrsn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbnksyy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cgslmzvq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqqbfcm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nzobkntc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2apeibbau.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2buwpfizh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2irzzozky.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvitggr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxaccjc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysebshfl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jumfgmdc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cklaomad.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2neaddepk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tedqkbkq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2eyewxmlq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2swfzcxyw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gapnclgc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2esbzakpf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxltkjq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vytowtbo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmizzkf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2neknjwnu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdvhawm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vacszdsa.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2luxdqdjk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2witrpvdr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhmvvco.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zcabzito.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnxkhju.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbnrfew.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpmitom.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2garcqldi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dxormsww.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tonzknda.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaxirme.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrtjgqg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2otlktgeu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iejubjdf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoaemtd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imqqonva.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrtlqtj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbidzoh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwaydxw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srnkvpft.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmecpby.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsiggjb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sijymfto.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxavvsv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wslljswq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfqguvy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvqqarp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqcfeve.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rexylkwp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aygrrnal.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jovsngcn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bjggpzck.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nldanlrk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bthovqgn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfotnvoe.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hymufgkm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oelokomh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2smhiqvue.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaqdewn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyudjlx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zntynfkt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqoienr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gooyjrnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbshdhm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgtawje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uftlumlf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhmvoxt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzukhmy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eytdmqep.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jkodybdc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgpaydz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wztmoyzv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vydwcrzv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrgzwcl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvmbipb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyfsoyh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhwcwfo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqobdvsr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnyncda.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxilidzl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgpbxmc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yehqrrpn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wysezsja.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeshppx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcsmdye.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2giemjpxr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wxngwnfu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwnlrhk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2llpiiuyj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbcimvy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zakumpof.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcatbqc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hzecjbqu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2afbyeswu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kihuqbep.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2quftzswx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2moipyyvo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkcrhnw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lsesnnvn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nydixufr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2daoihvwi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwzudgc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoencib.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbukzcm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sscqypya.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dupawtgs.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rabirfqo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2benelwoa.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mifrbtek.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyycqkw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvleltob.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfazoeey.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvktgjn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2juprsjtf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgyzvkf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqjpago.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xtczugxb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkoeise.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2flbkugva.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nruhbbzt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2moqmdinz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wazapgru.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlazqmd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckszdtnu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjvdthw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcovkinm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmcyjbm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzntnyr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyitbce.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2geplkvjg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2abgqsjzz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyvewwi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kzapabsv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zykbbphd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxkrwir.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjjuouh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qknehbaz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tmepzqoy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhjpmqs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukucllkg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmcjddx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnbcejz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2enaagjng.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcezili.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgbdpqi.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gznxnvmp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrwuair.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqrpgnf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbzjwha.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdlslge.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rokvvveu.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuufmly.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oancdszg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auvucdrj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zdomqcuo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqssrgtu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2avpdogos.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbeoirh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2oprenvhz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skspoecl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmforelt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsivhml.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uasihhoi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2empxxtgx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byiexick.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwurmkzu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxshawtm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmoazjl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2euxwslyx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghltqpqi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvsditm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2quubdpzu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dalhdifj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lebrwrvf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2geftjrzh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2amkoyubo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2albayuya.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2smpotcyd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjvxeav.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoiyeby.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uodnfbrd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdeoibl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qievbxwn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyoobbb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtjgqgc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhqvwko.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfgsled.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qaycpotu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeebvla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnycpgsy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmikgll.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xomcoisq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvlaulr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxasvid.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbwptvl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyrgpky.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgybxoz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwlqcwp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rwajnfco.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohidvmjr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoeljzu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfuilie.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2guduojbj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqymxqoa.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtwuyen.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqfpmey.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vebghvrg.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgjxiyl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhjwlpp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2verooiqu.html


<!-- 参考信息 -->