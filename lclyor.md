代发 wailian999

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gt2judcqehb.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gt2genmpsde.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gt2nmaskcov.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnestqua.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iymtjnxd.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gt2srlbvsum.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gt2elkmazzf.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2dtykimda.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gt2ieyrtscn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhsqlimi.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oovhpfom.html

std::string s = "hi";  s += "!";
来源：http://dali.shuidangran.top/Article/details/gt2xlzsnfuc.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gt2zveroudf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gt2syirqbat.html

[S34] C++：遍历 vector
来源：http://dali.yanxiufei.cn/Article/details/gt2vvhhpsjx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gt2xjxsqvgp.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gt2iwbbnsgk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2jfxagkep.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gt2wvquyvqw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfarsxgm.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gt2rdtodqjl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gt2bnflkvjl.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gt2ybtpztxl.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gt2wxkvgyzm.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gt2qpxetlkj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gt2kksjjnkq.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gt2tekjohod.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gt2znqylghr.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsgwrnjk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gt2cbevlhiv.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gt2cewlbgwq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gt2esckmhqz.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gt2lzfcvmsw.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2yexhgziz.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gt2leyneshl.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gt2ybdncrjw.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncjfoovo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gt2sjqpagfr.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gt2mojefplh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vzgymmhj.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2iogoxiyg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2deccvwkl.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2khqkdrag.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gt2yufhixmk.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gt2qutmtsai.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2fwiwdoma.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gt2bjjfeint.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gt2fpwqtvnw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2kofkygzz.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gt2vnabfzff.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2aybbvjip.html

[S52] C++：const 与 noexcept
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcyoftyw.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epsngcri.html

[S53] C++：移动语义
来源：http://dali.cheryme.top/Article/details/gt2vgfhtxrn.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gt2sjxutaqq.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gt2mxdneigu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.redwolf501.top/Article/details/gt2qhmysuca.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkyklppl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gt2ylxjfqvd.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gt2qsrcobic.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gt2zvtglukt.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gt2paislfxn.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gt2bmeerdac.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gt2evtrwzmk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gt2swxyeeod.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gt2crpmdibe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyzrkzt.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gt2topqnlrr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gt2lheafkln.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2wnfngevk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojwzokag.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2nsuabcvo.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2fwjemmyy.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztzpdorl.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmwfiyuy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gt2ttirieaz.html

[T03] Kotlin：字符串模板
来源：http://dali.tianlin.xyz/Article/details/gt2wdxagoai.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2fcqzbsfc.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gt2twferdko.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gt2txahlrtz.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gt2jtzvrgbp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gt2opqtnwad.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ienhwepg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2kpjnbkse.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2pkuxaxhe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yongpay.top/Article/details/gt2utuleprt.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gt2ymnxmdee.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gt2qpbbknog.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2nieslgwb.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sowalpss.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2ysaeprcy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gt2cuujkpiq.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gt2hcwueqhj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gt2pibhozcc.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gt2qylzcojq.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spztscdc.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigufen.top/Article/details/gt2jirxqpkk.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gt2pskigdbz.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gt2kzcdseqg.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gt2kykgfwnu.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gt2hcojtrmh.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gt2vkaekgej.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2jxcwhxlm.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2vwiufytx.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gt2lzopfuvb.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gt2ancqsmwf.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gt2ifhfjvsr.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gt2fvjntylm.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gt2dxjslhpn.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gt2onzunsut.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gt2ilkdzqbm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gt2xsxhfowz.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gt2wkofdxlh.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gt2lfhsjiqn.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gt2rjmroeex.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenzaomai.com/Article/details/gt2lmkmuntm.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gt2sviibouo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnqzz.top/Article/details/gt2usnwniyp.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gt2cdwoysay.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2wkyzzfum.html

[T25] Swift：结构体
来源：http://dali.zhongyouzk.top/Article/details/gt2kbvyflqv.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2edhuoutp.html

[T26] Swift：类与重写
来源：http://dali.cucudq.cn/Article/details/gt2qdtsbwrc.html

class A: Base { override func f() {} }
来源：http://dali.ppjwa.cn/Article/details/gt2rkmqbzsa.html

[T27] Swift：错误处理
来源：http://dali.sxryk.cn/Article/details/gt2ycfgfktt.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gt2pgyafliw.html

[T28] Swift：枚举
来源：http://dali.yongpay.top/Article/details/gt2dqymhewn.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gt2uvatyibl.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gt2eyqxbbze.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gt2tdkddocl.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gt2uxcgtfju.html

protocol Shape { func area() -> Double }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqeetwav.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2tcnqjxai.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2zrmvkhyx.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gt2mywcxkow.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gt2sajhrefx.html

[T33] Lua：表（数组）
来源：http://dali.zdqjudy.top/Article/details/gt2fdwboltq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.havefunace.top/Article/details/gt2ibvsvxov.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gt2nwxmdcho.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gt2gfdsdvpw.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gt2lhjjvrtf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.redwolf501.top/Article/details/gt2mjnxuqse.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gt2pustgqni.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gt2lgobprmj.html

[T37] Lua：字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2brzybhgo.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gt2xunmjadt.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gt2evwcqgls.html

if x > 0 then print("正") end
来源：http://dali.aibaodan.cn/Article/details/gt2iewtxeht.html

[T39] Lua：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gt2vfookkvm.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gt2szcrdjun.html

[T40] Lua：元表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ueexduim.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gt2qkbgsujm.html

[T41] Perl：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2ncpsttkk.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gt2ouvonliv.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gt2ysfvdepg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fengsongda.top/Article/details/gt2ltalnytb.html

[T43] Perl：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2gazmqixz.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gt2bklupfyg.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gt2vlqayzkz.html

if ($a > 0) { print "正"; }
来源：http://dali.pycfn.com/Article/details/gt2mlugawem.html

[T45] Perl：数组遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2rndgtodt.html

for my $x (@arr) { print $x; }
来源：http://dali.gotoacloud.top/Article/details/gt2cdbqcbxy.html

[T46] Perl：哈希操作
来源：http://dali.sxryk.cn/Article/details/gt2wltpdutz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyxcjumt.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gizftnhg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gt2gmoepbby.html

[T48] Perl：正则替换
来源：http://dali.cucudq.cn/Article/details/gt2xvjipoxa.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gt2hfolgbqv.html

[T49] Perl：函数
来源：http://dali.zhengqikj.top/Article/details/gt2obsgorbb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcillabi.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2rtbhqacb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvyrbvxp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnqzz.top/Article/details/gt2jlbhpqvv.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2olextzhj.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gt2chycezrm.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlrivrhc.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gt2zajschxz.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gt2lhyqdszf.html

s"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2mjjvetwy.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gt2gssayobr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aizwys.cn/Article/details/gt2gyrsncio.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gt2fhimxdap.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yonumen.top/Article/details/gt2pcrlthoe.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gt2ncrqyxjv.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gt2bmpyxdoe.html

[T57] Scala：模式匹配
来源：http://dali.shuidangran.top/Article/details/gt2hvpwmbek.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gt2sirfgfsk.html

[T58] Scala：函数定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2ugdrywdt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cqqwz.cn/Article/details/gt2gzglolyf.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2nalerkqv.html

for (i <- 1 to 10) println(i)
来源：http://dali.xziqi.cn/Article/details/gt2fbraubam.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gt2cqifdyun.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gt2optyabqn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqearapp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2gtrqkpzm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2npkhpali.html

[U01] Py：创建虚拟环境
来源：http://dali.hnqzz.top/Article/details/gt2fxmdpedv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhixingplan.top/Article/details/gt2nkijguza.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gt2kfsxjxfb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cqqwz.cn/Article/details/gt2auwrcoik.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gt2emswfmnt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gt2ststpmow.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwvgmjqp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dashuyun.cn/Article/details/gt2rjmmtpae.html

[U05] Py：列表去重且保序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfyxewxv.html

list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gt2yatrfuyu.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gt2zqqokfxm.html

{**a, **b}
来源：http://dali.hywenlv.cn/Article/details/gt2spuktxfu.html

[U07] Py：反转字典键值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzidrffp.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gt2udimczqr.html

[U08] Py：展平二维列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqeejagz.html

[y for x in nested for y in x]
来源：http://dali.cheryme.top/Article/details/gt2kvliibga.html

[U09] Py：字典取最大值的键
来源：http://dali.xylfe.cn/Article/details/gt2gelsxgwg.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gt2rfmocigj.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gt2twwyjrvq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhixingplan.top/Article/details/gt2lriuuknq.html

[U11] Py：生成器表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahwdxquw.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gt2sllybrns.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gt2cnzvjtdt.html

Counter(arr).most_common(3)
来源：http://dali.birdmap.top/Article/details/gt2jkqsovyv.html

[U13] Py：固定长度队列
来源：http://dali.redwolf501.top/Article/details/gt2atafyiwe.html

deque(maxlen=10)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpqujfhp.html

[U14] Py：分组收集到列表
来源：http://dali.kuanghao11.cn/Article/details/gt2gtkpfrve.html

defaultdict(list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbysyznw.html

[U15] Py：高精度计时
来源：http://dali.sweek.top/Article/details/gt2txywoxjr.html

t = time.perf_counter()
来源：http://dali.hammf.cn/Article/details/gt2nlucgebn.html

[U16] Py：命令行参数解析
来源：http://dali.cheryme.top/Article/details/gt2abcjofak.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxljtacn.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gt2cuqqfttx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenzaomai.com/Article/details/gt2ladqtgwk.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2likfmsty.html

pat = re.compile(r"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2hnmleaxi.html

[U19] Py：正则替换带回调
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwytxxet.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yangfankeji.com/Article/details/gt2nxxlkvjl.html

[U20] Py：缓存函数结果
来源：http://dali.ehwqpu.com/Article/details/gt2ypzzghpo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqicvych.html

[U21] Py：自定义上下文管理器
来源：http://dali.jyoumei.cn/Article/details/gt2vwddaeow.html

@contextlib.contextmanager
来源：http://dali.tianlin.xyz/Article/details/gt2djyldhku.html

[U22] Py：矩阵转置
来源：http://dali.9152youxi.cn/Article/details/gt2kbtgtpym.html

list(zip(*m))
来源：http://dali.zhoulong.xyz/Article/details/gt2cgmvkymx.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gt2mdtqlvvl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.vqdsnc.cn/Article/details/gt2lwoszckr.html

[U24] Py：路径操作
来源：http://dali.hammf.cn/Article/details/gt2bvipxmuw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzsuhhre.html

[U25] Py：CSV 按字典读
来源：http://dali.mhx1999.top/Article/details/gt2mkngthyr.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpudlooh.html

[U26] Py：并发下载
来源：http://dali.jyoumei.cn/Article/details/gt2qkundiar.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fzhhl.top/Article/details/gt2qkaxhnpo.html

[U27] Py：异步 HTTP
来源：http://dali.chenzaomai.com/Article/details/gt2pogchwoi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ehwqpu.com/Article/details/gt2udcyxqxz.html

[U28] Py：类型别名
来源：http://dali.gotoacloud.top/Article/details/gt2tidonbfy.html

UserId = int
来源：http://dali.svipenyu.cn/Article/details/gt2fmfsuyre.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gt2dpepdsfe.html

@property 与 @x.setter 配合
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwvsawin.html

[U30] Py：数据类
来源：http://dali.jinqigufen.top/Article/details/gt2whlzoghu.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gt2lqmsvjho.html

[U31] Py：单测
来源：http://dali.jinqigufen.top/Article/details/gt2krqqcisl.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gt2deviluon.html

[U32] Py：代码格式化
来源：http://dali.gzhubu.top/Article/details/gt2ugtqaxfd.html

ruff format . && ruff check --fix .
来源：http://dali.hammf.cn/Article/details/gt2cujnhvvf.html

[U33] Py：打包发布
来源：http://dali.jyoumei.cn/Article/details/gt2ztbbkvvc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gt2oerflzos.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gt2vuaiidsz.html

chardet.detect(raw)
来源：http://dali.zhoulong.xyz/Article/details/gt2iybzehmn.html

[U35] Py：发送邮件
来源：http://dali.hnxiangtu.top/Article/details/gt2rwmztxld.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hfpthk.cn/Article/details/gt2tgaimbty.html

[U36] Py：定时任务
来源：http://dali.tianlin.xyz/Article/details/gt2eqlgtrcj.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuetiantiany.cn/Article/details/gt2usstsobs.html

[U37] Py：读写 Excel
来源：http://dali.redwolf501.top/Article/details/gt2hoohppol.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gt2lblurixz.html

[U38] Py：获取脚本所在目录
来源：http://dali.bjfxy.top/Article/details/gt2kzxshtsj.html

Path(__file__).resolve().parent
来源：http://dali.yueranfly.top/Article/details/gt2lbygrmva.html

[U39] Py：判断是否在交互环境
来源：http://dali.jlsjyb.cn/Article/details/gt2qizyodak.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gt2zdztuvtg.html

[U40] Py：打印到标准错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdpzabgx.html

print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gt2dxcppyud.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.snrcjt.cn/Article/details/gt2kholynof.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxinkj.top/Article/details/gt2hjtgtfsj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhengqikj.top/Article/details/gt2vpdrpopl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gzhubu.top/Article/details/gt2pnlbxtcl.html

[U43] PHP：声明命名空间
来源：http://dali.cucudq.cn/Article/details/gt2kclycbcs.html

namespace App\Http;
来源：http://dali.sxryk.cn/Article/details/gt2nqqfbown.html

[U44] PHP：开启严格类型
来源：http://dali.hywenlv.cn/Article/details/gt2vhdvccag.html

declare(strict_types=1);
来源：http://dali.havefunace.top/Article/details/gt2xqigrboq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gt2uzrgvsom.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2sltzbziu.html

[U46] PHP：可空类型
来源：http://dali.shuidangran.top/Article/details/gt2ulwatylf.html

?string $name = null
来源：http://dali.aizwys.cn/Article/details/gt2epujniwe.html

[U47] PHP：联合类型
来源：http://dali.quarkkingdee.top/Article/details/gt2rjhdphyd.html

int|string $id
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyuwyfyf.html

[U48] PHP：纯枚举
来源：http://dali.316326.xyz/Article/details/gt2bsikpxme.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shzxlz.cn/Article/details/gt2uegcmuje.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ytskcpnt.html

public readonly string $name
来源：http://dali.yanxiufei.cn/Article/details/gt2dvdxuoqd.html

[U50] PHP：构造器属性提升
来源：http://dali.xuanzx.com/Article/details/gt2jsqbssqv.html

public function __construct(private int $id) {}
来源：http://dali.yuxming.cn/Article/details/gt2mjzqqnak.html

[U51] PHP：数组解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knorfitm.html

[$a, $b] = $arr;
来源：http://dali.shzxlz.cn/Article/details/gt2wjfgotdy.html

[U52] PHP：箭头函数
来源：http://dali.xinyue.icu/Article/details/gt2kfvlstre.html

$double = fn($x) => $x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gztifunk.html


<!-- 参考信息 -->