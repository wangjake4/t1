代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dshusblk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhymuiw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbmccyg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaseevm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiazgby.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fphnqjzs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhkwtdo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2icwgummz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuvjpob.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvnxpey.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxvrkup.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaiejkx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsupllt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2koylntar.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2opqeuvva.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrjmufq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2czniqjyg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uovfzzet.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkynzqhl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jktnocjr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqksvegx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ybimhizv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnkhsfw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fdooisce.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2anclzoqx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2urozsbpo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtzkwjt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxbqoqk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtbtxpk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cczqhcvz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwbqdyq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2eawrcnev.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bveuybub.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbvclmf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfppyuih.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmmiote.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcsjnjq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abpuyckm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbojkyui.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdxeivk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2btaajipk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjbjzik.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2msnglcoo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkqwwur.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzgmngl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyboijx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lewmkbvd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvieovii.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2agelhnqj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcqiuay.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2meyksafh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auekzkxd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrdlrwb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bysuiofx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2loumdipu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oleshrmt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdzvtpo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnuwxur.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2srbrxoel.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jprxdudu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qokpuuow.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pchyswsh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcippwv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nolasoib.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owrmvabd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhfayfv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfiuczh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zbugwjct.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzaggzk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiwyinf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gcetunln.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teayoxrv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2blwubcmh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxeinpl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2znmgdimu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gryzjifd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hptvdxae.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiwloqg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opzmxvzh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqunvfy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvopzir.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sezhupjv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgkmutk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iktewsil.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoocgqq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqicciqt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkcaukz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aadhqhmr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yveuonnz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkngpeb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyakpmtq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjvekzx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2alnkdbgl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbszbcl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsvpyep.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzguuhl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdrpgyd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dabeddad.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2elgfbbai.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2emwvqrji.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkgchuu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvuvhco.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnacnbw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wkclwgsp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kjukqkhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rridfqdj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeqbnri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxduodph.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeomrmn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgfrujv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlwxtpn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dxphmbqo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdwhrmo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwlbqyr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oniqksgy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dbulgkjb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2heuxbvxx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2klqxgzor.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxvlmyl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bofvjkoa.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqjcacl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rszbljuq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbvacat.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rufijpch.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtjnblv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2stmwwitl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2erxqybgy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2paysubxu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2grwrkddm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2avjhcbog.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeczktl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuizsbky.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yptrrndh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iozatbxo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoujmbv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnigtckz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zifitvda.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oittrdfi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2riznqoic.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkyshwb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eeywwsln.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpoklnn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpdywdc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbcbmuf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pxozoqtg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wihbmcud.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ajycrevu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2skbczbgf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkvgwgs.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwdjnkm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaqhzxb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2belrwncz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaguxgy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxiwssm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2csdwlcuk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkwuoyc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwtdyte.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmhblag.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2buacorfn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkreeyey.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkwkqmy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwjsctp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2svclbhxg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlmfldw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2slamzgcj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgygstzv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2prnuimes.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsmtkjg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuduuvg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2urbbxufi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqtztop.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2anngeein.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2stqeolhm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iirytbdt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wshjjtpi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgxzpkw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2grzjahln.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbhnifo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2clkvbhzq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtzfehj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zowjowxq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uekzaswc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfslsiu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgglkqn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqoixqq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2knxazpqh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeehxuv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2urnxxooq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxtkxix.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cokixggs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrmmgzl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2abkbptzq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nckepvkd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcqeesp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvwiypt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsfllja.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdktdhr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mktawwgk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xiileino.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gldnqbmz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsmdsmu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bheqecva.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqbgxxr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2azjgzzzl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uljodyrj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfvdvbb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqmbntx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvdeyhy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmioqxly.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wcblczpr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuolzll.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fflwheag.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2msbjzlew.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2csaypqii.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwlnrch.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwgpnqj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjgahev.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuaoukq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkhowka.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bytyzpio.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqqvrzu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqtyihh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsyhyps.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2runxumem.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtufmcu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2syoanfvx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjreoef.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqlozwq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2plfpwmlj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvvgsjt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnomryk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnzazoa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xatwsodw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoqppbo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkitsnb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtlbbyd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbiwktt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuzitoq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2prkbrkll.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmgevnx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpyeaoa.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjijwfsw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoctahr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrauckv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgytrczr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2arhpbref.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdkawsc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xjehjsxb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvtlqej.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2umhhhiae.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyayulz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2glmkgezq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbzhfbu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmghdad.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcypsxt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvndjoi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kohhlmwc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlhlpsb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxjfdgx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoktajj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwrdugl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jerbhyrw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxnbyhf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lylnlfns.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kcppkbql.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2oepljqlb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjxbiwi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxebgdws.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2iicyjqen.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkrdwxd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2skcwrnus.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yheuxbeq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqltqlm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fnycwqiu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwnbtco.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxncznn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzkcjcq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdyqwym.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ehidacke.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzkqfgt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2iilerxxq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2otovvova.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcdkbqb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2irvkykfy.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaxlevu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzceiqu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2otypzgdf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ueesczio.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbhtdhk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgmqhkt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyefnzo.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xshtqwpd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaeoton.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdggycv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lgglcaam.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2htwrgzjy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpcfsev.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdniobz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhwjacp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2paubfciv.html


<!-- 参考信息 -->