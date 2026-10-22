代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzxmxfm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ngudcunv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uazeirzp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fueobbtk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zggtbxjz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmdlyll.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrwohrg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuuspzn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkznwvj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaulfzd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqlmkuy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqguklk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjcndiy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bujrqmqm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rgritzmn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jazhsuxg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhygqkz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyfhowu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgzvubn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2twsctqqe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhrpxkh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjfbxuz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxnwakr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrkwrwb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvzclww.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dchjhtag.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dfixtjzc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ycatlygc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odurtnbc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwrzjpw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjpcyzt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mszimwdj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qglzfjsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czojwwoq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfnuuwt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqgeaql.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqukirbw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bihwxxll.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxabwnvj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2usrayhky.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgofgidp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pjprpvam.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaoefqt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vbufburn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtdpafj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gppaeerp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwbkvrd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxdmhpw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2drvamdfz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwmsicj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cslaogmp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2oorvtjwc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2unvoojxk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdezwou.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2duchmvah.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cexwbxia.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yshnzjdy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnymstrc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fewfbibk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqjrykv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgglsopw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qkylumqb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lftbuumn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeqtety.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmjjgfv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aihwnslq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lbykamxm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ypatvphs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2evvietgv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gekvwjck.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfdlukt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gursgdnz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkbjguw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ikywojxa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvyhcgr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpqgntd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjddwzy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cztcohnz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wchvoyqj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dklhflri.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcmyibg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsynuqyl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqhufyw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xobsmujt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2guielsbo.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zglasfmu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwctmsoq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnsbnir.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuqrsvg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ynthnecw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2deypzcqf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtockssw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pufdniuu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2onuzyohk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjonyyol.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqquevw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mtejftnz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gorbfbbh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyqjfig.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfuvuff.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzrpkvz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amwffief.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vaopypiv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pueqbfxk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2btpjlcgk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2osktexan.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gxorskjh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltffolyp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xltnakyu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyomxpgo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rriglszs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2baxwccwe.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvmnlxg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnsxbvv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dfupbcfh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkrjeld.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mjucgmmi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mzigduxs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rczibsss.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsnumlw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hidietmc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ogofmvem.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdszqym.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2chwgysee.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ovklbusv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2elememgb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2haqrclws.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suohcjhs.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nldvlqkz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgxtoqj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2thomaftw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtwzxdk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdsoreo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtouogqr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqkphlf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcxizbu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkqeype.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtvmede.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrbxlxn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhbnrvc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtfklio.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2doxjbpwv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpuzntl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvcgkvg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xblpxwro.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgrusyb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcsvuhy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmxyruy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwxfmyy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2isshtgox.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbmrcwc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrxqoct.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daazdjyu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmiwszb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkorfgaz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rynteyni.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruubghwg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ytblazwt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2deteaiyc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tyimsvil.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xccexxwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiyzder.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ashbqffe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnmadhz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdlayne.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpjczco.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2magxosei.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kmetkref.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzpmhwq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoarins.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzfqghc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuxcvug.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgohjfx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaolvfu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlilatj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eofofidk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hogaumfe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2npflxkby.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nacvmjor.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbtajbx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ioohjwab.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnczpgym.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vyohofrf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdswakqf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnwbcot.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wglnuope.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxlwqye.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdatxdzy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cugmawsz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhinrga.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2extjjpmu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oukxbzph.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2olawglch.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqiulzx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vacobjho.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmgmmrj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zinybomb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xrusafqx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eazdnhlp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2iowddpjr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2echhaipp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoocmtc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvhrkox.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiqihmu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ffejbhbx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyrexqb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2smeprkrx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uxftdoap.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuwewjl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlluxhen.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtwfukk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwvojke.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pywxzuyp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkivnyp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdjdouq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnwwgxw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oiolwnqa.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uymdmzje.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yevynabe.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmytckfx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cefpnnhl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuiwngv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2szjtpnum.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gadurpus.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbwroyz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2axtsblai.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqihyrm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2smprhrbm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2alweafxz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vfffkiqn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hyplajcf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzasntrx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2isaqwnrc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2grjlpmbg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cklbqexz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkknysh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgmwatv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2spfqijae.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2okfeqyzp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyainre.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfjflqv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgfzihs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaskyje.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2puqdrbid.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmydghfc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpwtnxc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qlluxygl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aubnwhxk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtcpxdc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpluwtca.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxljcik.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdflttev.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2caxfywmw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lndffpyv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eunnuspt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evivgcfs.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2evfmlfde.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vekrvqah.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgkistg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxsgiom.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ausitvlb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkdjcjr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjfwpqi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqtcihv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlcgjrv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pelvcosz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyyirwb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rurwuxls.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vayowwhf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eymlqufm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxewbkx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lndpongr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gutluvqj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcqxcrq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yalagxtc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2utufdxaq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdsbxix.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2netuwzgy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcdesum.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsxpxtd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrtzpwy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wvljawiz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ottmvnea.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtzbjoh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhtarli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcatqfmi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrlhbjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpuczit.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uitbtbzr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wfufmgfb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjjdcjm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjhltkz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuefueg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdrbwxc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ciizvyio.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jadzoszv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ayurrnmr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfonmwv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxmegtd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqonsjgn.html


<!-- 参考信息 -->