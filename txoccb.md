代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gt2rznaanlf.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gt2hravhumj.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2mqitlaau.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gt2kyfvhvpg.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gt2fwtuvkxz.html

[S29] C：变参函数
来源：http://dali.jyoumei.cn/Article/details/gt2wlhhtkxb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gt2zjoyxlov.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gt2zkipgtpc.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gt2xopneoav.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gt2yxhpnzpo.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbkkfuhx.html

[S31] C++：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2qsinjtmt.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gt2vikfqmcg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vlmwwxse.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2ninipcrt.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gt2ckwvempv.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gt2bpkatfpf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gt2trfwvdeb.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afyntqcx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vnvvekbv.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gt2cvckgxzc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2ghsulntt.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gt2gypzfqbq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdtrufiv.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gt2skafurbf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gt2cxsgsgqo.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gt2infwqkpz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gt2gihnnplu.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gt2prvuxsow.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gt2qejwpxtu.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gt2faytytni.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gt2klbbvloi.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gt2vtbpfqvp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gt2jnpbrpun.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gt2sbeckcbi.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gt2povmdien.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gt2svmkcomd.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gt2rpoqgqio.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gt2heajxwyp.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gt2ubjjebbg.html

[S45] C++：lambda
来源：http://dali.gzhubu.top/Article/details/gt2sgannytc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gt2zxrcwlgx.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gt2btlitezr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2moskyxmp.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gt2ubaxixqe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gt2hltlzubm.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2xguruvwl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gt2uesuygun.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gt2nnsqnhmy.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2nhetqslo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gt2smjclzpe.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gt2kroshznc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2mmnesrmd.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gt2khxqnksh.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gt2pgnwftwo.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gt2hcuwpgem.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2maeshaws.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gt2iuqkiutf.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gt2imhjprok.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gt2nmlfwnud.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gt2dgrvipmk.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gt2gphdrvvh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ramnetof.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gt2frxcxrux.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bzyhunol.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gt2ehesihwu.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xflbheie.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ludfgogf.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eahoumpg.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvlzsqru.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gt2tnwqovpi.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2yqcyhciv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2nrzosesf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2gvisopaw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gt2shegnjey.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2gryqnmnk.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2kihfbmhw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2asjkclvf.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gt2lumlsmtx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gt2wahxidhc.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gt2htaojhql.html

"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gt2atxhhnvg.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gt2gucjwptk.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gt2ehuwbrtu.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2wuebxifb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gt2ajmuyjem.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gt2tbecgmkx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2vtzgvili.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2coqviqch.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xubvacml.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2hxmmbrnz.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gt2rnnfxdiw.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gt2cqcwcktr.html

fun String.exclaim() = this + "!"
来源：http://dali.cqqwz.cn/Article/details/gt2bqweqqbr.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gt2rvmwpfcr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gt2chzadydp.html

[T11] Kotlin：协程
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldytqspg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gt2vegnuofu.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gt2ylfhwrtz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jyenslmr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2okloqmri.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gt2qnztuqsw.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkewiwje.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2prowirbp.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmfnhsjm.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gt2hczdlvmo.html

[T16] Swift：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxyxgkbi.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2efrlwqxk.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azwpteie.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrlouixi.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2ckoslwdy.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gt2gxyscsxp.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2peobwvdg.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gt2bcclbgbj.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gt2vnfdmqrc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gt2owwdmnwx.html

[T21] Swift：遍历
来源：http://dali.shuidangran.top/Article/details/gt2zhhtlehq.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gt2pdchyati.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gt2pxmnaats.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gt2mtwdyfcw.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gt2nbsgotmo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hammf.cn/Article/details/gt2wwxtxkda.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gt2dzqnxapw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2xtrhapii.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gt2mokalqxu.html

struct P { var x: Int }
来源：http://dali.yueranfly.top/Article/details/gt2dtpcpdtt.html

[T26] Swift：类与重写
来源：http://dali.yueranfly.top/Article/details/gt2nxgqeyfp.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gt2bqhyrivy.html

[T27] Swift：错误处理
来源：http://dali.jianghu66.top/Article/details/gt2fmdnhxbw.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gt2hzvanbzz.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2gifrhtgb.html

enum Color { case red, green }
来源：http://dali.zhoulong.xyz/Article/details/gt2qysguyzu.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gt2hfftrzoa.html

guard let x = opt else { return }
来源：http://dali.zhongyouzk.top/Article/details/gt2rfdjdafb.html

[T30] Swift：协议
来源：http://dali.pycfn.com/Article/details/gt2stwthszm.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gt2vvekctwu.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2zustrvip.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2dulfweis.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gt2fqnaesnb.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gt2ifqiobma.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gt2oyeprctv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jyoumei.cn/Article/details/gt2vlykghwv.html

[T34] Lua：遍历表
来源：http://dali.bjfxy.top/Article/details/gt2nfucqdyf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pevpsgwq.html

[T35] Lua：字典表
来源：http://dali.andypj.xyz/Article/details/gt2uwdyryjj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqnilnwq.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gt2sdukzxff.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2heydymwt.html

[T37] Lua：字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gt2njvysavl.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gt2dmecjjni.html

[T38] Lua：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yupscuqb.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gt2nppgwhlr.html

[T39] Lua：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qaqzzdat.html

string.find(s, "%d+")
来源：http://dali.yj20258.top/Article/details/gt2qkhmuofy.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gt2agnduisk.html

setmetatable({}, { __index = base })
来源：http://dali.yanxiufei.cn/Article/details/gt2uldnjjkw.html

[T41] Perl：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2zxbkdceg.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gt2opcwjzqh.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2naklpymt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqoxcir.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaecfwv.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gt2lfelmcyb.html

[T44] Perl：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmznenxn.html

if ($a > 0) { print "正"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xqyadzpp.html

[T45] Perl：数组遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahnebscd.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2smpzfiwg.html

[T46] Perl：哈希操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjuklrgg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kizpzltx.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gt2gnpcgpoz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gt2whabeizq.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2tuiuflxc.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvuxirzs.html

[T49] Perl：函数
来源：http://dali.fengsongda.top/Article/details/gt2nkoixeie.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2aojkrcdf.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2xhpqpuwe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gt2qloxbbnl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxuanxn.top/Article/details/gt2hlxeghys.html

[T51] Scala：Hello World
来源：http://dali.pycfn.com/Article/details/gt2bnmclsni.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2acgowggm.html

[T52] Scala：变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbkwncrb.html

val a = 1;  var b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlvppeed.html

[T53] Scala：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2wniemexa.html

s"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzqoqhcj.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2awjtgmmw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gt2hnhezdhk.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmjfeelb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2qteaoyhn.html

[T56] Scala：样例类
来源：http://dali.cheryme.top/Article/details/gt2etsjpviz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbltgzeu.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gt2vwkndalg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangdashe.top/Article/details/gt2ehiseruh.html

[T58] Scala：函数定义
来源：http://dali.chenzaomai.com/Article/details/gt2dfiswftg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangdashe.top/Article/details/gt2uoammfdv.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gt2crabqkuq.html

for (i <- 1 to 10) println(i)
来源：http://dali.iojbl.cn/Article/details/gt2ljfoypxh.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gt2jwcbnjcf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zssbtgtm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2rlwujtln.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2pqevzpti.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2hemvgylv.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gt2idrvgbne.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yongpay.top/Article/details/gt2cdrkwpwo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigufen.top/Article/details/gt2wectkhjy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gt2papwikgt.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gt2hziuohpo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2suunxjmv.html

[U04] Py：变量调试打印
来源：http://dali.pycfn.com/Article/details/gt2shylhdcw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yanxiufei.cn/Article/details/gt2vhtdszmw.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigufen.top/Article/details/gt2lexrbhkk.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gt2uwvkafbe.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gt2oogkzqug.html

{**a, **b}
来源：http://dali.xinyue.icu/Article/details/gt2nxjugvai.html

[U07] Py：反转字典键值
来源：http://dali.hnqzz.top/Article/details/gt2vexzmykr.html

{v: k for k, v in d.items()}
来源：http://dali.sufxvd.cn/Article/details/gt2baitfyts.html

[U08] Py：展平二维列表
来源：http://dali.havefunace.top/Article/details/gt2rehpruvv.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gt2wyiaaxpw.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gt2wtniugwt.html

max(d, key=d.get)
来源：http://dali.zhengqikj.top/Article/details/gt2uhnhxkyp.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvugqwqn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenjidiqi.icu/Article/details/gt2plwqsakb.html

[U11] Py：生成器表达式
来源：http://dali.sxryk.cn/Article/details/gt2nbelorbu.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gt2mxojutld.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gt2tcnzplbq.html

Counter(arr).most_common(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2zsnasgbi.html

[U13] Py：固定长度队列
来源：http://dali.yanxiufei.cn/Article/details/gt2cvtigoag.html

deque(maxlen=10)
来源：http://dali.vqdsnc.cn/Article/details/gt2mjujoaip.html

[U14] Py：分组收集到列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddqvytbk.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gt2piigzhnv.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gt2kedhnpqn.html

t = time.perf_counter()
来源：http://dali.gzhubu.top/Article/details/gt2ifcszqfc.html

[U16] Py：命令行参数解析
来源：http://dali.xuanzx.com/Article/details/gt2xhriwicv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gt2nspzztqi.html

[U17] Py：初始化日志
来源：http://dali.haohaochexian.top/Article/details/gt2tylgoiss.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azqegefg.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gt2uibqrgzk.html

pat = re.compile(r"\d+")
来源：http://dali.andypj.xyz/Article/details/gt2jbemxlbn.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gt2yzbhwaax.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhoulong.xyz/Article/details/gt2htvewuot.html

[U20] Py：缓存函数结果
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxbitnqv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gt2qzepgdml.html

[U21] Py：自定义上下文管理器
来源：http://dali.mhx1999.top/Article/details/gt2fadmutak.html

@contextlib.contextmanager
来源：http://dali.tianlin.xyz/Article/details/gt2wljkhzac.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gt2booymkmp.html

list(zip(*m))
来源：http://dali.tanke756.top/Article/details/gt2uvgambsl.html

[U23] Py：分块读取大文件
来源：http://dali.sweek.top/Article/details/gt2hsdpuafd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tianlin.xyz/Article/details/gt2ohfidevi.html

[U24] Py：路径操作
来源：http://dali.cashguo.top/Article/details/gt2gostjcel.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gt2fujjlujd.html

[U25] Py：CSV 按字典读
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddvyfaco.html

csv.DictReader(f)
来源：http://dali.yueranfly.top/Article/details/gt2mrezorgt.html

[U26] Py：并发下载
来源：http://dali.kuanghao11.cn/Article/details/gt2bpgmqijo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gt2bwhponwk.html

[U27] Py：异步 HTTP
来源：http://dali.yvedp.cn/Article/details/gt2plojnmpj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdopdeia.html

[U28] Py：类型别名
来源：http://dali.gaohongyu789.top/Article/details/gt2bmhlbbmc.html

UserId = int
来源：http://dali.hysaishi.cn/Article/details/gt2ccjnzarf.html

[U29] Py：属性校验
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbrayzfh.html

@property 与 @x.setter 配合
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkvnokco.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gt2lqlcdwgn.html

@dataclass(slots=True)
来源：http://dali.sufxvd.cn/Article/details/gt2lskbkpwy.html

[U31] Py：单测
来源：http://dali.guowangkeji.top/Article/details/gt2fargmndf.html

python -m pytest -q
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sukjnvot.html

[U32] Py：代码格式化
来源：http://dali.dashuyun.cn/Article/details/gt2jtbvyerh.html

ruff format . && ruff check --fix .
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngitewus.html

[U33] Py：打包发布
来源：http://dali.svipenyu.cn/Article/details/gt2wjqyeqrx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258888.top/Article/details/gt2glnyueob.html

[U34] Py：判断编码
来源：http://dali.yangfankeji.com/Article/details/gt2kvbonrro.html

chardet.detect(raw)
来源：http://dali.ppjwa.cn/Article/details/gt2fsyxmwil.html

[U35] Py：发送邮件
来源：http://dali.tanke756.top/Article/details/gt2gcjubvcw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xinyue.icu/Article/details/gt2zarkaxpk.html

[U36] Py：定时任务
来源：http://dali.chenlongwang.top/Article/details/gt2poiregta.html

schedule.every(10).minutes.do(job)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggpcrwlb.html

[U37] Py：读写 Excel
来源：http://dali.haohaochexian.top/Article/details/gt2vcuagouq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxxkbmgl.html

[U38] Py：获取脚本所在目录
来源：http://dali.tianlin.xyz/Article/details/gt2rgxzxsek.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aafuckze.html

[U39] Py：判断是否在交互环境
来源：http://dali.aibaodan.cn/Article/details/gt2zyfgbflf.html

sys.stdout.isatty()
来源：http://dali.jinqigfzy.top/Article/details/gt2ariigdmp.html

[U40] Py：打印到标准错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2kulobtrn.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gt2gjdezlrd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysqsmnmq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gaohongyu789.top/Article/details/gt2hwyntzvj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jlsjyb.cn/Article/details/gt2wwnunhqk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.vqdsnc.cn/Article/details/gt2sarogyzt.html

[U43] PHP：声明命名空间
来源：http://dali.cheryme.top/Article/details/gt2pqpmjqsl.html

namespace App\Http;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lkfzrcri.html

[U44] PHP：开启严格类型
来源：http://dali.daxiang520.top/Article/details/gt2cmpwztzv.html

declare(strict_types=1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzrmwwpg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2szcuhmwp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gt2kzjlemib.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gt2xhdangwf.html

?string $name = null
来源：http://dali.jqgufenzy.top/Article/details/gt2pkyykajj.html

[U47] PHP：联合类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrszyrse.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gt2mpxeygtr.html

[U48] PHP：纯枚举
来源：http://dali.cheryme.top/Article/details/gt2ehwyuchk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hysaishi.cn/Article/details/gt2zddronnk.html

[U49] PHP：只读属性
来源：http://dali.haohaochexian.top/Article/details/gt2vcmrgsol.html

public readonly string $name
来源：http://dali.cashguo.top/Article/details/gt2cwthagkl.html

[U50] PHP：构造器属性提升
来源：http://dali.vqdsnc.cn/Article/details/gt2phfcsswd.html

public function __construct(private int $id) {}
来源：http://dali.jyoumei.cn/Article/details/gt2pajqxcrl.html


<!-- 参考信息 -->