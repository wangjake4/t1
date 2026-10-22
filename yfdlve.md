代发 wailian999

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gt2ufsvnkus.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gt2rpzzwcwv.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gt2zeygusjt.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gt2tozowkvg.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gt2iufohxjh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gt2vooifxpa.html

[S34] C++：遍历 vector
来源：http://dali.sufxvd.cn/Article/details/gt2ujkpkwsm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gt2mstxpmpu.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyilizuw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2vcxqomic.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gt2pnaothyg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2tiykxtxo.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gt2dcdcfjyn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gt2acinkfzo.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gt2cdozohue.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gt2ptmnkzol.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2qliadcfb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gt2xknothae.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gt2eydkghsp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqrydbdz.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gt2kfnebefu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gt2rpomwzex.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gt2tnlctcuq.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gt2fynndvpn.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gt2wbrzaupq.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gt2swwdhabi.html

[S44] C++：引用传参
来源：http://dali.quarkkingdee.top/Article/details/gt2sbjpnnct.html

void inc(int &x) { ++x; }
来源：http://dali.yvedp.cn/Article/details/gt2gddnbweq.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gt2ptwspcxr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gt2qednvkao.html

[S46] C++：函数模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtbbvlxt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gt2cckyxcaz.html

[S47] C++：结构化绑定遍历
来源：http://dali.snrcjt.cn/Article/details/gt2poqxxbxi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gt2ukbccins.html

[S48] C++：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2davieyyy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gt2jkklofmf.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gt2ggrbzxjn.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2liqwjakg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gt2tpiwyizg.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gt2kiitrjwp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2pvixtfce.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gt2xohiupvg.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gt2fsevonsi.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gt2iuooxfwq.html

int size() const noexcept { return n_; }
来源：http://dali.jyoumei.cn/Article/details/gt2omwspslz.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gt2qhdwndsi.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gt2wwpqguqw.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gt2luwdsxbg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gogol.net.cn/Article/details/gt2mskcvzdy.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gt2qwktmkwb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gt2yygilcyg.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pabdzysj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhixingplan.top/Article/details/gt2xbzfafly.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gt2hikiycye.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gt2spkziwaf.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gt2tjiefhvq.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gt2fryzgssb.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gt2oigszjww.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yylkstzt.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gt2bsjthalr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2iwhslnvo.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ykfylvra.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gt2ofmnbmho.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2vtoqzusk.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2qrucicgz.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2uutbjwyl.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gt2ufvfdqzp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gt2bbimgdqz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvbmixp.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gt2lxrxcsea.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gt2fcxjbcbk.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gt2bmbsewzv.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gt2nvjdextt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gt2akkghhmz.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gt2sgzhbrtp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gt2dnjgrlqy.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gt2mierhmis.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gt2ltcjmykn.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2alitlmit.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2balaffhv.html

[T09] Kotlin：扩展函数
来源：http://dali.xinyue.icu/Article/details/gt2qipqfqhg.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gt2icgqgtyi.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gt2zqkluvfm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gt2wndrlfun.html

[T11] Kotlin：协程
来源：http://dali.sweek.top/Article/details/gt2jxghcvqe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vitfgmtf.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gt2rfjhukrr.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2afeugrug.html

[T13] Kotlin：只读 Map
来源：http://dali.nwbrower.top/Article/details/gt2dlrwbzrs.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gt2fputpipk.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gt2bccitcbk.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gt2buwvuuxr.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gt2wicfdual.html

interface Shape { fun area(): Double }
来源：http://dali.yvedp.cn/Article/details/gt2pqhwnlov.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gt2xndzbkhz.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2joobsrrf.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gt2jcckwisn.html

var a = 1;  let b = 2
来源：http://dali.yuanzhike.top/Article/details/gt2qownfavp.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvomaobn.html

"值: \(b)"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehkilvxb.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gt2cpsxlzwd.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gt2xeikfbyn.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2nikjmmia.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gt2fgnwkqbb.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2desjaxlt.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gt2yxycfhti.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gt2xojlmrmh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gt2afpwjruu.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gt2mpdbacea.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2rnuxkeov.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gt2ahuqelwi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsqbgrzz.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gt2fjnssejf.html

struct P { var x: Int }
来源：http://dali.quarkkingdee.top/Article/details/gt2bhsvcojx.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gt2fgqfthks.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gt2xrpbfbhi.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gt2qhsfirrm.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gt2uecrjlvt.html

[T28] Swift：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqyaxkzw.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gt2ntmdoguz.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gt2rkoelbwm.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gt2hytxhizv.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gt2ccxwencd.html

protocol Shape { func area() -> Double }
来源：http://dali.ehwqpu.com/Article/details/gt2jnoeomzf.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2lzoqdovj.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2avnantvm.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpihnhae.html

local a = 1
来源：http://dali.nanxinkj.top/Article/details/gt2ijaswjia.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gt2iehhnywx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhixingplan.top/Article/details/gt2tajrdmtq.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gt2nlxiowvj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.havefunace.top/Article/details/gt2uerxhhaq.html

[T35] Lua：字典表
来源：http://dali.jianghu66.top/Article/details/gt2lasyhfxf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxinkj.top/Article/details/gt2eduzsoja.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gt2feebccsf.html

function add(a, b) return a + b end
来源：http://dali.andypj.xyz/Article/details/gt2obflgkzv.html

[T37] Lua：字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2gldhkwdo.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gt2rbtiryjq.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gt2vzzlcoir.html

if x > 0 then print("正") end
来源：http://dali.fzhhl.top/Article/details/gt2ozsmttkf.html

[T39] Lua：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfgscizr.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gt2kcjnjuup.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewkxaaph.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gt2xndnsxpc.html

[T41] Perl：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2rbgtnqku.html

print "Hello\n";
来源：http://dali.havefunace.top/Article/details/gt2hvzpkrbm.html

[T42] Perl：变量类型
来源：http://dali.svipenyu.cn/Article/details/gt2qpragqjj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aizwys.cn/Article/details/gt2xfhiggoi.html

[T43] Perl：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gt2qprsntzj.html

"值: $a"
来源：http://dali.yuanzhike.top/Article/details/gt2sgxfusbi.html

[T44] Perl：条件
来源：http://dali.vqdsnc.cn/Article/details/gt2gsyeyerp.html

if ($a > 0) { print "正"; }
来源：http://dali.andypj.xyz/Article/details/gt2tuwhkosi.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxqpjori.html

for my $x (@arr) { print $x; }
来源：http://dali.guowangkeji.top/Article/details/gt2xyndwmfg.html

[T46] Perl：哈希操作
来源：http://dali.cqqwz.cn/Article/details/gt2fjldzivh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gt2pxeyzipw.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gt2ysjdsxwo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fengsongda.top/Article/details/gt2kmtwbyyv.html

[T48] Perl：正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfwdwagw.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gt2vxhswsbn.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gt2cgumkayc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2mklwevgi.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2ptrkssdf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gt2pubhpjex.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gt2kxyysiyo.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2oaldqilm.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2ktnqobxq.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gt2qbfiwfda.html

val a = 1;  var b = 2
来源：http://dali.yongpay.top/Article/details/gt2vzdsoapt.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2vjuelmje.html

s"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gt2gzastutd.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gifkkzbc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2hilzigop.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2hgxjfqvh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gt2rufqlthn.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gt2kqywmoyd.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gt2swfdjnxz.html

[T57] Scala：模式匹配
来源：http://dali.jianghu66.top/Article/details/gt2ewnzckhw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mijbrmwa.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gt2dtmpfwst.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hfpthk.cn/Article/details/gt2fbzdhhif.html

[T59] Scala：循环
来源：http://dali.chenlongwang.top/Article/details/gt2ayxvefut.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gt2iyumeplx.html

[T60] Scala：折叠
来源：http://dali.jqgufenzy.top/Article/details/gt2iocpdlwu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dptmegpi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2qbhajupv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gt2tdrfeyfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uknzfrcp.html

[U01] Py：创建虚拟环境
来源：http://dali.ybcxt.top/Article/details/gt2wodwsvpy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gt2yrjoalmf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gt2ggvaviru.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gt2eunxghig.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gt2gkkgsyhm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gt2spfjtpso.html

[U04] Py：变量调试打印
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyqjoqfd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gt2hbecuokx.html

[U05] Py：列表去重且保序
来源：http://dali.snrcjt.cn/Article/details/gt2ysdtcqry.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gt2ipzdwvrm.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gt2krtwadym.html

{**a, **b}
来源：http://dali.tanke756.top/Article/details/gt2uxmnzywp.html

[U07] Py：反转字典键值
来源：http://dali.yj20258.top/Article/details/gt2ozoedhgn.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gt2svvtjwwk.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gt2tuajbdrg.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gt2yxuxlffn.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gt2obafvtyo.html

max(d, key=d.get)
来源：http://dali.daxiang520.top/Article/details/gt2lqlfvdke.html

[U10] Py：按值排序字典
来源：http://dali.gzhubu.top/Article/details/gt2dftvgxne.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxinkj.top/Article/details/gt2ktdcrrsr.html

[U11] Py：生成器表达式
来源：http://dali.guannengcc.top/Article/details/gt2wjqxtzsd.html

(x * 2 for x in arr)
来源：http://dali.iojbl.cn/Article/details/gt2ublmaisd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xinyue.icu/Article/details/gt2arcaxpdf.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gt2jiiyscmg.html

[U13] Py：固定长度队列
来源：http://dali.jiagoushi.top/Article/details/gt2vtdjiqgx.html

deque(maxlen=10)
来源：http://dali.cucudq.cn/Article/details/gt2omahavng.html

[U14] Py：分组收集到列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnheynjl.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbtzulpg.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gt2nhkdcxfk.html

t = time.perf_counter()
来源：http://dali.ivvv.top/Article/details/gt2sjriexxg.html

[U16] Py：命令行参数解析
来源：http://dali.ybcxt.top/Article/details/gt2wwtimgtw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gt2iucjzwrl.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gt2ppuznprn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenzaomai.com/Article/details/gt2levsmklm.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gt2irwgxkaa.html

pat = re.compile(r"\d+")
来源：http://dali.cashguo.top/Article/details/gt2yxrvhjmi.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gt2vdsmbsjl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gt2zzwldprh.html

[U20] Py：缓存函数结果
来源：http://dali.andypj.xyz/Article/details/gt2ldezdqaz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangdashe.top/Article/details/gt2zokltfgw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zycfv.cn/Article/details/gt2hxrectoi.html

@contextlib.contextmanager
来源：http://dali.guannengcc.top/Article/details/gt2dxvizrkx.html

[U22] Py：矩阵转置
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlpftgvt.html

list(zip(*m))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhzepwcr.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gt2nevrglsr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gt2vfjiifhb.html

[U24] Py：路径操作
来源：http://dali.sufxvd.cn/Article/details/gt2omoeuthn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gt2bzniltcn.html

[U25] Py：CSV 按字典读
来源：http://dali.sufxvd.cn/Article/details/gt2kvwrnvbb.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gt2toxtwifm.html

[U26] Py：并发下载
来源：http://dali.yueranfly.top/Article/details/gt2hmtnitvq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sknnxpdw.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gt2otvegtid.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odhdeewd.html

[U28] Py：类型别名
来源：http://dali.daxiang520.top/Article/details/gt2fjljkoge.html

UserId = int
来源：http://dali.ydzc1.top/Article/details/gt2qoaudsgq.html

[U29] Py：属性校验
来源：http://dali.smart0.xyz/Article/details/gt2wrrizlyy.html

@property 与 @x.setter 配合
来源：http://dali.andypj.xyz/Article/details/gt2phksamxu.html

[U30] Py：数据类
来源：http://dali.gogol.net.cn/Article/details/gt2xfdxmxlk.html

@dataclass(slots=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2foknxfpc.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjzyuphk.html

python -m pytest -q
来源：http://dali.dianchejie.cn/Article/details/gt2ljtpesgw.html

[U32] Py：代码格式化
来源：http://dali.zhengqikj.top/Article/details/gt2wanavpbz.html

ruff format . && ruff check --fix .
来源：http://dali.sufxvd.cn/Article/details/gt2kbmyopdj.html

[U33] Py：打包发布
来源：http://dali.nanxuanxn.top/Article/details/gt2zgqgruox.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cdnleiting.top/Article/details/gt2jsvzylms.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gt2buuklqaq.html

chardet.detect(raw)
来源：http://dali.c1oappe.top/Article/details/gt2tdsdjqiv.html

[U35] Py：发送邮件
来源：http://dali.ehwqpu.com/Article/details/gt2dyzdwooi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gzhubu.top/Article/details/gt2sqqjxcby.html

[U36] Py：定时任务
来源：http://dali.ybcxt.top/Article/details/gt2jbkpwrzu.html

schedule.every(10).minutes.do(job)
来源：http://dali.yonumen.top/Article/details/gt2fstoltyu.html

[U37] Py：读写 Excel
来源：http://dali.zhongyouzk.top/Article/details/gt2vkazbwsh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tian-w.cn/Article/details/gt2yntsyxah.html

[U38] Py：获取脚本所在目录
来源：http://dali.316326.xyz/Article/details/gt2mwkzaxig.html

Path(__file__).resolve().parent
来源：http://dali.nanxinkj.top/Article/details/gt2qbliafbo.html

[U39] Py：判断是否在交互环境
来源：http://dali.tianlin.xyz/Article/details/gt2chlqggdq.html

sys.stdout.isatty()
来源：http://dali.gotoacloud.top/Article/details/gt2lgolzmyu.html

[U40] Py：打印到标准错误
来源：http://dali.vqdsnc.cn/Article/details/gt2nikeydea.html

print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gt2bzgnazbi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yonumen.top/Article/details/gt2swkyculh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pycfn.com/Article/details/gt2jocdtbve.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.iojbl.cn/Article/details/gt2wmkbnjvu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yongpay.top/Article/details/gt2ssvwirqb.html

[U43] PHP：声明命名空间
来源：http://dali.xylfe.cn/Article/details/gt2cjejznic.html

namespace App\Http;
来源：http://dali.wangshuangyany.cn/Article/details/gt2giskxkkl.html

[U44] PHP：开启严格类型
来源：http://dali.xziqi.cn/Article/details/gt2chxehwvj.html

declare(strict_types=1);
来源：http://dali.jyoumei.cn/Article/details/gt2fbacoiis.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2irlqrtqd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kyuiuact.html

[U46] PHP：可空类型
来源：http://dali.ybcxt.top/Article/details/gt2rfcpjgrx.html

?string $name = null
来源：http://dali.xuetiantiany.cn/Article/details/gt2xccgotdp.html

[U47] PHP：联合类型
来源：http://dali.jiagoushi.top/Article/details/gt2fspxovxb.html

int|string $id
来源：http://dali.birdmap.top/Article/details/gt2jlnznewa.html

[U48] PHP：纯枚举
来源：http://dali.hywenlv.cn/Article/details/gt2xefigpsx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.havefunace.top/Article/details/gt2kahongho.html

[U49] PHP：只读属性
来源：http://dali.jqgufenzy.top/Article/details/gt2evkxphry.html

public readonly string $name
来源：http://dali.zhengqikj.top/Article/details/gt2khulknyi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhengqikj.top/Article/details/gt2kgspvoxu.html

public function __construct(private int $id) {}
来源：http://dali.yj202588.top/Article/details/gt2pipcijme.html

[U51] PHP：数组解构
来源：http://dali.yangfankeji.com/Article/details/gt2ywncevld.html

[$a, $b] = $arr;
来源：http://dali.hysaishi.cn/Article/details/gt2upaiaqjq.html

[U52] PHP：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gt2yiafcvvc.html

$double = fn($x) => $x * 2;
来源：http://dali.yangfankeji.com/Article/details/gt2vnpxxytr.html

[U53] PHP：空合并运算符
来源：http://dali.ivvv.top/Article/details/gt2vticwdgv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gt2smjqwgdg.html

[U54] PHP：空安全调用
来源：http://dali.ydzc1.top/Article/details/gt2wpzqfsta.html

$obj?->method()
来源：http://dali.yongpay.top/Article/details/gt2ntgayqya.html

[U55] PHP：match 表达式
来源：http://dali.yongpay.top/Article/details/gt2msdudhsy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdmyxkfa.html

[U56] PHP：命名参数
来源：http://dali.redwolf501.top/Article/details/gt2mskxkqms.html

f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2rohugbwk.html


<!-- 参考信息 -->