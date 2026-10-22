代发 wailian999

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqwkghmf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gttratghfp.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtlarqfocu.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwqqbvuf.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gtyskpkaeg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sweek.top/Article/details/gtgceejtph.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcbpsfsi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtsrwdogfg.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtgtiibgob.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtfalwhcdi.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gtlppdyfiw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gthbgnxhxv.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtcngbqmgs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtrdrpvxho.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitulhars.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtxfvkpfnr.html

[S39] C++：自定义比较器排序
来源：http://dali.cashguo.top/Article/details/gtjnesfkjt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dashuyun.cn/Article/details/gtgsozjpcm.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtehqqlvnw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gtnathjmfk.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtsuopxzbv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gttbjaieaj.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gtrvdfbapo.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtzwrlevic.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtdrnaojzb.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtnhfounqh.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gtknikrpkl.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtgjeszrrc.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gtgbfqgxkt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gterjvynov.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmnvitvx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gtkerdnrdm.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gtvqecxgsm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gtvbwyvace.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtlhxaubsx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gtzyxhnfnj.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gtnpdzldko.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gthyxbwwfq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gtratunmyc.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtgpuontbl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtrzurvplv.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqodcibca.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtfklseykc.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gtmwevqgaw.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyohfdoap.html

[S53] C++：移动语义
来源：http://dali.yj20258888.top/Article/details/gtdnsrcsuj.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtmhvukkgo.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gtxjcgigoy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtqsgyajhm.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gtpowvtlli.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttptokhey.html

[S56] C++：optional
来源：http://dali.zdqjudy.top/Article/details/gtlkcaitzi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtlknfghdo.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gtjbhfgmua.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gttxbrbvzi.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gtjmshvpym.html

namespace ns { int f() { return 1; } }
来源：http://dali.guannengcc.top/Article/details/gtoiqaxcwk.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gtdyuolaoc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtcvtbarej.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gtehozwfmu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gtdspbolss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtkqvzkrep.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtlflmldyv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrzoxpwvl.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtettuwv.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtvpfdkqjz.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gtpohyftho.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtaownbayy.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gtxntttrwg.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtymborhcd.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gtvcxlqmjc.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gtlkbkcnpr.html

[T05] Kotlin：when 表达式
来源：http://dali.snrcjt.cn/Article/details/gtgcisamni.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daxiang520.top/Article/details/gtuxfvfdym.html

[T06] Kotlin：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtbcghnpst.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtqqntppsm.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtrrzlhsyn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtrbebnjub.html

[T08] Kotlin：数据类
来源：http://dali.gzhubu.top/Article/details/gtipvrubrn.html

data class User(val name: String, val age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtzmfgnnni.html

[T09] Kotlin：扩展函数
来源：http://dali.gzhubu.top/Article/details/gtmboynjdh.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gtzfhihboe.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gthaxwbrsj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gtykmjuxrv.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gtcxsxyvfj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtbvjsosga.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtrwblnpwb.html

val (a, b) = Pair(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtvaadjpzi.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gtlvptifyr.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gtcekqysvi.html

[T14] Kotlin：循环
来源：http://dali.daxiang520.top/Article/details/gtylolmcxk.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtbcgllcjj.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gtcxnhhlxh.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gtqrzvshet.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtyjqvfhjx.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtxgcssrlz.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gtakbprkld.html

var a = 1;  let b = 2
来源：http://dali.nanxinkj.top/Article/details/gtbtskmirj.html

[T18] Swift：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtbrhhkjlh.html

"值: \(b)"
来源：http://dali.shangyingyoupin.top/Article/details/gtwehfqmtx.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gtdmfrsrnv.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gtfnppfruw.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtidqpzctq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xylfe.cn/Article/details/gtfvifkask.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtuwjjnlzc.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gtlkvtarch.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gtknmicnmo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pycfn.com/Article/details/gtvwtpcgds.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gtmvuikbkb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.havefunace.top/Article/details/gtuflqkvup.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gtnbgwhasd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtuxcjphrs.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gtdsizmyia.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gtkhxpfbcn.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtvehsaozz.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gtqxnvwdlp.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtkcbubmlt.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gtfskwqqau.html

[T28] Swift：枚举
来源：http://dali.pycfn.com/Article/details/gtnqodxkru.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gtajqjorab.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gtjcrnqnwe.html

guard let x = opt else { return }
来源：http://dali.bjfxy.top/Article/details/gtilzbsbow.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gtctbvxczk.html

protocol Shape { func area() -> Double }
来源：http://dali.sweek.top/Article/details/gtglrvgyut.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtarpftmfl.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtazndhmub.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gtywejuekg.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gtlomunake.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gtgnamtlfg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yonumen.top/Article/details/gtbpfsvmtf.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqfbuhjg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gtgsfbxnmz.html

[T35] Lua：字典表
来源：http://dali.jqgfzy.top/Article/details/gtlejjztuf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gtfznqyyku.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gtyetbptfk.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gtuzarozxo.html

[T37] Lua：字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtquryicnd.html

"a" .. "b"
来源：http://dali.jinqigfzy.top/Article/details/gtttvbzfay.html

[T38] Lua：条件
来源：http://dali.smart0.xyz/Article/details/gtvabmqhrf.html

if x > 0 then print("正") end
来源：http://dali.aibaodan.cn/Article/details/gtkpfgzncw.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtkfsoussc.html

string.find(s, "%d+")
来源：http://dali.sufxvd.cn/Article/details/gtzxbkrggr.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gthlvwrxog.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gtzdyhjibx.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtzlmcffzs.html

print "Hello\n";
来源：http://dali.zhengqikj.top/Article/details/gtvuzfwkvv.html

[T42] Perl：变量类型
来源：http://dali.jqgufenzy.top/Article/details/gtsiriqjcj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gaohongyu789.top/Article/details/gtfvcppyuv.html

[T43] Perl：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtygoawtvs.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gtyldejpip.html

[T44] Perl：条件
来源：http://dali.dianchejie.cn/Article/details/gtxjimxmig.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gtfturooqm.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gtocgfcoun.html

for my $x (@arr) { print $x; }
来源：http://dali.yangfankeji.com/Article/details/gtvdbuyaut.html

[T46] Perl：哈希操作
来源：http://dali.pengpengdd.cyou/Article/details/gtjcdkomdp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ydzc1.top/Article/details/gtajbkkrdg.html

[T47] Perl：正则捕获
来源：http://dali.yueranfly.top/Article/details/gtgjtyogfx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gtyptidktk.html

[T48] Perl：正则替换
来源：http://dali.xziqi.cn/Article/details/gtzbqgbonz.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtgyvcbocy.html

[T49] Perl：函数
来源：http://dali.yj20258888.top/Article/details/gtcqayvstx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtcfepjoya.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gthvvwtwlo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.316326.xyz/Article/details/gtidyuiqnx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqniyawh.html

[T51] Scala：Hello World
来源：http://dali.meibo888.top/Article/details/gtimcwlhbu.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtykkmxwwz.html

[T52] Scala：变量
来源：http://dali.zhixingplan.top/Article/details/gthpyhmkll.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gtxxwnhnxs.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtqpgurmie.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtptewtnmx.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtdwcoblid.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gtarakprtg.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gtxdlfpush.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtwwwggqel.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtketirmkw.html

case class User(name: String, age: Int)
来源：http://dali.meibo888.top/Article/details/gtmaamjlbt.html

[T57] Scala：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtcushpzmd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtwetjpbpx.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gtptgeipmi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gtqbcthbuk.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gtdlkmpxdj.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258.top/Article/details/gtkkbvgmml.html

[T60] Scala：折叠
来源：http://dali.yj202588.top/Article/details/gtmtfiijdf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ppjwa.cn/Article/details/gtlacvuuiw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtczpaanru.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gttsexeyxm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrmvhiepf.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gtgmfzoxms.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hywenlv.cn/Article/details/gtlbfaqbeb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.vqdsnc.cn/Article/details/gtdsozujmx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gtxhyhasle.html

[U03] Py：加载 .env 配置
来源：http://dali.cucudq.cn/Article/details/gtapzmclww.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gtslveiglf.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gtgniwqcxm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchfeicqx.html

[U05] Py：列表去重且保序
来源：http://dali.316326.xyz/Article/details/gthqlpfpsv.html

list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtfetlrtco.html

[U06] Py：合并两个字典
来源：http://dali.redwolf501.top/Article/details/gthkzysdjb.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gtpzoyefho.html

[U07] Py：反转字典键值
来源：http://dali.mhx1999.top/Article/details/gttrwdbury.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gthfbgivob.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gttghzbzbo.html

[y for x in nested for y in x]
来源：http://dali.zhixingplan.top/Article/details/gtjvjalyiy.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gtajqctnfh.html

max(d, key=d.get)
来源：http://dali.nwbrower.top/Article/details/gtxuzqygyr.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtcfjnjzqg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gtqedeoyao.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gttjggbtfo.html

(x * 2 for x in arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapgubgdo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpktzzjck.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gtvtgtfgsj.html

[U13] Py：固定长度队列
来源：http://dali.sweek.top/Article/details/gtrgrasmog.html

deque(maxlen=10)
来源：http://dali.shangyingyoupin.top/Article/details/gtqkcqgpsf.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gtqmvmoqyh.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gtcxldkhjj.html

[U15] Py：高精度计时
来源：http://dali.gaohongyu789.top/Article/details/gtgsxfuxre.html

t = time.perf_counter()
来源：http://dali.fzhhl.top/Article/details/gtumtuqjkr.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gthfaiqozf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuanzhike.top/Article/details/gtwfupqvsc.html

[U17] Py：初始化日志
来源：http://dali.andypj.xyz/Article/details/gtbsqjayul.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuetiantiany.cn/Article/details/gtvglctmdr.html

[U18] Py：预编译正则
来源：http://dali.0kj1m.cn/Article/details/gtqsaqnlff.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtppykkbne.html

[U19] Py：正则替换带回调
来源：http://dali.hnqzz.top/Article/details/gtdcgcoqjw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gthpgblnfn.html

[U20] Py：缓存函数结果
来源：http://dali.zhoulong.xyz/Article/details/gtnjqazlep.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gtkrpixbuh.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gtfyspkqxl.html

@contextlib.contextmanager
来源：http://dali.daria6918.cn/Article/details/gtjyjdcvkz.html

[U22] Py：矩阵转置
来源：http://dali.iojbl.cn/Article/details/gtlsbhlpnx.html

list(zip(*m))
来源：http://dali.chenjidiqi.icu/Article/details/gteksaqylm.html

[U23] Py：分块读取大文件
来源：http://dali.yj20258.top/Article/details/gtpkanabdc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.haohaochexian.top/Article/details/gtovfyimsn.html

[U24] Py：路径操作
来源：http://dali.jqgufenzy.top/Article/details/gtuidphngi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtrbuzfmjr.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gtjcthajmb.html

csv.DictReader(f)
来源：http://dali.sweek.top/Article/details/gtisxvbdlh.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gtutrxqpiz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlihhwic.html

[U27] Py：异步 HTTP
来源：http://dali.sufxvd.cn/Article/details/gtvxsefmnf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuetiantiany.cn/Article/details/gtparhjlos.html

[U28] Py：类型别名
来源：http://dali.meibo888.top/Article/details/gtochmvucl.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gtwjtmyemn.html

[U29] Py：属性校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gtresfpbhz.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gtxrjsuwre.html

[U30] Py：数据类
来源：http://dali.wangdashe.top/Article/details/gtadobggwc.html

@dataclass(slots=True)
来源：http://dali.andypj.xyz/Article/details/gtyxcxwnde.html

[U31] Py：单测
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmuqlvhv.html

python -m pytest -q
来源：http://dali.vqdsnc.cn/Article/details/gttyatkkiv.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtztltqmnh.html

ruff format . && ruff check --fix .
来源：http://dali.ydzc1.top/Article/details/gtbwvlthie.html

[U33] Py：打包发布
来源：http://dali.jyoumei.cn/Article/details/gtyqmpfevj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guowangkeji.top/Article/details/gtfncbmavm.html

[U34] Py：判断编码
来源：http://dali.zycfv.cn/Article/details/gtwgjrpyuy.html

chardet.detect(raw)
来源：http://dali.iojbl.cn/Article/details/gtqyqjcwtq.html

[U35] Py：发送邮件
来源：http://dali.daxiang520.top/Article/details/gtlakbhzaf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuxming.cn/Article/details/gtckwjybnh.html

[U36] Py：定时任务
来源：http://dali.aibaodan.cn/Article/details/gtwyilmbyn.html

schedule.every(10).minutes.do(job)
来源：http://dali.svipenyu.cn/Article/details/gtjopeisnd.html

[U37] Py：读写 Excel
来源：http://dali.zycfv.cn/Article/details/gtdnvokmny.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shzxlz.cn/Article/details/gtupgttcnm.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnqzz.top/Article/details/gtidjkcztl.html

Path(__file__).resolve().parent
来源：http://dali.ydzc1.top/Article/details/gtixznbgzi.html

[U39] Py：判断是否在交互环境
来源：http://dali.sxryk.cn/Article/details/gtvjjawpfn.html

sys.stdout.isatty()
来源：http://dali.aibaodan.cn/Article/details/gtnalbtgdo.html

[U40] Py：打印到标准错误
来源：http://dali.zhengqikj.top/Article/details/gtodrplrzk.html

print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtfpbcatnr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gtmnqjygwx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.smart0.xyz/Article/details/gtgpysfqju.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hongshengwenyu.top/Article/details/gttmriqvod.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yongpay.top/Article/details/gtwoxdtapw.html

[U43] PHP：声明命名空间
来源：http://dali.pycfn.com/Article/details/gtavewvugy.html

namespace App\Http;
来源：http://dali.svipenyu.cn/Article/details/gtclfutsnc.html

[U44] PHP：开启严格类型
来源：http://dali.yj20258888.top/Article/details/gtlhmnielt.html

declare(strict_types=1);
来源：http://dali.cqqwz.cn/Article/details/gttvkzepqm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yonumen.top/Article/details/gtoabdpusy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtnidioxgu.html

[U46] PHP：可空类型
来源：http://dali.xylfe.cn/Article/details/gttpawlkgj.html

?string $name = null
来源：http://dali.yvedp.cn/Article/details/gtsbyyqnju.html

[U47] PHP：联合类型
来源：http://dali.yanxiufei.cn/Article/details/gtisniaxrw.html

int|string $id
来源：http://dali.gotoacloud.top/Article/details/gtsvbxrpqj.html

[U48] PHP：纯枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnsxmrti.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenlongwang.top/Article/details/gteacinulj.html

[U49] PHP：只读属性
来源：http://dali.sweek.top/Article/details/gtvuvobwgp.html

public readonly string $name
来源：http://dali.xuanzx.com/Article/details/gtgkdflzin.html

[U50] PHP：构造器属性提升
来源：http://dali.hnqzz.top/Article/details/gtcpjbzvvl.html

public function __construct(private int $id) {}
来源：http://dali.zhongyouzk.top/Article/details/gtikslnbys.html

[U51] PHP：数组解构
来源：http://dali.chenlongwang.top/Article/details/gtccmmapdn.html

[$a, $b] = $arr;
来源：http://dali.cashguo.top/Article/details/gtcgdsgkyi.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gttaohdhzp.html

$double = fn($x) => $x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gtotfnfhts.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gtsucqclbv.html

$v = $a ?? $b ?? "default";
来源：http://dali.fengsongda.top/Article/details/gtllatodah.html

[U54] PHP：空安全调用
来源：http://dali.dianchejie.cn/Article/details/gtnwxbgffv.html

$obj?->method()
来源：http://dali.c1oappe.top/Article/details/gtruryxtot.html

[U55] PHP：match 表达式
来源：http://dali.chenlongwang.top/Article/details/gtujqhhnev.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258.top/Article/details/gtknvrwtyk.html

[U56] PHP：命名参数
来源：http://dali.ybcxt.top/Article/details/gtxdqfhqbc.html

f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gtsnzmcrbw.html


<!-- 参考信息 -->