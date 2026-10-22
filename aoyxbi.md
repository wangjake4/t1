代发 wailian999

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiqjppk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nyswmtuh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvplqusx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2djmdxrzw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxbdpkg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2iyicslyi.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzqcqkv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtysabj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwlrobv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rszojcwv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sargvcik.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2llxlzhcu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ghukhnyc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2skpqoacw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhkeefv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrntfwf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuabzpk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxloyngp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vkniesme.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrxmzuj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xladbcpe.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgajpez.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fzomqcdi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2htpmpwqt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrjrkuz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcqfjnf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2audkauhy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omzoxohi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtlykeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhleaef.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcldfjv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2urlffzsh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqhnzqo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqqxvrp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoootokq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgzfnsx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iigiosox.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2buwlgdrh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnalbneg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2huvlbfxo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrfgshv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqkkcbb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2geiyhmpn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeiozdl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhrawky.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnedkrf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgotdooh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fozzpllt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdrddzs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgurjab.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjzfute.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khhjnqnr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtoqtbi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2walfxuru.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcricnu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzhdtir.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvzrgza.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2flqictxu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfoiayj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uhonrryl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zukniylq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyklzrb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pzskzphr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yxilrenl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlibwsd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdzwcmc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rulseuvb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoirdde.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sponxngx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpablge.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtoiacy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gibrsbwa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gexthvog.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2scsrxkvs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuswqea.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iljloanu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xujrneru.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dntqdfma.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdnpcrf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2smtrvvad.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nymextig.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwcntgp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlesvld.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtkurpc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gemwdrse.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ytimbngx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nawlzomu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaibubd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fukovcbs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuvjico.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2abkpbfrv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwdpncj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pnytykjx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2brmerwqt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxmdstm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zikjvfzx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzbnbfu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zacsmmki.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkidqbxq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtzbfir.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhajstk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2emwjqctk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dphqcaaw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2telqanqv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2advekfsh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiirgqot.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwtavrc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvswiqw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtsowrk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eazimccp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2glkqozpq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxnlyts.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlgqpcg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2euavlrzf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2edvlsjjw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2byfpcmzu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2reopdrkk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pykqjqth.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhnlzov.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbarsnq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rmazjiey.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vceinggk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoayhyf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlnnibe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2btckgvue.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aubtyjsw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sthjapgc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2remcalqm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dqikgndh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nntfzctb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwrlhpr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2njpfsjyx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhyfmvr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbpfzgv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2komhwuww.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pgunkecx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrrobqm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuvavcn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wqznbwvc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcinzew.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhqtiwm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbttmkr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgpyhge.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cssvcqvi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oncqualy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfcucnt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrusnkh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hmorfdij.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nizayrii.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhchqop.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbuqqub.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2feshieun.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2chzfbwhf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwyajqp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzplifng.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzlmvqw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2suthtyqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asyicybc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kceagdhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wafwpcgq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hqstnylj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdemzpbe.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnxxejo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdulxnb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2svyhrslr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2saoizuvx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2spopskra.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2amxnwoic.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2slysexyr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2txbbcbni.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2swrfnjdl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvhlbnx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dkebyjca.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2otznxmow.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjayroa.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwvctvw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmsxvgr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yptmxfle.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbixvty.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sasxrvlc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfbhnvr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2apnnytqr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kslwlgfu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jussaadj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ctubtsom.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2stymdiab.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hepowzpr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2asvmjmyb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tyokpqxu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdhsvom.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhatflf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnsface.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuwsgof.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yimhvwuj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2limbpipx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtotodg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcjiwgh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtjpmrz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiqejda.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjukyfa.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2okjtskez.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwxlnyu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zosurdsp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ysduzinn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgdcclb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxocjgfu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fcolbvay.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnipvkb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2emkidahw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsagdwyu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqgrabw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdlkkzz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhtpshp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzlzgvp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vovuyooe.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2prgfhnqb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ngovgett.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkmkzrz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqerlsd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyyicmj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxdflqs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gttaurbl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzgaxhc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcwouko.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sinruvco.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrayzut.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bszxwief.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxwymmc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnvylop.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jtudmcbz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhmvcju.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkzklgo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ielkpkhh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpimskbb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iymoillg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jslbaosb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvqjyck.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtbzftx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdgjiug.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dspiheii.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jwobwxku.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2khkxljwh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kurvxptl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqpxlel.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lemyyczg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdphysj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqmayiw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdrwabc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfwrffd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfteikx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwccsco.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqbpdmg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wllodoxx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upmkuiqd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2keohqxvq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2odsblxpt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbczfhnn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nblcverq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iibjyfao.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2szdmlbrh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjixaxt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iigpytfn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zszspclo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjlyfgx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vketswdd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gekstvfo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnusuhq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vglcekwk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2chbmblsh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhapefn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuhmdpn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bznygrsb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxehpbzi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdjvned.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2exwehoaq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzhxvvz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gdljldio.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hetgazzq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeddoan.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wmckecye.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbhvdqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tndorpdo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmmohhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgcbeso.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqpuzup.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuvcmhr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2egepxkor.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bpabzyvx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbrbevh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhafdhr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2btpbfaun.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqsjwya.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcfplga.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrmifte.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2alvjikma.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsftntg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyeyfjx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxyzrkm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgwlxhq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pezzclhs.html


<!-- 参考信息 -->