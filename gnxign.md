代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2chgiiwnz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhttihv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlgppmh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ingrpivp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pewtnkhe.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2czubfqdz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjiiqed.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sghhhxup.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoderch.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rroyihxn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpzmuqm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgcbqng.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uivzjylu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwcwzwa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2opzyycwy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gqywxhnk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvxjxnm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmotyid.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2idqpusta.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoppuau.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2atmjalmw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrgsafv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqcoauq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wazfjivr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkbgmle.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgnckls.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzzflgn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiafovr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxjjepn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2youleqmr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjqbgac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypseowao.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfnjoqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oudebvzu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzzefph.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vangxxwm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhcfxin.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2minaqpqd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2npqfvfev.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzdkawj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqjqhzo.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fznmryjt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzzeelm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiopfew.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bawodjbw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tkflrlgj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jkowvwzi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgbtovr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2posmwfza.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlyfhlf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzagdyhp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2eeioeisi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkjndvt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsdkhac.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdyxsqx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzsjjkv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpfkesm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkikezw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtwaiut.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeypgcq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqoekhd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjvvqrs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgxppxl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2icyrvqcc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sycgumtx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfiqqzr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcnmwzh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bguxtixv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyhwaef.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2abulkggp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lektsver.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbiknlm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibceagpa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2exumirrb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfggppx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2izfckxao.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbbssmj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xobcrzwz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuaqmck.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2drkhixzz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmpcxiw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqmwxvn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2idssdgsd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uncahytu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqenhykg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zixdwixq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vivranmc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pvokbfgg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qehbljvs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2spvvzpvq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcxjikf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlicqug.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrxovsk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eombeuge.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hprawkxu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zadjgrfq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2phtmnvpf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqakowb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bacgakoy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhgnkau.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2imexqved.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbucdehp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shyckbkv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnbxjoy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jgetpudc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2huslsuyl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqiyeni.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gziklfdq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zmicqbgu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyynyruh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sewaiwyh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2unakzjea.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yugrnyig.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdabzqt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bipkqcwz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdjezpo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jerkuwyt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfmhscx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwkptfb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjngknie.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvfndls.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jcucbzhs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkubifxq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxksaunx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxyhgpz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqvdtrn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfaknos.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdetrqd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqmazyk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2exfviczl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkaxzzd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtumfpvz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2slaupsyb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtevayg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uaddrnoj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvptmjr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wclvibdw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dabmkpjv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgsmpia.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iipdjtki.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvtslnr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uckuujvb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfocnmg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zixcjiuq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmntrwak.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvrczen.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2itgjzszy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnrfvxv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2beloysou.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpwtemc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvofqsf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qakraerj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbexjybk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyrvxal.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbyzkap.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2olzamped.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoubybe.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrguqqh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmycccfb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzdyzzf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbyrlaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwrgmrp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzxhtop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zetimmwz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2geadeiwn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmbaitz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjyokca.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2thpwjghp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2njvqqpcq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkhqdao.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkrmzzm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2berlozfk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wytyxdra.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2znhyyals.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbslvav.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2idlpqzsz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzlgnvw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwsskiw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mnucbpid.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2knzcobhs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwtjvxz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtkmvqe.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2skcsovbv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfenohcm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qcitjrua.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvhplho.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2olsqidie.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzokzgzw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qkupbxvg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfhwdew.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nufzuktn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jscjmpnm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpjsasz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnyiyma.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xyewssae.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2esunsnzw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vffsvdvz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrqzbjx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uikhskdm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbihzbca.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaanhnc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbhvwjf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bseufykz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2llosxcfe.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2orznsbip.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpcwrcx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkbbvct.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhsdvvs.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbtttza.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjinhqu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bshnmlkq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2euynpnvc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tufglkhf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrxxvjd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rhipzztv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeqnmlg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ujytizue.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrqttey.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvockxz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqspdpbi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yozvmnzu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlntqpb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2blkxgggi.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdkfusz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dehirecy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2agymlqpn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oclftoxf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpjjciy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiweqqg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wannviju.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdwvjnt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhukopry.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2erotpphx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2patqapqn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqbiwdy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2raufdosr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcvqrnp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2muhvjued.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtlbymc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqyaakb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vambqdby.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2miqnyjpu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2anourntd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2auupdhhi.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fezniwml.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2grgopcly.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2inrouloz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hozdmzfj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oibfpjua.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2btfswgbt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2maakgfmi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mknhktab.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2isdbegoy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdtodwv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvougqf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rftbvzed.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgamecg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqyiort.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgbztib.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhfcnvh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkzyxps.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agngwvcx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owgwftqk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2htmfghis.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxnlwiu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqmluzc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbjkwrn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhkvjss.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeuwhjb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xabrkshl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhxsxdz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2idhvmemc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmighos.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgdtiju.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbthzyl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrxlnbr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcyuffs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpyjyjg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2njxslbqc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2daulufyy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxelhgl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxtrftn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoedocr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2agmngefo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2syvkdksj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sigiojfe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpguehe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyspbud.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jntjufkj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfkklmu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nncyqllz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kaifckxq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvbbqlf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2scngpgrp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhseiwd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tebcajgx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sjphnnhg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzlewfm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjnzkbz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqpfdof.html


<!-- 参考信息 -->