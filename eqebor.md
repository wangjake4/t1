代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtggwhdjws.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gtkvapvlqs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gtuabahbys.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gtspapbkbf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gtqtmrnvby.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gtjhcafhev.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtudewolmu.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gtzgimujjl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gtwhxnpkxh.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gtkqeogafr.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtcdkjorsl.html

[S26] C：内存清零
来源：http://dali.aizwys.cn/Article/details/gttlzqhxix.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtactxqxqb.html

[S27] C：定义常量
来源：http://dali.aizwys.cn/Article/details/gtzyzhdmjm.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtzttydxdz.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtmdjxorap.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gthsmtvcur.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gtbujgrjhp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtubqfmsas.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gtirdlwgft.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gtmacnkybh.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gtehqiflsz.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssagitrl.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtvatdjxqw.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gtarbvnaws.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fengsongda.top/Article/details/gtdxeyvrme.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtukeskkjk.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtrpxlqdfe.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gtgnrjorfa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtknaqkscg.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gtrxprutdy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtsgywhmjc.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtadixrxtd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gthwjigzmf.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gthfevjbmd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtnjglbfbf.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtxizayrzc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gttlvucgem.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtiinsbnhs.html

std::sort(v.begin(), v.end());
来源：http://dali.yueranfly.top/Article/details/gtinckrynt.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gtuubvehhk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gttaowiavo.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gtonktjfen.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnwicqwe.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtpgeuxjuw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gtypdsgrax.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtrsjvyxym.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtjzgkldvj.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gtqzgadwfe.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuanzx.com/Article/details/gtmlefqjvh.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeepfhvn.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpwoesnj.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gtemcmgeko.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gtvpkvhhio.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtmqcxpksf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtiyvkelia.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtvbedgcru.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gtbyebuqih.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtwktvcquu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuetiantiany.cn/Article/details/gtglrcqdtg.html

while (std::getline(in, line)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtshhefakd.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcnupdbd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gtlseskymh.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwsrctlv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtlwvbsnqw.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gtwjpolxso.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gtpryxmekz.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gtxeqheutm.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtundajsjq.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gtljekkbev.html

std::vector<int> w = std::move(v);
来源：http://dali.xuetiantiany.cn/Article/details/gtrbdteipq.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gtrmxhchyr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigfzy.top/Article/details/gtgsuxgwyk.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gtcaflfqld.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gtltgjwopo.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gtroooqljc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtcryjneuz.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtbzbdflhe.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gteluvddfk.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gtpntecgff.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtgdjceerx.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gturwynxay.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcefmemc.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gteoovhhkw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtntnrseqt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtssumcxmc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtmfqcnall.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgpcybalp.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gtjzeixxrw.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gteurgoyct.html

[T02] Kotlin：变量
来源：http://dali.hammf.cn/Article/details/gtjhfexppc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gtejfhtprj.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gttqeapduq.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtlbajhzoi.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtqnkjofkk.html

val n: String? = null;  n?.length
来源：http://dali.jianghu66.top/Article/details/gtfhibkgre.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gtgivzduhh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aizwys.cn/Article/details/gtiopvsbod.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gtmwaarywu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gtqkiiktbd.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtbsibyeui.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gthpzdynel.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gtohovomlu.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtfnsoptin.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gticpwpuom.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gtkpboyzlc.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtvsuwbckr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtoemhkeis.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gtaqotgyeq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gtpaoyzcuh.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gtlmjjrrlb.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtcarrqflm.html

[T13] Kotlin：只读 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtotxsvxdd.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtmusvcjdg.html

[T14] Kotlin：循环
来源：http://dali.svipenyu.cn/Article/details/gtdrinvxyf.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gtofmhphhp.html

[T15] Kotlin：接口
来源：http://dali.shangyingyoupin.top/Article/details/gtwlyixtkx.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtqnajbrqn.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtqhjzywam.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtfxuyxrby.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gthkssdycn.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gtldlmkqsy.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtbrkublsv.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gthfhsleem.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gtdgknezvx.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gtwbgvgnsi.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gtuzbewwak.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gtcpuvzisf.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gtvamtvjpy.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gtwhtwbocq.html

[T22] Swift：字典
来源：http://dali.guannengcc.top/Article/details/gtxedwixrs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj202588.top/Article/details/gtcvrhwgmn.html

[T23] Swift：函数
来源：http://dali.dianchejie.cn/Article/details/gtsoendhch.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gtvtonhdag.html

[T24] Swift：闭包
来源：http://dali.yonumen.top/Article/details/gtqqowtnru.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtjsfkjudq.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gttqqkselq.html

struct P { var x: Int }
来源：http://dali.sweek.top/Article/details/gtkhvqvavu.html

[T26] Swift：类与重写
来源：http://dali.yangfankeji.com/Article/details/gtwtzpxdzl.html

class A: Base { override func f() {} }
来源：http://dali.sysykeji.top/Article/details/gtbqjtbqwk.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtrqliwwpx.html

do { try f() } catch { print(error) }
来源：http://dali.sysykeji.top/Article/details/gtajccmbxj.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gtrjfrbpgo.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gthhvtjiwt.html

[T29] Swift：guard 提前返回
来源：http://dali.nwbrower.top/Article/details/gtihhzifsd.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gtgdvfalmv.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gtuctvnnai.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gtgkkyeriq.html

[T31] Lua：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtvwfwbhon.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gturtltsjx.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtnxhpxpvj.html

local a = 1
来源：http://dali.xylfe.cn/Article/details/gtggxxlkgc.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gtfbigkrbg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gtzkgklntx.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkqajnhh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.316326.xyz/Article/details/gtyjgzytub.html

[T35] Lua：字典表
来源：http://dali.zhengqikj.top/Article/details/gtydyelhgs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gthjikohbr.html

[T36] Lua：函数
来源：http://dali.cdnleiting.top/Article/details/gttjyphxvb.html

function add(a, b) return a + b end
来源：http://dali.zycfv.cn/Article/details/gtobqydweh.html

[T37] Lua：字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtpgodtdec.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtjrumzbjl.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtoediavaw.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gtryrrdysk.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtlezqyhvo.html

string.find(s, "%d+")
来源：http://dali.vqdsnc.cn/Article/details/gthqmkogpv.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gtgiafaydi.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gtgjbaefpa.html

[T41] Perl：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtdakwpghl.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gtpyoyoznk.html

[T42] Perl：变量类型
来源：http://dali.yuxming.cn/Article/details/gteycqilrf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ybcxt.top/Article/details/gtuujnunix.html

[T43] Perl：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtqfozvaga.html

"值: $a"
来源：http://dali.zycfv.cn/Article/details/gtwuudtful.html

[T44] Perl：条件
来源：http://dali.yangfankeji.com/Article/details/gtsukslnqv.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtiuicyuad.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtdrgevlpq.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gtilplbyel.html

[T46] Perl：哈希操作
来源：http://dali.cashguo.top/Article/details/gtowscezne.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gtkpfxjcpj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gtkabjgzoc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gtqctuholv.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gtwuvhdfkh.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gteqdzxxfg.html

[T49] Perl：函数
来源：http://dali.yonumen.top/Article/details/gtziriifjx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtdenmsurq.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtsoweyozo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dashuyun.cn/Article/details/gtqyurkkhm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsuyjxlpa.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gtukokvevk.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtvyormgnn.html

[T52] Scala：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasxceukb.html

val a = 1;  var b = 2
来源：http://dali.dianchejie.cn/Article/details/gtvqrjxvqf.html

[T53] Scala：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gttwtsrnfr.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtiskyiuvz.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtsiprvqor.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtorlhsnrp.html

[T55] Scala：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gttdxhciev.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gtlylggigo.html

[T56] Scala：样例类
来源：http://dali.wangshuangyany.cn/Article/details/gtxfyxchnx.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtgttzgyvi.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtsdkeozue.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gtmujijdjk.html

[T58] Scala：函数定义
来源：http://dali.birdmap.top/Article/details/gtxdzdlqvi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtwnfcapjw.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gttzbsevbz.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtevnehfix.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gtfttjesen.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtppghryxw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmkhiqhpa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gtxblkrvdn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpcxxjets.html

[U01] Py：创建虚拟环境
来源：http://dali.bjfxy.top/Article/details/gtpmqxrica.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.mhx1999.top/Article/details/gtzsrnudtc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.haohaochexian.top/Article/details/gtucoestlg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtjhliqkmw.html

[U03] Py：加载 .env 配置
来源：http://dali.yuxming.cn/Article/details/gtgfbjqwhq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aibaodan.cn/Article/details/gtuekthwpy.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmimxrip.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gtlofcuvvx.html

[U05] Py：列表去重且保序
来源：http://dali.yuxming.cn/Article/details/gtpdoemqwr.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtbcixhtgm.html

[U06] Py：合并两个字典
来源：http://dali.jinqigufen.top/Article/details/gtfufdpwiq.html

{**a, **b}
来源：http://dali.yanxiufei.cn/Article/details/gtnrihykog.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gtlkkhrstk.html

{v: k for k, v in d.items()}
来源：http://dali.sysykeji.top/Article/details/gtzzrcxfjo.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrehlovoq.html

[y for x in nested for y in x]
来源：http://dali.0kj1m.cn/Article/details/gtuoiyhrct.html

[U09] Py：字典取最大值的键
来源：http://dali.chenjidiqi.icu/Article/details/gtnzfunkez.html

max(d, key=d.get)
来源：http://dali.wangdashe.top/Article/details/gtpfpycyrg.html

[U10] Py：按值排序字典
来源：http://dali.nanxinkj.top/Article/details/gtzqbqrxxg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gttuynbevl.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtmknazmxu.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrusmnrpj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gtrinzbrce.html

Counter(arr).most_common(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtoqcghamt.html

[U13] Py：固定长度队列
来源：http://dali.daria6918.cn/Article/details/gtpcwvhtax.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjbkgmxk.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gtzwcmxdgp.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gtulajstwz.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gtrglydnvv.html

t = time.perf_counter()
来源：http://dali.daxiang520.top/Article/details/gtmwueirpd.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gtrastfrug.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guannengcc.top/Article/details/gtbydknppq.html

[U17] Py：初始化日志
来源：http://dali.jiagoushi.top/Article/details/gtbzbbnils.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhoulong.xyz/Article/details/gtlecscqoe.html

[U18] Py：预编译正则
来源：http://dali.zhongyouzk.top/Article/details/gtdzfreajd.html

pat = re.compile(r"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtnemduwhb.html

[U19] Py：正则替换带回调
来源：http://dali.smart0.xyz/Article/details/gtcavfinmb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigufen.top/Article/details/gtxenxkpuw.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gthlxnhsdn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxinkj.top/Article/details/gtufpfdkai.html

[U21] Py：自定义上下文管理器
来源：http://dali.tian-w.cn/Article/details/gtyijnqgyv.html

@contextlib.contextmanager
来源：http://dali.bjfxy.top/Article/details/gtttkcgjgw.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gttqneourn.html

list(zip(*m))
来源：http://dali.dianchejie.cn/Article/details/gtszevppkk.html

[U23] Py：分块读取大文件
来源：http://dali.shuidangran.top/Article/details/gtfqeeaxut.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvlsxgkz.html

[U24] Py：路径操作
来源：http://dali.yvedp.cn/Article/details/gtswhslafw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtavwsmbye.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gtvsqzwdlm.html

csv.DictReader(f)
来源：http://dali.cucudq.cn/Article/details/gtvqhxipbn.html

[U26] Py：并发下载
来源：http://dali.dashuyun.cn/Article/details/gttxeahsxt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gthususzna.html

[U27] Py：异步 HTTP
来源：http://dali.dianchejie.cn/Article/details/gtltrvghcp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.0kj1m.cn/Article/details/gtkdtfoskc.html

[U28] Py：类型别名
来源：http://dali.sufxvd.cn/Article/details/gtacxjskxj.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtbfauuxzz.html

[U29] Py：属性校验
来源：http://dali.tian-w.cn/Article/details/gtcwofistz.html

@property 与 @x.setter 配合
来源：http://dali.meibo888.top/Article/details/gtmoofsxhi.html

[U30] Py：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtfnyijsax.html

@dataclass(slots=True)
来源：http://dali.yvedp.cn/Article/details/gtqycataqu.html

[U31] Py：单测
来源：http://dali.0kj1m.cn/Article/details/gtefoscers.html

python -m pytest -q
来源：http://dali.chenjidiqi.icu/Article/details/gtqzyzdnxp.html

[U32] Py：代码格式化
来源：http://dali.kuanghao11.cn/Article/details/gtoootzhux.html

ruff format . && ruff check --fix .
来源：http://dali.dashuyun.cn/Article/details/gtihrmpmsq.html

[U33] Py：打包发布
来源：http://dali.zycfv.cn/Article/details/gtaibfcygq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhengqikj.top/Article/details/gtsteycgtj.html

[U34] Py：判断编码
来源：http://dali.yuxming.cn/Article/details/gtfkfsexfa.html

chardet.detect(raw)
来源：http://dali.xylfe.cn/Article/details/gtdhkwkcrd.html

[U35] Py：发送邮件
来源：http://dali.ybcxt.top/Article/details/gtsrdzybck.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hysaishi.cn/Article/details/gtqsinhukp.html

[U36] Py：定时任务
来源：http://dali.hysaishi.cn/Article/details/gtfjcabctu.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigufen.top/Article/details/gtakihchum.html

[U37] Py：读写 Excel
来源：http://dali.iojbl.cn/Article/details/gtjikqmctw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hywenlv.cn/Article/details/gtzgdlzzit.html

[U38] Py：获取脚本所在目录
来源：http://dali.guowangkeji.top/Article/details/gthanwshxj.html

Path(__file__).resolve().parent
来源：http://dali.yonumen.top/Article/details/gtaknawmyl.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangdashe.top/Article/details/gtlecvrsnd.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiauevtjc.html

[U40] Py：打印到标准错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmdgpksr.html

print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtvprlkvfw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gtxmwmahfk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yvedp.cn/Article/details/gtztiecreh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.snrcjt.cn/Article/details/gtlcnojifs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhoulong.xyz/Article/details/gtvkkxupbv.html

[U43] PHP：声明命名空间
来源：http://dali.cdnleiting.top/Article/details/gtewostjul.html

namespace App\Http;
来源：http://dali.cqqwz.cn/Article/details/gtahuzjhuz.html

[U44] PHP：开启严格类型
来源：http://dali.sysykeji.top/Article/details/gtvhinvgwj.html

declare(strict_types=1);
来源：http://dali.svipenyu.cn/Article/details/gtrlxawich.html


<!-- 参考信息 -->