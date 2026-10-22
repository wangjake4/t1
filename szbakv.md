代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dblumkkx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsubowq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2crddrapo.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwshprqb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2erywjhqn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfwsqfb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zykuecbs.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfdxxst.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mykcrcdo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzwoshr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqfkqpb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yetygrvo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aevkyecp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxqfmlb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vijeuuqd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvynfrq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2patjybpr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2knqzashp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtvqmdt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrjlqgc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwssxgm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuagdal.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2idbwwxsi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeogbfz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmruvrf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmhlywc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlvpnbs.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2famfrjur.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxyzcys.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvnomtp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvghrleo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hdniivcv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvlyypt.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vquciyab.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2atazounc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uozdxvvr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgwyofq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zngcciek.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqncfhnk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbjfhay.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jbthmbhn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzuvdmz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cflysety.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kymtunyf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2suxnmzoj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hckvjczx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eccxzqhq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvbnuuv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwazdux.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtpkqqk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lopfqqoc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaafrys.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2raedowfa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2livfolof.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrjvprk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2numfvilm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzjglyi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnejabgp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jslcfsym.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2frycrkke.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zpglopze.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzpycep.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vscnaoof.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmryfsa.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfixgtji.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gugitodt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjstobbe.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjxsdvh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2eljqvtfr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxrqlia.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2oymyffoh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wewphehl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jliaphze.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbaczmw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wprchszy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynofiqtz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2khweyajh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hczpjbfy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oncnqqpa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkreovr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqufwppl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2msxkhevn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cwntazrl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yykbpuqr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gomahzfg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlprokix.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2talvtsmp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkctsgc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhicxkd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyumzcx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2htktrukm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxksnrj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2isdgvusy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqtyqjs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfykvcp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2acufivta.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrkjazf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvpmbyu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2darykjeu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnyzcqj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfnocua.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxwsmlz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qojmlrfq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdnargs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jubwuhzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2reiuegyj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbnpypq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eciyizkb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfcssny.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jelikkml.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjcxueg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2emuhcesd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qfedjpkq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2etoxvkax.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrvkvji.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzuqwuf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aksukzsn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uddhalze.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcdgvnb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuqylxw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2drxwvlow.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2blzemkfa.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzsrpto.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgeqaer.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnccoxrp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sovoflfx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2srrccnes.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlovvbl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2juaxwppx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxkxfxg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2saqpprhd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iluhvvtr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yirvnnaf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pagywjkh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2trodoqta.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfdbfja.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2haerxygt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzjxyfd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bneqtlzf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfymbye.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbufshy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmyvtxq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2povasuaj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcrlvxl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfhfdsl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jevsrenx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlwnwgt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcjlxqt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwubesm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrnujlf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qdznhuht.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iurpscne.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unooljbt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2slbpitpn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqflzuy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzinleta.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuvsiio.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpowtgi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gudcavki.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxwhnjw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wxghxahe.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jywujjmm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2stnwuwes.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vieyaqeb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgddkud.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnxnfyt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpszqun.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkneqkmq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cvduprkv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxjumfg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbvmktb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuwfoqb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzakntb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqrrwrv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdykhso.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ewenylhn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fytmjkog.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaqxees.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewueuvlp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pexustjg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdjylvx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgwtzft.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbwrgil.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyyoytc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrytofp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hylhmtjl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrsrzgj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tynjlscf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kllzyiek.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wikgmwsw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjiveqt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdbzvoc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fleyhhhm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsovznal.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2exlyhsoo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xojezbop.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmmczcc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqelpejv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kiitvegq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icvexzqi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuarzda.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfidbnh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gufjiyus.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxhmmjg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfpgqms.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmoinyc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyojbykl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2btrmemgj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhncsnpq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iawstbhf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrgoxrg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiijncp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gezhzmya.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2evkeodvf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsqonry.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ylopbaof.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bztglwyh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzvvnru.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edqfjsvz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuxakrs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aawqeiir.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmtspvp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtfuuda.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwbkmca.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vzegfzaa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkgkiuu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sstklwnd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kaofjxfw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqdahpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmfflwf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwesrqno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fuklmneg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gccsjkjw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgljija.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2clpekbsf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjatfphg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nscqlhnl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lafhjkmc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qqylklre.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxasatv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tubkdwfx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2egilqhak.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzkluyy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyxxxlu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2whkvynrq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgllbje.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxphulb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbykgcpf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nnngmwmx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2erliyhoq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdbbock.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjrwuxp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcefprx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aktqnumv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqmvcpp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzaiyjq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqsgqxs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmljbdc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmgslio.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2texxmywh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlinimu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrriccr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnuleja.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxsugac.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgevyzs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlwydse.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlbmhqi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyzbacj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoihfns.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbommdq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bowobift.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2givdnzpm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wcugmlad.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2prfosxwa.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpprjpq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzkzdpk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkysmgzg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lzomekso.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjhsdhe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2swxroaax.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xznmqpaf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcduxmh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xatlkeyi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yogwjqwf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2iuakgpaw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqelfnj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaytwcg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhswsqx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtkflrg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuddlcn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmqqwmv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wutdbsur.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fywoaegt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2eripzwka.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjkwwvw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cstwjteg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdjqgxm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2stjdcgpd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhrftfc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfyhdya.html


<!-- 参考信息 -->