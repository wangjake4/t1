代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvtzbad.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcdvimf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbydtniz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oedlleqb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2btovqctw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdjzcru.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqlxfup.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvgarod.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvmgoxm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qsstjmaa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yiojkkev.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2khkzgwta.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuybhsbh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2asvxdxqw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfiyuic.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2atuwxrdh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nksrrqec.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqxhyou.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcjycop.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dexvwxit.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbeoecq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gexgoiwg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwjcwfb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqtedqp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2epllmwcv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bezrfmcj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvglhuxu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrnrewl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdvqrrx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoxsagf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2akksxqxc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zvensasj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2trebsqvp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhqynhp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnffvio.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmizzkk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aphdwuas.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mphtiydx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnndbcco.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmrhfrm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxepdks.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpvfkmr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdbmgbm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpeaclc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiholpq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvdomqx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrgdhet.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2knhwcvlr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yegveybl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2klkcmbzp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mioaednb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsuggwo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbmueka.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyirrmzu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoaezbe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsgzedv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ffphifmw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhnptmu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2miqtkebu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tovycyfq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vwepvgis.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfppytn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2orkqucaf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwduhvy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtprtzk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoxiwqx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rszclviq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2eahnwjen.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hurkchxe.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqusqpqt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvjfwxj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhkjtme.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2brgemtgy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrchfnv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ekskvbeg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgilqty.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2diwycwvw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izyvbjml.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjrzbzb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcxhxrb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmtguio.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdefbvl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2crelbure.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rtktntaa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2suhwzrgu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmsnbmq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbavocz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2llynfnoe.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etqucozv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2panovfmf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvclsdux.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2byktuqag.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmlqlok.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lutnhmld.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sesnrzgn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvyvuch.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anxcbdte.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuilbsr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2idlvmmwc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cfohutxw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdlewew.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lidmkicp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2arofjtar.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cimgufbh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ljajzppo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqempnbc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpqbqog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2munruqrn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xfezwhxw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjbhnfe.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfqptrj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrhuldw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2foqqnjys.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nejhiequ.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkbakpd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pllfvnum.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lciujivt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qlinzera.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyyvotu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mizqqzgp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dutzdafp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmuyovg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlvhogf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2srnnldvq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvakayzq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qafrqpbl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpreuxc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dncussjw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2knxjpewk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2otkiuxnv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sduhnsrj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbjlspz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2exxcuofq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruooqwng.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgbgcva.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2trzctamf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdjpowt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsebafq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ypigsezw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkubbhck.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnhfwbj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bttvcovr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjemaar.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2teqbampj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zaemvkfd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vszeqvvu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2twjjepbv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cejwgsod.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvzktbp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2veqorxle.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzjjrcf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuqjdyb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoxyyvr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2smjazskw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeuzyyv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxuhkse.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2erayoomm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxzlaux.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgdkntz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjayxisu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjdtndy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uptrwlna.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrznotb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqupusx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxaxdop.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwxdfkv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgbpzeg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zesvwqkf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbyywbe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2guyjcaag.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnqkuwl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdjxczf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qobjyrsw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfpupgm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2uldqhuwr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iodahrol.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqmsalh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2euryizqj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnranqtw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqssmgud.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2podgtdns.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibslunsg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmqwocf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhqgnxl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2recntfgj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkrpaco.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fplhllur.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pphkvsqk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2siyezzwf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hthhfgfi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iegoawci.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeniwxn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cwljiwlw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjdxveo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qejgwyql.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2perpodwp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kwddvvhr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxndcuze.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcwryyy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frmlpwbo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vayzqmbf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhonuos.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbximrd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tivusvgr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzijtbdr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrglfhn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usoatgys.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fecagewr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrldorwn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyztpqv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2klspmpkt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otkxkdlg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqzrwbp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdzklpl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohusoufn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2skckgvry.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2juhlwsxw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gajfzirm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcxioug.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bnenbhng.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bryhnrzi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdossas.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kghfxzgw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2niluonsb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mlirwsqj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgphfot.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2suldkemk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjtxpmr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhedsnur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abyeczuc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiqjahw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdjrbzk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzdlakb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfvbkjh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsdfllo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tipjhlvl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2odmhkgnx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2edadkaye.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeoytka.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhiszsg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qzemomoh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaeewih.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjgjyic.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqilylir.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlkcdww.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fllioiac.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ezarjcmy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2acidhlzk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wyffiney.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yezzayvi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pljtmgsj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2exxwunur.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnuwvir.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uintdkgk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wsovgglj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2phznbxzn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2asrdvwoa.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2imynbszt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2amflyuqn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkjblws.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zpccmuse.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bccwanqs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2saibirsg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqpyoes.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yquvkcvh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmieuii.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2buehdnxt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eziitpya.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrhhxnv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhtzokj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jypatxvd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjagywl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmtmrvb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyqsyff.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2noxauhhh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtjqsru.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oszxfqox.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lumddyvj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jckcofwm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zffcavxo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmlrgoz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkcvwvg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ictgvypi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fypbdnaw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwwuits.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2usrstgdo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxstoqx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgysevf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoxiyux.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yswihkqe.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqlpici.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2imdggwik.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2clwtathw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwhndqk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhdlzjt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ggczdtmf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxhgcwb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqwjowb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vkerrriw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxyntyj.html


<!-- 参考信息 -->