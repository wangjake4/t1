代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gtlshhrryn.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gteayfizpy.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtipzggznk.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gtrkzqptsi.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gtypjwnsho.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gtxyhctyqn.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gthznufbxc.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtpqhjbohz.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gtvtllnmbk.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtdjgbpdyd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gtyyluugfy.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gtjlmiwjfi.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtfkxlcdow.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtsiigfnul.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gtxoubiuny.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gtjrtdymci.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtaqiadeau.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gtupswsuek.html

[S32] C++：字符串
来源：http://dali.cashguo.top/Article/details/gtzcqpikfp.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtwituagex.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtfydmpehm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddvyenht.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfrdtsyh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbwjswro.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gtpfivaytv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtpnkqqrxf.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtjoxtzbgw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtpgnhfckn.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohbgqjhy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gttbpuvmge.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtvadbuats.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtazcecgvu.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gtsldevhon.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtfymldsbu.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gtlbjqdwta.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtujrzhfko.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtijnckmcr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gtepjhwupf.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gtqirdwmwx.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gtpwmagmap.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtlmochkle.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gtimqybnfb.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtzcxknwif.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtxfhfsemn.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gtmnlqqwpr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gthtnvysbd.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gtvfojszus.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gtllaywaeb.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gtfzihnkia.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gttjirdipx.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtclnapzwn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtvjdzburj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtgtjtuegq.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtlawxjvav.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gtyptzdvjk.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gtffzckrci.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gtmwqpwirv.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gtepzvbgzh.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gtoiwguwnj.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtfkmhannx.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gtexqiccoj.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtvgkmeoio.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gtmdzkchkk.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gtxczsuvvb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtsivkopsn.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtiikrbgox.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtxtykseoz.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gtwafwyvix.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtrspkkbaf.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtbeeizsuk.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gtgrairuwv.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gtpbsozepc.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtrpmggwcm.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gtopewcpng.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtsvddppob.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gtxhlgtbiv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtpnugzxva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthlcoshbw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtsyxfmyxp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtilikuipq.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtvnuywmjn.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gthmvbuxdh.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gtcvqyhdsx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gtguqkqoiv.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabciqkap.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtwcmulqez.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gthkcwbwrp.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gtzfbybelk.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtvdjjoxit.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gtbzrajent.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gttrdlxiis.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtysvsaefk.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtagwpjwki.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gtrabovdoj.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gtqgewnyly.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtwbgglwpm.html

[T09] Kotlin：扩展函数
来源：http://dali.shuidangran.top/Article/details/gtgropgqhe.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfvuacjv.html

[T10] Kotlin：默认参数
来源：http://dali.sysykeji.top/Article/details/gtjfkqzfar.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpomevdgg.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gtkeyojnnb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gtymzgkyau.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gtmafxmqwl.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258.top/Article/details/gtqiytnwrr.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtfnxslecw.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gtashdwqau.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtqyspneyc.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gtkvfysmco.html

[T15] Kotlin：接口
来源：http://dali.shangyingyoupin.top/Article/details/gtazrwfite.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gtojlhqvxf.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gtwdypvqgk.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtfcrwukpq.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagonhpgc.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtrizebsuk.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtfhghjvbl.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtnrifsori.html

[T19] Swift：可选绑定
来源：http://dali.yanxiufei.cn/Article/details/gtwakvzwqk.html

if let n = opt { print(n) }
来源：http://dali.ppjwa.cn/Article/details/gtgegfpuzd.html

[T20] Swift：数组操作
来源：http://dali.kuanghao11.cn/Article/details/gtzdsydzpf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pycfn.com/Article/details/gtryeoifbl.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gtxkbvjova.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gtjqigcfqy.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gtublntaua.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gtlmktbmmi.html

[T23] Swift：函数
来源：http://dali.aizwys.cn/Article/details/gtfdtvbcqr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nwbrower.top/Article/details/gtdgkqapdo.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gtbusqfujj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtaawxpyzq.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gtcrmnoyjm.html

struct P { var x: Int }
来源：http://dali.zhoulong.xyz/Article/details/gtseoyiuam.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gtygywqsfi.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gtxwfyxabk.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gtaxjjfaqj.html

do { try f() } catch { print(error) }
来源：http://dali.jqgufenzy.top/Article/details/gtjwmwbpgw.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gtnqdbrato.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gtijmryvfy.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gtwthwbaha.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gtfpdzpdoc.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gtyfrtrdvi.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkypvvqwv.html

[T31] Lua：Hello World
来源：http://dali.xinyue.icu/Article/details/gtkkpmlbzs.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gtgqrrrjcb.html

[T32] Lua：局部变量
来源：http://dali.zdqjudy.top/Article/details/gtjhdmmcom.html

local a = 1
来源：http://dali.sufxvd.cn/Article/details/gtitrynajd.html

[T33] Lua：表（数组）
来源：http://dali.sufxvd.cn/Article/details/gtdmnjnrka.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gtfhkhhogf.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gtfnkheysi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtykuvbkds.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gtwwmyxvfi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.redwolf501.top/Article/details/gtkcqxnemt.html

[T36] Lua：函数
来源：http://dali.andypj.xyz/Article/details/gtxvcyytlu.html

function add(a, b) return a + b end
来源：http://dali.ybcxt.top/Article/details/gtdxpotbhq.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcanrmnz.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gtntifgyut.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gtaxnxbsgj.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtgxngdylb.html

[T39] Lua：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtbwjupeur.html

string.find(s, "%d+")
来源：http://dali.cqqwz.cn/Article/details/gtreijpxld.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gtkdwxjevd.html

setmetatable({}, { __index = base })
来源：http://dali.cdnleiting.top/Article/details/gtuwyhbwgb.html

[T41] Perl：Hello World
来源：http://dali.fzhhl.top/Article/details/gtzdkisdkh.html

print "Hello\n";
来源：http://dali.jqgufenzy.top/Article/details/gtdtjjsabt.html

[T42] Perl：变量类型
来源：http://dali.gogol.net.cn/Article/details/gtjnofmwkx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gtyakdzhzj.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtqlgikhhm.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gtyqdqoxgq.html

[T44] Perl：条件
来源：http://dali.yuanzhike.top/Article/details/gtrfofntyx.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gtssiofvob.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtieszwpdc.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gtffpxqzdz.html

[T46] Perl：哈希操作
来源：http://dali.shuidangran.top/Article/details/gtuexdhpcz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gtbzyvygpz.html

[T47] Perl：正则捕获
来源：http://dali.yj20258888.top/Article/details/gthdgwsios.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcyyckvx.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gtaaphzhte.html

$s =~ s/old/new/g;
来源：http://dali.0kj1m.cn/Article/details/gtgmwwhmmw.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gtitqcmppf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gttjjfffay.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gteteiyaap.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gtnaxnirwq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gtpnwelqyc.html

[T51] Scala：Hello World
来源：http://dali.sweek.top/Article/details/gtoujnrgwf.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtenhntwxx.html

[T52] Scala：变量
来源：http://dali.yuanzhike.top/Article/details/gtcynupebk.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gtmuumdbsb.html

[T53] Scala：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtkkoviyxk.html

s"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtnixcrhqo.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gtamqgdymm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtxsxioury.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkosxeisq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtfrpsrjtj.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gtbngxyovl.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gtaqflgojt.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtsfyomxfb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gtojasteqg.html

[T58] Scala：函数定义
来源：http://dali.daria6918.cn/Article/details/gtnrvotzoz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gtzitmjwof.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gtqozrzkcp.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtbstlnmfp.html

[T60] Scala：折叠
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbaqvybkj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gtzeqpqbha.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdpdtczhg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtdrbycthb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtipifmjgc.html

[U01] Py：创建虚拟环境
来源：http://dali.yonumen.top/Article/details/gthzyzbeab.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hywenlv.cn/Article/details/gtuuyildlv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangtech.top/Article/details/gtodnuerxi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuxming.cn/Article/details/gttwjoohwl.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gtskxvcdmh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtqyarkpgd.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gtbcytiiok.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gthlbfjtiy.html

[U05] Py：列表去重且保序
来源：http://dali.sysykeji.top/Article/details/gtjxsuadxp.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtfwsqpqku.html

[U06] Py：合并两个字典
来源：http://dali.sufxvd.cn/Article/details/gteqoiraoz.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gtufmdklse.html

[U07] Py：反转字典键值
来源：http://dali.guannengcc.top/Article/details/gtimbueshi.html

{v: k for k, v in d.items()}
来源：http://dali.shangyingyoupin.top/Article/details/gtowpzsvve.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqowiuoc.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gtdsffzwhm.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gthcswyheh.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gtsnralhda.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gtgcgptxmx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gtcxhywiip.html

[U11] Py：生成器表达式
来源：http://dali.yangfankeji.com/Article/details/gtfrxbvaes.html

(x * 2 for x in arr)
来源：http://dali.fengsongda.top/Article/details/gtkgwwkxog.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gtgwzcaxav.html

Counter(arr).most_common(3)
来源：http://dali.havefunace.top/Article/details/gtjgwepefs.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gtqdjqrrir.html

deque(maxlen=10)
来源：http://dali.xinyue.icu/Article/details/gtggcrpmcw.html

[U14] Py：分组收集到列表
来源：http://dali.jlsjyb.cn/Article/details/gtwdjkdmig.html

defaultdict(list)
来源：http://dali.316326.xyz/Article/details/gtcatowtjh.html

[U15] Py：高精度计时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxagehpol.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gtqgsaodzd.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258.top/Article/details/gtlvudiwch.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shzxlz.cn/Article/details/gtsuejevys.html

[U17] Py：初始化日志
来源：http://dali.meibo888.top/Article/details/gtgsfzczeg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gtpjywuxdw.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gtenzdyrxe.html

pat = re.compile(r"\d+")
来源：http://dali.yj202588.top/Article/details/gtjnbdsaxg.html

[U19] Py：正则替换带回调
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsqhbcok.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258.top/Article/details/gtffabjvgk.html

[U20] Py：缓存函数结果
来源：http://dali.mhx1999.top/Article/details/gtefmevbqb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gtkykomtmb.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gtxqjzzqxn.html

@contextlib.contextmanager
来源：http://dali.tianlin.xyz/Article/details/gtomnswtwo.html

[U22] Py：矩阵转置
来源：http://dali.jinqigufen.top/Article/details/gtzmmqovtv.html

list(zip(*m))
来源：http://dali.wangdashe.top/Article/details/gtpffvqfuj.html

[U23] Py：分块读取大文件
来源：http://dali.hongshengwenyu.top/Article/details/gtkdswyleq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ehwqpu.com/Article/details/gtmuejmyot.html

[U24] Py：路径操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwggozau.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtkdulnslg.html

[U25] Py：CSV 按字典读
来源：http://dali.havefunace.top/Article/details/gtmzcezvte.html

csv.DictReader(f)
来源：http://dali.fengsongda.top/Article/details/gtfojmzunp.html

[U26] Py：并发下载
来源：http://dali.yj20258888.top/Article/details/gtbpsoefkm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gtjivksnua.html

[U27] Py：异步 HTTP
来源：http://dali.yueranfly.top/Article/details/gtfhwmdlnl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.smart0.xyz/Article/details/gtqifotonl.html

[U28] Py：类型别名
来源：http://dali.yuxming.cn/Article/details/gthbbxzzfq.html

UserId = int
来源：http://dali.nwbrower.top/Article/details/gtkvnktklo.html

[U29] Py：属性校验
来源：http://dali.jinqigufen.top/Article/details/gtzkctjynp.html

@property 与 @x.setter 配合
来源：http://dali.chenjidiqi.icu/Article/details/gtyobmebhk.html

[U30] Py：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtbkpohysw.html

@dataclass(slots=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtflylerqd.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gtcfozxkav.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gtasgrlvva.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtvjeoarcy.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gtbknwxcaf.html

[U33] Py：打包发布
来源：http://dali.aizwys.cn/Article/details/gtkaanzzes.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yonumen.top/Article/details/gtzwbuzhew.html

[U34] Py：判断编码
来源：http://dali.ppjwa.cn/Article/details/gtfogdoijq.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gtzilubneg.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtiyxqaepd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangdashe.top/Article/details/gtccwzwugt.html

[U36] Py：定时任务
来源：http://dali.xuanzx.com/Article/details/gtsjevxbio.html

schedule.every(10).minutes.do(job)
来源：http://dali.daria6918.cn/Article/details/gtmmobkbjl.html

[U37] Py：读写 Excel
来源：http://dali.sysykeji.top/Article/details/gtyvulttfb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigfzy.top/Article/details/gtfzqqdpei.html

[U38] Py：获取脚本所在目录
来源：http://dali.cheryme.top/Article/details/gtunvgbltu.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gtqzcxwina.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gtakqwlcqr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gtkvssyaqq.html

[U40] Py：打印到标准错误
来源：http://dali.cashguo.top/Article/details/gtmxusfcra.html

print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gtsrlkbyce.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hongshengwenyu.top/Article/details/gtfvnqdopj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ydzc1.top/Article/details/gttdowckoi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhiwuduotai.top/Article/details/gtibhgsmmx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnxiangtu.top/Article/details/gtebhxucfw.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gtaoeavyvq.html

namespace App\Http;
来源：http://dali.yuxming.cn/Article/details/gtpprpckwn.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gthbcexlhh.html

declare(strict_types=1);
来源：http://dali.sysykeji.top/Article/details/gtjtedawmi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cashguo.top/Article/details/gtatmpetvh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gttnigjyqe.html

[U46] PHP：可空类型
来源：http://dali.tian-w.cn/Article/details/gtnsofyeiz.html

?string $name = null
来源：http://dali.gzhubu.top/Article/details/gtiiuprazr.html

[U47] PHP：联合类型
来源：http://dali.smart0.xyz/Article/details/gtzcykkzuv.html

int|string $id
来源：http://dali.xziqi.cn/Article/details/gtdlrneixv.html

[U48] PHP：纯枚举
来源：http://dali.jyoumei.cn/Article/details/gtmwnzhqgw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhengqikj.top/Article/details/gtmcesszpi.html


<!-- 参考信息 -->