代发 wailian999

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gt2swpaephm.html

#define X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zijusolv.html

#endif
来源：http://dali.aizwys.cn/Article/details/gt2vbqpmnay.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2flcoifyb.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gt2vrpjzgbg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gt2bekxmgol.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gt2hthvobjd.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gt2mgspxlsz.html

[S33] C++：vector 增删
来源：http://dali.kuanghao11.cn/Article/details/gt2bpscyjrc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2uuobeyde.html

[S34] C++：遍历 vector
来源：http://dali.ivvv.top/Article/details/gt2efppjycy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2agfbmwuo.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gt2fziddbeq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2ofplhysq.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcxtceye.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2yffucfpg.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gt2hdehqbhx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhzzowdt.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gt2biaklocn.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gt2dqteeyzg.html

[S39] C++：自定义比较器排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqolxaco.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gt2myutpvgd.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gt2zijzctws.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gt2sfeuinfa.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2ywcquzhj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gt2nmicckhu.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gt2yelysbur.html

class B : public Base { public: void f() override {} };
来源：http://dali.tian-w.cn/Article/details/gt2mkmwwxjq.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gt2adempzqn.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gt2kjfplkmq.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mswmdisb.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gt2wmdauzqe.html

[S45] C++：lambda
来源：http://dali.fzhhl.top/Article/details/gt2fyhiprgt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gt2kixfdayz.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gt2uhlgwutg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gt2kcnfuncn.html

[S47] C++：结构化绑定遍历
来源：http://dali.tian-w.cn/Article/details/gt2tfnnzrce.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gt2dfijofip.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2flcwgbjv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ziwtoblo.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gt2mgfkmrxh.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gt2yhrdobzr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gt2cvmmqusq.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gt2xjdbynnq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2bqsnkfoj.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2dydlrehb.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gt2zhlrxhqf.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gt2ebochmmd.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gt2qrjyojbi.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gt2kjjetyys.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gt2rulzpabs.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gt2pntgxaxy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gt2jcbrjidu.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gt2inrqzqvh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gt2oegdeetg.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gt2rjkycyub.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gt2vmldgsle.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gt2ykweuhie.html

constexpr int N = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wenqsspp.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gt2kxlrjxws.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gt2inkuyfvw.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gt2hbncjurg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gt2jeibyoqm.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gt2nxzfoszj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gt2gflottrm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2cnktrltd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gt2yghcyvdv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2kjrqucdz.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2nktmrkqc.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2zqqmczmj.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gt2gevyuxao.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gt2bwpyvlab.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2zzjdgieh.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gt2abpvacll.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gt2ktyiwhgx.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gt2dnunibyu.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gt2wleubocu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gt2bxlnpwhd.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gt2jdbvdogz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zycfv.cn/Article/details/gt2hmybmogc.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gt2tcxkgzae.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gt2xihmkrex.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gt2mkiwsxxj.html

data class User(val name: String, val age: Int)
来源：http://dali.hammf.cn/Article/details/gt2ztztlqxd.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gt2xzmzhcat.html

fun String.exclaim() = this + "!"
来源：http://dali.quarkkingdee.top/Article/details/gt2vuqyavub.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gt2gkdvhwig.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gt2yczdhofi.html

[T11] Kotlin：协程
来源：http://dali.sweek.top/Article/details/gt2qsxxhlkc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gt2rscbynah.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gt2tlpxhtcu.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2slucdqjn.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gt2kaoucmgi.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gt2wemhykyy.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gt2xronbrcd.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gt2dsycnkao.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gt2mszammym.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gt2lvdrxero.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2qxcejyua.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2pvnqnhtl.html

[T17] Swift：变量与常量
来源：http://dali.0kj1m.cn/Article/details/gt2adrpiihn.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gt2mtgjrkcr.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gt2dfwxspys.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gt2rrohnjij.html

[T19] Swift：可选绑定
来源：http://dali.ybcxt.top/Article/details/gt2iumvgqgs.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uomnpxig.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gt2tpmmqcng.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gt2yrpngeet.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gt2tepltfdd.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngpxmzfw.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gt2tpkduwwh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gt2hfqfujfn.html

[T23] Swift：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpjizddv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2pnpwepfx.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gt2jnfuzldf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gt2jtwcbwou.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gt2fzytybtw.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gt2lvxoybmr.html

[T26] Swift：类与重写
来源：http://dali.hywenlv.cn/Article/details/gt2sexymsnn.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gt2uvjdusob.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gt2wfmmppca.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gt2zmcruelm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pahgmdcy.html

enum Color { case red, green }
来源：http://dali.jinqigfzy.top/Article/details/gt2ktvypsnh.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2fhibqnet.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gt2qkaaynmw.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gt2pcwcjohq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzapypui.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2mbkvbztp.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2slriqlmc.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gt2ujyexrla.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gt2bimgbckc.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gt2nonyohsa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gt2aefupjko.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gt2cmwfrfxj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shuidangran.top/Article/details/gt2rzdvfsnz.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gt2vedehpys.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2ivsqdkxy.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gt2nfcoyzjq.html

function add(a, b) return a + b end
来源：http://dali.cdnleiting.top/Article/details/gt2erzzhysf.html

[T37] Lua：字符串拼接
来源：http://dali.ivvv.top/Article/details/gt2wajlmsyo.html

"a" .. "b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2guxufhdn.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2eanwyvrf.html

if x > 0 then print("正") end
来源：http://dali.gaohongyu789.top/Article/details/gt2jqyabsil.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwmrheal.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gt2oylhglgr.html

[T40] Lua：元表
来源：http://dali.guowangkeji.top/Article/details/gt2wtdweyki.html

setmetatable({}, { __index = base })
来源：http://dali.wangdashe.top/Article/details/gt2myiuwbrr.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gt2arbqcmsk.html

print "Hello\n";
来源：http://dali.zdqjudy.top/Article/details/gt2ftijtats.html

[T42] Perl：变量类型
来源：http://dali.zhengqikj.top/Article/details/gt2yjyffwyf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zycfv.cn/Article/details/gt2ksldgrdx.html

[T43] Perl：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2iqsibuuw.html

"值: $a"
来源：http://dali.iojbl.cn/Article/details/gt2wzkpfyin.html

[T44] Perl：条件
来源：http://dali.gotoacloud.top/Article/details/gt2nnoouzba.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gt2iomqsovp.html

[T45] Perl：数组遍历
来源：http://dali.jyoumei.cn/Article/details/gt2kkkcoylj.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gt2yxmahank.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gt2ncqtqehc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gt2trubpkoo.html

[T47] Perl：正则捕获
来源：http://dali.zycfv.cn/Article/details/gt2drrmecsg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gptpmzta.html

[T48] Perl：正则替换
来源：http://dali.yueranfly.top/Article/details/gt2vrimkxzh.html

$s =~ s/old/new/g;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqtkmyeb.html

[T49] Perl：函数
来源：http://dali.birdmap.top/Article/details/gt2forbyovg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2fdgyhdrj.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2eazcboiv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sufxvd.cn/Article/details/gt2fbbeckdu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gt2uqjhssut.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2egiubxzn.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsmsheyl.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gt2guakfazu.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwemvopc.html

[T53] Scala：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2kxswulph.html

s"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmabuftp.html

[T54] Scala：集合映射
来源：http://dali.sysykeji.top/Article/details/gt2vwxqtiov.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sufxvd.cn/Article/details/gt2qtgfzvxs.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gt2pcpgysuk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2sjgkkjzv.html

[T56] Scala：样例类
来源：http://dali.redwolf501.top/Article/details/gt2gyejjzzn.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gt2vklvoamp.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2hwpmclqv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gt2lpigdqfb.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gt2xgnfopkp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gt2bmsopcug.html

[T59] Scala：循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2hztpczem.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2argxqcaw.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gt2muiyxwiu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenzaomai.com/Article/details/gt2ngjmqqup.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2sgwccplb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mylijtpu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2unrvcrcg.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gt2bbrfojcg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjducdxm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hammf.cn/Article/details/gt2djqrarhg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.svipenyu.cn/Article/details/gt2uxjmdtub.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gt2vgeujtqb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gt2aqolmyfu.html

[U04] Py：变量调试打印
来源：http://dali.zhoulong.xyz/Article/details/gt2rahossco.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gt2jmuypnjk.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gt2zkegzuda.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2didfhrgb.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdlyusho.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gt2slqoqorl.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gt2njpoixiq.html

{v: k for k, v in d.items()}
来源：http://dali.yanxiufei.cn/Article/details/gt2zcvswguy.html

[U08] Py：展平二维列表
来源：http://dali.havefunace.top/Article/details/gt2glaisrsz.html

[y for x in nested for y in x]
来源：http://dali.xziqi.cn/Article/details/gt2vfbmswwi.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gt2fgarfuse.html

max(d, key=d.get)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yiyrqlpp.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gt2gakgsvde.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnxiangtu.top/Article/details/gt2kowqfxft.html

[U11] Py：生成器表达式
来源：http://dali.jiagoushi.top/Article/details/gt2tuwrtwoc.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gt2uwzjjupn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdqgcwut.html

Counter(arr).most_common(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2bdodpdit.html

[U13] Py：固定长度队列
来源：http://dali.aibaodan.cn/Article/details/gt2vnzhacll.html

deque(maxlen=10)
来源：http://dali.yanxiufei.cn/Article/details/gt2nskchiql.html

[U14] Py：分组收集到列表
来源：http://dali.iojbl.cn/Article/details/gt2hmwjxayt.html

defaultdict(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2ntejijux.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gt2mwclxrvo.html

t = time.perf_counter()
来源：http://dali.zycfv.cn/Article/details/gt2gdhuyjra.html

[U16] Py：命令行参数解析
来源：http://dali.jqgfzy.top/Article/details/gt2kntyomup.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzwdyoai.html

[U17] Py：初始化日志
来源：http://dali.yj20258.top/Article/details/gt2fuzplpgz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gt2piepkxfq.html

[U18] Py：预编译正则
来源：http://dali.zhengqikj.top/Article/details/gt2ylbbuyrm.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gt2zuppluht.html

[U19] Py：正则替换带回调
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrfhelkc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gt2cfarrgpb.html

[U20] Py：缓存函数结果
来源：http://dali.jiagoushi.top/Article/details/gt2fhgaaeau.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gt2xjahbwqy.html

[U21] Py：自定义上下文管理器
来源：http://dali.andypj.xyz/Article/details/gt2jaxlxdbb.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gt2wzmpgeam.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gt2ifdiifuc.html

list(zip(*m))
来源：http://dali.daxiang520.top/Article/details/gt2domevhnx.html

[U23] Py：分块读取大文件
来源：http://dali.ehwqpu.com/Article/details/gt2mfuvyoec.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.meibo888.top/Article/details/gt2ousktqef.html

[U24] Py：路径操作
来源：http://dali.ybcxt.top/Article/details/gt2inlxutyu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gt2tlwpnplf.html

[U25] Py：CSV 按字典读
来源：http://dali.c1oappe.top/Article/details/gt2nykodpcn.html

csv.DictReader(f)
来源：http://dali.gotoacloud.top/Article/details/gt2kdcqywjc.html

[U26] Py：并发下载
来源：http://dali.ivvv.top/Article/details/gt2xrracovh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cucudq.cn/Article/details/gt2uljcrmha.html

[U27] Py：异步 HTTP
来源：http://dali.dianchejie.cn/Article/details/gt2vinosurz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.birdmap.top/Article/details/gt2miilthgw.html

[U28] Py：类型别名
来源：http://dali.quarkkingdee.top/Article/details/gt2jtvacoau.html

UserId = int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qtjinnye.html

[U29] Py：属性校验
来源：http://dali.shuidangran.top/Article/details/gt2nemugnlq.html

@property 与 @x.setter 配合
来源：http://dali.zycfv.cn/Article/details/gt2zacvxgpx.html

[U30] Py：数据类
来源：http://dali.daria6918.cn/Article/details/gt2wzkxexkd.html

@dataclass(slots=True)
来源：http://dali.zhixingplan.top/Article/details/gt2btnzjztf.html

[U31] Py：单测
来源：http://dali.sxryk.cn/Article/details/gt2ymrhibvr.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gt2cuowbsyt.html

[U32] Py：代码格式化
来源：http://dali.jianghu66.top/Article/details/gt2mkfxrfak.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gt2racecdbx.html

[U33] Py：打包发布
来源：http://dali.hnqzz.top/Article/details/gt2ybuayjgb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gt2egunresy.html

[U34] Py：判断编码
来源：http://dali.fzhhl.top/Article/details/gt2dkjlspxm.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gt2vxqvvvtr.html

[U35] Py：发送邮件
来源：http://dali.hywenlv.cn/Article/details/gt2qqufchmb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2quozrqoj.html

[U36] Py：定时任务
来源：http://dali.jqgufenzy.top/Article/details/gt2etvovuhe.html

schedule.every(10).minutes.do(job)
来源：http://dali.zycfv.cn/Article/details/gt2ayfuaydo.html

[U37] Py：读写 Excel
来源：http://dali.zhengqikj.top/Article/details/gt2cwriakpb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvxxgynu.html

[U38] Py：获取脚本所在目录
来源：http://dali.svipenyu.cn/Article/details/gt2xpmoemfv.html

Path(__file__).resolve().parent
来源：http://dali.cdnleiting.top/Article/details/gt2kydudpyc.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnqzz.top/Article/details/gt2rgqntmdp.html

sys.stdout.isatty()
来源：http://dali.fengsongda.top/Article/details/gt2hqrxmyfx.html

[U40] Py：打印到标准错误
来源：http://dali.shzxlz.cn/Article/details/gt2gpjqypjv.html

print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2kdjuxvte.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmrsdpj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gt2owugsmch.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jiagoushi.top/Article/details/gt2fmogeben.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cqqwz.cn/Article/details/gt2szvppgqp.html

[U43] PHP：声明命名空间
来源：http://dali.sxryk.cn/Article/details/gt2imnjwspz.html

namespace App\Http;
来源：http://dali.cashguo.top/Article/details/gt2ftinqobf.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gt2oldcryja.html

declare(strict_types=1);
来源：http://dali.meibo888.top/Article/details/gt2gblsyinn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gt2djjgpsyn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2oayklpyc.html

[U46] PHP：可空类型
来源：http://dali.iojbl.cn/Article/details/gt2yeoomapz.html

?string $name = null
来源：http://dali.tianlin.xyz/Article/details/gt2ecgrwlqu.html

[U47] PHP：联合类型
来源：http://dali.sweek.top/Article/details/gt2mpmmyakj.html

int|string $id
来源：http://dali.sweek.top/Article/details/gt2fjfzlnte.html

[U48] PHP：纯枚举
来源：http://dali.dashuyun.cn/Article/details/gt2ghpatiot.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258888.top/Article/details/gt2ekcypwis.html

[U49] PHP：只读属性
来源：http://dali.zhoulong.xyz/Article/details/gt2dxwgnvqf.html

public readonly string $name
来源：http://dali.yongpay.top/Article/details/gt2lmcbfwim.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gt2wfrnjzvs.html

public function __construct(private int $id) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2zsyjrtmw.html

[U51] PHP：数组解构
来源：http://dali.jqgufenzy.top/Article/details/gt2haoaesro.html

[$a, $b] = $arr;
来源：http://dali.sysykeji.top/Article/details/gt2fdmnbpkm.html

[U52] PHP：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gt2dbcutwbv.html

$double = fn($x) => $x * 2;
来源：http://dali.fengsongda.top/Article/details/gt2oqcocqeg.html

[U53] PHP：空合并运算符
来源：http://dali.shuidangran.top/Article/details/gt2qhmghueq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gt2bjgroyjd.html

[U54] PHP：空安全调用
来源：http://dali.jqgufenzy.top/Article/details/gt2cqylkbyo.html

$obj?->method()
来源：http://dali.sxryk.cn/Article/details/gt2easrowfo.html


<!-- 参考信息 -->