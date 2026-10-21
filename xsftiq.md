代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtldkugdbi.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gtvffyprrp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hammf.cn/Article/details/gtjdjrrdnl.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gtvhqcmbjb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gtawysoyzn.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gtawmjlmyh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gtkriawqfq.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtqkwxellk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gtgphkdmjj.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtgnmmmazp.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtjbdlasxn.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtsmpxzoam.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gtdssctytx.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gtfiujysys.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gthekfnpng.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gtjwasjqrc.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtzkewirxp.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtzwqzqmwg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gthftourac.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtvsxuuhmh.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gtsdtnidjl.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexuryyya.html

#endif
来源：http://dali.tian-w.cn/Article/details/gtieuueizu.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtmhruxfao.html

#include <iostream>
来源：http://dali.yongpay.top/Article/details/gtzgiqujsg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gtpriwklfe.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gtstqtysbv.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gtqltghzxr.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtnksyngpm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gteggjjiro.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gtxmppwzoo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gtwwyogxjv.html

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gtzbdgbpmw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtzkjxxmds.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gtjkplruco.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdrigipi.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtysbhigbd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gtoluomxgg.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gtvcmxgsex.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gtzbpfiruz.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gthbzobijn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gtejnjbyjr.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gthtfbunxo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gtnpjovlql.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gtehakpobt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cqqwz.cn/Article/details/gtyhcfycyx.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gtikbbohav.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gtommocbkv.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtnryhlrof.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gtxfrpzzlp.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gtzufhhqap.html

void inc(int &x) { ++x; }
来源：http://dali.ivvv.top/Article/details/gtukwosozr.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtscfzqglt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtopjqssrf.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtywychaxi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsznaysh.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtvrsciqak.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtywxyqgik.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtwveoinpf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtnsykczjo.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtipwcbblw.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtndvumdhx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtfqeodutm.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuvsdmdb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gthcxjxxba.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gtwobjfbbp.html

static_cast<double>(a) / b
来源：http://dali.gzhubu.top/Article/details/gtosmhlttv.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gtjsegfjzj.html

int size() const noexcept { return n_; }
来源：http://dali.kuanghao11.cn/Article/details/gtcnldfxux.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gtejyseyhl.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gtbotkjquu.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtmlmtnreq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gtqxylnjqh.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gtuiyjaxqt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtzuhlnxma.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gttckhdtiu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gthmstuvaa.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtksmmcpuj.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtkmcdaddh.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gtacjuvphb.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtycdqjkpn.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtechchcge.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gthamshkik.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gteqvwllwj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtclywgwao.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtstzzsrpo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtwuwkobwo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmnotldz.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtpmigfqdc.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gthgsdwzwt.html

[T02] Kotlin：变量
来源：http://dali.xinyue.icu/Article/details/gtboutdmpq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gtfvxxuqmo.html

[T03] Kotlin：字符串模板
来源：http://dali.yuxming.cn/Article/details/gtrohsdavr.html

"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtsnzlwerf.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gttjhfmhtj.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gttwhtftai.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtldzecspr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gtmrypftfh.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gtpbifhnib.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gtdoayumql.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtnqeukckd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gtozkteucp.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtgreulynm.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gtsjiosizo.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtricsbbit.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gtaaxrrudk.html

[T10] Kotlin：默认参数
来源：http://dali.tianlin.xyz/Article/details/gtqwhraetj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gtmiacwttg.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gtufbgkfqn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gtfimxfnux.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gtylbcuegb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtnzqztbyv.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gtpsgqqttp.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtfeabwnkk.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtrwcmwuqk.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtwqvllntc.html

[T15] Kotlin：接口
来源：http://dali.mhx1999.top/Article/details/gtwaxtvojh.html

interface Shape { fun area(): Double }
来源：http://dali.xylfe.cn/Article/details/gtnrenvqan.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtdqpvkiij.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtgdplfuuo.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gtlnwhlgrk.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gtrwfltaik.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtmydotkvz.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gtrptmmkzx.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gtlibrzimu.html

if let n = opt { print(n) }
来源：http://dali.yangfankeji.com/Article/details/gtdtfwcjvo.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwziyicvm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtkotzglmm.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gtwimknkxm.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gtidofpqha.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gtcroxglsi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gtaxppqmdy.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtrfghgkkq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtplxqzfag.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gtnawyodzk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtasuvzsub.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gtojrtmshv.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gtbehvktap.html

[T26] Swift：类与重写
来源：http://dali.mhx1999.top/Article/details/gtscxxuqxc.html

class A: Base { override func f() {} }
来源：http://dali.gaohongyu789.top/Article/details/gtjdtficyo.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gteoewzlwl.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gtomnhuplq.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gtlynjkeox.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtcnrdtzbg.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtokmfmncl.html

guard let x = opt else { return }
来源：http://dali.sysykeji.top/Article/details/gtkpypzrma.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gtifjwddbv.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gtngildcbw.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gtbkrlqddk.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gtglxwcwvz.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gtzvggrpqx.html

local a = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmozhserx.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gtmjjhemei.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tian-w.cn/Article/details/gtdmdpblwe.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gtqgugghxd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gtmygmqpgj.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gtuthbeazg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gtlkalosfg.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gtlwcrckaw.html

function add(a, b) return a + b end
来源：http://dali.sxryk.cn/Article/details/gttxfiiyix.html

[T37] Lua：字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtsnjcrpix.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtttfwimqq.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gtctroatjx.html

if x > 0 then print("正") end
来源：http://dali.fzhhl.top/Article/details/gthsvjmavs.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtzzlvwmoh.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gtgzasdkqe.html

[T40] Lua：元表
来源：http://dali.shzxlz.cn/Article/details/gtybjuyvwc.html

setmetatable({}, { __index = base })
来源：http://dali.xinyue.icu/Article/details/gtiqejqvbe.html

[T41] Perl：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtlpxvoxuf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gtadxlhpth.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gtwsptgrci.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.9152youxi.cn/Article/details/gtnjtteeqb.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gtyfbdtgoi.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gtviuiwlfo.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gtorsqqtnv.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gtaobiqtpv.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gtklekqxmq.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gtyczortfd.html

[T46] Perl：哈希操作
来源：http://dali.jlsjyb.cn/Article/details/gtyuypnipo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gtahynlqum.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gtkpdutnrw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gtheqatgcw.html

[T48] Perl：正则替换
来源：http://dali.yongpay.top/Article/details/gthasaahvi.html

$s =~ s/old/new/g;
来源：http://dali.andypj.xyz/Article/details/gtevipoirj.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gtcdsnbuwx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtbcnrkhgg.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gturhqexqt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gtydtlusti.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gtvmshakmf.html

[T51] Scala：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtboudewjp.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtgvckpcub.html

[T52] Scala：变量
来源：http://dali.xuanzx.com/Article/details/gtgfjfftdf.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gtagwkzrgd.html

[T53] Scala：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtzuufupww.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtjsplyoaq.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gtsjplxvts.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbyqdnxy.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtqeyiqhbc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonwnltra.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtzgbjqisu.html

case class User(name: String, age: Int)
来源：http://dali.aizwys.cn/Article/details/gtddfareoe.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtngujioii.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gtiaaxhakg.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gtlhamgghb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gtanhyebve.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gtdonusiif.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtjdgedjqg.html

[T60] Scala：折叠
来源：http://dali.chenlongwang.top/Article/details/gtttmtpnhn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shzxlz.cn/Article/details/gtojztnxgr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlzsljqkt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.0kj1m.cn/Article/details/gtfciyagtx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlralxqyx.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gtfoxstjsp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gtfkrqcfqq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gtfwziitny.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ybcxt.top/Article/details/gtmhhgesgu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gtcxshzhfp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gtswcvpsfu.html

[U04] Py：变量调试打印
来源：http://dali.xylfe.cn/Article/details/gtgjeeewdh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daxiang520.top/Article/details/gtxbmxhrur.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtckvhutxd.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdyqajmy.html

[U06] Py：合并两个字典
来源：http://dali.0kj1m.cn/Article/details/gtjrgtguyi.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gtmksvrwaz.html

[U07] Py：反转字典键值
来源：http://dali.yonumen.top/Article/details/gtmuvaihup.html

{v: k for k, v in d.items()}
来源：http://dali.fzhhl.top/Article/details/gtyfrskdyy.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtipchfedt.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gtpcahvauk.html

[U09] Py：字典取最大值的键
来源：http://dali.yj202588.top/Article/details/gtwptpwwnf.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gtmwcmojvm.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gtlviktswc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvrkpunc.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxmgztsd.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gtbiioyxzh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yonumen.top/Article/details/gtgydpmcaz.html

Counter(arr).most_common(3)
来源：http://dali.yangfankeji.com/Article/details/gtusvzsvmz.html

[U13] Py：固定长度队列
来源：http://dali.chenjidiqi.icu/Article/details/gtcpkbgzfb.html

deque(maxlen=10)
来源：http://dali.aizwys.cn/Article/details/gtesizepow.html

[U14] Py：分组收集到列表
来源：http://dali.daria6918.cn/Article/details/gtclqlfqki.html

defaultdict(list)
来源：http://dali.chenjidiqi.icu/Article/details/gtzswkbwhl.html

[U15] Py：高精度计时
来源：http://dali.hfpthk.cn/Article/details/gtecbrkoel.html

t = time.perf_counter()
来源：http://dali.dashuyun.cn/Article/details/gtqnomjzfo.html

[U16] Py：命令行参数解析
来源：http://dali.zhengqikj.top/Article/details/gtvjvtfsew.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jlsjyb.cn/Article/details/gtxkwfutyw.html

[U17] Py：初始化日志
来源：http://dali.hywenlv.cn/Article/details/gtsopivoka.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.havefunace.top/Article/details/gtptfmycif.html

[U18] Py：预编译正则
来源：http://dali.hysaishi.cn/Article/details/gtahgkvywb.html

pat = re.compile(r"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtsytnfvsh.html

[U19] Py：正则替换带回调
来源：http://dali.hfpthk.cn/Article/details/gtctkrpimt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aizwys.cn/Article/details/gtrydszvzv.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gtjizeguay.html

@functools.lru_cache(maxsize=None)
来源：http://dali.svipenyu.cn/Article/details/gtsfzqzerx.html

[U21] Py：自定义上下文管理器
来源：http://dali.hywenlv.cn/Article/details/gtuhfwnbhl.html

@contextlib.contextmanager
来源：http://dali.jianghu66.top/Article/details/gtziyncche.html

[U22] Py：矩阵转置
来源：http://dali.wangdashe.top/Article/details/gtfdlgnlye.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gtooeiuvys.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gtklbqhkcw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gtgazjavgl.html

[U24] Py：路径操作
来源：http://dali.feifeiyinyue.top/Article/details/gtbzmyvmcf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtupgnvbvh.html

[U25] Py：CSV 按字典读
来源：http://dali.9152youxi.cn/Article/details/gtqwjaeczk.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gtbhhtttxe.html

[U26] Py：并发下载
来源：http://dali.c1oappe.top/Article/details/gtbgeuxxke.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gtxkctnfdx.html

[U27] Py：异步 HTTP
来源：http://dali.havefunace.top/Article/details/gtxwrwhaco.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gtdsofpsqm.html

[U28] Py：类型别名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnpbypds.html

UserId = int
来源：http://dali.mhx1999.top/Article/details/gtnxyegqnj.html

[U29] Py：属性校验
来源：http://dali.pycfn.com/Article/details/gtvyijmyhs.html

@property 与 @x.setter 配合
来源：http://dali.yj20258.top/Article/details/gtizjqumou.html

[U30] Py：数据类
来源：http://dali.hammf.cn/Article/details/gtqsoqhfqm.html

@dataclass(slots=True)
来源：http://dali.aizwys.cn/Article/details/gtxvmbfkmc.html

[U31] Py：单测
来源：http://dali.havefunace.top/Article/details/gtjjkysoyz.html

python -m pytest -q
来源：http://dali.nanxinkj.top/Article/details/gtuntnjjmz.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsofoyjha.html

ruff format . && ruff check --fix .
来源：http://dali.haohaochexian.top/Article/details/gtjnopkcwb.html

[U33] Py：打包发布
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsqxvyzn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinqigfzy.top/Article/details/gtjzanannf.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gtgtazvzib.html

chardet.detect(raw)
来源：http://dali.sweek.top/Article/details/gtvinoipne.html

[U35] Py：发送邮件
来源：http://dali.xziqi.cn/Article/details/gtphmixrcn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sxryk.cn/Article/details/gtwqjostzi.html

[U36] Py：定时任务
来源：http://dali.shuidangran.top/Article/details/gtwlplsbqs.html

schedule.every(10).minutes.do(job)
来源：http://dali.daria6918.cn/Article/details/gttjoqxqbl.html

[U37] Py：读写 Excel
来源：http://dali.pengpengdd.cyou/Article/details/gtbeegzdgv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dianchejie.cn/Article/details/gtrmrkqxky.html

[U38] Py：获取脚本所在目录
来源：http://dali.zdqjudy.top/Article/details/gtvfiqvors.html

Path(__file__).resolve().parent
来源：http://dali.gzhubu.top/Article/details/gtqctycwmx.html

[U39] Py：判断是否在交互环境
来源：http://dali.ivvv.top/Article/details/gtaukzjqjs.html

sys.stdout.isatty()
来源：http://dali.hnqzz.top/Article/details/gtfcprjoyu.html

[U40] Py：打印到标准错误
来源：http://dali.jyoumei.cn/Article/details/gtoygnibqh.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtbzowwgai.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxinkj.top/Article/details/gtpegiwshz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.svipenyu.cn/Article/details/gtbtznjcma.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hfpthk.cn/Article/details/gtumpisrhm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuanzhike.top/Article/details/gtotwuezrs.html

[U43] PHP：声明命名空间
来源：http://dali.nwbrower.top/Article/details/gtvtvanjsr.html

namespace App\Http;
来源：http://dali.gaohongyu789.top/Article/details/gtmrawtvuw.html

[U44] PHP：开启严格类型
来源：http://dali.jiagoushi.top/Article/details/gtgzzjwhgp.html

declare(strict_types=1);
来源：http://dali.cheryme.top/Article/details/gtkmnonfjq.html


<!-- 参考信息 -->