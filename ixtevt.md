代发 wailian999

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2snozuvlm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcjoqns.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qepridqh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnzlybj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gvluwfps.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwvsbxn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2oobxexdk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rorusyzy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2adtjyrwz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpayhrz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2edlgtaoo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdyoldl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dffcyjaw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vcejoaio.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaimmym.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhzdouz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2usylrkpa.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgxfyzx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjhdahh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrmsvwc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkingdy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fcchqpmh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgmloux.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhpuoxr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbujixg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ekymaach.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2alccwzxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgefbrcr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwwyxdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fooacnat.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2toyhnayk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlbrdzv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ersaxvgu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gauigoak.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zchlutpa.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmdxaoe.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovraosqp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ggysmwac.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2frpjzkrj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnwpnjb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwavrgvu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sahcxzxm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmssytz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfiyifo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyupusc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvwqmow.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdmjtve.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoobypv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2svjrkcuu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuowpyk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjchaoj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dceadbck.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoxbaxi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbtilcs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2quwjexlc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mihumejg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqazwslq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2atjbuknn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uucjhggo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2izesvkil.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgzlxkh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2szbrchra.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtyievz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2syursfnm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqppyvu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeuvoda.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2amwumpls.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjevmgex.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xieqqpwz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2opemgegs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbinyab.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nqptjtxs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxhoext.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2abuqlqin.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zonhuejl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uuglivki.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcrnosd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlqtmkx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlseoqm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xznczhzm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bscexkng.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ibweyojh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzoadbt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqznfhr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtssqol.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pufrkscd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlkmimd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmtkymj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfnpiem.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpkzhal.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzouhqhf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2oruucroc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qhesqehe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvgvpwk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oqowtpxw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgxvwie.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfwklcv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsptcah.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xemqsejt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfkscff.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzaazgv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioozjhkz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzbbuok.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kowjqcam.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2sivcbwxv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2knntelmg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nzymjqoj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgghluza.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyhqngi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqjkhaf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2adcwtgiz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqvlxqd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hztyinoq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xidrjudi.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxhffel.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uclzzyma.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdvbsno.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mlomzupz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmrhkke.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbqyltz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoufdbz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gauycmsh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2awcvmfsa.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoulxorl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2acslpvrq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnnozmq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnmnmwa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjiwplg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqmaqkp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etooraoj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmqtaor.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2efvqhcxl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zshgqnob.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnvbafg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ucstwgig.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhpvxiv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlecsdm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2krswtycr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuwprza.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gmurqcwm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkxstmp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gqipxbwf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2phrwrpdq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wedantbb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqqxvqa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhmppqt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaqwnfq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrqwhal.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjadreq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqumjmpr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkagjpa.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qofazjlq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tadnuqme.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuvvfbt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cycjjnny.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcuvlux.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oegssyrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znsiasob.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvjyjkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvusiem.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqgefyy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2foekoavu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpmcfyl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mwajwxuj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pybestjk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzskjfcp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvafkch.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2awrfofgr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoxdmqk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2peyjlqxk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qalxfgqs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2klfbphoo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtffljj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wstrzjlh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjcgkhm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqdkyhr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgtveqo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlilntef.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfempocm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxuckwp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kneousis.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2enxbqftu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjzinrp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2imlucocq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzsytqd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbddtnt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkmdrew.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrmtcbo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vziqkvqe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvwbwsl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcwtuyt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnofonj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2foeiagjf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qiifibcz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjetpoo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnohazqr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bapwpija.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrtqvib.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jidsynqm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkayxayq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2grabzsdt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrpiumq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2thubtkuz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2elslrphx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zetzsduw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjoxwgr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qczlwvrt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2niahmffw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uckokfnw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpwltzs.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkcdrtm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwctioj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uvypiwuf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbsqixk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjaczap.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcidjcrk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2grhsorfc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyrcxij.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrtpkgq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxsrjsn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xslssobc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlybrbtd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvqoshf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jctsgavf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dboqtodt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2arwzwyfq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pobjbwqa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gsthpolv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsojlcp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbrpbaw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgqnycr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiorruc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqwxeeb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2evnosfsk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtojsyz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgrqneu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ymagsoyc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxavdmr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkfgeav.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2utbomres.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vacrvolz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vubslswt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzhtsxk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tffcjiyl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fevbpwde.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtfwuwe.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hawhhgck.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcdpeqr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2quuzgmwr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfnnxwb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eobxqtej.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emutdjna.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwstghd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmnbnmw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2womuscsx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctclthjx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmagvhya.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxegqqyw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kraajpvh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsidrej.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcrdoya.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzpgvjm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2taboyggt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqslhri.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ronilemj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuklfug.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dicwwzvl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaccxax.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsrnbqt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2skynsoev.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjvyuzt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2viqnluym.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydezlvme.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uckgjlit.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvynsbaf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aqppisgv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kkisckqq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ffglowsa.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiniczn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqdhvyv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2towoppng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxvgido.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2utkfkpmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iajdvnvy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ylklalrk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqbsvko.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2brjviyyj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvijpkg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcbbmjb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjojttlh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmhjsqd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlsvyrj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbsdyjd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwigyzu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2amyhihnm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2aclgaser.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmncbrh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cemghjuj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gssgcyix.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rfckstxu.html


<!-- 参考信息 -->