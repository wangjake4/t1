代发 wailian999

static int counter = 0;
来源：http://dali.guannengcc.top/Article/details/gt2sfrlkndh.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gt2usnafwxi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdabvije.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gt2bkfjsdrv.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gt2qjicuexs.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gt2trwbofdf.html

#endif
来源：http://dali.dianchejie.cn/Article/details/gt2hcriovin.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2pbpuvqrx.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghzdumvi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gt2wkpeglez.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2dscndpgv.html

std::string s = "hi";  s += "!";
来源：http://dali.shuidangran.top/Article/details/gt2kjgjifwk.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gt2jcsyapgo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gt2hlvvakua.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gt2nglylhoe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rggpezko.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gt2iqhvhaqu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2ylguacfe.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gt2cogrjlrj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2xlgnqvrn.html

[S37] C++：set
来源：http://dali.quarkkingdee.top/Article/details/gt2rdsgfuns.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gt2qhhlnazd.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gt2lffswuhu.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uaoxjizm.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gt2acsxjoic.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gt2dfcwnzpz.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gt2yarqxthw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gt2ftprvijf.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gt2dilodihq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gt2cozefcks.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyzjtjno.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gt2kusllnri.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gt2ttvykkik.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gt2pguusvsg.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gt2tmggxvsq.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gt2zytjmiof.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gt2kmmbdjwq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqoydohh.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gt2vxhfnapy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gt2skrvjpzi.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hytgjqvr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lwdljtch.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcbwocff.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gt2tmhzgaoa.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2rokkaqub.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2opphxfzm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gt2gnchjscw.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gt2pvjnlqex.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2twsmdqkr.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gt2lkmqzejb.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gt2gjhqutyx.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gt2tguxjsrp.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gt2rifljccx.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gt2eocasxqc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gt2wxbyganu.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gt2dslsgutt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2kvtszkgx.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gt2xihdxfqp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gt2bjrfaqsz.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aozsqukw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gt2ejcnonkg.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gt2ygutclau.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gt2nhfyauxl.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gt2mieuujka.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenzaomai.com/Article/details/gt2klziejwe.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gt2lcjretip.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gt2csgryzaa.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2hhxztpbc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2svteqtem.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2cfbjpimk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gt2xakxesud.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2rfdouitg.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2gyolpqpl.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2pjsdnude.html

[T02] Kotlin：变量
来源：http://dali.xylfe.cn/Article/details/gt2ioqcdxzs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gt2zevpkvof.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gt2yjwgieyc.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2rlaiwkpx.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gt2dkkyvncj.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pygyuxgr.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gt2xisjnyvh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gt2gcpbcnhe.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gt2dqkoyrxa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gt2gaecgznk.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gt2wjnhbyoz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gt2popglemo.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gt2cgbmuzvw.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gt2uengkzyn.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgfzy.top/Article/details/gt2wjaefuja.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gt2djhnbclg.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gt2zkpnuapz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gt2xxqngoxo.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gt2damdzubt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gt2kwpnfpnc.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gt2iihqajgj.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrxekldr.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gt2gvpxshjd.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtidshsf.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gt2nhcjcvay.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gt2wlsvivvt.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gt2zqzhxtos.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gt2evtckopo.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2iqqsxqhx.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2katoszit.html

[T17] Swift：变量与常量
来源：http://dali.jinqigufen.top/Article/details/gt2krhmdeyx.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gt2bhzzqbiq.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2hdyiprao.html

"值: \(b)"
来源：http://dali.hfpthk.cn/Article/details/gt2zcdzbauw.html

[T19] Swift：可选绑定
来源：http://dali.cqqwz.cn/Article/details/gt2myaabuwy.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gt2npbmmfon.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gt2fvqeiavs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gt2raagyell.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gt2dfgcckxt.html

for x in a { print(x) }
来源：http://dali.zycfv.cn/Article/details/gt2ketepxce.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gt2rxvyjafb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yangfankeji.com/Article/details/gt2csgngzmb.html

[T23] Swift：函数
来源：http://dali.zhongyouzk.top/Article/details/gt2avxuirvq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gt2ttgugvjx.html

[T24] Swift：闭包
来源：http://dali.chenjidiqi.icu/Article/details/gt2gaxmxgvo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cyvfspjq.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlfyydql.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gt2jhgaxnwt.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgikuddj.html

class A: Base { override func f() {} }
来源：http://dali.sweek.top/Article/details/gt2idcuguuv.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gt2uskssdio.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gt2iflmtndb.html

[T28] Swift：枚举
来源：http://dali.svipenyu.cn/Article/details/gt2xqoayxac.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gt2auylfsuh.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gt2ikgzsixl.html

guard let x = opt else { return }
来源：http://dali.jqgufenzy.top/Article/details/gt2dbcfxiqt.html

[T30] Swift：协议
来源：http://dali.yongpay.top/Article/details/gt2glcbldln.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gt2vgfrwwkq.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2eqtocsdf.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2ivqywhiv.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gt2wifwyhms.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gt2hjizxasp.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gt2qcdorjoz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gt2hgxxmwgk.html

[T34] Lua：遍历表
来源：http://dali.smart0.xyz/Article/details/gt2sqdpnvut.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tian-w.cn/Article/details/gt2lwgocprh.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gt2farifopj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gt2wkisifmg.html

[T36] Lua：函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfujlcro.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gt2dgtfzmcg.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gt2neiusgda.html

"a" .. "b"
来源：http://dali.haohaochexian.top/Article/details/gt2qivktnse.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gt2tjmknbqw.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gt2vthhupyc.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gt2szboqvsa.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2boseaslw.html

[T40] Lua：元表
来源：http://dali.zhengqikj.top/Article/details/gt2bwcoatpp.html

setmetatable({}, { __index = base })
来源：http://dali.chenzaomai.com/Article/details/gt2wqabcvau.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2ffcgimax.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2lgcdknpc.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gt2kumqkwol.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqkzgwnt.html

[T43] Perl：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2jgjhuzus.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdemvysi.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gt2xjoqbswj.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gt2nvxikkup.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gt2wicdgajw.html

for my $x (@arr) { print $x; }
来源：http://dali.yj202588.top/Article/details/gt2votnzjud.html

[T46] Perl：哈希操作
来源：http://dali.shuidangran.top/Article/details/gt2bsxhctde.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gt2xqhgpoug.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gt2ghirmonp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnqzz.top/Article/details/gt2zmagfiil.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gt2qyuaxipq.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gt2mvxwonue.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gt2czdoouav.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gt2qqwuaniy.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2upaezpje.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenzaomai.com/Article/details/gt2vcgbsglq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rldkhmku.html

[T51] Scala：Hello World
来源：http://dali.cashguo.top/Article/details/gt2xyrmenet.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gt2fdziuflp.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gt2qyafzdew.html

val a = 1;  var b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2ifcrzvrg.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2hpsmnywm.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2dchufory.html

[T54] Scala：集合映射
来源：http://dali.c1oappe.top/Article/details/gt2tyqxlvtx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gt2zmiyjyck.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gt2rpxvfrnt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gt2mxhhtxoo.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gt2aiobdzqw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lenoeotq.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gt2xscmfeuj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ehwqpu.com/Article/details/gt2lffoxlav.html

[T58] Scala：函数定义
来源：http://dali.wangdashe.top/Article/details/gt2iniqvfuf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gt2bqifgowg.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gt2gfamdpqy.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gt2xzxfitdi.html

[T60] Scala：折叠
来源：http://dali.jinqigufen.top/Article/details/gt2fnccdiqc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hammf.cn/Article/details/gt2lshyyuoh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2lbpvypel.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2arbgkpgd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2rphyswia.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gt2slbnyoxg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ehwqpu.com/Article/details/gt2kidluodu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gt2inbwbujd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2txisfarp.html

[U03] Py：加载 .env 配置
来源：http://dali.guowangkeji.top/Article/details/gt2zsbfetep.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gt2qmcxkvdi.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gt2onyxqkve.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gt2wxgzhbbd.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gt2vgnjcsyr.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gt2zfarzonm.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gt2owvtuhme.html

{**a, **b}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkvnwsco.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gt2omhrwxpz.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gt2rhguhhsn.html

[U08] Py：展平二维列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncdghjyp.html

[y for x in nested for y in x]
来源：http://dali.yonumen.top/Article/details/gt2gknnzmte.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gt2snsmutkt.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gt2djpxqmnc.html

[U10] Py：按值排序字典
来源：http://dali.quarkkingdee.top/Article/details/gt2ksrufbid.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gt2bpmzdmdt.html

[U11] Py：生成器表达式
来源：http://dali.nwbrower.top/Article/details/gt2cdrhrhdh.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gt2dtduexsp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.c1oappe.top/Article/details/gt2alfhfyvi.html

Counter(arr).most_common(3)
来源：http://dali.yonumen.top/Article/details/gt2rxvrvwxy.html

[U13] Py：固定长度队列
来源：http://dali.jqgufenzy.top/Article/details/gt2eqjchems.html

deque(maxlen=10)
来源：http://dali.chenlongwang.top/Article/details/gt2pyziyklu.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gt2azzaolwb.html

defaultdict(list)
来源：http://dali.vqdsnc.cn/Article/details/gt2wszhscvs.html

[U15] Py：高精度计时
来源：http://dali.feifeiyinyue.top/Article/details/gt2dylyccuk.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gt2qxiasdmr.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gt2ihjekjxx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sxryk.cn/Article/details/gt2blyuwcve.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gt2wpcagbeo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yvedp.cn/Article/details/gt2qjkqfxav.html

[U18] Py：预编译正则
来源：http://dali.shuidangran.top/Article/details/gt2pasizydi.html

pat = re.compile(r"\d+")
来源：http://dali.yueranfly.top/Article/details/gt2xvkjhvuj.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gt2ldewxnbz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.svipenyu.cn/Article/details/gt2rrbbejon.html

[U20] Py：缓存函数结果
来源：http://dali.wangdashe.top/Article/details/gt2jubjvbud.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gt2pwywxqcg.html

[U21] Py：自定义上下文管理器
来源：http://dali.tian-w.cn/Article/details/gt2vjsuzxym.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gt2vbvonjuc.html

[U22] Py：矩阵转置
来源：http://dali.xylfe.cn/Article/details/gt2zcbjwrtg.html

list(zip(*m))
来源：http://dali.nwbrower.top/Article/details/gt2dkrulqqn.html

[U23] Py：分块读取大文件
来源：http://dali.aizwys.cn/Article/details/gt2geosfxaz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxuanxn.top/Article/details/gt2djpsdfqt.html

[U24] Py：路径操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwqqlhin.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2vzjrcsal.html

[U25] Py：CSV 按字典读
来源：http://dali.cdnleiting.top/Article/details/gt2zodjwdxf.html

csv.DictReader(f)
来源：http://dali.ehwqpu.com/Article/details/gt2zsduxxbo.html

[U26] Py：并发下载
来源：http://dali.nanxuanxn.top/Article/details/gt2cakgbiiq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.0kj1m.cn/Article/details/gt2ziculcwy.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gt2ysynylsy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gogol.net.cn/Article/details/gt2mwalkhzk.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gt2vfrevxyy.html

UserId = int
来源：http://dali.snrcjt.cn/Article/details/gt2tdavwgst.html

[U29] Py：属性校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwivgsig.html

@property 与 @x.setter 配合
来源：http://dali.aizwys.cn/Article/details/gt2etebvqqy.html

[U30] Py：数据类
来源：http://dali.birdmap.top/Article/details/gt2qhrogssh.html

@dataclass(slots=True)
来源：http://dali.aizwys.cn/Article/details/gt2uberwigh.html

[U31] Py：单测
来源：http://dali.gzhubu.top/Article/details/gt2xpbbtejp.html

python -m pytest -q
来源：http://dali.aibaodan.cn/Article/details/gt2lyjxiuex.html

[U32] Py：代码格式化
来源：http://dali.9152youxi.cn/Article/details/gt2bhjkuglf.html

ruff format . && ruff check --fix .
来源：http://dali.zhengqikj.top/Article/details/gt2ffhunmxs.html

[U33] Py：打包发布
来源：http://dali.xinyue.icu/Article/details/gt2uisdkozc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenzaomai.com/Article/details/gt2ulqnroon.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gt2krpdhcos.html

chardet.detect(raw)
来源：http://dali.tanke756.top/Article/details/gt2odsnpcpc.html

[U35] Py：发送邮件
来源：http://dali.chenlongwang.top/Article/details/gt2lsoofvps.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xinyue.icu/Article/details/gt2fijfzuhg.html

[U36] Py：定时任务
来源：http://dali.guannengcc.top/Article/details/gt2zwugxety.html

schedule.every(10).minutes.do(job)
来源：http://dali.snrcjt.cn/Article/details/gt2ezzoamyd.html

[U37] Py：读写 Excel
来源：http://dali.shuidangran.top/Article/details/gt2kfdmbvuz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gt2bjixbmrj.html

[U38] Py：获取脚本所在目录
来源：http://dali.bjfxy.top/Article/details/gt2lwuxsanj.html

Path(__file__).resolve().parent
来源：http://dali.yuxming.cn/Article/details/gt2bargybyo.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj202588.top/Article/details/gt2zanbxjjy.html

sys.stdout.isatty()
来源：http://dali.aizwys.cn/Article/details/gt2nfghungz.html

[U40] Py：打印到标准错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmbupdty.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejxrryst.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.c1oappe.top/Article/details/gt2eqdndvba.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guowangkeji.top/Article/details/gt2yejwbdcy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.feifeiyinyue.top/Article/details/gt2bymbiwzw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhoulong.xyz/Article/details/gt2pjygpxjl.html

[U43] PHP：声明命名空间
来源：http://dali.nanxuanxn.top/Article/details/gt2orpmzxte.html

namespace App\Http;
来源：http://dali.tianlin.xyz/Article/details/gt2ofyqovit.html

[U44] PHP：开启严格类型
来源：http://dali.c1oappe.top/Article/details/gt2qeykhyms.html

declare(strict_types=1);
来源：http://dali.yvedp.cn/Article/details/gt2xfrduplq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jiagoushi.top/Article/details/gt2qkyyrgrz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2nqszpcfo.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gt2lqrlmxbi.html

?string $name = null
来源：http://dali.xuetiantiany.cn/Article/details/gt2izjmvoqy.html

[U47] PHP：联合类型
来源：http://dali.sysykeji.top/Article/details/gt2spkjjbmf.html

int|string $id
来源：http://dali.jiagoushi.top/Article/details/gt2vjsozdqc.html

[U48] PHP：纯枚举
来源：http://dali.redwolf501.top/Article/details/gt2xgaqnqox.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gt2gzinoyzo.html

[U49] PHP：只读属性
来源：http://dali.gaohongyu789.top/Article/details/gt2zmbcaist.html

public readonly string $name
来源：http://dali.fzhhl.top/Article/details/gt2gnvxjqok.html

[U50] PHP：构造器属性提升
来源：http://dali.sysykeji.top/Article/details/gt2axbqqgak.html

public function __construct(private int $id) {}
来源：http://dali.9152youxi.cn/Article/details/gt2pqgkpmas.html

[U51] PHP：数组解构
来源：http://dali.pycfn.com/Article/details/gt2rclshode.html

[$a, $b] = $arr;
来源：http://dali.daxiang520.top/Article/details/gt2rrypcxas.html

[U52] PHP：箭头函数
来源：http://dali.cashguo.top/Article/details/gt2okbptwtn.html

$double = fn($x) => $x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkmbbmoc.html


<!-- 参考信息 -->