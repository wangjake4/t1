代发 wailian999

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkuqpnj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjtggjq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2penaynrs.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsnectd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2apylagfo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gsycbhge.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmisetz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvkowfa.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbnqpim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oylyybtb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjwxpiv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hykwfeop.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgskrqnb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gpicagsp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnjpsus.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oknrqnhm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqvniqf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xglmfrww.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbygtbx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2worfqkox.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcojkrcv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbjotzp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dosscenh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxzrdzk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdyzzaz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tuokepoi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2navrlxib.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2krhnubmr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rukqmhjw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nhypzbdv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjponlyj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyevvzlo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhfhfjl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2upyuujvl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jshuzfac.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2biwdkdii.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqhljme.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhkqvxt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdhsfla.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeseqys.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2byrsfszx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbwhxon.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuxmdqp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmsedup.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiowgtra.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqotgoi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ponovgji.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vywmnbgq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2exipeime.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nzglsgwi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpplqoap.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lyatzvdh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjqhdbm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqltnyk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uusraesa.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ysifkngw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyajdns.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2oocvatud.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iymskqyk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2agdczgwu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkviofvb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zpozvfjz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tavmvwbm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lzioengy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zalhwjeq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2flxhskpn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2opcxjdoa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmejqxk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnapqbas.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkdsnhj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyprdmsd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwijbgy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gacgvtgq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmyebbv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zexfwnzj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhjapzy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcxgprn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbidigy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdhirel.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eukwpnhs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2opdyphmf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2abvzngca.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2txweayyb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhmlfky.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wawyipbn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpguhwm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2oymspuox.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzntnjzp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ouswtjmq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwykiib.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfzewrl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hixbycln.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzokouc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlbymzz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmtxazl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2norhjrnc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcwumsz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnctfxr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvjfalm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mwewdbmg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgyktnq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fziatemn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dyceyvis.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcblssx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2buuocixb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnepwrjd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjqtfnx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwycbbm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kekduqxn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfdsbcs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsswwfc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcsnzgw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2epvrxabm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsechjsi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dswvclpw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtupjmj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsfkghn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2panilcpx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmsrfgq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2szidioyz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okqvtiri.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xjggozwc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjdmuhq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2scwsauom.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2genzaode.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bncehtpk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tejabknq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmpbiut.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gspdxrjo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vecchagh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqxjipn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2krdxpkhe.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnsuvir.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbykfbl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxfzqua.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnxvddt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uxztsjru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsglnpo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwciczj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgpllpt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zthcqext.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkdwoki.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evxgfaps.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxcpblj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hphfytnt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2widhuqtv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsnlkyb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xteghwhr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rneqhrfb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzqkndk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ikskkduz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyinfux.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jklftquu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2axuvrcka.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dahxypmr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivapbunb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bysyngyx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2khjccoov.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iekgggzl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiojgsc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ophktytw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vavicnpl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nduichls.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rioqzceb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrvjafz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2onxlypeu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjfkasb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmyusou.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpavtfo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvuvqfn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdjvnro.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxjixqh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzgamwu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hnawkdef.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtkmlar.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpafxig.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2paudqwrg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtqrncb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmnlmwf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrtasoi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jkydopwb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lexqopzg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mvanwpnf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qufcjsci.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpayrqx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zprfxeri.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmjpddk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeghonlg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jytpiias.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwlakyo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2loklgkcd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fitwqmfk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2csbdpwuy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbmfsse.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rphpkzkk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hswbysig.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcwfcrp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkcmzpi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrhwtpf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aasmrhhe.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyvakdi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iudbwudc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pltkbjle.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2drltqgvh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hidlygyl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2betuuqkb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiqegiw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xyumnoqx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbbhhxh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtbvcqp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gncitwmi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mclidenf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgaqukz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhybhemd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfdhwpa.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwfvhgh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jgirrgrj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xikjzjld.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtwtcor.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wytcrzgr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tcibebbz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyynhqi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxfeudl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysthmqzy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkpgolf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwocgow.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxixjka.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioidcghk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2flsctpjc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xldmwkxr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fngnrbsk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdosdnif.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuvoagl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riwvyrhh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnnazkq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkfeiii.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuosvbn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmbgbec.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhorocdw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2iujdrjtn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpvtplp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2exprslwe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvrqgds.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yknbjhzp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdzwlxj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrlpung.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsqprhq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcbmhmr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwcpgju.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvophls.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyluynsv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mnntwyfp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgpokmq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jimfnzno.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2acmxsvbs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiqtvao.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlhjkcs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfyovvx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgavzwut.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxddytr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mebltpjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qshycclm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zetmzeva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjdnagq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2onnnuzfl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2biojrepg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfyovee.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzobgnn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nxinodog.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2blqsfabr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mfefjmux.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnuxbgh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxyvebf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tegfkmwf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzstdeu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2muqxqksh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2iytlajfv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjicbxfi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2facvagwy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtroptr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyntxjt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfqfbyz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ciszunrg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2puyztikp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjzemnu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncydvdap.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqxqdqw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmftojyr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxbexqt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmcpfts.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwhfrna.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2spholowf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzfwdtu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2eorvgqrd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxdanif.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dozvoaon.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxuufya.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnzhbjj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhbfqmx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfisrjme.html


<!-- 参考信息 -->