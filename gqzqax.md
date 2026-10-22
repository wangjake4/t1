代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gt2viytlujm.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gt2teaqpbsn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gt2krwrwjnj.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gt2ijtcwosq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xylfe.cn/Article/details/gt2qiytozpi.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gt2bpfakhsh.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwfsxmas.html

[S26] C：内存清零
来源：http://dali.gzhubu.top/Article/details/gt2unvxhdfj.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gt2ophdkjbe.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqrmtzja.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2xkhdviov.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gt2xfgescwg.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gt2waohydmd.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gt2jdlayqyj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyvqxyyl.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gt2xgjlnmbs.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gt2etvbznwq.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gt2xtjixpxe.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gt2fmezopse.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qegfkefc.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gt2kcjcbtkl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gt2lzpeuzen.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gt2diuqazze.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gt2ffvkongz.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gt2cwwnlhgf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gt2qimnjkvk.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gt2ofrkcqdz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gt2asnlxvea.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxmvqlus.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2dkypieyd.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gt2gfsqgsyd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2dgsgnvmz.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gt2tvydbcsc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxxszmzs.html

[S38] C++：排序
来源：http://dali.yj202588.top/Article/details/gt2dbrxnlua.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gt2tgeraloi.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gt2qfwbodrp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsrxxusv.html

[S40] C++：查找元素
来源：http://dali.pycfn.com/Article/details/gt2shhqagfi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gt2ipmrssdr.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gt2wqjmcuet.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gt2rrawkmhj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqzgsqf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhengqikj.top/Article/details/gt2lddtzrfq.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gt2krjxhjja.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gt2nrpyqvzn.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gt2zjvivkpp.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gt2enseuwsi.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gt2botmmfuu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gt2pleiayec.html

[S46] C++：函数模板
来源：http://dali.ivvv.top/Article/details/gt2xcatnzfy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gt2fykgwfio.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gt2avvtxfed.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dashuyun.cn/Article/details/gt2yhkqpqlp.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2hjztsiqr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gt2ofazseeo.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2lzwbcnbd.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2zwynhqtt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gt2vbswvlpd.html

[S50] C++：格式化数字
来源：http://dali.haohaochexian.top/Article/details/gt2ocgivavj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2onkkduml.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipfprxpl.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gt2cxsbywko.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gt2drypacum.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gt2ganyyhmp.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gt2komrchhl.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gt2uoijuugt.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gt2sletelzp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aizwys.cn/Article/details/gt2xrjilqcz.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcfmfopz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gt2srbdlpbb.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gt2kdztodnq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gt2uuvwegxj.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gt2ehgrzbqo.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gt2iviqwjdx.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gt2lzyjoyfk.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gt2bnlmgcrh.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gt2tadaxtlv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gt2gacgzppv.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gt2argjoirj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2ydabozlk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbowyzio.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2wzgcsbhv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2mwocvrmt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2unynzsvo.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gt2efvdmtsp.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gt2gjxfmgqs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gt2hvungkbf.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gt2iqdqwdfu.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gt2mxijuyui.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejwsdofw.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gt2xxokcggc.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2ussccxyq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gt2toaepphl.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gt2nsbzomle.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gt2axvanchp.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2ekdkvicd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2ouvxnvfz.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gt2ftmezfvc.html

data class User(val name: String, val age: Int)
来源：http://dali.gotoacloud.top/Article/details/gt2hecudgvc.html

[T09] Kotlin：扩展函数
来源：http://dali.ybcxt.top/Article/details/gt2ivpuhzax.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbttrnjn.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gt2zhbrtsmy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gt2olylpubl.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gt2lizocrqf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gt2mwnrogzm.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gt2lymyyuua.html

val (a, b) = Pair(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2goobbyhz.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gt2gakgdgrn.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gt2eaqknzcs.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2owmftgir.html

for (i in 1..10) println(i)
来源：http://dali.yongpay.top/Article/details/gt2whjqybme.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gt2guwdfjag.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gt2zwokmufn.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2nldewmqw.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2jpmikbio.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gt2yybqzbog.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gt2aihousoy.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2qtahmfnr.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gt2hnalolky.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gt2utwfnqhn.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gt2dvabpxhs.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gt2jdjnezbo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gt2vplpwyvt.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gt2wwcxgmjy.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgpbgwgn.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gt2xmqmckkc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.316326.xyz/Article/details/gt2cnjozthj.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrgaptts.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2omqtgtsx.html

[T24] Swift：闭包
来源：http://dali.hysaishi.cn/Article/details/gt2zoagrkxa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2oyyoinwz.html

[T25] Swift：结构体
来源：http://dali.pycfn.com/Article/details/gt2drbxtwii.html

struct P { var x: Int }
来源：http://dali.havefunace.top/Article/details/gt2soudhqtm.html

[T26] Swift：类与重写
来源：http://dali.yangfankeji.com/Article/details/gt2rpjqibqc.html

class A: Base { override func f() {} }
来源：http://dali.jinqigufen.top/Article/details/gt2nrxkekzf.html

[T27] Swift：错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2cxalwdty.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gt2xcrqnzxl.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2eaxdqnrt.html

enum Color { case red, green }
来源：http://dali.xylfe.cn/Article/details/gt2hbpngzde.html

[T29] Swift：guard 提前返回
来源：http://dali.shuidangran.top/Article/details/gt2kunuzyew.html

guard let x = opt else { return }
来源：http://dali.c1oappe.top/Article/details/gt2lipjmvar.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbwbnybe.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gt2pzzipspr.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2ntvbttgl.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2iceumzqu.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gt2eadlknhy.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gt2jqdghjai.html

[T33] Lua：表（数组）
来源：http://dali.jyoumei.cn/Article/details/gt2bnvaahoi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuetiantiany.cn/Article/details/gt2dutbicsf.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gt2bhztgstf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gt2ngswoqqh.html

[T35] Lua：字典表
来源：http://dali.iojbl.cn/Article/details/gt2ngowbxjk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuxming.cn/Article/details/gt2rlvjaums.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gt2hzhkpwxq.html

function add(a, b) return a + b end
来源：http://dali.haohaochexian.top/Article/details/gt2zoybvkfn.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2tbcckkfp.html

"a" .. "b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rocpmnal.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gt2rztmwbtu.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gt2idgcyqtk.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2lesvlgsn.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gt2otrkaufg.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gt2cnuwppju.html

setmetatable({}, { __index = base })
来源：http://dali.hysaishi.cn/Article/details/gt2vfuqihqy.html

[T41] Perl：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2svnndgtt.html

print "Hello\n";
来源：http://dali.zycfv.cn/Article/details/gt2owjyfpnm.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eaqrsuhc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gt2wjgxozck.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2djjwgjej.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gt2isfdhuah.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gryqkhvc.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gt2tututedj.html

[T45] Perl：数组遍历
来源：http://dali.chenzaomai.com/Article/details/gt2sihdvmek.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gt2nicayizj.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gt2hslhfnfj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gt2dsqdtsun.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gt2eealalpi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gt2bszrjinm.html

[T48] Perl：正则替换
来源：http://dali.hywenlv.cn/Article/details/gt2vlzutlcv.html

$s =~ s/old/new/g;
来源：http://dali.nanxinkj.top/Article/details/gt2yiqvujos.html

[T49] Perl：函数
来源：http://dali.guannengcc.top/Article/details/gt2seafqtnx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2ofvcojvu.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2pvfnbpnu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuetiantiany.cn/Article/details/gt2apfgejin.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2kbaajzxh.html

[T51] Scala：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2dzsormsf.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2blpbxeak.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gt2lqrniphc.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gt2bpxffwub.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2mdmgblxn.html

s"值: $b"
来源：http://dali.hammf.cn/Article/details/gt2sxbtogtt.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkojynsr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangdashe.top/Article/details/gt2vbiqsfcm.html

[T55] Scala：集合过滤
来源：http://dali.zycfv.cn/Article/details/gt2lxmhgqvp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yangfankeji.com/Article/details/gt2mkmfjswf.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gt2nbgufgxf.html

case class User(name: String, age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gt2zaxwtftr.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gt2najzhcpd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gt2uibnbpwx.html

[T58] Scala：函数定义
来源：http://dali.shzxlz.cn/Article/details/gt2jvsalcni.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.haohaochexian.top/Article/details/gt2ndtedfef.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gt2yfkplnuf.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gt2pnasnjam.html

[T60] Scala：折叠
来源：http://dali.zdqjudy.top/Article/details/gt2rnmpazbw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xinyue.icu/Article/details/gt2yyekwjkt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2twkalprz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2jwzqlzxz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2wmzlojxk.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gt2jjgabfrz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuanzhike.top/Article/details/gt2jueoxhyg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbgjujgw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2qwxpvlsx.html

[U03] Py：加载 .env 配置
来源：http://dali.pycfn.com/Article/details/gt2fhpfnpnd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.kuanghao11.cn/Article/details/gt2fwtzpuqt.html

[U04] Py：变量调试打印
来源：http://dali.gzhubu.top/Article/details/gt2udqxarqc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gt2ijunpsoe.html

[U05] Py：列表去重且保序
来源：http://dali.cucudq.cn/Article/details/gt2kpjaecvm.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2jjtbfqbv.html

[U06] Py：合并两个字典
来源：http://dali.daria6918.cn/Article/details/gt2lqvmnwfr.html

{**a, **b}
来源：http://dali.dashuyun.cn/Article/details/gt2kglytuuo.html

[U07] Py：反转字典键值
来源：http://dali.316326.xyz/Article/details/gt2tkpfnrrb.html

{v: k for k, v in d.items()}
来源：http://dali.jiagoushi.top/Article/details/gt2jsjslynt.html

[U08] Py：展平二维列表
来源：http://dali.yanxiufei.cn/Article/details/gt2fyrzfure.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gt2lqltwfyk.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gt2otkfogsn.html

max(d, key=d.get)
来源：http://dali.yj20258.top/Article/details/gt2pbyijxom.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gt2aiwbkjff.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gt2yrnagpjh.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gt2fgnjknmk.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifccuohd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsgbvifs.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xeqfhbuq.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gt2lpofkkqu.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gt2ecfgedna.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gt2ryqlrxzb.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gt2qommkmoy.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gt2arfmqtbn.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvxxwfir.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gt2trpdgrbt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gt2bwczrvqh.html

[U17] Py：初始化日志
来源：http://dali.gzhubu.top/Article/details/gt2pczydynf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sysykeji.top/Article/details/gt2dbyqjkcf.html

[U18] Py：预编译正则
来源：http://dali.yj202588.top/Article/details/gt2jiahsven.html

pat = re.compile(r"\d+")
来源：http://dali.cqqwz.cn/Article/details/gt2kibtqvwi.html

[U19] Py：正则替换带回调
来源：http://dali.0kj1m.cn/Article/details/gt2mmchzbul.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ltsxisan.html

[U20] Py：缓存函数结果
来源：http://dali.sysykeji.top/Article/details/gt2vfxdgjhm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gt2iecqcodm.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnqzz.top/Article/details/gt2njofgpnt.html

@contextlib.contextmanager
来源：http://dali.chenlongwang.top/Article/details/gt2cyhaqocr.html

[U22] Py：矩阵转置
来源：http://dali.guannengcc.top/Article/details/gt2kqtsquts.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gt2haxwirfd.html

[U23] Py：分块读取大文件
来源：http://dali.yuxming.cn/Article/details/gt2zvfibtdo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sufxvd.cn/Article/details/gt2kielewem.html

[U24] Py：路径操作
来源：http://dali.aibaodan.cn/Article/details/gt2dlbwzlay.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2pjbmvxgd.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxuanxn.top/Article/details/gt2rgbxgklc.html

csv.DictReader(f)
来源：http://dali.jianghu66.top/Article/details/gt2nwhtlcdy.html

[U26] Py：并发下载
来源：http://dali.gaohongyu789.top/Article/details/gt2muxygtiy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhixingplan.top/Article/details/gt2qtiwphew.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gt2ktfulqum.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ivvv.top/Article/details/gt2wfshfxfg.html

[U28] Py：类型别名
来源：http://dali.gotoacloud.top/Article/details/gt2kmqkgemy.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gt2zhmjfzss.html

[U29] Py：属性校验
来源：http://dali.zhoulong.xyz/Article/details/gt2omzirseo.html

@property 与 @x.setter 配合
来源：http://dali.cdnleiting.top/Article/details/gt2slbuywry.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gt2holrezqm.html

@dataclass(slots=True)
来源：http://dali.jianghu66.top/Article/details/gt2gdkliyhf.html

[U31] Py：单测
来源：http://dali.cucudq.cn/Article/details/gt2bvcphthx.html

python -m pytest -q
来源：http://dali.haohaochexian.top/Article/details/gt2keikkepc.html

[U32] Py：代码格式化
来源：http://dali.shzxlz.cn/Article/details/gt2tzkpglfe.html

ruff format . && ruff check --fix .
来源：http://dali.yj202588.top/Article/details/gt2lfttsmus.html

[U33] Py：打包发布
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dronceum.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dianchejie.cn/Article/details/gt2npyhhhpp.html

[U34] Py：判断编码
来源：http://dali.jlsjyb.cn/Article/details/gt2sstgtmmn.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gt2fcojgies.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gt2hhzhueyn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gt2cdkbfwll.html

[U36] Py：定时任务
来源：http://dali.xylfe.cn/Article/details/gt2xvbvfphe.html

schedule.every(10).minutes.do(job)
来源：http://dali.quarkkingdee.top/Article/details/gt2xbbxkpay.html

[U37] Py：读写 Excel
来源：http://dali.xziqi.cn/Article/details/gt2vuoyfrfb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhixingplan.top/Article/details/gt2jyzqeqby.html

[U38] Py：获取脚本所在目录
来源：http://dali.xylfe.cn/Article/details/gt2jiteoudj.html

Path(__file__).resolve().parent
来源：http://dali.xylfe.cn/Article/details/gt2mwralynb.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuanzx.com/Article/details/gt2uqsccpfe.html

sys.stdout.isatty()
来源：http://dali.ivvv.top/Article/details/gt2qowbqesh.html

[U40] Py：打印到标准错误
来源：http://dali.snrcjt.cn/Article/details/gt2gvcvnhrg.html

print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gt2bdribpfu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj202588.top/Article/details/gt2wlmlfksz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuxming.cn/Article/details/gt2hpionvpn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.bjfxy.top/Article/details/gt2bvkujlqg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tian-w.cn/Article/details/gt2zsndooau.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gt2lbeqcjwf.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fltktord.html

[U44] PHP：开启严格类型
来源：http://dali.aizwys.cn/Article/details/gt2obwzzqpc.html

declare(strict_types=1);
来源：http://dali.zhongyouzk.top/Article/details/gt2fmnndisx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigufen.top/Article/details/gt2xehtavft.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2pvktibpt.html

[U46] PHP：可空类型
来源：http://dali.kuanghao11.cn/Article/details/gt2jlftryhf.html

?string $name = null
来源：http://dali.yvedp.cn/Article/details/gt2vphkkdiq.html


<!-- 参考信息 -->