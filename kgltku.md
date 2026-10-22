代发 wailian999

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtzwcrbmat.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtoifdnvkt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtoynatdsg.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtyjzarilu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtpjdmamen.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gtnbvodevu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenlongwang.top/Article/details/gtphbptpkg.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtviqqlqww.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gtbzmuezjf.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtycupgsrm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gtwnichqwc.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtjcejbfwu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gtohntklik.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowkeekzn.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gtnmtlgggx.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gtjbzzkehj.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gtquliherv.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gtenudcrzq.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtvczpyuim.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtbqvxpwxh.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtkxkrqaek.html

[S29] C：变参函数
来源：http://dali.feifeiyinyue.top/Article/details/gtpdmfpaxd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cheryme.top/Article/details/gthzwqvvcw.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gtuljqwohe.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtbrqmrifh.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtqqmddqsr.html

#endif
来源：http://dali.yj20258888.top/Article/details/gtpdszkbgz.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gtswuzhpll.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gthtmtjxrq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtrpfobdgd.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gtzsaxvwwa.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtvvdhbi.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtbtkejpwq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiptpommv.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtclzyztkv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtppskqtas.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gtvqytaamo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtuxdxzimo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gtteilwnpd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtgkzhkpoy.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gtyztgifsw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gtcyckcyik.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtqrbpurie.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gtiyvsupmj.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtatbchtpg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gtnlggqbpr.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlsyxien.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gtwdaehqmu.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtuwyzpqtr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gtocfyegep.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gtkirekpgn.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtfufeqmgf.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gtbrfwbxgs.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gtlqdziimu.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gtpwpclptx.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtgjbhojmk.html

[S45] C++：lambda
来源：http://dali.ppjwa.cn/Article/details/gtntnqbudn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gtwvqstvhq.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gtxbhtporp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gtechnnwlv.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gtzeousvay.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtleoewjha.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtgxcqqbys.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtgrosbtyg.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gtypmwljtm.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gtetsbaanx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtyfnxytve.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtittzksph.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gthvbneezk.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtcqqiuocf.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gtpnnmlhqv.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gtoiepwrxt.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtsezaevzm.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gtumytjcdi.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtlibwemhl.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gtghsaqync.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gtbhhxjhdp.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gtbeeyvtdl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtfvogoudl.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtosycxsnw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sxryk.cn/Article/details/gtnuajtztg.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtqfzbdbnb.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gtvifgxvyr.html

[S58] C++：命名空间
来源：http://dali.xziqi.cn/Article/details/gtlhcfiyaq.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gtjbweojpy.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gtjkglofjk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gtnwkuyoog.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gtekijuroq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daria6918.cn/Article/details/gtoptlkcir.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gteuxtrwjn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gtkomzhpqb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtsmbtvdhm.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtidbrvkwm.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtcqufqdpu.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gtbqkhvtev.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gtlexempib.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gtpbrwddsk.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtlmfnzogy.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggrkcwhs.html

val n: String? = null;  n?.length
来源：http://dali.jinqigfzy.top/Article/details/gtbthbqvie.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gttvoigwer.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gthqzlwovb.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gthlpvbczo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtbmozvcdx.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtafxovhsc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtavzqtwwh.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtbzvaacmo.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtuzuibwhl.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gtqypwaysn.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gtcagiaozd.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gtvaqpucqd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gtexxudvth.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gtlrmoymdf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gtkdnoudly.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gtrjzrzsjn.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtxhnbpbtc.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gtcxafgozd.html

val m = mapOf("a" to 1)
来源：http://dali.nwbrower.top/Article/details/gtgdcqxssn.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gthemhrfsc.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtxhhkgnim.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gtmqniepsn.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtqlgpwsfh.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtgbychzgz.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtxvkqqyyu.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtsglwpohw.html

var a = 1;  let b = 2
来源：http://dali.wangdashe.top/Article/details/gtlmbjbvuh.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtgbvslgsu.html

"值: \(b)"
来源：http://dali.yuxming.cn/Article/details/gteokvauid.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gtxuejyhqv.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtwsrjmmov.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gtimayslpu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtmdqigjga.html

[T21] Swift：遍历
来源：http://dali.ehwqpu.com/Article/details/gtjiojwkyp.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gtacjuppul.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtizdwhaks.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtwwmhkjeu.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gtkxzwoxry.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuhuvgkq.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gtqzokehjl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtjwhhcsij.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gtcnqtdnaf.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupzyfdqj.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gtiwnhynlf.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gthegwfifb.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gtxkavslvz.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gtawdldjlh.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gtglezahpm.html

enum Color { case red, green }
来源：http://dali.sysykeji.top/Article/details/gtqwfgrory.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gtauhayzwn.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gtrtederbk.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtenpomxfs.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gtwozovxbv.html

[T31] Lua：Hello World
来源：http://dali.aibaodan.cn/Article/details/gttvutrnrw.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtcvjtvwca.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gtatcfvgwp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gtkzujektv.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gtntfthvyg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gthmzdzmzz.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtsvmdmays.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gtywpmqgdo.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gtzozfjpkq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gtmjcpotzd.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gtiqejkbxb.html

function add(a, b) return a + b end
来源：http://dali.iojbl.cn/Article/details/gtiiqgoxdr.html

[T37] Lua：字符串拼接
来源：http://dali.havefunace.top/Article/details/gtoyuolncn.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gtpvotsavu.html

[T38] Lua：条件
来源：http://dali.dianchejie.cn/Article/details/gtkwvghene.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gtehlzrprq.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtrejaxlcb.html

string.find(s, "%d+")
来源：http://dali.xziqi.cn/Article/details/gtbrlgvkuj.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gthfxbqjbu.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gtjrjvtkbk.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtwwkubzbp.html

print "Hello\n";
来源：http://dali.yanxiufei.cn/Article/details/gtvlumwljo.html

[T42] Perl：变量类型
来源：http://dali.cheryme.top/Article/details/gtahdstpml.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gtigzkoilj.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtbzcatlds.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gtxnylwuea.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gtbxaxrjda.html

if ($a > 0) { print "正"; }
来源：http://dali.snrcjt.cn/Article/details/gtrxysdgfb.html

[T45] Perl：数组遍历
来源：http://dali.gotoacloud.top/Article/details/gtqegoesxb.html

for my $x (@arr) { print $x; }
来源：http://dali.cheryme.top/Article/details/gttegwkkrf.html

[T46] Perl：哈希操作
来源：http://dali.vqdsnc.cn/Article/details/gtrzmiyljk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtszjrjusp.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gtkhlhyysy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtebszpbjr.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gtouuxsvvq.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtmvjlrmde.html

[T49] Perl：函数
来源：http://dali.ppjwa.cn/Article/details/gtbhuheswe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gthfpvwkbl.html

[T50] Perl：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtzvivzzqj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.9152youxi.cn/Article/details/gtpoftdcyf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tian-w.cn/Article/details/gtxszdgyhh.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtbggsjelm.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtwmwmkehg.html

[T52] Scala：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvarqihid.html

val a = 1;  var b = 2
来源：http://dali.jiagoushi.top/Article/details/gtrdlisqvz.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtdenvxqhj.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtdboevhwr.html

[T54] Scala：集合映射
来源：http://dali.smart0.xyz/Article/details/gtagkswshp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtavtfbgaz.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gthyvpnxuo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ehwqpu.com/Article/details/gtnpeoftou.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gtquzyfpcf.html

case class User(name: String, age: Int)
来源：http://dali.yj202588.top/Article/details/gtwavwjqda.html

[T57] Scala：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwqtgect.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gtnjswwwbv.html

[T58] Scala：函数定义
来源：http://dali.hywenlv.cn/Article/details/gtqcrvxxka.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.0kj1m.cn/Article/details/gtteldhdti.html

[T59] Scala：循环
来源：http://dali.gzhubu.top/Article/details/gtbnhredcb.html

for (i <- 1 to 10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtfmhkglwg.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtwxlhwrlr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gtxtrfixbz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmvpfyule.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gtolyuoyvb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnbaslzon.html

[U01] Py：创建虚拟环境
来源：http://dali.wangshuangyany.cn/Article/details/gtmtkikvsh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gtrmbhknrz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sufxvd.cn/Article/details/gtydofjady.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxinkj.top/Article/details/gtbifvcxyo.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gticapecfb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhiwuduotai.top/Article/details/gtaufapihe.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gthjctiltw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hysaishi.cn/Article/details/gtnwjwkoss.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtvelrdsdi.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbezarsh.html

[U06] Py：合并两个字典
来源：http://dali.gotoacloud.top/Article/details/gtmiirwcmc.html

{**a, **b}
来源：http://dali.yj20258888.top/Article/details/gtjkdvgfvg.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gtmxwwfunv.html

{v: k for k, v in d.items()}
来源：http://dali.316326.xyz/Article/details/gtkvfxcjqd.html

[U08] Py：展平二维列表
来源：http://dali.yanxiufei.cn/Article/details/gtfsvmkljz.html

[y for x in nested for y in x]
来源：http://dali.jinqigfzy.top/Article/details/gtnvufkair.html

[U09] Py：字典取最大值的键
来源：http://dali.jinghuilouyu.cn/Article/details/gtcidzquwx.html

max(d, key=d.get)
来源：http://dali.xuetiantiany.cn/Article/details/gtmibyevtw.html

[U10] Py：按值排序字典
来源：http://dali.hammf.cn/Article/details/gtzbrfcifj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gttdvivlfw.html

[U11] Py：生成器表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxainovt.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gtklovzwyo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.kuanghao11.cn/Article/details/gthyrrdkgw.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gtfmnyxkwg.html

[U13] Py：固定长度队列
来源：http://dali.hnqzz.top/Article/details/gtjslvlxok.html

deque(maxlen=10)
来源：http://dali.vqdsnc.cn/Article/details/gtygxuqbwh.html

[U14] Py：分组收集到列表
来源：http://dali.hongshengwenyu.top/Article/details/gtfcwwaiey.html

defaultdict(list)
来源：http://dali.kuanghao11.cn/Article/details/gtljgqpgwj.html

[U15] Py：高精度计时
来源：http://dali.hysaishi.cn/Article/details/gtzljralax.html

t = time.perf_counter()
来源：http://dali.redwolf501.top/Article/details/gtunqzchkj.html

[U16] Py：命令行参数解析
来源：http://dali.guannengcc.top/Article/details/gtwewnsyoj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.c1oappe.top/Article/details/gtlgiljize.html

[U17] Py：初始化日志
来源：http://dali.fengsongda.top/Article/details/gtrcfjlhfx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pengpengdd.cyou/Article/details/gtmamqpnlx.html

[U18] Py：预编译正则
来源：http://dali.zhixingplan.top/Article/details/gtrxqovfeg.html

pat = re.compile(r"\d+")
来源：http://dali.sweek.top/Article/details/gtfneglzje.html

[U19] Py：正则替换带回调
来源：http://dali.bjfxy.top/Article/details/gtbdvteahr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jianghu66.top/Article/details/gtrdqnslky.html

[U20] Py：缓存函数结果
来源：http://dali.birdmap.top/Article/details/gtogefmqrl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnqzz.top/Article/details/gtfgajcsjt.html

[U21] Py：自定义上下文管理器
来源：http://dali.gotoacloud.top/Article/details/gtmzdbwnlc.html

@contextlib.contextmanager
来源：http://dali.pycfn.com/Article/details/gtfvncwzkp.html

[U22] Py：矩阵转置
来源：http://dali.zhengqikj.top/Article/details/gtqmmwirbx.html

list(zip(*m))
来源：http://dali.yj20258.top/Article/details/gtreaazkky.html

[U23] Py：分块读取大文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmotajqi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gtaqwtmlyl.html

[U24] Py：路径操作
来源：http://dali.birdmap.top/Article/details/gtsbedbxay.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtrnitsjar.html

[U25] Py：CSV 按字典读
来源：http://dali.gaohongyu789.top/Article/details/gtkwawnkon.html

csv.DictReader(f)
来源：http://dali.mhx1999.top/Article/details/gtjzllztfz.html

[U26] Py：并发下载
来源：http://dali.hnxiangtu.top/Article/details/gtgxjixhhb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.vqdsnc.cn/Article/details/gtxovanadx.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gtzdmsucki.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhgejtld.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gtbhtdmqtu.html

UserId = int
来源：http://dali.hnqzz.top/Article/details/gtjtmmdtyw.html

[U29] Py：属性校验
来源：http://dali.jinqigfzy.top/Article/details/gtqkkxapdi.html

@property 与 @x.setter 配合
来源：http://dali.redwolf501.top/Article/details/gtncgdrqhs.html

[U30] Py：数据类
来源：http://dali.jqgfzy.top/Article/details/gtjiobglht.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtoyhsakhf.html

[U31] Py：单测
来源：http://dali.hnqzz.top/Article/details/gtlmzptjur.html

python -m pytest -q
来源：http://dali.nanxinkj.top/Article/details/gtwdivvpyn.html

[U32] Py：代码格式化
来源：http://dali.andypj.xyz/Article/details/gtvnxjwvkj.html

ruff format . && ruff check --fix .
来源：http://dali.zycfv.cn/Article/details/gtxrboabcw.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gtscpukmcf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenzaomai.com/Article/details/gtlplgrzgn.html

[U34] Py：判断编码
来源：http://dali.sxryk.cn/Article/details/gtaxcvveyl.html

chardet.detect(raw)
来源：http://dali.yonumen.top/Article/details/gtxtwdkmqw.html

[U35] Py：发送邮件
来源：http://dali.yanxiufei.cn/Article/details/gtakcdyhlr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgonfwgtp.html

[U36] Py：定时任务
来源：http://dali.yonumen.top/Article/details/gtzqblibdy.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtugxynflz.html

[U37] Py：读写 Excel
来源：http://dali.jiagoushi.top/Article/details/gtydgfuzoq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gtcmvtitma.html

[U38] Py：获取脚本所在目录
来源：http://dali.ehwqpu.com/Article/details/gthnghcitd.html

Path(__file__).resolve().parent
来源：http://dali.fzhhl.top/Article/details/gtaiptdkdf.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gtuatwehsd.html

sys.stdout.isatty()
来源：http://dali.pycfn.com/Article/details/gtqgelgbnl.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gtgfnfarnu.html

print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gttyacfryp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yonumen.top/Article/details/gtjssfoomu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xylfe.cn/Article/details/gtgnotuaey.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gtnixwbows.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fzhhl.top/Article/details/gtkjanwkzp.html


<!-- 参考信息 -->