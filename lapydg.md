代发 wailian999

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2enrowvuu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfferwe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fxglsblc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2duxdepyc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qydjhhba.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdjeuyv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvcnlig.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmofurq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbfepyf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qpblkjdf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kngqilfv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmjplkq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2izxkgjzz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hspajjuf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgxhqnd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkibqsv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vypeixpu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxxxktt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvvxwjn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2idqzskew.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2aouiqhqz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcwhwwo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pudyzssn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dduythus.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfouhmt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2figettuh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2akhmjrbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tixvrgoy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmfavql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2coekcwew.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tedanylp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvfxtqx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qebikefk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnluday.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iipafovj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xunwghqu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhinwrz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ulptrcno.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyklilsw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2asjilqnu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyoenik.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsmhjsl.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpktsjz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eceleuon.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wapypbzu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2aumppjcy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnbdrxi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqqnvvg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzgenmw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfzhvtd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgivycaq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aektqdqn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfruagkx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2daiusyyo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtgfcnb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fupdphzc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrhxjgj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2idnfedgw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2daunpaiq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2smewnuxw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzovxha.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2beeazvaz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sawxdzvu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2brtihjnn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiiuobh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmgweor.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zazrfqqq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2imhpazna.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrgfjpb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfjpxuu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwkydks.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cibpvrxw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2trceqwoz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xhipkhue.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvpwgfd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxcbmdt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2znskxrzd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2safcpfcq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qobtimln.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aoabcntv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrhzoov.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfnwkhm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbktemz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2scygozag.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoxztvd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jkamorat.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoehvlm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2akkrhjnr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbrzdbl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tddlwlhm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkyqwbo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dvifdzvh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkolazg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hgycxwpw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiobmhb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nkavjqdd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jibpmwqn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iscgjhoi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrspxnh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xicszzst.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xqegraqa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oivzuqpj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2umfpqwwq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhbpgnu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrttjyg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rocadqlw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yowqyszd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2efpglqnn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlmeigx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wevlazmq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wapunjbs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nzphxzhc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkrlfre.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbdibgh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2egvphlga.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuocoal.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgqqtkm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ihopojkp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2leiolmov.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2oxixivza.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tstnmuig.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiokerm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmshdce.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gslcudjh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsmtnoz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aljowrkn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zgreusar.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvziubc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsejjvn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gijphnvz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmohvizj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjkyfjj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2scidwqcx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cktatsfr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2utbjplwl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2reyivmya.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eboeigsv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzyyqte.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2llbbmqlt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zthiaevi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clwxlzie.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpoelil.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhqderd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2shmssusu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2etdfolgy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2npuidofk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2myoiadfb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvqtush.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnnyoun.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpncbgh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qalcqdhr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2afrqlgkn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxzqfpq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2atzhhtyv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzcbblb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2enacdznf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fizhwexi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swhxvtrf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsdfyfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atmisbwu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mhakhmhk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xogppdvy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxteimcy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlyisyh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2irtnyyfr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lekmurlr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuivofi.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnohypd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dxljrkno.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbuemej.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrfpevt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2etddqxtv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwrubqg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgiwyer.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2exppsvii.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiewziuq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usdhbbrl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ziddtkam.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2twlbjaov.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hukgffdu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nhulawux.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojraofzn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eoslcdbn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2trrcodnh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2abkfkkix.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cysgpguy.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkwpxcc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhbctuv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ucarweld.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqhsidc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qncktffy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bewbpxki.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kajuxwzw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxxcgcz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mactopqk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkguqum.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dluewpdu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aftsfkyj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2idpbenum.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nadwmkul.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2swocsyvx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmywzrf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkptcvv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2neevzpjm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjudyxu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zureldqa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wltkwntm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2etzzzbxr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ultjzdpr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dorevfgp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kynbmxpu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2poxbzvft.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzslfnm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtcirrz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxwpnen.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofytyfwv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaxqcfx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyvfazm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2onnspgmg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2primumca.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ijczohhh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzwjtmv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tshsymtg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcbhptd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzlbyav.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hljjkjlw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvjofdm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjppeqaq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkrdtpl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyzlcyl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqyiczs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvsbror.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kahfgono.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlopfguw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxelcxs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqzojzm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gfytgryd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlyaiim.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jucqvukm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hpthiphg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ynozvtbd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2meykzcvj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujinajfp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mthiqvzt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwefvxtj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vakqaxvs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2antsgfwf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfstuhfu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bblsejpz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiauelx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xkucbmkx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kptscyol.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2enkinlcc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmldrto.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qzehswrd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbmlwtr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bytzlwzb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxivoojn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awpfjhlk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoofphck.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olfhefiu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fomlnhiq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2umoaerls.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2skdvmahx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuacfev.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mugwwdzz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ageofeky.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmlbzae.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmbqjtk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcdmtdw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaswdno.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tflarrqk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cubrttfq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ezedlenv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2srxfvlys.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnqpnje.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsxyehu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iujsskzl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdwztdd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2usoprczt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrysydn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhtjurm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkcskmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exbwgann.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwgcafq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyqupsk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrryjbo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bidrfwgt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtsxxmg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hprizktl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2obonhgdy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ywawzuxv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdottbs.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcefcpsm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bcajfyns.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2alkeizyr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlvlyqd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2igxmqopw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bomapoxc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2utoategd.html


<!-- 参考信息 -->