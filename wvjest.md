代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gtfmkxvxlb.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtkxpgzicj.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtkziiyghp.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gtcfwhfnof.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtfywslehg.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gtqzbtauts.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiftrbbps.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gtkwofkhgn.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gtnodxtblm.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gtksitatlu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtriwyyvug.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtcmuzjrio.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtksctxhhr.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtuchwpeyb.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtsxtyhilf.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtnumqfhxe.html

#include <iostream>
来源：http://dali.birdmap.top/Article/details/gtvhsqerer.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gtntnkyrwc.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtadehkzmz.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gtwxnwzfnz.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gtwuymqpfj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtqqrsknul.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gtyumnekhk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gtrhcqbsjh.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gtwakhunru.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtrlwufhxe.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtwvnjebjk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtfxxfuhhh.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gtsgskmgud.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gtzviiullu.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gtapwumrgg.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbmpipas.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gttdjzvmmx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gtesgwgihi.html

[S40] C++：查找元素
来源：http://dali.zhoulong.xyz/Article/details/gtqrsfrrfx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gtdrwauhyu.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gttdzdcvkj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gttnfrqpqk.html

[S42] C++：继承与虚函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivkjqmcs.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxuanxn.top/Article/details/gtdgmnpbmr.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gtwlqkbeoe.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gtcckymdce.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gtdkmaongd.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtfvecniis.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gtwtwrsdya.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtwjvgrnxs.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gtnwqjhdpg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gttxflloml.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gtmmbflzcv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gtbmlgolzi.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtrspooboj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gtigijltzb.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhnzuwls.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gtwgtstjcs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtcinybijv.html

[S50] C++：格式化数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxqpbwvh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtojprzjjg.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gtxfahgsyn.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtzmjfgnxg.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtbmhtsujt.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gtcdgvbohj.html

[S53] C++：移动语义
来源：http://dali.pycfn.com/Article/details/gtusbyemyn.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gtivguvryf.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlizjllpm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gttvybdyuf.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtftkboyrp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gtuvfgikxs.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtqdavcgxy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gtmxjehklu.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gtvkqffgeo.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gtcwptatdy.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtviryrkma.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtbwfojpol.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gtykygndhw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gtcnghvexd.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gtcgbyqwde.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtlfwcpprk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtyrtmupuf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtxywxuuku.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdsosjmfp.html

[T01] Kotlin：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtqzzfbdnf.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgaxzeyg.html

[T02] Kotlin：变量
来源：http://dali.yj202588.top/Article/details/gtvdillpcg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlnbktvu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhoulong.xyz/Article/details/gtwqzvkepp.html

"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gtcdbbunut.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdilyffo.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gtrqctcbht.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtacfdqjjn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtolxxurmb.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtsobnhuxl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gtiocfjajz.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gthvhkjkld.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtzcahzfjo.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gtlfsaiteh.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtxutrocnc.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtxkprtrsz.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtfypgxqbf.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtjiouqrjr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.316326.xyz/Article/details/gtlewcejkl.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gtdcoallgb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtvbcmmdmr.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gtbcrabwhc.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtgrkxrxtu.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gtsqdisfku.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtnwlkrjrr.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gtfpqlolxu.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gthijfzodj.html

[T15] Kotlin：接口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxziqeduk.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gthpmqlmeh.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gtmsaaowzf.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtqmpkqubw.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gtkpvyyxwr.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtyygukkmq.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtrnqzazqp.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gtarpatwmv.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gtnkbwyrep.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gtbhtilkru.html

[T20] Swift：数组操作
来源：http://dali.bjfxy.top/Article/details/gtvtijzxnq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtjoqfbp.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gtzntyraai.html

for x in a { print(x) }
来源：http://dali.guannengcc.top/Article/details/gteefewasx.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtnnggqahc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtuymyfvak.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gtikvcrbhl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyanuejo.html

[T24] Swift：闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtwrfytmwb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtkbinkmsf.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdtfqrnk.html

struct P { var x: Int }
来源：http://dali.cqqwz.cn/Article/details/gtsxtkjshl.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gtmwgwlvkf.html

class A: Base { override func f() {} }
来源：http://dali.pengpengdd.cyou/Article/details/gteraeruzg.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gtgncbixif.html

do { try f() } catch { print(error) }
来源：http://dali.zhengqikj.top/Article/details/gtemstcwsu.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gtmvaeizlr.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gtqpbnfowj.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtejvmdthy.html

guard let x = opt else { return }
来源：http://dali.sxryk.cn/Article/details/gthrmltbed.html

[T30] Swift：协议
来源：http://dali.hammf.cn/Article/details/gtkicfjlbo.html

protocol Shape { func area() -> Double }
来源：http://dali.cheryme.top/Article/details/gtyugjggsp.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtkqhtbvzx.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtgmtklgar.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gtiwaabasn.html

local a = 1
来源：http://dali.xylfe.cn/Article/details/gtxgbztypr.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gtgxhyjvch.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gtvqjfbzpu.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gtaihuavkj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gtiuhabdft.html

[T35] Lua：字典表
来源：http://dali.xuanzx.com/Article/details/gtouhywgqw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hysaishi.cn/Article/details/gttbnveglo.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gtrssnnljz.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gtnxsmblkk.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtkbdppcxs.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gttufizcud.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gtkzvqkyzw.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gtzhafsgin.html

[T39] Lua：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyagdszt.html

string.find(s, "%d+")
来源：http://dali.cdnleiting.top/Article/details/gtyeaisglm.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gttggwikbl.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gtylcxpveg.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtfkbmtuly.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtxoouvtnq.html

[T42] Perl：变量类型
来源：http://dali.gogol.net.cn/Article/details/gtqglkksmx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hywenlv.cn/Article/details/gtvupwtnql.html

[T43] Perl：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtoujlitnm.html

"值: $a"
来源：http://dali.cdnleiting.top/Article/details/gtbrcwzsbc.html

[T44] Perl：条件
来源：http://dali.tanke756.top/Article/details/gttifduuyv.html

if ($a > 0) { print "正"; }
来源：http://dali.yonumen.top/Article/details/gtgunclwse.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gteyhqwibp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gthsyrswfd.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gtqlenkexr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hysaishi.cn/Article/details/gtdvcewgpq.html

[T47] Perl：正则捕获
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxunokrq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gtmtfrjfjg.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcltypozo.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gtcgvhqkpm.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gtdcgwfmyp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtjozgbqqw.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtqzgledng.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcpefziv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gtaosxewhh.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gthlppcaeg.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtbcxlkqnv.html

[T52] Scala：变量
来源：http://dali.meibo888.top/Article/details/gtsmvcamhg.html

val a = 1;  var b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwfqhojr.html

[T53] Scala：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtbdcexerl.html

s"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gttptdaqhc.html

[T54] Scala：集合映射
来源：http://dali.birdmap.top/Article/details/gthfelogom.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenzaomai.com/Article/details/gtzojmrovk.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gtwfjuuimt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gthlvvtuzp.html

[T56] Scala：样例类
来源：http://dali.wangdashe.top/Article/details/gtjpccbqgl.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtaiddeqdc.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtsgtobbpa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nwbrower.top/Article/details/gtvwqupzbo.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gtrstkoaug.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258888.top/Article/details/gtgimfilgg.html

[T59] Scala：循环
来源：http://dali.yj20258888.top/Article/details/gtmgqhscbp.html

for (i <- 1 to 10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtyubcsqfd.html

[T60] Scala：折叠
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnzzebzt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gthcqxsfbi.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtexmtodgk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtfiheytmj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttfbnpdns.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gtikvbpkat.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnxiangtu.top/Article/details/gtelifcazg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jyoumei.cn/Article/details/gtiphqjlxs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pengpengdd.cyou/Article/details/gthaybfvgp.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxinkj.top/Article/details/gthimqryon.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gtjqqytvrl.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gtubnmurqv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yonumen.top/Article/details/gtvkjfszwf.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gtwbplrvlt.html

list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtkklzslri.html

[U06] Py：合并两个字典
来源：http://dali.jinqigfzy.top/Article/details/gtlybvjffs.html

{**a, **b}
来源：http://dali.yueranfly.top/Article/details/gtqvaehrkq.html

[U07] Py：反转字典键值
来源：http://dali.feifeiyinyue.top/Article/details/gtdakhzeae.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gtrqtqlrfk.html

[U08] Py：展平二维列表
来源：http://dali.zhixingplan.top/Article/details/gtbhnusbka.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gteyanuedf.html

[U09] Py：字典取最大值的键
来源：http://dali.yangfankeji.com/Article/details/gtwjikofue.html

max(d, key=d.get)
来源：http://dali.hammf.cn/Article/details/gtcecddare.html

[U10] Py：按值排序字典
来源：http://dali.chenzaomai.com/Article/details/gtdeotenec.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfxavton.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gtkqbsghfp.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gthmzprsuo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cashguo.top/Article/details/gtkqfbycwn.html

Counter(arr).most_common(3)
来源：http://dali.redwolf501.top/Article/details/gtvtorlqjh.html

[U13] Py：固定长度队列
来源：http://dali.shangyingyoupin.top/Article/details/gtwvgecaws.html

deque(maxlen=10)
来源：http://dali.ybcxt.top/Article/details/gtznhpqubp.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gtfzarabkl.html

defaultdict(list)
来源：http://dali.yvedp.cn/Article/details/gtbptdgxbg.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gthnzkwqza.html

t = time.perf_counter()
来源：http://dali.wangshuangyany.cn/Article/details/gtgmqldspr.html

[U16] Py：命令行参数解析
来源：http://dali.shzxlz.cn/Article/details/gtytxsvggj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigufen.top/Article/details/gtcwsntlvd.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gtueqmplxa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigufen.top/Article/details/gtzvhyqglu.html

[U18] Py：预编译正则
来源：http://dali.hysaishi.cn/Article/details/gtjjuwaiqi.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gtckdzakxm.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gtkmfymbpw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gtzbzqlzky.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gtlghsjkwr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtzbktolnf.html

[U21] Py：自定义上下文管理器
来源：http://dali.shangyingyoupin.top/Article/details/gtqdljczxp.html

@contextlib.contextmanager
来源：http://dali.sufxvd.cn/Article/details/gtlqotdohq.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gtdprxxsno.html

list(zip(*m))
来源：http://dali.xinyue.icu/Article/details/gtgsvimutm.html

[U23] Py：分块读取大文件
来源：http://dali.cdnleiting.top/Article/details/gtpcebivdh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgbnolig.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gthfvayjyn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gthkuwcidx.html

[U25] Py：CSV 按字典读
来源：http://dali.ydzc1.top/Article/details/gtwucehlqm.html

csv.DictReader(f)
来源：http://dali.zdqjudy.top/Article/details/gtgbjubpkb.html

[U26] Py：并发下载
来源：http://dali.xuanzx.com/Article/details/gtyyyfgapu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuetiantiany.cn/Article/details/gtsahayadd.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gtpioxqpcs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhongyouzk.top/Article/details/gthwimezri.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gtsseoyeso.html

UserId = int
来源：http://dali.hnxiangtu.top/Article/details/gtxazctapq.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtnlviguiw.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gtvzippvfq.html

[U30] Py：数据类
来源：http://dali.dashuyun.cn/Article/details/gtptfrqzrz.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gtdhbgsbmz.html

[U31] Py：单测
来源：http://dali.yvedp.cn/Article/details/gtfjpcilcy.html

python -m pytest -q
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnwfwspk.html

[U32] Py：代码格式化
来源：http://dali.jinqigufen.top/Article/details/gtqyecjgij.html

ruff format . && ruff check --fix .
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawudeovw.html

[U33] Py：打包发布
来源：http://dali.chenlongwang.top/Article/details/gtrthuuglw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gtncehmnqo.html

[U34] Py：判断编码
来源：http://dali.quarkkingdee.top/Article/details/gtbtclisqv.html

chardet.detect(raw)
来源：http://dali.sweek.top/Article/details/gttujriwvd.html

[U35] Py：发送邮件
来源：http://dali.guowangkeji.top/Article/details/gtsemwcbce.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhixingplan.top/Article/details/gtnkpowpjr.html

[U36] Py：定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gthffgvwwp.html

schedule.every(10).minutes.do(job)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewuxrcpx.html

[U37] Py：读写 Excel
来源：http://dali.tanke756.top/Article/details/gtskgiethx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ivvv.top/Article/details/gtumuxuzto.html

[U38] Py：获取脚本所在目录
来源：http://dali.jyoumei.cn/Article/details/gthydhygdo.html

Path(__file__).resolve().parent
来源：http://dali.zhoulong.xyz/Article/details/gtlihxiwvh.html

[U39] Py：判断是否在交互环境
来源：http://dali.xinyue.icu/Article/details/gthorpclre.html

sys.stdout.isatty()
来源：http://dali.c1oappe.top/Article/details/gtctcgmurs.html

[U40] Py：打印到标准错误
来源：http://dali.yanxiufei.cn/Article/details/gtwwdifnpe.html

print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gtnzkvpnjq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258888.top/Article/details/gtdeumejii.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ehwqpu.com/Article/details/gtskjfnqfs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.bjfxy.top/Article/details/gtxvmwtgve.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnxiangtu.top/Article/details/gtzxuujhmp.html

[U43] PHP：声明命名空间
来源：http://dali.daxiang520.top/Article/details/gtnkmkfexi.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gtesbkoxjq.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigfzy.top/Article/details/gtxzounpiq.html

declare(strict_types=1);
来源：http://dali.havefunace.top/Article/details/gthlbslkxf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhiwuduotai.top/Article/details/gtvkwmbdty.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtuwcwnyoa.html

[U46] PHP：可空类型
来源：http://dali.daria6918.cn/Article/details/gtjckiayms.html

?string $name = null
来源：http://dali.cdnleiting.top/Article/details/gtaoqjjvpq.html

[U47] PHP：联合类型
来源：http://dali.cdnleiting.top/Article/details/gtodbmvkwj.html

int|string $id
来源：http://dali.jiagoushi.top/Article/details/gtfgcksvaj.html

[U48] PHP：纯枚举
来源：http://dali.zdqjudy.top/Article/details/gtoypgatzw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.meibo888.top/Article/details/gtcvfbvgxu.html


<!-- 参考信息 -->