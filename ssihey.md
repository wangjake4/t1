代发 wailian999

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtwuargpdq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtvivcyxzn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgwfwfmt.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gtjobyfxwu.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrefmxnt.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gtzoqcicvd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtcxdfprvw.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyzycmae.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtrlbvbked.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gttucvgasz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gtnhrvesaj.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gterzclpab.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtcxmaburu.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gtruilggbn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtejcvfuld.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gtmvjbxojq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtwmwmyvsp.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtyfczjxac.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzsjlqrd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtnrblvrop.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtmxgpeqqb.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtsfpdfnjr.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtmwejglgr.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtwcyngsgn.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtrjbbypsx.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtaxqxbttg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gtxfljhqlm.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gtwxpnwpnq.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtzmfettox.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gtrrrxcyqa.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gtpjnkmqrm.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gtaxdogyqs.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtnmuyflcb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtxnhgvcwl.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gtwmsnggic.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtwsjblnog.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gtpwdzjafs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.snrcjt.cn/Article/details/gtybrcpuff.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gthistuaqf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gtycqmlbqe.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gtzptkhhjz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtvjpdljxf.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtnszyzmhw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtrszkauvj.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtwtgzylgi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtbdxdpsym.html

[S38] C++：排序
来源：http://dali.ppjwa.cn/Article/details/gthtnsdfbi.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtopozbpcu.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gtwgtkaupy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gtdgtfxuha.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gthjbfeixq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gtrsbbgynz.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gtyvzxacet.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsxmrrjo.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtwpvxfzbl.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gtchcwicwq.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtbyittjuq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gtwcbnjjuk.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gtjxfhosbs.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtciedgafv.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtqaaxmhtb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtrqnilgpy.html

[S46] C++：函数模板
来源：http://dali.dashuyun.cn/Article/details/gtprtsmuqn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gtvzmvqzga.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtnazyveno.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gtfxtyiiqw.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtlyrufens.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gtpohzqefc.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gtewurvgzl.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gtfhdutpmg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gtkepktamg.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gtkodkflxa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtwsdtkwdm.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtzxtaydbz.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkkrtohn.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gtrxebnvxj.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gtipmsppdg.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtxgsqeasb.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gtpmankzeu.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gtcnkwusew.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtiekdiqon.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gtjnurnfiy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtlzjhoqla.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gtczclvhws.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gtscvlyhpj.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gtvoqizxux.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gtukpbidet.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gtrebcmkdn.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaeafwobk.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtedmimnbq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gthietbqmf.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtzilfnkvn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtyohnzusb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzgjpfcpi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gtkawenxtk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtxgzghtny.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtmvfumplw.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtycouknzi.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gtssocroec.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gtfpvrhafr.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtfqbqrhwt.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gtqoamrlvk.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gtwglatwep.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtnsoslxai.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gtmqktpdwx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gtpsduqlmr.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gttxjcbkct.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuxming.cn/Article/details/gtbyunmzyb.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gtckixvhdu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gtvjffuzab.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gtalkwslrg.html

data class User(val name: String, val age: Int)
来源：http://dali.zycfv.cn/Article/details/gteiyzqyqr.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gtjyxynxaq.html

fun String.exclaim() = this + "!"
来源：http://dali.chenjidiqi.icu/Article/details/gtxxotffrl.html

[T10] Kotlin：默认参数
来源：http://dali.sysykeji.top/Article/details/gtnssiylcm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gtxbchxdfv.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gtvpkdrfzg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gtsxrcsoee.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtkqapdl.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtqsutsfmn.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gtoasdyxxn.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gtqwpnjugw.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gtpckxmkqo.html

for (i in 1..10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtreoqxetu.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gtvnuqmatx.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtbfpbpfft.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gtcjqjdiup.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtzzxujgle.html

[T17] Swift：变量与常量
来源：http://dali.daxiang520.top/Article/details/gtpekxnktw.html

var a = 1;  let b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtzyjdihzs.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtwtfiwqvp.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gtisotqwwb.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gtaczmuwda.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gtqjcnkjqu.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gtijfedokn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gtfrowyinn.html

[T21] Swift：遍历
来源：http://dali.meibo888.top/Article/details/gtlytesyxc.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gthgkgrfrd.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtvgaogjqx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gtqyaopbkw.html

[T23] Swift：函数
来源：http://dali.mhx1999.top/Article/details/gtsyowdund.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gtddugngim.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gtsvxqexfp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gthjhzcflx.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gtfukgnvkb.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gtvtixwfjv.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gtqhealfha.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtkwhftxof.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gthtzzdcli.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtbbssqwcg.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gttnxrmlvt.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gtzxxezirt.html

[T29] Swift：guard 提前返回
来源：http://dali.chenzaomai.com/Article/details/gtsddahfzf.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtrddwidgr.html

[T30] Swift：协议
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwcickbz.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gtttopatba.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtsvqvjmsb.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtsgsaxcnn.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtrcgmzqiq.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtakbplkmt.html

[T33] Lua：表（数组）
来源：http://dali.316326.xyz/Article/details/gtnnueyitx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnmtmixs.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gteuuormza.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gtazsmwzcu.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gtyglojaln.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gtdncsbcxv.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gtjltisbrt.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmngmysij.html

[T37] Lua：字符串拼接
来源：http://dali.yonumen.top/Article/details/gttotyuomj.html

"a" .. "b"
来源：http://dali.sysykeji.top/Article/details/gtreidrtep.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gtfoftacux.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gtkwghovwf.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gthhqvysoa.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gtdsvautee.html

[T40] Lua：元表
来源：http://dali.c1oappe.top/Article/details/gtexeilbmw.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gtolzfktxo.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtfsxxftte.html

print "Hello\n";
来源：http://dali.tianlin.xyz/Article/details/gtfchdwgky.html

[T42] Perl：变量类型
来源：http://dali.dashuyun.cn/Article/details/gtcnnjftow.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gtomgjgenc.html

[T43] Perl：字符串插值
来源：http://dali.havefunace.top/Article/details/gtluekvoot.html

"值: $a"
来源：http://dali.dianchejie.cn/Article/details/gtoiogtham.html

[T44] Perl：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtvopuuxue.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gthyaamowi.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gtvdbeyjxz.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gtabkoomrz.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gtesijhrfi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.svipenyu.cn/Article/details/gtjogufvzv.html

[T47] Perl：正则捕获
来源：http://dali.aibaodan.cn/Article/details/gtqktwyvfp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.bjfxy.top/Article/details/gtzmkxldth.html

[T48] Perl：正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtpzibebig.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtloaaorkm.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gtzsyaogjg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gthbkzqmzm.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtuhymfrgw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gtmploaxoe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gttcgjforl.html

[T51] Scala：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtchsmnzia.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtfqxyoyvc.html

[T52] Scala：变量
来源：http://dali.sxryk.cn/Article/details/gtpsdhguwe.html

val a = 1;  var b = 2
来源：http://dali.yongpay.top/Article/details/gttzirksme.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gtblvdzelk.html

s"值: $b"
来源：http://dali.cucudq.cn/Article/details/gtrbxexxqi.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtxnwsymxo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyedrohg.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtlogjkxyc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gtxosqmqun.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gtqyhtxrpv.html

case class User(name: String, age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtdvurlgkj.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtefogtjwa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.smart0.xyz/Article/details/gtdzgnpegi.html

[T58] Scala：函数定义
来源：http://dali.ehwqpu.com/Article/details/gtpebihwiw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xylfe.cn/Article/details/gtrhdzezxi.html

[T59] Scala：循环
来源：http://dali.guannengcc.top/Article/details/gtqedulbrf.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gteuqlzcdf.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gtfdqtfxre.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xylfe.cn/Article/details/gtlljvavun.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzpvgrqop.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gterpdtjis.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtbqvzndgm.html

[U01] Py：创建虚拟环境
来源：http://dali.ybcxt.top/Article/details/gtknwllayz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sysykeji.top/Article/details/gthzyrltlg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtngpcyyib.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cqqwz.cn/Article/details/gtqvbnpmkv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gttqpmafvu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigfzy.top/Article/details/gtgaqormvj.html

[U04] Py：变量调试打印
来源：http://dali.gogol.net.cn/Article/details/gtxfxwincx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gttxxseufh.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gtcixnqbla.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gthbbehthq.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gthqqekrgl.html

{**a, **b}
来源：http://dali.jqgufenzy.top/Article/details/gtbqdcvjdx.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gtcqpqadeq.html

{v: k for k, v in d.items()}
来源：http://dali.jyoumei.cn/Article/details/gtxubedcce.html

[U08] Py：展平二维列表
来源：http://dali.yueranfly.top/Article/details/gtlrmluhso.html

[y for x in nested for y in x]
来源：http://dali.cucudq.cn/Article/details/gtpvyijvsp.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gtqrddlauo.html

max(d, key=d.get)
来源：http://dali.yuanzhike.top/Article/details/gtaxmuggxn.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gtcgqyycwh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxinkj.top/Article/details/gtkypklryo.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlwxrbvx.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gtvlvmnups.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tian-w.cn/Article/details/gtwybetesu.html

Counter(arr).most_common(3)
来源：http://dali.nwbrower.top/Article/details/gtbainwiig.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gtwzlwcgdp.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gtmkugjdgv.html

[U14] Py：分组收集到列表
来源：http://dali.yuanzhike.top/Article/details/gtruqvowqk.html

defaultdict(list)
来源：http://dali.yongpay.top/Article/details/gtfluuujok.html

[U15] Py：高精度计时
来源：http://dali.cucudq.cn/Article/details/gtzdnmgbpt.html

t = time.perf_counter()
来源：http://dali.snrcjt.cn/Article/details/gtwiwwjeir.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gtexghqrpc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gtddlzkqgq.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtukzjqvdi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ivvv.top/Article/details/gtuzwsbsno.html

[U18] Py：预编译正则
来源：http://dali.chenzaomai.com/Article/details/gtnygjdmug.html

pat = re.compile(r"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtaztvdkkt.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gtduofduib.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsovxscp.html

[U20] Py：缓存函数结果
来源：http://dali.zhoulong.xyz/Article/details/gtjwptubof.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gaohongyu789.top/Article/details/gtkwobuisp.html

[U21] Py：自定义上下文管理器
来源：http://dali.cucudq.cn/Article/details/gtmdvupnid.html

@contextlib.contextmanager
来源：http://dali.jinghuilouyu.cn/Article/details/gttdnjocvi.html

[U22] Py：矩阵转置
来源：http://dali.fzhhl.top/Article/details/gthpoqdtlq.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gtavnnulka.html

[U23] Py：分块读取大文件
来源：http://dali.cdnleiting.top/Article/details/gtnlbnyaqf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhypmpxs.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gtfktpsraa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtwkncdlsz.html

[U25] Py：CSV 按字典读
来源：http://dali.xylfe.cn/Article/details/gtcgvfzzll.html

csv.DictReader(f)
来源：http://dali.sweek.top/Article/details/gtwdbqulph.html

[U26] Py：并发下载
来源：http://dali.yj202588.top/Article/details/gtrvevcoko.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudghcann.html

[U27] Py：异步 HTTP
来源：http://dali.cheryme.top/Article/details/gtqgjiiosq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hongshengwenyu.top/Article/details/gtdwgrjlpl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gtbjslocjy.html

UserId = int
来源：http://dali.cqqwz.cn/Article/details/gtrtpupsgm.html

[U29] Py：属性校验
来源：http://dali.jyoumei.cn/Article/details/gtmwfsvcxc.html

@property 与 @x.setter 配合
来源：http://dali.gzhubu.top/Article/details/gtmyrrojrr.html

[U30] Py：数据类
来源：http://dali.zycfv.cn/Article/details/gtdkxqyoia.html

@dataclass(slots=True)
来源：http://dali.vqdsnc.cn/Article/details/gtbhxcmjzc.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gtvrawihjo.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gtnvesczut.html

[U32] Py：代码格式化
来源：http://dali.hnqzz.top/Article/details/gtossezhil.html

ruff format . && ruff check --fix .
来源：http://dali.hnqzz.top/Article/details/gtwzceapxc.html

[U33] Py：打包发布
来源：http://dali.hammf.cn/Article/details/gtileiuqcd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgfzy.top/Article/details/gtxcibkbuq.html

[U34] Py：判断编码
来源：http://dali.yj20258888.top/Article/details/gtzxhvqaml.html

chardet.detect(raw)
来源：http://dali.aizwys.cn/Article/details/gtwemxlkle.html

[U35] Py：发送邮件
来源：http://dali.wangdashe.top/Article/details/gtbefunswo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.9152youxi.cn/Article/details/gtytpjezbr.html

[U36] Py：定时任务
来源：http://dali.shuidangran.top/Article/details/gtcptylvpg.html

schedule.every(10).minutes.do(job)
来源：http://dali.cdnleiting.top/Article/details/gtuynjzwbw.html

[U37] Py：读写 Excel
来源：http://dali.kuanghao11.cn/Article/details/gtckzebnsb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.redwolf501.top/Article/details/gtuokyjlxa.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj202588.top/Article/details/gtgvthdqha.html

Path(__file__).resolve().parent
来源：http://dali.cucudq.cn/Article/details/gtffgjanld.html

[U39] Py：判断是否在交互环境
来源：http://dali.aibaodan.cn/Article/details/gtenkrvrhk.html

sys.stdout.isatty()
来源：http://dali.yj20258.top/Article/details/gtvedczmnz.html

[U40] Py：打印到标准错误
来源：http://dali.mhx1999.top/Article/details/gtqvmhqjep.html

print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtcjwmobos.html


<!-- 参考信息 -->