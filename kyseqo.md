代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gt2bjektxaw.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gt2slmwdhfm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbkiuxiq.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gt2dtpbqusj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gt2fkfjqfqc.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2rumhrovn.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brklirfh.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gt2pcvxetkq.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gt2fluzkidb.html

[S27] C：定义常量
来源：http://dali.nanxuanxn.top/Article/details/gt2juaxvjwe.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2vovguudc.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gt2louqdhwy.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gt2rkaxodpp.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gt2bsgotwrs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gt2mlzfrphd.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gt2cjyhmdux.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gt2qfghivee.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gt2ovphleem.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cixverye.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2lawklbsw.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gt2uqhwzgvc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.c1oappe.top/Article/details/gt2bqgtsvnh.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gt2uskwbkzk.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gt2jrrhthaz.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gt2qmtrzsqp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2jcbmjaso.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gt2rudashtw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zycfv.cn/Article/details/gt2bwhrlvnq.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gt2rknwrmey.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svryechz.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gaojpxds.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2yrzetcgx.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmetxpsk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gt2iierogtf.html

[S38] C++：排序
来源：http://dali.tian-w.cn/Article/details/gt2bjnpmzni.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqrwfpxt.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gt2tywbbotm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gt2hkotjvok.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gt2nluaoqks.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gt2orsqckfa.html

[S41] C++：类与构造函数
来源：http://dali.daxiang520.top/Article/details/gt2sehlwqlz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gt2vwxxverr.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gt2lbmvpebh.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gt2keoenzqd.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gt2cmftrkok.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gt2yysypmjt.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gt2dswwebaa.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gt2jmkmpqqc.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gt2kdhlkqze.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gt2eoxmosyl.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfgssimz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258.top/Article/details/gt2gkoevrpx.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gt2zbcacfpn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gt2uxddftbl.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhnyxsza.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gt2jmjvwvda.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2myhwwvau.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2yndxtgck.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gt2sxrcikby.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gt2moxdtjoz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2ugbvmcml.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gt2wzmwgffo.html

static_cast<double>(a) / b
来源：http://dali.daria6918.cn/Article/details/gt2jweoiitz.html

[S52] C++：const 与 noexcept
来源：http://dali.yj202588.top/Article/details/gt2ftfozrwf.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ajbixmwk.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gt2cubvanpn.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gt2woftvvyx.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gt2ghzhvpxa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gt2jnpixlxz.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gt2wzivbkbr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gt2sztgllel.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gt2hvnpixzn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gt2usqipuxn.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gt2ufsxqmos.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2qjhmgkcn.html

[S58] C++：命名空间
来源：http://dali.ivvv.top/Article/details/gt2uuikstrb.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gt2pyresxmw.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gt2tencpqcd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gt2ykaodnaw.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gt2dfigialw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gt2gwusgwfx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2uaovttqi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gt2dmporsdk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikorlucg.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gt2ajfinhbu.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhemmwcd.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gt2vhtktdog.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gt2wefgyvrf.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gt2xjsvfgrh.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gt2kaiwyrzl.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odfyoygv.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gt2kaltimng.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2scdwjsnm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gt2qexfkesi.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gt2mipsubxi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wddfvcix.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gt2awqewlzo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gt2oprjbhah.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gt2zakhyizy.html

data class User(val name: String, val age: Int)
来源：http://dali.jyoumei.cn/Article/details/gt2gjkrytkm.html

[T09] Kotlin：扩展函数
来源：http://dali.guowangkeji.top/Article/details/gt2acrmgntn.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gt2axnhxycx.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2klgnfepf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.haohaochexian.top/Article/details/gt2agrktktl.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gt2ckujllzp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gt2vkkfkdgb.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gt2fxuxcbuc.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dafknnzo.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gt2siylijtw.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gt2vjzovasr.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gt2tgwlkbdn.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gt2ixgktqlb.html

[T15] Kotlin：接口
来源：http://dali.hysaishi.cn/Article/details/gt2vuchukhs.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gt2xwzxkofb.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2hpnynffp.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbxmrmcv.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gt2dvfexbfg.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2eoxznvky.html

[T18] Swift：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gt2sinmiyvy.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gt2mbqgozkp.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gt2jpahdecp.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gt2ervtwvzw.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gt2thkwtjtv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gt2fgdnfgbk.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gt2ohufckoj.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydumiqjh.html

[T22] Swift：字典
来源：http://dali.cheryme.top/Article/details/gt2yssgkape.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guowangkeji.top/Article/details/gt2rhtrqvdq.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gt2omwfcffj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2crjmbynz.html

[T24] Swift：闭包
来源：http://dali.hongshengwenyu.top/Article/details/gt2clrefkhv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2srvkoxmp.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gt2rlcnzsdn.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gt2kipcrkgz.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gt2ctwscxde.html

class A: Base { override func f() {} }
来源：http://dali.xylfe.cn/Article/details/gt2ssbdtxah.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gt2mfkiudxw.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gt2dnjjnpoe.html

[T28] Swift：枚举
来源：http://dali.aizwys.cn/Article/details/gt2gygoyudu.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gt2fqlszurv.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2qemdxkem.html

guard let x = opt else { return }
来源：http://dali.9152youxi.cn/Article/details/gt2asapqdhb.html

[T30] Swift：协议
来源：http://dali.tanke756.top/Article/details/gt2zylmmdek.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gt2umebvnho.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygxnxblx.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2xbjzzdaf.html

[T32] Lua：局部变量
来源：http://dali.hnxiangtu.top/Article/details/gt2dgzwqqoo.html

local a = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfansqrj.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gt2tzfpsnxj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gt2okkpprex.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gt2xueywlyw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gt2cbeqfqnx.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gt2drofsdjv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2qhdcapdl.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gt2eaqhrzua.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gt2qcawgqkr.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2frghrcbe.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gt2rzivjnkb.html

[T38] Lua：条件
来源：http://dali.shuidangran.top/Article/details/gt2mncfouch.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gt2pqqqowch.html

[T39] Lua：模式匹配
来源：http://dali.aizwys.cn/Article/details/gt2zacmnmqe.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gt2dxfybyhh.html

[T40] Lua：元表
来源：http://dali.hfpthk.cn/Article/details/gt2neuiryyw.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gt2qqtwqjqu.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2ksglrdbz.html

print "Hello\n";
来源：http://dali.smart0.xyz/Article/details/gt2oouzfgfq.html

[T42] Perl：变量类型
来源：http://dali.jianghu66.top/Article/details/gt2vfzrqacv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gt2jdpgfeht.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2qnxnsrom.html

"值: $a"
来源：http://dali.birdmap.top/Article/details/gt2wsalojnc.html

[T44] Perl：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxdtgijo.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjiasrgx.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gt2wbznehgu.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gt2esrsslwu.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gt2vnjrydhu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fphhdwrx.html

[T47] Perl：正则捕获
来源：http://dali.9152youxi.cn/Article/details/gt2ttspjdlp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvlfgewu.html

[T48] Perl：正则替换
来源：http://dali.cashguo.top/Article/details/gt2phlycmhe.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gscvfoeo.html

[T49] Perl：函数
来源：http://dali.jinqigfzy.top/Article/details/gt2kqaylgos.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxzegyww.html

[T50] Perl：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2fbelhbed.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sufxvd.cn/Article/details/gt2jtbauwfs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guannengcc.top/Article/details/gt2nuqujbef.html

[T51] Scala：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2yyocfbrk.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2djdbfgrx.html

[T52] Scala：变量
来源：http://dali.nwbrower.top/Article/details/gt2cdufzoue.html

val a = 1;  var b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2prjxnjxt.html

[T53] Scala：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2regroipf.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gt2vglhiutq.html

[T54] Scala：集合映射
来源：http://dali.gotoacloud.top/Article/details/gt2stjdybbu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gt2icsntznx.html

[T55] Scala：集合过滤
来源：http://dali.c1oappe.top/Article/details/gt2qpoojkee.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gt2erhymido.html

[T56] Scala：样例类
来源：http://dali.zhixingplan.top/Article/details/gt2zcrcodqs.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2jaspxzcz.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prvnygpj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gt2jvzyjvru.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gt2nbhvrwya.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gt2xfjiccti.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gt2sshfettm.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gt2wfbiepdp.html

[T60] Scala：折叠
来源：http://dali.haohaochexian.top/Article/details/gt2vkykjmwi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ivvv.top/Article/details/gt2usubfytq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2kewhwcxh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gt2otmewslu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2qyobutqh.html

[U01] Py：创建虚拟环境
来源：http://dali.yueranfly.top/Article/details/gt2cblmpcnn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenjidiqi.icu/Article/details/gt2pspelmew.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ivvv.top/Article/details/gt2cmbfkomc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unvpdhgu.html

[U03] Py：加载 .env 配置
来源：http://dali.tanke756.top/Article/details/gt2syxhdaah.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sufxvd.cn/Article/details/gt2yfnfrdyr.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gt2ljtlndfo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gt2xloiqkcc.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gt2zyaoiwkr.html

list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gt2xihyhmpy.html

[U06] Py：合并两个字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhbimhef.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gt2gjhiiddp.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gt2nvhiktes.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gt2jgmwvmvb.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gt2igdelwbd.html

[y for x in nested for y in x]
来源：http://dali.yvedp.cn/Article/details/gt2bgtkxmvb.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gt2zszazpyi.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gt2whsbwrsm.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gt2uhcoptrc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zycfv.cn/Article/details/gt2veyrnucf.html

[U11] Py：生成器表达式
来源：http://dali.xinyue.icu/Article/details/gt2eebdortt.html

(x * 2 for x in arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2fpjdqiob.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gt2lfsawyiq.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gt2nfwqtluk.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gt2xmpskymk.html

deque(maxlen=10)
来源：http://dali.yuanzhike.top/Article/details/gt2yqhefjab.html

[U14] Py：分组收集到列表
来源：http://dali.sysykeji.top/Article/details/gt2kymmghvd.html

defaultdict(list)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzgzxwgt.html

[U15] Py：高精度计时
来源：http://dali.svipenyu.cn/Article/details/gt2qdheuqwc.html

t = time.perf_counter()
来源：http://dali.shzxlz.cn/Article/details/gt2fnwjrivi.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258888.top/Article/details/gt2jlggxkzj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgufenzy.top/Article/details/gt2knhhpfje.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gt2urcaqcpf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gt2whecroar.html

[U18] Py：预编译正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zawrqtqz.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2zmzojosm.html

[U19] Py：正则替换带回调
来源：http://dali.shangyingyoupin.top/Article/details/gt2aweisqxq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shzxlz.cn/Article/details/gt2oewifhog.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gt2ezezticf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gt2arhxewvi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuvieexi.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gt2fahvwhrd.html

[U22] Py：矩阵转置
来源：http://dali.jinqigfzy.top/Article/details/gt2qfarozba.html

list(zip(*m))
来源：http://dali.hfpthk.cn/Article/details/gt2grueoylv.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gt2ecrvqoxb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gt2iqtvbmyt.html

[U24] Py：路径操作
来源：http://dali.jqgfzy.top/Article/details/gt2ntypjxzv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gt2iotmviuw.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jyplryxg.html

csv.DictReader(f)
来源：http://dali.cheryme.top/Article/details/gt2vndyeilv.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gt2rvvmtvof.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gt2rcngqksb.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gt2opkuagzo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.svipenyu.cn/Article/details/gt2lljgowiw.html

[U28] Py：类型别名
来源：http://dali.ppjwa.cn/Article/details/gt2dgjoszvo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqoglbl.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gt2bjebrhro.html

@property 与 @x.setter 配合
来源：http://dali.gzhubu.top/Article/details/gt2qedjucxu.html

[U30] Py：数据类
来源：http://dali.haohaochexian.top/Article/details/gt2bpwdgpcg.html

@dataclass(slots=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmgzxcuk.html

[U31] Py：单测
来源：http://dali.xinyue.icu/Article/details/gt2cfwvyfws.html

python -m pytest -q
来源：http://dali.fzhhl.top/Article/details/gt2unapthvy.html

[U32] Py：代码格式化
来源：http://dali.yj202588.top/Article/details/gt2cwrcgalx.html

ruff format . && ruff check --fix .
来源：http://dali.zhengqikj.top/Article/details/gt2vllyapiv.html

[U33] Py：打包发布
来源：http://dali.shzxlz.cn/Article/details/gt2bjgfxirb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhoulong.xyz/Article/details/gt2wsykngzy.html

[U34] Py：判断编码
来源：http://dali.jqgfzy.top/Article/details/gt2xonqsemq.html

chardet.detect(raw)
来源：http://dali.nwbrower.top/Article/details/gt2ljtvyagn.html

[U35] Py：发送邮件
来源：http://dali.shangyingyoupin.top/Article/details/gt2liuiuhdu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhixingplan.top/Article/details/gt2ozqjaqcf.html

[U36] Py：定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgdwhaxa.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenzaomai.com/Article/details/gt2qdciwrdt.html

[U37] Py：读写 Excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjuuzmgx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhixingplan.top/Article/details/gt2sgaxdujv.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangdashe.top/Article/details/gt2dzmgdjyn.html

Path(__file__).resolve().parent
来源：http://dali.bjfxy.top/Article/details/gt2tjzqragf.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elikkhcr.html

sys.stdout.isatty()
来源：http://dali.zhixingplan.top/Article/details/gt2wbfghvrt.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gt2sddyrubb.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2xkprqbcz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.snrcjt.cn/Article/details/gt2mogocksq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gt2actysdhb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhongyouzk.top/Article/details/gt2kldecfyg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgfzy.top/Article/details/gt2htdpfqaq.html

[U43] PHP：声明命名空间
来源：http://dali.cdnleiting.top/Article/details/gt2rdrvrafi.html

namespace App\Http;
来源：http://dali.xuanzx.com/Article/details/gt2hduniqjm.html

[U44] PHP：开启严格类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfmcjdol.html

declare(strict_types=1);
来源：http://dali.fzhhl.top/Article/details/gt2npkudgnb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yueranfly.top/Article/details/gt2uycwlxlh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gt2mczdsyhv.html

[U46] PHP：可空类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvatmrvm.html

?string $name = null
来源：http://dali.zhongyouzk.top/Article/details/gt2ucwnmmbv.html


<!-- 参考信息 -->