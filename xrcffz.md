代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gt2zizbeiqg.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gt2vukjsyoq.html

const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2wbytocqp.html

[S28] C：静态变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pajjzhka.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gt2eobdvatn.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gt2rwmorwbg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhujbuel.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gt2nidywjtx.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gt2nsmviqde.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gt2ydqmbizf.html

#endif
来源：http://dali.bjfxy.top/Article/details/gt2afknndxp.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gt2dbctnssj.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gt2kyvvpdue.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2usqpfjqq.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gt2aameemmo.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gt2pnlawvty.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivbuynxw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gt2serctzyv.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gt2slsgonnn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gt2ueuldxwl.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gt2csnlxluz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2wpasmkfv.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gt2xqbnfipk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2ezudsodv.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gt2opnmwanm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gt2yidoflwc.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gt2fwlemvpi.html

std::sort(v.begin(), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gt2jzcghqjg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2xowpkqil.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gt2sgwhbyrj.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gt2lomcvgmi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yonumen.top/Article/details/gt2yuzyjkfr.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gt2lmcvznzv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnmxxuwk.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gt2rkgowthe.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zufchykp.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gt2rqtexldp.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gt2pgqrmyzt.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gt2dxrdrtwg.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gt2lzuqyykm.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gt2ladthzyt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gt2fsrduxxj.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gt2kmclsjxi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gt2uhzsdylk.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gt2zlqrvrfi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gt2yjpqvhyv.html

[S48] C++：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2unmrtner.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csaehkfx.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gt2qxufuyjd.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gt2jrnbquvs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gt2wjsoqdqw.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gt2gbdoexup.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2fkxvcwhh.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezpisaec.html

static_cast<double>(a) / b
来源：http://dali.meibo888.top/Article/details/gt2nzmegsoz.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gt2tvmnueby.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gt2sobqgicv.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gt2rqfxewws.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gt2hmqbwaal.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttdhtkkx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jovdfkxj.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gt2eldrnrcd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aweejlco.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gt2gebcflwu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pddexjhv.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gt2ubziiikm.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gt2kxuwunuz.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gt2etgyjfyg.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gt2hvspivpp.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gt2osgztjtc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gt2iaiqgzse.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gt2umxadbfi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gt2jhovener.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2awvqpsed.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gt2osyjuequ.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2hwddfgeo.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2gubxbphm.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uokxyjus.html

[T02] Kotlin：变量
来源：http://dali.yj202588.top/Article/details/gt2wvnslfqk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gt2pdvlyhmy.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gt2khgbdojh.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gt2nfzccohb.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gt2wjnipqsy.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2eotxoech.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gt2ftrpjbhm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gt2glzaufba.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqibxbbl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2ofebgfub.html

[T07] Kotlin：集合过滤
来源：http://dali.gzhubu.top/Article/details/gt2igpcyjqr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gt2mweasuiq.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gt2xentvpus.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gt2hyaarkjd.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gt2mhecrblg.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gt2naofehrf.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gt2mrvxmoir.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gt2rdmvawzk.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gt2zssqajqv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uogxmiys.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gt2rhrdxwsh.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2ltdgubwn.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gt2hmoodqxc.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gt2wydomzow.html

[T14] Kotlin：循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuneqmpp.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gt2viiuxdrf.html

[T15] Kotlin：接口
来源：http://dali.hywenlv.cn/Article/details/gt2ilzopyyk.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gt2lsgpfyqg.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2cshnvhmm.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2jpsxeezb.html

[T17] Swift：变量与常量
来源：http://dali.cqqwz.cn/Article/details/gt2xqccxiku.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gt2paryttmg.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2baqeyvde.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gt2jjzkgbeb.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gt2lmkjfjmm.html

if let n = opt { print(n) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apkgtdlg.html

[T20] Swift：数组操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2ysytbqde.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gt2zctzwdbq.html

[T21] Swift：遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvzxqcls.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojihjmei.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gt2dyurkcle.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hywenlv.cn/Article/details/gt2tmkbkqol.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2whvegfbo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkupwscd.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gt2vtovwujv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2bitrgylj.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gt2wjuoxwvl.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gt2ggdzenzm.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gt2pgabqpag.html

class A: Base { override func f() {} }
来源：http://dali.zhixingplan.top/Article/details/gt2zrsocoal.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gt2kaawzypc.html

do { try f() } catch { print(error) }
来源：http://dali.tian-w.cn/Article/details/gt2otrrgvpb.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gt2kevybqyj.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gt2hgncpcvu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gt2buecggyv.html

guard let x = opt else { return }
来源：http://dali.hammf.cn/Article/details/gt2lvpweugz.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gt2kvuvhwtk.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgfzy.top/Article/details/gt2gelrlnqe.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2utlimswz.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2kbrjojnc.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gt2tilqpxzd.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gt2sxttixtd.html

[T33] Lua：表（数组）
来源：http://dali.c1oappe.top/Article/details/gt2oazigout.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuetiantiany.cn/Article/details/gt2papuecqh.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gt2znuylfzs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gt2mufsyoml.html

[T35] Lua：字典表
来源：http://dali.guowangkeji.top/Article/details/gt2ctwdulde.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ppjwa.cn/Article/details/gt2dogyayuz.html

[T36] Lua：函数
来源：http://dali.xinyue.icu/Article/details/gt2yajkufna.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gt2bkectknp.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gt2mlxosflj.html

"a" .. "b"
来源：http://dali.hnqzz.top/Article/details/gt2sgejvkit.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gt2iuaxywem.html

if x > 0 then print("正") end
来源：http://dali.yonumen.top/Article/details/gt2rowdemed.html

[T39] Lua：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gt2fdtsrikp.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qeoadyvs.html

[T40] Lua：元表
来源：http://dali.jqgufenzy.top/Article/details/gt2tsmaacrb.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbvitxfv.html

[T41] Perl：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2mbqjgfhe.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gt2duihbmwq.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gt2jekwdwki.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fzhhl.top/Article/details/gt2zvoehdsz.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gt2kvktrbwl.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gt2sgkxevno.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gt2izhsvxfo.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gt2nulsljvh.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gt2reurykjh.html

for my $x (@arr) { print $x; }
来源：http://dali.aizwys.cn/Article/details/gt2odhlahdk.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gt2pcwnowcx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.9152youxi.cn/Article/details/gt2dqharqsj.html

[T47] Perl：正则捕获
来源：http://dali.feifeiyinyue.top/Article/details/gt2maosgxti.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gt2getbxmrg.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gt2jlnpwexi.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gt2gnguaoqv.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gt2tunsxpyk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gt2gdkoewdr.html

[T50] Perl：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2bahsiraa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ivvv.top/Article/details/gt2sblcptne.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhixingplan.top/Article/details/gt2idpiugsd.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2pizgebfd.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2gbrzdnku.html

[T52] Scala：变量
来源：http://dali.nanxuanxn.top/Article/details/gt2rlrpjvxx.html

val a = 1;  var b = 2
来源：http://dali.daxiang520.top/Article/details/gt2oapjxlsl.html

[T53] Scala：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gt2aeocfdok.html

s"值: $b"
来源：http://dali.sweek.top/Article/details/gt2mxmvbskr.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gt2gfdzrkce.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gt2wkytgaqa.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gt2qwieyuyr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmldtiqp.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gt2rmxibsma.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2ppovlaia.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2iopxyqct.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.snrcjt.cn/Article/details/gt2qcqhclbj.html

[T58] Scala：函数定义
来源：http://dali.sxryk.cn/Article/details/gt2ikbbheeb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsjoedot.html

[T59] Scala：循环
来源：http://dali.gotoacloud.top/Article/details/gt2wwnhrdnc.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cffgojmw.html

[T60] Scala：折叠
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejesaryr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gt2shmjifri.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2xpuparlq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gt2mrgufwwd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2dfnikgsa.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gt2iiejjeun.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gt2bxqkeese.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gt2ncgtbsnv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gt2mwdczmez.html

[U03] Py：加载 .env 配置
来源：http://dali.hysaishi.cn/Article/details/gt2xbxbojil.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpskqwif.html

[U04] Py：变量调试打印
来源：http://dali.feifeiyinyue.top/Article/details/gt2illbcbyi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuanzhike.top/Article/details/gt2nnuqimlj.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gt2uwwmzuyp.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gt2brvzlyqi.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tytruivp.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gt2xjbncyfc.html

[U07] Py：反转字典键值
来源：http://dali.meibo888.top/Article/details/gt2rgodqfzc.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gt2mvsybsvd.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gt2bizyezuw.html

[y for x in nested for y in x]
来源：http://dali.haohaochexian.top/Article/details/gt2tleltgej.html

[U09] Py：字典取最大值的键
来源：http://dali.ydzc1.top/Article/details/gt2hmrctvfn.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gt2kddyreln.html

[U10] Py：按值排序字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzhtffow.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fengsongda.top/Article/details/gt2fbxyqyiy.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gt2utzzwuqy.html

(x * 2 for x in arr)
来源：http://dali.yj20258888.top/Article/details/gt2uakhxzjt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.iojbl.cn/Article/details/gt2ujyhjwuu.html

Counter(arr).most_common(3)
来源：http://dali.jyoumei.cn/Article/details/gt2wnssrhdt.html

[U13] Py：固定长度队列
来源：http://dali.tanke756.top/Article/details/gt2mxnuxieu.html

deque(maxlen=10)
来源：http://dali.chenlongwang.top/Article/details/gt2mlmuklfh.html

[U14] Py：分组收集到列表
来源：http://dali.hysaishi.cn/Article/details/gt2effbmqcr.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gt2jiejnsst.html

[U15] Py：高精度计时
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxsfwnyz.html

t = time.perf_counter()
来源：http://dali.sufxvd.cn/Article/details/gt2aowfqcot.html

[U16] Py：命令行参数解析
来源：http://dali.sufxvd.cn/Article/details/gt2hpfmivad.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuanzhike.top/Article/details/gt2arkhrrng.html

[U17] Py：初始化日志
来源：http://dali.dianchejie.cn/Article/details/gt2omkmvzim.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gt2ymwwcayy.html

[U18] Py：预编译正则
来源：http://dali.iojbl.cn/Article/details/gt2tchyltid.html

pat = re.compile(r"\d+")
来源：http://dali.fzhhl.top/Article/details/gt2lthyvkex.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gt2ziyqmbas.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgfzy.top/Article/details/gt2veuiajil.html

[U20] Py：缓存函数结果
来源：http://dali.dashuyun.cn/Article/details/gt2gfhfellm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gt2aqfkragf.html

[U21] Py：自定义上下文管理器
来源：http://dali.jlsjyb.cn/Article/details/gt2qbfoqhwj.html

@contextlib.contextmanager
来源：http://dali.birdmap.top/Article/details/gt2jggpztqe.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gt2uswrtspn.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gt2lroyhlop.html

[U23] Py：分块读取大文件
来源：http://dali.nanxinkj.top/Article/details/gt2osduvrsb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xziqi.cn/Article/details/gt2ckfiiuoa.html

[U24] Py：路径操作
来源：http://dali.guannengcc.top/Article/details/gt2dfoolkuf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gt2znrqdcng.html

[U25] Py：CSV 按字典读
来源：http://dali.birdmap.top/Article/details/gt2lyindhcb.html

csv.DictReader(f)
来源：http://dali.yuxming.cn/Article/details/gt2anmjqowg.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gt2ahousqdi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hammf.cn/Article/details/gt2vvbfpcex.html

[U27] Py：异步 HTTP
来源：http://dali.chenzaomai.com/Article/details/gt2wbwnqvlh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gt2fajrebih.html

[U28] Py：类型别名
来源：http://dali.chenjidiqi.icu/Article/details/gt2iszdehwx.html

UserId = int
来源：http://dali.tian-w.cn/Article/details/gt2vqacoalb.html

[U29] Py：属性校验
来源：http://dali.pycfn.com/Article/details/gt2vebabwci.html

@property 与 @x.setter 配合
来源：http://dali.hywenlv.cn/Article/details/gt2fvhegpyu.html

[U30] Py：数据类
来源：http://dali.c1oappe.top/Article/details/gt2gylxwepv.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gt2xkvwnaee.html

[U31] Py：单测
来源：http://dali.yanxiufei.cn/Article/details/gt2exvervzd.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gt2hinzivtu.html

[U32] Py：代码格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2coajwmvr.html

ruff format . && ruff check --fix .
来源：http://dali.9152youxi.cn/Article/details/gt2acqukevv.html

[U33] Py：打包发布
来源：http://dali.zdqjudy.top/Article/details/gt2drtwfwcc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gt2zglpdtch.html

[U34] Py：判断编码
来源：http://dali.jqgfzy.top/Article/details/gt2ffvgqgsm.html

chardet.detect(raw)
来源：http://dali.andypj.xyz/Article/details/gt2otgyeals.html

[U35] Py：发送邮件
来源：http://dali.quarkkingdee.top/Article/details/gt2tfmgqdml.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aizwys.cn/Article/details/gt2ihpjpgmf.html

[U36] Py：定时任务
来源：http://dali.sufxvd.cn/Article/details/gt2xjabkqxh.html

schedule.every(10).minutes.do(job)
来源：http://dali.yanxiufei.cn/Article/details/gt2rmleqxah.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gt2rzflvtot.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenlongwang.top/Article/details/gt2kylicizf.html

[U38] Py：获取脚本所在目录
来源：http://dali.hywenlv.cn/Article/details/gt2blwumyxi.html

Path(__file__).resolve().parent
来源：http://dali.feifeiyinyue.top/Article/details/gt2faxxitdg.html

[U39] Py：判断是否在交互环境
来源：http://dali.fengsongda.top/Article/details/gt2uslpqvkv.html

sys.stdout.isatty()
来源：http://dali.zhongyouzk.top/Article/details/gt2zcbstncg.html

[U40] Py：打印到标准错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqhjvzaq.html

print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gt2agfqfvan.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jyoumei.cn/Article/details/gt2qbrekfqe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shuidangran.top/Article/details/gt2csbynfqn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhoulong.xyz/Article/details/gt2bakajing.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gt2llkejtxa.html

[U43] PHP：声明命名空间
来源：http://dali.xinyue.icu/Article/details/gt2wjedrcjw.html

namespace App\Http;
来源：http://dali.yuanzhike.top/Article/details/gt2dsayqymj.html

[U44] PHP：开启严格类型
来源：http://dali.jlsjyb.cn/Article/details/gt2vsssbhlq.html

declare(strict_types=1);
来源：http://dali.guannengcc.top/Article/details/gt2zkfjjemg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258888.top/Article/details/gt2zolndwqu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2buxkxwqt.html

[U46] PHP：可空类型
来源：http://dali.dashuyun.cn/Article/details/gt2pupifpme.html

?string $name = null
来源：http://dali.tian-w.cn/Article/details/gt2qzcsjloo.html

[U47] PHP：联合类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2wezmnvwk.html

int|string $id
来源：http://dali.jinqigufen.top/Article/details/gt2zxgazfmm.html

[U48] PHP：纯枚举
来源：http://dali.sufxvd.cn/Article/details/gt2ngrububx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.316326.xyz/Article/details/gt2zyutcyvh.html

[U49] PHP：只读属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2kesmzydp.html

public readonly string $name
来源：http://dali.0kj1m.cn/Article/details/gt2ophzralj.html

[U50] PHP：构造器属性提升
来源：http://dali.ppjwa.cn/Article/details/gt2bcladzvr.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gt2fajhgrpk.html


<!-- 参考信息 -->