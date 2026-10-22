代发 wailian999

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzkvdzh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcdabht.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvyfucb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2izgkliks.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2popyascf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdgjtfb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtxvcqr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoxdhnr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mrniqhom.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdkgowj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpazchsv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stpeexie.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zendcjur.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfaoigl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vumdzdxt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qedkwnfg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqxueoc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfuprwd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxfsnta.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwrvrox.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2panwjsew.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbrupvy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zsboefvn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2stooireh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmgqmkj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfymqos.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvyyvag.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2luimbbnj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxfkabu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dafpeaba.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2omvamdod.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdlvsbg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2waimbqek.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpmcnih.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2knuhlshn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2swgwiotc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrflvup.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2exyyiwbc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxprwzpd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmftepr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiuylog.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzppvdy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvdowcm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2twaowqfa.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2norupxhs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaalews.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2auiegjdv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2shxxiuqp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pchrmymj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrrnxiw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2icmoafos.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jhirdclv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwvfzqf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpkohqo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mganouyy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkusvrj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yntchiyr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhvlqrm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhbwknx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrbcgbp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqjmdcd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2axmgrjew.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2swjpisxl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xccyoyuo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxppnvz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyicrgq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2urmitzpj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2whmdwcmu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmniwoa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwdcomn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjbfrfe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfiijyd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxueakg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzatgzs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbomrif.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpgdpxm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrshdpi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrsnmnn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2foozdxld.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfopboh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ltossmkj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jawcuaua.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zoscuzko.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipadbjhn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dbydnufv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bgteyywx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2slrncziz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsqieab.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqmlpqu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgxqipf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpmjofm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyotutzm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbecqcd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zymouiaw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wlontrwx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aduyfizr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2whakpial.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lgipuywq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2egiagccs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gapconbz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neqtgssr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cieivxvz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxctsfh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxltpct.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbaminu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jsexrtad.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yieswgat.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfvegfp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svcmrlhh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2njxkefqm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhimbau.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pepmsrhm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jukimisu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2trwkycut.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlalnltk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpjhxqq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzutuht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htccszcz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyotdmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmvdqgc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lfreqiwh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qezwostt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmdsjdg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uixavyhi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqfvwmv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuhdwqe.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2knlsjogb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgfsrdy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjctfxi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2onasnonk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mblmvodc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iztxuwyz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jftgbojz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzmcldd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtzzfgh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zigphyla.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htllaejk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jikofmzq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcbhqoz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkwmsin.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2agbbtnki.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ontrvjlk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjbqgdz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxctvag.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhhkmzr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvhmeuf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mumlkqhn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqajltri.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bldilnuh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdlolkf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hjisoooj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mksasybb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrruuaoj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2spoqxwng.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wopehndc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoytqqu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pitybots.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhplzifu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mnurgklm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jankmfcn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxxikic.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrfjaya.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mitktppf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jajefsqv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrcmxhf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oprophdj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jiulldgj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2meerxiyg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lwysvepl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oudoapmf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2clrhohrf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqeemaq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcqstij.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjogesb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cblkuthb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoxsswg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxzrztw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvebbuju.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzkovuz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjikyabx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zcznycol.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zifecudd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaixjhu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzldleqx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2momlqbpr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2izxabaey.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rggnbtdz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2msowfvgn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjptmdn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2heyauzrb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iarwsauy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxpqjse.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdsfmoa.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlllggm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlwxime.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rrasnonb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlzuboe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jygiuvhm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2axrmtqki.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkxwfqn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvcmyos.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbofkarx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqusajv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbdmvcc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2toowpcyv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgynkyw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrolwzp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgerpah.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcrcpkt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmpqzlt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2poeyasgu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrxpftd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tjefsutf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgiatbv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjqacaf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2thffgjda.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2quhlteay.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iacjcizb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2veszskic.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbxhyze.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmtlsik.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swrqjvxs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnminfsj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vyumgsyu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rsysvttx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzoichv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jquyfaqh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fubnjjha.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2reomnmvf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnfqqvh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcffzlj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dpydctnz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxhbacj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2knzpubtt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqgzmax.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2euzoxgil.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxeykyv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aiojlrgy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbojzzxx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2npsmkahy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqfwvch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrixfsut.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfycgqgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgnpirq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwefbrc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2etcdrodb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqfxppm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wffgieqo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbecmuj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2djrgzkzs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sznnzlkl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbkiwjf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dcroxtis.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdaqsoy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mzadkuxc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxuzasr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpxbdnh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwuboay.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2azbzinkl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpmfheo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqezvgd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyhknky.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsjbihx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qnecyxod.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2epzmersg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbuegzh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbwerzi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2afqxtruo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuhsvzq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhadlcph.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qhozjkvh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dewstypq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdrqcab.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2najzuaau.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bapifufa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oypamxno.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fszllxuf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccymbnun.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2whrrxejk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmubnii.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkmlore.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfsjazo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvckmpn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoivdbm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2trzyyxam.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2scpssrvv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhvxelb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtajgjjt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wafdqkgf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2duvrnkhj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mudesbhx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmjavna.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zeulmuxi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2iozqhhrl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhzvozw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyssxdl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cqogtnti.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfjhdtz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tdenwwsm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cibcnlbq.html


<!-- 参考信息 -->