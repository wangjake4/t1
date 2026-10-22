代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjchvya.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vselcpxp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2asfrxybw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxbhjnq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2eadipouj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ovctebcl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2adkjgiqv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvzdumw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2oevjglqr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdffwztd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2emghyrro.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgkbzpf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbqgccd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xooztjbh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pixwgfjx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2naqsczjc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fksmkkxu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmexafy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2thhsiajo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yiealmqd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzcugrq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2omyflmwd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2farzjdop.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiwnicq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvevwgfg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2toisuwkh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsofoif.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzfnohl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdvrjms.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqmnicq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bejagzkj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpriezu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbamgcjd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrsdimo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jifhhczc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jadimszt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sytryjor.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2txuraoqh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mducfzds.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jwculhpl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbeafsz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjfbzih.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxjrtda.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pntwldgd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwsdzni.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnrmktx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqmurnp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qefofhsk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzlsnia.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvawntz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqutszs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhauemy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rnohquei.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usbwnnln.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2clzbwthy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfsrffa.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzebfce.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aywrhhye.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfqdqnl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxobbxhg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2htstkaky.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfdpquk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sclqdnrf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqsuvqh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2plzfyobi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hodjnlae.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rwekuxbb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsfaxim.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xghswwmh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdcbgym.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmiiech.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhkperd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bodekiti.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzvshlz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcupsip.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ksswvmsa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ojksvkrp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbtajgl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vdivnflm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwkmzyn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbgatho.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wcskvjfl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iessxdtw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raqdcovk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tucxujrr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiiqqwj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvuymyu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwrlfus.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2atvsdvao.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2seijxvtl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbfghlw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bugfpgay.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmsjjsu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2feljsmin.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbzvrzq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mqufveek.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umemomhq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcktlry.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqlzulj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbnyiuu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkpvktd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wrddphbn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnleuiq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ottdjatz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxbkucs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrxbvxj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2npusajsa.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvthrdf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tinqgdac.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxiovwg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yamovakz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqijuxb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjkxmlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyrwzeg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jntxknhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqbmdwb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qslfqxch.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2neodchru.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axipjhkb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpryweg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgjlgax.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxgyded.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2heejwzjl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wrinwzcf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jczebxfc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwvasyd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wegvqqgk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxufehvi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhjxwou.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdymrpi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wnraegbd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdwltxf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtqxfzi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwcljpq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbkkmpg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivncudku.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xsavcpsf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fasrzoqn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2onlkxfir.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsgofen.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgdxkyz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljviyjtv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvueadx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvdyxfv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcijsqm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcljvhgq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yhflbhqi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwtemtn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qecpqyvm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vltremus.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2erwgrhjt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nupymzcd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2heqibeye.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqwbevd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuoidxl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2keemjijz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jsunjqbf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lezatzkp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yceuqwbw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrksrrf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlcdvud.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcjvfou.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hzijhcug.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2goqtnrmo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cbklgigm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxpdnhi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2quwumidr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2plcqziwx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfjzhvo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvuliaz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxxqtvo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyjkrxg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gczgrujb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2shefevsg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwzbtmt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mytqvtlb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ityigvmq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnxzzlc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpthpcy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdmmgcm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2suebswjn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdjpqma.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2agnasvge.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqvmxos.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaekqfm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2przqumdc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yaubbvud.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhogzmlg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2roxynkxj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2alxucqoj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqkatag.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2elpgutva.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fseroorm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwutihja.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2caixztzg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoehjtp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlcwyeu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nndepqzh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xenzzyhz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxsfxlk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzulhgt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qddkjizp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfacwrh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnzcsfx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiselvs.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iddmllug.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnqsysa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgopbrf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqysvsb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txzktwqx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvfadmj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjujzam.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjrqxgs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thkokzhp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zaifjgcy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnteetrq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlejpoi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zpywgzcf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbsfncb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gtozppvu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxyguls.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pbupivoq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2phheozzp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvrwkzd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uexsarkf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvxynem.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbdmpnk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqytcjd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2djqssduy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxdktzo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dztwivci.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nzotnfli.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jxakcjxg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdrkuxs.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2flanfgmi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtegyyw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2evbwqgjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpiwwso.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qakyzrpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmifkck.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qxttfhmt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dlivwwcm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmbeeer.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2auzqltzy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2djnuvufb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cacsdzqx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wahicrfk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2strulrbc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vdooubqo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwckgec.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbidytl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzulpulx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqoablm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cimjlclc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwkoasb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fkawcsvp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsjhhei.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbchigrr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxwyyvp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzmkcjr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhldntr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ragjynzx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtrboas.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tirkpppj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2esaunchb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkllsply.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbvypcw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sushgyxr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxtjxig.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbmwvog.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxrjsfp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqblffg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eevprwlm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwqkctf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2opqkaqzu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvngcrfr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyiezur.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuptlbc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fpguitcl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rziimons.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2blwymmle.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrdmowq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ibalujvr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uieyqvof.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwmumqp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2guzzmely.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpojaje.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqracim.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nioayssn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zicambec.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bofufnxi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2utbevzhu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zapuspok.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaoqkcs.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2agscbzck.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2solcnxek.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2btycwyqz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yuixymmo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dpucvjog.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkbvnja.html


<!-- 参考信息 -->