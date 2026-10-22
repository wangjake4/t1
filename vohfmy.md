代发 wailian999

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2foxooaiw.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gt2ncmukzww.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.c1oappe.top/Article/details/gt2nnassjhg.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gt2tkcqinfm.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shkcinxj.html

#define X_H
来源：http://dali.cqqwz.cn/Article/details/gt2cmdvnoos.html

#endif
来源：http://dali.sysykeji.top/Article/details/gt2ichvmizj.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfqvdfuf.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gt2afkyetcj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2adbnodin.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2qjchwami.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gt2eeaawuud.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gt2lwrehfkr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gt2pdztdblt.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gt2qnjpcoza.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxszyqcu.html

[S35] C++：map
来源：http://dali.yanxiufei.cn/Article/details/gt2ydidhrlc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2xmiqjgtn.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gt2ooonzkwh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2bvetvqes.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gt2sbbrekle.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gt2jdfyafqw.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gt2bcjpuapw.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gt2qldsanbs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gt2mkcxzlix.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gt2baujhbik.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gt2abdioicr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gt2niddfixd.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nauqtxns.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gt2yewrflgs.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrdkqyiq.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gt2umoyjdxv.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gt2diyvozqc.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gt2zswukppi.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gt2nytjvzib.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gt2oycoclsx.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gt2nphzxogx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gt2jdajoyty.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gt2ungftzki.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pnjtqkxs.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gt2tixttbpn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gt2rbxjvhbv.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2sujrhdgl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gt2gvrnfusa.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbreqfny.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgffhavc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlyrsoyr.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pigjpate.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2mzeyjoiw.html

[S51] C++：显式类型转换
来源：http://dali.xylfe.cn/Article/details/gt2okxgrivo.html

static_cast<double>(a) / b
来源：http://dali.zhongyouzk.top/Article/details/gt2wwzyhtga.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gt2yoaxmqzj.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gt2aabqehiv.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oekrovvn.html

std::vector<int> w = std::move(v);
来源：http://dali.ppjwa.cn/Article/details/gt2uphjtatx.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gt2hajjcrlc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlbqruxr.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gt2athrmwhc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gt2eeowhmho.html

[S56] C++：optional
来源：http://dali.jiagoushi.top/Article/details/gt2brczcwej.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gt2euwmvpxa.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gt2tlfaplae.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2xsxabukq.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gt2wvwqlzht.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gt2hpcfepgi.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gt2xykvhmup.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gt2mtspygim.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gt2ydjevrhp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2qlarmpqy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2qwcoxckp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gt2bnthjnid.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2sworlmle.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmdppgrj.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2eurybllp.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gt2znoteyil.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cashguo.top/Article/details/gt2zhmqghjo.html

[T03] Kotlin：字符串模板
来源：http://dali.tanke756.top/Article/details/gt2gdpfomsq.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gt2nrkzpisd.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gt2uhgrpcav.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbqtgtee.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2tqdimifz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pycfn.com/Article/details/gt2rfplvuam.html

[T06] Kotlin：集合映射
来源：http://dali.dianchejie.cn/Article/details/gt2pogatabb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gt2mdohranq.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2txkbgdil.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gt2uiiqxloo.html

[T08] Kotlin：数据类
来源：http://dali.yanxiufei.cn/Article/details/gt2yuqvzmrs.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gt2cmrqmfuv.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gt2jfnkaweq.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gt2fnxseqsu.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gt2wwknbtap.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gt2kmqitrdc.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtuiagam.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gt2jfcwhpdp.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gt2kuvkgnym.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2ojiyrjlc.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gt2ywecrzbe.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2fatryvoz.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gt2lnbsyeyh.html

for (i in 1..10) println(i)
来源：http://dali.iojbl.cn/Article/details/gt2aruheafo.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gt2pzyyvvng.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gt2xuipgarv.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2xarydbyn.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2yqrbqbcs.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gt2bgojljvh.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gt2hbiezhgp.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2auwdpifg.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gt2wopbmrua.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gt2ribckdwz.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gt2cjbhxxpk.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gt2ubnkchqm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sysykeji.top/Article/details/gt2xcwfqtab.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gt2fkyullec.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gt2wbhjrwbn.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gt2xmfuouag.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gt2ffrpjcmm.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkpgofrf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shuidangran.top/Article/details/gt2pfyquklp.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gt2klwkgxxi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gt2snqsirkb.html

[T25] Swift：结构体
来源：http://dali.ivvv.top/Article/details/gt2mmkozsia.html

struct P { var x: Int }
来源：http://dali.guannengcc.top/Article/details/gt2ufwitggs.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixwyngzv.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gt2ioxzutzf.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gt2haesjfrb.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gt2akqjifai.html

[T28] Swift：枚举
来源：http://dali.shuidangran.top/Article/details/gt2syemxwuu.html

enum Color { case red, green }
来源：http://dali.gogol.net.cn/Article/details/gt2sqprsjnw.html

[T29] Swift：guard 提前返回
来源：http://dali.ivvv.top/Article/details/gt2xfkioppu.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gt2riisuddp.html

[T30] Swift：协议
来源：http://dali.nwbrower.top/Article/details/gt2gonuvisr.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gt2tawrrzbf.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2ufpevurd.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2rtmodsni.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gt2btgwlfvw.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2thootkau.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gt2hgyqhvdp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gt2gpvbmqoa.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gt2doaoxhlt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gt2wvicmrgk.html

[T35] Lua：字典表
来源：http://dali.jianghu66.top/Article/details/gt2zdyiwrlz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2epumzjsk.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gt2stvbomhl.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gt2orwdlogp.html

[T37] Lua：字符串拼接
来源：http://dali.yonumen.top/Article/details/gt2ldogmvsk.html

"a" .. "b"
来源：http://dali.tanke756.top/Article/details/gt2ubqwyiir.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gt2hrnrjwhw.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gt2neluaeld.html

[T39] Lua：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2umwpbnib.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gt2hgkhlgld.html

[T40] Lua：元表
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjbnsthe.html

setmetatable({}, { __index = base })
来源：http://dali.ppjwa.cn/Article/details/gt2qrwsudpr.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gt2tgqvuacm.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gt2cedhqsrc.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2xgyuqwap.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2qhczhspt.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gt2chippnha.html

"值: $a"
来源：http://dali.cucudq.cn/Article/details/gt2eegvdury.html

[T44] Perl：条件
来源：http://dali.dianchejie.cn/Article/details/gt2trupbftm.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gt2kkmsgder.html

[T45] Perl：数组遍历
来源：http://dali.dashuyun.cn/Article/details/gt2mggkafca.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gt2xgmgdmgg.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gt2owhyjzbs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2atbwxwpa.html

[T47] Perl：正则捕获
来源：http://dali.svipenyu.cn/Article/details/gt2lndfufdg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuxming.cn/Article/details/gt2awjfnazo.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2fwsusqzf.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gt2cmlmqnpm.html

[T49] Perl：函数
来源：http://dali.sweek.top/Article/details/gt2zwnowghs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2iwfrzrfo.html

[T50] Perl：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2vawycsmc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gt2ngxcnvsn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yongpay.top/Article/details/gt2mhxphagw.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dxvzndlw.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2dkvktofp.html

[T52] Scala：变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2khacvukm.html

val a = 1;  var b = 2
来源：http://dali.xuanzx.com/Article/details/gt2loowhoco.html

[T53] Scala：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2wpminiau.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2kvtcqjeq.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gt2rkfjxlce.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sysykeji.top/Article/details/gt2mnklgbla.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2oybtzltw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gt2yhdctdwe.html

[T56] Scala：样例类
来源：http://dali.hysaishi.cn/Article/details/gt2rimiccil.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gt2boisczdv.html

[T57] Scala：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gt2lcnvddhz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gt2ngkfndqu.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gt2gjxgameq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxuanxn.top/Article/details/gt2ggdcbzds.html

[T59] Scala：循环
来源：http://dali.yj20258.top/Article/details/gt2cyxrhycz.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gt2mfdmqext.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gt2mqjpnktz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixbsxnic.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2yvcjjykw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gt2hemnyxev.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2epmamdlm.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gt2itbcwzzf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gt2omhqyxdu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjabswtw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yueranfly.top/Article/details/gt2gbaazgjr.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gt2qknyvtxy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztinokla.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gt2mgomybkn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gt2xcdtvxma.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsxnmvni.html

list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gt2ejjhyaiz.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gt2exkjfvsy.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gt2jbtubqjo.html

[U07] Py：反转字典键值
来源：http://dali.guowangkeji.top/Article/details/gt2xllxjkab.html

{v: k for k, v in d.items()}
来源：http://dali.ppjwa.cn/Article/details/gt2igedcuba.html

[U08] Py：展平二维列表
来源：http://dali.sxryk.cn/Article/details/gt2houhahdw.html

[y for x in nested for y in x]
来源：http://dali.jlsjyb.cn/Article/details/gt2gajekmbe.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gt2uguwcwrs.html

max(d, key=d.get)
来源：http://dali.9152youxi.cn/Article/details/gt2tmkffcox.html

[U10] Py：按值排序字典
来源：http://dali.hywenlv.cn/Article/details/gt2zvnoxfre.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shzxlz.cn/Article/details/gt2lgftlrtt.html

[U11] Py：生成器表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2ugrgbvio.html

(x * 2 for x in arr)
来源：http://dali.shzxlz.cn/Article/details/gt2cyrpifhz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gt2vfivxift.html

Counter(arr).most_common(3)
来源：http://dali.zycfv.cn/Article/details/gt2aylmgwsk.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gt2kirjevua.html

deque(maxlen=10)
来源：http://dali.yuxming.cn/Article/details/gt2tgpldpqe.html

[U14] Py：分组收集到列表
来源：http://dali.zhongyouzk.top/Article/details/gt2lsuhsmix.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gt2lglpyspc.html

[U15] Py：高精度计时
来源：http://dali.guannengcc.top/Article/details/gt2pwkugnud.html

t = time.perf_counter()
来源：http://dali.jyoumei.cn/Article/details/gt2eejfhmrm.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gt2oioytder.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.9152youxi.cn/Article/details/gt2tlrihetd.html

[U17] Py：初始化日志
来源：http://dali.nanxuanxn.top/Article/details/gt2cjkibpze.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yuanzhike.top/Article/details/gt2oibbsnvr.html

[U18] Py：预编译正则
来源：http://dali.wangdashe.top/Article/details/gt2tmytmfna.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2kfelbrzo.html

[U19] Py：正则替换带回调
来源：http://dali.gotoacloud.top/Article/details/gt2kvnsuynl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gt2cgathzxb.html

[U20] Py：缓存函数结果
来源：http://dali.cdnleiting.top/Article/details/gt2fjkelthd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yueranfly.top/Article/details/gt2kqwmfuvw.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gt2jxyqxikf.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gt2rlwzexfy.html

[U22] Py：矩阵转置
来源：http://dali.gzhubu.top/Article/details/gt2ouvgvoip.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gt2dyziznlx.html

[U23] Py：分块读取大文件
来源：http://dali.ivvv.top/Article/details/gt2mkyhgpvu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhongyouzk.top/Article/details/gt2jncpdnzs.html

[U24] Py：路径操作
来源：http://dali.haohaochexian.top/Article/details/gt2wkqtbqlh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2bnwazgwi.html

[U25] Py：CSV 按字典读
来源：http://dali.zycfv.cn/Article/details/gt2goouhqwx.html

csv.DictReader(f)
来源：http://dali.jinqigufen.top/Article/details/gt2bicbnfbq.html

[U26] Py：并发下载
来源：http://dali.yvedp.cn/Article/details/gt2zivkknex.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shuidangran.top/Article/details/gt2juxnriph.html

[U27] Py：异步 HTTP
来源：http://dali.yuanzhike.top/Article/details/gt2sujhvlhw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dianchejie.cn/Article/details/gt2ockaidki.html

[U28] Py：类型别名
来源：http://dali.yuanzhike.top/Article/details/gt2ecsqtilm.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gt2stwgjwdg.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gt2fqxaofse.html

@property 与 @x.setter 配合
来源：http://dali.sxryk.cn/Article/details/gt2hcokjdjp.html

[U30] Py：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gt2kioasira.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gt2wqjlktyl.html

[U31] Py：单测
来源：http://dali.sufxvd.cn/Article/details/gt2zxspaetr.html

python -m pytest -q
来源：http://dali.gaohongyu789.top/Article/details/gt2znmsfjvi.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybjbpucs.html

ruff format . && ruff check --fix .
来源：http://dali.smart0.xyz/Article/details/gt2vwyaqyqs.html

[U33] Py：打包发布
来源：http://dali.ybcxt.top/Article/details/gt2nmqfkeox.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gt2ywhppgnj.html

[U34] Py：判断编码
来源：http://dali.daria6918.cn/Article/details/gt2yvrtmaix.html

chardet.detect(raw)
来源：http://dali.redwolf501.top/Article/details/gt2cjrrygfg.html

[U35] Py：发送邮件
来源：http://dali.hnqzz.top/Article/details/gt2ljhekbmr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gt2mjsdydwo.html

[U36] Py：定时任务
来源：http://dali.hfpthk.cn/Article/details/gt2xsufqkkq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bphuqono.html

[U37] Py：读写 Excel
来源：http://dali.hnxiangtu.top/Article/details/gt2araeaotb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sweek.top/Article/details/gt2ttncyptj.html

[U38] Py：获取脚本所在目录
来源：http://dali.hfpthk.cn/Article/details/gt2szhymvyx.html

Path(__file__).resolve().parent
来源：http://dali.yj20258.top/Article/details/gt2bgsnmiww.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenlongwang.top/Article/details/gt2ukxgyjtt.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gt2nhodaluc.html

[U40] Py：打印到标准错误
来源：http://dali.cashguo.top/Article/details/gt2dqugdbdu.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2aexpdvtu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gt2ztcbuilt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zycfv.cn/Article/details/gt2mrogetai.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gt2aaiyagsu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gt2wxklouil.html

[U43] PHP：声明命名空间
来源：http://dali.ivvv.top/Article/details/gt2ksnfydaa.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gt2rftnmgvv.html

[U44] PHP：开启严格类型
来源：http://dali.chenlongwang.top/Article/details/gt2sudittji.html

declare(strict_types=1);
来源：http://dali.jiagoushi.top/Article/details/gt2syxnzvuy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cashguo.top/Article/details/gt2xjawhpzt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2yseinixy.html

[U46] PHP：可空类型
来源：http://dali.zdqjudy.top/Article/details/gt2ndsgozld.html

?string $name = null
来源：http://dali.fengsongda.top/Article/details/gt2gsszcrkg.html

[U47] PHP：联合类型
来源：http://dali.gotoacloud.top/Article/details/gt2jjnmwkqv.html

int|string $id
来源：http://dali.shangyingyoupin.top/Article/details/gt2odolxgfy.html

[U48] PHP：纯枚举
来源：http://dali.cheryme.top/Article/details/gt2blyvrbnf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daria6918.cn/Article/details/gt2kitrkboc.html

[U49] PHP：只读属性
来源：http://dali.zycfv.cn/Article/details/gt2ngjzcsvx.html

public readonly string $name
来源：http://dali.tian-w.cn/Article/details/gt2xnvwtpmg.html

[U50] PHP：构造器属性提升
来源：http://dali.guannengcc.top/Article/details/gt2xetdutyd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yecyfnan.html

[U51] PHP：数组解构
来源：http://dali.kuanghao11.cn/Article/details/gt2krnpmpon.html

[$a, $b] = $arr;
来源：http://dali.yonumen.top/Article/details/gt2yzpdqkhm.html

[U52] PHP：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqzhtbqq.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udkfsnme.html


<!-- 参考信息 -->