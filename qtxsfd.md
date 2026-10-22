代发 wailian999

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gt2lkgvioxc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gt2qkjsoufb.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2buxfjekz.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gt2senzbtzf.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gt2ttrdcjqq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gt2qpxospro.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gt2twynmeti.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gt2gwelwdna.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gt2xauvxjla.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2jgmhrzjr.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gt2wkmlnkxd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2nxtmaiqf.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gt2vmakjqvp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gt2qjkvrsjm.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gt2asgheqzf.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gt2sullwqbc.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gt2cpydcjsp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gt2wjxrvvix.html

[S40] C++：查找元素
来源：http://dali.aibaodan.cn/Article/details/gt2mujjghfd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jylsousb.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2fbwbbuwc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gt2xsdsmjla.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gt2mjqchtwe.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigfzy.top/Article/details/gt2qjdkgoln.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gt2uqyzpamu.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gt2zsuhjgkz.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzlnifut.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccmnmpaz.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gt2xywcmsrq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gt2hghnhcjh.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gt2ylnlxptc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptsjylpz.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gt2gjdyctvj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gt2pozqbksm.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2vlmxfksb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2wiqkxcyk.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2yqzpgfgp.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gt2riyenqlz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gt2hiavklov.html

[S50] C++：格式化数字
来源：http://dali.kuanghao11.cn/Article/details/gt2zubxeeld.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2cpolyhmt.html

[S51] C++：显式类型转换
来源：http://dali.zhongyouzk.top/Article/details/gt2ivggsrfs.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gt2iqjtpphg.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gt2khlndhfy.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gt2gurepkng.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gt2ubvlebdc.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gt2korbvsmp.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gt2wvpqfgum.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gt2jhrwxlzr.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gt2alzxdngf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gt2tpgkujaz.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gt2stvrakxb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gt2ykqkckja.html

[S57] C++：编译期常量
来源：http://dali.xziqi.cn/Article/details/gt2szqlxwdy.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzuynddk.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gt2idbhdlfp.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gt2ejvikguh.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gt2nouqgiqz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gt2serzovyu.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gt2fepqfeem.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cucudq.cn/Article/details/gt2qnfvjyaa.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2gmjnmrpt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnsajnop.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2sevqmiwy.html

[T01] Kotlin：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgcuuhsq.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2mmjarzky.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqzwffoi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gt2oakdnkbi.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfoqnbcz.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gt2grmjjvlg.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gt2xhaunbxw.html

val n: String? = null;  n?.length
来源：http://dali.vqdsnc.cn/Article/details/gt2ygcvfwwl.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gt2bsfdhcvi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gt2ctdsnzuw.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gt2gdzynmyx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2zwsnwxxn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2dpakqtlb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gt2tbltdzsy.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehnjchkq.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gt2tueyqonl.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigufen.top/Article/details/gt2ssgyrdez.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gt2gjzspwlg.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gt2aadufdge.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohmbezur.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gt2akmwsdls.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gt2biverdgt.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gt2nplydags.html

val (a, b) = Pair(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2ikxxxaek.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gt2coshkcfq.html

val m = mapOf("a" to 1)
来源：http://dali.yvedp.cn/Article/details/gt2whthgogb.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gt2jiorotsh.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gt2vqjagjxw.html

[T15] Kotlin：接口
来源：http://dali.ppjwa.cn/Article/details/gt2lrrpylek.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gt2tbshposh.html

[T16] Swift：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2usjxuggh.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2bbqqqhlw.html

[T17] Swift：变量与常量
来源：http://dali.jqgfzy.top/Article/details/gt2qsibofln.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2dwjymirb.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2aiybesnw.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gt2mdgzezdp.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gt2ierstuog.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gt2tkjyuopm.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gt2mrzrpmim.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gt2mqaecpkc.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gt2swalilgv.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gt2fnwsdnfh.html

[T22] Swift：字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnyoahcc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daxiang520.top/Article/details/gt2icxnngbq.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gt2lmzanwct.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gt2fkeqdswv.html

[T24] Swift：闭包
来源：http://dali.havefunace.top/Article/details/gt2xfowfwqx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gt2bmdmepkl.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gt2ldpendeg.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gt2jtquvkoy.html

[T26] Swift：类与重写
来源：http://dali.cucudq.cn/Article/details/gt2vvsdvvrg.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gt2hyfiupqu.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gt2vniisfeq.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yiobohij.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2bvanjyrw.html

enum Color { case red, green }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqxhuzor.html

[T29] Swift：guard 提前返回
来源：http://dali.xuanzx.com/Article/details/gt2ipdvibur.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gt2ncvoarnq.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gt2oedpseua.html

protocol Shape { func area() -> Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2xebmxihx.html

[T31] Lua：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2vytwrazv.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsiuqlrk.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gt2plqahqzw.html

local a = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwuplvto.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gt2eazsupfn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnvvjolz.html

[T34] Lua：遍历表
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfrkjuid.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.316326.xyz/Article/details/gt2hcioxnwm.html

[T35] Lua：字典表
来源：http://dali.fengsongda.top/Article/details/gt2ihwneofh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gt2qmaljhfl.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gt2jdukqmcg.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gt2ygjggsvg.html

[T37] Lua：字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gt2kndlgftz.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gt2nedkneut.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gt2ipwkhngr.html

if x > 0 then print("正") end
来源：http://dali.hywenlv.cn/Article/details/gt2txmabibw.html

[T39] Lua：模式匹配
来源：http://dali.shuidangran.top/Article/details/gt2onpegjxb.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crviytqn.html

[T40] Lua：元表
来源：http://dali.shzxlz.cn/Article/details/gt2mprheywi.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gt2gygstvwn.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2dqnfxikr.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gt2ssthtzro.html

[T42] Perl：变量类型
来源：http://dali.cashguo.top/Article/details/gt2jsjqnbfz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gt2kqjevnok.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2aldzcumy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uofwdbhm.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gt2fkbqiyyy.html

if ($a > 0) { print "正"; }
来源：http://dali.nwbrower.top/Article/details/gt2zevvaosc.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gt2odfwdgiz.html

for my $x (@arr) { print $x; }
来源：http://dali.daria6918.cn/Article/details/gt2bdxdvbyz.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjjwlhiv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gt2twrdacdk.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gt2uwpevfnq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenzaomai.com/Article/details/gt2azucmhyi.html

[T48] Perl：正则替换
来源：http://dali.yuxming.cn/Article/details/gt2nurudbfe.html

$s =~ s/old/new/g;
来源：http://dali.xuanzx.com/Article/details/gt2ycnhwagq.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gt2fqujbuip.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2yjlgfmbd.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2ohfvslwb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndrgzglw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gt2lrmfxdvi.html

[T51] Scala：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2blfivhuh.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2ukqwdgvn.html

[T52] Scala：变量
来源：http://dali.cucudq.cn/Article/details/gt2niupmvvv.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gt2xmggiszp.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxtccrqu.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gt2pclrfgmh.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gt2gupgzehy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2lvutfwab.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gt2xebpgqqr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gt2iuouiloo.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gt2lpebkmaq.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2rnofyrsn.html

[T57] Scala：模式匹配
来源：http://dali.yj202588.top/Article/details/gt2rmmsanvo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gt2aickggoh.html

[T58] Scala：函数定义
来源：http://dali.hysaishi.cn/Article/details/gt2awkwhdhc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gt2kceuzmnt.html

[T59] Scala：循环
来源：http://dali.vqdsnc.cn/Article/details/gt2epyarmbh.html

for (i <- 1 to 10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugqcpokw.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gt2ilxijnya.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gt2kcswytre.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2fiziaobp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gt2ukxfwxbx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2lqppzivc.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gt2cdhnjjoy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgufenzy.top/Article/details/gt2mexrlnnd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cheryme.top/Article/details/gt2ntwtyywo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbidqvbk.html

[U03] Py：加载 .env 配置
来源：http://dali.jlsjyb.cn/Article/details/gt2azflwfgi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jlsjyb.cn/Article/details/gt2pjthqnel.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nloykmnd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hysaishi.cn/Article/details/gt2zugqzqdv.html

[U05] Py：列表去重且保序
来源：http://dali.snrcjt.cn/Article/details/gt2kkmwgqyn.html

list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2nmnbyovc.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gt2bgzvpshk.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gt2avrmujhx.html

[U07] Py：反转字典键值
来源：http://dali.yj20258.top/Article/details/gt2yquwohuy.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gt2czxslunf.html

[U08] Py：展平二维列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veqgcfeb.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gt2ajpkyamt.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gt2yevfynsz.html

max(d, key=d.get)
来源：http://dali.zhoulong.xyz/Article/details/gt2pyhateji.html

[U10] Py：按值排序字典
来源：http://dali.snrcjt.cn/Article/details/gt2npjjysht.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxinkj.top/Article/details/gt2mcgtjoci.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gt2vnxmxrmg.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxedlooe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pycfn.com/Article/details/gt2feaknxjt.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2uaparaqh.html

[U13] Py：固定长度队列
来源：http://dali.ppjwa.cn/Article/details/gt2rfbhtxlr.html

deque(maxlen=10)
来源：http://dali.kuanghao11.cn/Article/details/gt2udcjuuwn.html

[U14] Py：分组收集到列表
来源：http://dali.gogol.net.cn/Article/details/gt2qxtthmwp.html

defaultdict(list)
来源：http://dali.cdnleiting.top/Article/details/gt2dluuljxo.html

[U15] Py：高精度计时
来源：http://dali.yj202588.top/Article/details/gt2wxphclpl.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gt2mwbqjrkf.html

[U16] Py：命令行参数解析
来源：http://dali.kuanghao11.cn/Article/details/gt2yfaztjtj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfqkxozm.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gt2whxkmbdl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daxiang520.top/Article/details/gt2wcgnaqsj.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msxtnria.html

pat = re.compile(r"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qehdioqg.html

[U19] Py：正则替换带回调
来源：http://dali.guowangkeji.top/Article/details/gt2izbttyii.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hnqzz.top/Article/details/gt2nbugfcaz.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gt2sepvpltc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ybcxt.top/Article/details/gt2wqngozsl.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangdashe.top/Article/details/gt2lgfdqkmq.html

@contextlib.contextmanager
来源：http://dali.jiagoushi.top/Article/details/gt2vmdpxocg.html

[U22] Py：矩阵转置
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrcfsgrb.html

list(zip(*m))
来源：http://dali.ybcxt.top/Article/details/gt2ofaihxuz.html

[U23] Py：分块读取大文件
来源：http://dali.nanxinkj.top/Article/details/gt2mdueagsb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gt2dicpijrm.html

[U24] Py：路径操作
来源：http://dali.ydzc1.top/Article/details/gt2govynlln.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gt2joyddwzq.html

[U25] Py：CSV 按字典读
来源：http://dali.jianghu66.top/Article/details/gt2ivqbakzx.html

csv.DictReader(f)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wykzpruw.html

[U26] Py：并发下载
来源：http://dali.jianghu66.top/Article/details/gt2ngxedxyf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gt2jxuacwqb.html

[U27] Py：异步 HTTP
来源：http://dali.jqgfzy.top/Article/details/gt2gawwohpf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yvedp.cn/Article/details/gt2bjutxknx.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gt2yjcybznw.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gt2hhbioocv.html

[U29] Py：属性校验
来源：http://dali.zhongyouzk.top/Article/details/gt2eetepgqa.html

@property 与 @x.setter 配合
来源：http://dali.tianlin.xyz/Article/details/gt2xtresvgd.html

[U30] Py：数据类
来源：http://dali.bjfxy.top/Article/details/gt2atojqadl.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2zfuziiqx.html

[U31] Py：单测
来源：http://dali.cheryme.top/Article/details/gt2batobduc.html

python -m pytest -q
来源：http://dali.gzhubu.top/Article/details/gt2aqiaepcw.html

[U32] Py：代码格式化
来源：http://dali.yuxming.cn/Article/details/gt2vlyukoto.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gt2ytokzgpc.html

[U33] Py：打包发布
来源：http://dali.cdnleiting.top/Article/details/gt2tlzijvfq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apxisbxp.html

[U34] Py：判断编码
来源：http://dali.cdnleiting.top/Article/details/gt2ajvrqxmc.html

chardet.detect(raw)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkbaobse.html

[U35] Py：发送邮件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fvrsktwd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.mhx1999.top/Article/details/gt2ebmscbwe.html

[U36] Py：定时任务
来源：http://dali.yvedp.cn/Article/details/gt2srjwhxsz.html

schedule.every(10).minutes.do(job)
来源：http://dali.svipenyu.cn/Article/details/gt2gpyaaimc.html

[U37] Py：读写 Excel
来源：http://dali.nanxinkj.top/Article/details/gt2msvfgjms.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nanxinkj.top/Article/details/gt2hpamgrkh.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2zinbeiqs.html

Path(__file__).resolve().parent
来源：http://dali.guowangkeji.top/Article/details/gt2lubtzsil.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gt2popwxxrc.html

sys.stdout.isatty()
来源：http://dali.andypj.xyz/Article/details/gt2awkezloc.html

[U40] Py：打印到标准错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrdiuclv.html

print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gt2tzlyukog.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gt2sbdaqrme.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hysaishi.cn/Article/details/gt2kqzfboht.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cdnleiting.top/Article/details/gt2rrpzdhzz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.svipenyu.cn/Article/details/gt2wabpertr.html

[U43] PHP：声明命名空间
来源：http://dali.aizwys.cn/Article/details/gt2tglurvbk.html

namespace App\Http;
来源：http://dali.haohaochexian.top/Article/details/gt2ulzpqcfu.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigufen.top/Article/details/gt2azzpuuew.html

declare(strict_types=1);
来源：http://dali.kuanghao11.cn/Article/details/gt2mwkwfxal.html

[U45] PHP：类型声明与返回类型
来源：http://dali.snrcjt.cn/Article/details/gt2fqfcwhkh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2bxcdkcto.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gt2tuooxoag.html

?string $name = null
来源：http://dali.tian-w.cn/Article/details/gt2eozifdlt.html

[U47] PHP：联合类型
来源：http://dali.fzhhl.top/Article/details/gt2xhvkpzvf.html

int|string $id
来源：http://dali.havefunace.top/Article/details/gt2zguaxvna.html

[U48] PHP：纯枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2dgvpuspy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yonumen.top/Article/details/gt2iugrabvp.html

[U49] PHP：只读属性
来源：http://dali.fengsongda.top/Article/details/gt2ppidncli.html

public readonly string $name
来源：http://dali.yuxming.cn/Article/details/gt2cxaffqnl.html

[U50] PHP：构造器属性提升
来源：http://dali.mhx1999.top/Article/details/gt2mdatwbzd.html

public function __construct(private int $id) {}
来源：http://dali.chenlongwang.top/Article/details/gt2zolzmjxp.html

[U51] PHP：数组解构
来源：http://dali.hfpthk.cn/Article/details/gt2pbdortqy.html

[$a, $b] = $arr;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvuitals.html

[U52] PHP：箭头函数
来源：http://dali.zycfv.cn/Article/details/gt2nkzyekzd.html

$double = fn($x) => $x * 2;
来源：http://dali.iojbl.cn/Article/details/gt2hfpiidov.html

[U53] PHP：空合并运算符
来源：http://dali.haohaochexian.top/Article/details/gt2ylcurips.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenlongwang.top/Article/details/gt2dzmucoxq.html

[U54] PHP：空安全调用
来源：http://dali.9152youxi.cn/Article/details/gt2nafcrrsg.html

$obj?->method()
来源：http://dali.yuxming.cn/Article/details/gt2zmtjabts.html

[U55] PHP：match 表达式
来源：http://dali.yangfankeji.com/Article/details/gt2fnretpcj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ydzc1.top/Article/details/gt2jvedfmus.html

[U56] PHP：命名参数
来源：http://dali.9152youxi.cn/Article/details/gt2mdmkykkm.html

f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gt2aahwysks.html


<!-- 参考信息 -->