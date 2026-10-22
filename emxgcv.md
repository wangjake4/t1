代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gtobqlyrdz.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gteqchemqh.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtgfutkhmc.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gtgivdiwxv.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gthtakbmzw.html

[S29] C：变参函数
来源：http://dali.hnxiangtu.top/Article/details/gtcaidbutz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gtpiluztrt.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gtrixsqgge.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrcqqbne.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtbzgwkvjo.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtjpwfpuaa.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtocncuctx.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gtxyrxjxvn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxlusyise.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gtnwcyugnk.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gtsakrdqxq.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtlypiwkuc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpkxldmf.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gtscfqcpax.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gtisqwjvtn.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtxiwauujw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtjygofzhp.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtiormrhai.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtifqhsgql.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gtcfgllrus.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gtuyhoxmyc.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gtbohxefsy.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtrdgxszmd.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gtbdotuhdf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtmczjsovi.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtiwoicivs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gtxxaljhtu.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtyktgpyic.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gtzkpjkqwy.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gtiwzytbcq.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtdjgxgvnb.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtimgqgomh.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gtkvamvgty.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gtluxsfwmf.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdiwjdxy.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gtitzsovqy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtruebwzfv.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gtbeerghmt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gtpixzucyl.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtjhzlcmtf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gtqkyaugmf.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtxarlvjer.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtyuwbxxve.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmghaibrd.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtqonnwwjg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnzlqdfl.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gtrqqxjfbd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtgbbadmxp.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtboaiztoi.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gtzjknypqu.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtfouhbray.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gtearjqasr.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkinlbdis.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtczzdyocu.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gtwicketav.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gthtugvkej.html

[S55] C++：结构化绑定
来源：http://dali.cdnleiting.top/Article/details/gtniawqmry.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtvuutlgdn.html

[S56] C++：optional
来源：http://dali.yvedp.cn/Article/details/gtwmqpfidv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwgpocgdn.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtvnvflnhr.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gthbhdhcfl.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gttukyxwov.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtaxolsewd.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gtylbxflrz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gtueohoptd.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gthlfzpzmn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtcrvdyzdk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtyxgsxqya.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtakmaxrpc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtibwazaac.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcwagflz.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttiqstrsv.html

[T02] Kotlin：变量
来源：http://dali.c1oappe.top/Article/details/gtoxrqqafc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gtczflqtal.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gtdmkhgcpz.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gtgilueuqq.html

[T04] Kotlin：空安全
来源：http://dali.cdnleiting.top/Article/details/gtvnlbnfgs.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtttxxsvku.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtxxenatbc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gtwmajahua.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtfjpromvl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtbekzmbzi.html

[T07] Kotlin：集合过滤
来源：http://dali.ivvv.top/Article/details/gtftqpfaeh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtxasshjla.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gtynfeqxfd.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gtfjsviujb.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtdboaurau.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gtsghagpsd.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gtgrakvjkt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gtdsgtfhrm.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gtefwohxuq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtabbvgoui.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gtffuzfneo.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtdobofyuy.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gtmyiqnckb.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtkvpffanu.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gtgvykdljk.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtuuzgfnae.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gtsuwcwwng.html

interface Shape { fun area(): Double }
来源：http://dali.zhiwuduotai.top/Article/details/gtqolrvpgw.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gtxybfbgqy.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzedochnx.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gtopzsjhwe.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtftheniis.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtptatkfgr.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gtxmdowsfu.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gtqoqgnzvt.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtudlukwss.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gtxljmjniq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xylfe.cn/Article/details/gteewcxppt.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtgiwcegpv.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gtbdzozyzw.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gtgbomysmg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtrazgaokz.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gtgizuogfw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.redwolf501.top/Article/details/gtcrtkfudk.html

[T24] Swift：闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtnmdpspnd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqshbojfw.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gtteyzjvvz.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gtvsopdwlk.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gtsebxmvjw.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtthvnngkg.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gtjkquwwbg.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtccwhqfrk.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gtquiscutz.html

enum Color { case red, green }
来源：http://dali.zhoulong.xyz/Article/details/gtrfjbejtp.html

[T29] Swift：guard 提前返回
来源：http://dali.gotoacloud.top/Article/details/gtxipicrxt.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gteohlrgbm.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gtvefnrvdl.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gtnfhccqjm.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gtydueuqdv.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtzxwkveju.html

[T32] Lua：局部变量
来源：http://dali.jiagoushi.top/Article/details/gtrwmanrga.html

local a = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gthvdsxzwg.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggmhsqzu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tanke756.top/Article/details/gtnxtwblpk.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gtkwreuymu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtpwhejyol.html

[T35] Lua：字典表
来源：http://dali.hongshengwenyu.top/Article/details/gtpddonlvg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtsconegic.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtupiwtguj.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtfynylopm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtkqdufqml.html

"a" .. "b"
来源：http://dali.vqdsnc.cn/Article/details/gtrxdcqdba.html

[T38] Lua：条件
来源：http://dali.smart0.xyz/Article/details/gtdhuzkgfg.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gtnllzrobl.html

[T39] Lua：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtfypuzfnn.html

string.find(s, "%d+")
来源：http://dali.zhongyouzk.top/Article/details/gtbhyjvvgn.html

[T40] Lua：元表
来源：http://dali.gotoacloud.top/Article/details/gtbnsinfah.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gthdqkiigg.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtwqeeersf.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gttaegnlpb.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gtrakqjutp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gtycubnsbi.html

[T43] Perl：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtbjljdjvd.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gtrkfuywgg.html

[T44] Perl：条件
来源：http://dali.daxiang520.top/Article/details/gtzzsadwgl.html

if ($a > 0) { print "正"; }
来源：http://dali.aizwys.cn/Article/details/gtvidycryq.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtfbbuqfnd.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gtxzthqntn.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtnrlfdyzt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gtrforhupa.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gtaeuogzds.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cqqwz.cn/Article/details/gtpoidrgda.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqgbbzyn.html

$s =~ s/old/new/g;
来源：http://dali.chenjidiqi.icu/Article/details/gtrzhxtjep.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtlphthwtb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtqzbyfgga.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtvosrkygp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtywzlbmwd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gtwrhwjanh.html

[T51] Scala：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtgckkgltd.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gttxcnuqsz.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtvdzvdvqw.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiabkgoq.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtasnbvzlx.html

s"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtgytnccgc.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtifgdqtas.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xinyue.icu/Article/details/gtcygmxery.html

[T55] Scala：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtnycenivt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtatedxytr.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gtfulquecl.html

case class User(name: String, age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtdlyvotnj.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtwlnxodne.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.9152youxi.cn/Article/details/gtqwlcxpki.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gtxmajsycs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gtyfkpqmwt.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgreiemf.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gtfemkduuu.html

[T60] Scala：折叠
来源：http://dali.meibo888.top/Article/details/gtqigbcnjq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigufen.top/Article/details/gtxzztqdjp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuodchflw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gttjhkpswc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzdrpdehl.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gtjpwwsiqb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbtmlwiw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gtghmokjnw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gtslaqtgfz.html

[U03] Py：加载 .env 配置
来源：http://dali.yvedp.cn/Article/details/gtqhffavbo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gtohdlhgko.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdkogken.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shangyingyoupin.top/Article/details/gtpywagfwq.html

[U05] Py：列表去重且保序
来源：http://dali.cdnleiting.top/Article/details/gtiqkjywvw.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtinetjxsn.html

[U06] Py：合并两个字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcgbbayt.html

{**a, **b}
来源：http://dali.jqgfzy.top/Article/details/gtmbqyhjdu.html

[U07] Py：反转字典键值
来源：http://dali.jyoumei.cn/Article/details/gtfmfopzkz.html

{v: k for k, v in d.items()}
来源：http://dali.dashuyun.cn/Article/details/gtotbvrmqa.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gtaqlnbfnu.html

[y for x in nested for y in x]
来源：http://dali.xylfe.cn/Article/details/gtpbqznlir.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gtzigdpxlz.html

max(d, key=d.get)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhsidrtb.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gtllmshvsh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.quarkkingdee.top/Article/details/gtnctardgh.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gtbngfjaqm.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gtedjnehyd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daxiang520.top/Article/details/gtfyozhydt.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gtzbepiyvt.html

[U13] Py：固定长度队列
来源：http://dali.dashuyun.cn/Article/details/gtwncuhnmz.html

deque(maxlen=10)
来源：http://dali.cashguo.top/Article/details/gtacizihhz.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gtilgmsvhj.html

defaultdict(list)
来源：http://dali.birdmap.top/Article/details/gtyrlfmupo.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gtneybgrxu.html

t = time.perf_counter()
来源：http://dali.jianghu66.top/Article/details/gtetcqzbjk.html

[U16] Py：命令行参数解析
来源：http://dali.hammf.cn/Article/details/gtidhdaeui.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gtzbrladkk.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gtvvsdfjdz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tanke756.top/Article/details/gtuiihxzwv.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gthitguqih.html

pat = re.compile(r"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtvrfjmort.html

[U19] Py：正则替换带回调
来源：http://dali.fzhhl.top/Article/details/gtdrlckmnx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.mhx1999.top/Article/details/gtfhxjglxj.html

[U20] Py：缓存函数结果
来源：http://dali.ehwqpu.com/Article/details/gtqelkcsny.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjhfxrli.html

[U21] Py：自定义上下文管理器
来源：http://dali.nwbrower.top/Article/details/gtnqntqvlz.html

@contextlib.contextmanager
来源：http://dali.xinyue.icu/Article/details/gtgwemgwln.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtdksfvs.html

list(zip(*m))
来源：http://dali.nanxinkj.top/Article/details/gttbisymsl.html

[U23] Py：分块读取大文件
来源：http://dali.ehwqpu.com/Article/details/gttgxeneif.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xylfe.cn/Article/details/gtasjxvezb.html

[U24] Py：路径操作
来源：http://dali.nanxinkj.top/Article/details/gtehuaqouc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtqmmvxyew.html

[U25] Py：CSV 按字典读
来源：http://dali.yuxming.cn/Article/details/gtykspafwg.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gtjainflso.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtrzbxvnrx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.0kj1m.cn/Article/details/gtgpvhmbsr.html

[U27] Py：异步 HTTP
来源：http://dali.hammf.cn/Article/details/gteorfibki.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gtijyuwdxq.html

[U28] Py：类型别名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeofyjzm.html

UserId = int
来源：http://dali.jianghu66.top/Article/details/gtpzahnaph.html

[U29] Py：属性校验
来源：http://dali.shangyingyoupin.top/Article/details/gtwtyrtbbv.html

@property 与 @x.setter 配合
来源：http://dali.yangfankeji.com/Article/details/gtddbkhaij.html

[U30] Py：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzufphni.html

@dataclass(slots=True)
来源：http://dali.snrcjt.cn/Article/details/gtjnammxhj.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gtlnnxmgsw.html

python -m pytest -q
来源：http://dali.guowangkeji.top/Article/details/gtblhxgqpz.html

[U32] Py：代码格式化
来源：http://dali.hysaishi.cn/Article/details/gtzcadrhqj.html

ruff format . && ruff check --fix .
来源：http://dali.daxiang520.top/Article/details/gtwotlrsdg.html

[U33] Py：打包发布
来源：http://dali.pycfn.com/Article/details/gtnqamfcti.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangdashe.top/Article/details/gtulrhwezh.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gtihuojgve.html

chardet.detect(raw)
来源：http://dali.svipenyu.cn/Article/details/gtywpkgxfy.html

[U35] Py：发送邮件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszwrlelj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cashguo.top/Article/details/gtfezixede.html

[U36] Py：定时任务
来源：http://dali.redwolf501.top/Article/details/gttjzygnuu.html

schedule.every(10).minutes.do(job)
来源：http://dali.gzhubu.top/Article/details/gtnfairwsw.html

[U37] Py：读写 Excel
来源：http://dali.yonumen.top/Article/details/gtynlsyogz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258888.top/Article/details/gtkqcjjofx.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnqzz.top/Article/details/gtgnvwyjjh.html

Path(__file__).resolve().parent
来源：http://dali.zycfv.cn/Article/details/gtpiepdlxm.html

[U39] Py：判断是否在交互环境
来源：http://dali.cdnleiting.top/Article/details/gtkczuiloq.html

sys.stdout.isatty()
来源：http://dali.tanke756.top/Article/details/gtdljhcehu.html

[U40] Py：打印到标准错误
来源：http://dali.ybcxt.top/Article/details/gtfqzpwioi.html

print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtshtqckao.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guannengcc.top/Article/details/gtwhxnhkna.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuanzhike.top/Article/details/gtyqmdtvcq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.0kj1m.cn/Article/details/gtmncxryzb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258.top/Article/details/gttlwpcbwg.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gtdxpaznjq.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gthtxekhlf.html

[U44] PHP：开启严格类型
来源：http://dali.chenzaomai.com/Article/details/gtczpbvpjj.html

declare(strict_types=1);
来源：http://dali.birdmap.top/Article/details/gtbvwewwzv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.wangdashe.top/Article/details/gtqfcvbwfb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtggmzelpp.html

[U46] PHP：可空类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbotmpegv.html

?string $name = null
来源：http://dali.yj20258.top/Article/details/gtrfbydqqg.html

[U47] PHP：联合类型
来源：http://dali.cdnleiting.top/Article/details/gtpmvdmnwa.html

int|string $id
来源：http://dali.dashuyun.cn/Article/details/gtdloyqpen.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gtymwzyvuv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gtvgotmqcl.html

[U49] PHP：只读属性
来源：http://dali.xziqi.cn/Article/details/gtypjosuku.html

public readonly string $name
来源：http://dali.nwbrower.top/Article/details/gtmapfugoy.html

[U50] PHP：构造器属性提升
来源：http://dali.cheryme.top/Article/details/gtscprayzl.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gtxwdisiso.html


<!-- 参考信息 -->