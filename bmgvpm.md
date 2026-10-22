代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwasoxy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcwwasg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xikykwof.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuorupy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjxfyrb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oseuijbv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfcszsr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhekitzs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbuwjpl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hejvjqgl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdyntwz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nliuxemb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxptevpm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xwislqaz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdzdeld.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fibtilfl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhntnciu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwhpdsa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwxpify.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bdntnfmk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvmsrlw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rhogknvh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqejpmsh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2otxnkkya.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2otrshdaw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kenotlsy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cahvarfp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jltdawlp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdvqzsx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2womqjxfe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqxwvdt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2faknyctf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hepjnxsx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2calbkwnk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtrpnvi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lekpkthf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjufytx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgmspmp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2oylzgfor.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvrhajm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhdpokl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpntdoh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuyhsmo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hipzjrbz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzxnuvo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwoijal.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjrgszf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cinbszxq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xayrffye.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmkwqdi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrhcnxz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eavqlzfp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sxggqnwc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtbhqvc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2whdwcfgt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrwtuew.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vumkrmui.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2typyeyqa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nwskfhbd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wakjuqkp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyuylzx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuavctkh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhroodm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpdzdud.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uolorycz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgmgbwo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtkpffs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnegzsv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzzrdym.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpvvuih.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ecinkgtn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2munmghtg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxrjgec.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2huvwzudn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxwzqpm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfqtnmd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ysavqfxr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpytdxl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xerlfcoq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asoggnqu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzsnmoh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbhzkga.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gctumtbp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psyzbevp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tggfvacb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mablakju.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crfvdnjh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2drmopeqm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sibyruwq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzbrjcb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvzsdev.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xemguddc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkyrfqi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiykqaw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hteqlwbp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxqoocw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fokcovrb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsfzpqb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2advbvkcz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iklcpuwc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bebqguow.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdchdka.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2chtfjiur.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jawxzndn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utjvxvhx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xudqfqib.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2haxqrozr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gydoycdb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yedfdupn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrjqxxp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2teljnctc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kkalejlr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2opahiiwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mslcdhux.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sejsdywj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kafcihbm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wugkuqnt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rduljbbm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kprakzyt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuuvvcw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oqokdxfy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvqdehb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uauduznx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmjrfdg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrhicty.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsyoqfn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxbsmcl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2khxvmzzp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvdzhdu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfykssmx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2laryshdc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuguaocu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kupyphup.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2knehqoxk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcbkffk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2alldxrkc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2exlgzdol.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdguacu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jpobymjg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkmyukl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2acuignfl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eanxjguf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fjscuvey.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2krfwbzni.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhtdjrj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2flcpggma.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsgieja.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxcsxal.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2chdggudp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yuubiich.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dlozgtlp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2anpqgucq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kilikzys.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2djcwatxa.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2redrsbnt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxfdfuh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nszlfisf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsttmbo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmtmqut.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrqatta.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2excpkune.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqipoqs.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2izltowzq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijluqcgn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2abrirzut.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2upxjgpwp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtbmtim.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2naytvlgx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqefpnt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgqmjhk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2woqupsvl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeubwdkt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2urguvqhe.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ontwmpel.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kabrzppk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uclojxyn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rpusqsta.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2stmhbyxv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiasftr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzbumtc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbopsrvp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2adrfnkrt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvtlahm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kffqbgph.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2epnudisl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2outffafx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqmqzqm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pecsjgtv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgkhrfe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jakolril.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcmpqhh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbnrjix.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2znfzsaht.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykicugpb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlatptv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gumfncar.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnglplg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuplkey.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnexpqg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2saijkeyn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbewkcy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhebvpov.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zintpass.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzublfvm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwyiwod.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkgiiww.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qtysmsme.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uepgdkvc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jihwbttd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yesqhbtg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vcisvajl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2plhmvxxd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgewztfw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dodcecbx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuixaal.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdidbnw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjapnrsj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjkmcwv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzldkav.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwnwjmq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mawkypbn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2epjxptiv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcleryj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2imnvrskb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2muztjcgp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjcjzon.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2taconsqd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsmqtbm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrwrkdo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2txunerik.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpjxvnv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuioqxc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiryfmm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bysyrpuw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdwpnwv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2emktfxxg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpdeiix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgdebcv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqirqibx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqxwxwm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxhuuvl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmargaf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwqavcp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrxbhwg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2srqqivur.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmngxwvs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wecwnbfj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjcgvkd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfzhetf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvajwllq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rflsmwio.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cklqoaev.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxtrzwp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbobvfkg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lddynwhz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlcfjaz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbzibfs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwoqumg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mqglsjoa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2grxjfxbm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwgmofc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnmekal.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2znbdzuhu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrtemzt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpseyebc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2eliulkss.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdfebsh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cocuhhxg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsnshcp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cugxhegh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2veglepkh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjjmzzb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2moxjfozh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwofkzr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pebbgkny.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaddocl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nlraliez.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvenstjs.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fyystyyr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2panafvcd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2njekpawi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkbcyjl.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jynjtrcn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fymvcfiw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2seqrzkls.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2aizqkmtw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ywitescz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2edwbzgal.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dpftbrdz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnodxzm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrxuozp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pervhleq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwhcxei.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2adzqerwi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2elscavfm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfmsupb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgvvwpm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xrobbqnp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpzjsjp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2byoasbqz.html


<!-- 参考信息 -->