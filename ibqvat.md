代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxisuag.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjrlcfp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2glhsdnhk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2erkkbebo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsrfgio.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kguutqux.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tizmckvx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxelsfl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqvgisf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjghcek.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gianthlk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xxibitzj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugohwezq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqnepow.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdsfekc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqkbquw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkpaipb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jejacdtq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwpnlne.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmyeame.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sruudbrh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjziuzov.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jggcqmhm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hqftlvxt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jumphtfo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuxxhos.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2anxsmnro.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhsdrxr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcfvawz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgzopgm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eblejluj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnovsqmh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzgwmvd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fazrrkwd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2emxtrksq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcmkjax.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnqhfjj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2txffzuhk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hevfhkvc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2irzwaucs.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcqaxag.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiixrky.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrekegr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cdncidoh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xkspwzsu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2smlazpow.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zydppzdd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaupzxs.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhvamii.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jbygeazj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqhsbvd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2asrmhslg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hjywhvdk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmotkkz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtqrrle.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owwfjaro.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoegaja.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wfksstsg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2praserzu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axigzrnf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrlcobq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtxzrhn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dapfbtlt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcrxeup.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkxvhnn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvnjvxs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hlowxzbx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2krplfmpv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgazocpf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2axvrthja.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2juhgapif.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgeomtl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vignkudx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2inrjpkle.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqoufof.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyickjd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcbnvex.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lyprfhwi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpbzfpp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuzaqat.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azkpucxj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kpffdnjv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiymcqvv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2whcnxdrf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqehbxbr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wgolvpxm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryafphcl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ijetirbs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnwfabd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2moijdios.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhqoqzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwktgxh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkwevlr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkngcpm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2buildmri.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsxjrrv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2orqjosvy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bubfzyvw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hacaytqk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ustnpjyk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2whhhfawe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wynlpsit.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfnkggw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlfqqzu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pscuklfc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yysykfml.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaluytc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwmupii.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmabdcq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvtozip.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzumsdsk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpmzuet.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2immbjqzf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yirhzqma.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2osibbozs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzacnhow.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbjbqwe.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oogggjdn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaiazak.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuieigln.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2evbxypte.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeimtuk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nqejjksj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2feunmwvb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lruwxbjf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaujlfe.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cahqxqtu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbsoruc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bsflokfc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oohvshny.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2otaflmuh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnjxpvv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqptdvd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyraijs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2crndusjq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fwynrotq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuakaqa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtykeobc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wkptwhri.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vprllesw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhgentc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpuscpo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2duxowrjc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyhsxwu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ayauyviw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwguanrn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwgjgpo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2molfxuqy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2npshokes.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlbmlpa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qntfqzbw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhsniut.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxgkuji.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2niovekle.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjgufqs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2undpiesf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2oordtlhv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pbizxkfb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgbwoke.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqxgena.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lzixdzaj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ywggzgrv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wejtcmmw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnlxfah.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaqpmvu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbnzhgc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvwruhb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2prxtbvhz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wolvsbmd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaxfpls.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhkfhyw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2heumbmsx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdygams.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrvztke.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzbcxtu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjdiwyn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbojquc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcftiuel.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpzbher.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stwgjrfq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrltfmy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgxmmgi.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vmebwgsq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izmtnfod.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2axuutprw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izwpbbgj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqqisza.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rimknabp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kerriqvv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzvcnde.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2haszymmr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoxegnu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jboxrjox.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlcgbdy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiiwtpn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsldndd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzjgqia.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoaavph.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iutilqzn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2negqirkb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eegxkncj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2udzvbthr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2upzyiffy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hinazwzm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwktuib.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rycwpkpb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2adfmtzyk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zsavbfar.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmvyhkn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjhwccu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2geitvsyz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bmegjhkw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2olmbxfty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqekslta.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvathosk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhtyfld.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrgcnzk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2omkmggup.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2asprwtby.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aksruulj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeyeagq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtityqgg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfjmfse.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xcipaadx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbzdzrx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eedbguqf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvwtxsg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2apmphnbe.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvjsjcu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuavahap.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsikswx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdpxfpw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyjlmyn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjqbojl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkfsnvk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsaccka.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyetbbn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2btutabjh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qmioydhz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpibcwz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnmggch.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqapaows.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2glgvavsm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2skpzerod.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfzcrwe.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikllfhxn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzdosle.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2saatwlax.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vrklfgdy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwgspho.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oxatjrtj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmisldzo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyztbgo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgltcbmy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xnogxcyc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzytjpe.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdcsuum.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vetgpeon.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2adralayl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vticezyl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiypudj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2izfzrtkx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pasmttcl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgdyuff.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bfchgiqq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjmjmsk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bmplgzoo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsxmxys.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2edmntycj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaraoud.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxcoumr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vtivpjhs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2svqvwpsn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xftdqcno.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwsfebk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpegqist.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vlixzoia.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jntxkrjg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhnpiei.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2atfvzaqy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2upuwbjql.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2upksheou.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmsodoo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbtljvp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbriurs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2glkpmvcg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2scrtnqxr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqlzrmv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeijxqs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxogfxk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jltldhpr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzzwzzx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxkpyey.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2eofsykjk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2spfqbczp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgmtzbm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dyneupow.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2edcrbdyk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kzphnqve.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpnxyqg.html


<!-- 参考信息 -->