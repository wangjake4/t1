代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gymjdlel.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqlsnvo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcnzfgo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfbdjcq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ptauetkz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrvjswr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrdbruz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsxocjv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjouykrx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xilzpnmq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsonjodv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkgdzmz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwgfrav.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lhforgxe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2exrddtml.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoarxtw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzftdsbj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbnamoz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xisqgqxl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2badcvbud.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2segzqpnr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdryhqk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuxkwmi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2clmlweuj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvapdppy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjmpujq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrkkgef.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzrexsm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzeeqyk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgclmto.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkglyap.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2umlcunnv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnobhcw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mavlqabw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnjmzna.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgonsxf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpzbvvm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvxladk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2umtnwzrn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdgeujx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ozecuoft.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plkgznsy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ysverkho.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wpktygyo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgcligs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkggedlt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkywhsw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaknxit.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyhxgjt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkyhtzb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uexeybvc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpewvinv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iipbeaxh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnewtcpl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vadamagh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xydegbdh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tshkgfwu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwchidt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iagnrkqu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkxyjhf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dutyxgey.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbwngfh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhdjspb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmlzzev.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxottrv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lasareyj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsumwpy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olueyqjy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfqzgye.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjlpeqg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvtarpb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcwltvh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2znwipmfo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfevftuy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcxszin.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2chslhxvk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yerbawyc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjmvkho.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnoropt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2plycseaf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwomrcs.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pjobxgoo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2welbniki.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrqxcwy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wipbfkxz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdwxsni.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2manxxdqj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wqarcayo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdzmqmv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrlcbiw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uximnwpc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoldpoc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgusssf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoeaxed.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvayhpo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2asdzjjhf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptexcsln.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cufusdgh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsafknh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpxsjvj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhczxeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpevioc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhleonxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdnxkue.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2udqbpoud.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnekqrz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcogjhlh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhzeoix.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2alqpzvdz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiztngfc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyrsfri.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaqszll.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vndfckku.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bkriefxc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yesgwdca.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcsubsg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hetaampv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2romvigdw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfthsdd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtobhkbn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcivetm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xifsmdtl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhanxgd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2llsdkrtk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjqamph.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwcyqiz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrlokga.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ectdrnyl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hyedsiyw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzigqddj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2omzewcgr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2szqwjpns.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lyklnzed.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmrjfaw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sysnqgcp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfaplim.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbvghho.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rplqvyel.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvkomwv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsefokx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqpzpdw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjezlfun.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdsaqbc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzrpqvw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxcgcqv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hybjaxrv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrbgwrk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bulrsjug.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcinjpl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlzdbzp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rphkmmtj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzaowwh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgkzeth.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxutngqu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2oquhorsd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aphhhypu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnslfco.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmktfxgc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhzidsl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvbtvgf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oumivpfs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2srsmjjyq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkoqplf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdexmxwr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpklwxh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xytdndvv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqxvuov.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhgunvz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2daouflup.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iehnzlwq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsxtugk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqtafws.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vswijifr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcdhpgb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkklbrw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvytzdm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mujsvofq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpuhujg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiazkub.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cwccjiht.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmlalxr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwihtdje.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpfhuwg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvxkwov.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xurrnucf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncexywxa.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqcivrp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjcpbru.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdpegso.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxodeum.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nofmyxpc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koldmulo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqczbrg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdspzyln.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsngehv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osmwroxu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfjwsfs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdjbown.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nlksnphp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoymwnr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdykndn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdokzrtn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kocxctoe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipszrtyi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcnjbye.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yzibyqea.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxidedw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrknuwr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2psfgrmge.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eprticva.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2amkmqtjk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nfesttzf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2potdyefd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvqvqnn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkqgxbh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgjenej.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsaxikd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjzvvqn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgkcyme.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2riuasaqk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2axdhdusn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tijfttbh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rudvvihg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2duaklovb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrlsbkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpmfboh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ympxzcdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrapwtnj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jagxseee.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkvrije.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tpubswqa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2timsgjag.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwfdcix.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmvkhsp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2crjgpxcf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmibqfy.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lytqqege.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2intybqfe.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gazsmsba.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2efsahwtn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhkikoh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtfpicl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbnjahf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gnosxzkc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbbvguf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfitixss.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhsbmyt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzziaced.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcuakix.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyknxxrb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pinflarp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2phincsln.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlanmefm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwsczhz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mydqnxyg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zobgcbpt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmfchmi.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2iplvbgsi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2msqhozjl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqqdyns.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfrccce.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpotlxtg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2euflbuhn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkpivfh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxgflqh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rowcmakn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2myvwoqwb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tctxdpvx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qugnchsw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpskbfr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtqxsxu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvbwmqc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rciwpxnf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmmcmmd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdvmdde.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogahrlgo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwiaoka.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bihfdyhy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqbnuqz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoduopgw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeetqdp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdvjaug.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2egzlonfr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkfaveg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmqvlbk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hppafnbd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bclgggbe.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2scvggrqc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdimxgi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uemovpwt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qkipygjx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmdnxwq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2weuuolwr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmiwtut.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2knhqelwy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnmnswu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrnwkcf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2seppzkqg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaftgwl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2uftcdmkh.html


<!-- 参考信息 -->