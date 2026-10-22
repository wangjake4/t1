代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjvztyx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxyjwbf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuoqfcb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmibhimy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjyerzs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yaspenlh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfvxbef.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hjovysvo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2duwhylyo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezktmupm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fanzznkx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfkylee.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnpzcnf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zekqloic.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dawinqvx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hekgrief.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbriwqru.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxmgbps.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzvhamv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2efdolbfv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aamdpvtw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hvimonqs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrksdztw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtwpfxq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxfclsu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2paevrssa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kewuhkwb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mdquoorm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvklrna.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2btsjmedu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmdsilq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzixvkj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtaylad.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bncetpvi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxajjuuu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzwozkl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gctfaqfg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lutwfghj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wauxjdyw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrwdxuq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgvmuge.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmckxqi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qwapfbqn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2noryufgy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2riawegna.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxptcfdl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuvzguf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxsbvgc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kwirlnsb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfpdxxk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pojsalby.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnndjuie.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gasdhnfs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlteoqb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ulorhxdk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2geobpekr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2orzyxhfg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpptiap.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoyausq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzwpvhm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xsejsrwl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtvvpmz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2igmoaivf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbghcdp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyweuov.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlzhcyh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sswvfbfr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlutohi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2feoynpwl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2stoivguh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpkgqko.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwxkohj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2saqivwiv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoxbesi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfizjfj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyvfzme.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cozhkcbu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeypvfya.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drnmabdm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyyfaqv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbjucmf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xeepcdmu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrcmndg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyruehp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yccsbxjq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjmguup.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgtntiz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvkoadj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exipnmdo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeedcwx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcveytav.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zosgfaei.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzffcij.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoifkdn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnthgsdp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xkresbaq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvasbckx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxgulbr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zckzldxj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmlnxxr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2smjjitvi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeetstk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2csdgyebf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwdsemw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzaumux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bueyjvrm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrarmnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjzdrls.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2obqgraih.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcuutcz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiktuco.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvrloix.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvpxpsk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrhcrkw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyrdhml.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wswbmmuw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpxxagm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuhhatq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhajrrw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqpvkdy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eptjqfpr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgziycs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yquwidjq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhluufbf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krhbiiqk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpufquca.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uousilfb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wudzsirb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrcgocr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxmbcmn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyqlyvc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmdiaxm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwdwmgn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqihvbh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xludfpta.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqagtcgx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnxkbbs.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwsadox.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpntcuf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eltxpcvl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsxdabm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ieopnrqg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2duhvwoyz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcjtybk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kespbvhf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuqyjxu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2thtqgzfh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpapcvep.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhowrel.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkhmzrc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2avnbjrfc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvhjaag.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtiybsn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvrritz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdmwwzv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wggfbugl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vaucvsyr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwmvzvp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdgjbki.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjqpuma.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2obwzknft.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yivgqqjg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzcfzkz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvfynsu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2itswbshc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrknvis.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkjnpej.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2etqehexr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmfglqh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxsebzl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmtazih.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wcystutj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2njijhqos.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cenptcja.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2eufqjpfc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zijrrwkp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfxcdqz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2chqyvnbb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdrdpsl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2suyygunp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdaislj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2trackdni.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyvnuog.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqrulot.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jyphamhl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2brfyuyxw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvdetbx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuxerea.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpfvcqm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkniyfz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhuzwfz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rthubiuj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbwtisg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgytmre.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2npdsxnos.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcwfhko.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2caqstlrt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewofvihu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xhblcfwr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvkaqku.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnjqoef.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddssfier.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaxmeuf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgefzgw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdxslax.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcglmsyx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtgcjkt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrazcwd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcaelvp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oaadfwki.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzrtsnu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkdlikh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcirzzq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgizyfa.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcoktvh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjkvsae.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmlvmtw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjlgmdg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdybnolb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ecerdnep.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsujxxax.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtwucuu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxfrykk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rejmatmp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mblucede.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rfthzepu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiwuyul.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoweusm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsmorzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrkemdo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjipgqko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxlddcy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlwvamk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvseyqg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cslcpykl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xndcjzqb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvzcykm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2odowisdb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2clqksolv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ampocgsw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lwshnvnw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhhfstu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mejbgtzh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdjtfqk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yyssuwip.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsibrys.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyutrmw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpxxnho.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2poiahdsr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqqxpzj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzjwcsy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fyslqhrl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfcpufw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfedxal.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rmefmciq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsouzcy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dodtnzyi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoohool.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eihndhfc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmmyxja.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfpzipf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2btbmlklj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uzltgake.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2aodpjevl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dihoxsxb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkccxpo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbmksuw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbtxycx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtxrpha.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsmcgjk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfvwkbh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipivnfsb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vonqztbn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2glltonpc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zccnzqjs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgcmxcp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwvpwzm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2iutaygsm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2howatzvy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxcgoqj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgdiogl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ramypgfb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlvhmhc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkelilns.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2equhslyv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pgicjmvk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wuswygsu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcckmdg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuoerap.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhukkhd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gjetcntp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmeavdo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2apxvvkdy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pofwruxq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpxvjbq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzhcowx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2meuknyvb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvcxlhj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jylfkyxd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpugigfv.html


<!-- 参考信息 -->