代发 wailian999

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqhdyhsx.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gtkbzzmwgi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtgnbqiezn.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraovduxl.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtiplljkps.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gttaazxztj.html

#endif
来源：http://dali.redwolf501.top/Article/details/gtorclzwoa.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtjtznlvhk.html

#include <iostream>
来源：http://dali.zhoulong.xyz/Article/details/gtybfiqsnl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtnfdacyvb.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtbyntnvsd.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gtxotgnelh.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gtcwxugtkw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtbutwbnfx.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gtccgxrcue.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcgnnfeg.html

[S35] C++：map
来源：http://dali.cqqwz.cn/Article/details/gtwvhmgdhq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtekrktdeb.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtaixvphvb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtwnchddhb.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gtukakeute.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtnyokicby.html

[S38] C++：排序
来源：http://dali.0kj1m.cn/Article/details/gtldvmncav.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gtvmfrkbwz.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtlrutptyy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gtbieyuauz.html

[S40] C++：查找元素
来源：http://dali.hongshengwenyu.top/Article/details/gtkcikxfpm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gtfnbgritx.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gttafrktwv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gthcmaeyqd.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gtihollfnj.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtindqrzmc.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gtsvgcowac.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtgizpiyly.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlxfpdgm.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gtvvmwixbu.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtilvaumdp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gtqcdhaspd.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtvcylrccr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gtbwomzkrk.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gtkwwxuhet.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtzwgrworr.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gteygtkfjf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtbloqodcg.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gtknbgocau.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gtxekqwwep.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gtgzalcyfb.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gthpanxvor.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtsfmdwgvg.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gtozesplhr.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gtkzgtucwp.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtmowzwpvu.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gtlyhexpkt.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtlwqqrebc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjxtokej.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtgmstkgqf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtgusxnxkh.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtaukcubry.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.9152youxi.cn/Article/details/gtkspudnwn.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gtzchqvghf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcffawfru.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gtfyibmays.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gtyhoubqgq.html

[S58] C++：命名空间
来源：http://dali.chenzaomai.com/Article/details/gtaomqcwto.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtiyutvsuh.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gtczwidghy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gtsvrztnvo.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gtjofdptcq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtqxtazfvr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthgxhqnem.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gthbxqdjlj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gttbzpckpt.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtqzqeaeuc.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtmxksbgjm.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gtglxshgpk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.c1oappe.top/Article/details/gtofdhicma.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtumxkeqqn.html

"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gthgnzojtv.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gtjaiadrnf.html

val n: String? = null;  n?.length
来源：http://dali.zhongyouzk.top/Article/details/gtwcxfuvdb.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtaiptrgay.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtpxdcozby.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtbwhimiue.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtneetrqyk.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtowbuwigm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gtnahwnhuc.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtdmbvxhgh.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gtfhtodtbi.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gtyqsneocm.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gtfyfmcfkq.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gtytnpbgik.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gtvevucwth.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gtfjlemazt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gtddxjrrwt.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gtcqugvejh.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gtiskcvura.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gtoksmwnee.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gtxxhhylry.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtiqhfqudy.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtkaxbaexy.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gtumlciaov.html

interface Shape { fun area(): Double }
来源：http://dali.hywenlv.cn/Article/details/gthtihpaig.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gtbbjisnbp.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtsjpbmbcc.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gtcvcompkg.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gttqohstyc.html

[T18] Swift：字符串插值
来源：http://dali.wangdashe.top/Article/details/gttzifqvcp.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtldlssgco.html

[T19] Swift：可选绑定
来源：http://dali.haohaochexian.top/Article/details/gtzarlrwzw.html

if let n = opt { print(n) }
来源：http://dali.ybcxt.top/Article/details/gtzxhbqkrx.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtrkuexbau.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlswzbow.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gtgeqngquj.html

for x in a { print(x) }
来源：http://dali.ehwqpu.com/Article/details/gtiwshwjhb.html

[T22] Swift：字典
来源：http://dali.cdnleiting.top/Article/details/gtxjwbdzba.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cheryme.top/Article/details/gtlkgkjiat.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtqneziiho.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hammf.cn/Article/details/gtkkfrnmdv.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gtzqptvukc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtppfornke.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gtoisxcstb.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gtmteuwulb.html

[T26] Swift：类与重写
来源：http://dali.redwolf501.top/Article/details/gtpxjgiucn.html

class A: Base { override func f() {} }
来源：http://dali.cucudq.cn/Article/details/gtzuhrdhev.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtisthruzl.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gtxmwsicwi.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gtiymhjmus.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gtktdelenp.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gthijohywn.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtcbrmbrel.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gtlqwsmwfd.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gtabomxkvu.html

[T31] Lua：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtyivkjiyl.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtzimuaacd.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gtmahixrgx.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gtbupuxvya.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gtxwazoyhb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gtfqmtpqgv.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gtfnaxcuzs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xylfe.cn/Article/details/gtusnrrvxk.html

[T35] Lua：字典表
来源：http://dali.sysykeji.top/Article/details/gthaxaiumo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtfcrjpgid.html

[T36] Lua：函数
来源：http://dali.andypj.xyz/Article/details/gtcufjvkiz.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimovhtch.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gttyxlmnyl.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtqlrjuqmg.html

[T38] Lua：条件
来源：http://dali.hywenlv.cn/Article/details/gtgvsbmaet.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtavchgckp.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtesygqosw.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gtlabwcxkg.html

[T40] Lua：元表
来源：http://dali.hammf.cn/Article/details/gtkhudrxcc.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtfqlinnow.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtagqpsydn.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gtugseyixm.html

[T42] Perl：变量类型
来源：http://dali.yonumen.top/Article/details/gtrutmxdwx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtoyoprdpz.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gtujddcdqn.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gtwiafjrmt.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrzdpabn.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gtzselkmpz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gtjjitvxhx.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gtxlvwoxrn.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtsnepyhrl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gtjrkveffr.html

[T47] Perl：正则捕获
来源：http://dali.zhaomingkeji.xyz/Article/details/gtziilauyb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtndfirwsl.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtgjvpowft.html

$s =~ s/old/new/g;
来源：http://dali.ppjwa.cn/Article/details/gtcusyitwt.html

[T49] Perl：函数
来源：http://dali.meibo888.top/Article/details/gtrojfxxmr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gthmtdzjrd.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtcqzunewr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj202588.top/Article/details/gtsjjotrlt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.snrcjt.cn/Article/details/gtrniiizbz.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtakjbqkil.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtbxgfzixk.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gtmycuqnfv.html

val a = 1;  var b = 2
来源：http://dali.daxiang520.top/Article/details/gtubwyjvyk.html

[T53] Scala：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtitfmzfuh.html

s"值: $b"
来源：http://dali.andypj.xyz/Article/details/gtlmjqtqdi.html

[T54] Scala：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtkuasnzoe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfifeqxo.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtulfucwqb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigfzy.top/Article/details/gttlcjodyy.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtuxthewxp.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtsfmdweix.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtrjduojfm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hywenlv.cn/Article/details/gtueyqwqsm.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gtumuprqpp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffnkythk.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gthungopng.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtxwfmoylz.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtrjqpodxf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuanzhike.top/Article/details/gtykktknuh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtzpsydmdw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtnfhyavxi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtosibbtke.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gtvzdrdaog.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.316326.xyz/Article/details/gtzajjhovv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtktvstqcl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gtnadlrhbm.html

[U03] Py：加载 .env 配置
来源：http://dali.wangdashe.top/Article/details/gtnyxokyvj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ydzc1.top/Article/details/gtozzjyqbf.html

[U04] Py：变量调试打印
来源：http://dali.ybcxt.top/Article/details/gtdvjnhayp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hfpthk.cn/Article/details/gtauittgwj.html

[U05] Py：列表去重且保序
来源：http://dali.c1oappe.top/Article/details/gtcfzyveos.html

list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtnteegdll.html

[U06] Py：合并两个字典
来源：http://dali.tanke756.top/Article/details/gtqtxvnjcr.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gtchtrardb.html

[U07] Py：反转字典键值
来源：http://dali.guowangkeji.top/Article/details/gtoaqktjeh.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfuypcnk.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gtowiauucg.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gtrtpaqkru.html

[U09] Py：字典取最大值的键
来源：http://dali.hammf.cn/Article/details/gtzxfdijhu.html

max(d, key=d.get)
来源：http://dali.yuxming.cn/Article/details/gtuycjqudh.html

[U10] Py：按值排序字典
来源：http://dali.cheryme.top/Article/details/gtakkzuidf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gzhubu.top/Article/details/gtwnuagdsk.html

[U11] Py：生成器表达式
来源：http://dali.andypj.xyz/Article/details/gthnowpniz.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gthzljccdi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xylfe.cn/Article/details/gtzizxmgxm.html

Counter(arr).most_common(3)
来源：http://dali.iojbl.cn/Article/details/gtqaupdnrv.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gtgxqfgbrj.html

deque(maxlen=10)
来源：http://dali.yj20258888.top/Article/details/gtvhazjrvr.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnebrshd.html

defaultdict(list)
来源：http://dali.yj20258888.top/Article/details/gtfyeljtdy.html

[U15] Py：高精度计时
来源：http://dali.xuetiantiany.cn/Article/details/gtttwiujeu.html

t = time.perf_counter()
来源：http://dali.hnqzz.top/Article/details/gtrfelsdhq.html

[U16] Py：命令行参数解析
来源：http://dali.tian-w.cn/Article/details/gtmdacjpih.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangdashe.top/Article/details/gtfbjybube.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gtkzecictt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gtgptgvaby.html

[U18] Py：预编译正则
来源：http://dali.c1oappe.top/Article/details/gtofhxbsgb.html

pat = re.compile(r"\d+")
来源：http://dali.xinyue.icu/Article/details/gthzdpbjhg.html

[U19] Py：正则替换带回调
来源：http://dali.jlsjyb.cn/Article/details/gtuhkqhnet.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jyoumei.cn/Article/details/gtfcojpwej.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258888.top/Article/details/gtsijkqilt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gtggfmviou.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gtgqmwbdfv.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gtlusezmuw.html

[U22] Py：矩阵转置
来源：http://dali.tanke756.top/Article/details/gtuhqvluvg.html

list(zip(*m))
来源：http://dali.chenjidiqi.icu/Article/details/gtgcafpyab.html

[U23] Py：分块读取大文件
来源：http://dali.316326.xyz/Article/details/gtgddhgnez.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nwbrower.top/Article/details/gtbanixlwp.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gtbtmenbjm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtiuhzcveg.html

[U25] Py：CSV 按字典读
来源：http://dali.yueranfly.top/Article/details/gtjtkcigls.html

csv.DictReader(f)
来源：http://dali.bjfxy.top/Article/details/gtjmelsqqq.html

[U26] Py：并发下载
来源：http://dali.smart0.xyz/Article/details/gtmdogielt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cqqwz.cn/Article/details/gtwjjfoakf.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gtxplnyxmx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangshuangyany.cn/Article/details/gtkrykcezr.html

[U28] Py：类型别名
来源：http://dali.svipenyu.cn/Article/details/gtqwxhbnfr.html

UserId = int
来源：http://dali.zhongyouzk.top/Article/details/gtgnvkazya.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gtbuljunye.html

@property 与 @x.setter 配合
来源：http://dali.zdqjudy.top/Article/details/gtiseewlkn.html

[U30] Py：数据类
来源：http://dali.jyoumei.cn/Article/details/gtbesueytn.html

@dataclass(slots=True)
来源：http://dali.dashuyun.cn/Article/details/gtetydeosl.html

[U31] Py：单测
来源：http://dali.sysykeji.top/Article/details/gtrbqnsjzo.html

python -m pytest -q
来源：http://dali.fzhhl.top/Article/details/gtjeolkqac.html

[U32] Py：代码格式化
来源：http://dali.hfpthk.cn/Article/details/gtehhxrqct.html

ruff format . && ruff check --fix .
来源：http://dali.vqdsnc.cn/Article/details/gtssdawvxl.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gtkzxaletj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guowangkeji.top/Article/details/gtufmywjpc.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gtsivffurm.html

chardet.detect(raw)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpmnrxih.html

[U35] Py：发送邮件
来源：http://dali.cqqwz.cn/Article/details/gtlrasgdrj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.iojbl.cn/Article/details/gtcaocoosj.html

[U36] Py：定时任务
来源：http://dali.yanxiufei.cn/Article/details/gtxekfktjd.html

schedule.every(10).minutes.do(job)
来源：http://dali.kuanghao11.cn/Article/details/gtmznrhjdm.html

[U37] Py：读写 Excel
来源：http://dali.smart0.xyz/Article/details/gtmqdrdgut.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guowangkeji.top/Article/details/gtllaxtqxi.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfglawso.html

Path(__file__).resolve().parent
来源：http://dali.quarkkingdee.top/Article/details/gthigmozlf.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gtgaifrnas.html

sys.stdout.isatty()
来源：http://dali.sysykeji.top/Article/details/gtwgyatzrz.html

[U40] Py：打印到标准错误
来源：http://dali.tianlin.xyz/Article/details/gtfguxbudr.html

print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtfkycvapx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tianlin.xyz/Article/details/gtopfxakhn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fengsongda.top/Article/details/gtlkpsozxy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fzhhl.top/Article/details/gtyebfjgwe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gogol.net.cn/Article/details/gtorftnsjs.html

[U43] PHP：声明命名空间
来源：http://dali.cheryme.top/Article/details/gtammjmfmd.html

namespace App\Http;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmalxnqrh.html

[U44] PHP：开启严格类型
来源：http://dali.ydzc1.top/Article/details/gtexfqhwnt.html

declare(strict_types=1);
来源：http://dali.chenjidiqi.icu/Article/details/gtigwlzeob.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gtgktbfjam.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtvosdisnf.html

[U46] PHP：可空类型
来源：http://dali.wangshuangyany.cn/Article/details/gtkrscnvth.html

?string $name = null
来源：http://dali.yj20258.top/Article/details/gtiqoppfts.html

[U47] PHP：联合类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesjuufyt.html

int|string $id
来源：http://dali.smart0.xyz/Article/details/gtkmbsmgjj.html

[U48] PHP：纯枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobxxoyed.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jiagoushi.top/Article/details/gtjxyarojl.html

[U49] PHP：只读属性
来源：http://dali.tian-w.cn/Article/details/gtxbmcnuvy.html

public readonly string $name
来源：http://dali.c1oappe.top/Article/details/gtlwrdlajj.html

[U50] PHP：构造器属性提升
来源：http://dali.tianlin.xyz/Article/details/gtpebkhqst.html

public function __construct(private int $id) {}
来源：http://dali.andypj.xyz/Article/details/gtkvzjljxo.html

[U51] PHP：数组解构
来源：http://dali.hysaishi.cn/Article/details/gttokbtatj.html

[$a, $b] = $arr;
来源：http://dali.shzxlz.cn/Article/details/gttetlxjze.html

[U52] PHP：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gtcsojqlau.html

$double = fn($x) => $x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gtnwzybdnq.html


<!-- 参考信息 -->