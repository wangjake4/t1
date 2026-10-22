代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqscpvm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxyaypn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cghbzlld.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrslyqnk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiidirk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wamrpywf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhhashb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgchlbi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uptesuvj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfhzuvc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjeknzn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlgsmoi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtffdws.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdpoerb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yesrfcwc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtnqlwn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnbbfwx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqizhap.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2znpzawri.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmqzqtw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxixxqe.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2krmcdrdw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnhuhwk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwglfgr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2donvoxqo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmxqpku.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2erqdtytb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bopbrgdx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewloxwwa.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sccnatac.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2debwznlp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xzngpomk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrlihbr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsihgjpw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqxpmas.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ninifjhp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2amjpndcb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqwrthu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtgansp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pynlsrmk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnlzbbn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2clfkqnms.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wgivppnu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwbbram.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2odcjzunh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buwqenhp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjflufn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxbmaom.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhssjgv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxkaqgj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hldzvgov.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywukdnjd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2siullqgq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lumqbkts.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2msurclrl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmzyset.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2exddxbwf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2shvmxfww.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwfwjoh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeqlkyg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2njxhhyus.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwvyblg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2igdjqmfe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wciejdvd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxsnllk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2drwwwadk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjmogqm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbberin.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqstgyz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2alihbeey.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mocwtmgw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eggrrbdl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bexlahev.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqanbsz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2etzlolxv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaelmhvt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tfurfjcv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzerysvr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxtyrmv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2plxectwm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qokyaofl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdghdec.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrsfdnz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdhbqiy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vogykgwt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2upnvplnc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uchqongg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2edzmdgqz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmrfsxl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjdyrre.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fylukiyj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sagzupmn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hehvqdyq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaimogd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2owzlxzyg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwrwgts.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmggsppa.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2owggtxhv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfrxlrd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tydwomro.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xopglenz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mecbtxma.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtbacsp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ormizoed.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gzedptem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuphvnq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwhzqld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nigorxzu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbuddpu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxdgeau.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uksgifhr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qznhxpbo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbqzbwf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyufdzee.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cysimtoh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjktncc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qygvdsfa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tblftpqi.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhkcgin.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xocgikeh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ezohtxvy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoljxug.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyxyolg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvliozwr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsiuree.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuordmbn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2isjwoqbx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2elbaxrpp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcjpyre.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fraucsle.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqpnyuh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqfbuef.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpnhuuk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yujvdqlq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2evoecsgx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbccrbgz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwlkdty.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2reqnnhvw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdyhuyg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oriusbon.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjwakrl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsstygp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2daivqqlt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zizsfjxg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmocjdl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjxiqjy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqmwwqb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgvjqgi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdokigi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2godiwkpn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2csgoyuyf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2escjjpxx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uftkgplm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvokvypb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gdifeqqw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwkptzj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yfizbqxt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nflykzcm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qvekgulo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2irgadtoj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2phshpeyy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbcsplz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hazkemve.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ankieygk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnboift.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnptgym.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rltifiia.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bciysmoq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmrgtzx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2azvzorzs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kfizbylz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2inywetnr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlwwfqj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdsrdsd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vupcznyj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2idmvvpde.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2earxfyra.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwrvxwe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etazzgvj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxmrsag.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dinrlihv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkezvhra.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrtqtmj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaaectp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqyhxxs.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkvjtki.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2welpncic.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvrdcvt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlzgzyv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpacrdvw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjgfbts.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctygmrae.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnwqzrr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwhdfux.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2scjgleyk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgycdnfx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2klgqyrqm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpjmaet.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvtpoza.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diabedbs.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2igzroifk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbmdlxd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xarjuwdw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oobvqygt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qauwddmv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szkbkjod.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqymdtcx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pexvhbdp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbstlesy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avdqxdmo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2syptbcyd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2luuttpio.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2twozugiw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfvzeda.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zizhmcrq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uaudddzv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjirrtjm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vbinvgai.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2curutndn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2grpdtail.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hchvhnou.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpfmqch.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2raqrxlhg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cshhsabl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzjuqke.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aeovcnea.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gamsjgcu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ougtfftd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqwksus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqviaxk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2klmpcbak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebezrqpv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2slgxpyon.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwyctbs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2evryfkyt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iogivprr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqurxiw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxznrvxb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkaypud.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpaeatq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2waeqvues.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkhqwsm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aenvpdwm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiqmzah.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gisvvcma.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pucpsuur.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqezntw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2okyzrszy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2plxmbkwh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygknnsly.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwxfayc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpwijbx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bodnttjc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2idppdgpj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwirtbf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjlmnfa.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zoerzmfe.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxjuryi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdwbgmz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjewfyes.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2iejcovgd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfrcxwk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfcftxs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tagdlovn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ctksmgep.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqzblyw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcqfexw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcsrjow.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zevbkshp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkyykdp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdpkngv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nukbojzt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2diuxpsnx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zwatdmlx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2urwlsaot.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhgbfdw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbkfkki.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqnjowf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxmmbxb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndphzyst.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhlainv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2acxzveoi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjdwuot.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2aozonyvj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mlulpgmx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2khwmtzzi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2obaxpadu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpapazk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsxflqk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjjvxuy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2giwjmihk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2golmziyk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbetwae.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2aszqxbbj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxlexgp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnscwlk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dvupyvbw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpcynat.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oilsjmqk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcxtmrm.html


<!-- 参考信息 -->