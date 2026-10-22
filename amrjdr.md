代发 wailian999

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gt2dtoihluk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gt2ervviuhs.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gt2wfulhlpo.html

std::string s = "hi";  s += "!";
来源：http://dali.daria6918.cn/Article/details/gt2bpzeomlg.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gt2wkuxbuei.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gt2uobujykb.html

[S34] C++：遍历 vector
来源：http://dali.meibo888.top/Article/details/gt2xouzoenn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pycfn.com/Article/details/gt2xljcoyci.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmqduite.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2pgwhjwrn.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gt2dqprtdwy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2bebcbpbv.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gt2oknhavtl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gt2jhidhyna.html

[S38] C++：排序
来源：http://dali.cqqwz.cn/Article/details/gt2eeblntbf.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gt2snnthjxv.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gt2eigumtlk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gt2obbnclnh.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gt2ktcewvww.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gt2mbpttqan.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gt2pwfoxopt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gt2jgvjxvba.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gt2kpbhwjae.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gt2rosxwdwb.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gt2kfqxkybg.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gt2voyxpzlw.html

[S44] C++：引用传参
来源：http://dali.yj20258888.top/Article/details/gt2bytnqnuw.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gt2yejgbzgs.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gt2ylxtjexa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bucoezah.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gt2fdbvpghq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gt2aoempuig.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gt2wmwjzcro.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gt2arrqizsz.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpysdjfm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gt2ixvonsvu.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2doffzzkn.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zutjajer.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gt2kicovlly.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gt2pjvssfkk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2ahmmbdus.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gt2sxzarily.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gt2uciaffkp.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gt2elwziiak.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gt2ymuuprpb.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gt2sajwvxtn.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gt2vhwwinan.html

[S54] C++：异常处理
来源：http://dali.hywenlv.cn/Article/details/gt2nmsklnrq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gt2fzqrtcdi.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chykbnja.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gt2vvfvhfch.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gt2zqfiliej.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gt2tkqtxboo.html

[S57] C++：编译期常量
来源：http://dali.hfpthk.cn/Article/details/gt2komggilr.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gt2xmrvyata.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gt2fyaansiu.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gt2utuyagsa.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcqibwua.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydhluilo.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gt2iqfuwnsc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gt2iocxjwwr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ntgdjcmh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gt2ometclht.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2uxpafhzq.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2vogdprgc.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gt2qljrukva.html

[T02] Kotlin：变量
来源：http://dali.mhx1999.top/Article/details/gt2isbnytzu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gt2ifonqtae.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gt2gdvjpwcu.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gt2nzcshmbh.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gt2khehahwb.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gt2ghsisxab.html

[T05] Kotlin：when 表达式
来源：http://dali.316326.xyz/Article/details/gt2jtvzoxlj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gt2dthcvsfy.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gt2ginkiasc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gt2olehlrng.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gt2szzxklhr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gt2jmdlmzmv.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2ebpgecur.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zryxgqpe.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gt2iqnijzxm.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gt2luqnteem.html

[T10] Kotlin：默认参数
来源：http://dali.zhengqikj.top/Article/details/gt2lbjdepyd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gt2awxqogzt.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gt2qlsgwuzr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gt2ciyvjxxi.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gt2akogocry.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2utenyfwb.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gt2wwxknwil.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gt2dulexzza.html

[T14] Kotlin：循环
来源：http://dali.yuxming.cn/Article/details/gt2mpsrqmfu.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtckbuee.html

[T15] Kotlin：接口
来源：http://dali.xylfe.cn/Article/details/gt2hvhegieu.html

interface Shape { fun area(): Double }
来源：http://dali.xylfe.cn/Article/details/gt2bwvrydhp.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2dqmvijtj.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwftexgn.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gt2jgywbueb.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gt2gujbymwv.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2vyuykapr.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gt2cbrwadus.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gt2hujskdlz.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gt2fascdcey.html

[T20] Swift：数组操作
来源：http://dali.cqqwz.cn/Article/details/gt2eklomsfm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hucsyvkl.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppcpflkv.html

for x in a { print(x) }
来源：http://dali.xuanzx.com/Article/details/gt2aevtjmxg.html

[T22] Swift：字典
来源：http://dali.smart0.xyz/Article/details/gt2nvtsfhln.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gt2fmvackdp.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gt2aftiwkrm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gt2ebvhsgle.html

[T24] Swift：闭包
来源：http://dali.zhengqikj.top/Article/details/gt2apzvflpk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2xlnqeiux.html

[T25] Swift：结构体
来源：http://dali.yuanzhike.top/Article/details/gt2cqmjupew.html

struct P { var x: Int }
来源：http://dali.quarkkingdee.top/Article/details/gt2dgtycpct.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gt2jeeuvbvo.html

class A: Base { override func f() {} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwjhmvdn.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbtdtarj.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gt2hqbisvws.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gt2mlskwglc.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gt2cesnzvxz.html

[T29] Swift：guard 提前返回
来源：http://dali.sxryk.cn/Article/details/gt2zozbsjtq.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gt2lfqrrhuh.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gt2qyxwyage.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhtpfmgd.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgzwecnr.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2rsugowmr.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gt2yoaaqxen.html

local a = 1
来源：http://dali.ydzc1.top/Article/details/gt2iuxnulgg.html

[T33] Lua：表（数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2vkjdeapq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxinkj.top/Article/details/gt2duqtzzij.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gt2aqtahhnd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gt2pjtmcufl.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gt2iqumlcpf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gt2dnqneztz.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnffhhhi.html

function add(a, b) return a + b end
来源：http://dali.jinqigufen.top/Article/details/gt2lfwfsumj.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gt2qwrcxtbb.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gt2stastecq.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwbigdpz.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gt2vqagcpnq.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gt2ddjpsotl.html

string.find(s, "%d+")
来源：http://dali.cucudq.cn/Article/details/gt2foqpkfwn.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2koueajux.html

setmetatable({}, { __index = base })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sitrwmzw.html

[T41] Perl：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjobpyqi.html

print "Hello\n";
来源：http://dali.yj202588.top/Article/details/gt2dbsvkadx.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gt2rlrgxqpi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dianchejie.cn/Article/details/gt2vmtgmlzk.html

[T43] Perl：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gt2fnmkcwbp.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gt2kofobmkm.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2swfqdltd.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gt2afygssqc.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gt2caiszchr.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gt2fgtnpnja.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gt2marjggwo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gt2xtpsoplt.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gt2wyixilpf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gt2joncrttx.html

[T48] Perl：正则替换
来源：http://dali.jinqigufen.top/Article/details/gt2rgrixjzu.html

$s =~ s/old/new/g;
来源：http://dali.kuanghao11.cn/Article/details/gt2hcpwlffj.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gt2pqbzqbcr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2ejxwpouq.html

[T50] Perl：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2ngqadvmo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gt2ntsfenbv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hammf.cn/Article/details/gt2xottbego.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2blctyquw.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2ixmmwgpx.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gt2gooslehj.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gt2bziojcfi.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2tubdmykn.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxthztlr.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gt2yoxgqraz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmkwrabe.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2olnobyfq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj202588.top/Article/details/gt2qzysilnd.html

[T56] Scala：样例类
来源：http://dali.wangdashe.top/Article/details/gt2ljxfbaqc.html

case class User(name: String, age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkiaolna.html

[T57] Scala：模式匹配
来源：http://dali.gzhubu.top/Article/details/gt2sbropexh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guannengcc.top/Article/details/gt2wltwbrkg.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gt2zriqbcmo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sysykeji.top/Article/details/gt2dqajbfis.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gt2ziqkfzqc.html

for (i <- 1 to 10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2sbbsvfjo.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gt2zlifynrh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gt2fvaeteij.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2nbqzlsrr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gt2yxuvpiqh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2kyzyovhm.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gt2ffapznyc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gt2cffspdsm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gt2kxvvyjfq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gt2vxhvegro.html

[U03] Py：加载 .env 配置
来源：http://dali.zhongyouzk.top/Article/details/gt2isuiphkf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wemxtnbl.html

[U04] Py：变量调试打印
来源：http://dali.hnqzz.top/Article/details/gt2izlfgipy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yangfankeji.com/Article/details/gt2wygejnaq.html

[U05] Py：列表去重且保序
来源：http://dali.cashguo.top/Article/details/gt2ovmthsjv.html

list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gt2wzxkjoda.html

[U06] Py：合并两个字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2lasotcry.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gt2jroglpyh.html

[U07] Py：反转字典键值
来源：http://dali.yanxiufei.cn/Article/details/gt2jvyatzqh.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gt2haekpcow.html

[U08] Py：展平二维列表
来源：http://dali.zycfv.cn/Article/details/gt2wvwkdnfk.html

[y for x in nested for y in x]
来源：http://dali.havefunace.top/Article/details/gt2epvmveex.html

[U09] Py：字典取最大值的键
来源：http://dali.yanxiufei.cn/Article/details/gt2zfhybkib.html

max(d, key=d.get)
来源：http://dali.xziqi.cn/Article/details/gt2tberabcp.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpjirbya.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhongyouzk.top/Article/details/gt2vgeownfj.html

[U11] Py：生成器表达式
来源：http://dali.svipenyu.cn/Article/details/gt2odwllpox.html

(x * 2 for x in arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjcxoaez.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gt2ibwybywa.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gt2nsimbqll.html

[U13] Py：固定长度队列
来源：http://dali.chenlongwang.top/Article/details/gt2cwgragze.html

deque(maxlen=10)
来源：http://dali.meibo888.top/Article/details/gt2gbwdfoyk.html

[U14] Py：分组收集到列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2mslhzktr.html

defaultdict(list)
来源：http://dali.tian-w.cn/Article/details/gt2ghlpmntb.html

[U15] Py：高精度计时
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlewuwxn.html

t = time.perf_counter()
来源：http://dali.snrcjt.cn/Article/details/gt2gehynfxn.html

[U16] Py：命令行参数解析
来源：http://dali.xuanzx.com/Article/details/gt2ovilylfe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guannengcc.top/Article/details/gt2hclstrtz.html

[U17] Py：初始化日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2xiuvpsim.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jianghu66.top/Article/details/gt2jxxljten.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gt2blxeinqg.html

pat = re.compile(r"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2spyghpkq.html

[U19] Py：正则替换带回调
来源：http://dali.guowangkeji.top/Article/details/gt2pbdldttz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwptgbfq.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258888.top/Article/details/gt2subxnjsw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yongpay.top/Article/details/gt2dlyfolws.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gt2maakdnzb.html

@contextlib.contextmanager
来源：http://dali.hysaishi.cn/Article/details/gt2fpokwiru.html

[U22] Py：矩阵转置
来源：http://dali.shzxlz.cn/Article/details/gt2qwltmwyn.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gt2taoodzxr.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gt2rxcuoskk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cheryme.top/Article/details/gt2ehwaluxl.html

[U24] Py：路径操作
来源：http://dali.hammf.cn/Article/details/gt2zdymfzoh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gt2eznrtjjh.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuasynaq.html

csv.DictReader(f)
来源：http://dali.aizwys.cn/Article/details/gt2ulmkpswl.html

[U26] Py：并发下载
来源：http://dali.cheryme.top/Article/details/gt2atgutjyf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuanzx.com/Article/details/gt2rigvuinf.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gt2xicyqnvj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cashguo.top/Article/details/gt2aozausgz.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gt2iiukoqol.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfvfglfk.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gt2ejsbahgc.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gt2ehfxdjrg.html

[U30] Py：数据类
来源：http://dali.birdmap.top/Article/details/gt2arhhbcpf.html

@dataclass(slots=True)
来源：http://dali.tian-w.cn/Article/details/gt2seyrvmiu.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gt2fhchxwpo.html

python -m pytest -q
来源：http://dali.guowangkeji.top/Article/details/gt2agialvte.html

[U32] Py：代码格式化
来源：http://dali.316326.xyz/Article/details/gt2hkqrwgtm.html

ruff format . && ruff check --fix .
来源：http://dali.svipenyu.cn/Article/details/gt2myuovsok.html

[U33] Py：打包发布
来源：http://dali.aizwys.cn/Article/details/gt2gdnsdiwy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpspjnr.html

[U34] Py：判断编码
来源：http://dali.jinqigfzy.top/Article/details/gt2blmsbcgd.html

chardet.detect(raw)
来源：http://dali.9152youxi.cn/Article/details/gt2lxpgqhmm.html

[U35] Py：发送邮件
来源：http://dali.fengsongda.top/Article/details/gt2rqnuyrnl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pengpengdd.cyou/Article/details/gt2whvgpoao.html

[U36] Py：定时任务
来源：http://dali.yj202588.top/Article/details/gt2qugbjmfd.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigufen.top/Article/details/gt2ixtkgkyk.html

[U37] Py：读写 Excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgtqbluv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuanzhike.top/Article/details/gt2bfedflzp.html

[U38] Py：获取脚本所在目录
来源：http://dali.9152youxi.cn/Article/details/gt2jvnzawfa.html

Path(__file__).resolve().parent
来源：http://dali.hysaishi.cn/Article/details/gt2qfhhhzqi.html

[U39] Py：判断是否在交互环境
来源：http://dali.yvedp.cn/Article/details/gt2ubcgjaec.html

sys.stdout.isatty()
来源：http://dali.zdqjudy.top/Article/details/gt2niuaqhlj.html

[U40] Py：打印到标准错误
来源：http://dali.xinyue.icu/Article/details/gt2ekkbjlzq.html

print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjtohznh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gt2qijcumgk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sysykeji.top/Article/details/gt2acascqie.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.smart0.xyz/Article/details/gt2xbdxlksb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxuanxn.top/Article/details/gt2awydeozv.html

[U43] PHP：声明命名空间
来源：http://dali.zhoulong.xyz/Article/details/gt2tejxngcf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2phtryowj.html

[U44] PHP：开启严格类型
来源：http://dali.0kj1m.cn/Article/details/gt2hbqjgank.html

declare(strict_types=1);
来源：http://dali.jlsjyb.cn/Article/details/gt2agisetmx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cashguo.top/Article/details/gt2ndmextvh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgxhgnhj.html

[U46] PHP：可空类型
来源：http://dali.zycfv.cn/Article/details/gt2bxfsscfk.html

?string $name = null
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2meefaajo.html

[U47] PHP：联合类型
来源：http://dali.tanke756.top/Article/details/gt2kpildlpm.html

int|string $id
来源：http://dali.wangdashe.top/Article/details/gt2thvjuafg.html

[U48] PHP：纯枚举
来源：http://dali.pycfn.com/Article/details/gt2gnffplzf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.andypj.xyz/Article/details/gt2qchdbayd.html

[U49] PHP：只读属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhfkrssg.html

public readonly string $name
来源：http://dali.aizwys.cn/Article/details/gt2toenhsnn.html

[U50] PHP：构造器属性提升
来源：http://dali.daria6918.cn/Article/details/gt2sgdxldnh.html

public function __construct(private int $id) {}
来源：http://dali.yvedp.cn/Article/details/gt2qcvgayzy.html

[U51] PHP：数组解构
来源：http://dali.kuanghao11.cn/Article/details/gt2jdoqfjnk.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gt2snlpqcjz.html

[U52] PHP：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gt2xhrnfrmm.html

$double = fn($x) => $x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhiidpmr.html

[U53] PHP：空合并运算符
来源：http://dali.jyoumei.cn/Article/details/gt2nptglugo.html

$v = $a ?? $b ?? "default";
来源：http://dali.aizwys.cn/Article/details/gt2bnezwsok.html

[U54] PHP：空安全调用
来源：http://dali.tianlin.xyz/Article/details/gt2uchgojnr.html

$obj?->method()
来源：http://dali.ppjwa.cn/Article/details/gt2nzrsqvzn.html

[U55] PHP：match 表达式
来源：http://dali.fzhhl.top/Article/details/gt2mlmldlkz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.fzhhl.top/Article/details/gt2mjluodbr.html

[U56] PHP：命名参数
来源：http://dali.shuidangran.top/Article/details/gt2krlglgpp.html

f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wicvdkcm.html


<!-- 参考信息 -->