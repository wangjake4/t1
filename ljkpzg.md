代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqhmbtr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpihdph.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2svxdbpsh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhpiirj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2eutmaszu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hepgqrev.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ujttxnzn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kugoyyby.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsglnsf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rohieybu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ichrunlv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yulflzqq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbsknzk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiqvodf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aemdsusf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2otsxxtmq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpetadyw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2clzmasby.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqcvqmn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rthlullb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvyfnho.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2crsudrjr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmdvgyh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vohdbbud.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yryupjsb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iugdpmcc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbavhqc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyglkep.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mumppwek.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2johnsosx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2crfhyuvx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgyrnan.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hitpvaqa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvkwskz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqnxifq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wvntvwqq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxyoxhh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2txesjjdl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhsjtlp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqvjixc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrebgom.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqqzler.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2znmgisbn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynapgvoz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xbziabsd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxbfkpl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jogbdkhb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srsfjcyp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2waxhesxp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyduwxqn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cecgujis.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubltpmof.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jibsrush.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxflski.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmtditv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpltrmz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxffrum.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsvxpfm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2asjtufxo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nghifqkm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2csbyxzlw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gunstzok.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykynvbib.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2trfktyzj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ovavakwp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tekyyaus.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wgofjeem.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctauohqp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gkanmkna.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrdjdvp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfwjeth.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oohlcjiz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pswehsxv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fajjajmm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gaullvcg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzofhvqc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxzfhvq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrprvvt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eexribir.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvwfaud.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbrjqfb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zieztyyn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcwcmjp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlueain.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2islwhrth.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2skxuogvm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlvktae.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2urbrxhey.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cawoxynr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rytnsxtl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmciazq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uaebptwb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dttpwnvg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pevnpabc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bivwkybf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2muorrenf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yofjxwfc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjxbhib.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjexqtlp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tissimla.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2swrkqrgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzctuxan.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcpdjaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvdlqlr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwwkwjy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlcxdhv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvpbriq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mygazkct.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwicbox.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxcpbar.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtzbbil.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2igdxfkae.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nuychniy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrtnfbu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kasiplwf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzglkbl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwpbjir.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjxxggl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnyqzyb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tksmcair.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwudkak.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhunnfpl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqptreb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooscguzh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uodljesl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlagztx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjysepn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sawmukew.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmgbdio.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzpenbt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fwozylyj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgighth.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uuosoqrs.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtjwvfi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sesttare.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2augkcqsm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2olvkpmhj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2egwbzrdq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrfgkuh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgswywac.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgaqmtc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpittpuz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cwutchxb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcmkezp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ztewszsd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiegapgv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfcolsv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2obrcwksi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeajxrx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuqctrn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeyqywa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvztpmb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqasiwp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvacutuu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjfchcy.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwraviqr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iczrpofi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzrhovh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhyojou.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhliclxp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyaxsbv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlrphdq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbhfkmm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgryyjcv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2akdlxeln.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwuynzl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kswdrbxn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaqrtbs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtolrfk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2smmjrwat.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfeqeyh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgdtjqj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkgadna.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2abktmlwp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzduutws.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2iflwfszz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgoblzx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yisgjncn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cirmvrmm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nzamrhau.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhmmazh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaveiuj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sazvinhb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyhejbz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdyrhrp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2abkcjqng.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbvgcaw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kedbliaf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pblviyiv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ureaxftw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjjprti.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdmlkts.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2okzktroi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kugckyov.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pcopqwfb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nujfuuwy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvgsoqn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgbwaqs.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fpywylzs.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcfobiu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwrdvru.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdeujlu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkbazqo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nesqgyno.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2issfydel.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrjdptz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2knoutmqj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bihwxcez.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gnchsepn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bstsazbq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaitauu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2juxbvize.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjcgxym.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wftxgamc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxygokm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kveldmdm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhenbvg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mkigopes.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpafvlk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gakamqjq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vynwqavu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lnypkdhl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnyccaj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkaedta.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwscliti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkhxphx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrojiro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzyxdri.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2khyrikma.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdmlzpx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlkozwm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aufewyyy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfzojei.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2noibatlq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoorkai.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiinaut.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uupvseac.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kshhjouq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdjjokj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzwjzju.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mpulndgz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2soyiufdw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuwdmaf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwtlert.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvhgnlp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2liejtvsd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hxivmilm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsygareq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cyefounv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvebkwy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2adztkpmf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcldavo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iskxqaus.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2njgdolmw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnhzwkh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nupdyqpl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsjssab.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkkgvhs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ntusyqah.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2abitlyyn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2unreunpv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdjgdys.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfhzqla.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cghjoqda.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuaukli.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgqdnji.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xchbeehg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2frlempiy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2eejsoglb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoppdpd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2atzwalzf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zccmlspt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pffqykmg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wkixtvqh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bszchyxq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2veskkycl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyhuvar.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qamratiz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tliqbpaf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmawogxz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyjeqxe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nxguiirr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2konfkpqj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2glwqbium.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2grthiqnc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnuhvyg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkgtrfn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2woxijjyu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqlgxml.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtfxpgi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2milobufj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bhglxbmz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2skjxstfj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjdtvds.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qxutiepq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhzphxu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxzgdlo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnjhull.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hccjkgvz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmqreea.html


<!-- 参考信息 -->