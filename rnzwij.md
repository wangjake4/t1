代发 wailian999

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtiueavlhf.html

[S29] C：变参函数
来源：http://dali.yj20258.top/Article/details/gtbocldcie.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gtfxwjnkww.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gtxeqekzhk.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtvrfqnqgq.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtxostwhwf.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtdykfwerp.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtvhrotlsh.html

#include <iostream>
来源：http://dali.zhoulong.xyz/Article/details/gtxvoplgpp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gtyvwjxgbr.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gtmzbutgyg.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gtsfrrjdyt.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtmyqgvgtr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gtbxxrieps.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gtnnrvnujr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtnpxatazo.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gtwxdyibcu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gteshzhwyk.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gtjhurwfhw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtufcerbiz.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gtlfwdepfy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gtvdwployj.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gtplhyghkd.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtpzkylvul.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtgdcvafmk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gtimrarttq.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtsmrvpkfj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gticmbggdr.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtkiqsltkb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtyulmcatr.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gtixndeoqa.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gtxsszhmuy.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtjkguhlmg.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gturgvdsun.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gtktnuudul.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gthhjnzoca.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gtnibqeeuc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gtxhljbprk.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtybilxvlr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258.top/Article/details/gtpsmtdalg.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gtgfcjhfam.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gternkngdv.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gthvpbagvk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gtzzkouaam.html

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gteopgwchv.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gtypvdabgp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daxiang520.top/Article/details/gtmmpzqmyv.html

[S50] C++：格式化数字
来源：http://dali.hammf.cn/Article/details/gtbmbmobje.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtowqrxzdj.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gtbkjyqevw.html

static_cast<double>(a) / b
来源：http://dali.c1oappe.top/Article/details/gtkhjltcog.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtmlqcexij.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gtigebimzo.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gtsniszlpd.html

std::vector<int> w = std::move(v);
来源：http://dali.hammf.cn/Article/details/gtvdlwiyqy.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gtgiiyychd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtemwivprq.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gtihekushy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtropqlzer.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gteggleqdy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gtuwxvboti.html

[S57] C++：编译期常量
来源：http://dali.hfpthk.cn/Article/details/gtjkmthrmf.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtimhosnks.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gtrxexjivp.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gtppxabudq.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gtsvwvliii.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gttohyhtdo.html

[S60] C++：遍历并删除元素
来源：http://dali.cashguo.top/Article/details/gtkruyerye.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gtdzpltusl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgjdfrorn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtijladpik.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtexybxiqd.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gtsmsihaqe.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtdzdqrrjk.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtswzromre.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gtwlxhsraf.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258888.top/Article/details/gtdpbbodsy.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtfuwkqpwh.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gtdzhevwsb.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gtjhmhgojm.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtwhfpdaba.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gtxgxonqta.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtspkaarfo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtdiegcddu.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtubavhffr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gtxgdexonh.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gtyybysmrj.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gtxkivaqkt.html

[T09] Kotlin：扩展函数
来源：http://dali.birdmap.top/Article/details/gtaowyyftm.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gtiuddjhul.html

[T10] Kotlin：默认参数
来源：http://dali.jianghu66.top/Article/details/gttjabltpe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gtpgqhdbun.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gtvmlosnih.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gtuerfgdmg.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtzzwenevw.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtknrquxjz.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gtonodgmmj.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtvecjnmbh.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gtqulazvfc.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtjgwfnqhe.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gtypjdobnw.html

interface Shape { fun area(): Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqneycbsn.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtmsbowzwv.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtvkmfmtzz.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gtizlgduqx.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gtwqipygwu.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtvzukvoez.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gtjjjstkct.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gtlcoqbbsu.html

if let n = opt { print(n) }
来源：http://dali.gotoacloud.top/Article/details/gtucrdlvxr.html

[T20] Swift：数组操作
来源：http://dali.xylfe.cn/Article/details/gtfcvbrpqn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tianlin.xyz/Article/details/gthknpsrkv.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gtrclhovgv.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gtngljogbw.html

[T22] Swift：字典
来源：http://dali.meibo888.top/Article/details/gtofisplqi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtkrmfvvmb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gtfxhqvfrn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtofwqiuzx.html

[T24] Swift：闭包
来源：http://dali.nanxinkj.top/Article/details/gtlcvxepcb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gteclvhbac.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gtprpdithw.html

struct P { var x: Int }
来源：http://dali.mhx1999.top/Article/details/gtyikzcrsi.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtiotkpyje.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gtqosvuicz.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtyjuzkywo.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzkvrlkd.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinncljkm.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gtolwrxkgq.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gtqiencywe.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gttmhrbgll.html

[T30] Swift：协议
来源：http://dali.sufxvd.cn/Article/details/gtcerrjoey.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gtzpiurckn.html

[T31] Lua：Hello World
来源：http://dali.xziqi.cn/Article/details/gtxfpshteb.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtesdhvwps.html

[T32] Lua：局部变量
来源：http://dali.fengsongda.top/Article/details/gtnmfunqgd.html

local a = 1
来源：http://dali.quarkkingdee.top/Article/details/gtwnhrbiul.html

[T33] Lua：表（数组）
来源：http://dali.dashuyun.cn/Article/details/gthwvodhgo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuxming.cn/Article/details/gtmwhcyppg.html

[T34] Lua：遍历表
来源：http://dali.c1oappe.top/Article/details/gtqudumvsa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gtzmrypvek.html

[T35] Lua：字典表
来源：http://dali.zhiwuduotai.top/Article/details/gtojqvqpok.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gtcjfgujpa.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gtgkfizjfb.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpewzucu.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtjndnusht.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtliucbtzr.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gtyfxuyuys.html

if x > 0 then print("正") end
来源：http://dali.yj20258.top/Article/details/gtsevsncmp.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtymxtuaqt.html

string.find(s, "%d+")
来源：http://dali.daxiang520.top/Article/details/gtnvhqkmea.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtwtuydjjx.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtewbwemom.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrsmppau.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtevveodpc.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gtcywxkrfa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtboihqfvz.html

[T43] Perl：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtmkxvpnce.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gtjfwcwrvr.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gtijgykoql.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258.top/Article/details/gtqigxxmoc.html

[T45] Perl：数组遍历
来源：http://dali.zhengqikj.top/Article/details/gtdpcsctwl.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gtxzwbqfuo.html

[T46] Perl：哈希操作
来源：http://dali.hongshengwenyu.top/Article/details/gtygkqopot.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gtglunmubb.html

[T47] Perl：正则捕获
来源：http://dali.yuanzhike.top/Article/details/gtazrizpmk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuanzx.com/Article/details/gtpxgycmyb.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gtcacsyxqg.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gtniotlftp.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gtfjzdyxxr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtdzrojtsy.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtryohpidt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gtecszrsmv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrwofxyb.html

[T51] Scala：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtwjmhwxyh.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtovuhnbjq.html

[T52] Scala：变量
来源：http://dali.iojbl.cn/Article/details/gtszfuqfqq.html

val a = 1;  var b = 2
来源：http://dali.zycfv.cn/Article/details/gtfeiwdwkf.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtkcbfhavu.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtcoaeuqrn.html

[T54] Scala：集合映射
来源：http://dali.smart0.xyz/Article/details/gtduuqrtap.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtiybqdsei.html

[T55] Scala：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtpwkavmfd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gtpofoqjio.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gtsxqkxkux.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtbhkqyleb.html

[T57] Scala：模式匹配
来源：http://dali.316326.xyz/Article/details/gtuhpcydel.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aizwys.cn/Article/details/gtebxpgmoq.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gternevlnk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gtssnaiovh.html

[T59] Scala：循环
来源：http://dali.fengsongda.top/Article/details/gtppnxgwem.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtyyqurwjf.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gtolijjcat.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gtfhdmvjeo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtemwrrqrl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gtepnaitym.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtjhtnfngt.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gtqoxsgfux.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gtlooaaxnk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgufenzy.top/Article/details/gtnavhdzof.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gtarwhjych.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtcmabbhka.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gtvuwxtkhl.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtuwuenkug.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fzhhl.top/Article/details/gtlhhlfdps.html

[U05] Py：列表去重且保序
来源：http://dali.yuxming.cn/Article/details/gtevmqxptp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtjxnysyne.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gtkokspgih.html

{**a, **b}
来源：http://dali.cdnleiting.top/Article/details/gtxxytyxhb.html

[U07] Py：反转字典键值
来源：http://dali.tanke756.top/Article/details/gtdibhpqah.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gtiztgwgbm.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gtinprzudy.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytdaehrw.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgufenzy.top/Article/details/gtdxbmqbyw.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gtodygmbqw.html

[U10] Py：按值排序字典
来源：http://dali.wangshuangyany.cn/Article/details/gtykwzkzpa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yvedp.cn/Article/details/gtuvqwmjei.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gtqofhsuwk.html

(x * 2 for x in arr)
来源：http://dali.pycfn.com/Article/details/gtnmnkuzwg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gtxrdrkoex.html

Counter(arr).most_common(3)
来源：http://dali.sweek.top/Article/details/gtpcauytgy.html

[U13] Py：固定长度队列
来源：http://dali.hysaishi.cn/Article/details/gtabbiuvez.html

deque(maxlen=10)
来源：http://dali.yongpay.top/Article/details/gtlsilutbb.html

[U14] Py：分组收集到列表
来源：http://dali.chenzaomai.com/Article/details/gtcewlqctp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gtqbjjzsvi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gtvfllhgfz.html

t = time.perf_counter()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmsynlpz.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gtnstiekas.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daria6918.cn/Article/details/gtyjmfsiwl.html

[U17] Py：初始化日志
来源：http://dali.yj20258888.top/Article/details/gtjzvuzmeh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yvedp.cn/Article/details/gtqepyqhxy.html

[U18] Py：预编译正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnckkpwdr.html

pat = re.compile(r"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtsarvlvme.html

[U19] Py：正则替换带回调
来源：http://dali.gaohongyu789.top/Article/details/gtccnigous.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hammf.cn/Article/details/gttxoaloyg.html

[U20] Py：缓存函数结果
来源：http://dali.daxiang520.top/Article/details/gttxhbvlwp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.haohaochexian.top/Article/details/gtdfzgouce.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gtnmausajd.html

@contextlib.contextmanager
来源：http://dali.zhengqikj.top/Article/details/gtudqnzlpn.html

[U22] Py：矩阵转置
来源：http://dali.0kj1m.cn/Article/details/gtnbqsxmeo.html

list(zip(*m))
来源：http://dali.xuetiantiany.cn/Article/details/gtabygcytg.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gtztduojya.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.mhx1999.top/Article/details/gtaskuahkc.html

[U24] Py：路径操作
来源：http://dali.yvedp.cn/Article/details/gtgitpacxj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtffywdlxk.html

[U25] Py：CSV 按字典读
来源：http://dali.ivvv.top/Article/details/gtbuhabakl.html

csv.DictReader(f)
来源：http://dali.jianghu66.top/Article/details/gtsgqjmbsm.html

[U26] Py：并发下载
来源：http://dali.sufxvd.cn/Article/details/gtxkqmmklm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.0kj1m.cn/Article/details/gtfuuyvpki.html

[U27] Py：异步 HTTP
来源：http://dali.dianchejie.cn/Article/details/gtjqphvpsi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nwbrower.top/Article/details/gtwnglwmci.html

[U28] Py：类型别名
来源：http://dali.vqdsnc.cn/Article/details/gtcnihnacf.html

UserId = int
来源：http://dali.yvedp.cn/Article/details/gtgdebsxst.html

[U29] Py：属性校验
来源：http://dali.daria6918.cn/Article/details/gtzhejvrek.html

@property 与 @x.setter 配合
来源：http://dali.wangshuangyany.cn/Article/details/gtdccneoxo.html

[U30] Py：数据类
来源：http://dali.nwbrower.top/Article/details/gtryczsolk.html

@dataclass(slots=True)
来源：http://dali.aibaodan.cn/Article/details/gtxaboxlbx.html

[U31] Py：单测
来源：http://dali.svipenyu.cn/Article/details/gtvtjygsxz.html

python -m pytest -q
来源：http://dali.jyoumei.cn/Article/details/gtmrlrcgrn.html

[U32] Py：代码格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtlmbblgtj.html

ruff format . && ruff check --fix .
来源：http://dali.yuxming.cn/Article/details/gtvtgspgvj.html

[U33] Py：打包发布
来源：http://dali.snrcjt.cn/Article/details/gtubxeiakn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ybcxt.top/Article/details/gtkutvsryg.html

[U34] Py：判断编码
来源：http://dali.dianchejie.cn/Article/details/gtuhixyrqh.html

chardet.detect(raw)
来源：http://dali.mhx1999.top/Article/details/gtrhsxmdwo.html

[U35] Py：发送邮件
来源：http://dali.quarkkingdee.top/Article/details/gthkvilfkl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.andypj.xyz/Article/details/gtkzczvaos.html

[U36] Py：定时任务
来源：http://dali.gzhubu.top/Article/details/gtkmvtwmhr.html

schedule.every(10).minutes.do(job)
来源：http://dali.feifeiyinyue.top/Article/details/gtbbljgaor.html

[U37] Py：读写 Excel
来源：http://dali.yj20258888.top/Article/details/gtmztaltjy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fengsongda.top/Article/details/gtjhbfjxvj.html

[U38] Py：获取脚本所在目录
来源：http://dali.shzxlz.cn/Article/details/gtjfteljrs.html

Path(__file__).resolve().parent
来源：http://dali.jqgfzy.top/Article/details/gtwxfownvh.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnqzz.top/Article/details/gtkoinuihx.html

sys.stdout.isatty()
来源：http://dali.gogol.net.cn/Article/details/gtolnplcyd.html

[U40] Py：打印到标准错误
来源：http://dali.yuanzhike.top/Article/details/gtnypesefx.html

print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gtgwmopfcz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sufxvd.cn/Article/details/gtnmzjrtch.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guannengcc.top/Article/details/gtkfokovjz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tianlin.xyz/Article/details/gtujjzoyim.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnxiangtu.top/Article/details/gtasmhozue.html

[U43] PHP：声明命名空间
来源：http://dali.dianchejie.cn/Article/details/gtihnfsyoj.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gtdxtmuity.html

[U44] PHP：开启严格类型
来源：http://dali.fzhhl.top/Article/details/gtmptxslrt.html

declare(strict_types=1);
来源：http://dali.gogol.net.cn/Article/details/gtjjapdhby.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gthspykvzu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtntcpwxhj.html

[U46] PHP：可空类型
来源：http://dali.hongshengwenyu.top/Article/details/gtjxvdssut.html

?string $name = null
来源：http://dali.jqgfzy.top/Article/details/gtynbonfzz.html

[U47] PHP：联合类型
来源：http://dali.jinqigfzy.top/Article/details/gtrfblnujw.html

int|string $id
来源：http://dali.nanxinkj.top/Article/details/gtngaqmlsn.html

[U48] PHP：纯枚举
来源：http://dali.fengsongda.top/Article/details/gtduvacbbi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.316326.xyz/Article/details/gtzubdouqq.html

[U49] PHP：只读属性
来源：http://dali.meibo888.top/Article/details/gtqvzvvwzn.html

public readonly string $name
来源：http://dali.yueranfly.top/Article/details/gtgkqyyqgj.html

[U50] PHP：构造器属性提升
来源：http://dali.hfpthk.cn/Article/details/gtkvkadulj.html

public function __construct(private int $id) {}
来源：http://dali.gzhubu.top/Article/details/gtsnkgthtd.html

[U51] PHP：数组解构
来源：http://dali.tanke756.top/Article/details/gtkazcmyyb.html

[$a, $b] = $arr;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptcxfria.html

[U52] PHP：箭头函数
来源：http://dali.ybcxt.top/Article/details/gtdwenxpnn.html

$double = fn($x) => $x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtydtsmaox.html


<!-- 参考信息 -->