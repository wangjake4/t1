代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2whipqjmp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yfimrtwl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxcrysx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dusltfhr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2inupypdt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2thqgnpjx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uagshngg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyazwfb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkykkssj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vohdrfxh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpdpanm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbtuzbm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzxycwl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpzosqm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2igdfqmoj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lrohwtqr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aawamhwc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hubqvbsm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2driyuumz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdazlfox.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xljftank.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmqdmse.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsetmrz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ieapfikf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfgeohg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jztjupyz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvjodcn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jelwvzrl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjukmmp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsbackb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxuqbtn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lymttcfu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jybyuhus.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2swywvzjr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoetpgc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpgykwy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uujuazjs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvahgyku.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzfxzfo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhxqxny.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2awzxzbrx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqakosvt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2swpansne.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2edfmmpqq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwbvpzf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxqmgwr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcdlpnh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2czxhjhde.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nguckoam.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pebckpjd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2inuztmnm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vguwxqno.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfnnqyl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnchsqia.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkjguhc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyydxeq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fojvxcia.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ednnyrqz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lbheevzx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlebhnw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzvsbbc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaxhvtp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjtthux.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvgcvpw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xovpkveo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqehakzb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrdnykd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqtvpvg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sshphnqn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhedfoxx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2arwenabb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2atywwbdm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlswnyql.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2guzfodok.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwsbkku.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wlslaahe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeazemk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxzagpi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2smmpazpe.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hslfbgmb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfennjzl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2txvrvyan.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvkighd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uerohqri.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcegzer.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hakaqmdb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgwdmks.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmupidk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fknocmlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzsfcyz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqpumsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndktipfc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlenxgg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2acfdznck.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzzoxmp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kokebmns.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmdumnw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2juxqmzer.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ojylqwiu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqpjdrt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2umymohhp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkpbvnu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2glpweklz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2glftdigu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwphkwu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmkfevx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvvdapo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iownvwhw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqxkfkv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqleicot.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2urubvrsr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2isiqcija.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fghrrnlc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tycthahp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvrvzzg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrqdknk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wefdqhvr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xloaksry.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2reftppde.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsajzpgn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hbejgqve.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2acluewry.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzdiyap.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdymwfq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxigznai.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uayjxizh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ohraqgax.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2akzmpivr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnjwyrh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhhfxhj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bftenlwl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtuzqrt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bivlwlvk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmgwvzq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iuopqtwx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yojkafju.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhwvbau.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyzukny.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlnlrzl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dghjmtel.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdpthoy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjkenmv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtlwmeg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2owheeazk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhjwnxc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vovubzqq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2achpdpnv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkagyaj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fyetwtnx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ighlpvry.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyqoksm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbismur.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdzjovx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2agxmfikc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hiccpegb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yntkdhfk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzcwuvb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dfukucpj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuuhihc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2umffodra.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhyjkjj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kambickt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaajppsk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkuaykt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gofjrmmf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uedgxhdp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnldolwp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2frngwopq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vojnqflm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rohntohz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilibbava.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbujpsn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dabgzbvc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnjhuwd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2anzxbjyk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2upisdrjn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoiifml.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2omgmjbxs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnkpzfv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyksvvav.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2omxyjfnw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsuaabp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhgkqmt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxekxywl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kbveokak.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekorcrgi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfogrtp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qijgkcfi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xodcfckb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exauwdnq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzadgcbt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tggdysom.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itxblyal.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izqxixbd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrmmgbt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfsixzw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhgupqu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkvdmrr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxppeoe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2awumrhpo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfugwng.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sksfswan.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2txpssdgt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mllkpqjv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2demfjjae.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pethxmar.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqlkcrt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pbggtzio.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuqsiau.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zngtarcs.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtgpdhj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnojijv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxltpxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sykslzul.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqszyqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmdemyy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2usyfougp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqiubni.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2knoqbank.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thzxzfze.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwpeyyc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2husghggz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqheftq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzvvfnt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lhafwxxt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwgsotg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2juiylcqv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssodjlxn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdgmkkx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvafmwq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vbculoce.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kirlisno.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpiikye.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpjyvun.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hypsdxyp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wodjajre.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqqjusg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2svciwqxp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fjymyryw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmicxdgy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlbjawm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtyszuo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwocpgq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzudibkw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2imnxnclm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wehjqixv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyrfkzj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrancpl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tovagajk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqqtgvs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtjhzvb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaxnbsn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2utnrkliy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxywsaw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sqegcpxa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dokmrkac.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xnehxqox.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2puwliipu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkrihus.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpawxuy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wihbahob.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzmhchu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2efmauxzd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2spyhpmfi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmghhdz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfcvavd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rollzbwu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gerztdqt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmwzbfp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeaijxy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2duzlsxnp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ldenlumy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jwedpyyy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhortpp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmqxpnv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrunxlr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tazjwguy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2eshgpcyy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgryawp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaytrat.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtlaehs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxbnztz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnpycvk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2frrasojj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2szlhuqrx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlilsyx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgskzvz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjadeafs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2anftpkop.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2btrgogor.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqxdjws.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzlbhun.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ehccxnrz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbeofex.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2voglecvu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hputfjsa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdrlgdy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dkemwkty.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tguihrts.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2itzwkwcd.html


<!-- 参考信息 -->