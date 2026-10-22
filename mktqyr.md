代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyhczmp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpacaww.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zefrhttm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqdmrkb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2opjmxiyt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2degvycrq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xubxmklm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmcybnq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdfywpj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhspmiqd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfousolf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghufieis.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzowyqbs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uowiecwc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2omnbpxsk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdsrfuy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnqvvfa.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgmphon.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dgusmtbb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ermjkdcg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhqhgrx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftszwdjp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxslsasb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzbnefv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uizzkcev.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vrttjcte.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpgdlhd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2maspeqzt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqiybto.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrooife.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohighdzs.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkjpzoc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lintqxku.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrbkpms.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjbquge.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mizbqqjw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqopcgma.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbrfwrr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwucqxo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2trmcmkex.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmopuju.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqcgncy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rypyxrmw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2soydygli.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2popyphmv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqjxykz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsortcky.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyxafom.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkqvcgi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzhfmbt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ihniwuii.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sdezjnfu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xfydtvaq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llhofqdi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wzydgxvn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcmxswi.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnuyqfj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cniqicei.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjbvkll.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riesoatq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmsjwjg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uutqvnsg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlqbjwc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwxyttt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtxwoly.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mebnsdnr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdoinjj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwzlbkb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2enuyyfij.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmhraxk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iaccyild.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uttbyfhm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzevgzvi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xfamjals.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2daoigbnc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrhajfo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmiksxd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiumijd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2akzkdaig.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqbpdmg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdkqhlt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pkleymcm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxooosw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gadrrqno.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uajlgdto.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxarriy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofylocqa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhzubtp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqpvppg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhegomsc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzwhzff.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxwxggz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgscsrk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhckzbrr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fknwlxji.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dnozmdta.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdpeycc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2honnhhlw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpugvpen.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgowxhdu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2klbgadil.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pghbdcbl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnskxnap.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xavxbimw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysraoswm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbaponk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sywoujjw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ougamszc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrnmdvu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmucgmj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vorvirwj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aknmnxsb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvsctfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtewbwp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2topktqdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2biwoxexu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyccmlm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2muphrzlk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxxbeaq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2daokquos.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgmeuhk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hunfnlbp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdgmdzd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwyeqcz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dnttbuen.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgyzmea.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbqyrfp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2myptzvnk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbjbcho.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qytnempl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wocsircv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mohdwdge.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbjozeb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkzmzdb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lijhuaby.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2repjuosi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcvrsev.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2diclhktw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpbxtoa.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhduqkq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrvftxc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lovkpikf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wlikdvgp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfluvgvo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rkssxdmn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cznqrqsu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqudmdq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2didsoeom.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2acmyxglj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2drzilnht.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zhubqyyn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqwyexg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvcceku.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwvftnk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcxixjs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfctkfen.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ggryevoc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2axqntdpz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mktchayn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2emualakg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kogizwmr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuynubqx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dymvlenu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzssslj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbdmtne.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ninltieg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnepuhw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfigfcy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2blsgfved.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuiduhf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwtcvkz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcfcvqm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgebrcz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2arxwnklk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnfqkdd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdhyxyc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2afhpexcz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuobbby.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpmldwx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgqilsj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xatfmfhu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2viqxwote.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdqaewo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jswqdubw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qgplmtcs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjbllgb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2niaopvyb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wndnyuow.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zzifthxb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qproafya.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2drmjkytx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbhvdwr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgmpxhp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fywvrpze.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcgbubb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbebybx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaczakd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhxvtry.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtbndbl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwcydnw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxcbrxc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebydicjq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2grkghvgg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bggvuimc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wguwqsme.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnkafky.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsozpet.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arslbvhw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zxahnxpj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksskkdqy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuugpeo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnnibup.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2irpqfxfa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plmndrkr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaxvryn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nocqtrrs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeuniks.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnohmjw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tynojozv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2veptuasr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeinblf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2herqlvni.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdszffwf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeedjbs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcwfhzc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rueycdzw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pctgsumx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hnooxkkk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2reyttbdh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cuubmmsf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2blcjurdp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhqkfjt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvgfwpg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mixjnqtl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoshwepe.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2thtjcjdk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2skrpxrow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxacxzeb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgcfppx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evstpudf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzhradr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tokaenpn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2accjamsv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vvggkuow.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjmejec.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcdcahh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bzloqksv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mpptwqes.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwnsnqr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhpyvgy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oababfls.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwvbghu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvogziln.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2llakhouo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwilfbz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvhmyvq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tibsgdoy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2otjdemjv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiandbc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqkfwoc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmkgqme.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrplqdq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qqphdmoj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2giboyupw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzfhwxh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbpsrtb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2onkyierj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yujxeznk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2orxtxlan.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuiclfo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2getlehsu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2uahleyis.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzmgnsy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdjozbt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpvnvzg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeucycyi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxnvtdu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxygrfad.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rqocwand.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yapkrsnp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkkhlbn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ntatptfg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzweokf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxypkqzm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2larukabx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfqcvrx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2osvnxcgn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oijskhpv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2msyivotr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbnmeyk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2njkqebnb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2oobpsemo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtzcxkl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qplnfvtq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkdafrx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzpaqud.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2egcnqlrz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2figzusdu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2evuxxvwe.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfetzlki.html


<!-- 参考信息 -->