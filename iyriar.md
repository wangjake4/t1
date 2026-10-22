代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvifnkrt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoudkdm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zllsqbrz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kilibosu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvdaemh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2apmmjcsg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnaogyj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuygcle.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpjjbdr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jazjyexx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvsaihe.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuqgjwn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2peihutxg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxrqahw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyqmcca.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqlaalh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2unwlvuag.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2indrfqiu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcyyqvk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2enyyqsdt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwrciqj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrmlirh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uffztdft.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2liikuixz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjftnty.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqamynyz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gizhivlm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2upfrlwmi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbiakal.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqljlty.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwghwme.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tlouqljx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2myrbnchk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcelbjnb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqkzssq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzposhmr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoyfioh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuqffng.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyvqbov.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfzuyxu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tvipxkwq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ampunqkz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2eooaqocb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2grbdjftq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmmfvrm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvflpmw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iplqizpl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeopydp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhpazqw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2whwyuruv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pbozsnnt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfqojgu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhqlehq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2grkdafyp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwffosq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cccvaesy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2eshxupun.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkgwfkm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2swxetjqt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qhajhqpa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ahahdfti.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2oshbtngw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnzzuui.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2quziztyj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnrjgyi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2noymynnj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2snxtfwcn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wouquyiv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfsoorv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwqwqsw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmmuoep.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yktvtfau.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzzefrg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2slwiavqj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2acyujtjm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtnbqhr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiteaak.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdzwaug.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rngriguw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbheapy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2afnjbgni.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjbflgm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkiedct.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxsamsx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjebiiix.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmesahef.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqdrtwb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jctmvqfa.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isozbvls.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2djuopjkr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmerycfb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uckpnnyf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lokrhdcb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuwiplo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2orzzszxt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgulucd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbopqqgx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mazxocoq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhwwlcu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjxtjdj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2trzwebor.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxsakpt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrfghqc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqkblau.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjnbplu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twhowtxo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2noarufvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jofqeuoc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ludqwakc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfhrsnc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuiqvhg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zwovffio.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bilzhztq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gapsemvk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fswspbsc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2okkcjdfx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmikcnz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhaqukv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbvnhue.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyxclqs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jtolqims.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmduorw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgzesyo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcqofzw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwzsetl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dotpwhpn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vribvonv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaskhto.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyryszq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjejslbt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2exyiolem.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxcpjso.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbzcatt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lotlryea.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hfycoudb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsrfspt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2orsxctsb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zziwmwwj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yohhmqwz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvhgtxe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqdbpzx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyzaapp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsktegb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlxfrit.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgqvzpu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2korlpsys.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gltfqjpz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmmfuxr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhilpgu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dusqntfb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dseppslc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbvgste.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oltvxdul.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2udzfzqfy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiiavcx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwunbcq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vfojkzji.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qonhqoch.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dppylmty.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmenwjsn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vmepzpch.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2caphdrcs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2agisdovt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlhmods.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2exfrlejc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaboafp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2honabntu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgsbesu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsnkfym.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsvodgx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ytthoksa.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtihjhu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nobsmmxj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiwwktg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cewzoeky.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrfllwz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2grlzzugt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ndarfofy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdslult.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvktvqi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fayygbdg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lojzkptr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2djclqpuh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkokyay.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvtvmdb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2efdirjsd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmfkhka.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2adylewyj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uksghsqp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjzjion.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbjidaw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpcvpuf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlfnoli.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvlvcyy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2otepoagv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pezkrqne.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2degmvpkf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhfgznj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ganqqdgj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmhplmh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2anaikgzg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxktpvzm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2skdvpknp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyptetre.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxrumxy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lttecjrq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvgxrzb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2esgtbigx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvupajxc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2odmswzha.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljybbcaw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2clrahaye.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jtopdhsf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdblazi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2idjwykfw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuqklno.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoyqnyl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lzztezue.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdbkzbl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2enyhnbda.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vewbtwyb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwiknwb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfomngjr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xwocugyi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlwbknb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dryxbphi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrgmcwc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pddmbrcw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2odupxqht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugczhhst.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbxrgfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnrcacs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxfogkc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2iydkkhsd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoywbgw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jhursoie.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xgivcoiu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2obvtveyy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2foedzbbv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2klqsatmq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2htqgpewd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxjrlxt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlvumzb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiugxoh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjhkyrt.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrfaejk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kndcpxyj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzfreyv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jonwmbmn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uywcfnft.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ayshcqyh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2grxcwyqj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2axkluzfj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yorompss.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbnfgqx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmredui.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ktahqygw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfbjcig.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fndrvikw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhumnhe.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbjwypl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqxeywy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nytbaqbn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2omsjshgz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hclnyevb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmrelak.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vhahbhzw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kolcnprj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fphotgwr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2flwxbkpn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rivlzjzj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjdjreh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2teokcesf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rwennplq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lceludtz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxhluog.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmkdvzi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtrfmwf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrwpyan.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtobxlh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjhtfvc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxfnvsp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jimgvmgy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2srjnxsdq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2pnagkktd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkpbtop.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzqfrha.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2esuggpla.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqnhqqi.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uczdddjs.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ngylxnws.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjtjkbq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xfazplsz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2irqhcmjy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2whtxokuk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fycmwbze.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuigucf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhldche.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2shfrllqe.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2sawfzhba.html


<!-- 参考信息 -->