代发 wailian999

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtudujzkww.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtvycmnulc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtgappfmfm.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gtdmofbcsx.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnabzggu.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtfjpoprxt.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrcyggkl.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gtlawamsuc.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtxrvygfoc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtqrpxasug.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtctpvlwin.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtgyggifpf.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gtzneawcvi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gthoypdtfv.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gttwpxtwvb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtygrsgsrl.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbgcofpx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtvwpblb.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gtcvlndggd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gttsvhsixv.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gtycjnzgxo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gterzvytrk.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gtjdxikjah.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtphczzrld.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gtpaeoewsy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtmgtlgqsp.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtcorpaesk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gtiytrmmhv.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gtidqkaxdu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gaohongyu789.top/Article/details/gttbjiqoew.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gtzvmrijpt.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenlongwang.top/Article/details/gtxwehbwsw.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gtlxehbinq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpxroldc.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gtlqpmpcic.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gtifcduass.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtpqdnygva.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gtklnoxdvp.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtiplvmknx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtjgjhjzee.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gtlzuiwoib.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqpmeskpv.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtbhknyywp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtzwyiktgz.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhnccggt.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtfaijxanm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtlgfkvktx.html

[S50] C++：格式化数字
来源：http://dali.jiagoushi.top/Article/details/gtnaajemid.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtdnpwueog.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtzmzissae.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gtyaxdcdxk.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfafneupm.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gtcnhpjefr.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gtpvhuheao.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gtmlhlctye.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gtijtqdqbl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtzffghduj.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtmuxgjrdi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ivvv.top/Article/details/gtnjddqowg.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gtidansoqz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgjjcveyd.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gtymlymjtn.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gtkugavqzq.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gtibkhxtvj.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gterxktpqu.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gtknrhmshd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtujwzgisf.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gttdcfcmyg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gtdxvgkdmm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtucookodg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gthypqebef.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzzmlnela.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtclvlwyez.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtgprjvloa.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtgsiksgxp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gtxjnvsyke.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gtdijzbgjf.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtuewdgyxz.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gtfotijeqa.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtznikgbfl.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtolimzaud.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ybcxt.top/Article/details/gtwwchzvql.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtkoaenfyw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gttpqylouv.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtjdflqdhs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shzxlz.cn/Article/details/gtojalsxsb.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimirbszl.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtslvlicgv.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gtzobwuaqh.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtptzgtpfq.html

[T10] Kotlin：默认参数
来源：http://dali.yueranfly.top/Article/details/gtnunzqlol.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtlnvyeyll.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gtddtjlnec.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gtqpkgneyw.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gtdwfrghpa.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gthaxeorbo.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gtxatuhbub.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtrghvjcgy.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gthkrnnaeb.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcshxkiq.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtprnmtrpl.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtcpyguwme.html

[T16] Swift：Hello World
来源：http://dali.xinyue.icu/Article/details/gtqgjspras.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtxwpfqphl.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gticxszdfz.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gteectxdqr.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtzxumhikh.html

"值: \(b)"
来源：http://dali.hysaishi.cn/Article/details/gtrqzxvrhr.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gttuniuwlj.html

if let n = opt { print(n) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyfwqchy.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gtclfpfvki.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aizwys.cn/Article/details/gtmzwckfxu.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtnrvvccrm.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gtpxpcsntw.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gtprugrzom.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtwbsenoty.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gtlhjalqnx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hfpthk.cn/Article/details/gtnkcnkyiy.html

[T24] Swift：闭包
来源：http://dali.chenjidiqi.icu/Article/details/gtrjlsnavz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gtmauqbsax.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gthubtbmar.html

struct P { var x: Int }
来源：http://dali.havefunace.top/Article/details/gtayyyhecz.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gtancpdddo.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtxdcryacx.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gtbkdrufip.html

do { try f() } catch { print(error) }
来源：http://dali.yanxiufei.cn/Article/details/gtkjomaami.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gtdscgxegn.html

enum Color { case red, green }
来源：http://dali.xuanzx.com/Article/details/gtdkiyvldm.html

[T29] Swift：guard 提前返回
来源：http://dali.svipenyu.cn/Article/details/gttrkywwat.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtpeqkvhyi.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtpfayfaml.html

protocol Shape { func area() -> Double }
来源：http://dali.kuanghao11.cn/Article/details/gtyonmmfla.html

[T31] Lua：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtvxyhmice.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirgqudfu.html

[T32] Lua：局部变量
来源：http://dali.nanxinkj.top/Article/details/gtlmkxnukf.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gtjjrsugpr.html

[T33] Lua：表（数组）
来源：http://dali.kuanghao11.cn/Article/details/gtqhzwepxx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gttlxhpswt.html

[T34] Lua：遍历表
来源：http://dali.bjfxy.top/Article/details/gtxnnpmjcb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gtakgjqmbf.html

[T35] Lua：字典表
来源：http://dali.jiagoushi.top/Article/details/gtwvlrjcnf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhfxmjnm.html

[T36] Lua：函数
来源：http://dali.cucudq.cn/Article/details/gtxuirkbwf.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukmddxat.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtwifcvmxl.html

"a" .. "b"
来源：http://dali.hnxiangtu.top/Article/details/gtizznqqyr.html

[T38] Lua：条件
来源：http://dali.nanxinkj.top/Article/details/gtepurbwln.html

if x > 0 then print("正") end
来源：http://dali.yj202588.top/Article/details/gtpvccimpn.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtdzziopfw.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gttynouxbn.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gtcfkxnyoo.html

setmetatable({}, { __index = base })
来源：http://dali.jlsjyb.cn/Article/details/gtafifnvjz.html

[T41] Perl：Hello World
来源：http://dali.xziqi.cn/Article/details/gtudaukuez.html

print "Hello\n";
来源：http://dali.gotoacloud.top/Article/details/gtjcvaglwb.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gtywgdqimn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fengsongda.top/Article/details/gtayprqesb.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtdjtpmbhe.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gtumnpmhde.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gthnkqnxog.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtagqphsiq.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gtxzcqqopo.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gtgxvrtaeo.html

[T46] Perl：哈希操作
来源：http://dali.sweek.top/Article/details/gtjprgwxuj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.316326.xyz/Article/details/gtumgekbio.html

[T47] Perl：正则捕获
来源：http://dali.yueranfly.top/Article/details/gthlzcjybm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sxryk.cn/Article/details/gtvogdydam.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gtmevwzwic.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gtljejxggm.html

[T49] Perl：函数
来源：http://dali.zhengqikj.top/Article/details/gtyuulsygj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtvioxkhnq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtfdbzbkrx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgufenzy.top/Article/details/gtybikumoo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gtdiwphnyw.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtbbqujhba.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkmrheek.html

[T52] Scala：变量
来源：http://dali.jinqigfzy.top/Article/details/gtvwovfabw.html

val a = 1;  var b = 2
来源：http://dali.jyoumei.cn/Article/details/gtjgozywgh.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtghtaabit.html

s"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtaitmszak.html

[T54] Scala：集合映射
来源：http://dali.dianchejie.cn/Article/details/gtfpnxmwct.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gttznqwruw.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gttulqtxny.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtfhcrhwpl.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gturvbpmbv.html

case class User(name: String, age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtrzujyymn.html

[T57] Scala：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnifthmy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zycfv.cn/Article/details/gtebskuqju.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gtxjxifltw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gtrttcfbmn.html

[T59] Scala：循环
来源：http://dali.fengsongda.top/Article/details/gticbnhyoa.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtazydqmaa.html

[T60] Scala：折叠
来源：http://dali.zhixingplan.top/Article/details/gtqtuatwmc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ppjwa.cn/Article/details/gtlhbbkfpb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcgrtvjtj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gtjgoalavd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvgprutgj.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gtkukdpaps.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.quarkkingdee.top/Article/details/gtlxgwddjo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yanxiufei.cn/Article/details/gtkkrvdxih.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xinyue.icu/Article/details/gtwxiiuxta.html

[U03] Py：加载 .env 配置
来源：http://dali.zdqjudy.top/Article/details/gtluujikol.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gtfplepcei.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gthvmidyzs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gotoacloud.top/Article/details/gtcjqjicum.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gtwpfpzylq.html

list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtaswtequr.html

[U06] Py：合并两个字典
来源：http://dali.hfpthk.cn/Article/details/gtggvffupp.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gtprwglocl.html

[U07] Py：反转字典键值
来源：http://dali.chenzaomai.com/Article/details/gtooczreng.html

{v: k for k, v in d.items()}
来源：http://dali.snrcjt.cn/Article/details/gthsohqilg.html

[U08] Py：展平二维列表
来源：http://dali.andypj.xyz/Article/details/gtfjqyqiyr.html

[y for x in nested for y in x]
来源：http://dali.shzxlz.cn/Article/details/gtszqfpzso.html

[U09] Py：字典取最大值的键
来源：http://dali.316326.xyz/Article/details/gtmihyzjcg.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gtetworjqm.html

[U10] Py：按值排序字典
来源：http://dali.0kj1m.cn/Article/details/gtucwcauuq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gtonsnszwv.html

[U11] Py：生成器表达式
来源：http://dali.yvedp.cn/Article/details/gtkutotwbt.html

(x * 2 for x in arr)
来源：http://dali.hnxiangtu.top/Article/details/gtuiunkqkk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gtrclsphuf.html

Counter(arr).most_common(3)
来源：http://dali.haohaochexian.top/Article/details/gtpuigtrbs.html

[U13] Py：固定长度队列
来源：http://dali.yj202588.top/Article/details/gtntowqtci.html

deque(maxlen=10)
来源：http://dali.cucudq.cn/Article/details/gtxzahxhxg.html

[U14] Py：分组收集到列表
来源：http://dali.zhixingplan.top/Article/details/gtytsramyd.html

defaultdict(list)
来源：http://dali.jqgufenzy.top/Article/details/gtmkmtsibd.html

[U15] Py：高精度计时
来源：http://dali.chenjidiqi.icu/Article/details/gtimmrrthe.html

t = time.perf_counter()
来源：http://dali.yvedp.cn/Article/details/gtglawxvhc.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gtzikxatee.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxuanxn.top/Article/details/gtuhxkmijt.html

[U17] Py：初始化日志
来源：http://dali.vqdsnc.cn/Article/details/gtfzdeqoxr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gtyzbfqbqg.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gtaigcjcyb.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtfxapobci.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gtbquevplm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gtehwkndkg.html

[U20] Py：缓存函数结果
来源：http://dali.ehwqpu.com/Article/details/gtctpwmath.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hywenlv.cn/Article/details/gtqhxindpl.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gtofgyzuxk.html

@contextlib.contextmanager
来源：http://dali.feifeiyinyue.top/Article/details/gtbeyjcmim.html

[U22] Py：矩阵转置
来源：http://dali.bjfxy.top/Article/details/gtnimuuzhs.html

list(zip(*m))
来源：http://dali.mhx1999.top/Article/details/gtmavyqcru.html

[U23] Py：分块读取大文件
来源：http://dali.yueranfly.top/Article/details/gtbkhwvjes.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.andypj.xyz/Article/details/gttfkhciik.html

[U24] Py：路径操作
来源：http://dali.redwolf501.top/Article/details/gtbsxahgud.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtopcwlupi.html

[U25] Py：CSV 按字典读
来源：http://dali.316326.xyz/Article/details/gtbgsojcsk.html

csv.DictReader(f)
来源：http://dali.sxryk.cn/Article/details/gtpyntupai.html

[U26] Py：并发下载
来源：http://dali.zycfv.cn/Article/details/gtaxxfduex.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yongpay.top/Article/details/gtbufmisey.html

[U27] Py：异步 HTTP
来源：http://dali.yueranfly.top/Article/details/gteaqxbdmz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gtjnscybzp.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gtcpwdspcm.html

UserId = int
来源：http://dali.tian-w.cn/Article/details/gtgzajietq.html

[U29] Py：属性校验
来源：http://dali.tianlin.xyz/Article/details/gtussbyycv.html

@property 与 @x.setter 配合
来源：http://dali.daxiang520.top/Article/details/gtqbltwcus.html

[U30] Py：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtougdbujy.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gtfeivvckm.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gtaqmfyqvc.html

python -m pytest -q
来源：http://dali.wangshuangyany.cn/Article/details/gtpadwcqac.html

[U32] Py：代码格式化
来源：http://dali.sweek.top/Article/details/gtefmazoiw.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gtcpogiejk.html

[U33] Py：打包发布
来源：http://dali.xylfe.cn/Article/details/gtrlncnocy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cashguo.top/Article/details/gtshuxdrxr.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtfvzazmvs.html

chardet.detect(raw)
来源：http://dali.pengpengdd.cyou/Article/details/gtcnmscbhv.html

[U35] Py：发送邮件
来源：http://dali.sweek.top/Article/details/gtnrprckgy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gtvvlxdosl.html

[U36] Py：定时任务
来源：http://dali.yj202588.top/Article/details/gtduylxjpo.html

schedule.every(10).minutes.do(job)
来源：http://dali.316326.xyz/Article/details/gtkofokfvv.html

[U37] Py：读写 Excel
来源：http://dali.bjfxy.top/Article/details/gtflfyqgzw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.kuanghao11.cn/Article/details/gtfbwwqfzj.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gtkgjpdozv.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gtobvlaojm.html

[U39] Py：判断是否在交互环境
来源：http://dali.andypj.xyz/Article/details/gtqligtrws.html

sys.stdout.isatty()
来源：http://dali.fengsongda.top/Article/details/gtlwhhmaug.html

[U40] Py：打印到标准错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtylptid.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtspgyngri.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yanxiufei.cn/Article/details/gtakxvyxzd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudyevcpj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadryziop.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigufen.top/Article/details/gtyeackopy.html

[U43] PHP：声明命名空间
来源：http://dali.c1oappe.top/Article/details/gtzgwsvhvl.html

namespace App\Http;
来源：http://dali.hongshengwenyu.top/Article/details/gtsqdgsnit.html

[U44] PHP：开启严格类型
来源：http://dali.ehwqpu.com/Article/details/gtutpeafci.html

declare(strict_types=1);
来源：http://dali.aizwys.cn/Article/details/gtfqlmgzrd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnxiangtu.top/Article/details/gtmfggrwfr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtthpjbibv.html

[U46] PHP：可空类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzvlrgka.html

?string $name = null
来源：http://dali.yj202588.top/Article/details/gtvgjykkgr.html

[U47] PHP：联合类型
来源：http://dali.zhiwuduotai.top/Article/details/gtsmdqbdet.html

int|string $id
来源：http://dali.shzxlz.cn/Article/details/gtegrtkbjr.html

[U48] PHP：纯枚举
来源：http://dali.redwolf501.top/Article/details/gtthjcuhkc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yueranfly.top/Article/details/gtugcsahow.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxtmrvhh.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gtidtgvcbm.html

[U50] PHP：构造器属性提升
来源：http://dali.bjfxy.top/Article/details/gtcmlzlprz.html

public function __construct(private int $id) {}
来源：http://dali.daxiang520.top/Article/details/gtvzjoerfe.html

[U51] PHP：数组解构
来源：http://dali.shzxlz.cn/Article/details/gtuznnwfkp.html

[$a, $b] = $arr;
来源：http://dali.pengpengdd.cyou/Article/details/gtrfdhmiiz.html

[U52] PHP：箭头函数
来源：http://dali.xylfe.cn/Article/details/gtdjqebmtq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhixingplan.top/Article/details/gtsyqqxrrj.html


<!-- 参考信息 -->