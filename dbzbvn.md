代发 wailian999

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hawnvzax.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gt2lrrpbwqe.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2pkhoykkc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gt2hgeyxflx.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gt2ukdgqfyk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gt2hnnwbfio.html

[S34] C++：遍历 vector
来源：http://dali.sxryk.cn/Article/details/gt2qcqmsxzs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gt2swrtzgyb.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gt2qkpipzus.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2wfmhdbyo.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gt2rphurbre.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2lsfxrgfc.html

[S37] C++：set
来源：http://dali.dianchejie.cn/Article/details/gt2qotnnrmu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwicyclp.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkhznqdm.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gt2qvgnkeft.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gt2gercfcbx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehuswhwl.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gt2gqqlzywg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gt2tzzlwlvg.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkgygdeh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gt2fqccrtbd.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258888.top/Article/details/gt2hvaznkog.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gt2hqmrljpb.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gt2egochkne.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvzsfiio.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gt2ompoumnx.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2fpqywktg.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mycgogqn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gt2jngalabs.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gt2dgwnpujt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gt2zqosfdam.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gt2bmwmzrjn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwvabfrz.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2qqmphdqj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gt2gqefhzcx.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2dguxbjwj.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gt2zxprpvdi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gt2nduqrteo.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gt2voxkaxna.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2chyojtpn.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gt2ozjqcnvs.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gt2xrgznhfd.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gt2ngusiita.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gt2gjdivgns.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gt2wbyvlrkt.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gt2slccbbom.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gt2qcyatdfv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gt2rhqrlung.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gt2hixlmoou.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2tdmdsmkh.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gt2xlpsxyjh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gt2xfhfcfpe.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gt2abyacmnx.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gt2qslrxiew.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gt2onqagczw.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gt2saadvqwt.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gt2xwhwfgpt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozjkypjt.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2hxqqyipf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gt2wxffubfg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2lzhhvluj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gt2rniquasf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2sauikzvx.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gt2pynxnxaw.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2nbvzmfal.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gt2keeatjoc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ydzc1.top/Article/details/gt2iiuofhoq.html

[T03] Kotlin：字符串模板
来源：http://dali.tianlin.xyz/Article/details/gt2epcxpxmh.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gt2gopzzanx.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gt2gbrxsbiy.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gt2xhobkllq.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigufen.top/Article/details/gt2zszvcdra.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gt2emjyvbif.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gt2vbphdsnr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2dprmkjca.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2hhuauuyk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gt2sptcgwkq.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gt2sibredld.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gt2xwbsdyhj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkyjjslx.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gt2hufzpzet.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gt2xlxaxbuj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2duhxxjhj.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gt2eupjqbjt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gt2lwfhzdth.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gt2ljfulnoy.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2izsbhcrk.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gt2rlvwdmfi.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gt2evcjlhox.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gt2bgdgatgc.html

for (i in 1..10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2msycfbga.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gt2afpzoxeo.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzoceitb.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2lsvstpex.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2fqzhzrxh.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gt2ujywdlrd.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gt2qitzrdar.html

[T18] Swift：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2tulhuegc.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gt2hylnsxka.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gt2oxwvtzoy.html

if let n = opt { print(n) }
来源：http://dali.sxryk.cn/Article/details/gt2ydjjgfds.html

[T20] Swift：数组操作
来源：http://dali.chenlongwang.top/Article/details/gt2dqaoqyqv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gt2bnofwhdx.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gt2tlrgvoph.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gt2bknctkrt.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gt2dkxdqkhk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gt2ywsupujy.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gt2ypjicnun.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gt2hpaccxdb.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gt2yqqzyata.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gt2qxtszbug.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gt2gdlebccm.html

struct P { var x: Int }
来源：http://dali.zhengqikj.top/Article/details/gt2konetomo.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gt2ciuxpbeu.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gt2esvhsebg.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2ozygdtty.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2duyqiqtv.html

[T28] Swift：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjzaqcmo.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gt2tbkejhjn.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gt2wzchpmag.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gt2bnqzvrqa.html

[T30] Swift：协议
来源：http://dali.9152youxi.cn/Article/details/gt2qrjhblkp.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gt2lzggaxas.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2digkqfin.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gt2pjxxrhob.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2aclcdqpj.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gt2nvqygjmn.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gt2muyatjsx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gt2xtcrxepq.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gt2ykaztvde.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gt2hmxdeeog.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gt2fmqxhkpn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gt2sfjessdk.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2jzlybmvq.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gt2bcdnvbbd.html

[T37] Lua：字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2ndwltyeq.html

"a" .. "b"
来源：http://dali.gaohongyu789.top/Article/details/gt2zcnwegqq.html

[T38] Lua：条件
来源：http://dali.yanxiufei.cn/Article/details/gt2xhxclrfp.html

if x > 0 then print("正") end
来源：http://dali.guowangkeji.top/Article/details/gt2cjdeztcu.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gt2zgeryvpo.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gt2itqwsndh.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gt2nxcurzlf.html

setmetatable({}, { __index = base })
来源：http://dali.fzhhl.top/Article/details/gt2gniycseg.html

[T41] Perl：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2jhfakymo.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gt2fumimpkr.html

[T42] Perl：变量类型
来源：http://dali.fzhhl.top/Article/details/gt2ammtescb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gt2kmeauzne.html

[T43] Perl：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gt2kivcpxzt.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gt2bpfukjys.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gt2dpdgyunv.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gt2xnvmfsrs.html

[T45] Perl：数组遍历
来源：http://dali.yj20258888.top/Article/details/gt2dfwlicmw.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gt2mpcrnwnf.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gt2pzvbgmde.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erogomex.html

[T47] Perl：正则捕获
来源：http://dali.yuanzhike.top/Article/details/gt2uzcvsegt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gt2tfxqqymr.html

[T48] Perl：正则替换
来源：http://dali.cashguo.top/Article/details/gt2acgjgjnt.html

$s =~ s/old/new/g;
来源：http://dali.daxiang520.top/Article/details/gt2jwbsvpkl.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gt2mefdomag.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2taipxyqc.html

[T50] Perl：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2dehjfbum.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gt2qgtnkhox.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gt2dyfmvfnh.html

[T51] Scala：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2imntazgn.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2ipynnijv.html

[T52] Scala：变量
来源：http://dali.ydzc1.top/Article/details/gt2uqwjzkfu.html

val a = 1;  var b = 2
来源：http://dali.yj20258.top/Article/details/gt2xkxtokmr.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2fdktbvfb.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gt2cebbilws.html

[T54] Scala：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2astuxwbp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gt2iffhtsfz.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gt2znqdityc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2jcujsbeh.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gt2tlnwxvnm.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gt2vrcqjxym.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2lsrpdtrq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gt2leynheto.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gt2hnvdgxmj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gt2vlhszchm.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iceqlwyi.html

for (i <- 1 to 10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gt2qiosluso.html

[T60] Scala：折叠
来源：http://dali.jianghu66.top/Article/details/gt2yrtmqwgt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gt2qszhtajp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvravcte.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gt2glpssglg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2hnlxwhtl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhongyouzk.top/Article/details/gt2bdiiywri.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrhonooq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gt2dysznrpi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gt2gmkardbi.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gt2sfbdlgce.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guowangkeji.top/Article/details/gt2hezerflb.html

[U04] Py：变量调试打印
来源：http://dali.sweek.top/Article/details/gt2nycnjgbd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gt2stuecfqo.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gt2umlxszzj.html

list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gt2zoqysoub.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gt2ostzkmzc.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gt2zdfjwiqw.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gt2mkdbqrvc.html

{v: k for k, v in d.items()}
来源：http://dali.havefunace.top/Article/details/gt2xpihcoqu.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehrjvfaa.html

[y for x in nested for y in x]
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzhfhnbt.html

[U09] Py：字典取最大值的键
来源：http://dali.cucudq.cn/Article/details/gt2cxjixoca.html

max(d, key=d.get)
来源：http://dali.hammf.cn/Article/details/gt2ibxjatbr.html

[U10] Py：按值排序字典
来源：http://dali.tianlin.xyz/Article/details/gt2ngctgwvp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gt2cshyhcmt.html

[U11] Py：生成器表达式
来源：http://dali.gogol.net.cn/Article/details/gt2dbygcepl.html

(x * 2 for x in arr)
来源：http://dali.xuanzx.com/Article/details/gt2qfjpozkc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jyoumei.cn/Article/details/gt2fnotglne.html

Counter(arr).most_common(3)
来源：http://dali.316326.xyz/Article/details/gt2fbxuszvs.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gt2exhetjsl.html

deque(maxlen=10)
来源：http://dali.jqgfzy.top/Article/details/gt2iconzlxu.html

[U14] Py：分组收集到列表
来源：http://dali.jianghu66.top/Article/details/gt2qnjogims.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gt2vwfvhqkg.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gt2kbptkaae.html

t = time.perf_counter()
来源：http://dali.smart0.xyz/Article/details/gt2ewpudxsu.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gt2ameefgvq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daxiang520.top/Article/details/gt2rpanyczt.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gt2jknbpimo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.redwolf501.top/Article/details/gt2ugjzuluy.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imexkebk.html

pat = re.compile(r"\d+")
来源：http://dali.fzhhl.top/Article/details/gt2atyygvlz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xkojejey.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2affngwpk.html

[U20] Py：缓存函数结果
来源：http://dali.0kj1m.cn/Article/details/gt2clajhmnp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tncucsnz.html

[U21] Py：自定义上下文管理器
来源：http://dali.aibaodan.cn/Article/details/gt2yxqlxqtj.html

@contextlib.contextmanager
来源：http://dali.yj20258.top/Article/details/gt2lfbmmeio.html

[U22] Py：矩阵转置
来源：http://dali.yongpay.top/Article/details/gt2zvxuvvkl.html

list(zip(*m))
来源：http://dali.tianlin.xyz/Article/details/gt2gzvmdmqw.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gt2fgmdugit.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnxiangtu.top/Article/details/gt2zpyifwfd.html

[U24] Py：路径操作
来源：http://dali.haohaochexian.top/Article/details/gt2gwumdvpn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2ubrwigvg.html

[U25] Py：CSV 按字典读
来源：http://dali.redwolf501.top/Article/details/gt2exsxtwks.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gt2tdwuhcjh.html

[U26] Py：并发下载
来源：http://dali.ehwqpu.com/Article/details/gt2hndkaxiw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhengqikj.top/Article/details/gt2wtssamlb.html

[U27] Py：异步 HTTP
来源：http://dali.gzhubu.top/Article/details/gt2zfwqbknl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yonumen.top/Article/details/gt2oczallnt.html

[U28] Py：类型别名
来源：http://dali.dashuyun.cn/Article/details/gt2qgbnjazc.html

UserId = int
来源：http://dali.zhixingplan.top/Article/details/gt2zqgdcknl.html

[U29] Py：属性校验
来源：http://dali.wangshuangyany.cn/Article/details/gt2trunxghd.html

@property 与 @x.setter 配合
来源：http://dali.kuanghao11.cn/Article/details/gt2sjbaxuli.html

[U30] Py：数据类
来源：http://dali.zycfv.cn/Article/details/gt2gfpchtlu.html

@dataclass(slots=True)
来源：http://dali.fzhhl.top/Article/details/gt2fmdcokxk.html

[U31] Py：单测
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnfdklfg.html

python -m pytest -q
来源：http://dali.xuetiantiany.cn/Article/details/gt2nciyxxqs.html

[U32] Py：代码格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpamtrxh.html

ruff format . && ruff check --fix .
来源：http://dali.pycfn.com/Article/details/gt2yjgdvfgm.html

[U33] Py：打包发布
来源：http://dali.redwolf501.top/Article/details/gt2azuocjdw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewcytflb.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gt2ndfhancb.html

chardet.detect(raw)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmlkuoic.html

[U35] Py：发送邮件
来源：http://dali.yonumen.top/Article/details/gt2rkulravm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258.top/Article/details/gt2wfxopnuk.html

[U36] Py：定时任务
来源：http://dali.birdmap.top/Article/details/gt2awzmwznw.html

schedule.every(10).minutes.do(job)
来源：http://dali.yangfankeji.com/Article/details/gt2kyvaypjm.html

[U37] Py：读写 Excel
来源：http://dali.shzxlz.cn/Article/details/gt2oevcgatr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czelzedp.html

[U38] Py：获取脚本所在目录
来源：http://dali.haohaochexian.top/Article/details/gt2jquhypre.html

Path(__file__).resolve().parent
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dubdrpat.html

[U39] Py：判断是否在交互环境
来源：http://dali.jiagoushi.top/Article/details/gt2kqdsuzco.html

sys.stdout.isatty()
来源：http://dali.jlsjyb.cn/Article/details/gt2pbqkujze.html

[U40] Py：打印到标准错误
来源：http://dali.jyoumei.cn/Article/details/gt2rmyjrszl.html

print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gt2ngwgehjv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangdashe.top/Article/details/gt2shdweaxd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgufenzy.top/Article/details/gt2mpcdetak.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.pengpengdd.cyou/Article/details/gt2padmvawv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cdnleiting.top/Article/details/gt2kvedalbx.html

[U43] PHP：声明命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gt2kecahkvu.html

namespace App\Http;
来源：http://dali.hnqzz.top/Article/details/gt2fkpkszdt.html

[U44] PHP：开启严格类型
来源：http://dali.quarkkingdee.top/Article/details/gt2vbzcobzp.html

declare(strict_types=1);
来源：http://dali.nanxuanxn.top/Article/details/gt2bhgmgcer.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nwbrower.top/Article/details/gt2pekydluj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2xsrfaoex.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unshmgvy.html

?string $name = null
来源：http://dali.quarkkingdee.top/Article/details/gt2jjvplrtr.html

[U47] PHP：联合类型
来源：http://dali.hysaishi.cn/Article/details/gt2xibsxdze.html

int|string $id
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gatfhvwq.html

[U48] PHP：纯枚举
来源：http://dali.fzhhl.top/Article/details/gt2nhzsbbac.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhixingplan.top/Article/details/gt2unzjrori.html

[U49] PHP：只读属性
来源：http://dali.zhixingplan.top/Article/details/gt2fcoacoon.html

public readonly string $name
来源：http://dali.yangfankeji.com/Article/details/gt2kfwkmtyz.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gt2ejisrptu.html

public function __construct(private int $id) {}
来源：http://dali.yonumen.top/Article/details/gt2pfooobqy.html

[U51] PHP：数组解构
来源：http://dali.smart0.xyz/Article/details/gt2efyftdzl.html

[$a, $b] = $arr;
来源：http://dali.sufxvd.cn/Article/details/gt2wqaliwcr.html

[U52] PHP：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gt2mbwaqqeg.html

$double = fn($x) => $x * 2;
来源：http://dali.zycfv.cn/Article/details/gt2dgdkdwgw.html

[U53] PHP：空合并运算符
来源：http://dali.hfpthk.cn/Article/details/gt2irqitfxd.html

$v = $a ?? $b ?? "default";
来源：http://dali.hammf.cn/Article/details/gt2cougljpo.html

[U54] PHP：空安全调用
来源：http://dali.wangdashe.top/Article/details/gt2ghwpfmqg.html

$obj?->method()
来源：http://dali.zdqjudy.top/Article/details/gt2kduuwber.html

[U55] PHP：match 表达式
来源：http://dali.nanxinkj.top/Article/details/gt2oapcthqb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.c1oappe.top/Article/details/gt2jqvvlwef.html

[U56] PHP：命名参数
来源：http://dali.zycfv.cn/Article/details/gt2qjrttkpe.html

f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gt2mhmofhfx.html


<!-- 参考信息 -->