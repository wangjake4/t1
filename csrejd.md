代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2crthyzkp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkpfyey.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrigijl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2diiecjss.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgnrvrc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2npzfyswu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkupdtss.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlkrrrz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fihakqye.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpjkwvs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjnblao.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwrljuk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2onlfolru.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2chpckrng.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2adgkrimd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rbogttxc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mokduwxo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qysvtcfh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wygofhbn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cndkodib.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2deuzsajg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhtafse.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2inmpqqyo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnhceei.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dccxsgyb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkxlobm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqeevmr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrhxscn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uidbivrn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqdlcts.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciywsihu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2oubsgwts.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rkimvsny.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mybpanmx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaexqss.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsgmphz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uondgsuk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckytmsrv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmqakwi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kznaydub.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpczwba.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpaalgp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuprciz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdxtlzo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgteqds.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhcvbwy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mskttrfl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyskcml.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcyrjcm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxekvoew.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrwwpyh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2epipqytm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdudejo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkrzpgf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2solginkm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzlgzrc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhaitno.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvdredo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzqhhdp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zcljcytt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ystnyzds.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqdjtfn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwtlsuy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkcrlun.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2sfchyrgv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mscmvnqh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjfeoaz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwsvrod.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwnmgxo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvmofwr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2miazovfe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oalszvnl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kojerowj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2peaivfic.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yflrjeoz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eematipt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyzzqnj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rzepcjon.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhvmazi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rafbgunl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkpigeq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zmifdzwe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nggwuzep.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2njjqajwl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2poogewxg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxtryis.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2btzwmmpq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2opflaftl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfrnbtt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2horefzjx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iusdpxcr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nayagotx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyiojbr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiajowj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfwpasq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pizwbqqp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fliuigis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyxicsk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uiftogla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdziqdvq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnpblae.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqesrljj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrxmpol.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2chvyllsz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdmzoar.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcomzexh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaligoh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpjddpy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2keajfqrj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2obfhktjh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sujxowoe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsingvt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwkmjya.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vclcnvjx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwmgllb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zskmpeyr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnxgqfv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqonocw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqerrjmh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwfibwi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrvowtz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgkqjcn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzmjcyp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2isbqhufh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aztidozx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oourxjtc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtgdwtf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zidncwur.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pepzkumg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2avcxucwj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nmczocnb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2azyvhcmo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2onwczqza.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2slwfboro.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfllzuf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpklnaqw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wxedgvnb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxusgaz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbtsvqx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2subhrlfm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tlswuqru.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzxaapq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2utahfomf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmzgsuz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxdlwuj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2brzdwdgo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vsukdrfe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktntsvuk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdfcuii.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vquwrtrd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jtndfqna.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieksxqxy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxonyux.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2giwqqlna.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmcqrtf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qunjfoqj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iweiprbh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyhpney.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2iygfzvtt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixallbmb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzsmnnn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlhaers.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwiohiy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqostjk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wibgklmd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2eeptqszo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qipxqegf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2eetnfvni.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2aesgfkyb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2skmjypmn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtisgkk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmjjvgk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2netqiwwx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pirvjcnf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxnrvrn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2girxkcwb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdnsfbw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdukzev.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2eddcyulx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2aufhkymu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjsgmsd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ongocdum.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrfxqyk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygemqsin.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqetbtf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgvhkxl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdpxjwc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuvhxeb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrpwuhr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pedodafg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rkusuqsg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcfdmfk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2loqwaypv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luzsyvnz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aaorgmtz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2aotmfnpc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wntztmem.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjatmoo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnjojsp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnhuugn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtzirey.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvciuub.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeilqmfu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjemzgb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjqszsw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2brxshfbi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rriglcbn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvxfbor.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nidxgxbv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xruqpumo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqadufp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qywieosl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifukdsfu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jichgpdj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvbpauu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeioqzz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hllcctbt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfjtzxm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmnunmp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlunjlx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wijrlqeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjsdduw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2naihrbhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zekekwst.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jailgzgm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jlitlrlu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bosuchei.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bavrujfj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrkerrw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2apqaejic.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsgufvm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2epklpmrz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdekdlg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpndcvs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fbghyvaa.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqxscnt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdjhqie.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrqsxnn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaadvqh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2codhnneo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gspfrohd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjikxmm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrksvzn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cotfevtr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqesjcq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeotugvq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2etfptxqm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqtuxjy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgqkkjd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2shnqqxfq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkoswde.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmdvekt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzpagnj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcoxwht.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2evyqkeda.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ateoaprm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlprpoj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpjdleo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uihqpfoy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2epddwkph.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvhvkkf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrbkfmj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnbyugm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekatbgou.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkhlwud.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkuyerh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gdozzkfp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmnlowm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgffxzv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfwmrwk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfyicyu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsqqgwd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfnqclu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuscfhfd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lntilzgf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlultvj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyvvejd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2gitasfue.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlkuxtz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2apefsebh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iadyuurv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkvhyqy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrdxgug.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsanfpfs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdvymzx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fnigrfdt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfwqexb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbquirz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwivbjv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2frjommsn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdqrqpo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrmweqm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fuosybor.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lowuxner.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyldrqx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmwzclo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2egekufju.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2spekklej.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2scegjrbf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ueakcgij.html


<!-- 参考信息 -->