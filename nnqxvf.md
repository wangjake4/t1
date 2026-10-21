代发 wailian999

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtqlirqhqc.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gtkcshahpo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gtbgmkirsl.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gtzgonvaba.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gtzbcwqovi.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gtlykvppto.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gtstnkfhkh.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtmjuxfxep.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gtczvmsnew.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtvrogetjz.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gtgrxggnnu.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gtnovgxcvk.html

[S33] C++：vector 增删
来源：http://dali.sxryk.cn/Article/details/gtxokdvkmb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtoptqmzqo.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gtmkclzjca.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gteieqdoww.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtaljkuoxl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtlihkfhad.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gtbpcmgpto.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtqsybupqb.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gteopydryk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnxiangtu.top/Article/details/gtzdaehxpx.html

[S38] C++：排序
来源：http://dali.xuanzx.com/Article/details/gteyuqbojp.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gttyljxfxo.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gtfijmmxxe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gtpgyotpwp.html

[S40] C++：查找元素
来源：http://dali.yj20258888.top/Article/details/gtujidxodp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtezskhshj.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtyesqofdk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtmwyzuqmv.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtngvkfnhn.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtykvylqkg.html

[S43] C++：智能指针
来源：http://dali.zhiwuduotai.top/Article/details/gtrrbwezhq.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gttpcdnodo.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gtnwgkohec.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtcxotzzrb.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtvvjmjuxy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gtnmtuxabj.html

[S46] C++：函数模板
来源：http://dali.gzhubu.top/Article/details/gtddapdsyn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gttoilifra.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gtkztxfwzq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gtzgsfngpz.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtzrsxmasg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gtfrozhclp.html

while (std::getline(in, line)) { }
来源：http://dali.daria6918.cn/Article/details/gtzfeanquk.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtghxohtrr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtzhywkqus.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gtuhwwqnmu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtfefcpxld.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gtgwtdvqtq.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gtsapylmsq.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gtgbimiedt.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gtukdvufps.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtvldbgxtp.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gticdlrgld.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gtekjgcuoq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtkjstudpb.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gtcscvlunr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtflhzzfmb.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtosxymqee.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gtfpqfvjyq.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gtxwljqklr.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtsjgcqf.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gtvazzsivf.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtnehmmvti.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gthftetpta.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtbbctlbig.html

[S60] C++：遍历并删除元素
来源：http://dali.dashuyun.cn/Article/details/gtxkprhoqq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtzehhtxaw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpdqispvl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzmxqokl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtzmokuhav.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtdnduhwyy.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtqtoswxpw.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gtbjdywajf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gtpgymlejp.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtgqcyphkb.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtkzkulrad.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gtqzjcfpia.html

val n: String? = null;  n?.length
来源：http://dali.smart0.xyz/Article/details/gtiryzsbyj.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gtwwmujwjx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jyoumei.cn/Article/details/gtvxcnhtqb.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gtwcrrsbtk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sysykeji.top/Article/details/gtsspdpulg.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtqoqezlnp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtodyrvrsq.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gttrukeebc.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtysksdznb.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gtngwmfxhp.html

fun String.exclaim() = this + "!"
来源：http://dali.cdnleiting.top/Article/details/gtyubsvjhk.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gtwxowzieq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yvedp.cn/Article/details/gtthadrwen.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gtalpghbyr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gtmvcqsfry.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gtuwpdbkya.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtbmxwymzy.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gtkvmduoyg.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtshhmueju.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyefqbsy.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtnteszopi.html

[T15] Kotlin：接口
来源：http://dali.gotoacloud.top/Article/details/gtjfrrhqow.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gtruciffuk.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtxnzkhfsk.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gtftmprboe.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gtlmivkzfn.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gteuvyexec.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtbujzmxaw.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gtqynenrwi.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gtqflhvbnj.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gtgwvkdupz.html

[T20] Swift：数组操作
来源：http://dali.tian-w.cn/Article/details/gtzjuaycwv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gtjtjeaxps.html

[T21] Swift：遍历
来源：http://dali.hnxiangtu.top/Article/details/gtfkoxzdpe.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpriyhvk.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gtypirtayo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gtceeduxfm.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gtisjhbbmr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtrxygcdno.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gtbbuabpvd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtkvxoskjs.html

[T25] Swift：结构体
来源：http://dali.birdmap.top/Article/details/gtffanfloe.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gtbzbwxvnj.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrverezal.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gthvmgedbx.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gthmsvefqy.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gteydfldhj.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gtnqchdfjc.html

enum Color { case red, green }
来源：http://dali.dianchejie.cn/Article/details/gtizudvixl.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gtnmgoclna.html

guard let x = opt else { return }
来源：http://dali.svipenyu.cn/Article/details/gtlohohnjk.html

[T30] Swift：协议
来源：http://dali.jinqigufen.top/Article/details/gtkstamnqm.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gtmtvaimlc.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gtjjuxfrny.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtmpxaddov.html

[T32] Lua：局部变量
来源：http://dali.birdmap.top/Article/details/gtcewxikpd.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtpdahutpz.html

[T33] Lua：表（数组）
来源：http://dali.ybcxt.top/Article/details/gtjqbjmavc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shangyingyoupin.top/Article/details/gtmnwkeovu.html

[T34] Lua：遍历表
来源：http://dali.daria6918.cn/Article/details/gtxkmjanfl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtikdeakdq.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gtotobaylf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtfxkcgwlm.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gtahqqatmg.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gtscgbxruu.html

[T37] Lua：字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtphmtglba.html

"a" .. "b"
来源：http://dali.dashuyun.cn/Article/details/gtgoqitrja.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtxuntpeau.html

if x > 0 then print("正") end
来源：http://dali.yuxming.cn/Article/details/gtzwnebgxy.html

[T39] Lua：模式匹配
来源：http://dali.yj20258.top/Article/details/gtuflsnpps.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gtmucskqfk.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphlctxik.html

setmetatable({}, { __index = base })
来源：http://dali.iojbl.cn/Article/details/gtmzyqmspx.html

[T41] Perl：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtpfxnssex.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gtdvpokwxl.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gtruqvyzzb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtielddyso.html

[T43] Perl：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtfzjpgjyf.html

"值: $a"
来源：http://dali.zycfv.cn/Article/details/gtmtidutnd.html

[T44] Perl：条件
来源：http://dali.yuanzhike.top/Article/details/gtypqorfdv.html

if ($a > 0) { print "正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtpyttjmqr.html

[T45] Perl：数组遍历
来源：http://dali.jqgufenzy.top/Article/details/gtwqrxzzvy.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtlntpfoex.html

[T46] Perl：哈希操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfeztkcx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gtikcykpug.html

[T47] Perl：正则捕获
来源：http://dali.jinqigfzy.top/Article/details/gtxinjhqiu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gtsvkgkrat.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtqcavjvit.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gttixihfui.html

[T49] Perl：函数
来源：http://dali.xinyue.icu/Article/details/gtlkpctuoe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtpxmrtwhr.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtgspciegz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhiwuduotai.top/Article/details/gteqhqkvlx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gtcrmmsrys.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtrwhqtssc.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gtfvsdmryt.html

[T52] Scala：变量
来源：http://dali.aibaodan.cn/Article/details/gtaldqynyp.html

val a = 1;  var b = 2
来源：http://dali.dashuyun.cn/Article/details/gtdfdxbrth.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtxvlfnolm.html

s"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gthswkdedx.html

[T54] Scala：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtjxvcdofk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gtqzkkpffn.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtndapeixi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gtgwsvvysu.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gtfjhugrbs.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gtiwyetwnm.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gttztwkpbl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtqlvbyvwx.html

[T58] Scala：函数定义
来源：http://dali.yj202588.top/Article/details/gtzjholppb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gttbfjmhgr.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtjebdltyx.html

for (i <- 1 to 10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtijyqefgl.html

[T60] Scala：折叠
来源：http://dali.redwolf501.top/Article/details/gtntggbwcm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gtkphbzevq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgdddoxme.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gtgqssutqq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvinttpiz.html

[U01] Py：创建虚拟环境
来源：http://dali.daxiang520.top/Article/details/gtkzbpibvy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daxiang520.top/Article/details/gtrslnknes.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gtkrchsuhz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jlsjyb.cn/Article/details/gthlmzjhmg.html

[U03] Py：加载 .env 配置
来源：http://dali.redwolf501.top/Article/details/gtetxbiwnb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ehwqpu.com/Article/details/gtzintoitb.html

[U04] Py：变量调试打印
来源：http://dali.hnxiangtu.top/Article/details/gtuwfsnxgi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcjfkgvw.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gtaeuvtvow.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtmostxvex.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gtpkyubzhm.html

{**a, **b}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccpzymyx.html

[U07] Py：反转字典键值
来源：http://dali.zhiwuduotai.top/Article/details/gtiockzzqw.html

{v: k for k, v in d.items()}
来源：http://dali.snrcjt.cn/Article/details/gtynowqdgd.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gtcayxehgz.html

[y for x in nested for y in x]
来源：http://dali.redwolf501.top/Article/details/gtrpbezkut.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangtech.top/Article/details/gtrribdyvy.html

max(d, key=d.get)
来源：http://dali.sweek.top/Article/details/gtqlvewvpv.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gtvozeujen.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangshuangyany.cn/Article/details/gtlbcbdmvu.html

[U11] Py：生成器表达式
来源：http://dali.yuxming.cn/Article/details/gtbbrkrowe.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrecbjnmp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.0kj1m.cn/Article/details/gthaiukgna.html

Counter(arr).most_common(3)
来源：http://dali.cucudq.cn/Article/details/gtvbgbezdr.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gtpbhowjef.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gtiujotmlk.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gtlwhacmlz.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gtpfsribjj.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gterzxjvhl.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gtpdeeguby.html

[U16] Py：命令行参数解析
来源：http://dali.guowangkeji.top/Article/details/gtjeivhpgq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.redwolf501.top/Article/details/gtbariglxk.html

[U17] Py：初始化日志
来源：http://dali.fengsongda.top/Article/details/gtbdvarqqm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sysykeji.top/Article/details/gtyndaketr.html

[U18] Py：预编译正则
来源：http://dali.jiagoushi.top/Article/details/gteguwagju.html

pat = re.compile(r"\d+")
来源：http://dali.yueranfly.top/Article/details/gtwdleqgsk.html

[U19] Py：正则替换带回调
来源：http://dali.guannengcc.top/Article/details/gthsxvqyxx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xylfe.cn/Article/details/gtmrhtbwez.html

[U20] Py：缓存函数结果
来源：http://dali.jqgufenzy.top/Article/details/gtwcfcgqig.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jiagoushi.top/Article/details/gtdsqoayrr.html

[U21] Py：自定义上下文管理器
来源：http://dali.svipenyu.cn/Article/details/gtozumkagg.html

@contextlib.contextmanager
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkklzgpkm.html

[U22] Py：矩阵转置
来源：http://dali.316326.xyz/Article/details/gtassrhsfh.html

list(zip(*m))
来源：http://dali.daxiang520.top/Article/details/gtwekasjou.html

[U23] Py：分块读取大文件
来源：http://dali.cucudq.cn/Article/details/gtgzilinuy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnqzz.top/Article/details/gtgsweorfz.html

[U24] Py：路径操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygxoatbz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtqyhcrvzr.html

[U25] Py：CSV 按字典读
来源：http://dali.cheryme.top/Article/details/gtdqinbfsx.html

csv.DictReader(f)
来源：http://dali.jinqigufen.top/Article/details/gtfdttmzqo.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlbzatpz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gtbpfvmvwb.html

[U27] Py：异步 HTTP
来源：http://dali.meibo888.top/Article/details/gtrkyzlnej.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nanxuanxn.top/Article/details/gtlzerklte.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gtkzcbippi.html

UserId = int
来源：http://dali.daria6918.cn/Article/details/gtfbctsasu.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtblybbzwl.html

@property 与 @x.setter 配合
来源：http://dali.meibo888.top/Article/details/gthqfhuvbp.html

[U30] Py：数据类
来源：http://dali.gzhubu.top/Article/details/gtpngmkrwv.html

@dataclass(slots=True)
来源：http://dali.hammf.cn/Article/details/gtbhucvyzt.html

[U31] Py：单测
来源：http://dali.xziqi.cn/Article/details/gtbvnzpegg.html

python -m pytest -q
来源：http://dali.zhoulong.xyz/Article/details/gtbnambkcq.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gtxfeohkpi.html

ruff format . && ruff check --fix .
来源：http://dali.gzhubu.top/Article/details/gtbkaiaifn.html

[U33] Py：打包发布
来源：http://dali.zhiwuduotai.top/Article/details/gtcqpwijgk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jlsjyb.cn/Article/details/gtvcafdcku.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gtlmbrojsi.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gtrgmtqbxy.html

[U35] Py：发送邮件
来源：http://dali.bjfxy.top/Article/details/gthkhzzzzs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jyoumei.cn/Article/details/gtsahbvrwf.html

[U36] Py：定时任务
来源：http://dali.bjfxy.top/Article/details/gtzmmmncix.html

schedule.every(10).minutes.do(job)
来源：http://dali.andypj.xyz/Article/details/gtfgtdjcrm.html

[U37] Py：读写 Excel
来源：http://dali.pengpengdd.cyou/Article/details/gtjidyzkmx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ybcxt.top/Article/details/gtwocukffx.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtilipjxsv.html

Path(__file__).resolve().parent
来源：http://dali.316326.xyz/Article/details/gteqtvbblq.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhwfgbun.html

sys.stdout.isatty()
来源：http://dali.wangshuangyany.cn/Article/details/gtmpowihuo.html

[U40] Py：打印到标准错误
来源：http://dali.jiagoushi.top/Article/details/gttklmtupa.html

print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtsxjsbumd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gthbusjfya.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gtuoklcmwh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ivvv.top/Article/details/gtiqswvpjq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yvedp.cn/Article/details/gtkqwjqgyl.html

[U43] PHP：声明命名空间
来源：http://dali.gogol.net.cn/Article/details/gtqjeiohbq.html

namespace App\Http;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxcpqbzv.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gtznfaqceh.html

declare(strict_types=1);
来源：http://dali.fengsongda.top/Article/details/gtfwoptblz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tanke756.top/Article/details/gtbpxrtyfz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtezzoboxn.html

[U46] PHP：可空类型
来源：http://dali.sysykeji.top/Article/details/gtyjgctxpt.html

?string $name = null
来源：http://dali.guowangkeji.top/Article/details/gtukrtlrnm.html

[U47] PHP：联合类型
来源：http://dali.yvedp.cn/Article/details/gtmzrnlkxk.html

int|string $id
来源：http://dali.daxiang520.top/Article/details/gtxalpgmtf.html

[U48] PHP：纯枚举
来源：http://dali.9152youxi.cn/Article/details/gthxnchbtq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jianghu66.top/Article/details/gtxpcwhabe.html

[U49] PHP：只读属性
来源：http://dali.zhiwuduotai.top/Article/details/gtcxhobtuc.html

public readonly string $name
来源：http://dali.jyoumei.cn/Article/details/gttysqavcd.html

[U50] PHP：构造器属性提升
来源：http://dali.cheryme.top/Article/details/gttcbvjesj.html

public function __construct(private int $id) {}
来源：http://dali.andypj.xyz/Article/details/gttjnzxhmc.html

[U51] PHP：数组解构
来源：http://dali.havefunace.top/Article/details/gtqmwvuziz.html

[$a, $b] = $arr;
来源：http://dali.cheryme.top/Article/details/gtegaevudq.html

[U52] PHP：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gtnmzftpqu.html

$double = fn($x) => $x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtecojqvfd.html


<!-- 参考信息 -->