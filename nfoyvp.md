代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgnzfap.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfwypdf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2drxzffqp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuwgbeu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjcgnqs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nidzsypu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blchivyx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzerqwh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxdrahv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yxttzavs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfffudt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzzvbjk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2psbnztmo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hugqzsnu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnfhyax.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuioxuk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfvxvrn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2udhrdggq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2psgnqoju.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjkdcmq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmknvwjs.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rupmbjgr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fchfrhvc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wchzkgnf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ejulyacx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wasoaqyl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zalclcgl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hkstbmex.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rotzbewe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vejmhwdn.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2euggtwwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqibcsq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rliounyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jieuchlm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2koofpiac.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2intjduhd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmszfyju.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtqwjoa.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiahzsr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyazpypm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vazunaig.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zrudlzzz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rymlltqg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgglzhr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvhbpbu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfcapnf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmnwanl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aldbsxjf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hslcfzxh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxibujy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuamvuvk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qpheebmh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2aoryjexx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mcffally.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwmmjnm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdlmrud.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgepodmg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2otesjhzs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmldpqe.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isyfwvim.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkqytit.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cskqhgie.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2blmrzppm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ozimbjis.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2trwvimrt.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvbbwdm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2euwkkbkb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwspzjs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pplyqkhq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vxscgufz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsefpsdb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2guhirhrx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tggdijma.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwyvmhi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpfejpj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2swyynjsc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqwnbms.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ytffybay.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcyikdw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mefxpmst.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pifyofgl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrfeslk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2koyknnpw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrinipk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qniiinof.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2orwuusls.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnudijgb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2soailuaz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lubwvrri.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbykbqli.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfnvwfi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnjulgz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzusrgm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfeyaxp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vskiozvt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vokoavsd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2efbmzlee.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lerpxjgv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ovddidyi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoruwlx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuwoumb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omgvkaxm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iaraykaz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzkvjid.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wcujmxax.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2chkyqrdf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uawbybka.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yigqgapa.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjayqqc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpfpmdh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbkpvvc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxeoxyw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmqlckq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vacaivxb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbjdmds.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zleqlmou.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xircgril.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdrbdux.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gifvumug.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzavoueo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpdlicp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbtoryf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ringkvgk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xajsdzdm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpvtntz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbpuftd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbeeszv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtscydeg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2grnhpqtj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqjkczs.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaympgy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkspnxpu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbqhboz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfduvjff.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phqhjxxi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sozhnith.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwalffb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxnzvqy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2paphhcis.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aoawtbrd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxjmkif.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzezjlf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnfnmmf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nljlwpyt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aknkqsnx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiphwtp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwcjwve.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rnucuyzl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrppdws.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eygomvyl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2doblwqst.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hprpnmyu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkmuetj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwelmkt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmceeuu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqdmwfs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjnnipg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mimwwmof.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuecbus.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kirubief.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sjugymmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbwpyyh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fljwbdfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxzrzxf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnywldf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaadnchj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yikkozdx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uacgarsp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrbhjou.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjowtyzd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjnbhio.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2blpmsnbj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jdthujfp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2shihrcrj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhmjxkh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzurnjl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbijiel.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wphjgksi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaivvli.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpqrjzc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kejycrsr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlqfkmg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bepzobba.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwwnusp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2umsiyksw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrennhgz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2awmhxfjd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2diukhipl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjqmhbw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwnhawt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrcpirx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2spentrgg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvazqce.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuszsci.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2psxstuem.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybatieuv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2weacaors.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjpbgfc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hujhcdwg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmqxumm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgmeehi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkiemzan.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yagsrfgb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nujqodzj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdrzikn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfovnxra.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iahsfoep.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ismsmesv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdmcuws.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcqmxum.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvvrmgr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmffzwy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxvozao.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmpprmf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2plyeigcf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yopgtoiq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yednelft.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyvopeu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gloaymny.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2apcitkmd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xailtpsy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbahfab.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sxleamxo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdijudow.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcjjjkq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtvacdg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eskuvenr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdbnmuv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ishxvknd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyyrrtv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2luxzhsid.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmoqluc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sudaxznq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqawlxr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzoiwpc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2honebkjv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vykgxvxh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rykaetxt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzcahxv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cvohturw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kekxyzje.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmczxnwg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbhbxap.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzbbczq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etnimftx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ioszwind.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2obhnqqzp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2btmynelr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vigtpjsm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsllqctz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2envhyiho.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjwuogu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2luvshxig.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdivyfvz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eozclpbd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbopbpeg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqylnba.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaovyjyu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmlpssy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2louczadc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bymkgbpi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyslexzk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkfcfxb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkelyxj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnbhvbp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbixtgh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaoqasa.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcenbmp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdtmumx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvjvgpc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmllvhp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnzwqsj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2abfnsqct.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwdvzsa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxvxyzn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vzalhpoh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2apbxoblg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2crliupso.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrawcnp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aijlybbm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qodmljig.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yldtypnb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dklxewbt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ueelthkh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hivubtmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkyjgyo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hofswdgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2neexfmvn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jmflgcad.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyjeogi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2osdqadnn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cetmapzd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtikwdg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdakmday.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2faxkmuza.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xtumoldv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dfolmdgo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mikjklwn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ozksfjmv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdujyeeo.html


<!-- 参考信息 -->