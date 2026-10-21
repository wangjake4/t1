代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gtkcmciazz.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtrwyaaqjd.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gtfmuqrzlq.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtojjyjhgc.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtufpwoyyy.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gtonifgrex.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtikmjjkcl.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtxrynwizn.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gtnhbeurbb.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gteruqhqks.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gtckdzejkr.html

[S30] C：头文件保护
来源：http://dali.wangshuangyany.cn/Article/details/gtnhhgsxkz.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gtkltzvenx.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtmbtgmemb.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gtvqiqhccj.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtbjsekpuj.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gtpikeratc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gtbomfqerp.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gtyidsklfy.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gtvxhknwrj.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gthlmsfxqa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtyzluycur.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gtpclcyznn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gthhqwzpeo.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtrumptwlh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtjbgybnal.html

[S36] C++：unordered_map
来源：http://dali.cdnleiting.top/Article/details/gtmbcsgycx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtzthqfptj.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtczcgmwda.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gtygewbjye.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gtdzuwjauf.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gtstmqgnjv.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gtefmmtfss.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtqihvrlve.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtggevlyui.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtpjytybin.html

[S41] C++：类与构造函数
来源：http://dali.ydzc1.top/Article/details/gtngeiojka.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.havefunace.top/Article/details/gtpsxqmgtv.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtsgmqyvew.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtzwynaloj.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtwimukncd.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gtsmtbmala.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtpsaxeuya.html

void inc(int &x) { ++x; }
来源：http://dali.zhixingplan.top/Article/details/gtajudurrs.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtmibmoyld.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gttaihjnqq.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gtpgayhlfj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gtvwujtjdu.html

[S47] C++：结构化绑定遍历
来源：http://dali.316326.xyz/Article/details/gtnzvsotwi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtyadtmmkb.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtzfikhzaw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtjzbmtfre.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gtaoyfeysn.html

[S49] C++：写文件
来源：http://dali.sxryk.cn/Article/details/gtihyvsczr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtxnnmbxse.html

[S50] C++：格式化数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijzblvlg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtsfjoncwm.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtenjpssqy.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gteywafenz.html

[S52] C++：const 与 noexcept
来源：http://dali.xinyue.icu/Article/details/gtekplvhpg.html

int size() const noexcept { return n_; }
来源：http://dali.nanxinkj.top/Article/details/gtiztoobzs.html

[S53] C++：移动语义
来源：http://dali.hammf.cn/Article/details/gtmctlxawh.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gtirdvrbop.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtaebwhckh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdilvsrrs.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtdabavlua.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtybpzhjvg.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gtxpinyyfw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gtcxzatqkk.html

[S57] C++：编译期常量
来源：http://dali.0kj1m.cn/Article/details/gtwftuhgrt.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gtsftspwcx.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtynfxjgtm.html

namespace ns { int f() { return 1; } }
来源：http://dali.tanke756.top/Article/details/gtvturupiq.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvyyeold.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtvgwrcvih.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gttjyyfuzn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtripgucfr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmydlqdtr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtjfaztghv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsdhkajik.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gtahffttzp.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtnanzheab.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtfqblgapt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqdrrfsi.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgjkhhaa.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtluqgcbmg.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzpmwowp.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtuirsuclt.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gtatqpapzs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daxiang520.top/Article/details/gtmcledvlw.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gtvfdmwkwp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtbajqpxgy.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtyvsqaoku.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtrqkvhoeg.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gthjmshunu.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtdskpdnfd.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtmxpnwskt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtfjayld.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gtknxjlfft.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.316326.xyz/Article/details/gtwsdhsltq.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gttalylpni.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gttwljopwj.html

[T12] Kotlin：解构声明
来源：http://dali.chenzaomai.com/Article/details/gtbgccrruq.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyhgoqxn.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gthqiztbac.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gtajcyhoxt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gtbqxlvkjj.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gtyzrewwzz.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gtwbkombxl.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gtltwruvdd.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gtclqzwrao.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtlhgmbcwz.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gtbwmnljue.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtvmpfbqjk.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtvgypqiax.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gttgmkkxrs.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbyamqbh.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gtzboknltj.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gthaznvgxw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuxming.cn/Article/details/gtronezngz.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gteahxankm.html

for x in a { print(x) }
来源：http://dali.cdnleiting.top/Article/details/gtiibybkjm.html

[T22] Swift：字典
来源：http://dali.redwolf501.top/Article/details/gtalhnzoya.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnztzcgkw.html

[T23] Swift：函数
来源：http://dali.gzhubu.top/Article/details/gtxghtpjwp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sweek.top/Article/details/gtxuzfzqcv.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gtivqwbcul.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtcyrjedqo.html

[T25] Swift：结构体
来源：http://dali.zdqjudy.top/Article/details/gtrieltnkp.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gtcizixlym.html

[T26] Swift：类与重写
来源：http://dali.xuetiantiany.cn/Article/details/gttuwuwhku.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gtcislcurj.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlpnzhyo.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtajillhmf.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtlkecxmeg.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gteedooqmf.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gtdpfwtlgh.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstufpfdz.html

[T30] Swift：协议
来源：http://dali.fzhhl.top/Article/details/gtlzbmzmus.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtdfgyrvny.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gtdubkviib.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtannuwayy.html

[T32] Lua：局部变量
来源：http://dali.jiagoushi.top/Article/details/gtwkdtfipg.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gtinaohjjw.html

[T33] Lua：表（数组）
来源：http://dali.shuidangran.top/Article/details/gtsiieadtr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.havefunace.top/Article/details/gtxsidvcwn.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gttydowfjf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhixingplan.top/Article/details/gtslrqxyug.html

[T35] Lua：字典表
来源：http://dali.wangshuangyany.cn/Article/details/gtbjpxrxdt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gtvavhhhlk.html

[T36] Lua：函数
来源：http://dali.yj202588.top/Article/details/gtibqqcnpa.html

function add(a, b) return a + b end
来源：http://dali.andypj.xyz/Article/details/gtniewkswd.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtqthsrlpi.html

"a" .. "b"
来源：http://dali.kuanghao11.cn/Article/details/gtdlbvyuwv.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gtxbmkdxvm.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gtsnbhxvpl.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gtyeppvdll.html

string.find(s, "%d+")
来源：http://dali.c1oappe.top/Article/details/gtpdkgmyzj.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gtlgniugoz.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrcsbaql.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gtodriidrq.html

print "Hello\n";
来源：http://dali.dianchejie.cn/Article/details/gtfvvvcdpt.html

[T42] Perl：变量类型
来源：http://dali.zdqjudy.top/Article/details/gtbhsaofnm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gtzjshxxqy.html

[T43] Perl：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtwmyvmmbm.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtzundhdxq.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gtibqldjfk.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gtbyjeecxa.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gthmttbwrq.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gtyajvyyzw.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gtlgfrpnrp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.mhx1999.top/Article/details/gtmochscwy.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gtyeqcmgar.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gtgopbcktf.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtbbwlfynb.html

$s =~ s/old/new/g;
来源：http://dali.dashuyun.cn/Article/details/gtfusbgtmm.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gtqudergau.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtehsqaruw.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtmsfmeucx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sufxvd.cn/Article/details/gtjyxsdzvr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.mhx1999.top/Article/details/gtopeseuwa.html

[T51] Scala：Hello World
来源：http://dali.316326.xyz/Article/details/gtbzcipcfn.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtefuwesta.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gtzqxzbevd.html

val a = 1;  var b = 2
来源：http://dali.yangfankeji.com/Article/details/gtkmasjxyw.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtkavqxtdb.html

s"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtkdkbbdjc.html

[T54] Scala：集合映射
来源：http://dali.yonumen.top/Article/details/gtkgxzcuky.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gtwzbodncj.html

[T55] Scala：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtodqwlsfn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenlongwang.top/Article/details/gtasjqlopo.html

[T56] Scala：样例类
来源：http://dali.ydzc1.top/Article/details/gteptwmuir.html

case class User(name: String, age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtrbiotsfa.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtydievzau.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqlkbjui.html

[T58] Scala：函数定义
来源：http://dali.andypj.xyz/Article/details/gtheprgqoz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigfzy.top/Article/details/gtksbedfqu.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gtswkvlbuw.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtbgrbtwpy.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslhflhnt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gtfajhjuyv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcxwzpqzj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtyjhdpfol.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcafngjpc.html

[U01] Py：创建虚拟环境
来源：http://dali.xziqi.cn/Article/details/gtolyferjj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ivvv.top/Article/details/gtwgfliayw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gtgjszqoqe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jlsjyb.cn/Article/details/gtowegayaf.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gtnwsetcjx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gtvknnuotx.html

[U04] Py：变量调试打印
来源：http://dali.fengsongda.top/Article/details/gtyoecgeil.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hywenlv.cn/Article/details/gtaryblagk.html

[U05] Py：列表去重且保序
来源：http://dali.zhixingplan.top/Article/details/gthexmcvga.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtnlnokvos.html

[U06] Py：合并两个字典
来源：http://dali.zhengqikj.top/Article/details/gtutfmvgqi.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtzbxolmow.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gtyweebmek.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gtbxgtkhjn.html

[U08] Py：展平二维列表
来源：http://dali.jqgufenzy.top/Article/details/gtzgiiajdg.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gtfmuwixzj.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzglzjsgx.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gtafldwaez.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gtvmpjvwtp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hammf.cn/Article/details/gtardzxjum.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtpffmmjri.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gtelibeeaq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.vqdsnc.cn/Article/details/gtdfidpkkr.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gtmcfbvcjn.html

[U13] Py：固定长度队列
来源：http://dali.hysaishi.cn/Article/details/gtfonxpull.html

deque(maxlen=10)
来源：http://dali.fengsongda.top/Article/details/gtwwmgfpml.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gtmiadpuik.html

defaultdict(list)
来源：http://dali.birdmap.top/Article/details/gtrzkhuvce.html

[U15] Py：高精度计时
来源：http://dali.tanke756.top/Article/details/gtmbipmlqf.html

t = time.perf_counter()
来源：http://dali.mhx1999.top/Article/details/gtutrcscyg.html

[U16] Py：命令行参数解析
来源：http://dali.zhengqikj.top/Article/details/gtfsvnhwqj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gtqhncaghs.html

[U17] Py：初始化日志
来源：http://dali.yuxming.cn/Article/details/gtmaxfgzuz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxpzfiwm.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gtvykydmhi.html

pat = re.compile(r"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtiyascjpn.html

[U19] Py：正则替换带回调
来源：http://dali.zycfv.cn/Article/details/gtyucouymw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhoulong.xyz/Article/details/gtnwiukmvb.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gtiucfgqfs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xinyue.icu/Article/details/gtreujncrz.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gtuljcjfxh.html

@contextlib.contextmanager
来源：http://dali.snrcjt.cn/Article/details/gtnqldmgmh.html

[U22] Py：矩阵转置
来源：http://dali.hfpthk.cn/Article/details/gtswdvtsrz.html

list(zip(*m))
来源：http://dali.fzhhl.top/Article/details/gtjqxxxbxi.html

[U23] Py：分块读取大文件
来源：http://dali.tianlin.xyz/Article/details/gtkpkoktfk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.meibo888.top/Article/details/gtesazbnyj.html

[U24] Py：路径操作
来源：http://dali.haohaochexian.top/Article/details/gtqvvsidmd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtyicqdvci.html

[U25] Py：CSV 按字典读
来源：http://dali.cqqwz.cn/Article/details/gtobfxhwxh.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaiotrzgl.html

[U26] Py：并发下载
来源：http://dali.yanxiufei.cn/Article/details/gtkdgmxquv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ydzc1.top/Article/details/gtcxysqisc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gtzjibmens.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aibaodan.cn/Article/details/gtoclntfyv.html

[U28] Py：类型别名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwxmnziu.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gtvmnlsrhb.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gtrnebtsgd.html

@property 与 @x.setter 配合
来源：http://dali.aibaodan.cn/Article/details/gthdxzkjmg.html

[U30] Py：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtuoehuzbb.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gtuxekwmjz.html

[U31] Py：单测
来源：http://dali.yanxiufei.cn/Article/details/gtggixlbtp.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gtkrzapiun.html

[U32] Py：代码格式化
来源：http://dali.yangfankeji.com/Article/details/gttozfrxje.html

ruff format . && ruff check --fix .
来源：http://dali.dashuyun.cn/Article/details/gtrnrovmsh.html

[U33] Py：打包发布
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhfbwqil.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guannengcc.top/Article/details/gtyqgbbbif.html

[U34] Py：判断编码
来源：http://dali.ehwqpu.com/Article/details/gtwqgieqnj.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gtfsifrtav.html

[U35] Py：发送邮件
来源：http://dali.shuidangran.top/Article/details/gtkxoblirp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangdashe.top/Article/details/gtkckrfaan.html

[U36] Py：定时任务
来源：http://dali.wangdashe.top/Article/details/gtaqyyowdp.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gthorertry.html

[U37] Py：读写 Excel
来源：http://dali.gotoacloud.top/Article/details/gtwiuaekot.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gtmgouxpab.html

[U38] Py：获取脚本所在目录
来源：http://dali.gaohongyu789.top/Article/details/gtgpnfasea.html

Path(__file__).resolve().parent
来源：http://dali.pycfn.com/Article/details/gtskmitocx.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gtoyrzsyhs.html

sys.stdout.isatty()
来源：http://dali.ehwqpu.com/Article/details/gtrolhlalg.html

[U40] Py：打印到标准错误
来源：http://dali.redwolf501.top/Article/details/gtdzxyszxp.html

print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtrfgdcrcp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gtlyodtiff.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hywenlv.cn/Article/details/gtkacdlwoq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gtmqcpvrui.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sufxvd.cn/Article/details/gtkgntyunb.html

[U43] PHP：声明命名空间
来源：http://dali.mhx1999.top/Article/details/gtlsebsldu.html

namespace App\Http;
来源：http://dali.yueranfly.top/Article/details/gtvtwyhgvk.html

[U44] PHP：开启严格类型
来源：http://dali.sweek.top/Article/details/gttokpxfxj.html

declare(strict_types=1);
来源：http://dali.jlsjyb.cn/Article/details/gtawihloiw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gtkcbxxxky.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtmfivzmxr.html

[U46] PHP：可空类型
来源：http://dali.0kj1m.cn/Article/details/gtubcpgxdg.html

?string $name = null
来源：http://dali.9152youxi.cn/Article/details/gtegxkiuxv.html

[U47] PHP：联合类型
来源：http://dali.ehwqpu.com/Article/details/gtddhkhill.html

int|string $id
来源：http://dali.pycfn.com/Article/details/gtzjdqimif.html

[U48] PHP：纯枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgmlclxg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yonumen.top/Article/details/gtyauzfpdp.html


<!-- 参考信息 -->