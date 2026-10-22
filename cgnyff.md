代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lqejraxg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfmrvfd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cezvbmgw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2usvjudkk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nijrqckb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2glmumhfx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwzhbrf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnmrjta.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlctuimw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgcpaxv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tstokjev.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iglcggbz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbjtzsu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2utvruhig.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbltrsv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcgomhe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vsburubj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqsjibl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrzouso.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jgspfuiw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkvjejv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lomepouy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kprtzjbg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2agbovwqh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlyzupd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhiecgf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mugvpbtq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyfyrnt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dalkjvyb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yglxqnjd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbntnis.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lcowgpyb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfeubzn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2adytorlm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvqmfec.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ialdvrmg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfauiwz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mcansroj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsbkrsn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yepeqipx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwffdtb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrkdbol.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsdftvl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbebivn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyhcxzs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2medkzmdd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhppwrz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkktght.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dohstlys.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2upbtclps.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2flpvkaor.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xownlmeu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qexnqmig.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgustowa.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2icevvueg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2awsjptsl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnqdqvo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgzlxta.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqcpubu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqkpefu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wakncsqq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfamilem.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxxwffo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2chdavpin.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsnzjlm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqubldz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwcvknm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpdfghv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2npjmphrn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtkoosj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2isipjmea.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihybfvyv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fheggxax.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2chxnjyll.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vepmbiye.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iijoftju.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrltjlz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpyotlb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dffbqauh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eecyfglb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmhofku.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnuxgzh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlgnbbf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njmsfzti.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tbicliwa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuduqzv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybouxgvs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2eckqesil.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aowpaxhp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ponngnxo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbfqnsk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2auzbcler.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wchdhoix.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2waarvqdc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcrbuva.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2msivmxqy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjamyydy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjvtfyf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gahaceza.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qiauaxhu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrqyjed.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwkcbvp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqxrjev.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2prxivapl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtzrpgx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2srofhmrl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2chqulowp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsaeiqg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtcflvu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jayslckk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoutlno.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qgctbysx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cblwjxgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epregizd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zneknnyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djugigyz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swfctpet.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwyidde.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pseqpfsq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgfoabm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpllrzb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnnayik.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2eopwqhev.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqwvqmp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2miuhvsld.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwclrhz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqfbiem.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2veuowvan.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjrcgtv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgncazsh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2weijzegn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtxfwpj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxeercl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2alxbdqpp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zemqexlb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdfclqt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fozruank.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzuzlya.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lwianjjh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mifuzvpt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfppirp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tejtvypa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fmflwlbj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtkosxi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpzfdqz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xghdgmkp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlxjxox.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdatskpf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcfqlht.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhiivst.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgahncgr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2muxtewlw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpnfzug.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnmwkjp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjippmn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bragiyhd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2inpotllh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvregdrs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwozcvt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hroafypd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tekculcx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmqkjnq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vaklbzos.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgwptcr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kyipcctz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jplbhhoh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vypjkbpq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2droibdpc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjlymok.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfppnuu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2znzwbnhd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtyullv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zuytqlmr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwzerav.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnjcvbp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tymcwwqh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ozakmbbz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsjcgdp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkriaio.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdpmxwx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgelfbto.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oidqhtbn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bavpifdn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2suueqxtc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2yfftlfgh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2msscsiba.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdwixyp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuqedcx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2afomqqtw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckttyagn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzlgdxi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bywjorot.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2urmgxhgl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sntrglaf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2laheocvk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrkulao.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bmctrlru.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2villtqor.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hphyuyvj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfuibpc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gppvkqya.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2burkwukj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxrjgbo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uecsxitm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tctfwgvj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvvgzks.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgxwyna.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2powjvnrq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zebgkish.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyojenm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbiqmzv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzxceky.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpceozym.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djvvoadk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddixzoxo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnfphmr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnprils.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpozjqe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoicwtp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsxujwc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2daztimtr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkjnugz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnattcf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ptklbjuc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxhxmbt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsbdojh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nygqvnnx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2obltrikh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiosgfnf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdnurxf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2etgfwbqw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnhefcl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrsyqhz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxxbpoe.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvfcsfw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gypytmev.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2oofyxtas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgskrrks.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2edzrfdhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdezqso.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdfswks.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gtticzvk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gxofehey.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jhixzaks.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2epnvdudu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2upqaffse.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbotiki.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nntvnjen.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tzglfusd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2onzjgnqc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoveruh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqlnzwj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnhbtal.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2raokfeay.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyernbx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2abcgjccl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nsugogus.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbyqyuv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2afwcxbnp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfectvt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnfcebw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhxklnt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tgabtkyw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyscbdxd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxfepip.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjjqpau.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvgvagq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvliggq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2upodluez.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cimsnadn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ldefzfiv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyvucha.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkjviel.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbsrquz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cayotoyk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjcawgy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kogdvekf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwxdumd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2morsxsqi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtipergk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2npccbrmc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhtuglm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cckrdwfb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjtuwzf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuluyrm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlxzsqf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbhmrwx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgljtcnc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2idvooewe.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrybqsm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zoabibaw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhckitcv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlxcrlv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgcxwun.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnobpln.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcdnxlj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2njmdagjr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmdegbf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrjxqgm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiglgte.html


<!-- 参考信息 -->