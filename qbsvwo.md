代发 wailian999

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmewlct.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cxywspsa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgiynxn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pujvvvfp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxkawcq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vqttwjxk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jklgtpvt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2htnsjuze.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eccikixm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhkhwkx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2oteyuzbi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwfmxts.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vigstcqr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjfxksy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhwbuww.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dbysdqrq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmghjeoo.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2klzpnlki.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtnzafk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rblaktau.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxgxwnj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqejmqpi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaywlvg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzqowst.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoeikbd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeplzdx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuaoxuq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzajijw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvvwjyp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2icbthbqx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmoqosz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhxqhts.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2clpljjcl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eydxsbvt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwvjjmb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fthenwfl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ckphouvp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iefnrukp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mumjykvb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsdwpfh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvujtwn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtocevq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xptmunkv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iacyvmqb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2efdbfyky.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bislpiqu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ejayzgue.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2atbysnli.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oougymid.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqyintg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpngytu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jynezmmh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjhagou.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lixvpkbk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdrxioy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zovenoly.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrshqwu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvvfjqu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lbspvqhi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duibjnyr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2sndifstt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jnabiocm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlsdbst.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noisvirg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvfmkth.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjchxybd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkmgppu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2brrzaxyv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2geojokvx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmcwcib.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2umlnldgp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ommhdvdt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoxssvv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2goqwxxqj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yrntxrub.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bheqsoop.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnctejf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yhydufkg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2adyyfkih.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhsxksw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwikxab.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqsszfs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2arbhxszk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gtecifhn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfnhijc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eugcmjvk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcvmrpm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtyphrf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nusbhjaq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxjbsws.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdhiivd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jntjxhoc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2whizowgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzidlitt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozggxjmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2moauxjnw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oeleskrv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2chsbktku.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sisgdtlx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bptzwpxl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2chpvkpfb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcmlxqs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qclonnhi.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ieylurfl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfieacs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yigkjsbw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqdsbzx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kambfynm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zinhinkd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnndlema.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqdximq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuykeko.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqftctc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbktuzr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bckrtbyu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkrllyz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2omwuaeki.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdrgttn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gthlxmzu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiirisrw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2smozufls.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnljunwk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrryjxx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgziuogq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2simpfrly.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdltquia.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmddrzww.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtzpmvx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnyilcq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkyonzy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwkzbqi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2efwntwlp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqydmrg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mppqomdz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsxohva.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnxbxyr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xupuihuq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtenjuwx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrnyvwh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfhchym.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkdgmjg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwczbith.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoxgdli.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwnzxsp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxrhadi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjymrhyb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzxwqiq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyrmsid.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pqadswjm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2slzepzwr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2joenhqwz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlnqsrc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbshekp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hghulcux.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ivljvhdn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziplsqwh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgwfpsy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2liumkckc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mosjbkvm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcgmeiq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqrovuu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2erdognfx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xokoajvl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgflfbd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zrweftum.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkemwhf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lproefmx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2odxnxgbv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhvqjxj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rovyopuf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2klqgcfwr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnhmqjk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqpazas.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnkdzym.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2asfacock.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dklyeegt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awsulqtb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuhhshq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwusawv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrkxkul.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zajrfzse.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bblbrktg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lziyrras.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqotjnbj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2igxpyqgb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrqoafj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrbjkfl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqygxpb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2arbaypng.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuftneb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuvkgjs.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaymfcwf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2untpjdyh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xytqvfuk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2guncqkjp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fowhuewa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqldeun.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2muqzzxdo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2orbkdtbx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrpadlq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ciztscac.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rylkkiyk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlotdfz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2smkqxzbr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pordehez.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdczeqj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkhhcrg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lysuyvoy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhfjlbl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjigleg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaabyvh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2njspyall.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjgteoq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dwixyqgj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2plxfxjxn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwozoso.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2stwwzblt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uijvfpbk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iunuyxee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqzakbg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gabpsqag.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2doyewhfq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxtptgv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qpalxanr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iclutlep.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2unxfhhay.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyfhmfb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fiezubka.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmyghay.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnzruan.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2veiqekof.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rifhdgvb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2aghqswfd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2oebhzdvt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvktsok.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2klpijnuu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsrjxgz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcexfovh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2skuylyyx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxmqksf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhqukzq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgizjiw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjrmjiz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrcsoid.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpircoz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2idqlemqq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzuprqf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2chgvycch.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nzueghhi.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcyurvi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uigxbosn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2juatqmai.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxxztom.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzrcnfb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2opxxkokf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdatkhiq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tznazbix.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2trjaisbo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdypfdi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuhvbqw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpddhsb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzjxobu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ankhtrpw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzmtdeh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhihpvu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ywamutsi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2shywoeoy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeynpjdr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sssxwecd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2auoxzfpo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqqxieu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2altijlvm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2uyphyhbe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2grtrbqhz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cklrppoc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hioihpbg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfdxoda.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tzabgapc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hmarxqws.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcrzztm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wabefsmj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkcxqan.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsjzzjp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2knzgdczo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzjzvfa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2atfmfdaj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ledfdvnc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhulqjor.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdagtfgf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bueyegnb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhiipax.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjcqrff.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkizzoo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbieyxt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zrskxqum.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnyocrn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2welzfwem.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2asqulfwg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxsgrsc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnvixfn.html


<!-- 参考信息 -->