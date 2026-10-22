代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bsidsgjh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fflkhmbx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2slktozsz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkqejxf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqgqxqq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nidctoye.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmwdyml.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2czpryvbq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbvjnih.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2myfwijzw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfugnmv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aukwcoiq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaojoen.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgewswd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmmemwl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuubolj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtchrrm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2oujpxyff.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrevppt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmwuiwr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwkojiq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njqnnvpn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbvdveo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfqhnfm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhomxrk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qzprecij.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2szseywul.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qepyrzqs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uldkxkfw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rhewuxeh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ryujposa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrdjmib.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtcknyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhqsxwj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eiebiflf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqhszya.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcvucbq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjuhsbj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iryhoqyv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlxgtwb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2laewvpic.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoofsrd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrzmzrb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsqdyae.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbdmdqq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2edgmkppw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsritoh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpbsqzu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yacyhriy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlholrx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlqnran.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2khqaxtsw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuvdfbl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxbolxb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucutgqeh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmttaiho.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnmglci.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2asqbxljv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjufdvr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uozjscuj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjyihwd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2agctuetz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvylhla.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2guvkqmsd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lolieznb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlxhvhu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sojuempv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgujodj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnymggrf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2henedoga.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xprxthdv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfnyorz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sadmfojx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbckdwh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjwakhy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2urgrgibb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlouystw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vehridpp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yobcedhw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzrucbk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mckipdsh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiexsxh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvlickf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rphxlult.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fczcongz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhznmzr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgtkkgd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqascaq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gskyeseb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvyksim.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tckbhvsz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxphdal.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xczvxwrl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkmchoj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpvrdut.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpgrhsm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfvukak.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxajsdg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hobhyowx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcrqwdb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xubghkfq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjvugmr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcllmzc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdguhaeh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbstnns.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2inldhfio.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2snhtmsyu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyagymcb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvyeuxf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxfhejy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbrljxd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzsvmpj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cffrlwab.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmdfwnl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgguyfd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaystex.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zrimlvmf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxiyndk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gywuvpig.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuegrmgf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxexmixs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2agvcdwwp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eepkbwrb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wrakjulu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhvpihs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2angexock.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtdvnmc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szpydcpg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrbezjk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gaprwzgs.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfkksfr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeruakfo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkgsntp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uutbhqqw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkdfogu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lytwvhhw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpqhiqv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vykxnkpw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjirlfo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iebzoofu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fleppuvg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqdzvte.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wbizjjrf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtqveff.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gccpqsaw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iiddpvxg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhvmbjl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cehwusiv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2apiorgmg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcdsvgf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnubyhs.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jobdplbd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzatwqka.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgrroym.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tosyzruw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuupbnw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoymabs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bymgohjy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtfdycv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmfiudd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kycsxapv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmiwpvg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhwqapr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fopjgyvz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2puqunpps.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfglykfl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2svkmgiyn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoqsrol.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqbzfzq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2amhtatwn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2liohtjiz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnzakte.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vmalqodg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtaeiuk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fydsragn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpzxmxn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhumoui.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sulufkzg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2efnpvlas.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohexyaes.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjyzmka.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfskgtwp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2divekgon.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iymxtyor.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uavckbwn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2awswjeve.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tordipbv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2arjlziag.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbasfhs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuexwqr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtbjeqy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2peqovekn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdfeytc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxieqcws.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdeblck.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjunqxo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2marjhewe.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvnncng.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mpordhdq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxubvfix.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2atqelwfz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvjqyru.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbwzbny.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqkkisj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfnayuy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmiksdf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyzxqfx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpixauu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhlgayk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mltumsha.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqdmlpx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqonhcw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2przzlaod.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeygnrtn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwngmsr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2thyjzhpt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfqygus.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2avhutuqa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyakdky.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkxssur.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoekqhp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2npnitvxc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2icjostbn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvcyuoj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfnplqw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vswukzcz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2maaewkjv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuduxmc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pisxwcra.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2npjgvvqj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hxapomba.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yayxhdbk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bemjxqgc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbpgagc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kozrtycf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaovfqa.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdhjqik.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hewqcfej.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrktwbz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2amrhlkai.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcmpmmz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwqtbrw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsbjpme.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2emofuhfq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzwbppg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yybszwew.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpdlkuj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiphdcn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqmgikb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxtipgp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2azcwxowd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgozghkl.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxyxqjy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsvctro.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bjajxepc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmbirnd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kwemsnra.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrxzlfz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dbomodzd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vksachfs.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pieqpyia.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svijoifc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drcnlfth.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuwlylj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyvgjuh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hxikxwwq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbchxvto.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnarfbs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnggmxk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcubbiv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqdmnon.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlgzcxd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoualtg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqwskmf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyorozs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmieail.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2beocvzct.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wmofawog.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmncqllb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzugifx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdwvtxi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvrvbyt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzruyuuw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jjijtzkx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhahxake.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnecbnap.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2slbyeuoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbsfopu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zulhrndj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2imvsegsz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcbtdgm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oizqhicy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ftizuwwj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zckxkmqy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyffuws.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ejylhykc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kcecuiay.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hafneves.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wiweriqe.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tifpydxq.html


<!-- 参考信息 -->