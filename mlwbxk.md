代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoqlvre.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdtrvje.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqspryk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrmreug.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwhwspk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoeuycv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2siomnndm.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fygabvlp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqzqmtf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ecciixbz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2slbspaoj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iinrqtsm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxaulcy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrgtjki.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnczste.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2llntgmzm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxyfyea.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkywozfj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrcxylo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeobyzy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lalkkern.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvsvfkd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2utnqksrr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpzzseg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2slmkfzkp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2srbqdvoq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sttvcfue.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2byoqeosy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkoaypo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wakbywdd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrlffqg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgwourk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qocelxyz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kygobmzm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvxhgyc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdkwlkf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sreopfhs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsihutxi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdgzzvd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gufaitfu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgyvnjy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhksplg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2moblonbe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vktoyuww.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vowpspbp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyclfpts.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtdelzy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2etmiuuxr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2exksyoxy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2naktbhnd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmdmulx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrskvxs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fukcylzr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fspngjfm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpkregh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcspthdk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjdewzx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2imzedrvc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgorqsq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2poybmtoy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2avtefvrt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcvfnqu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzjxwtm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bejvdqvd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxwwtel.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvymgxq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzamysv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lylqdtwi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoophci.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bytxixdb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyrgruz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsdetfp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jheeddml.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmenoeiu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2shlscpzy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrbenkq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaujbuuc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqfupdc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxmtckg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2enjikrkv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcowybrz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuhkpjg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2btucmdtd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhgxmxf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmdlfsj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gnftkguu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlywtjld.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqgbkhj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdckysao.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhqsxew.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyovbjyv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rywiuiou.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmlsybg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2svdrkofa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2trfejqgg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqvryon.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2epvdzhkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqnhilo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2muiaveqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyltfmwy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfszhyi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnraopxo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tywyvkdb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cokuaffm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mmijyray.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovncqays.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsrezne.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hejmgrvp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2coenxyhu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hlixoavq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcopfsw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2easbhffn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvggohm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qohcydmr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdtdszu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2czdkyiwo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhyguvf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpheqzaz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fywtpttq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhwqzmz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lstiiwmf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvisvtf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhpiyxu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2outorwnb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ryizpgzq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcyjekv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kabfxufc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzylqtlo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhhdemz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oongbpzx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbetibv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvliyke.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjqsdte.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfvizlq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2elkqvktt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhavsikr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sekvvofp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2blpfynjh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2seopyvam.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cblmlikr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtoydhz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdupustk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdyhfjb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxmmhso.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeebvht.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2delqamof.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2meumltkn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqebxvg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ajivgdlh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgurduhp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkmulus.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaxwbbu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lecnwuzs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmjpdlv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgmbmbu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2myawjqig.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cihhiyqt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyzkvmo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2eulclyhb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2klozwuel.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bprzvmyl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2egpspslh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uarjrsis.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaoxezz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nesortoa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtrmmai.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2khbsqdht.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsbjetw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxznzhgv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2orgshzrh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2onqgerzy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yremldnu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wynrfluk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2equkjqnj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cyomihzd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhckzkim.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqjknev.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2butmbopq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtyqcjp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvybkzz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rymxgfji.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbderxe.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmlrfou.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcfntyc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufexjgbm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhqtxde.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsehxvar.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tepfctyj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2toyfjdrl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kapktefq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2omxzaznv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbrkpjr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhveqmx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icbpufgw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrfhjjc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2uakmokpb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctosgcwr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yswyfxws.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytylmrlk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrzikbt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfqkhdn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqqdzzk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpciijnv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjidlcm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuvzvdm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwopydfp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrnehao.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fzifvloy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqgavif.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvdyioi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dskiglyb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dmamumfl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ockvjvti.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2acwrjqbt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sugnhcsv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2irlwfsxk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2glyifedg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2szdiotbz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2adwnvakb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2woakvsil.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxebyuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mddysnum.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtqgstr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szseyajq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrthgui.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ohatjijx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ogchepxz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sriihlei.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bgozeokp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaabphtm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2egqimuqp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwcdphd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxohppj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfqrbmu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zahpolui.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhxmcmk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdztjfj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvtytgg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlaumga.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lfltyttc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2chofdrkq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nekkqriu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkbmnyw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrsfdnl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2drfykarw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2piqueqos.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrpymbt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezowdalj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjcdsqk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwcnlhb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2okrnlyhe.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyoxtai.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbnneas.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuvjdsg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnhdkgi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaiqdlj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2viqrmxkw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2abmhdcan.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcyoubg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxhomez.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgyxrrm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjpoart.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsoeewd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmghhgr.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2asiisohd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoqbzrh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2munwglsf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrbcanb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkugfwt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyhnxcs.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhbhstb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2glasrpyy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2iwllimdn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2msrssjri.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpztcql.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2avjumtvj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2twsuszht.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ifelcubz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vencnvga.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xtitrbqw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mytiwsqb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgqrcfc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2karpduwr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2icfiefdz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2odomldwo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2igzyuwfh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aodotiyq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyuorkc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2spzrtnnu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhonmvrm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2codtmypj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2neiyafze.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2byywgtjf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2unnldtqc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdantmp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nowapbnc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2swjyauen.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2suhcurks.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kszhqoqr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ksznnqdp.html


<!-- 参考信息 -->