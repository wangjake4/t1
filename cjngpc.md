代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ansdqjui.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vanhikvj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwujgijv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2okgwwmmt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxloomay.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2urrgxujo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqtlfoo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbxuqun.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2spcyqhmc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaitogb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqyaudg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hayaatww.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wapukfmd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdtxbjw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uasqijxp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpssanx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwiumip.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmdwrnv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzbphnm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evloeijq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtomotjr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2houxqmuc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xiffpzzq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2keftvwix.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mirwqipf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wivpptlm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2acorjfen.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hxubcnxs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcaadhl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvzkonh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaxcaxl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2elbkagbz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnliblj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiqamij.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyzceve.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyrhnqm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsnaywu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwidaxo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiubgqm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwhywya.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbucbgz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2eafeqdud.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlgyswr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2umrtwevm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqroumrj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lyexqlvn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxvxbuw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2souviyns.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwadvuw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqpaxrp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjprdrk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zaechxmm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oukfuwnn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyrfgcb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xujxoayy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2acnlowel.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2osfmrvhq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mhliktlk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgpubmm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlzxjau.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sccvhhrm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgurhab.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcwmvsh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2noerbqgh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2plyfvcgd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wksjzwzu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bkosesaz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbchphqs.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mawylfcn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbyswpj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ademxgxk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ollnsyto.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhyshoz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2czlfknnc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2isivbbeu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdcviut.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2glrlhztr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2puxyomne.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkoveht.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfsgsuv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2andmjatx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdjopou.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqdkfii.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tduaqjlp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2aejrpvan.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzeayif.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjupgzv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhnzpbo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwxmqdt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcifdby.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjktvyl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdfchyr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoxawdt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynijhohx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnfpwmp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mebhkrbq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiyqtbo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qobduslo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxzpbqs.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2heubevtm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoxicnq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yafurwoc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yceplblk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjqvdqk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xedtjhuf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxmqotn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkllzrv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eencqhpj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxhmmgz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2skrfzfjg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipafcurq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdwakrg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxswckz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2glfmgmlq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2udtgdtwd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxzvnit.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqxrsab.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cumjzuka.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jobmjhqw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xielpaik.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvgntes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tytjbrql.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyarrta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrboyab.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtgqrcf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvyszqa.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vujxrbls.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpwbwnn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tpevwslj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2drkdbyaq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xxznzbov.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bukvqoas.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wabfsdrg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjbsnwv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwpkstb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqhijls.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfvsmii.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dijkxhlo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrmiitn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpihgzjy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhkeovc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2axqblkdf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2omfktyyq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngouyyua.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2icbsaetg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2aniqfzzd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yeomcuyl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxligaei.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ycscjmnc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qonnmvjg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mciwnicz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zepxwmyh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhtqdsp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zywaxqdl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpcgvll.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwleyqw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nofbjwdv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuugcac.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyqsbrn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2eejsgxpj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxdamwk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fofatxzn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmgbqaq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoatzli.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mezxpbpd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2efarmwoi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2outslcoh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qemxiumm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oycsflxh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxwxedz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgxfcvc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfctevso.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2amavoese.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqtjaby.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2adxhawxr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjecguf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzyafas.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqyfbbv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiwyryj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwzqayr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2asdfooqu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxiiuet.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zairrdev.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2juixkadn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hsubajhp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjhlnbm.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgycdpsj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcsuisj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2svzpgbns.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2omrxkaal.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbbrwzi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlymxvz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2boxbxgfg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aikgmmxt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxrmjkq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jydpyzjy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dabzfcfv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpsfbuo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgncpwrl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmhdhzk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmxqndu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdzguyw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2eowceusu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmlkdeg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfuvsoq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwabobgr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrvkkag.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaoqhsr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdudhrq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaohunk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aselnfld.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwjjdik.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2newshzpj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exchqqpt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyvpach.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xamxryem.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxjvwwv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhrcajv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2acdskhcy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2smpnmppu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihagrwqd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioupknvu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnvoqun.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrgxxxn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trvvuihf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lzumcgvh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsobwsdd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nykfclot.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjwjcyl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzeslba.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2epvjbkwo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2etkbdslp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpanxxzk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bawxlooe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vueaequt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmqnrzt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtjtfis.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzjpdwz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sakcornn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjbosur.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrhhnru.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cxayzstm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkvumpi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbdabou.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzprgfcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipctvfvq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2idemhpjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnoxqfs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwovpmw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jlalxthp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdwhsqm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2votyured.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iidbelcm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwypenl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxtbesr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iczzuphf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vawkelal.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrezqwi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2atoapjfr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2khucwjiu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcdqyfh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iydxmoxx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjcplxr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2blimvnod.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2djftrvse.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbblkidf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qncepbri.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nspnzyxl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrfpwbu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdgzper.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkkfaml.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoipmyi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xufcehfu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvurwtls.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2atplndgc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hevnkkak.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyrlxke.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuykzny.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2aejvkijq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcqqjnd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dptvidtq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpitoct.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfkyudv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpxirmc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxnishi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoqqsek.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfigost.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2trqiipox.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pyavlciu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxbsmju.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jtalpnke.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2sffqoign.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrqsrfa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vacffflv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dzntihab.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yydesyxo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2eswvmggv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcotlzp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wfldezat.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrhnrrv.html


<!-- 参考信息 -->