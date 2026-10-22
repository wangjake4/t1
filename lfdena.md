代发 wailian999

static int counter = 0;
来源：http://dali.hywenlv.cn/Article/details/gt2poynmutw.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gt2fjhkcxae.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gt2sowqywtf.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gt2fciubnkx.html

#ifndef X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2jiiorskm.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gt2wxnxazbe.html

#endif
来源：http://dali.jianghu66.top/Article/details/gt2rgdvkjba.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gt2ldrpjogm.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gt2mnjwmdnt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258888.top/Article/details/gt2fecftwso.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2ocxaepvy.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gt2sdcujqtx.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gt2lwfhvrit.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gt2ujbygjwr.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gt2eaxbwquu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gt2zlqwveqc.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epdlopha.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2hemsncjw.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gt2wsebiajl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2mqlohhgc.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gt2omqaifnx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2hrdupcox.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gt2ywwuzxvc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gt2kccpxdhe.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gt2jbuyrjnu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gt2uklbqcwd.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2upauhkkt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2vlvyqkyn.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2eynpdcql.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gt2zasexbwa.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gt2guislkrj.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgmuqipl.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gt2pmraianp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2rxoeekyv.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gt2sdmavzee.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2shucszoi.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gt2gaoghylb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gt2vyntyawb.html

[S46] C++：函数模板
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wctvrbzn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gt2otptfsej.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gt2hpxfaweg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egrdpvqp.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2hfpfllbs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzxrplts.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gt2vnlckyjm.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftyolkfv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2uhtbjrnw.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gt2jajjpnhb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2ixganbom.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gt2yzvwjvgt.html

static_cast<double>(a) / b
来源：http://dali.daria6918.cn/Article/details/gt2xorkuyth.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gt2bbiixsjd.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xyntlrjr.html

[S53] C++：移动语义
来源：http://dali.tanke756.top/Article/details/gt2knffhcbi.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gt2tgsrwhwr.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gt2vdyoyxxc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gt2svgacuem.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gt2emgyxoir.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gt2txmkfjyq.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gt2gxfhovno.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gt2lsgpebuo.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gt2mzxmqvgw.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gt2uzdecegv.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gt2ljneaykc.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gt2gwveltkb.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytkcriip.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gt2aotvuuob.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gt2cdlwwveo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2xmgrpqkc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2jisurzie.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gt2iwxcikll.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtrskqmd.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2qtkmuqkr.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2qxnehueg.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gt2mymbdqrw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gt2eanpdnvy.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gt2uhalfnsk.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gt2mejsxaij.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gt2hpomdjic.html

val n: String? = null;  n?.length
来源：http://dali.yonumen.top/Article/details/gt2siaildpb.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gt2drkmnztk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gt2dstyrmdo.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gt2oferqpuv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2obddjocj.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gt2emweqara.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ussggwpx.html

[T08] Kotlin：数据类
来源：http://dali.ybcxt.top/Article/details/gt2dtvkddic.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gt2ymhuhecf.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgueudqy.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gt2puavwrzn.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gt2xhobfbxp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gt2hitidvsf.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gt2hxyivton.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gt2mhwxvwvk.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehzhzhky.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2wvqvbuoj.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gt2yclevsvw.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gt2jovqfdoq.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gt2rdbtbjah.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gt2atgtqvve.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gt2svqbezrv.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gt2civxechc.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2hfttrwcp.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2criihtpp.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gt2xidryzvl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfjvaub.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2ainfhtdt.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idhncprt.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gt2clvmiogc.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gt2ztdsvimg.html

[T20] Swift：数组操作
来源：http://dali.zhongyouzk.top/Article/details/gt2wpvctuvh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqvvkzax.html

[T21] Swift：遍历
来源：http://dali.dashuyun.cn/Article/details/gt2kltzqght.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ruxbggtw.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gt2kxyjqyko.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gt2kivkulkn.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2qzwciler.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2gobudiet.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gt2zeewkjbc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2lpwatyzx.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gt2xjhrxmhk.html

struct P { var x: Int }
来源：http://dali.mhx1999.top/Article/details/gt2zutuoulb.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gt2nzecaufl.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gt2ecvmvakl.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gt2qmqpyfch.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gt2nsilixbl.html

[T28] Swift：枚举
来源：http://dali.svipenyu.cn/Article/details/gt2zvkgwbxu.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gt2zzmojbjj.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gt2aokxmpjs.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gt2rktdserk.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gt2ddhnswbt.html

protocol Shape { func area() -> Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2ogceatzs.html

[T31] Lua：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xchxwlbp.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gt2awayrnwc.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2migtckmi.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gt2hbnbkxba.html

[T33] Lua：表（数组）
来源：http://dali.dashuyun.cn/Article/details/gt2urgyuzzi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gt2bldyrxoq.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bggjpaui.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.c1oappe.top/Article/details/gt2ikzdsqdj.html

[T35] Lua：字典表
来源：http://dali.kuanghao11.cn/Article/details/gt2zccinlqk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gt2zvpbwogx.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2rkjiuykk.html

function add(a, b) return a + b end
来源：http://dali.hysaishi.cn/Article/details/gt2vzfhbkxo.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gt2cgwrmcjy.html

"a" .. "b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2tdshurmv.html

[T38] Lua：条件
来源：http://dali.ybcxt.top/Article/details/gt2zyykazlp.html

if x > 0 then print("正") end
来源：http://dali.meibo888.top/Article/details/gt2weimacpw.html

[T39] Lua：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hahfwtop.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gt2fvfypbga.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gt2yuidilpr.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gt2kzrwcljg.html

[T41] Perl：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2iwbktigj.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gt2sivoldgw.html

[T42] Perl：变量类型
来源：http://dali.ivvv.top/Article/details/gt2lbvapsve.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2lgmdgomf.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvjhaclg.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbclzowl.html

[T44] Perl：条件
来源：http://dali.c1oappe.top/Article/details/gt2wilruhce.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258.top/Article/details/gt2xczeesri.html

[T45] Perl：数组遍历
来源：http://dali.iojbl.cn/Article/details/gt2aypousaa.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bofeobat.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gt2kqdwcikp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dgtwlnho.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmndloae.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cqqwz.cn/Article/details/gt2ajzefyvg.html

[T48] Perl：正则替换
来源：http://dali.yueranfly.top/Article/details/gt2dvrdzwoo.html

$s =~ s/old/new/g;
来源：http://dali.hysaishi.cn/Article/details/gt2stejhyly.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gt2hzlzyxky.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2iykeknkn.html

[T50] Perl：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2cjdyguee.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gt2atgtyabt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gt2boehzmyl.html

[T51] Scala：Hello World
来源：http://dali.meibo888.top/Article/details/gt2ewcxtvud.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcqbmobk.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gt2nvduhief.html

val a = 1;  var b = 2
来源：http://dali.redwolf501.top/Article/details/gt2oxvoniwt.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2sdvxxjpx.html

s"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2ycybkwik.html

[T54] Scala：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gt2ybfxfkxn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xinyue.icu/Article/details/gt2lbxxrfhd.html

[T55] Scala：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gt2vcricfih.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gt2vwadepmq.html

[T56] Scala：样例类
来源：http://dali.smart0.xyz/Article/details/gt2asfxqwai.html

case class User(name: String, age: Int)
来源：http://dali.yonumen.top/Article/details/gt2bsowkhon.html

[T57] Scala：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utjtzbcx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgfzy.top/Article/details/gt2mofleoda.html

[T58] Scala：函数定义
来源：http://dali.cucudq.cn/Article/details/gt2jahtyuxz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2woscubro.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gt2mbpmhicd.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2kusppkws.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gt2wukhopgy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gt2pyhugdmn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ylztzxil.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gt2nvkogwlc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2bzjzvdds.html

[U01] Py：创建虚拟环境
来源：http://dali.guowangkeji.top/Article/details/gt2wwerkdtn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gt2wmxjihxj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gt2iswsbhxy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.svipenyu.cn/Article/details/gt2idfaxxbw.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gt2pgzqafsx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfxciabx.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gt2qftchtfl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.andypj.xyz/Article/details/gt2coyhmczt.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twxiiwht.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzhvstct.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gt2siwnxjvq.html

{**a, **b}
来源：http://dali.fzhhl.top/Article/details/gt2xglxyryz.html

[U07] Py：反转字典键值
来源：http://dali.gzhubu.top/Article/details/gt2gcjsqbwm.html

{v: k for k, v in d.items()}
来源：http://dali.nanxuanxn.top/Article/details/gt2iibtmvgj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuxeuwh.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gt2hnmssmap.html

[U09] Py：字典取最大值的键
来源：http://dali.yvedp.cn/Article/details/gt2elfeagvj.html

max(d, key=d.get)
来源：http://dali.guannengcc.top/Article/details/gt2fybczmgv.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gt2jkglrdyx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gt2yhpwgjnh.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2oyxzenaw.html

(x * 2 for x in arr)
来源：http://dali.xuanzx.com/Article/details/gt2sdgubwuu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yonumen.top/Article/details/gt2sllnzshh.html

Counter(arr).most_common(3)
来源：http://dali.ehwqpu.com/Article/details/gt2taqopwir.html

[U13] Py：固定长度队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2nggixvqc.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gt2leejeyhh.html

[U14] Py：分组收集到列表
来源：http://dali.yvedp.cn/Article/details/gt2bhmyntgm.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gt2gibzbwpm.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gt2esoefgil.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gt2clljbizs.html

[U16] Py：命令行参数解析
来源：http://dali.guannengcc.top/Article/details/gt2heuvgapa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gt2amaewhsm.html

[U17] Py：初始化日志
来源：http://dali.snrcjt.cn/Article/details/gt2wssdnvcs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tztjbmcj.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gt2sxpxymyt.html

pat = re.compile(r"\d+")
来源：http://dali.yvedp.cn/Article/details/gt2bgpghtvq.html

[U19] Py：正则替换带回调
来源：http://dali.guannengcc.top/Article/details/gt2rnnirwkv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jianghu66.top/Article/details/gt2qscgvpyj.html

[U20] Py：缓存函数结果
来源：http://dali.cdnleiting.top/Article/details/gt2ojpafccp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hfpthk.cn/Article/details/gt2vruxnunx.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddxkatwh.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gt2hpxnycio.html

[U22] Py：矩阵转置
来源：http://dali.ydzc1.top/Article/details/gt2vmlfmagj.html

list(zip(*m))
来源：http://dali.svipenyu.cn/Article/details/gt2xxlejtjt.html

[U23] Py：分块读取大文件
来源：http://dali.haohaochexian.top/Article/details/gt2ynhsvtfi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dashuyun.cn/Article/details/gt2qjfyplco.html

[U24] Py：路径操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2msgypjvd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gt2fkzieqsj.html

[U25] Py：CSV 按字典读
来源：http://dali.kuanghao11.cn/Article/details/gt2kgvmekvy.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gt2itltyijf.html

[U26] Py：并发下载
来源：http://dali.zhixingplan.top/Article/details/gt2etsespbl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.9152youxi.cn/Article/details/gt2vvnysjvn.html

[U27] Py：异步 HTTP
来源：http://dali.zhengqikj.top/Article/details/gt2hhqfcxlg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ehwqpu.com/Article/details/gt2butqtjdt.html

[U28] Py：类型别名
来源：http://dali.cheryme.top/Article/details/gt2dleeiabf.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gt2oilyqhux.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gt2gviadran.html

@property 与 @x.setter 配合
来源：http://dali.hysaishi.cn/Article/details/gt2fqknrzrk.html

[U30] Py：数据类
来源：http://dali.wangdashe.top/Article/details/gt2alacifzy.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2nivhmqnq.html

[U31] Py：单测
来源：http://dali.wangshuangyany.cn/Article/details/gt2blrjoywd.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gt2bpyqcbwr.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrsummzu.html

ruff format . && ruff check --fix .
来源：http://dali.meibo888.top/Article/details/gt2lfvegwpd.html

[U33] Py：打包发布
来源：http://dali.0kj1m.cn/Article/details/gt2hpzkeqfw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dianchejie.cn/Article/details/gt2ksfkmcws.html

[U34] Py：判断编码
来源：http://dali.andypj.xyz/Article/details/gt2ddjkhxwo.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gt2hvbvukon.html

[U35] Py：发送邮件
来源：http://dali.ppjwa.cn/Article/details/gt2vsnrbkci.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xuanzx.com/Article/details/gt2lvbysukd.html

[U36] Py：定时任务
来源：http://dali.redwolf501.top/Article/details/gt2igtfjgwk.html

schedule.every(10).minutes.do(job)
来源：http://dali.dianchejie.cn/Article/details/gt2ohlvvlse.html

[U37] Py：读写 Excel
来源：http://dali.316326.xyz/Article/details/gt2qijvuocm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenlongwang.top/Article/details/gt2alxtugiy.html

[U38] Py：获取脚本所在目录
来源：http://dali.kuanghao11.cn/Article/details/gt2gzymitkg.html

Path(__file__).resolve().parent
来源：http://dali.jqgufenzy.top/Article/details/gt2axtgjtja.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2caytuxrt.html

sys.stdout.isatty()
来源：http://dali.ydzc1.top/Article/details/gt2prrgegsx.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258.top/Article/details/gt2avutgcca.html

print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gt2vvqnvman.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.316326.xyz/Article/details/gt2otvmjzeu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gt2yosubtek.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aizwys.cn/Article/details/gt2lfbopimq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gt2rwpstbow.html

[U43] PHP：声明命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxnqfbua.html

namespace App\Http;
来源：http://dali.yj20258888.top/Article/details/gt2svjndpqb.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gt2ajzvhdxj.html

declare(strict_types=1);
来源：http://dali.meibo888.top/Article/details/gt2matntpkg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gt2vfzopkyd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2gkyhbyvg.html

[U46] PHP：可空类型
来源：http://dali.xylfe.cn/Article/details/gt2xygnqkpa.html

?string $name = null
来源：http://dali.yanxiufei.cn/Article/details/gt2rtfqqaxj.html

[U47] PHP：联合类型
来源：http://dali.sweek.top/Article/details/gt2rdysxdmp.html

int|string $id
来源：http://dali.yj20258.top/Article/details/gt2ranjcpim.html

[U48] PHP：纯枚举
来源：http://dali.0kj1m.cn/Article/details/gt2hrwdicjp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aizwys.cn/Article/details/gt2aasyrvst.html

[U49] PHP：只读属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqkkndnf.html

public readonly string $name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2faormidu.html

[U50] PHP：构造器属性提升
来源：http://dali.snrcjt.cn/Article/details/gt2gakcxdcp.html

public function __construct(private int $id) {}
来源：http://dali.jinqigufen.top/Article/details/gt2zlbrvbqu.html

[U51] PHP：数组解构
来源：http://dali.shzxlz.cn/Article/details/gt2mipuywcs.html

[$a, $b] = $arr;
来源：http://dali.fengsongda.top/Article/details/gt2uoorgyfl.html

[U52] PHP：箭头函数
来源：http://dali.redwolf501.top/Article/details/gt2qtfpwuou.html

$double = fn($x) => $x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtzxewju.html


<!-- 参考信息 -->