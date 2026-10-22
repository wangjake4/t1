代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.nwbrower.top/Article/details/gt2tpffkmgy.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gt2lssgilug.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2ayxssyie.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gt2mqpeeiie.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gt2lyfgczab.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gt2iyosmufn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gt2zoyldjpi.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzsfbfhy.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjpyzpjb.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gt2inotzvdp.html

#endif
来源：http://dali.yueranfly.top/Article/details/gt2idfyktmb.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2ubgiljed.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gt2mtqchddp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xylfe.cn/Article/details/gt2ltxjyado.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gt2hoqrqyyq.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gt2uftenqcf.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gt2vpokhepl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gt2xkudfijn.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gt2ckrjfiqu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gt2puynqkok.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gt2urximlqn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2poxwsbht.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gt2ogpbwcdo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2rqyduiuq.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gt2dbvcwkxu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2ldjocvar.html

[S38] C++：排序
来源：http://dali.xylfe.cn/Article/details/gt2dpupygis.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2tbdmhehk.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gt2okhknzhi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gt2umpqzijh.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2ennxsiqd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gt2krkokewa.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2cxrljlhh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gt2xrjmsehn.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gt2uapgsyqf.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gt2twzsrkdw.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gt2erknehux.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gt2ykmdepdw.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gt2akbcspim.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gt2gpooawpx.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gt2znudhxeg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfjsrpwx.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gt2ushsrkxk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxfmboip.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gt2odiqvwjy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gt2prgljyue.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldnohcmm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gt2ndlpgvvf.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gt2lxxzivqo.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2aevqahva.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpbsdfgl.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gt2cjwwoaeg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2oegnxxte.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2eshggsns.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gt2iyytrbbd.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gt2chibrntc.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gt2jcszkpwo.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gt2melwydez.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vatbyqjy.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gt2srlxvopi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gt2leyhjlbh.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gt2oskwvgxf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gt2yrrlzooc.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gt2njwchhna.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gt2ktdqbred.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gt2dbadxvao.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gt2dyeiekog.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqqjxfjf.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dybgawjt.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mpwtsnob.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kinzcefs.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gt2irnohygb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2opisoyag.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2yyqippkj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gt2cljahprm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2wmjafqav.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2jbmcipva.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gt2snpkzfsm.html

[T02] Kotlin：变量
来源：http://dali.ydzc1.top/Article/details/gt2ikuumbgw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnonoja.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gt2wlnzkumb.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gt2vqtjayfa.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gt2vhnzynwj.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gt2nevalcek.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hwknxnyu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gt2aommxexr.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gt2cgpzzqou.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2abiwtxvp.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gt2jyhvrelt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gt2irfkoeem.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrepqnvg.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2lnyubhkg.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gt2sdbthdtm.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gt2lsbjqsby.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gt2lahdrxns.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gt2lqwuvadb.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gt2cgkmeiol.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gt2pyrpcdzy.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gt2saqcozmn.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2jpmjjlbl.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gt2nwzkppaz.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2naggdyht.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gt2vzbiyxqk.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gt2kkrkgige.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gt2knrckljr.html

interface Shape { fun area(): Double }
来源：http://dali.zhongyouzk.top/Article/details/gt2krelianp.html

[T16] Swift：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2pstpumgn.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gt2xvdlzxqm.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gt2jyywjcsr.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gt2hztrfral.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2xthwoquo.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gt2fsnnucjc.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gt2ozkucomm.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uonyjpwp.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gt2bsbaipef.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gt2nrgicvdp.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2kphaqqro.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gt2hotlonqq.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gt2bmimrmwg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pycfn.com/Article/details/gt2hensuxkt.html

[T23] Swift：函数
来源：http://dali.chenlongwang.top/Article/details/gt2rbqjeijq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gt2qwomrdvq.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gt2ishatpnr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2sbetdtcj.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gt2xdkfzzju.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gt2aivnbriw.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gt2pjjdxywe.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gt2jbsfnipt.html

[T27] Swift：错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2neqkmlie.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqzebjna.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gt2agdwocny.html

enum Color { case red, green }
来源：http://dali.hnxiangtu.top/Article/details/gt2dectkjwx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twjfkmzx.html

guard let x = opt else { return }
来源：http://dali.daxiang520.top/Article/details/gt2lultawtt.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gt2aythbnlv.html

protocol Shape { func area() -> Double }
来源：http://dali.yanxiufei.cn/Article/details/gt2lgjygfti.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2tbxsdvby.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2usxxxwxg.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gt2lcghyetq.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gt2idfhjajn.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gt2kwanmsuc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gt2cwucqgpt.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gt2zrkzsotn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gt2owbcohmz.html

[T35] Lua：字典表
来源：http://dali.9152youxi.cn/Article/details/gt2uvsehexi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gt2hqhjafvc.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gt2guvqlmvl.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gt2cvgxkdwl.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gt2sjpwsjmw.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gt2alcxvcxj.html

[T38] Lua：条件
来源：http://dali.jqgufenzy.top/Article/details/gt2wlpmgjyn.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gt2qhxywkgo.html

[T39] Lua：模式匹配
来源：http://dali.andypj.xyz/Article/details/gt2qopgfqhf.html

string.find(s, "%d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2jddcwdsl.html

[T40] Lua：元表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipjccrzc.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2duezsjfc.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2ghwbuldv.html

print "Hello\n";
来源：http://dali.nwbrower.top/Article/details/gt2haopopjp.html

[T42] Perl：变量类型
来源：http://dali.snrcjt.cn/Article/details/gt2rsccjaig.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2ikacusny.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2kkphbhxe.html

"值: $a"
来源：http://dali.guannengcc.top/Article/details/gt2ntwadjkz.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsttapby.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gt2gxpedxjt.html

[T45] Perl：数组遍历
来源：http://dali.ehwqpu.com/Article/details/gt2bcpygmvm.html

for my $x (@arr) { print $x; }
来源：http://dali.ivvv.top/Article/details/gt2bsansyjo.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gt2rpuuotuy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sweek.top/Article/details/gt2ustrqghf.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gt2tqpcepik.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pleachmk.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gt2trlcfvyb.html

$s =~ s/old/new/g;
来源：http://dali.zhongyouzk.top/Article/details/gt2zjyaiaad.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gt2goqbwwia.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2zgsywfsn.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2ltlmqabp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gt2nsvqsmwn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guannengcc.top/Article/details/gt2bvxkqahy.html

[T51] Scala：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2khxvyuux.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2qssbwycd.html

[T52] Scala：变量
来源：http://dali.zhoulong.xyz/Article/details/gt2hasdaunq.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2xlcecbhg.html

[T53] Scala：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2asujvwau.html

s"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlhhvnxf.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2uejbkczi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gt2vizebych.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcapafwv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdaqzqdm.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gt2owiwevyf.html

case class User(name: String, age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbbjqxmi.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2sqjuacnl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2umgttpqt.html

[T58] Scala：函数定义
来源：http://dali.xinyue.icu/Article/details/gt2vhrlwjak.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvvxjlra.html

[T59] Scala：循环
来源：http://dali.nanxuanxn.top/Article/details/gt2ichygrnd.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmbjmfzx.html

[T60] Scala：折叠
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujoowcee.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hammf.cn/Article/details/gt2wswaghzq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2hhlkuvgt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gt2msjtleyr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ljunsrrl.html

[U01] Py：创建虚拟环境
来源：http://dali.dashuyun.cn/Article/details/gt2pbkohkpf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gt2nlwepdrr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.haohaochexian.top/Article/details/gt2cqfmbnuy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gt2yzetdbhv.html

[U03] Py：加载 .env 配置
来源：http://dali.yj20258.top/Article/details/gt2ldrquyfu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykmozsfr.html

[U04] Py：变量调试打印
来源：http://dali.havefunace.top/Article/details/gt2pmipkbhi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2poxgnuxo.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gt2qhvmyukk.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gt2ayjxcpkm.html

[U06] Py：合并两个字典
来源：http://dali.hfpthk.cn/Article/details/gt2zxhsdfdj.html

{**a, **b}
来源：http://dali.birdmap.top/Article/details/gt2maltwvvc.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gt2yrkczxnu.html

{v: k for k, v in d.items()}
来源：http://dali.snrcjt.cn/Article/details/gt2txdjbyyj.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gt2rmxjxtez.html

[y for x in nested for y in x]
来源：http://dali.yuanzhike.top/Article/details/gt2cmjxcgvo.html

[U09] Py：字典取最大值的键
来源：http://dali.yj202588.top/Article/details/gt2tdmzruwe.html

max(d, key=d.get)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ksbcboak.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gt2kfquwvwi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gt2xjnefvzy.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gt2rxbicjnl.html

(x * 2 for x in arr)
来源：http://dali.hammf.cn/Article/details/gt2ocgvshcs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gt2pemcegpp.html

Counter(arr).most_common(3)
来源：http://dali.smart0.xyz/Article/details/gt2uwrjdciw.html

[U13] Py：固定长度队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrcwzepw.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gt2kmmsanpv.html

[U14] Py：分组收集到列表
来源：http://dali.zhongyouzk.top/Article/details/gt2vbsmrhyl.html

defaultdict(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxrsnymh.html

[U15] Py：高精度计时
来源：http://dali.cqqwz.cn/Article/details/gt2enwirydj.html

t = time.perf_counter()
来源：http://dali.chenlongwang.top/Article/details/gt2afdcfnmm.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gt2fzxwmhtn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zycfv.cn/Article/details/gt2ztztaedl.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gt2wlrrdjnd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gt2vzdvjirg.html

[U18] Py：预编译正则
来源：http://dali.andypj.xyz/Article/details/gt2spfihsfj.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gt2hafwsnhn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmjjmjq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tanke756.top/Article/details/gt2gdzxdhos.html

[U20] Py：缓存函数结果
来源：http://dali.yuanzhike.top/Article/details/gt2pzxinwpb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj202588.top/Article/details/gt2mfxokdqh.html

[U21] Py：自定义上下文管理器
来源：http://dali.0kj1m.cn/Article/details/gt2tgozajmt.html

@contextlib.contextmanager
来源：http://dali.jyoumei.cn/Article/details/gt2ueehlivi.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gt2upqamijo.html

list(zip(*m))
来源：http://dali.hfpthk.cn/Article/details/gt2xnthfhfw.html

[U23] Py：分块读取大文件
来源：http://dali.wangdashe.top/Article/details/gt2luiyqckh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjzybpob.html

[U24] Py：路径操作
来源：http://dali.ybcxt.top/Article/details/gt2tpavufvw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gt2hsiywpgt.html

[U25] Py：CSV 按字典读
来源：http://dali.smart0.xyz/Article/details/gt2ejnjkwxv.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gt2hnoskrbu.html

[U26] Py：并发下载
来源：http://dali.jyoumei.cn/Article/details/gt2nlhzujfe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gt2askpcear.html

[U27] Py：异步 HTTP
来源：http://dali.gzhubu.top/Article/details/gt2gemsxpqm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigufen.top/Article/details/gt2xesdslwp.html

[U28] Py：类型别名
来源：http://dali.chenlongwang.top/Article/details/gt2xslnytdb.html

UserId = int
来源：http://dali.cucudq.cn/Article/details/gt2rhbcrokx.html

[U29] Py：属性校验
来源：http://dali.jqgufenzy.top/Article/details/gt2izvrprmj.html

@property 与 @x.setter 配合
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdsrpskk.html

[U30] Py：数据类
来源：http://dali.hysaishi.cn/Article/details/gt2plfsilso.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gt2mexlskyx.html

[U31] Py：单测
来源：http://dali.mhx1999.top/Article/details/gt2qvywcrcy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bekifdbe.html

[U32] Py：代码格式化
来源：http://dali.pycfn.com/Article/details/gt2sgaglmst.html

ruff format . && ruff check --fix .
来源：http://dali.sysykeji.top/Article/details/gt2uiixlldu.html

[U33] Py：打包发布
来源：http://dali.cheryme.top/Article/details/gt2ivpjnral.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhcgekbo.html

[U34] Py：判断编码
来源：http://dali.tianlin.xyz/Article/details/gt2nlperqjw.html

chardet.detect(raw)
来源：http://dali.feifeiyinyue.top/Article/details/gt2armsgafk.html

[U35] Py：发送邮件
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgdcqskn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gzhubu.top/Article/details/gt2yfgposnn.html

[U36] Py：定时任务
来源：http://dali.aizwys.cn/Article/details/gt2yoedznzb.html

schedule.every(10).minutes.do(job)
来源：http://dali.andypj.xyz/Article/details/gt2ajweeyns.html

[U37] Py：读写 Excel
来源：http://dali.jyoumei.cn/Article/details/gt2hdjsvkdg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yvedp.cn/Article/details/gt2rimuszvc.html

[U38] Py：获取脚本所在目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2scoytgpo.html

Path(__file__).resolve().parent
来源：http://dali.gogol.net.cn/Article/details/gt2vxsesucm.html

[U39] Py：判断是否在交互环境
来源：http://dali.316326.xyz/Article/details/gt2jssrwuql.html

sys.stdout.isatty()
来源：http://dali.yuxming.cn/Article/details/gt2crxlbxqq.html

[U40] Py：打印到标准错误
来源：http://dali.xylfe.cn/Article/details/gt2nrhpmogj.html

print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gt2uvgkllgp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xylfe.cn/Article/details/gt2ftpcovok.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fengsongda.top/Article/details/gt2ngcodaqu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.quarkkingdee.top/Article/details/gt2obntkhrd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jianghu66.top/Article/details/gt2ldwyblhf.html

[U43] PHP：声明命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gt2adhfceoi.html

namespace App\Http;
来源：http://dali.zhengqikj.top/Article/details/gt2ozupqwjr.html

[U44] PHP：开启严格类型
来源：http://dali.cucudq.cn/Article/details/gt2cumnreyx.html

declare(strict_types=1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtwhxxtx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.c1oappe.top/Article/details/gt2hhwyanbo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2zbcyiipl.html

[U46] PHP：可空类型
来源：http://dali.ybcxt.top/Article/details/gt2inczvvhu.html

?string $name = null
来源：http://dali.guannengcc.top/Article/details/gt2ulwuilrs.html

[U47] PHP：联合类型
来源：http://dali.mhx1999.top/Article/details/gt2feqybdkc.html

int|string $id
来源：http://dali.9152youxi.cn/Article/details/gt2sruppyrq.html

[U48] PHP：纯枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfkdzpse.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxinkj.top/Article/details/gt2qzojrvga.html

[U49] PHP：只读属性
来源：http://dali.nwbrower.top/Article/details/gt2vfoejlly.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gt2ertqtilk.html

[U50] PHP：构造器属性提升
来源：http://dali.andypj.xyz/Article/details/gt2axrynsrf.html

public function __construct(private int $id) {}
来源：http://dali.zycfv.cn/Article/details/gt2gqsshjkq.html


<!-- 参考信息 -->