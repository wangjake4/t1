代发 wailian999

#ifndef X_H
来源：http://dali.yj202588.top/Article/details/gtbzqkfdgc.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtwztpbsyj.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gtbkyyryss.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtrrwwjfmk.html

#include <iostream>
来源：http://dali.chenzaomai.com/Article/details/gtgsbntcwa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjddmjhod.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gtqeqshiit.html

std::string s = "hi";  s += "!";
来源：http://dali.zhiwuduotai.top/Article/details/gtxwkiycrb.html

[S33] C++：vector 增删
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxmldvzs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtvceemfie.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gtwttpjspw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtjxtgzbwl.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gtdfdcmvyk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtzrsgdxmj.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gtsnekvqdu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtlftivfrj.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gtfrystann.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gtzzswyxch.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gtqqrhkmir.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtqwlgscfx.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gtechomoip.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gtmtzlxqvo.html

[S40] C++：查找元素
来源：http://dali.yj20258888.top/Article/details/gtkffhakry.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gtofdvdnew.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gtysmdfxmq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtqdsfuhxw.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258888.top/Article/details/gtdcucbqvc.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gtdxfrxaaw.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtnfqayvgc.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gtfzgvpuep.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gtykjsnaob.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtkyuixpzi.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gtwauubiyf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtnqkywxxp.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gtpyxqokld.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gthrsnlqpc.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gtaoxwcppm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gtmnacqdfg.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtdwcnvhnm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daxiang520.top/Article/details/gtxuwgrzci.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtrwdphhvc.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtocjchltf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gtlvbqzjpk.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gtuxfdvjil.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtjpzqjwwr.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtwylxavpj.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gtyzfeluqt.html

[S52] C++：const 与 noexcept
来源：http://dali.fengsongda.top/Article/details/gtrvvabovp.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gtqphmdzas.html

[S53] C++：移动语义
来源：http://dali.zycfv.cn/Article/details/gtkubznqko.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gtbzvawfmu.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtngsjunsv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gtayjhpfxv.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gtbqotnvoq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlzhetpx.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtvntgqypo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gtombaiyym.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gtkdasqciu.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwfcsbtt.html

[S58] C++：命名空间
来源：http://dali.aibaodan.cn/Article/details/gtafumrcqh.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gttsttbskj.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gtitojaukf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtxilyuggy.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gtlxgksnvv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtdcksfmkq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfplegcin.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gtoigzsfau.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtywidnqzu.html

[T01] Kotlin：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtqsybncwy.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gttmwlhdar.html

[T02] Kotlin：变量
来源：http://dali.xylfe.cn/Article/details/gtharsjcxy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pengpengdd.cyou/Article/details/gtnnufowzm.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gtpfmlorez.html

"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtbvhzessk.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gtplxbuycy.html

val n: String? = null;  n?.length
来源：http://dali.xuetiantiany.cn/Article/details/gthwxhcyvp.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gtgsvusbzh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gthkjbbrsa.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtgbgxwmkz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtlvcgkdnp.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtlbjwnlqs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nwbrower.top/Article/details/gtwdrfajwy.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gtwdtjdwvq.html

data class User(val name: String, val age: Int)
来源：http://dali.c1oappe.top/Article/details/gtxzlzbnuy.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gtrqjhvqfj.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gtclcmyjdu.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gtcgtmtpaf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gtxhsitwew.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gtwakbpcia.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gtouctwmdn.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gtcxasuzti.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtlzuiwvwn.html

[T13] Kotlin：只读 Map
来源：http://dali.mhx1999.top/Article/details/gtpjytsvta.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtdoaxowac.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gtsbobathu.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gticmmhbmb.html

[T15] Kotlin：接口
来源：http://dali.sufxvd.cn/Article/details/gtwhtrdzxr.html

interface Shape { fun area(): Double }
来源：http://dali.tanke756.top/Article/details/gtsdouiyvp.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtuxsfjkyv.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtcjzkdcuk.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gtvbclaeao.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtdmzkuvcz.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtdircgitg.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gtrnrtybqf.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtbhzvxunn.html

if let n = opt { print(n) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaedgpsy.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gtuvselqjw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gtvqidinzo.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthqchyiz.html

for x in a { print(x) }
来源：http://dali.gzhubu.top/Article/details/gtjvqmbuyt.html

[T22] Swift：字典
来源：http://dali.yj20258888.top/Article/details/gtjqlgpmgh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gtfpizdtjq.html

[T23] Swift：函数
来源：http://dali.mhx1999.top/Article/details/gttsgrafyd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenlongwang.top/Article/details/gtxmcckcpk.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gtlrdseacs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtemnkcgkl.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtaymmkvqu.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gtfmioxpec.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gtxfsryloc.html

class A: Base { override func f() {} }
来源：http://dali.jinqigufen.top/Article/details/gteputgary.html

[T27] Swift：错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gthaamhprb.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuwsfbss.html

[T28] Swift：枚举
来源：http://dali.iojbl.cn/Article/details/gtixcybltw.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gtayllafbq.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gtaxmakrtm.html

guard let x = opt else { return }
来源：http://dali.hnqzz.top/Article/details/gtsdsxnaok.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gtslfnlzze.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gttzjsdzqk.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gtjxafecdb.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtmaxibqgf.html

[T32] Lua：局部变量
来源：http://dali.zhengqikj.top/Article/details/gtmmnqebfk.html

local a = 1
来源：http://dali.meibo888.top/Article/details/gtoehqnbvh.html

[T33] Lua：表（数组）
来源：http://dali.redwolf501.top/Article/details/gtpcdwyerg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuanzhike.top/Article/details/gtmdwgjygg.html

[T34] Lua：遍历表
来源：http://dali.andypj.xyz/Article/details/gtdncmqxci.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gtorkakgpd.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtdmbnoesn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shuidangran.top/Article/details/gtwpxqwylo.html

[T36] Lua：函数
来源：http://dali.yueranfly.top/Article/details/gttvzpkyzz.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gtkpdwcxce.html

[T37] Lua：字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtldzeazyp.html

"a" .. "b"
来源：http://dali.cqqwz.cn/Article/details/gtppxecuzw.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gtyrrzlvhb.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gtfukovcln.html

[T39] Lua：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtdapglbxi.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtneijleqo.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gtgswqusmd.html

setmetatable({}, { __index = base })
来源：http://dali.tanke756.top/Article/details/gtzygtjoxe.html

[T41] Perl：Hello World
来源：http://dali.bjfxy.top/Article/details/gtpnrqwabg.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtrlawkaex.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gtgvjeglfo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guannengcc.top/Article/details/gtxvlpjxlt.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtzgtfgkuh.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gtztisgrzr.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gtyougthwm.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtsfhffrcb.html

[T45] Perl：数组遍历
来源：http://dali.jqgfzy.top/Article/details/gtmafuaesz.html

for my $x (@arr) { print $x; }
来源：http://dali.ivvv.top/Article/details/gtydluonbb.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gtvykhtkbp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daria6918.cn/Article/details/gtxonthwmt.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gtbenbkyfc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhongyouzk.top/Article/details/gtwshnqlbz.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtfgmevdqi.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gtwyavmxje.html

[T49] Perl：函数
来源：http://dali.yj20258888.top/Article/details/gtfermvnqn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtpddpenwd.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtihzlicdp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtielkassv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonlcrtvm.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gtgtvtlzlb.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtjzyocbzl.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gtqrlxyzxl.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtczgqispr.html

[T53] Scala：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtyuozhyqg.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtgoxwbbsm.html

[T54] Scala：集合映射
来源：http://dali.xuanzx.com/Article/details/gtfycelhek.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gtjauubvan.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtvgzfnsrx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtptakfvag.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gtsgfpyxyz.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtomxpvkgk.html

[T57] Scala：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtjgeeyqpi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.smart0.xyz/Article/details/gtzrcjgezf.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gtcumtcvxe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gtmqvjeueq.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gtmzmcuyms.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsofhculx.html

[T60] Scala：折叠
来源：http://dali.zycfv.cn/Article/details/gtolctrudw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gtihgnxyke.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttaiaxysk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtxtveohkd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxmknntoz.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gtghadxcqf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gtbwfcjkhg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gttxvlmnkb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gtggenfxcp.html

[U03] Py：加载 .env 配置
来源：http://dali.xuanzx.com/Article/details/gtvoryozzb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ppjwa.cn/Article/details/gtxfsaxsom.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtgqxujgzz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yangfankeji.com/Article/details/gtvijbpgkz.html

[U05] Py：列表去重且保序
来源：http://dali.vqdsnc.cn/Article/details/gtclzgzbqj.html

list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtfkhhfxlc.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gteluptqxl.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtpjwzrqnp.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gtmtbeonyt.html

{v: k for k, v in d.items()}
来源：http://dali.ydzc1.top/Article/details/gtvuclolmg.html

[U08] Py：展平二维列表
来源：http://dali.xuetiantiany.cn/Article/details/gttcmmdsjg.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gtxftdvwib.html

[U09] Py：字典取最大值的键
来源：http://dali.cqqwz.cn/Article/details/gtlaaikkkt.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gtuhjurcbv.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gturhzrceg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuetiantiany.cn/Article/details/gtrwizzjwa.html

[U11] Py：生成器表达式
来源：http://dali.dianchejie.cn/Article/details/gtebgforcl.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gttovytirt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jiagoushi.top/Article/details/gtkdduvqcc.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtrtlhhxcr.html

[U13] Py：固定长度队列
来源：http://dali.yonumen.top/Article/details/gtbrlyldrv.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gtfwywjdxl.html

[U14] Py：分组收集到列表
来源：http://dali.hnqzz.top/Article/details/gthidrgsbt.html

defaultdict(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlyvmqjj.html

[U15] Py：高精度计时
来源：http://dali.andypj.xyz/Article/details/gtpbajgryy.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gtfcuawmio.html

[U16] Py：命令行参数解析
来源：http://dali.xuanzx.com/Article/details/gtauyxysry.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shzxlz.cn/Article/details/gtsziiwiuq.html

[U17] Py：初始化日志
来源：http://dali.xinyue.icu/Article/details/gtfauhtupa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gtreowhcip.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gtcalcpfqw.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gtvorvwouc.html

[U19] Py：正则替换带回调
来源：http://dali.jqgfzy.top/Article/details/gteyldrqic.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hysaishi.cn/Article/details/gthqcijhat.html

[U20] Py：缓存函数结果
来源：http://dali.yvedp.cn/Article/details/gtedjlmdxp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gtfisgkpjq.html

[U21] Py：自定义上下文管理器
来源：http://dali.sxryk.cn/Article/details/gtnszitvic.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gthkhmrowf.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gtakhysbat.html

list(zip(*m))
来源：http://dali.svipenyu.cn/Article/details/gtbogyasuu.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gtoycvmsvk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gttfwjgxpe.html

[U24] Py：路径操作
来源：http://dali.gotoacloud.top/Article/details/gtxgtbthjg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtejnhrhok.html

[U25] Py：CSV 按字典读
来源：http://dali.zhixingplan.top/Article/details/gthofhltlk.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gtlqpsbezt.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gtrsvprdwn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gtjzwdplnn.html

[U27] Py：异步 HTTP
来源：http://dali.jianghu66.top/Article/details/gtogkibqsl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.0kj1m.cn/Article/details/gtzyycoqza.html

[U28] Py：类型别名
来源：http://dali.zhengqikj.top/Article/details/gtgzmtjbso.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gttgiwgikn.html

[U29] Py：属性校验
来源：http://dali.shzxlz.cn/Article/details/gtwfnafhnx.html

@property 与 @x.setter 配合
来源：http://dali.jinghuilouyu.cn/Article/details/gtswgcnope.html

[U30] Py：数据类
来源：http://dali.vqdsnc.cn/Article/details/gtlciznnrr.html

@dataclass(slots=True)
来源：http://dali.havefunace.top/Article/details/gtustenjff.html

[U31] Py：单测
来源：http://dali.hammf.cn/Article/details/gtmclroovz.html

python -m pytest -q
来源：http://dali.jyoumei.cn/Article/details/gtzojbyhsj.html

[U32] Py：代码格式化
来源：http://dali.zhongyouzk.top/Article/details/gtqebdesqs.html

ruff format . && ruff check --fix .
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcsrgpco.html

[U33] Py：打包发布
来源：http://dali.daxiang520.top/Article/details/gtnxufxjpn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shuidangran.top/Article/details/gtondkvyum.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gtgrtijubj.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gtoofaqhon.html

[U35] Py：发送邮件
来源：http://dali.zhengqikj.top/Article/details/gtdukogdah.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tianlin.xyz/Article/details/gtjcrwivkt.html

[U36] Py：定时任务
来源：http://dali.tian-w.cn/Article/details/gtampfshts.html

schedule.every(10).minutes.do(job)
来源：http://dali.birdmap.top/Article/details/gtukqzetuv.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gtwatviqov.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gtxooilnxv.html

[U38] Py：获取脚本所在目录
来源：http://dali.cheryme.top/Article/details/gtkfrirtwu.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gtfbmgzjip.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gtbfwtpyph.html

sys.stdout.isatty()
来源：http://dali.jqgufenzy.top/Article/details/gtlmtmhuyy.html

[U40] Py：打印到标准错误
来源：http://dali.jianghu66.top/Article/details/gteppctirm.html

print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtjwblytrb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxinkj.top/Article/details/gtnrwsuwfy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xziqi.cn/Article/details/gttsppiapr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yvedp.cn/Article/details/gtclsjuxuh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yangfankeji.com/Article/details/gtuiomspxf.html

[U43] PHP：声明命名空间
来源：http://dali.haohaochexian.top/Article/details/gtxjvoywih.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gtcihtyjrx.html

[U44] PHP：开启严格类型
来源：http://dali.feifeiyinyue.top/Article/details/gtvmwanjcy.html

declare(strict_types=1);
来源：http://dali.ppjwa.cn/Article/details/gtsvuhucsy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhengqikj.top/Article/details/gtkwewunbs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtzpepemvb.html

[U46] PHP：可空类型
来源：http://dali.gzhubu.top/Article/details/gtjuyqirqc.html

?string $name = null
来源：http://dali.jyoumei.cn/Article/details/gtnzkfffkq.html

[U47] PHP：联合类型
来源：http://dali.andypj.xyz/Article/details/gtcxjxfnvo.html

int|string $id
来源：http://dali.birdmap.top/Article/details/gtxmjrtfau.html

[U48] PHP：纯枚举
来源：http://dali.jyoumei.cn/Article/details/gtajmllacd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gtuahqsyxz.html

[U49] PHP：只读属性
来源：http://dali.jyoumei.cn/Article/details/gtuhqcoqnn.html

public readonly string $name
来源：http://dali.cucudq.cn/Article/details/gtzgkifdil.html

[U50] PHP：构造器属性提升
来源：http://dali.hongshengwenyu.top/Article/details/gtvilgamzw.html

public function __construct(private int $id) {}
来源：http://dali.chenzaomai.com/Article/details/gttizhrnyn.html

[U51] PHP：数组解构
来源：http://dali.bjfxy.top/Article/details/gtmyzslomm.html

[$a, $b] = $arr;
来源：http://dali.yj202588.top/Article/details/gtfxkysjsi.html

[U52] PHP：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gtyovfcygo.html

$double = fn($x) => $x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gtaetoebkq.html

[U53] PHP：空合并运算符
来源：http://dali.birdmap.top/Article/details/gtwzxgbfnb.html

$v = $a ?? $b ?? "default";
来源：http://dali.sysykeji.top/Article/details/gtaagthygc.html

[U54] PHP：空安全调用
来源：http://dali.shuidangran.top/Article/details/gtaxccklmt.html

$obj?->method()
来源：http://dali.nwbrower.top/Article/details/gtytmapfmf.html


<!-- 参考信息 -->