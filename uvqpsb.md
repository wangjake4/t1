代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gttnifsgpi.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtguwlduak.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtweebbfpg.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gtcyptqedb.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gtowmrzxrk.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtmonincrj.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gthifdwoik.html

[S28] C：静态变量
来源：http://dali.redwolf501.top/Article/details/gtzmpmtnnw.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtoyudlrtv.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gtuozxqjrr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtkqnjlurn.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gtzgaigmtc.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gtfqvuulhz.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gtapwcwsdp.html

#endif
来源：http://dali.birdmap.top/Article/details/gtxglnfgnh.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtsylanodb.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gthemfichz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtgfxnyout.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtcnokfmeq.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gtyjpkyidt.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtydhnbsyd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtrwlnhgys.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gtdbfznxlk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtmhswouda.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtdiigpvxh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtfgxjvxhj.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gtjvrctydh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtnzodexmf.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtmsxbctbj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gtckuvgzxx.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gtzkmuydji.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gtehaebuel.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwxbnlou.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaetvmkj.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gtgdlbkked.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gtlyflawks.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtyrqwohcm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtqshspmhd.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gtmcomhuyb.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gtulcsosxk.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtxxcxwtuc.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gtghwrbqly.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtpsbglirf.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gtttuittbe.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gthqrokglv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gtyrvcjwqk.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gtqnllehht.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtzqvmsmyv.html

[S47] C++：结构化绑定遍历
来源：http://dali.dianchejie.cn/Article/details/gtctclhlyz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gtpzihhibw.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtwrykxqab.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhixingplan.top/Article/details/gtgvrghwzy.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gtvqhbgikd.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gtcdnajbnu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sweek.top/Article/details/gtedfvgaub.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gtpwuwtazt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtcwagfusm.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gtwbvyjzec.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gtyjuaconx.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gttbtlqkic.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gtgedzuupy.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtuufmenmn.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtxpwsdnnf.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gtjjlqqjfq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtduhmhghb.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gthmcblhlt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gtstdgqsod.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gtooglrinj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gtxaydzyck.html

[S57] C++：编译期常量
来源：http://dali.0kj1m.cn/Article/details/gtnpeiebez.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtebdadtpl.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtjwmjnfdt.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gtxwcoyavj.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gtnujxtmjr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gtwrdojpsz.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gtfwujyhgf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtxqdpyadx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjkpmmja.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtrhxwnrre.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtpcahbdnq.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtadihnfqy.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtsxiquajf.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtpylgasdd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtyqnmhtjq.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gtxhjyfwct.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gtzzrascjw.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtpjooyyph.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtpebbvnpo.html

[T05] Kotlin：when 表达式
来源：http://dali.tianlin.xyz/Article/details/gtyrlyogud.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtaaiwvppo.html

[T06] Kotlin：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtwzsludrc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtrjykyfyf.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtderjcdnq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gtuwlhgsgd.html

[T08] Kotlin：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gtwjoydbet.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtbtxxsfkw.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gtvpcrcect.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gtmddvspkn.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtivuydlmj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gtncnsdvxo.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtwwnpfdka.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhbrzlhq.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gtknoyobfr.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtjevijdnn.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqafcxrm.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gtrnupfzhv.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gtajrwkllj.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtmmtyliwk.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gtuklfhkee.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gtmrporrse.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gtyvoynlsl.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtjbidiqre.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtfgoxojeo.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gtphknuvph.html

[T18] Swift：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtybtahvul.html

"值: \(b)"
来源：http://dali.pengpengdd.cyou/Article/details/gtrwecpkns.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gtiykequxg.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gtgfusikzc.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gtkxxfxain.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gthzfnnfky.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gtqwotumjz.html

for x in a { print(x) }
来源：http://dali.ehwqpu.com/Article/details/gteyostiot.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtqzzdbudn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtgbtwnabq.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gtbbsyshwi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtkxqaercx.html

[T24] Swift：闭包
来源：http://dali.guowangkeji.top/Article/details/gtwodlmkzv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtibwlmdds.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtapwqzpop.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gtgsjzeenj.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gtsbomelvo.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtryrueyjy.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtvfcktdbx.html

do { try f() } catch { print(error) }
来源：http://dali.nanxuanxn.top/Article/details/gtukcisbfm.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gthybfqliw.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gtmndcctse.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gtltmmtqmr.html

guard let x = opt else { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtpsfzwqib.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gtdpeqphpi.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gtkwnjkyzx.html

[T31] Lua：Hello World
来源：http://dali.iojbl.cn/Article/details/gtgzvyvejm.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtidjbybrt.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtgvskzqay.html

local a = 1
来源：http://dali.nanxuanxn.top/Article/details/gtmxbkuhxg.html

[T33] Lua：表（数组）
来源：http://dali.shuidangran.top/Article/details/gtdkauqyig.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gaohongyu789.top/Article/details/gtahbdendj.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gtrelbvsjq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuetiantiany.cn/Article/details/gtenhumgvf.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gtiwhnugsf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gtkmpzipkb.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gtruxzbkaq.html

function add(a, b) return a + b end
来源：http://dali.chenjidiqi.icu/Article/details/gtifedxxad.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtqjgeolvk.html

"a" .. "b"
来源：http://dali.haohaochexian.top/Article/details/gtnjmtyoxw.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gtdvennmhb.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gtdmawybov.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtlviozgbc.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gtddnznnth.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtvuazublg.html

setmetatable({}, { __index = base })
来源：http://dali.daxiang520.top/Article/details/gtqjszrcsm.html

[T41] Perl：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtrwovuuds.html

print "Hello\n";
来源：http://dali.jqgufenzy.top/Article/details/gtxdofoett.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndqxsybt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtjgjtjdry.html

[T43] Perl：字符串插值
来源：http://dali.tanke756.top/Article/details/gtvstbcfdg.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gtfpgltgbw.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gtgotluvzd.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gtjlxkxqww.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gtocnfshat.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gtmdgqpuog.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gtaxfhllwx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yonumen.top/Article/details/gtfermmxcl.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gtqcqyokrj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sxryk.cn/Article/details/gtbagnqmrz.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gtltwoqptp.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gtgrogcefu.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gtueqlbbck.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoadsvkyg.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtalgmicfz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gtofjykybf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenlongwang.top/Article/details/gtoakavzcc.html

[T51] Scala：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtbhigptyh.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gtyllqqrxq.html

[T52] Scala：变量
来源：http://dali.jinqigfzy.top/Article/details/gtyurbinln.html

val a = 1;  var b = 2
来源：http://dali.yueranfly.top/Article/details/gtjznzcvyw.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gttnkzfiqu.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtvtilddwg.html

[T54] Scala：集合映射
来源：http://dali.mhx1999.top/Article/details/gtdqcocikf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gtatnennls.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtrzffrsyn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbccmidkd.html

[T56] Scala：样例类
来源：http://dali.hongshengwenyu.top/Article/details/gtgwosnder.html

case class User(name: String, age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtdexlgdgh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gtslpebdsb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gtuwmjiaba.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gtzgafitfn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtzcddmxpn.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gtdmambsea.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcbphykk.html

[T60] Scala：折叠
来源：http://dali.wangdashe.top/Article/details/gtpmoapbis.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gtnqebygar.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdmezgvwz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gtxakvyfnx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtyrsalatw.html

[U01] Py：创建虚拟环境
来源：http://dali.yvedp.cn/Article/details/gtcbnigjbw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gtvrdamfbs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtyocevfnm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.meibo888.top/Article/details/gtanaaodvd.html

[U03] Py：加载 .env 配置
来源：http://dali.jlsjyb.cn/Article/details/gtkjcocorb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aibaodan.cn/Article/details/gtmzgyzukh.html

[U04] Py：变量调试打印
来源：http://dali.cashguo.top/Article/details/gtdbphfgds.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigfzy.top/Article/details/gtkttgsqaz.html

[U05] Py：列表去重且保序
来源：http://dali.shangyingyoupin.top/Article/details/gtxwuezyfo.html

list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtdbqumust.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzgdrmpq.html

{**a, **b}
来源：http://dali.zycfv.cn/Article/details/gtnwjtrmrk.html

[U07] Py：反转字典键值
来源：http://dali.yj202588.top/Article/details/gtegtqwysb.html

{v: k for k, v in d.items()}
来源：http://dali.yj202588.top/Article/details/gtginmvbkc.html

[U08] Py：展平二维列表
来源：http://dali.yonumen.top/Article/details/gtlncebdwi.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gturzpnlye.html

[U09] Py：字典取最大值的键
来源：http://dali.guowangkeji.top/Article/details/gthvqpmiyb.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gtanpqzlbn.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtwqpkmtmn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.iojbl.cn/Article/details/gtlbmnbyzd.html

[U11] Py：生成器表达式
来源：http://dali.jianghu66.top/Article/details/gtnibmsosm.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gtaihkritb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xinyue.icu/Article/details/gtzyacmxxf.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gtkrtxhbsj.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gtmoaihyqm.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gtgnvceyob.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gtpemggwcd.html

defaultdict(list)
来源：http://dali.ydzc1.top/Article/details/gtijnixsrb.html

[U15] Py：高精度计时
来源：http://dali.aizwys.cn/Article/details/gtxkxhsdgy.html

t = time.perf_counter()
来源：http://dali.hywenlv.cn/Article/details/gtqxnfsmid.html

[U16] Py：命令行参数解析
来源：http://dali.gogol.net.cn/Article/details/gtslnquqcg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yvedp.cn/Article/details/gtjnfzdzax.html

[U17] Py：初始化日志
来源：http://dali.yj202588.top/Article/details/gtzooxwejp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pengpengdd.cyou/Article/details/gtkfhkpqib.html

[U18] Py：预编译正则
来源：http://dali.xuanzx.com/Article/details/gtvashropk.html

pat = re.compile(r"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtaztiuoih.html

[U19] Py：正则替换带回调
来源：http://dali.guannengcc.top/Article/details/gtnhchmgud.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gttxmsfexw.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gteavrvraq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tanke756.top/Article/details/gtgtkrnkjh.html

[U21] Py：自定义上下文管理器
来源：http://dali.sufxvd.cn/Article/details/gtjekprlpr.html

@contextlib.contextmanager
来源：http://dali.jlsjyb.cn/Article/details/gtojxcrynz.html

[U22] Py：矩阵转置
来源：http://dali.havefunace.top/Article/details/gtajzwaqrx.html

list(zip(*m))
来源：http://dali.nanxinkj.top/Article/details/gtydhgtnqb.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gtjmgwtzgm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dianchejie.cn/Article/details/gtblhfsibt.html

[U24] Py：路径操作
来源：http://dali.c1oappe.top/Article/details/gtpydqhrwg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtiyddunxy.html

[U25] Py：CSV 按字典读
来源：http://dali.ivvv.top/Article/details/gtwnbmxaxe.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gtfkqaqzsx.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gtxjtcetzi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yonumen.top/Article/details/gtbktwgqel.html

[U27] Py：异步 HTTP
来源：http://dali.havefunace.top/Article/details/gttabxzpcv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gtkxczipvm.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gteikswmeg.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gtoivailex.html

[U29] Py：属性校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmabmgvz.html

@property 与 @x.setter 配合
来源：http://dali.xylfe.cn/Article/details/gtpwsjnynl.html

[U30] Py：数据类
来源：http://dali.cucudq.cn/Article/details/gtdasbrihd.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gtzoanwtol.html

[U31] Py：单测
来源：http://dali.ydzc1.top/Article/details/gtjwvoodeo.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtjqchojvj.html

[U32] Py：代码格式化
来源：http://dali.jlsjyb.cn/Article/details/gtbfkahwyg.html

ruff format . && ruff check --fix .
来源：http://dali.wangdashe.top/Article/details/gtekwsqbxs.html

[U33] Py：打包发布
来源：http://dali.chenlongwang.top/Article/details/gthhohmxge.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dianchejie.cn/Article/details/gtjdxdoupc.html

[U34] Py：判断编码
来源：http://dali.c1oappe.top/Article/details/gtibqrcgoo.html

chardet.detect(raw)
来源：http://dali.vqdsnc.cn/Article/details/gtzfzvtewp.html

[U35] Py：发送邮件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoodikcil.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gtamdzqzri.html

[U36] Py：定时任务
来源：http://dali.daxiang520.top/Article/details/gtdxabsyhw.html

schedule.every(10).minutes.do(job)
来源：http://dali.dashuyun.cn/Article/details/gtcdkagjtb.html

[U37] Py：读写 Excel
来源：http://dali.zhengqikj.top/Article/details/gtslnuonrw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.haohaochexian.top/Article/details/gtilogwqjz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gtrhlmgvwm.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gtlcefsujh.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gttkydztlo.html

sys.stdout.isatty()
来源：http://dali.sufxvd.cn/Article/details/gtjktnzrjw.html

[U40] Py：打印到标准错误
来源：http://dali.iojbl.cn/Article/details/gtkfazmxqj.html

print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtskfdvamp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyvfccgx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shuidangran.top/Article/details/gtjkpnbnst.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tianlin.xyz/Article/details/gtxxbhzdez.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiuyuzyo.html

[U43] PHP：声明命名空间
来源：http://dali.dashuyun.cn/Article/details/gtoppoztsm.html

namespace App\Http;
来源：http://dali.chenlongwang.top/Article/details/gtemrwuvxz.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gtemjxmpks.html

declare(strict_types=1);
来源：http://dali.yanxiufei.cn/Article/details/gtojvkunqr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.haohaochexian.top/Article/details/gtsozkeydq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtaptsezaw.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gtapdyleon.html

?string $name = null
来源：http://dali.svipenyu.cn/Article/details/gtcsdrjhmp.html

[U47] PHP：联合类型
来源：http://dali.jyoumei.cn/Article/details/gtnxdzwkam.html

int|string $id
来源：http://dali.cashguo.top/Article/details/gtuqysmdzo.html

[U48] PHP：纯枚举
来源：http://dali.fengsongda.top/Article/details/gtrggewqli.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aizwys.cn/Article/details/gtqkqexszm.html


<!-- 参考信息 -->