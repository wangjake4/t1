代发 wailian999

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gt2fqmjnhfd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gt2tgppnwge.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gt2wgmnhleq.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gt2ryyczpis.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gt2ofxedtfh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2sbxavaaf.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gt2cymbuher.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfgwjtyd.html

[S35] C++：map
来源：http://dali.hysaishi.cn/Article/details/gt2lmorzdin.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2gxhgvmcf.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gt2zxptofrk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2hljyavpy.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gt2uoqhuwqe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gt2qgvpmidz.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gt2nngllkeo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2azmrhoyd.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gt2ywyeblze.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gt2esctbdkv.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gt2xwacaeya.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdympbxd.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gt2quetxngz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gt2lxihwtet.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gt2mujvxtei.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gt2xntjsjhx.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqbcnonp.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gt2sbjkzbdb.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gt2nudqwnpr.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gt2zbzyqwkh.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gt2csucjdve.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ydzc1.top/Article/details/gt2lmsaucfj.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gt2wwyyftyj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gt2iqvgegbr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gt2isxolria.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gboszrmo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2caawtfwr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gt2fdawqbjm.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gt2uawaebyu.html

[S49] C++：写文件
来源：http://dali.svipenyu.cn/Article/details/gt2gmavckam.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gt2ewbdsara.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwelgphx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkqqmtkh.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2fufqmifs.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gt2efkxilba.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gt2fwcjrsls.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kydyqgjy.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gt2hkmvjoit.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gt2tyjkqfjz.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gt2puosmvey.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gt2xrnecdgh.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2zznwajgh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gt2digiuttf.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gt2edmkdaff.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhixingplan.top/Article/details/gt2ikrodzne.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gt2biunmmuq.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gt2pzrvwelf.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjtjlzhn.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gt2tqhugmge.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gt2rsdsrfrt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gt2exojahof.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gt2bcqrgnur.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ivvv.top/Article/details/gt2cgtsphpc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksndqycx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gt2guskclcb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2mlkflgjd.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aajkcjbv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2avembnly.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gt2cserccxu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gt2urdkchtx.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ormkbenh.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gt2tilzqvoe.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhnrtflz.html

val n: String? = null;  n?.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnthuddi.html

[T05] Kotlin：when 表达式
来源：http://dali.gotoacloud.top/Article/details/gt2vnuhlpka.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gt2fuyfrlvj.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gt2jeaeqzow.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2lltcoxyx.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2evjabzco.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gt2sedowxwv.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gt2ktmyicqe.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gt2jrklwvij.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcamplqb.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gt2ziajizns.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2eaeawefx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gt2zjhugfiw.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gt2xljqvffw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpejacfp.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gt2nrgakcqp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2rxkhhfhk.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gt2jpbkubot.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gt2dlchrtrr.html

[T14] Kotlin：循环
来源：http://dali.gaohongyu789.top/Article/details/gt2svikbtic.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gt2qttnohsj.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gt2phdgetjn.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gt2srqnywms.html

[T16] Swift：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2gedxhvlv.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2dvyhbsgd.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxtdtvyt.html

var a = 1;  let b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zkovlxol.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2rkxrlznl.html

"值: \(b)"
来源：http://dali.yj20258.top/Article/details/gt2qxlmgvlw.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gt2zomzgnzp.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gt2lwcqsbao.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gt2hinglijg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gt2oqdfcode.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gt2oqpzspse.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcftmkxy.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gt2sxdlsdnj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gt2cnlzibpr.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gt2goowhsmw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pleelxnj.html

[T24] Swift：闭包
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhzaaqff.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iprfpwyb.html

[T25] Swift：结构体
来源：http://dali.cdnleiting.top/Article/details/gt2lggcknmj.html

struct P { var x: Int }
来源：http://dali.zhengqikj.top/Article/details/gt2rqwliioa.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gt2mqenetzu.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gt2bmmjojyi.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gt2ifvmaeya.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gt2iduqkkbi.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gt2dwvmyhet.html

enum Color { case red, green }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzpobupp.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gt2olfcnvyi.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gt2hwwrjzvs.html

[T30] Swift：协议
来源：http://dali.aibaodan.cn/Article/details/gt2xpfxgten.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gt2yqqxkbvx.html

[T31] Lua：Hello World
来源：http://dali.hammf.cn/Article/details/gt2gdzdbuui.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2snsgqseb.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gt2fulopgez.html

local a = 1
来源：http://dali.hammf.cn/Article/details/gt2hmkrqjgp.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gt2hqmbkjwo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2myftiinc.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gt2tiflrpbb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylitauwg.html

[T35] Lua：字典表
来源：http://dali.shangyingyoupin.top/Article/details/gt2prqfmkju.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gt2wbistecf.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2huqwrvbm.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gt2reoswpug.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2arhacgqu.html

"a" .. "b"
来源：http://dali.svipenyu.cn/Article/details/gt2txhaills.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gt2pdkfqqvy.html

if x > 0 then print("正") end
来源：http://dali.cdnleiting.top/Article/details/gt2gzrzctvv.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gt2nmxibosr.html

string.find(s, "%d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2swbwscrr.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gt2jopjcddd.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gt2kadxszoq.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2mjhjpyds.html

print "Hello\n";
来源：http://dali.hysaishi.cn/Article/details/gt2iongfktf.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gt2nvppvntw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ppjwa.cn/Article/details/gt2qsfhrmiv.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdokbsfy.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gt2wxhzosxa.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gt2ijrwlwxk.html

if ($a > 0) { print "正"; }
来源：http://dali.pycfn.com/Article/details/gt2wnqbodej.html

[T45] Perl：数组遍历
来源：http://dali.zycfv.cn/Article/details/gt2jbdtfhze.html

for my $x (@arr) { print $x; }
来源：http://dali.yangfankeji.com/Article/details/gt2auuzhosk.html

[T46] Perl：哈希操作
来源：http://dali.sufxvd.cn/Article/details/gt2pqrmflrt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.svipenyu.cn/Article/details/gt2pwleswdl.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gt2pwecaewt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.haohaochexian.top/Article/details/gt2srbgywqc.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gt2vicfxxga.html

$s =~ s/old/new/g;
来源：http://dali.xuanzx.com/Article/details/gt2kdvwhmkl.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gt2sfzhknfl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2hymrbvun.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2aoywjabr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shuidangran.top/Article/details/gt2korahunb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258.top/Article/details/gt2zriwdiqa.html

[T51] Scala：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2mttixurb.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2qtknbvbx.html

[T52] Scala：变量
来源：http://dali.xylfe.cn/Article/details/gt2oxnihvbz.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gt2whxcjrbj.html

[T53] Scala：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2fkapqoip.html

s"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gt2drfsqnto.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxlggebv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ebvbvbpa.html

[T55] Scala：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gt2vcleckeg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.haohaochexian.top/Article/details/gt2cpwhzjvc.html

[T56] Scala：样例类
来源：http://dali.jyoumei.cn/Article/details/gt2yrhgdwea.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2hrlafugd.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2vnqwrhus.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.snrcjt.cn/Article/details/gt2ljngedlt.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gt2nxblgetm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gt2rotyhuof.html

[T59] Scala：循环
来源：http://dali.cdnleiting.top/Article/details/gt2yyfgxcwc.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gt2nmpyirvd.html

[T60] Scala：折叠
来源：http://dali.haohaochexian.top/Article/details/gt2qkckosmv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gt2jiinkenm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ixcwegqa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gt2pbwvzewp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2tklwhzbn.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gt2zjapzklo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfdkfeqb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gt2dinjljsj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gt2wfiqhiyg.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gt2nbbhxdrm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydnebobx.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gt2kunedhmv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yangfankeji.com/Article/details/gt2sojbrwnv.html

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gt2etycvzxc.html

list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxybvyss.html

[U06] Py：合并两个字典
来源：http://dali.jinqigufen.top/Article/details/gt2iaoyjojf.html

{**a, **b}
来源：http://dali.bjfxy.top/Article/details/gt2fxvmzgwt.html

[U07] Py：反转字典键值
来源：http://dali.xuetiantiany.cn/Article/details/gt2btznjjck.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gt2mdrzfewf.html

[U08] Py：展平二维列表
来源：http://dali.jqgfzy.top/Article/details/gt2yktytnwa.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gt2mntsagvh.html

[U09] Py：字典取最大值的键
来源：http://dali.guowangkeji.top/Article/details/gt2tvvpkyvn.html

max(d, key=d.get)
来源：http://dali.9152youxi.cn/Article/details/gt2gtjerzmp.html

[U10] Py：按值排序字典
来源：http://dali.gzhubu.top/Article/details/gt2gqulxxuq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gt2nljupqde.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhsmrzxk.html

(x * 2 for x in arr)
来源：http://dali.gotoacloud.top/Article/details/gt2tmolqcxt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fzhhl.top/Article/details/gt2wojfsvfe.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gt2teyxipqu.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gt2moawcbmc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsktjvr.html

[U14] Py：分组收集到列表
来源：http://dali.kuanghao11.cn/Article/details/gt2ukpozcds.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grtecvjz.html

[U15] Py：高精度计时
来源：http://dali.ybcxt.top/Article/details/gt2mvavcryx.html

t = time.perf_counter()
来源：http://dali.yj20258888.top/Article/details/gt2pghotgkm.html

[U16] Py：命令行参数解析
来源：http://dali.jqgufenzy.top/Article/details/gt2ecsoojvh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sufxvd.cn/Article/details/gt2uxmwthrg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsrapbn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fengsongda.top/Article/details/gt2huexwqaz.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gt2oanhifrx.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2nlrygqlq.html

[U19] Py：正则替换带回调
来源：http://dali.smart0.xyz/Article/details/gt2yybgopui.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krakxzuy.html

[U20] Py：缓存函数结果
来源：http://dali.birdmap.top/Article/details/gt2ozvtrvkf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gt2jqqzmqkc.html

[U21] Py：自定义上下文管理器
来源：http://dali.hammf.cn/Article/details/gt2oanksskb.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gt2mhtgldty.html

[U22] Py：矩阵转置
来源：http://dali.tianlin.xyz/Article/details/gt2yjcgskah.html

list(zip(*m))
来源：http://dali.chenzaomai.com/Article/details/gt2eejcwivw.html

[U23] Py：分块读取大文件
来源：http://dali.yueranfly.top/Article/details/gt2gviheeix.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.316326.xyz/Article/details/gt2rmervzat.html

[U24] Py：路径操作
来源：http://dali.hysaishi.cn/Article/details/gt2khfbwdvj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gt2fygtluxf.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gt2lvgzxbfq.html

csv.DictReader(f)
来源：http://dali.cheryme.top/Article/details/gt2mniubzlj.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2haslkccp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqrgkfti.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gt2ljlzoqpx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gt2lgqqqzgx.html

[U28] Py：类型别名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dypycqbx.html

UserId = int
来源：http://dali.zhixingplan.top/Article/details/gt2ryiciwnv.html

[U29] Py：属性校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cskzzejs.html

@property 与 @x.setter 配合
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnsraujb.html

[U30] Py：数据类
来源：http://dali.cheryme.top/Article/details/gt2pyqzcfby.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gt2hvhkxovs.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gt2wsnpqptd.html

python -m pytest -q
来源：http://dali.zhengqikj.top/Article/details/gt2gzqglukx.html

[U32] Py：代码格式化
来源：http://dali.jinqigufen.top/Article/details/gt2rtilmvbn.html

ruff format . && ruff check --fix .
来源：http://dali.guannengcc.top/Article/details/gt2cjxfdrss.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlghvpx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jyoumei.cn/Article/details/gt2mcknoxxu.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gt2ikycfuqp.html

chardet.detect(raw)
来源：http://dali.yuxming.cn/Article/details/gt2gnulxsfj.html

[U35] Py：发送邮件
来源：http://dali.zdqjudy.top/Article/details/gt2lhggqdpn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sufxvd.cn/Article/details/gt2ehjeoouf.html

[U36] Py：定时任务
来源：http://dali.yongpay.top/Article/details/gt2tlxszgef.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdgzblpz.html

[U37] Py：读写 Excel
来源：http://dali.cqqwz.cn/Article/details/gt2yywrwyoo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.redwolf501.top/Article/details/gt2bjgljrjt.html

[U38] Py：获取脚本所在目录
来源：http://dali.ehwqpu.com/Article/details/gt2yofwubzf.html

Path(__file__).resolve().parent
来源：http://dali.jinqigfzy.top/Article/details/gt2pafykapk.html

[U39] Py：判断是否在交互环境
来源：http://dali.ydzc1.top/Article/details/gt2pqgsqilo.html

sys.stdout.isatty()
来源：http://dali.meibo888.top/Article/details/gt2pryxvwei.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gt2qautwaby.html

print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gt2vmbnwfsk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cucudq.cn/Article/details/gt2mpqmgnql.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gt2wehqgwor.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sysykeji.top/Article/details/gt2dooqekmh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrxymmws.html

[U43] PHP：声明命名空间
来源：http://dali.sufxvd.cn/Article/details/gt2vizyktiv.html

namespace App\Http;
来源：http://dali.birdmap.top/Article/details/gt2lahvwsyk.html

[U44] PHP：开启严格类型
来源：http://dali.sxryk.cn/Article/details/gt2ljxnftum.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gt2rzfivvcj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hfpthk.cn/Article/details/gt2etisdpjv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2lxpwyftw.html

[U46] PHP：可空类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzqrmrnn.html

?string $name = null
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxwrfmfm.html

[U47] PHP：联合类型
来源：http://dali.birdmap.top/Article/details/gt2ucntrqpr.html

int|string $id
来源：http://dali.kuanghao11.cn/Article/details/gt2nbxbgome.html

[U48] PHP：纯枚举
来源：http://dali.sufxvd.cn/Article/details/gt2cwfbpzjx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gt2ydnderrv.html

[U49] PHP：只读属性
来源：http://dali.sysykeji.top/Article/details/gt2vnszsmup.html

public readonly string $name
来源：http://dali.ivvv.top/Article/details/gt2pldvufkb.html

[U50] PHP：构造器属性提升
来源：http://dali.quarkkingdee.top/Article/details/gt2dsigmoqm.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gt2lpqsrodx.html

[U51] PHP：数组解构
来源：http://dali.yangfankeji.com/Article/details/gt2fmidcypg.html

[$a, $b] = $arr;
来源：http://dali.yj202588.top/Article/details/gt2ptoiafcm.html

[U52] PHP：箭头函数
来源：http://dali.316326.xyz/Article/details/gt2olhjbilp.html

$double = fn($x) => $x * 2;
来源：http://dali.xziqi.cn/Article/details/gt2iaoinlfq.html

[U53] PHP：空合并运算符
来源：http://dali.pycfn.com/Article/details/gt2vrtpxqdc.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258888.top/Article/details/gt2mdorwbgh.html

[U54] PHP：空安全调用
来源：http://dali.fengsongda.top/Article/details/gt2rtppbybz.html

$obj?->method()
来源：http://dali.sufxvd.cn/Article/details/gt2nehuzkjd.html

[U55] PHP：match 表达式
来源：http://dali.yangfankeji.com/Article/details/gt2avgiaqvn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hammf.cn/Article/details/gt2rvogtxlx.html

[U56] PHP：命名参数
来源：http://dali.gogol.net.cn/Article/details/gt2ehcofnik.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mcmvjtdn.html


<!-- 参考信息 -->