代发 wailian999

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gt2fajauqmy.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gt2vjuyyqai.html

#endif
来源：http://dali.c1oappe.top/Article/details/gt2wunfugmu.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gt2muicpqpd.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gt2vybmwdye.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aesayvrh.html

[S32] C++：字符串
来源：http://dali.cheryme.top/Article/details/gt2tzutdioc.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gt2lstqzqwm.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gt2tjtoimki.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxlyymua.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gt2jlyvmmbd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gt2yhcstkuz.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gt2ulegdkeq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2lenmjfon.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gt2jqdhvoqv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2uoqwqtcj.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gt2mhzegzrh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eobmfakn.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2cammdoko.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2vulvvxcj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhixingplan.top/Article/details/gt2bfyfrglo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gt2wtfkvuuo.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2ppqywtdz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gt2lhznclpg.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2yhknijue.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gt2enltscxn.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gt2xkxjganb.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gt2ikjxfogv.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gt2lvbbbngl.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gt2yotriboj.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gt2okahjors.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gt2akpoywdz.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gt2jjchboia.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xylfe.cn/Article/details/gt2mbylgcgw.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gt2mzmgnbvt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gt2ccgqikqk.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gt2acebqhsw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gt2umeydfpn.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2qxvccfel.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gogol.net.cn/Article/details/gt2idmqxhin.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gt2fadhrstu.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2fxagdolu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gt2mxeakjrz.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gt2aevuaufz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2yqpvraml.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gt2hxuxzsdn.html

static_cast<double>(a) / b
来源：http://dali.yongpay.top/Article/details/gt2xeufivtk.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gt2fpqaivcn.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfhitdys.html

[S53] C++：移动语义
来源：http://dali.quarkkingdee.top/Article/details/gt2ebiiudnq.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gt2netrzccx.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gt2jwvbmmem.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gt2mvsjvsub.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gt2saqwehes.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2fbbisbls.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gt2xyaazupy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gt2blxtzepr.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gt2vouxydrj.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gt2gobfkvwm.html

[S58] C++：命名空间
来源：http://dali.chenzaomai.com/Article/details/gt2gptcnabv.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gt2nyuiamrb.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gt2syoqfvdf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hfpthk.cn/Article/details/gt2dqqgqbbr.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gt2ankajzen.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2eyvwcluq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2cpgpxhhi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gt2molznjcv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2wvqvwjck.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2peizjwok.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2gyclqlgp.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gt2gliagqmo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gt2mgylgomj.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gt2mwbnmdbc.html

"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gt2yhyetivn.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gt2nsrvzjex.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gt2vstploec.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gt2gjqrsmql.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cuwtbtcd.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gt2qpqpbuxz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2serhewwq.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gt2wkzfqfdd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gt2rddzqkgn.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gt2jgrmoqss.html

data class User(val name: String, val age: Int)
来源：http://dali.fzhhl.top/Article/details/gt2jfasmlcn.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gt2qdbvwrya.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gt2dbpchaqr.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gt2ojogmatf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gt2hnkhakan.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gt2uintqcda.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gt2ukllvkad.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gt2mmgriwdc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxliwci.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gt2rwaxzhkd.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzxiihjo.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gt2orqcxpoo.html

for (i in 1..10) println(i)
来源：http://dali.316326.xyz/Article/details/gt2fmklaejy.html

[T15] Kotlin：接口
来源：http://dali.shzxlz.cn/Article/details/gt2gzoppaoi.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gt2vfjdkxaq.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2xxkczuox.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2ynrclvbr.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gt2mwiyaklq.html

var a = 1;  let b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2lubrcgeo.html

[T18] Swift：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2sjcmraij.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gt2rvzgzqel.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gt2wohciimk.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gt2qspxafcx.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjlbwdfi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fzhhl.top/Article/details/gt2nmmobdqf.html

[T21] Swift：遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2outylinn.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gt2rvfsjmhi.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gt2ymqgjcts.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gt2ysqkazdp.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gt2dphfvujf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gt2yygrsiza.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gt2pxetvuwv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2zxfaplok.html

[T25] Swift：结构体
来源：http://dali.cdnleiting.top/Article/details/gt2nposddun.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrslmeie.html

[T26] Swift：类与重写
来源：http://dali.sweek.top/Article/details/gt2meboybqf.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gt2zorjzfft.html

[T27] Swift：错误处理
来源：http://dali.birdmap.top/Article/details/gt2gajtbdoz.html

do { try f() } catch { print(error) }
来源：http://dali.sysykeji.top/Article/details/gt2vjioqenr.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2stxkyxrh.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yclyikfc.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gt2biinawzl.html

guard let x = opt else { return }
来源：http://dali.yj20258888.top/Article/details/gt2umuguxhd.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gt2flszofmj.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gt2xempswsd.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2pnqhvion.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2rzoeptmj.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gt2ihsksgpy.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gt2muugzdmu.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzirdias.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gt2pdupekom.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gt2pyjnuexk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gt2frgxmsez.html

[T35] Lua：字典表
来源：http://dali.jyoumei.cn/Article/details/gt2snslgyow.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2otrtkhgw.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gt2ybefjwrb.html

function add(a, b) return a + b end
来源：http://dali.gogol.net.cn/Article/details/gt2nkkvjmld.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gt2yecyjziy.html

"a" .. "b"
来源：http://dali.sysykeji.top/Article/details/gt2zoiadufg.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2hevhwwpw.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gt2zxyljnyr.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gt2zikgtxwy.html

string.find(s, "%d+")
来源：http://dali.yueranfly.top/Article/details/gt2iwcylisw.html

[T40] Lua：元表
来源：http://dali.sxryk.cn/Article/details/gt2msiurhgz.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gt2ctwydocs.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2nqtdhnwr.html

print "Hello\n";
来源：http://dali.sufxvd.cn/Article/details/gt2whlbrmzv.html

[T42] Perl：变量类型
来源：http://dali.cheryme.top/Article/details/gt2msswrfgt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tianlin.xyz/Article/details/gt2pwfccdws.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gt2dvofdtuq.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gt2cnoaquin.html

[T44] Perl：条件
来源：http://dali.yj20258888.top/Article/details/gt2wphasepg.html

if ($a > 0) { print "正"; }
来源：http://dali.ehwqpu.com/Article/details/gt2yktnkopn.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwqwwoso.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gt2ephzipas.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gt2pchefevu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuanzhike.top/Article/details/gt2nsltfrlr.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gt2gcidnagt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gt2cpqjnoyq.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gt2xrkfqsds.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpkqhuh.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwczgkia.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gt2jiqxcryw.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2jbtfmpos.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gt2pznaliop.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gt2xuzyxdjk.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2zkaiqnyk.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gt2rmjrqpbt.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gt2kaacyngj.html

val a = 1;  var b = 2
来源：http://dali.316326.xyz/Article/details/gt2fujgbfgb.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2zotvapfg.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gt2cnxugclt.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkwpsiha.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2vzcismjh.html

[T55] Scala：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpgdyaws.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyjkgomy.html

[T56] Scala：样例类
来源：http://dali.tianlin.xyz/Article/details/gt2vraitrym.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gt2kkylpqdu.html

[T57] Scala：模式匹配
来源：http://dali.fengsongda.top/Article/details/gt2rvtcuwwf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cdnleiting.top/Article/details/gt2xfxqscke.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gt2yiiyormq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.andypj.xyz/Article/details/gt2ehmfhprn.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gt2sifpknvd.html

for (i <- 1 to 10) println(i)
来源：http://dali.ivvv.top/Article/details/gt2pzoszqmp.html

[T60] Scala：折叠
来源：http://dali.yj202588.top/Article/details/gt2nwkmkpkw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gt2egobfsrg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ajgsmofi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2wcugwayt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2nxhyfthr.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gt2xxoywoyc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gt2bcgnocux.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gt2shqaljcb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hysaishi.cn/Article/details/gt2zywvgiqm.html

[U03] Py：加载 .env 配置
来源：http://dali.hfpthk.cn/Article/details/gt2uynriyxg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gt2blbiupda.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gt2kmpqetvy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuxming.cn/Article/details/gt2akavndhn.html

[U05] Py：列表去重且保序
来源：http://dali.yuanzhike.top/Article/details/gt2kjkxqngd.html

list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2qujfpvoa.html

[U06] Py：合并两个字典
来源：http://dali.nwbrower.top/Article/details/gt2xhxizyrj.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gt2dtuyjfav.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gt2dwmhvvma.html

{v: k for k, v in d.items()}
来源：http://dali.jiagoushi.top/Article/details/gt2vkwctwsz.html

[U08] Py：展平二维列表
来源：http://dali.haohaochexian.top/Article/details/gt2llpthkmp.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gt2ofhioizw.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gt2ifhauxin.html

max(d, key=d.get)
来源：http://dali.jqgufenzy.top/Article/details/gt2mcgtnfxq.html

[U10] Py：按值排序字典
来源：http://dali.yongpay.top/Article/details/gt2kvbjoazm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gt2lvrrfzrg.html

[U11] Py：生成器表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2sgqwyynf.html

(x * 2 for x in arr)
来源：http://dali.ppjwa.cn/Article/details/gt2gldfxrqv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hysaishi.cn/Article/details/gt2znmzcvhj.html

Counter(arr).most_common(3)
来源：http://dali.pycfn.com/Article/details/gt2ufiswugx.html

[U13] Py：固定长度队列
来源：http://dali.gotoacloud.top/Article/details/gt2wlctgchg.html

deque(maxlen=10)
来源：http://dali.iojbl.cn/Article/details/gt2lmahszsl.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gt2ufvrsrpz.html

defaultdict(list)
来源：http://dali.yj20258.top/Article/details/gt2ozoeswtx.html

[U15] Py：高精度计时
来源：http://dali.zdqjudy.top/Article/details/gt2xaeayzuk.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gt2ceygasvj.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigfzy.top/Article/details/gt2vqefcewe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jlsjyb.cn/Article/details/gt2vyggrcyu.html

[U17] Py：初始化日志
来源：http://dali.yueranfly.top/Article/details/gt2dlbwlvmf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxinkj.top/Article/details/gt2zgqkpsyl.html

[U18] Py：预编译正则
来源：http://dali.cashguo.top/Article/details/gt2zzptdfai.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2cevfmhsz.html

[U19] Py：正则替换带回调
来源：http://dali.guannengcc.top/Article/details/gt2nrxssqdn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangdashe.top/Article/details/gt2uxfucopw.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gt2prmbonum.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xinyue.icu/Article/details/gt2sntosvzf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhoulong.xyz/Article/details/gt2lrigcesb.html

@contextlib.contextmanager
来源：http://dali.ivvv.top/Article/details/gt2moedifoc.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gt2inihjtrk.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gt2erlestwy.html

[U23] Py：分块读取大文件
来源：http://dali.andypj.xyz/Article/details/gt2bqrecgbs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.iojbl.cn/Article/details/gt2vkfvprhc.html

[U24] Py：路径操作
来源：http://dali.aibaodan.cn/Article/details/gt2xrlbkgtu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gt2bmdefchh.html

[U25] Py：CSV 按字典读
来源：http://dali.316326.xyz/Article/details/gt2abwvrlju.html

csv.DictReader(f)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgssnkvx.html

[U26] Py：并发下载
来源：http://dali.316326.xyz/Article/details/gt2lisdsadq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgfzy.top/Article/details/gt2yspuiqmm.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gt2qviagqiq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.snrcjt.cn/Article/details/gt2sqptsddc.html

[U28] Py：类型别名
来源：http://dali.yanxiufei.cn/Article/details/gt2cdkzxcii.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gt2bzufjuxn.html

[U29] Py：属性校验
来源：http://dali.ivvv.top/Article/details/gt2fbdfspke.html

@property 与 @x.setter 配合
来源：http://dali.haohaochexian.top/Article/details/gt2awreyhtf.html

[U30] Py：数据类
来源：http://dali.xziqi.cn/Article/details/gt2secmeqht.html

@dataclass(slots=True)
来源：http://dali.yj202588.top/Article/details/gt2vvhcvsik.html

[U31] Py：单测
来源：http://dali.aizwys.cn/Article/details/gt2neazowar.html

python -m pytest -q
来源：http://dali.yj20258.top/Article/details/gt2pcxbrxab.html

[U32] Py：代码格式化
来源：http://dali.redwolf501.top/Article/details/gt2fvhqdkps.html

ruff format . && ruff check --fix .
来源：http://dali.chenzaomai.com/Article/details/gt2rzxbtkhe.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gt2cbtngnzj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gt2yehkflny.html

[U34] Py：判断编码
来源：http://dali.guowangkeji.top/Article/details/gt2rplakbho.html

chardet.detect(raw)
来源：http://dali.cashguo.top/Article/details/gt2ngtosluo.html

[U35] Py：发送邮件
来源：http://dali.tanke756.top/Article/details/gt2rvdjvfsp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gt2mzgacljb.html

[U36] Py：定时任务
来源：http://dali.yuanzhike.top/Article/details/gt2pvzugjbg.html

schedule.every(10).minutes.do(job)
来源：http://dali.cashguo.top/Article/details/gt2ddxleqlo.html

[U37] Py：读写 Excel
来源：http://dali.sxryk.cn/Article/details/gt2sxyosdyn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigfzy.top/Article/details/gt2tonxqahb.html

[U38] Py：获取脚本所在目录
来源：http://dali.cqqwz.cn/Article/details/gt2jjzrmfhh.html

Path(__file__).resolve().parent
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfsrgcrp.html

[U39] Py：判断是否在交互环境
来源：http://dali.shangyingyoupin.top/Article/details/gt2prmpowdu.html

sys.stdout.isatty()
来源：http://dali.ehwqpu.com/Article/details/gt2uuwizoqz.html

[U40] Py：打印到标准错误
来源：http://dali.fzhhl.top/Article/details/gt2ulyayjyh.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gt2uvgyyfyv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gzhubu.top/Article/details/gt2ahztsngd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangdashe.top/Article/details/gt2fnwfxiwi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.316326.xyz/Article/details/gt2jlvzjfei.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guowangkeji.top/Article/details/gt2jqmwwduh.html

[U43] PHP：声明命名空间
来源：http://dali.ehwqpu.com/Article/details/gt2xrtqfjcp.html

namespace App\Http;
来源：http://dali.mhx1999.top/Article/details/gt2kdzwvsdx.html

[U44] PHP：开启严格类型
来源：http://dali.yuxming.cn/Article/details/gt2bjezdtal.html

declare(strict_types=1);
来源：http://dali.jyoumei.cn/Article/details/gt2vuwfuqwi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hammf.cn/Article/details/gt2mmakbwgg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gt2lrglgsly.html

[U46] PHP：可空类型
来源：http://dali.fengsongda.top/Article/details/gt2mjcrrnrd.html

?string $name = null
来源：http://dali.feifeiyinyue.top/Article/details/gt2smxsnvfr.html

[U47] PHP：联合类型
来源：http://dali.jyoumei.cn/Article/details/gt2thqxqjad.html

int|string $id
来源：http://dali.hammf.cn/Article/details/gt2ujgxnjbp.html

[U48] PHP：纯枚举
来源：http://dali.ppjwa.cn/Article/details/gt2jjoypumf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wexphvdq.html

[U49] PHP：只读属性
来源：http://dali.cucudq.cn/Article/details/gt2eigpitew.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpgugeth.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxinkj.top/Article/details/gt2cstteysu.html

public function __construct(private int $id) {}
来源：http://dali.havefunace.top/Article/details/gt2ojmzmysr.html

[U51] PHP：数组解构
来源：http://dali.yj20258888.top/Article/details/gt2fudsyqtv.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gt2eymgoqcg.html

[U52] PHP：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2uyentuve.html

$double = fn($x) => $x * 2;
来源：http://dali.zhengqikj.top/Article/details/gt2eoyhnugh.html

[U53] PHP：空合并运算符
来源：http://dali.yonumen.top/Article/details/gt2jmykbobt.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxaqjcxc.html

[U54] PHP：空安全调用
来源：http://dali.vqdsnc.cn/Article/details/gt2vtuyozyy.html

$obj?->method()
来源：http://dali.gzhubu.top/Article/details/gt2tlubzfzm.html


<!-- 参考信息 -->