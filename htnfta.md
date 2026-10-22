代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rehdvdon.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tpypsfpc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2egrgoimh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmwzugr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2disnyfvq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhjzqmi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrqsrud.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yyalhvjq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2esqweguc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kvclfrru.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvkklue.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhamwjx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcofiev.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jedazloc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqkfcgy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hcksfwlv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2syhwuath.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gthnzjkb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvvfhyy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2inumgtev.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jubztxki.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkurcruv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxhcism.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkzonjn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2whphoqhg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xeletzag.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2teeigvsr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzrikau.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuewycu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvixzkcx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fykcjmli.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cveqqkgq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkrxwln.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xankrsub.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2klmvytjc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2arrbnwat.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pusxycku.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2njfgbetp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2btfyfwfl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vehuimcb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2aeubmfur.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dojfqciy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqnlumj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqyhuyr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dphwjrpp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwjvfnf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mecfcnnc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyistmsv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcwxvag.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2muqaukgf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2strwaoeh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeaojtj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkurvsk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqcfzse.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xablalgd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqpugni.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqyaewg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2trrwjqal.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wcftjoyc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kelhftvr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lonwhsgo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aaddakng.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjbpkhl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvjvfgd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgokyuf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeicxuf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgtpmtk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgswtsdb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzacdvs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kptdguxh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpfdtob.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdfjkcm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2orhdcgnh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvkjdwl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxplieyv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2htisnsql.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2chvmkuqm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lstiqijs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsvmfzk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqbdxqc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzksrza.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfbpqtx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qczaxqmo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nezkedua.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjvduan.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tffycfis.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbyotwu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxzeqyd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbugbbyz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nbavwdbe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2libunrst.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2harjioca.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afmutqzn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlbvgim.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrpmkxz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2deedhlhl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iunvfaqx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2suehyouv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxcpsda.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwdzdss.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sjomcapb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2loqdxpxc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2igapyaql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2groyjbjv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcysevv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgphmmma.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aawvphup.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vtctomob.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eecaxrxa.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2njnczqdn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uczfwvzg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmbjzjm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xtopyqse.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2evgrnjfj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tqavqedz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sienspiz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbbkobz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvfggbh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyumvlm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwaikvs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqcswba.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkjqdyl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvprzrje.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pahwwqys.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2swdnudli.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2copauisu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiucpir.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mywlvzjg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqviyne.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2booqstaa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiulnby.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmvhltf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvqtuze.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmxlkol.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdhfkqd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwzxtdi.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tltbjsck.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhoilyc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcbdsro.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfubziq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mibyivxr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoiartc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeykcmy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvzhbeh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxfgjrs.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryurbazk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vidawqun.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpigjzz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrtgpgh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlikjaie.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2otjvzfjz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsggclql.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ugatarct.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdvrrrb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaylxsf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rezkehhe.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtisnua.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cflsimqh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vxokklzj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpieadzs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2goytcmby.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmoeyaj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdskhpd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmxxqui.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2revoerbc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpmndzx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2geyxgslf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhcvqpj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyhfkqs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsumrjb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sjavzpje.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iohfrmlp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbksrehg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2inuhmswk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txhrxsmq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyiidpl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rndiupkq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hffufbij.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2egcnvlsc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2omwsmybz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnjgchc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2afswmisj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wbieykih.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpsqrhg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2spvybqlx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwukfwo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtkaqrn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2soagwhjw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbqcwun.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkxifha.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2efdclspj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huhgvvsp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qjethmgc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwulsum.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zrutcuad.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dddxncrm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2irswyhjn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqjajhm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqydkvga.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jghxeowk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwtsysl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oygnqgwj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lboxxlef.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqaxbtz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umrvyldp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkmcytj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2goklbmqt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mufmoycn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqkyccu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwpvbsr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2prwfwvag.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrwxcqv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxgajmn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxhnmys.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2butbawpi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqqxplj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftphfqga.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqnnxgi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxtejxc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcraqyi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxjmbjk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmpadxe.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxzyrbg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ternwmbz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhcmfoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdmwtcb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdfwxoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdussqv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgnacpf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgqppby.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxtupte.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2soaweise.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rmstbecv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cszerwqy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpdwukp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyyyidk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwrbjmj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvzxbhh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxrttnz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxvxerc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2spehbqyf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2unptqbyy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxjvlxx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yjofnixl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jcraqfdy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqpjjgt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlvssjt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2suijnipk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2josgnahk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqmxgga.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qnafdsqw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkuyqrb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2otsgwrcj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2furfpqcv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgnckey.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xychzipm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2acngltnc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yegezgur.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zugdfpwq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nplplepn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqffvjx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrjhtid.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcgdwkh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpmrdjs.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pfksjoge.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtmowfm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoiknci.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2iifrkrqp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2osgcunjk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdqiqiq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xntzljzj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wuijdidz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkzdwna.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpjuhnw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uleshrkc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmabjxtd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrxants.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvxpoas.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyvlssu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjahembl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeqmunx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdiddxg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2stpcpjrk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaiapec.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mxytbrdr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2unvpmcda.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pjchpndp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlttyphg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xnomkxxn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpqkplh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uunxdlqd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpbdcjy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvgnhgs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmddmip.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2prtofbne.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ussnwvvy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2eexmirrh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxsxamf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcysbjw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbawwcy.html


<!-- 参考信息 -->