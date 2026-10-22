代发 wailian999

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgxtthqi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gt2adobeibi.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gt2jkhejvyo.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gt2okgeyiez.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gt2acsfvobg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gt2vfthmbqf.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gt2ppbglbvn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kowaugat.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gt2ewuegmln.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2djyjrgxi.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ppiywoil.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2iztjnqye.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gt2hfdsvtgk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gt2uqdjzlah.html

[S38] C++：排序
来源：http://dali.jiagoushi.top/Article/details/gt2vpeygapv.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gt2uffsjfco.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gt2tppidwmd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gt2ufxgbmcz.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gt2wemooaud.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gt2vkwjjyjp.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gt2vzluscvr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gt2swooyizp.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gt2snhpixjj.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gt2mvtbwdfl.html

[S43] C++：智能指针
来源：http://dali.nanxinkj.top/Article/details/gt2ygcymnsc.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2uzhggtbi.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gt2gaaiuxuy.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gt2yusdaphs.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gt2awddsexd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gt2nrlvrsqr.html

[S46] C++：函数模板
来源：http://dali.gzhubu.top/Article/details/gt2rswfnory.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gt2bwhyhevm.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gt2egylxlea.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gt2kvgzjkuh.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2xjsaezqh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gt2mrrevktc.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kusplotc.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gt2eoonuplr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gt2orcrjpxg.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndrdfvsc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2gsadzqwa.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2faubstfh.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gt2ckqlpjqr.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gt2iefvgfqc.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gt2igudccdw.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gt2daonycyr.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gt2vcjsvrhd.html

[S54] C++：异常处理
来源：http://dali.bjfxy.top/Article/details/gt2ywmvxgqn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdnvdvdz.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gt2oeythwnn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2aipfwzdv.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gt2glbxipii.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gt2pmmepqoi.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gt2xoysepvq.html

constexpr int N = 10;
来源：http://dali.c1oappe.top/Article/details/gt2vaehyldy.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gt2gmdzatti.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gt2ciqbimop.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gt2nlqresrz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhehtgtx.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2zdqrffma.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2dytdubtp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2fyzhcxmq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gt2eeafxecn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2wemqvpyr.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bomxhhgf.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2kvylkxyl.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gt2ezfglmvd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2gzuovhqb.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxuanxn.top/Article/details/gt2zxcrwtjs.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2yylzviox.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gt2vlxitnrz.html

val n: String? = null;  n?.length
来源：http://dali.guowangkeji.top/Article/details/gt2oegphzal.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2xqfrfdup.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dashuyun.cn/Article/details/gt2zwvemlou.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2wrhdcsxm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2ysksaggq.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2mupyugfa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gt2dkcevaie.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gt2beecnune.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gt2fyfjmqig.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gt2oxyblxlz.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntoyntxj.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2cerghtun.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gt2uqydoipu.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gt2dbtapaic.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gt2lzoctlqd.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gt2ycaqvltn.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2jywnxgyq.html

[T13] Kotlin：只读 Map
来源：http://dali.yuxming.cn/Article/details/gt2fipokuhz.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2zvkessmp.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gt2fdrkhcgh.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gt2hbqcucqh.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gt2dbhyaple.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gt2twnepgqb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjnrvhl.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2qgxqbylf.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gt2tvuhzfgj.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gt2ljglvxlk.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2hydygzzb.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgiftjib.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gt2rvvatqxo.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gt2cmymsyyw.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gt2kqayauue.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gogol.net.cn/Article/details/gt2zsnrubwk.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gt2oeisldrx.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2niigcogy.html

[T22] Swift：字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vviqcpyy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfvaimph.html

[T23] Swift：函数
来源：http://dali.shuidangran.top/Article/details/gt2udhedlpg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2puxyjeyj.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gt2rztozykv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258.top/Article/details/gt2eofzmtwg.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gt2faqasjgm.html

struct P { var x: Int }
来源：http://dali.yongpay.top/Article/details/gt2vrjujqzh.html

[T26] Swift：类与重写
来源：http://dali.kuanghao11.cn/Article/details/gt2etvzqakv.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gt2vobghgsi.html

[T27] Swift：错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrkpebud.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygvgdgsy.html

[T28] Swift：枚举
来源：http://dali.guannengcc.top/Article/details/gt2fxyfgdzh.html

enum Color { case red, green }
来源：http://dali.mhx1999.top/Article/details/gt2hwetxsqu.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gt2ksrpabiq.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gt2zdzozkog.html

[T30] Swift：协议
来源：http://dali.cdnleiting.top/Article/details/gt2nyurypib.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gt2amlgslbz.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdslqmyn.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2eawhjwbv.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gt2mmajlqat.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkgqshka.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gt2wjvpjzcc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yongpay.top/Article/details/gt2svywzxkt.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrkxlgwi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gt2srulkvnw.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gt2jijzxhmn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apzgnlre.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2kfskvmcz.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gt2ymnkzavz.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gt2aduqvsei.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gt2pefqumim.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gt2hhhczckc.html

if x > 0 then print("正") end
来源：http://dali.yanxiufei.cn/Article/details/gt2vytwigyf.html

[T39] Lua：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gt2lgbjgzzo.html

string.find(s, "%d+")
来源：http://dali.snrcjt.cn/Article/details/gt2qovxmzlw.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gt2amvwwhvj.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gt2bioufqkk.html

[T41] Perl：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2mkhpihbm.html

print "Hello\n";
来源：http://dali.ppjwa.cn/Article/details/gt2jdakzsmn.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gt2leyfzopn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.snrcjt.cn/Article/details/gt2uskssxyg.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vossgzbe.html

"值: $a"
来源：http://dali.kuanghao11.cn/Article/details/gt2hknfnzwp.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gt2vjdzxtwp.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gt2crrfmejr.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gt2sapnseua.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsnrscfc.html

[T46] Perl：哈希操作
来源：http://dali.ivvv.top/Article/details/gt2sjtnsond.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sftkgrhc.html

[T47] Perl：正则捕获
来源：http://dali.jqgufenzy.top/Article/details/gt2bkufjzmq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.bjfxy.top/Article/details/gt2jdblsxlt.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gt2vxdghhco.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gt2zmkkgosg.html

[T49] Perl：函数
来源：http://dali.meibo888.top/Article/details/gt2mjppqyie.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2cuvaifnb.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2ssjhrhjd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gt2izsdgdws.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xylfe.cn/Article/details/gt2zanmumyq.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2efcdxrhs.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvnrorlx.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gt2xjlpqraa.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gt2qmhtxyvf.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gt2nyvruveq.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duweoacw.html

[T54] Scala：集合映射
来源：http://dali.hysaishi.cn/Article/details/gt2jdwpizrq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fzhhl.top/Article/details/gt2vhrhcxge.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2zdtarvvl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gt2wzdlrffs.html

[T56] Scala：样例类
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjspwzek.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gt2ilseqcaw.html

[T57] Scala：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gt2ffbjdrst.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenzaomai.com/Article/details/gt2uxphidmw.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gt2nnqzrckr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.kuanghao11.cn/Article/details/gt2ovjtsccm.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gt2clowfxrk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gt2bkuxuydg.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gt2jgdyykni.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gt2bildlupv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2hiwjmizk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2qptqsagz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2zonmgqcf.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gt2zhicfqiz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.mhx1999.top/Article/details/gt2lwerothu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yonumen.top/Article/details/gt2svxiihej.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangdashe.top/Article/details/gt2ikcocgoc.html

[U03] Py：加载 .env 配置
来源：http://dali.hfpthk.cn/Article/details/gt2nabftifd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aibaodan.cn/Article/details/gt2ofhcuqhb.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gt2moqfmrwt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.snrcjt.cn/Article/details/gt2neiiarzv.html

[U05] Py：列表去重且保序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnsgrhfo.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gt2mcpbittj.html

[U06] Py：合并两个字典
来源：http://dali.zycfv.cn/Article/details/gt2jdoqgstz.html

{**a, **b}
来源：http://dali.gogol.net.cn/Article/details/gt2prnbunwb.html

[U07] Py：反转字典键值
来源：http://dali.hysaishi.cn/Article/details/gt2waacwrvb.html

{v: k for k, v in d.items()}
来源：http://dali.yongpay.top/Article/details/gt2yobatdph.html

[U08] Py：展平二维列表
来源：http://dali.sufxvd.cn/Article/details/gt2xdnufqzt.html

[y for x in nested for y in x]
来源：http://dali.zdqjudy.top/Article/details/gt2dcbtjpfs.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxuanxn.top/Article/details/gt2bfnbpxjg.html

max(d, key=d.get)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2colgawcu.html

[U10] Py：按值排序字典
来源：http://dali.yuxming.cn/Article/details/gt2sffeakqo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.havefunace.top/Article/details/gt2msmmxyyn.html

[U11] Py：生成器表达式
来源：http://dali.guowangkeji.top/Article/details/gt2rwunwhnh.html

(x * 2 for x in arr)
来源：http://dali.ppjwa.cn/Article/details/gt2xxvvxgwu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gt2rmqtsttg.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gt2qkjdepig.html

[U13] Py：固定长度队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvtgparj.html

deque(maxlen=10)
来源：http://dali.yuanzhike.top/Article/details/gt2hmlkibdz.html

[U14] Py：分组收集到列表
来源：http://dali.pycfn.com/Article/details/gt2bjexjfcd.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gt2hkwdgaaw.html

[U15] Py：高精度计时
来源：http://dali.tianlin.xyz/Article/details/gt2ijrsirsb.html

t = time.perf_counter()
来源：http://dali.zhongyouzk.top/Article/details/gt2fjuhsfmr.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gt2wwjxfvwh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tian-w.cn/Article/details/gt2ujjmzqyx.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gt2ailcksht.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gt2pgyocpik.html

[U18] Py：预编译正则
来源：http://dali.sufxvd.cn/Article/details/gt2emtdopqb.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gt2hrhvybig.html

[U19] Py：正则替换带回调
来源：http://dali.zhiwuduotai.top/Article/details/gt2gtzlwmmq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hysaishi.cn/Article/details/gt2jlciutem.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gt2iovrnyxc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gt2jdancmzz.html

[U21] Py：自定义上下文管理器
来源：http://dali.yonumen.top/Article/details/gt2meziqsno.html

@contextlib.contextmanager
来源：http://dali.cqqwz.cn/Article/details/gt2noreuhsh.html

[U22] Py：矩阵转置
来源：http://dali.haohaochexian.top/Article/details/gt2fqkuutnd.html

list(zip(*m))
来源：http://dali.yj20258.top/Article/details/gt2xyjhpjdp.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gt2qcoszemo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gt2zucozlhd.html

[U24] Py：路径操作
来源：http://dali.ivvv.top/Article/details/gt2ogcwlgge.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxrjuygm.html

[U25] Py：CSV 按字典读
来源：http://dali.aizwys.cn/Article/details/gt2yvlfrewt.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gt2oqikixlp.html

[U26] Py：并发下载
来源：http://dali.chenlongwang.top/Article/details/gt2fdoafxbh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shzxlz.cn/Article/details/gt2jjybibzr.html

[U27] Py：异步 HTTP
来源：http://dali.gzhubu.top/Article/details/gt2kaewqnep.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yonumen.top/Article/details/gt2vsnucrcg.html

[U28] Py：类型别名
来源：http://dali.dianchejie.cn/Article/details/gt2nkellcqx.html

UserId = int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izcupbgv.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gt2hnxadmxd.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gt2mhmgbzki.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gt2kmvyqwpw.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2xthqbdev.html

[U31] Py：单测
来源：http://dali.yueranfly.top/Article/details/gt2lgbjxpuz.html

python -m pytest -q
来源：http://dali.ydzc1.top/Article/details/gt2spkgfpmc.html

[U32] Py：代码格式化
来源：http://dali.316326.xyz/Article/details/gt2rlicryep.html

ruff format . && ruff check --fix .
来源：http://dali.smart0.xyz/Article/details/gt2nvinoncg.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gt2nrklwyme.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gt2oaopwnib.html

[U34] Py：判断编码
来源：http://dali.pycfn.com/Article/details/gt2aboqongr.html

chardet.detect(raw)
来源：http://dali.hammf.cn/Article/details/gt2lzhdbnai.html

[U35] Py：发送邮件
来源：http://dali.tian-w.cn/Article/details/gt2vrievxul.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gt2zhodjukg.html

[U36] Py：定时任务
来源：http://dali.aizwys.cn/Article/details/gt2tetrfdnz.html

schedule.every(10).minutes.do(job)
来源：http://dali.cdnleiting.top/Article/details/gt2ylpeexeb.html

[U37] Py：读写 Excel
来源：http://dali.redwolf501.top/Article/details/gt2evryhzgg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aibaodan.cn/Article/details/gt2yujheasj.html

[U38] Py：获取脚本所在目录
来源：http://dali.smart0.xyz/Article/details/gt2mscrinmd.html

Path(__file__).resolve().parent
来源：http://dali.daria6918.cn/Article/details/gt2iybkoluh.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzssvyyq.html

sys.stdout.isatty()
来源：http://dali.smart0.xyz/Article/details/gt2bpqldrjh.html

[U40] Py：打印到标准错误
来源：http://dali.tanke756.top/Article/details/gt2oxdqypmh.html

print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gt2cxiinwht.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.birdmap.top/Article/details/gt2zvttnuoi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyhihxu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jianghu66.top/Article/details/gt2xqxrvmgg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftodcudh.html

[U43] PHP：声明命名空间
来源：http://dali.daxiang520.top/Article/details/gt2wokkhduw.html

namespace App\Http;
来源：http://dali.cheryme.top/Article/details/gt2jmozurlj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpwqovg.html

declare(strict_types=1);
来源：http://dali.jqgfzy.top/Article/details/gt2cdqwhbfz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aibaodan.cn/Article/details/gt2pmuvijsv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2nqpnqtdc.html

[U46] PHP：可空类型
来源：http://dali.cashguo.top/Article/details/gt2lwsxocwo.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gt2xpxmdkyf.html

[U47] PHP：联合类型
来源：http://dali.ppjwa.cn/Article/details/gt2buseecnh.html

int|string $id
来源：http://dali.sxryk.cn/Article/details/gt2kcbuseul.html

[U48] PHP：纯枚举
来源：http://dali.hywenlv.cn/Article/details/gt2kqwynosu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.mhx1999.top/Article/details/gt2lccykcjy.html

[U49] PHP：只读属性
来源：http://dali.nanxuanxn.top/Article/details/gt2blzhiqge.html

public readonly string $name
来源：http://dali.hammf.cn/Article/details/gt2lmxyskcy.html

[U50] PHP：构造器属性提升
来源：http://dali.birdmap.top/Article/details/gt2xqjrmctr.html

public function __construct(private int $id) {}
来源：http://dali.fzhhl.top/Article/details/gt2hwyitxoj.html

[U51] PHP：数组解构
来源：http://dali.ehwqpu.com/Article/details/gt2zzzcaljr.html

[$a, $b] = $arr;
来源：http://dali.jinqigufen.top/Article/details/gt2ooktykke.html

[U52] PHP：箭头函数
来源：http://dali.birdmap.top/Article/details/gt2gosogpps.html

$double = fn($x) => $x * 2;
来源：http://dali.chenzaomai.com/Article/details/gt2fdclbjpl.html

[U53] PHP：空合并运算符
来源：http://dali.birdmap.top/Article/details/gt2yxjupubl.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuetiantiany.cn/Article/details/gt2errtlfwn.html

[U54] PHP：空安全调用
来源：http://dali.wangdashe.top/Article/details/gt2aqcjkqio.html

$obj?->method()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxycogty.html

[U55] PHP：match 表达式
来源：http://dali.jinqigufen.top/Article/details/gt2mlpkbntz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gt2siqqnauc.html

[U56] PHP：命名参数
来源：http://dali.yongpay.top/Article/details/gt2qkmndxdq.html

f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2lckqcwwu.html


<!-- 参考信息 -->