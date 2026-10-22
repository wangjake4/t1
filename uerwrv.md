代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shangyingyoupin.top/Article/details/gtxbewrjqc.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtzefzbbjy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gtevrfmtvd.html

[S24] C：获取本地时间
来源：http://dali.nanxuanxn.top/Article/details/gtnbbcqibp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gtpxivzgmg.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gtcremvftx.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gtlcrqrhii.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucqezvwg.html

memset(a, 0, sizeof a);
来源：http://dali.yanxiufei.cn/Article/details/gttxinpxyw.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gtpjjllonz.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtnobxwnjn.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gtoysgkzqr.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gtbvwvnwpp.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gtrhltdtdt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gthviisyjt.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gtdyytxwve.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gtehnmvlwx.html

#define X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfvjkbhm.html

#endif
来源：http://dali.aibaodan.cn/Article/details/gtppmanzod.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtnafxbtlq.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrvdorjg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.c1oappe.top/Article/details/gtfsyndcyj.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtivbxqjab.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gtgoeytrgc.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduypedtk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gtwtzjzxxc.html

[S34] C++：遍历 vector
来源：http://dali.redwolf501.top/Article/details/gtzmkjzsty.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gtxkohszin.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gthwisqgpo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtqspqhpgf.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtnrnblbrw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtocmseroc.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gtiucluwjr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gtrwipudrx.html

[S38] C++：排序
来源：http://dali.iojbl.cn/Article/details/gtxuapewid.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gtlbcbvgcq.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtpsctsbvl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtseniqrjn.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gtvjmchawl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiocvncq.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gtaspsybeu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gtgzsrmyve.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gtneidvapd.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gtuafmypbo.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gtkecdzamw.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtghvizyfe.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtqlojcstq.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gtxnfmqqtl.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gtyqpdefst.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gtamtitdlk.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gtrjfqwtsp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gtiyrkulih.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gtcazpednr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtedtpamkk.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtzjyyobcc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.meibo888.top/Article/details/gtghsafnuq.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtlqpxafef.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtermxpnhd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtnaezieav.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gtfvqwmmbv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtqgwkipza.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gtuftpydxs.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtrcxynrcp.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gttngmpijk.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtatdkfjze.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtlvpgedcj.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtajnkifym.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gtqtmsnans.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gtlbfynoob.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtxuijnusf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gtkeuaymch.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gtfoxuowrz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbesocxed.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtommmetyt.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gtkelpmkuq.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gtqdwklhqm.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gteonjbthg.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtqmunilzx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoenwsnc.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gttgxenmcz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtcmmnkogv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjkmthwfs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtidwccagr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdxfozrn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtzfearymr.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcipfijkn.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gtplnwropd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gtytxtqjby.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gtaibroisq.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtrbzydtsy.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gtvnyueelc.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gtciczwbis.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gtjgjhvgod.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gtmxawnzkm.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtutvmhbzh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuixhhqdk.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtrwoqfxtf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtfyhhggrn.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtvswopcmd.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gttudvwfcq.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gtvnebnidb.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gtllluwahz.html

[T10] Kotlin：默认参数
来源：http://dali.sweek.top/Article/details/gtgcdjzqtb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gtgxqhndbd.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtalkvplik.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gthnvtngdy.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gtmivveoce.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtjspkxysn.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gtzsqsrnyv.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgjcijam.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gtlplrpnto.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtzegkjzxv.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtyinsalan.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gtcjoonbnu.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gtfqqyyiwq.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtdbkgipdc.html

[T17] Swift：变量与常量
来源：http://dali.xinyue.icu/Article/details/gtsovlijaw.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gtlzwcltzo.html

[T18] Swift：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtkaenfpim.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gtcfconpdh.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gtkvruxhcs.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gtuefprlct.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gthcsflyoj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtyydwihem.html

[T21] Swift：遍历
来源：http://dali.zhongyouzk.top/Article/details/gtwliznoio.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gtubdauman.html

[T22] Swift：字典
来源：http://dali.zhiwuduotai.top/Article/details/gturhdrkbm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tanke756.top/Article/details/gtpnvqtkkp.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gtvmzystqb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gtnsmlahqz.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuowoflpa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtfkluhvmm.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gtbcupcbjo.html

struct P { var x: Int }
来源：http://dali.shzxlz.cn/Article/details/gthixrgybg.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gtueqexxng.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gttqavfmtz.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gtpwjkrpla.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzutmvdr.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gtkgusbcmd.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gtlyqsjhmv.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtkyrlodjn.html

guard let x = opt else { return }
来源：http://dali.nwbrower.top/Article/details/gtzheyftbb.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtrqqqikqb.html

protocol Shape { func area() -> Double }
来源：http://dali.yangfankeji.com/Article/details/gtbrsannpx.html

[T31] Lua：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtrqkazxwl.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtirfblmfr.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gtgeujeepx.html

local a = 1
来源：http://dali.yuanzhike.top/Article/details/gtwbiytqou.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gtiqlhreop.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gtxdtddywz.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbdaqrjs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtpnnowatb.html

[T35] Lua：字典表
来源：http://dali.sxryk.cn/Article/details/gtsjonswel.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtzvatusuu.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtovrimcwk.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtkblxdjej.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gttnwyjxan.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gtchvebmrs.html

[T38] Lua：条件
来源：http://dali.nwbrower.top/Article/details/gtpztrougz.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtjopbamln.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gtmyqvlokg.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gtodykygqk.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxlxirsx.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gtyudrhxcg.html

[T41] Perl：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtoehjsnky.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gtubguxdnz.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gtvgweyloq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuanzhike.top/Article/details/gtlwdsllao.html

[T43] Perl：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtwpiqyxfx.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gtowvddauf.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnhijfwe.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtmjyvkpdl.html

[T45] Perl：数组遍历
来源：http://dali.yuanzhike.top/Article/details/gtugiuggod.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtabsmehzi.html

[T46] Perl：哈希操作
来源：http://dali.andypj.xyz/Article/details/gtvlvfkvfa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gthzldoraw.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gtdzscwkmh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwkhpklpy.html

[T48] Perl：正则替换
来源：http://dali.redwolf501.top/Article/details/gtvkurvqbg.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gteqxvdnfp.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtstjmedvy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtyyucbbft.html

[T50] Perl：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtbotewbyp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jianghu66.top/Article/details/gtpcsxydaf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtftnwmvzm.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gtkzpxfohu.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtttbyjppd.html

[T52] Scala：变量
来源：http://dali.yuanzhike.top/Article/details/gtubgsnprt.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gthqforxwg.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtdmumylni.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtpickkupv.html

[T54] Scala：集合映射
来源：http://dali.sxryk.cn/Article/details/gtwauezcgo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sufxvd.cn/Article/details/gtebhycxwe.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtqcujvtkm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gtwxgogars.html

[T56] Scala：样例类
来源：http://dali.feifeiyinyue.top/Article/details/gtzcvzhqyk.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqyhdatb.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtutiofpoy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbmmbdzx.html

[T58] Scala：函数定义
来源：http://dali.gaohongyu789.top/Article/details/gtsgxhowdz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gtatoodcgg.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gtkvnedqza.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtkbxwhwsr.html

[T60] Scala：折叠
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifdbdoux.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtwrdqricr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvqzokjn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtblwisabc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrowvtsgc.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gtmuihimzb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkcpryrn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gtjikvobdh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gtsnevtbps.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gtrydbgmnb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gtggivlsde.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gthbarhlad.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.kuanghao11.cn/Article/details/gtaqojdwhe.html

[U05] Py：列表去重且保序
来源：http://dali.yanxiufei.cn/Article/details/gtymhcfsch.html

list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtsohcbjgp.html

[U06] Py：合并两个字典
来源：http://dali.dianchejie.cn/Article/details/gtkhgwisrl.html

{**a, **b}
来源：http://dali.hammf.cn/Article/details/gtkkntnizx.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gtqjcenqwc.html

{v: k for k, v in d.items()}
来源：http://dali.gaohongyu789.top/Article/details/gtiqndkiyo.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gtdpgvfzgi.html

[y for x in nested for y in x]
来源：http://dali.jyoumei.cn/Article/details/gtaojfoamc.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gtocsjobjm.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtqvyxqaov.html

[U10] Py：按值排序字典
来源：http://dali.fzhhl.top/Article/details/gtjmohyash.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aizwys.cn/Article/details/gtbmdpktzx.html

[U11] Py：生成器表达式
来源：http://dali.svipenyu.cn/Article/details/gtmcwrcmhw.html

(x * 2 for x in arr)
来源：http://dali.tian-w.cn/Article/details/gtnpjrmejt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gtqfumqbzd.html

Counter(arr).most_common(3)
来源：http://dali.jinqigfzy.top/Article/details/gtslpeaqaj.html

[U13] Py：固定长度队列
来源：http://dali.jqgfzy.top/Article/details/gtukaslbgd.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gtcfddaymd.html

[U14] Py：分组收集到列表
来源：http://dali.xziqi.cn/Article/details/gtbjetphcc.html

defaultdict(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhdwgfgr.html

[U15] Py：高精度计时
来源：http://dali.yvedp.cn/Article/details/gtorexytzx.html

t = time.perf_counter()
来源：http://dali.9152youxi.cn/Article/details/gtpyjvchlv.html

[U16] Py：命令行参数解析
来源：http://dali.yanxiufei.cn/Article/details/gtymbpisnt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shzxlz.cn/Article/details/gtwxgeulnb.html

[U17] Py：初始化日志
来源：http://dali.andypj.xyz/Article/details/gtkxawczlq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dianchejie.cn/Article/details/gtawkrsgev.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gtovvlsgov.html

pat = re.compile(r"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcamgfwhu.html

[U19] Py：正则替换带回调
来源：http://dali.aizwys.cn/Article/details/gtiomnhere.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gzhubu.top/Article/details/gtybrzmlgy.html

[U20] Py：缓存函数结果
来源：http://dali.jyoumei.cn/Article/details/gtlmuerpfa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnxiangtu.top/Article/details/gttfucvlds.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxjytxgj.html

@contextlib.contextmanager
来源：http://dali.guowangkeji.top/Article/details/gtdjkbenln.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gteavabuog.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gtxtvxzhwd.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gtstukrnic.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jqgfzy.top/Article/details/gtdnsrjpuy.html

[U24] Py：路径操作
来源：http://dali.quarkkingdee.top/Article/details/gtxzpucouj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gthyzhcflq.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvnsnvca.html

csv.DictReader(f)
来源：http://dali.yuxming.cn/Article/details/gtnhkpdsyt.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gtmzuarizp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenjidiqi.icu/Article/details/gtaxsaexmi.html

[U27] Py：异步 HTTP
来源：http://dali.zycfv.cn/Article/details/gtctmevofw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tian-w.cn/Article/details/gtagszyofm.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gtodqvzcwo.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gtnprldjwn.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gtfgjmovtr.html

@property 与 @x.setter 配合
来源：http://dali.birdmap.top/Article/details/gtrqvzofsv.html

[U30] Py：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtloyagjey.html

@dataclass(slots=True)
来源：http://dali.snrcjt.cn/Article/details/gteowwtkiv.html

[U31] Py：单测
来源：http://dali.vqdsnc.cn/Article/details/gtfitjdtrs.html

python -m pytest -q
来源：http://dali.ivvv.top/Article/details/gthnjwqfto.html

[U32] Py：代码格式化
来源：http://dali.jiagoushi.top/Article/details/gtcbynzshl.html

ruff format . && ruff check --fix .
来源：http://dali.cashguo.top/Article/details/gttqmyqart.html

[U33] Py：打包发布
来源：http://dali.zhoulong.xyz/Article/details/gtigxdkbhr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shzxlz.cn/Article/details/gtoacjlwmx.html

[U34] Py：判断编码
来源：http://dali.jlsjyb.cn/Article/details/gtmmnnhhfb.html

chardet.detect(raw)
来源：http://dali.gaohongyu789.top/Article/details/gthipltdoq.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gtvqgmiamp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaftgorl.html

[U36] Py：定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxykuujgv.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgfzy.top/Article/details/gtvhoeiyxy.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gtxioiuikd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnqzz.top/Article/details/gtwqykkpqs.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuetiantiany.cn/Article/details/gtpvcreylw.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gtlokhxvfw.html

[U39] Py：判断是否在交互环境
来源：http://dali.yonumen.top/Article/details/gtyvxoadil.html

sys.stdout.isatty()
来源：http://dali.haohaochexian.top/Article/details/gtilzeuqkn.html

[U40] Py：打印到标准错误
来源：http://dali.zhixingplan.top/Article/details/gtbyakdbmw.html

print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtdmgbbjtc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.bjfxy.top/Article/details/gtlqpyydnf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zdqjudy.top/Article/details/gtqugpgrmb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigufen.top/Article/details/gtmdzrxeir.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pengpengdd.cyou/Article/details/gtkvjnfnat.html

[U43] PHP：声明命名空间
来源：http://dali.hfpthk.cn/Article/details/gtptcglkpg.html

namespace App\Http;
来源：http://dali.guannengcc.top/Article/details/gtpxhpcdxl.html

[U44] PHP：开启严格类型
来源：http://dali.hnqzz.top/Article/details/gtyczbmfiq.html

declare(strict_types=1);
来源：http://dali.gzhubu.top/Article/details/gtuaguoyrk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.9152youxi.cn/Article/details/gtaixhccjl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtzgsiqpxj.html

[U46] PHP：可空类型
来源：http://dali.fzhhl.top/Article/details/gtaxpoenje.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gtruvssfjw.html


<!-- 参考信息 -->