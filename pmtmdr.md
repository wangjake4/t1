代发 wailian999

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtrogbojlo.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtevftizmq.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gtwvbqjzeg.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtkyavnefi.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gtlwuiabdc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtntwqszhs.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtefqczqck.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gtcwwnalph.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gtlzdixnab.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuanzx.com/Article/details/gtzkxpufuz.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtnrqflfww.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gtmyyggogb.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtbbkrruii.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtsqgyjzjd.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtgydsbjzs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcevmfgjv.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtbeutbgpl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gtuibhheyz.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gtphekbvpv.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gtivlkuvae.html

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gtvjgosheo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gtajykbwnj.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gtsyizkqng.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gthtdnpyag.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtdisuohfb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtzjxyyuzh.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gtgcefntft.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gteyxavixa.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtwemnmrbp.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gtcslawbpz.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gtkvbqqimg.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gtsqrdknom.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gtoflqkili.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gtzfgtzsdv.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gtorhstuza.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gtykvodkgm.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gtmyeybkmc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gtmnnuuscb.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbmadztc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gthyestnkz.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtsfdoqqzc.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtmnpaygdr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gthmnlnxeo.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtydinizpz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtxvzuvawm.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtvejvrlnn.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtvarpeipu.html

[S52] C++：const 与 noexcept
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbmqcbtw.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gtpzgtggnj.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtncemsqao.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gtqvdgjihg.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtqghtzrzz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gtwcppukqt.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtecihhthg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gtkrwehfzz.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtnnohcbps.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuluieuhy.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gtcniknrvz.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtyydlfozp.html

[S58] C++：命名空间
来源：http://dali.yj20258.top/Article/details/gtacmkvedr.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gtephppcdc.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gtwchvflpw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gtcaatczdd.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gtzgghccbg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gtrnljstvd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttcgaevvl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuqhizxl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqucowxde.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtedoiyygz.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtaqfaupgq.html

[T02] Kotlin：变量
来源：http://dali.sufxvd.cn/Article/details/gtyshlxjzl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtslmitveb.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gtghivzubb.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtwmnohmri.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gtsnmqweyl.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gtkdyqygke.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtmehqiiqk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtjzgzcbaz.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gtzyemnxsf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gtgrrfxtus.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtzuakohzo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daxiang520.top/Article/details/gtiycftdxx.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gtmrctegyo.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gteuhegcvu.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtvawljnlr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gtjngyrquc.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtpjbyzsra.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gtifjlnucy.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gtoodrrzws.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gtcuohpvin.html

[T12] Kotlin：解构声明
来源：http://dali.ybcxt.top/Article/details/gtoixcfafw.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtfnjfgsfq.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gttrbfkobi.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gtqhckbzjp.html

[T14] Kotlin：循环
来源：http://dali.zdqjudy.top/Article/details/gtqmfgyhxq.html

for (i in 1..10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtbwzlxgmt.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gtmzworyin.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtjpywajkk.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtpqypfpus.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtqrfjwlpy.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gtnknnedvu.html

var a = 1;  let b = 2
来源：http://dali.jiagoushi.top/Article/details/gtvdkfyrus.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtwxoocrgi.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtbtkcxxxv.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtixneoyai.html

if let n = opt { print(n) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvutyjtev.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gtxwoiacbx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gtvgfvbkwt.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gtuwjwkeih.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gtijbndvvi.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcimpvap.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gtqzvaxpac.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gtaulsptmm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdligstsj.html

[T24] Swift：闭包
来源：http://dali.redwolf501.top/Article/details/gtqnaanqgq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtyhzjxvgg.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gtkhiosmtv.html

struct P { var x: Int }
来源：http://dali.zhoulong.xyz/Article/details/gteiumwqiv.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gtpxmlpzfo.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtitzycqah.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gtxggzpkuc.html

do { try f() } catch { print(error) }
来源：http://dali.yongpay.top/Article/details/gthcjffkwb.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gtsmjrvjgq.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gttpsbwmdy.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gtfbuzpepg.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gtsnqdubrz.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gtgfmwbrxl.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtlrpzazei.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtsytzwecm.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtlqvtnkba.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtyrvecgyv.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gthxsabhtt.html

[T33] Lua：表（数组）
来源：http://dali.shuidangran.top/Article/details/gtbtufdoex.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglauzhia.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gtapkrojjx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbelhaedm.html

[T35] Lua：字典表
来源：http://dali.hywenlv.cn/Article/details/gtldfmhptg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gtlrakqeaj.html

[T36] Lua：函数
来源：http://dali.0kj1m.cn/Article/details/gtnrnrywtw.html

function add(a, b) return a + b end
来源：http://dali.yanxiufei.cn/Article/details/gtzimatryh.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtvenyrarn.html

"a" .. "b"
来源：http://dali.feifeiyinyue.top/Article/details/gtcpyzibak.html

[T38] Lua：条件
来源：http://dali.jqgufenzy.top/Article/details/gtekrgchsr.html

if x > 0 then print("正") end
来源：http://dali.yuanzhike.top/Article/details/gtkogbhmzg.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gtqobfgmyg.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gtmivqvfod.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtujzyloxm.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gtorcvhlea.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gtjxfypbca.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtsrbdeext.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gtinhpaiux.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtslbdsftc.html

[T43] Perl：字符串插值
来源：http://dali.smart0.xyz/Article/details/gttifbtrtp.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gtblztljqe.html

[T44] Perl：条件
来源：http://dali.cqqwz.cn/Article/details/gtzzykydog.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gtyjdafdbg.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtrownzusd.html

for my $x (@arr) { print $x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfcpfksf.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gtkpimregn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gtmrecezjk.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gtipiifsvs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gtwzsdadte.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtodzzedfi.html

$s =~ s/old/new/g;
来源：http://dali.xylfe.cn/Article/details/gtffbmxfyf.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gtgruciqze.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtweldnbqf.html

[T50] Perl：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gthavfvkpa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gtedmezjik.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gtnasywwxx.html

[T51] Scala：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtpdqftlsf.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtfhbjrwbv.html

[T52] Scala：变量
来源：http://dali.jinqigufen.top/Article/details/gtfxmekyev.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtwgggikgs.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtsktvtaoa.html

s"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtaxxjrhmp.html

[T54] Scala：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtuzqcvqxc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gtavpysqqz.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtqssiyxyk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gotoacloud.top/Article/details/gtkpchltwp.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gteejkcclc.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtjsyubyos.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtqpwhnbte.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gtgmzfsmil.html

[T58] Scala：函数定义
来源：http://dali.gaohongyu789.top/Article/details/gtntaqtliu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gtdsozdbsp.html

[T59] Scala：循环
来源：http://dali.guowangkeji.top/Article/details/gtpsmtrpwf.html

for (i <- 1 to 10) println(i)
来源：http://dali.ivvv.top/Article/details/gtdwanaxrj.html

[T60] Scala：折叠
来源：http://dali.gzhubu.top/Article/details/gthqpciyzu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gttwezjfvn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvaloizwb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtuolrfwlh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtsjqzquvz.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gtcvmxmwci.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.mhx1999.top/Article/details/gtaffhnmzo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuanzhike.top/Article/details/gtgyapjgku.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gtjmqthobf.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gtpxvlomhq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.kuanghao11.cn/Article/details/gtwqtcbhwp.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gtzjlhgmbh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.andypj.xyz/Article/details/gtcyzxyeiw.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gtckuokbtn.html

list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtvpreouyp.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtmcflynyv.html

{**a, **b}
来源：http://dali.zhengqikj.top/Article/details/gtbpguqiqp.html

[U07] Py：反转字典键值
来源：http://dali.mhx1999.top/Article/details/gtwcvswrzs.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gtusimjzxq.html

[U08] Py：展平二维列表
来源：http://dali.iojbl.cn/Article/details/gtcsllzxab.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gtsbrrdrpc.html

[U09] Py：字典取最大值的键
来源：http://dali.andypj.xyz/Article/details/gtmpepvcoc.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gtrdlvncbs.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gtrbveceqs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gogol.net.cn/Article/details/gthwlrmqhy.html

[U11] Py：生成器表达式
来源：http://dali.tian-w.cn/Article/details/gtuajqdmcc.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gthkkkwnzu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigfzy.top/Article/details/gtrcicjxdi.html

Counter(arr).most_common(3)
来源：http://dali.jiagoushi.top/Article/details/gtnmcenzvg.html

[U13] Py：固定长度队列
来源：http://dali.gogol.net.cn/Article/details/gtobqysiis.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gtbvkhvjnh.html

[U14] Py：分组收集到列表
来源：http://dali.shuidangran.top/Article/details/gtxvbkgusq.html

defaultdict(list)
来源：http://dali.yongpay.top/Article/details/gtqftbfgen.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gtfolgxnan.html

t = time.perf_counter()
来源：http://dali.yuanzhike.top/Article/details/gtkhvjcmmm.html

[U16] Py：命令行参数解析
来源：http://dali.svipenyu.cn/Article/details/gtfrryhjjs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sweek.top/Article/details/gtdnxarein.html

[U17] Py：初始化日志
来源：http://dali.cqqwz.cn/Article/details/gtnfqjzuus.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigufen.top/Article/details/gtrpgdmxhf.html

[U18] Py：预编译正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gttghwwiwe.html

pat = re.compile(r"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtkeghcumj.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gtzfrvifow.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gtqlmngyyc.html

[U20] Py：缓存函数结果
来源：http://dali.havefunace.top/Article/details/gtffxuvrul.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jyoumei.cn/Article/details/gtjblzufvj.html

[U21] Py：自定义上下文管理器
来源：http://dali.sxryk.cn/Article/details/gtqpwagead.html

@contextlib.contextmanager
来源：http://dali.hysaishi.cn/Article/details/gtkyzdirqq.html

[U22] Py：矩阵转置
来源：http://dali.dashuyun.cn/Article/details/gttsfkarse.html

list(zip(*m))
来源：http://dali.hongshengwenyu.top/Article/details/gtcloynony.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtfvtqbomc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gtvdycodaj.html

[U24] Py：路径操作
来源：http://dali.chenlongwang.top/Article/details/gtqwujzzlu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtsjqwcfgm.html

[U25] Py：CSV 按字典读
来源：http://dali.mhx1999.top/Article/details/gtebxueksc.html

csv.DictReader(f)
来源：http://dali.shzxlz.cn/Article/details/gtdphuadsr.html

[U26] Py：并发下载
来源：http://dali.ybcxt.top/Article/details/gtasddhvqp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gtoiaahmuh.html

[U27] Py：异步 HTTP
来源：http://dali.fzhhl.top/Article/details/gtmmstfyls.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj20258.top/Article/details/gthykcubpo.html

[U28] Py：类型别名
来源：http://dali.fengsongda.top/Article/details/gtgbjcskdz.html

UserId = int
来源：http://dali.shangyingyoupin.top/Article/details/gtyjfaamxx.html

[U29] Py：属性校验
来源：http://dali.hywenlv.cn/Article/details/gtywlclspy.html

@property 与 @x.setter 配合
来源：http://dali.yuanzhike.top/Article/details/gthpdtkifj.html

[U30] Py：数据类
来源：http://dali.316326.xyz/Article/details/gtyrxpwwpv.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gtldjlcdub.html

[U31] Py：单测
来源：http://dali.ybcxt.top/Article/details/gtdmmpwxpq.html

python -m pytest -q
来源：http://dali.jiagoushi.top/Article/details/gtsdvdavbz.html

[U32] Py：代码格式化
来源：http://dali.mhx1999.top/Article/details/gtedditmom.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaoncjvb.html

[U33] Py：打包发布
来源：http://dali.hywenlv.cn/Article/details/gtrxzsklgq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.iojbl.cn/Article/details/gttrrdupmg.html

[U34] Py：判断编码
来源：http://dali.fengsongda.top/Article/details/gtdlolmnft.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gtiatdsinm.html

[U35] Py：发送邮件
来源：http://dali.gzhubu.top/Article/details/gthuwzaupl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daria6918.cn/Article/details/gtgryayrom.html

[U36] Py：定时任务
来源：http://dali.yangfankeji.com/Article/details/gthdzsfbtg.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258888.top/Article/details/gtaxrxoboe.html

[U37] Py：读写 Excel
来源：http://dali.yangfankeji.com/Article/details/gtzdwcizdd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhiwuduotai.top/Article/details/gtgiprycux.html

[U38] Py：获取脚本所在目录
来源：http://dali.smart0.xyz/Article/details/gtqltaajvi.html

Path(__file__).resolve().parent
来源：http://dali.nanxuanxn.top/Article/details/gtfglhquww.html

[U39] Py：判断是否在交互环境
来源：http://dali.pengpengdd.cyou/Article/details/gtogxbgfyr.html

sys.stdout.isatty()
来源：http://dali.kuanghao11.cn/Article/details/gtavktmsyw.html

[U40] Py：打印到标准错误
来源：http://dali.jqgfzy.top/Article/details/gtirsqzkzi.html

print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtjywiqzap.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daria6918.cn/Article/details/gtywoyunrs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hywenlv.cn/Article/details/gteghdiazm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.bjfxy.top/Article/details/gtxdsibycy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gthrgqfnuk.html

[U43] PHP：声明命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtctqggqay.html

namespace App\Http;
来源：http://dali.jinqigfzy.top/Article/details/gtchkizjew.html

[U44] PHP：开启严格类型
来源：http://dali.guannengcc.top/Article/details/gtsmglqwkg.html

declare(strict_types=1);
来源：http://dali.havefunace.top/Article/details/gtknunujya.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tianlin.xyz/Article/details/gtsfrczada.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gteiszqpix.html

[U46] PHP：可空类型
来源：http://dali.vqdsnc.cn/Article/details/gtzhbxyogw.html

?string $name = null
来源：http://dali.guannengcc.top/Article/details/gttestniat.html

[U47] PHP：联合类型
来源：http://dali.jqgufenzy.top/Article/details/gtilomfxba.html

int|string $id
来源：http://dali.zhengqikj.top/Article/details/gtuyaqnaaw.html

[U48] PHP：纯枚举
来源：http://dali.jinqigufen.top/Article/details/gttumfnugb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvfaeihds.html

[U49] PHP：只读属性
来源：http://dali.hywenlv.cn/Article/details/gtpgziyygy.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gtkekizeuz.html

[U50] PHP：构造器属性提升
来源：http://dali.redwolf501.top/Article/details/gtdvereiuk.html

public function __construct(private int $id) {}
来源：http://dali.sysykeji.top/Article/details/gtglrowuhy.html

[U51] PHP：数组解构
来源：http://dali.smart0.xyz/Article/details/gttwkdjifk.html

[$a, $b] = $arr;
来源：http://dali.redwolf501.top/Article/details/gttqviawaw.html

[U52] PHP：箭头函数
来源：http://dali.xuanzx.com/Article/details/gtbwzaitsd.html

$double = fn($x) => $x * 2;
来源：http://dali.nwbrower.top/Article/details/gtwqssoqlb.html

[U53] PHP：空合并运算符
来源：http://dali.jiagoushi.top/Article/details/gtwydxdxdo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhongyouzk.top/Article/details/gtncexnkqy.html

[U54] PHP：空安全调用
来源：http://dali.chenzaomai.com/Article/details/gtqlisvfyr.html

$obj?->method()
来源：http://dali.xinyue.icu/Article/details/gtjtwljdmq.html


<!-- 参考信息 -->