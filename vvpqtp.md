代发 wailian999

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gt2qchayowy.html

#define X_H
来源：http://dali.zhiwuduotai.top/Article/details/gt2anwidhca.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gt2jcybnecf.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2yavwtytm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2belxjzmr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gt2npvirmcs.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gt2ndfsxmft.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gt2uztnvknq.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gt2kcytzbzy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2assxgmeq.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gt2zcwfkszu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gt2vaddollb.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gt2knujkgon.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2qapcjmez.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2edtwbmgm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2beismcck.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gt2tljynqox.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gt2pdyqiark.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gt2djhvikrv.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsskpojr.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gt2xtdxhzyn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gt2wfewhckm.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gt2lguskwgx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gt2bcachurw.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gt2cwukkrbp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqxphiko.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxjaqsss.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gt2jwmpzqla.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gt2pyqqtbmi.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gt2fkzezshl.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gt2aidckckg.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gt2gztjcdbx.html

[S45] C++：lambda
来源：http://dali.havefunace.top/Article/details/gt2tbcgxqxy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gt2hmmtjluc.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gt2teddakzy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gt2uncfkvcs.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gt2auyealal.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gt2apwugvib.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2aziopdej.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gt2ekdgqfzv.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gt2ulecgiwl.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjwtczuz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gt2mzqxxife.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gt2vshjyyzi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbmomlvn.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gt2bwoaliha.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gt2efcwowgu.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gt2ghanbxzv.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gt2asibwbgy.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gt2zrpkojhw.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gt2drcizsno.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gt2mojpftob.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gt2uclklvmc.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gt2wrykwbzl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.9152youxi.cn/Article/details/gt2eblrnhjl.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gt2jtsgnbqs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gt2jnszhota.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gt2ecxexqgf.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2mkhirozg.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gt2dknasidy.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gt2eayppsve.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gt2ngdfaalh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gt2wfmvnezo.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gt2jydbtvpl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gt2zljiktss.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ndxjmvxv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gt2cbadzpeb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2sblxitzf.html

[T01] Kotlin：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2dsjuopoy.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2aeteoymt.html

[T02] Kotlin：变量
来源：http://dali.guannengcc.top/Article/details/gt2qztndnvm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.haohaochexian.top/Article/details/gt2ihuwdzpk.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gt2flspacmu.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gt2icqeqcup.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gt2lsvcytci.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gt2ypsbgwzg.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gt2gnwqcjky.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gt2hrhwsnwi.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2lhoyfezv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2neuscqsn.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2rhbrdscn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gt2myrtcwoi.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gt2mvjqdddt.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szrbtttr.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gt2kjtajlhy.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gt2qdtaynih.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2wubxavvp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsxzhbbn.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gt2thuuwyrr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gt2jjuswuhm.html

[T12] Kotlin：解构声明
来源：http://dali.cashguo.top/Article/details/gt2twpdeyha.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2zlcwlkrk.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrsyugar.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2raobhxoo.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gt2stxwzskd.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gt2wxkdvcfz.html

[T15] Kotlin：接口
来源：http://dali.shuidangran.top/Article/details/gt2eswhsihg.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gt2puccppcf.html

[T16] Swift：Hello World
来源：http://dali.cheryme.top/Article/details/gt2pnytbhpi.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gt2cpejasgc.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gt2ggutukdx.html

var a = 1;  let b = 2
来源：http://dali.chenzaomai.com/Article/details/gt2allkfhty.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwmncloi.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gt2inmljrnn.html

[T19] Swift：可选绑定
来源：http://dali.zycfv.cn/Article/details/gt2qzsqmooc.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gt2pgzmkhab.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gt2fdachyof.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gt2jpnaotco.html

[T21] Swift：遍历
来源：http://dali.sysykeji.top/Article/details/gt2phjokvir.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gt2mvgbdkfd.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gt2hbjcdkiw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ydzc1.top/Article/details/gt2waxgkwwv.html

[T23] Swift：函数
来源：http://dali.smart0.xyz/Article/details/gt2iubbywhx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2awigxbjh.html

[T24] Swift：闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xpwhpzfy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2cflkkerd.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gt2ptyhgusg.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gt2gosxbwvj.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gt2bmheusib.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gt2nyrtyyrr.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gt2lcmfpwwp.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gt2hihfviod.html

[T28] Swift：枚举
来源：http://dali.zycfv.cn/Article/details/gt2uwpphteo.html

enum Color { case red, green }
来源：http://dali.hnxiangtu.top/Article/details/gt2byjqxgqh.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gt2mowqsbtp.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gt2opnoeahg.html

[T30] Swift：协议
来源：http://dali.sxryk.cn/Article/details/gt2tcvwbapi.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gt2xxididdw.html

[T31] Lua：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2ziduehfv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2prahrcih.html

[T32] Lua：局部变量
来源：http://dali.zycfv.cn/Article/details/gt2ujlyaqil.html

local a = 1
来源：http://dali.zhixingplan.top/Article/details/gt2ojgfdvcr.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gt2zeduwztf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gt2snmingex.html

[T34] Lua：遍历表
来源：http://dali.c1oappe.top/Article/details/gt2ntkvuhoz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gt2uasyabgb.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gt2xknmacrs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yonumen.top/Article/details/gt2cqycxuiv.html

[T36] Lua：函数
来源：http://dali.yangfankeji.com/Article/details/gt2cskwvwuz.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gt2zxjvxjfx.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gt2dbqggwuh.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gt2byhqqije.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gt2djmtxtdz.html

if x > 0 then print("正") end
来源：http://dali.fzhhl.top/Article/details/gt2abzpnuyf.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gt2vsxpzaie.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imrmgsgq.html

[T40] Lua：元表
来源：http://dali.ybcxt.top/Article/details/gt2ttmkfjdk.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gt2bdrdzgdn.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2scmiswax.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvxiskii.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gt2aobrggvl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangdashe.top/Article/details/gt2vfgiuwch.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2zdfbdqxa.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gt2iilhktbf.html

[T44] Perl：条件
来源：http://dali.zdqjudy.top/Article/details/gt2sspgmjmw.html

if ($a > 0) { print "正"; }
来源：http://dali.andypj.xyz/Article/details/gt2ijxsurbh.html

[T45] Perl：数组遍历
来源：http://dali.andypj.xyz/Article/details/gt2ljerzbgw.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vhkorron.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gt2lnzwvhkj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gt2sarmkjzi.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gt2naogjubm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2utdygsbi.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gt2gtzraoxo.html

$s =~ s/old/new/g;
来源：http://dali.bjfxy.top/Article/details/gt2zlqhukpd.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gt2cpkxrgqu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gt2bvrdkwxm.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2hjrxqxoh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gt2iqrocvyx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gt2iuyvldze.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2cdbfoorv.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2ktotzbey.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gt2ahpahmhz.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gt2bjmcbwkf.html

[T53] Scala：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2gqbhqcbj.html

s"值: $b"
来源：http://dali.xziqi.cn/Article/details/gt2lyyybmtp.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2acckwbol.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2jvbjvqjx.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekqrjgla.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gt2wxoeczod.html

[T56] Scala：样例类
来源：http://dali.xinyue.icu/Article/details/gt2gzojhpyo.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cplvcqyz.html

[T57] Scala：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2pytfdnhu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dianchejie.cn/Article/details/gt2ntieouvp.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gt2dxogaach.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gt2tcnohvkn.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gt2oiwtxacl.html

for (i <- 1 to 10) println(i)
来源：http://dali.andypj.xyz/Article/details/gt2zgynobda.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gt2opixtcot.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gt2aejparko.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2fdniigzd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gt2kptbcyot.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2wdlyfjfa.html

[U01] Py：创建虚拟环境
来源：http://dali.shuidangran.top/Article/details/gt2bonrdcrj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cucudq.cn/Article/details/gt2sygtcami.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sxryk.cn/Article/details/gt2enejkyjq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.meibo888.top/Article/details/gt2njseusry.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gt2pjkdixgs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gt2gedywfll.html

[U04] Py：变量调试打印
来源：http://dali.hywenlv.cn/Article/details/gt2ydybqrgb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jianghu66.top/Article/details/gt2vkzaukgn.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gt2duekmutq.html

list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2kwppgakt.html

[U06] Py：合并两个字典
来源：http://dali.sxryk.cn/Article/details/gt2pyrclrvt.html

{**a, **b}
来源：http://dali.jyoumei.cn/Article/details/gt2dsvuftkv.html

[U07] Py：反转字典键值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvjeuibg.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gt2znlpocoj.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gt2xqklzpsf.html

[y for x in nested for y in x]
来源：http://dali.316326.xyz/Article/details/gt2qlizbbub.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gt2izcvbttm.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gt2buvwglsc.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gt2hxvjmnpf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258888.top/Article/details/gt2bhvpkydo.html

[U11] Py：生成器表达式
来源：http://dali.yueranfly.top/Article/details/gt2dcolavmw.html

(x * 2 for x in arr)
来源：http://dali.sysykeji.top/Article/details/gt2cwbumdbz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gotoacloud.top/Article/details/gt2epdpjnwu.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gt2veschjag.html

[U13] Py：固定长度队列
来源：http://dali.jyoumei.cn/Article/details/gt2djadvvng.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gt2mputxkkb.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gt2vdaxspxt.html

defaultdict(list)
来源：http://dali.jqgufenzy.top/Article/details/gt2lhvpydzu.html

[U15] Py：高精度计时
来源：http://dali.guannengcc.top/Article/details/gt2bdlklrgn.html

t = time.perf_counter()
来源：http://dali.tian-w.cn/Article/details/gt2ckebjomo.html

[U16] Py：命令行参数解析
来源：http://dali.cdnleiting.top/Article/details/gt2nabyhzai.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenzaomai.com/Article/details/gt2nqztkedb.html

[U17] Py：初始化日志
来源：http://dali.fengsongda.top/Article/details/gt2ptnxlzvo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hfpthk.cn/Article/details/gt2fgdbhtka.html

[U18] Py：预编译正则
来源：http://dali.tanke756.top/Article/details/gt2ryirsbse.html

pat = re.compile(r"\d+")
来源：http://dali.gzhubu.top/Article/details/gt2upwmhdsn.html

[U19] Py：正则替换带回调
来源：http://dali.zhongyouzk.top/Article/details/gt2mlmftynp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xuxrvach.html

[U20] Py：缓存函数结果
来源：http://dali.daxiang520.top/Article/details/gt2kyjviuih.html

@functools.lru_cache(maxsize=None)
来源：http://dali.smart0.xyz/Article/details/gt2svkctgsz.html

[U21] Py：自定义上下文管理器
来源：http://dali.feifeiyinyue.top/Article/details/gt2jizonedb.html

@contextlib.contextmanager
来源：http://dali.hongshengwenyu.top/Article/details/gt2alisgtoo.html

[U22] Py：矩阵转置
来源：http://dali.cashguo.top/Article/details/gt2atbawzmj.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gt2hjbmktpl.html

[U23] Py：分块读取大文件
来源：http://dali.hywenlv.cn/Article/details/gt2jnbwwskj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tianlin.xyz/Article/details/gt2xohdozkm.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gt2yrfnjhtx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2swvrxhwt.html

[U25] Py：CSV 按字典读
来源：http://dali.316326.xyz/Article/details/gt2obxqvaqq.html

csv.DictReader(f)
来源：http://dali.tanke756.top/Article/details/gt2krpkiepb.html

[U26] Py：并发下载
来源：http://dali.cdnleiting.top/Article/details/gt2pcvlgnxo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cashguo.top/Article/details/gt2qhfcjkpc.html

[U27] Py：异步 HTTP
来源：http://dali.xziqi.cn/Article/details/gt2qnxlyjkd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sysykeji.top/Article/details/gt2eftmrhye.html

[U28] Py：类型别名
来源：http://dali.xinyue.icu/Article/details/gt2ojyoxqdb.html

UserId = int
来源：http://dali.snrcjt.cn/Article/details/gt2hkvzrgxb.html

[U29] Py：属性校验
来源：http://dali.zdqjudy.top/Article/details/gt2ozqunsql.html

@property 与 @x.setter 配合
来源：http://dali.gogol.net.cn/Article/details/gt2mluvqyaq.html

[U30] Py：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbubibbn.html

@dataclass(slots=True)
来源：http://dali.cashguo.top/Article/details/gt2zzqxbhsy.html

[U31] Py：单测
来源：http://dali.shuidangran.top/Article/details/gt2ndndyqid.html

python -m pytest -q
来源：http://dali.zhengqikj.top/Article/details/gt2vnsejloh.html

[U32] Py：代码格式化
来源：http://dali.hammf.cn/Article/details/gt2pfswcauc.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuodtnvp.html

[U33] Py：打包发布
来源：http://dali.havefunace.top/Article/details/gt2qgmunxdv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenzaomai.com/Article/details/gt2ejzkzgwt.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mayugvnw.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gt2wlkqeoge.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydvdkgoh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yinpvscj.html

[U36] Py：定时任务
来源：http://dali.iojbl.cn/Article/details/gt2eeyisvxf.html

schedule.every(10).minutes.do(job)
来源：http://dali.gogol.net.cn/Article/details/gt2xuexzhfw.html

[U37] Py：读写 Excel
来源：http://dali.xinyue.icu/Article/details/gt2tkcwwuxr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cucudq.cn/Article/details/gt2ifrxngce.html

[U38] Py：获取脚本所在目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrohhlhf.html

Path(__file__).resolve().parent
来源：http://dali.smart0.xyz/Article/details/gt2vrzzyxmx.html

[U39] Py：判断是否在交互环境
来源：http://dali.ehwqpu.com/Article/details/gt2nbrgcpnl.html

sys.stdout.isatty()
来源：http://dali.daxiang520.top/Article/details/gt2dupzsmob.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gt2pmyfvezb.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2caehxkgq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ppjwa.cn/Article/details/gt2fhirtzoo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pycfn.com/Article/details/gt2yzaatbkg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ehwqpu.com/Article/details/gt2efvjwdhj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cqqwz.cn/Article/details/gt2gyoaancf.html

[U43] PHP：声明命名空间
来源：http://dali.snrcjt.cn/Article/details/gt2wgrdvrna.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gt2cshhkbxb.html

[U44] PHP：开启严格类型
来源：http://dali.hnqzz.top/Article/details/gt2hejqqlqd.html

declare(strict_types=1);
来源：http://dali.hysaishi.cn/Article/details/gt2upxqtxnx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.9152youxi.cn/Article/details/gt2hysoapll.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imogfnpd.html

[U46] PHP：可空类型
来源：http://dali.meibo888.top/Article/details/gt2huworouq.html

?string $name = null
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzcygxjg.html

[U47] PHP：联合类型
来源：http://dali.yangfankeji.com/Article/details/gt2bdkfcuou.html

int|string $id
来源：http://dali.mhx1999.top/Article/details/gt2yqtbrqzd.html

[U48] PHP：纯枚举
来源：http://dali.hysaishi.cn/Article/details/gt2xuzhmwuf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yueranfly.top/Article/details/gt2ecizlxfa.html

[U49] PHP：只读属性
来源：http://dali.haohaochexian.top/Article/details/gt2jxlknyox.html

public readonly string $name
来源：http://dali.ppjwa.cn/Article/details/gt2wvvjgype.html

[U50] PHP：构造器属性提升
来源：http://dali.pycfn.com/Article/details/gt2jvikacad.html

public function __construct(private int $id) {}
来源：http://dali.hammf.cn/Article/details/gt2flwgfdvw.html

[U51] PHP：数组解构
来源：http://dali.meibo888.top/Article/details/gt2pfrslwpi.html

[$a, $b] = $arr;
来源：http://dali.jqgfzy.top/Article/details/gt2ydfczoha.html

[U52] PHP：箭头函数
来源：http://dali.cheryme.top/Article/details/gt2dzezafwy.html

$double = fn($x) => $x * 2;
来源：http://dali.yueranfly.top/Article/details/gt2vswgzjma.html

[U53] PHP：空合并运算符
来源：http://dali.vqdsnc.cn/Article/details/gt2nyofwquf.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzpxieau.html

[U54] PHP：空安全调用
来源：http://dali.zhoulong.xyz/Article/details/gt2rhvtibts.html

$obj?->method()
来源：http://dali.jinqigufen.top/Article/details/gt2idybdxcj.html


<!-- 参考信息 -->