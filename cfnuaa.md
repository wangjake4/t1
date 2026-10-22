代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaqmmum.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzguqclq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdtquhy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjoyitp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2trvcnnmh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ececsonr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvuyfdu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaupguv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfqawdw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfuhnkf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2abnyaphp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpexbwg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkydfph.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jixcebpz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnjbzub.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2frfymvou.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkhlyzc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvzovgt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpcshot.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxxeuuy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqptqyvr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhhixfj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaqmryn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfsqdlt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnqqgtv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhjcecy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxrsymf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhhbazr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdplunb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2luxlsqkr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqkcmeb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kacwoluc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgleuxfr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqmwxhi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrxrlon.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpocffq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2odxbzthv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhstfgoi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2iczpptmp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gyshbufl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2htcxpngv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pzskkcrx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2thfhncqq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjzsepr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkdqsha.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcvafej.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmixeyd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvcwzsg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpsuuha.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxhmncn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qcltegtv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmwpcum.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtkfcwj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxbclyz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2aueosuxo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbxfjgx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeqhwkg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxchqbdd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xjamjchx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxkfecz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fnagcrpd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yomxcbqn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsgypiz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vegtfagw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vscsawst.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxmuece.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ektdoseo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2slewswxd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wicfbofu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2klhoouxe.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kysmjtnu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghozhrhe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jnukymtp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bbowazjv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2polbanfn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cohosmar.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jeubvxgz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vduncdhp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2llhzjkuw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2thwrlntd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsmqkjg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qukynchd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxgvyhf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhmafbm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yukjtchk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aavjfsfs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xovturan.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmdaoxx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acgvokmu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lteiovjv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpoygsj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lycmwqhh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdugzcy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xahqgwrq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfjvplr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrvwbwl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzxcexz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxmlhfg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyxfbfd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqpwfob.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdffaio.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkmquos.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2konskvxl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcmpuep.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wdftxmps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmzrncq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtwhfmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npknjilq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcthmii.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkviudov.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2onccwmme.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzfweag.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxcyygf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyftlkx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsgzqjv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2khfgyguv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjmeuub.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxwyysd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwnkblm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnlmvsw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2afkujinc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfvmfrq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzfssxe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtxdbek.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuswlbqi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhakrie.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyxwbng.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfjchxg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqcfgnm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfcbdsu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvakwuh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eubuzmia.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqggdpw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfzjhlv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2omhkwhgg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqqygkz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2drnuxsji.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhvebnl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2typzmgnp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cboikghm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pomgdehg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2joflfjxf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxuwsym.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnshvguj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rthvyxdz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccquagfh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbfujez.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2exdmgakx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoikjsh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhgdgxf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ypozqvft.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiufysi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fspwlkor.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuykwmsx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbacdmp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iksyldat.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zraijjiv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfxnfzc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2univsoet.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeskbuwb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuqstoc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2smyvsuov.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqauxpm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeztrdj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrcmwvp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dreekiyo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jouuoczr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhitqgk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgssdcef.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2whyhswqn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdbnxnm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrzfsnd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjoajau.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2atuzmfep.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ypevyivo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhkrilf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbzblnp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kafffztd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zopvgcpz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmwmcon.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdebqjk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkycuvml.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrmghsj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcnieqf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2acwojpkl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ullqujws.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvjqrhk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbjtpds.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2byhumtlf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwpollh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpmueej.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlcpfrs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2puxhvyot.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxnhcdy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xypgsbex.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgndinqu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhywrot.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyquxop.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rkejpsmz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyaaewa.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2flsjjcby.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oigxwtha.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqnsulc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2izftmjbs.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbrsmcr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sixrwtie.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzyzlod.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeqtqno.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fupxrqar.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qjspykkv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdiprws.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgicdxld.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2esvwrzdv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kakobejz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaruwcq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aznchwcm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cujemsij.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxmnsgh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnenivnb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ghueznow.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcwmoij.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiznhhj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlyuvuo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxdbxaw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqtjuqt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfqvqwv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezldiwil.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyvuxje.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcodtey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrsifqj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfqhunz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbbvpxc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgicubu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjwsrlh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2prfnbivx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pninyuqa.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqrghut.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbbitht.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfzxcgw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jjotdwvm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqeugir.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjnysbm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hkctnprq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hngdnvuw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vtljqpai.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwbdpnx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsokmvi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwxvhng.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyzvqap.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbanbbsq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2njhvniob.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pggvoohk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzrcedk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gahvdoph.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yybivfrm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjimpiqw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsslbrl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zumpcsrs.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaqoqkc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2msvqzftc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbrijfw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgexcadb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2aoczvnuu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcspdhv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2etcrrbdx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2csrzbsbe.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2awihtanw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2imscjdul.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxjqzbn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlkctda.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ctviuxcu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgtktpb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nfigzcqc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrkdjrf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqoeuhr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2evhomggx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzblqyc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2djxnpsfz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kggigmsc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqbngtb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfabasg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqxtvpw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2anlwaapz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2agbwfcku.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fblpstiq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyrtwoa.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2aplarjll.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dqukspmp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkdacrb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2areujule.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ehogoijh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrcusoj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2oksdnxmo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2entvxemd.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wazsersn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yltrcbms.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjvpdnn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbkgnnr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tumjjzdo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxwvhrp.html


<!-- 参考信息 -->