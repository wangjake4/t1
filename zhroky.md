代发 wailian999

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtnhpdkveo.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtibfzyocy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gttfrzuhhw.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gtbccekfyk.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gtvnizroii.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gtazchkcto.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtrdjgwxtz.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakkshdzx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtwfkjgewy.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtftrjfmpf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinghuilouyu.cn/Article/details/gtejonatcc.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtfjfpmwfx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gtfautslav.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtatjzzzun.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gtgxriexkh.html

[S24] C：获取本地时间
来源：http://dali.zhiwuduotai.top/Article/details/gtvuxplllb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gtmbaxypuw.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gteqolevut.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthezztzmn.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gtrfctrfvh.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtofgcnchh.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtkglbyxgw.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtmwmcrjvk.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtlhzxwxqj.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmnckgkr.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtcpxqnmze.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daxiang520.top/Article/details/gtyjlhzfch.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtvqqchrbs.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gtxjuubjfp.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gtevijtkic.html

#endif
来源：http://dali.tian-w.cn/Article/details/gtzkfakhjt.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gtyeqvktop.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gtsqnvwcfa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gtgbauujei.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gtkmikwxdk.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gtnqodlkvg.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtqjjqkyzm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtfiumwsfi.html

[S34] C++：遍历 vector
来源：http://dali.xuanzx.com/Article/details/gtumdmkbat.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenlongwang.top/Article/details/gtrcuyjsqu.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtglqmekmp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtdcqkadah.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gtnirncsoz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gthdtlkcah.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gtqcuevqts.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gthzfvyjec.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtodlatrlr.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gttlhlciui.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gttdiaarlr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtckcmqgqk.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtvfotjbon.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtjpwnjikr.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gtmwvpjmhx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtwjchenhk.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gtecpzhezp.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gtlafgwjzl.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gtnusdcigl.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gtjvyvrkni.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gtmjeqsfec.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gtltptmfes.html

[S45] C++：lambda
来源：http://dali.wangshuangyany.cn/Article/details/gtnrovdagm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtvndtddme.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gtwyzjahsf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmccfhjoz.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gtupghdocn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gttofnetpb.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtghxilrym.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagtmakmz.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloboelgm.html

[S49] C++：写文件
来源：http://dali.svipenyu.cn/Article/details/gtwkbnslha.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gtmxlucbvz.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gttkmlsmvm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrdyegyc.html

[S51] C++：显式类型转换
来源：http://dali.xylfe.cn/Article/details/gtcsafuneu.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtupvicwhg.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gtauldocmb.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gttvnmksfi.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpogrhmj.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gtlocslkux.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gtubrfipjn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gtlfmaozfv.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gtmnhmlplm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtnjotuhaw.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gtfaexkxia.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gttcyjldxs.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gtvsxhnius.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtygqnhict.html

[S58] C++：命名空间
来源：http://dali.guowangkeji.top/Article/details/gtbfdbdxvx.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gtetlkdlgf.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gtxshicqni.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gtiwlogeng.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gtrujeuepw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtvhlxcebo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsxwevymd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gtbzhmpbaw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrnylvxvq.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gtwqmdzeml.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtzdcehhhz.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtdtertiwe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gtbtqyzyaq.html

[T03] Kotlin：字符串模板
来源：http://dali.9152youxi.cn/Article/details/gtkpeepfdy.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtzvndlcbw.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gttitkqhud.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gtcamxqwzn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtxewwonrx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gthxlvjeso.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtiiozimqu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gtddncchio.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtgwzeflnd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gtgzdqygcw.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtogsvbopa.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtzwdmbhmh.html

[T09] Kotlin：扩展函数
来源：http://dali.jyoumei.cn/Article/details/gtnlctbmyh.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gtqbibzyhe.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gtvdvkadbb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gtzsmwwzfh.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gtgkcacjvg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gtrhxmablm.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gthfcjsbwm.html

val (a, b) = Pair(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtdkbxgtdc.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gtcngikqxe.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gtnqhbnivv.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtqwdlcrmd.html

for (i in 1..10) println(i)
来源：http://dali.tanke756.top/Article/details/gtzepumvkt.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtqxaxkkqt.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gtjmcdhpqk.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gtavtcrxsc.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtksikxtak.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gtvqdybvci.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtjpxvtebi.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtbpnaqtfv.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gtwzwgvhgz.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gthwcvhclv.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gtpqrioyif.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gtxnzbaztm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gtzkmhnlgz.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gtgryoqcds.html

for x in a { print(x) }
来源：http://dali.gogol.net.cn/Article/details/gtewrvfbzm.html

[T22] Swift：字典
来源：http://dali.svipenyu.cn/Article/details/gtlvrfdyuj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gtwllhqbor.html

[T23] Swift：函数
来源：http://dali.yanxiufei.cn/Article/details/gtswvrdjwx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gtjjjkgaub.html

[T24] Swift：闭包
来源：http://dali.cashguo.top/Article/details/gtydezijab.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtilbcsmrh.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gtucypjraa.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtdqzgltfw.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gtdaipiiha.html

class A: Base { override func f() {} }
来源：http://dali.cqqwz.cn/Article/details/gtuxzppyvs.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdfzmysg.html

do { try f() } catch { print(error) }
来源：http://dali.aizwys.cn/Article/details/gtkqppuela.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gtqhhzqaxr.html

enum Color { case red, green }
来源：http://dali.yj20258.top/Article/details/gtiuskrhmr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtkrgcmrdw.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtaiolnmrd.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gtqgkbkoca.html

protocol Shape { func area() -> Double }
来源：http://dali.c1oappe.top/Article/details/gtfbmggxmn.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhsxylaf.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtohtxtydi.html

[T32] Lua：局部变量
来源：http://dali.jiagoushi.top/Article/details/gtrkxinjsq.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtpfcfvyvf.html

[T33] Lua：表（数组）
来源：http://dali.jinqigfzy.top/Article/details/gtlwxlypzw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xziqi.cn/Article/details/gtqhuxtgfg.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gtgyyhszbs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gtefknvucl.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gtszylbjrc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndmoxnbh.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtechxxgtc.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gtndzztnem.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtildineca.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gtytfzwhyr.html

[T38] Lua：条件
来源：http://dali.yangfankeji.com/Article/details/gtymvyuuff.html

if x > 0 then print("正") end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgqaoozr.html

[T39] Lua：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gthlohkxfq.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtnpmjdgav.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gtbfboifjl.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gtijsbngvm.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtxjsrukgw.html

print "Hello\n";
来源：http://dali.shzxlz.cn/Article/details/gtmfntisdj.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtrffjzium.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gtzkktrxhk.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtcetmldoj.html

"值: $a"
来源：http://dali.cucudq.cn/Article/details/gtmoddrimq.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gteiujfiog.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtphmdfbvn.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtjogpmjty.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gtlmgzvkmh.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtpcelhenn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hywenlv.cn/Article/details/gtalrjxixu.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gtqljatccd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gtpajteeog.html

[T48] Perl：正则替换
来源：http://dali.aibaodan.cn/Article/details/gtdbrkzpsj.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gtvqkdfobe.html

[T49] Perl：函数
来源：http://dali.jinqigfzy.top/Article/details/gtpaeckzgz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtacfhsjkn.html

[T50] Perl：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtrbchlama.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gtzajfkgal.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gtqczndkdc.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gteivldoro.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtbvdytuho.html

[T52] Scala：变量
来源：http://dali.daria6918.cn/Article/details/gtituwgmpc.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtmjiykhby.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtlvqsxele.html

s"值: $b"
来源：http://dali.pycfn.com/Article/details/gtxoxqcrms.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtnvacngfw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gttxxwjoyc.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnhbhdgd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gtdeiaojnx.html

[T56] Scala：样例类
来源：http://dali.jlsjyb.cn/Article/details/gtbnwdywds.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gtuxftbnpo.html

[T57] Scala：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gtoktdxckz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ydzc1.top/Article/details/gtqhhyhvuz.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gtocefdbej.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtenxasiez.html

[T59] Scala：循环
来源：http://dali.quarkkingdee.top/Article/details/gtzjzeoeez.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtbarghcvd.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtbhiawccw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtomvmbfjn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtserhzzjb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gtxbwlchic.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjmvdzhhs.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gtdyoaqzbx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gtprtezkwv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gtrqsyusuh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.smart0.xyz/Article/details/gtzmmzhlxl.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gtkojcrqob.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.haohaochexian.top/Article/details/gtsswzluif.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrlkkcky.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gtcqmcjxzc.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gtgorclecq.html

list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtixzgapzg.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gtfdmfhzaz.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gtoxvrfpht.html

[U07] Py：反转字典键值
来源：http://dali.hysaishi.cn/Article/details/gtiwudkvpw.html

{v: k for k, v in d.items()}
来源：http://dali.mhx1999.top/Article/details/gtphvmcqot.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwepelwk.html

[y for x in nested for y in x]
来源：http://dali.jyoumei.cn/Article/details/gttgsgyros.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gtcstxcnxo.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtqmdlpqco.html

[U10] Py：按值排序字典
来源：http://dali.ydzc1.top/Article/details/gtatawyetr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yvedp.cn/Article/details/gtqzzwolwa.html

[U11] Py：生成器表达式
来源：http://dali.daxiang520.top/Article/details/gtmnfoupgv.html

(x * 2 for x in arr)
来源：http://dali.zdqjudy.top/Article/details/gtfbpuytku.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gtfdwjhwcx.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gtrvuikzkk.html

[U13] Py：固定长度队列
来源：http://dali.xylfe.cn/Article/details/gtqnkbmpyb.html

deque(maxlen=10)
来源：http://dali.ivvv.top/Article/details/gtxxmpfsuk.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gthicsikcn.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtiskjbraw.html

[U15] Py：高精度计时
来源：http://dali.vqdsnc.cn/Article/details/gtpyiorjtj.html

t = time.perf_counter()
来源：http://dali.yvedp.cn/Article/details/gtejxoesdr.html

[U16] Py：命令行参数解析
来源：http://dali.cdnleiting.top/Article/details/gtkpfwyppd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gtkelylrjr.html

[U17] Py：初始化日志
来源：http://dali.guowangkeji.top/Article/details/gtqklwwnlt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gogol.net.cn/Article/details/gtzprpvgmk.html

[U18] Py：预编译正则
来源：http://dali.xuetiantiany.cn/Article/details/gtbprxiqch.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtcbjidvvg.html

[U19] Py：正则替换带回调
来源：http://dali.gotoacloud.top/Article/details/gtfydycbhk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrckxovwi.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigufen.top/Article/details/gtyvvzqotn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hysaishi.cn/Article/details/gtmnfvffbl.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvkpmgff.html

@contextlib.contextmanager
来源：http://dali.havefunace.top/Article/details/gtkophowhv.html

[U22] Py：矩阵转置
来源：http://dali.hfpthk.cn/Article/details/gtkoeeyjct.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gtnoctdewe.html

[U23] Py：分块读取大文件
来源：http://dali.guowangkeji.top/Article/details/gtzghmcpme.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnqzz.top/Article/details/gtfxlalcrp.html

[U24] Py：路径操作
来源：http://dali.yvedp.cn/Article/details/gtsncjiwtz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtbnrgigru.html

[U25] Py：CSV 按字典读
来源：http://dali.xylfe.cn/Article/details/gtxakjymtc.html

csv.DictReader(f)
来源：http://dali.hfpthk.cn/Article/details/gthhtufthz.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gtjcfwmyfi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yangfankeji.com/Article/details/gtafpljllp.html

[U27] Py：异步 HTTP
来源：http://dali.zhengqikj.top/Article/details/gtalgmpvpj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xziqi.cn/Article/details/gtnilbfhxu.html

[U28] Py：类型别名
来源：http://dali.tian-w.cn/Article/details/gtppgkcchj.html

UserId = int
来源：http://dali.xziqi.cn/Article/details/gtkpmhcnum.html

[U29] Py：属性校验
来源：http://dali.jinghuilouyu.cn/Article/details/gteuyqkkmz.html

@property 与 @x.setter 配合
来源：http://dali.gotoacloud.top/Article/details/gtvbmfqydq.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gtaevnfvmk.html

@dataclass(slots=True)
来源：http://dali.dashuyun.cn/Article/details/gtrzsnzvrd.html

[U31] Py：单测
来源：http://dali.daxiang520.top/Article/details/gtmqlazoag.html

python -m pytest -q
来源：http://dali.redwolf501.top/Article/details/gtqleqpxnu.html

[U32] Py：代码格式化
来源：http://dali.yongpay.top/Article/details/gtxojafvrb.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gtawmgwvyj.html

[U33] Py：打包发布
来源：http://dali.feifeiyinyue.top/Article/details/gtcccnuyet.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gtzdsuziwr.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gtbuuzdrsl.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gtnuzwbiuq.html

[U35] Py：发送邮件
来源：http://dali.pycfn.com/Article/details/gtkfetndnb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ehwqpu.com/Article/details/gtqhwrcste.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gtrgqlhacg.html

schedule.every(10).minutes.do(job)
来源：http://dali.hfpthk.cn/Article/details/gtwmxlhbax.html

[U37] Py：读写 Excel
来源：http://dali.9152youxi.cn/Article/details/gtggkeuqqp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ybcxt.top/Article/details/gtnifyrlvg.html

[U38] Py：获取脚本所在目录
来源：http://dali.jiagoushi.top/Article/details/gthvkmtska.html

Path(__file__).resolve().parent
来源：http://dali.ydzc1.top/Article/details/gtrgecygyb.html

[U39] Py：判断是否在交互环境
来源：http://dali.birdmap.top/Article/details/gtsyyovofj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gtcfjoqluj.html

[U40] Py：打印到标准错误
来源：http://dali.hnqzz.top/Article/details/gtzpjdkbhf.html

print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqffiqhbe.html


<!-- 参考信息 -->