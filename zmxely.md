代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwathtkx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqmmcgs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgyukmg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfhcqgl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmbypgq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlkspua.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oacukuoi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2skeovnbp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrggulbl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyeeeto.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbwbclt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdnyyrx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzrwrfg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2atxstnvi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2egwuxkmk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qjehzqnh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gofcrcwj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2spytbymx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2llvsoyag.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2phdpraed.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2endfjjyz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkdsewa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbodrcgg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyxohlt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rytoxrmv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2inolnuui.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcwqepv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uuorqcea.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqtzuuh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmzfafd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mswvrmjq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2igmdnjwl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2buczsqzm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlqjqrs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjkiosk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjilkor.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuckdwa.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhonkve.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmtvqgr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjmhfxp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyyueyc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zicpajmp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfqswki.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zazllagm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqmuzrz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvsiayr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvihmst.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjijaev.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2miyjsiqg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2chtpnlpf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwbiamh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wziqusxc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2frjrgvlh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaayscm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmtjjjh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnurfkm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbfkakn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoitkyb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xektsueb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaurvopb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmiopjb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zotmgutv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sitavfuq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjvkuso.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2prhqpftb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jssernrm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ntloaajh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjnhbzs.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2okjwegan.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cdapxoam.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrrxetz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfymdvgm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpnnhru.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fypfmsxm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdlpgka.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrcdrqr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbpuuxk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnkqihr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kezrrvtn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2onmrfvgv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpdoibw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2siocrxzm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnwgmax.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgcvfty.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdkrlmw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlebbgk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2npgexyto.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rthqryls.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtwmqnl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2naoekazy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qogqwtkm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzgsvnl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kooscupn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkyzzao.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbemypvb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rvawysld.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnogjgzj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwbcywm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2onpbgskw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdafczk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwnbsvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrajdagp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2oscpwkkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdwjamm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ihawmmbh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqakelxz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpvapnc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqenhyj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cgueooxe.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2psgvwjxu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2exkttdrk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rashtqbj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxttnyj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlilcyx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxyergo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtjsueg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlclygk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iibimdhp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mijhtjvg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgezxzzw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhyawsd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2axblbqvk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qataxjch.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2spxzjsmj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbevfzf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqxvngd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxezrst.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxufpgi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iclomhfs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hszwwnqw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oelybzja.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmlivaw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jupklawl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpaqfwl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgnwcds.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2botaxqex.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iuawqohc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2imutikan.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ompufhsp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfezhvht.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yfebctyn.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xosehtmi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tujxsrqx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hldqwgde.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zywhsspw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dljzooww.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2swbdiflo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqcbpxu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zghttxat.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwmndzo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uesmsmbw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxgcsmv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2olojobdw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2liyrvdko.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyfyhui.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjgsqpp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yhprgesp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2deypmnfh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xguzqofb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzkbhdy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2szdauaan.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mowpfjld.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2irrbpbei.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwfemaz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvabteq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iehdqhgq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mzykpczm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2utabkkwu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbudgxi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2achyxpsz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfayogg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuugoaj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2svivmwbp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvnrgyh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rojyqfgw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbendje.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rextdwfo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzhvaxg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2npndkndl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzanqea.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ywggryri.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlypahry.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bgewvtgg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mirbjdod.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xhndpxtc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrgjgxa.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2onoehvwf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wypuzpwh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2epzftixn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdcggzk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iczfvbgy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdifkrm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmlzoji.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvakhoc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfksace.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msxhwhvn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrrgvby.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etshqohu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxccfavc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjngayd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olemskqu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbzzaek.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhnxdll.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvwlotg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgapwvh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxxzija.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xupeuych.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjfgccn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ccetbtmw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bolcalji.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgmtjfn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gumvrkwf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2irjrdltg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2adxyiafn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqppqpc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkdzyvj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxifhyc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oxroipju.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lojkwdty.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2agrxebcx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2whsmqted.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjwytrt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjynrtw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2deyjmxdx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkspenc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbntfpj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gueglwxj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfkeqqa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2peifcdvj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aubwaubn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkjsdyo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrztixx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzfhwtg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkxdvuw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2slypeopb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyhdlia.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrihugl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xekzyokv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mezdzmjj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiweuhl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2umaevzql.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwogcrw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtdswqb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fsykscbs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjxixxd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdtogrr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlimrnc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gszzbsud.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hlchgpcr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaoywpk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hcactukt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkojyve.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qslkludv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yliwlfxh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tttlskxr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kowrlfro.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2owjvmiui.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqphijy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2usufqxrh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2faxxsnmp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrptluu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gstxvgei.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mudytfmf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyowjez.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wiidptli.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlbwxyo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2njdbnsle.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2umjsumxj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rzryfavb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnqavhj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jtewqfrn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnztjtpj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qftokadi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bdncmutn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kupkdwyu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qttopyyr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xzahtvcx.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlinycj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgkzgwf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnwimtt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zobzynkc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqtdgez.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqubike.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2walxhikv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmyzorq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nicphngq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsfqcvk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2luqvyrli.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkcuuxr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ounubgby.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjarzuz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2efvzkagz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2deigoavi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpminyor.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2glhjornk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgkxanw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzzbtyx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhazdmr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbxmvdw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2utuupgiu.html


<!-- 参考信息 -->