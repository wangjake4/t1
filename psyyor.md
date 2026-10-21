代发 wailian999

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtunzkymxj.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gtfkgxcjsq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtlkrpckfs.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gtpaoqayfa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gttddktuvu.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gtpczuzfaz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gtvywskiem.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gtfrjdjtvx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gtpcevpalp.html

[S23] C：随机数
来源：http://dali.dashuyun.cn/Article/details/gtltfgoggt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gtlhdqthkc.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gtxtsxzgpr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gtpiwbrvqo.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbombkpcy.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gtxikwjiqd.html

[S26] C：内存清零
来源：http://dali.xuetiantiany.cn/Article/details/gtpyvltozo.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtcuvhfxkv.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gtjoipqqtt.html

const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtvelnnpmt.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gtrczaxzwp.html

static int counter = 0;
来源：http://dali.hywenlv.cn/Article/details/gtkjnouosa.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtqwbulfpb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gtlkxaylyk.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gtstorhjgn.html

#ifndef X_H
来源：http://dali.yonumen.top/Article/details/gtuqfastyi.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gtbtpirbgg.html

#endif
来源：http://dali.daxiang520.top/Article/details/gtryxpniht.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtlpwldpdf.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtcyczsrlw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtkzciecas.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gtldobctza.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnyumezu.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrbzvybh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtgkkxudav.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gtcchubxgb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gtymmgqzht.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gtwgcphxtz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtdauwllzn.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gtayitfzkr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtctjqkqpw.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gtlgtchqjf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnxiangtu.top/Article/details/gtgpbzvnrq.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gtwryqqeto.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gtwafoptun.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gthzzbeuem.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gtlpmyyhrp.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gtkiruiiov.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gtcllwhjml.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtpxktjrzn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gthzcwdhob.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gtefcxafko.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gtjegpufra.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gttwedqcwc.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gtfmppplik.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gtmfiqfzjy.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gtnrinkvvl.html

[S45] C++：lambda
来源：http://dali.fengsongda.top/Article/details/gttzdqrhbs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtgareqtgu.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gtzzbzqeba.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gthmcvqija.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gtborvurhj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtxgaegvbz.html

[S48] C++：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtipzrbecn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gtrwgenwma.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gtwlasuexz.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gtnmdgomuk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtokqrouth.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtklatgslo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtdkgvedxx.html

[S51] C++：显式类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtkcpazvna.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gtuykasizl.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gtauerurha.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gtuiynngqd.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gtrvmfnubx.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gtsugxvzoo.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gtcztrttec.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gtcxcqekit.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtzvwpsqvn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteukdalkx.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gtaovesrew.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gtceyfkjek.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrndmder.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtwolehwpk.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtqucwxijz.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gtamqcoovy.html

[S59] C++：静态断言
来源：http://dali.guowangkeji.top/Article/details/gtfinjtaoq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtvcmxndhi.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gtqyygebri.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtxytoaynl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxaaapeil.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtfkwjizzw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtoyitvnlr.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtzghafiqi.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gtndvphqau.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfzwuxcl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuetiantiany.cn/Article/details/gtvziijjod.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtjwgotwtm.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtvhgeyckm.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gtvcegusvb.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtvtxqlhdc.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gtuxuyqdff.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.redwolf501.top/Article/details/gtfejqsmgx.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gtnhnwexwb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gtnwyvtulz.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtjrpbtbwt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gtgecahnqd.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtxlzxxedz.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtvmxzqxef.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gterwgnxaw.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gtebckvend.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtwtnmwdis.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daria6918.cn/Article/details/gtmionnxeq.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gtokeonaen.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gturuuoori.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtgaeeytzz.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gteurcizmg.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gtkdkaewrj.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gteqkytoiw.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gtyuosagjs.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquqjlqbi.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gtsflfyprv.html

interface Shape { fun area(): Double }
来源：http://dali.yvedp.cn/Article/details/gtjmmrftek.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtheznfscr.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gttcwzovxr.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gtekbigflc.html

var a = 1;  let b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcmlaosp.html

[T18] Swift：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gteayebgxh.html

"值: \(b)"
来源：http://dali.birdmap.top/Article/details/gtsfjtwjca.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gtqlfyukxu.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gtrcvkvsqw.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gtcfmygeiy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gtczpstdst.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gteizqlnvf.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gtoogxkadi.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gtqeljfnld.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gtvtzemvvu.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtvmyqqkjk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkagxgne.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtcpjwdznb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gtpdwuxkys.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtkojuvejt.html

struct P { var x: Int }
来源：http://dali.sweek.top/Article/details/gtjbheasmg.html

[T26] Swift：类与重写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmthvqysh.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtopglhgcj.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gtsphbhqgl.html

do { try f() } catch { print(error) }
来源：http://dali.cashguo.top/Article/details/gtrytvkhmq.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gteqzsadgw.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gtpkhoslyv.html

[T29] Swift：guard 提前返回
来源：http://dali.ivvv.top/Article/details/gtwmlkizls.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gtygvxitwr.html

[T30] Swift：协议
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmqfvglw.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gtmnpzszfc.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtxsdzjeoi.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtqgcgzosk.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gttzoauedy.html

local a = 1
来源：http://dali.zycfv.cn/Article/details/gtpcnguefl.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtihoqibji.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtxlswtyya.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gtjunsotuu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gthybtfaix.html

[T35] Lua：字典表
来源：http://dali.daxiang520.top/Article/details/gtqgnzkdnm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtqfytqfzf.html

[T36] Lua：函数
来源：http://dali.xziqi.cn/Article/details/gtpzhpuhso.html

function add(a, b) return a + b end
来源：http://dali.gogol.net.cn/Article/details/gtzyrlszsg.html

[T37] Lua：字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtgydkhjry.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gtxghnmtve.html

[T38] Lua：条件
来源：http://dali.andypj.xyz/Article/details/gtdhkdehuj.html

if x > 0 then print("正") end
来源：http://dali.yj20258.top/Article/details/gtszsmebiu.html

[T39] Lua：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtjvllraet.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gtqlpwedvc.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gtzatmmhgi.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gtmyomecia.html

[T41] Perl：Hello World
来源：http://dali.mhx1999.top/Article/details/gtgufnkdpv.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtvmocnvnh.html

[T42] Perl：变量类型
来源：http://dali.nanxuanxn.top/Article/details/gtijzascut.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tian-w.cn/Article/details/gtgfzsciox.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtuvpcyeep.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gtzjjkufab.html

[T44] Perl：条件
来源：http://dali.shzxlz.cn/Article/details/gtbsdumyoy.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gtspeqqkup.html

[T45] Perl：数组遍历
来源：http://dali.jinqigufen.top/Article/details/gtqohamyql.html

for my $x (@arr) { print $x; }
来源：http://dali.havefunace.top/Article/details/gtwrysojfx.html

[T46] Perl：哈希操作
来源：http://dali.svipenyu.cn/Article/details/gtqkpovgkw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gtyhwxgszn.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gtyhcenlgk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gthlyuyunc.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gtduwsxorh.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gtpcerdawt.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gtkorwqocd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtavjmfybv.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtvxurwtbr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenzaomai.com/Article/details/gterbvfzwq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdmicciki.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtszmypibt.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gttscctuhl.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gtoedqaewh.html

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtnnpzzcwt.html

[T53] Scala：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtswtrlmoq.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtrpwmcuof.html

[T54] Scala：集合映射
来源：http://dali.iojbl.cn/Article/details/gtqnhmosxw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xinyue.icu/Article/details/gtlkkoaggc.html

[T55] Scala：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtcybeenwp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tianlin.xyz/Article/details/gtlkjqzfwf.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gtiobimwhu.html

case class User(name: String, age: Int)
来源：http://dali.wangdashe.top/Article/details/gtqwoopdpl.html

[T57] Scala：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtiedvmrcj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gttbvoijhp.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gtxqngxxey.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.quarkkingdee.top/Article/details/gtoefrdyqi.html

[T59] Scala：循环
来源：http://dali.daria6918.cn/Article/details/gtewrpnylo.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtxpqjlksf.html

[T60] Scala：折叠
来源：http://dali.jinqigufen.top/Article/details/gtwnnmiwfm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yvedp.cn/Article/details/gtnljgihdx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtljlavjbi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gtmsynmkug.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdzabszls.html

[U01] Py：创建虚拟环境
来源：http://dali.hongshengwenyu.top/Article/details/gtlzolucvo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuanzx.com/Article/details/gthdtpokbc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pycfn.com/Article/details/gtpqmmfysb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.9152youxi.cn/Article/details/gtkczlodzj.html

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gtrvlltyrh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cdnleiting.top/Article/details/gtpmkzeepe.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gtrlqgfyfd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zycfv.cn/Article/details/gtqljqzyuv.html

[U05] Py：列表去重且保序
来源：http://dali.hongshengwenyu.top/Article/details/gtkztlqwup.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtkpgnjqcp.html

[U06] Py：合并两个字典
来源：http://dali.vqdsnc.cn/Article/details/gtdmvdnmpi.html

{**a, **b}
来源：http://dali.jqgufenzy.top/Article/details/gtpiotdqws.html

[U07] Py：反转字典键值
来源：http://dali.yj202588.top/Article/details/gtrqhkbfom.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258888.top/Article/details/gtatxeukmr.html

[U08] Py：展平二维列表
来源：http://dali.dianchejie.cn/Article/details/gtyltaunqe.html

[y for x in nested for y in x]
来源：http://dali.feifeiyinyue.top/Article/details/gtplnyeizv.html

[U09] Py：字典取最大值的键
来源：http://dali.0kj1m.cn/Article/details/gtlxnbiups.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gtrzwwctzu.html

[U10] Py：按值排序字典
来源：http://dali.zdqjudy.top/Article/details/gtbubukbop.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtsohqubxt.html

[U11] Py：生成器表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgsedhdx.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gtncldxtxg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xziqi.cn/Article/details/gtodmudruv.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtyfdkihil.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gtknavlkhf.html

deque(maxlen=10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlurtrwrn.html

[U14] Py：分组收集到列表
来源：http://dali.cqqwz.cn/Article/details/gtkmegbjyu.html

defaultdict(list)
来源：http://dali.cheryme.top/Article/details/gtnpbslvyq.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gtkskxqghz.html

t = time.perf_counter()
来源：http://dali.yj202588.top/Article/details/gtcvfygfvj.html

[U16] Py：命令行参数解析
来源：http://dali.yueranfly.top/Article/details/gtnukkphuv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gtehxyybos.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gthkhfynln.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gtgqafgrjh.html

[U18] Py：预编译正则
来源：http://dali.yj20258888.top/Article/details/gtcdguyjla.html

pat = re.compile(r"\d+")
来源：http://dali.daria6918.cn/Article/details/gtuxztagcy.html

[U19] Py：正则替换带回调
来源：http://dali.gotoacloud.top/Article/details/gtpgsprqrq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yongpay.top/Article/details/gtisfszipj.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258.top/Article/details/gtbkyflvaw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gtavffswxn.html

[U21] Py：自定义上下文管理器
来源：http://dali.daxiang520.top/Article/details/gtknoonzgc.html

@contextlib.contextmanager
来源：http://dali.daria6918.cn/Article/details/gtermfgfdo.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gtzxvkdkoe.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gtxujwvbij.html

[U23] Py：分块读取大文件
来源：http://dali.jqgufenzy.top/Article/details/gtynoafchw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuxming.cn/Article/details/gtzdvsvdih.html

[U24] Py：路径操作
来源：http://dali.birdmap.top/Article/details/gtdlzyyxts.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtzpmfugmh.html

[U25] Py：CSV 按字典读
来源：http://dali.ydzc1.top/Article/details/gtpkhixaak.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gtxaupepjc.html

[U26] Py：并发下载
来源：http://dali.yangfankeji.com/Article/details/gtkqikusvr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hfpthk.cn/Article/details/gtjldbignd.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gtvrctmmgn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gzhubu.top/Article/details/gthfplyhlv.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gtpcejiqwg.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gtjxctnkvd.html

[U29] Py：属性校验
来源：http://dali.hfpthk.cn/Article/details/gtuhjcatah.html

@property 与 @x.setter 配合
来源：http://dali.gaohongyu789.top/Article/details/gtgrnfmekf.html

[U30] Py：数据类
来源：http://dali.zhengqikj.top/Article/details/gtqrxzgsfe.html

@dataclass(slots=True)
来源：http://dali.nanxinkj.top/Article/details/gtwupaxczj.html

[U31] Py：单测
来源：http://dali.fzhhl.top/Article/details/gtoilpspmt.html

python -m pytest -q
来源：http://dali.hfpthk.cn/Article/details/gtzvblcomx.html

[U32] Py：代码格式化
来源：http://dali.pycfn.com/Article/details/gtodmpnlri.html

ruff format . && ruff check --fix .
来源：http://dali.9152youxi.cn/Article/details/gtpaqzfpwg.html

[U33] Py：打包发布
来源：http://dali.snrcjt.cn/Article/details/gtseoivaqy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gtwjgciieq.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gtqcjdsuwj.html

chardet.detect(raw)
来源：http://dali.jqgufenzy.top/Article/details/gtjxargomj.html

[U35] Py：发送邮件
来源：http://dali.redwolf501.top/Article/details/gtbpcfaqui.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xziqi.cn/Article/details/gtoihrnjkq.html

[U36] Py：定时任务
来源：http://dali.quarkkingdee.top/Article/details/gtefrkooik.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxuanxn.top/Article/details/gtrjfnpiws.html

[U37] Py：读写 Excel
来源：http://dali.hysaishi.cn/Article/details/gtjmrfhbuf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pengpengdd.cyou/Article/details/gtzbvqhcer.html

[U38] Py：获取脚本所在目录
来源：http://dali.yvedp.cn/Article/details/gttyzoflzi.html

Path(__file__).resolve().parent
来源：http://dali.hfpthk.cn/Article/details/gtynhuioyu.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenzaomai.com/Article/details/gttwviyfzz.html

sys.stdout.isatty()
来源：http://dali.yonumen.top/Article/details/gtnabkpvva.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigfzy.top/Article/details/gtfjcjcmmq.html

print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtjhoffcdt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gtnzxhsvfp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.andypj.xyz/Article/details/gtlqjksinh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.guowangkeji.top/Article/details/gtolucrrvg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.bjfxy.top/Article/details/gtpqqwusks.html


<!-- 参考信息 -->