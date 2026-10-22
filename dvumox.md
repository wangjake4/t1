代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2itwpuxfu.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gt2nyxumplx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gt2fezxhlez.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gt2clswqymm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gt2xfppcjcg.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gt2olbudsuj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwdcgtqp.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpimjwww.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gt2iyefsuht.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2qmhetora.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gt2cnoybdlb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfxfwod.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gt2fticmmka.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ionxhuhg.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2bmrohlvt.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gt2omdetxyr.html

static int counter = 0;
来源：http://dali.gotoacloud.top/Article/details/gt2qphykjsv.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gt2bhujvpyq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gt2czolmxsg.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gt2ddowlxar.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2gckwhqao.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gt2osnaaylf.html

#endif
来源：http://dali.0kj1m.cn/Article/details/gt2gkzthsyv.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2qscpantj.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lusswriz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gt2zdzoqtpt.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gt2nmepgzgd.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gt2zibfwsjs.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gt2vwletewg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gt2vxsxdxod.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gt2yoinxznt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gt2laubnkvo.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gt2asizsuxr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2ansidmlu.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gt2rcowxawg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdkkqjxo.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gt2kxpjvwhu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gt2ghtrfyow.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gt2fmcgwmdm.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gt2kuascqbj.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gt2ajeisctl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gt2mqvpatxu.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gt2czqpvktv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gt2maeafbff.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gt2ubksisbk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gt2wwdexiww.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gt2uxhmidvu.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gt2agdngndr.html

[S43] C++：智能指针
来源：http://dali.dashuyun.cn/Article/details/gt2twdwatim.html

auto p = std::make_unique<int>(5);
来源：http://dali.havefunace.top/Article/details/gt2oftbcylb.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gt2zjwwythp.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eulnbwgy.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gt2gwtwysrd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gt2yxtsbcwa.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gt2bjfpnisv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gt2qqgwuqfu.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gt2icpmjmwo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gt2kqxppdta.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlfmofqq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gt2euvprexh.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gt2qeyagjof.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2mwlovuoj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gt2efnqmxbc.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gt2tsrnkqel.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2ghjjyrno.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2hcghavvd.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gt2nvvnxgjo.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfnkmnlz.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gt2atqazbeg.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gt2ivjkkzju.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gt2yikcofdw.html

[S54] C++：异常处理
来源：http://dali.zhengqikj.top/Article/details/gt2clcgblas.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gt2fvpltnmo.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gt2amibxruf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sysykeji.top/Article/details/gt2dbwniwsp.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gt2kfydadte.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gt2bdmbqkzb.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhvabzcv.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcjuxvwc.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gt2cmtdnbye.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gt2xhqjqnaq.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gt2mxswnume.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjfzcwwr.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gt2onwuwfou.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2ptujyssr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2nvzncdhl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gt2uifmdoql.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2nbnznuai.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2cjbqyyeo.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2yzjkuyay.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gt2uqvtjexr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gt2clkfdxzm.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gt2xjptykrp.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gt2cmxybess.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gt2koiuoodb.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gt2bkkvzrqo.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gt2ynbxspkz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gt2iekcdobe.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gt2atfwsxru.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2ixxctdaf.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2hbaojiuz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gt2fghzgdtu.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gt2duzktyzo.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gt2ktocczuo.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gt2ohensbix.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gt2qbovmbdq.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gt2xqqogvly.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icaurqxl.html

[T11] Kotlin：协程
来源：http://dali.shuidangran.top/Article/details/gt2ezfltyza.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gt2fdkdbdyc.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gt2qcxglzuq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zelxyygi.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzqfmlld.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gt2asctpngi.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gt2uwcnhykv.html

for (i in 1..10) println(i)
来源：http://dali.tanke756.top/Article/details/gt2tjyipoam.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gt2jkhmyqbb.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfwmkyus.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2dzrlocec.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2vgeqglef.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gt2axaairgp.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epkgxcvo.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gt2crpshqml.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gt2uqofnbhp.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gt2qhzftroi.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gt2eihrqhfk.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gt2uclmyqzv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gt2dhrmqozn.html

[T21] Swift：遍历
来源：http://dali.aibaodan.cn/Article/details/gt2eqazmdny.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gt2mhaqimkl.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gt2deplijad.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2guevxmlb.html

[T23] Swift：函数
来源：http://dali.bjfxy.top/Article/details/gt2deyqcvvf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2rtudpkdi.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gt2duhnqgac.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2jlpbgltl.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gt2nqruqqvs.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gt2frjofjip.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csyssvdu.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gt2hnfgoclj.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2seedulfl.html

do { try f() } catch { print(error) }
来源：http://dali.zhixingplan.top/Article/details/gt2ksgfndgs.html

[T28] Swift：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2xftfswkc.html

enum Color { case red, green }
来源：http://dali.zhixingplan.top/Article/details/gt2qfjkbwvy.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gt2nogrlvbf.html

guard let x = opt else { return }
来源：http://dali.zycfv.cn/Article/details/gt2adyqkyid.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gt2qrtcwgqm.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gt2zqegcaju.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2jihrttgd.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2gzfgljax.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gt2pyiiycmw.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gt2eudkharw.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gt2kbfppiev.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gt2hrcyxaxg.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gt2eahuknel.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzbikfoe.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gt2xknhdpwl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gt2ohdealyd.html

[T36] Lua：函数
来源：http://dali.hywenlv.cn/Article/details/gt2qyrsfpfv.html

function add(a, b) return a + b end
来源：http://dali.mhx1999.top/Article/details/gt2icdsqsvo.html

[T37] Lua：字符串拼接
来源：http://dali.wangdashe.top/Article/details/gt2ujsvisgq.html

"a" .. "b"
来源：http://dali.jinqigfzy.top/Article/details/gt2pdymaoel.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gt2rkofbnjn.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gt2vszhntlo.html

[T39] Lua：模式匹配
来源：http://dali.aizwys.cn/Article/details/gt2pwyrxgvw.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gt2hjxcjkjy.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gt2sswcozox.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gt2paaboyuw.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yeaiqndi.html

print "Hello\n";
来源：http://dali.cqqwz.cn/Article/details/gt2irebfzkd.html

[T42] Perl：变量类型
来源：http://dali.xziqi.cn/Article/details/gt2mmtkedzz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gt2mnoeghnv.html

[T43] Perl：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2lwwnfwvl.html

"值: $a"
来源：http://dali.yangfankeji.com/Article/details/gt2diwpipdg.html

[T44] Perl：条件
来源：http://dali.shuidangran.top/Article/details/gt2wnlupkst.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gt2xnfxdeoy.html

[T45] Perl：数组遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2ipxdahlm.html

for my $x (@arr) { print $x; }
来源：http://dali.nwbrower.top/Article/details/gt2ffxpxiwr.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gt2surbissw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idlszjjl.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gt2cmkhuvmg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhhaxoa.html

[T48] Perl：正则替换
来源：http://dali.jiagoushi.top/Article/details/gt2aijrornb.html

$s =~ s/old/new/g;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpfajnvl.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gt2iyrwhlbq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jlxjwtaj.html

[T50] Perl：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2hvvmyoxf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdyerqhp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jianghu66.top/Article/details/gt2mzaqaygj.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcqsdkrr.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gt2mcgjjktz.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gt2mfecqkvg.html

val a = 1;  var b = 2
来源：http://dali.yj20258.top/Article/details/gt2rpjhbcrv.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2kaiwstrk.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gt2inhhsztx.html

[T54] Scala：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gt2lanllpsg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2reokfzuf.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clhkygms.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gt2pmazdhxi.html

[T56] Scala：样例类
来源：http://dali.hongshengwenyu.top/Article/details/gt2xowlvsch.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gt2bgqvluqb.html

[T57] Scala：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gt2vwuicfpr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gt2zbgxjmbo.html

[T58] Scala：函数定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdhzujab.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjxvbchl.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gt2ucxhonxg.html

for (i <- 1 to 10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gt2aayqecim.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gt2pjminuhz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gt2fxozonii.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2qstfjmwa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdhmiusc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2xfvudbds.html

[U01] Py：创建虚拟环境
来源：http://dali.sweek.top/Article/details/gt2xnajdkjb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gt2gebjhesk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.snrcjt.cn/Article/details/gt2xvbtzcap.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gt2kqbmqpyr.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gt2aycqpkqi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cucudq.cn/Article/details/gt2odutrjxk.html

[U04] Py：变量调试打印
来源：http://dali.yonumen.top/Article/details/gt2uvzlvdpw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydzvebkq.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gt2nypkzcyi.html

list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gt2qzwvscfg.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gt2bmursybp.html

{**a, **b}
来源：http://dali.hammf.cn/Article/details/gt2eemiascn.html

[U07] Py：反转字典键值
来源：http://dali.cdnleiting.top/Article/details/gt2fqkaklln.html

{v: k for k, v in d.items()}
来源：http://dali.jlsjyb.cn/Article/details/gt2vfwidreu.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gt2xhoyconm.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gt2tldstbaw.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gt2bhtopqjo.html

max(d, key=d.get)
来源：http://dali.c1oappe.top/Article/details/gt2ygkztfko.html

[U10] Py：按值排序字典
来源：http://dali.svipenyu.cn/Article/details/gt2cfdtwmxs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuanzhike.top/Article/details/gt2uqixxtkg.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2jvjupgjs.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gt2qopgywod.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gt2ztdwtrns.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gt2vkzztfvo.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gt2vmsbcdoe.html

deque(maxlen=10)
来源：http://dali.zhongyouzk.top/Article/details/gt2ryvuccyh.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clhyhiog.html

defaultdict(list)
来源：http://dali.xylfe.cn/Article/details/gt2sldxxfeo.html

[U15] Py：高精度计时
来源：http://dali.guowangkeji.top/Article/details/gt2faiqibfi.html

t = time.perf_counter()
来源：http://dali.zhengqikj.top/Article/details/gt2epacpflu.html

[U16] Py：命令行参数解析
来源：http://dali.zycfv.cn/Article/details/gt2lnshhvyp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhoulong.xyz/Article/details/gt2ltrafsqg.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gt2wlgmmkdq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gt2unavmmes.html

[U18] Py：预编译正则
来源：http://dali.zhengqikj.top/Article/details/gt2thssmhao.html

pat = re.compile(r"\d+")
来源：http://dali.yvedp.cn/Article/details/gt2bwzoejrj.html

[U19] Py：正则替换带回调
来源：http://dali.xuetiantiany.cn/Article/details/gt2abknwcyw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jiagoushi.top/Article/details/gt2iijjedhl.html

[U20] Py：缓存函数结果
来源：http://dali.hnxiangtu.top/Article/details/gt2vqtozpof.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cheryme.top/Article/details/gt2hkhevgho.html

[U21] Py：自定义上下文管理器
来源：http://dali.smart0.xyz/Article/details/gt2rpouqqvy.html

@contextlib.contextmanager
来源：http://dali.ivvv.top/Article/details/gt2gxmzhzsv.html

[U22] Py：矩阵转置
来源：http://dali.jinqigfzy.top/Article/details/gt2qbbhthcr.html

list(zip(*m))
来源：http://dali.yj202588.top/Article/details/gt2pkxhkdbp.html

[U23] Py：分块读取大文件
来源：http://dali.9152youxi.cn/Article/details/gt2slbsgpws.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yvedp.cn/Article/details/gt2xacczuzr.html

[U24] Py：路径操作
来源：http://dali.andypj.xyz/Article/details/gt2uquxtolb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyomkbfy.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vchelful.html

csv.DictReader(f)
来源：http://dali.kuanghao11.cn/Article/details/gt2guxgyxam.html

[U26] Py：并发下载
来源：http://dali.svipenyu.cn/Article/details/gt2czopctow.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gt2pcgtyjxu.html

[U27] Py：异步 HTTP
来源：http://dali.shzxlz.cn/Article/details/gt2ablyufrw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guowangkeji.top/Article/details/gt2hzosgulx.html

[U28] Py：类型别名
来源：http://dali.pycfn.com/Article/details/gt2oiurrnvn.html

UserId = int
来源：http://dali.wangdashe.top/Article/details/gt2woinnvbw.html

[U29] Py：属性校验
来源：http://dali.redwolf501.top/Article/details/gt2bnclsphd.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gt2ckmefxax.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2cijykozb.html

@dataclass(slots=True)
来源：http://dali.tianlin.xyz/Article/details/gt2hieuyzpn.html

[U31] Py：单测
来源：http://dali.iojbl.cn/Article/details/gt2rfrwgqaj.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gt2ixousnge.html

[U32] Py：代码格式化
来源：http://dali.daria6918.cn/Article/details/gt2tqhvmglz.html

ruff format . && ruff check --fix .
来源：http://dali.ivvv.top/Article/details/gt2qgrdiuzx.html

[U33] Py：打包发布
来源：http://dali.316326.xyz/Article/details/gt2veqvuryo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gt2fytmemja.html

[U34] Py：判断编码
来源：http://dali.zhixingplan.top/Article/details/gt2xmkioqhr.html

chardet.detect(raw)
来源：http://dali.yonumen.top/Article/details/gt2qrmuwtwd.html

[U35] Py：发送邮件
来源：http://dali.jlsjyb.cn/Article/details/gt2vznxvcdg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xinyue.icu/Article/details/gt2ttijqfbx.html

[U36] Py：定时任务
来源：http://dali.wangdashe.top/Article/details/gt2dmccantv.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gt2xiaczyqn.html

[U37] Py：读写 Excel
来源：http://dali.yangfankeji.com/Article/details/gt2zjqsoyet.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxqxcedp.html

[U38] Py：获取脚本所在目录
来源：http://dali.xinyue.icu/Article/details/gt2xvhbwfua.html

Path(__file__).resolve().parent
来源：http://dali.ehwqpu.com/Article/details/gt2rsemzrzy.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gt2hnofpzbb.html

sys.stdout.isatty()
来源：http://dali.hammf.cn/Article/details/gt2cxlfhkja.html

[U40] Py：打印到标准错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyjdpgos.html

print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2yrmjapnb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sxryk.cn/Article/details/gt2erngnbqn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.meibo888.top/Article/details/gt2wdvyoifu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuetiantiany.cn/Article/details/gt2zliaciex.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tian-w.cn/Article/details/gt2yvoigvpg.html

[U43] PHP：声明命名空间
来源：http://dali.yangfankeji.com/Article/details/gt2bfpreacu.html

namespace App\Http;
来源：http://dali.dashuyun.cn/Article/details/gt2zabkkjey.html

[U44] PHP：开启严格类型
来源：http://dali.havefunace.top/Article/details/gt2oncdglwa.html

declare(strict_types=1);
来源：http://dali.vqdsnc.cn/Article/details/gt2elqzpdds.html


<!-- 参考信息 -->