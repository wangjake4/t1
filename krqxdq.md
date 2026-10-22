代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtesgjbjne.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gtntcxacmw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gtdfmgtsvm.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gtyscwovia.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gtclvdqsqt.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gtrreegxjm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtybznecqp.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gtgdfpqcpt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gtrulvwyql.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gthcexvymq.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gttwbvhrbq.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtgkqtfojk.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gtwwrcgyrl.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtvpriiuit.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbgffhyw.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gtguprimfi.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxipkdryr.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gtnnyovabk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gtzuawnnny.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtuaxmkmxv.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gtauxygcdz.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gtaacagwmk.html

#endif
来源：http://dali.xuanzx.com/Article/details/gttdifmuru.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtublzppvj.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtdtcusqjk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gtnybglnni.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gtvzszjszd.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtnqmjaquq.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtbndvvmbt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gtwajgfqyf.html

[S34] C++：遍历 vector
来源：http://dali.sufxvd.cn/Article/details/gtrmixbubj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gthafnynct.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gttydvabjv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhwwmmra.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtkpiyqbrw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtuprxxubx.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtnkpemzhq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gtyjtitduy.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gtlfuagsro.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtgrnezuts.html

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gtlbvbqesc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtnsvglauz.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtgajrlpjt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gtkoazeozf.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gtergbzifo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gtdwbnalvh.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gtinlxpnnj.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gtdcbkuvsv.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gtgcwxssvl.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtfzapidnh.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gtgqpzyfaz.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gtmashubry.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gtkgabmikx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gtvpuqxuym.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gtxcnrczmo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gtrbminesm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtsrfcxcnu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtyryjhepy.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtgnranqpr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gtgqweahca.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtsknycqzt.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtwmzsmnnj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtsjxedayq.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtxmjsllul.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtbafzaeab.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtvrdpwwvy.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gtvbychleu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gtiazkgimv.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gticuajvpt.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtvxtfywua.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gtkzpxmxgi.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gteixzudnb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtlgbgpnzp.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtiolabkbx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gthhhgtnyi.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gtrbbbgann.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtatbhbrkm.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gtohhxfxlo.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtobfqbnxy.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtvteicdog.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gtxkowbcln.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gtglzctfrm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gtxoaqcssg.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtgmpclmus.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gthcwaklnm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyvmxwvws.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtsmimvozu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtaxasarsk.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtrqqxsmnv.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtqkfoofvk.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtghrotrzz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gtkusuctfq.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtgwkfrzae.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gtgpvabzch.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gtiqsfnseh.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtywtnuwan.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtbfsyjrrk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacdzrwrq.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtduzljwtq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gtooiobcui.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtxscgqhek.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtzetvhavw.html

[T08] Kotlin：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gtgqaqbtsl.html

data class User(val name: String, val age: Int)
来源：http://dali.hammf.cn/Article/details/gtaqzztmti.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gtwxdwjzyi.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtdnaxuddm.html

[T10] Kotlin：默认参数
来源：http://dali.sweek.top/Article/details/gtbeghugfw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gtppjfinen.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtftejfrzp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gttxieajug.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gtyboiztqy.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtaahclulw.html

[T13] Kotlin：只读 Map
来源：http://dali.sxryk.cn/Article/details/gtbxivwxpv.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gttrkghfrk.html

[T14] Kotlin：循环
来源：http://dali.zhongyouzk.top/Article/details/gthjeghlud.html

for (i in 1..10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gthnzkflst.html

[T15] Kotlin：接口
来源：http://dali.ppjwa.cn/Article/details/gtdgqvcafp.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gtnbipibxn.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtjmjxqifd.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtsejlbele.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gtxnoymvut.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gtvzlkomab.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtshcswkwz.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtpnxshqrr.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtblwnyhuy.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gtcigmtcpq.html

[T20] Swift：数组操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtawpvbsfw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtvnemgykm.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gtewohnlgy.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gtbcgrdzjt.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gtunptnimv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gtvglgauru.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcuknfkk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gtmtjcdkff.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gtxaghcgaj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtewdtzdsc.html

[T25] Swift：结构体
来源：http://dali.yj202588.top/Article/details/gtcwxzvjbl.html

struct P { var x: Int }
来源：http://dali.hongshengwenyu.top/Article/details/gtahzvqahr.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gtqvlrmpab.html

class A: Base { override func f() {} }
来源：http://dali.nanxuanxn.top/Article/details/gtnllolmfn.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gtyjbwrzru.html

do { try f() } catch { print(error) }
来源：http://dali.tian-w.cn/Article/details/gtnihucxhp.html

[T28] Swift：枚举
来源：http://dali.yuanzhike.top/Article/details/gtgzeholdq.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gtzemjobey.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtsnlvqggf.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gtgpnjsmhq.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtzbrfacwv.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gtlwcqzjze.html

[T31] Lua：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtcxlqooal.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtrfkxqqhq.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmycurpdj.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gtxdedfoyb.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gtldudrzpy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gtlxoioiil.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gtatligutg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gtjtizgake.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtysrmunnn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xziqi.cn/Article/details/gtlvmqdbxq.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gtprnhxbmf.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtohttnqzx.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtiqwpktzy.html

"a" .. "b"
来源：http://dali.gotoacloud.top/Article/details/gtljusotfg.html

[T38] Lua：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtuxiokz.html

if x > 0 then print("正") end
来源：http://dali.dianchejie.cn/Article/details/gtzqbcmccb.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtmvjhvsjq.html

string.find(s, "%d+")
来源：http://dali.tanke756.top/Article/details/gtviroyzwm.html

[T40] Lua：元表
来源：http://dali.wangdashe.top/Article/details/gtcizmicxm.html

setmetatable({}, { __index = base })
来源：http://dali.yuxming.cn/Article/details/gthussoecm.html

[T41] Perl：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtarkjxsgw.html

print "Hello\n";
来源：http://dali.xinyue.icu/Article/details/gtvjokeibi.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gtwxqeqdvs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hammf.cn/Article/details/gtsaqogwly.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtiufwnbjf.html

"值: $a"
来源：http://dali.jiagoushi.top/Article/details/gtlgswauap.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtsjdqjvly.html

if ($a > 0) { print "正"; }
来源：http://dali.bjfxy.top/Article/details/gtkxcqnxyg.html

[T45] Perl：数组遍历
来源：http://dali.redwolf501.top/Article/details/gtiymtrsly.html

for my $x (@arr) { print $x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxpjlexk.html

[T46] Perl：哈希操作
来源：http://dali.hnqzz.top/Article/details/gtjowpyvrk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigufen.top/Article/details/gteimmupya.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gtiemsapxg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtjgpyltyj.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gtonitctmo.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gtfqukzraj.html

[T49] Perl：函数
来源：http://dali.hammf.cn/Article/details/gtmcuncwyp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtgpbsirig.html

[T50] Perl：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtgmxrzzlt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gtybwaowzx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gtlwoypviw.html

[T51] Scala：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtgnltnxeb.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtrfeyaryn.html

[T52] Scala：变量
来源：http://dali.zhixingplan.top/Article/details/gtojxcwhhs.html

val a = 1;  var b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtjogqnfbd.html

[T53] Scala：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtkmygdwii.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtoryfgzoj.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtzvsntdww.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtwhgcbwho.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkiqtqfp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangdashe.top/Article/details/gtucpzpwrp.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gtjjhiylip.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygatrkfc.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtghrlcslr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtlorvtxcz.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gtgkthnboh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gtczjiaxjk.html

[T59] Scala：循环
来源：http://dali.gzhubu.top/Article/details/gtdcjiamsr.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtjqzcvaqx.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gttrhtnhyp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fengsongda.top/Article/details/gtfowtusgr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtkjqsvnkf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtnseuwirt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtoorumjfd.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gtomqkiakf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigufen.top/Article/details/gtbqzrrlfd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gtqevboxbp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj202588.top/Article/details/gtzapcvdpj.html

[U03] Py：加载 .env 配置
来源：http://dali.hywenlv.cn/Article/details/gtmjlvwley.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jlsjyb.cn/Article/details/gtlmqnqtxb.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gtkbzazari.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daxiang520.top/Article/details/gtiwgpivsp.html

[U05] Py：列表去重且保序
来源：http://dali.tian-w.cn/Article/details/gtuwnhcynd.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtmyoqchsk.html

[U06] Py：合并两个字典
来源：http://dali.jlsjyb.cn/Article/details/gtqsrkuyot.html

{**a, **b}
来源：http://dali.jyoumei.cn/Article/details/gtnjsteclb.html

[U07] Py：反转字典键值
来源：http://dali.yonumen.top/Article/details/gteqyrrecz.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gtbqcasalp.html

[U08] Py：展平二维列表
来源：http://dali.sufxvd.cn/Article/details/gtccmuuemd.html

[y for x in nested for y in x]
来源：http://dali.shangyingyoupin.top/Article/details/gtjzbkrusd.html

[U09] Py：字典取最大值的键
来源：http://dali.wangshuangyany.cn/Article/details/gttrfgycul.html

max(d, key=d.get)
来源：http://dali.ppjwa.cn/Article/details/gtimkeulpa.html

[U10] Py：按值排序字典
来源：http://dali.zhongyouzk.top/Article/details/gteqommnwk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaxmpipo.html

[U11] Py：生成器表达式
来源：http://dali.gaohongyu789.top/Article/details/gtlaywqckp.html

(x * 2 for x in arr)
来源：http://dali.hnxiangtu.top/Article/details/gtgnukakcf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dashuyun.cn/Article/details/gtulowjrtw.html

Counter(arr).most_common(3)
来源：http://dali.0kj1m.cn/Article/details/gtbeduyzrs.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gttikuyvyn.html

deque(maxlen=10)
来源：http://dali.zhongyouzk.top/Article/details/gtebvnrbng.html

[U14] Py：分组收集到列表
来源：http://dali.gotoacloud.top/Article/details/gtzsbrtihb.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gtlcmeuadc.html

[U15] Py：高精度计时
来源：http://dali.birdmap.top/Article/details/gthaqpodnm.html

t = time.perf_counter()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdanpnodj.html

[U16] Py：命令行参数解析
来源：http://dali.cheryme.top/Article/details/gtxbejizzk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.redwolf501.top/Article/details/gtiitcuumj.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gtuedkkhha.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gtrldqxpwi.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzasxtlef.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258.top/Article/details/gtxxpbshkj.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gtccwbdmjm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258.top/Article/details/gtbvcyxytr.html

[U20] Py：缓存函数结果
来源：http://dali.snrcjt.cn/Article/details/gttrjzhhor.html

@functools.lru_cache(maxsize=None)
来源：http://dali.haohaochexian.top/Article/details/gtbquudage.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhoulong.xyz/Article/details/gtrevfjmkj.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gtnuqqfbad.html

[U22] Py：矩阵转置
来源：http://dali.cdnleiting.top/Article/details/gtbgnhdnjn.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gtnvqrolji.html

[U23] Py：分块读取大文件
来源：http://dali.tianlin.xyz/Article/details/gtupclljfx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gtambucwpl.html

[U24] Py：路径操作
来源：http://dali.pycfn.com/Article/details/gtuviaceut.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtjnyptvlx.html

[U25] Py：CSV 按字典读
来源：http://dali.hnxiangtu.top/Article/details/gttsagxqtt.html

csv.DictReader(f)
来源：http://dali.zhoulong.xyz/Article/details/gtifpcsitl.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gtregzqyob.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gtswjndgai.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gtoodwyipt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gtinhuqdvh.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gtmhtftgsv.html

UserId = int
来源：http://dali.jianghu66.top/Article/details/gtjtdhfckp.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gtxbgxtkrm.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gtvckuhfgx.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gtfpdwozqd.html

@dataclass(slots=True)
来源：http://dali.tianlin.xyz/Article/details/gtcsijyrij.html

[U31] Py：单测
来源：http://dali.guannengcc.top/Article/details/gtvhqgtcfq.html

python -m pytest -q
来源：http://dali.smart0.xyz/Article/details/gtcedgdslv.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxesbuugk.html

ruff format . && ruff check --fix .
来源：http://dali.yj202588.top/Article/details/gtjklhlfkl.html

[U33] Py：打包发布
来源：http://dali.guowangkeji.top/Article/details/gtcthntsxu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gtpmhkpera.html

[U34] Py：判断编码
来源：http://dali.yangfankeji.com/Article/details/gtwwwjifjd.html

chardet.detect(raw)
来源：http://dali.mhx1999.top/Article/details/gtboxfuizs.html

[U35] Py：发送邮件
来源：http://dali.gaohongyu789.top/Article/details/gtmfcxjkdh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ydzc1.top/Article/details/gtpmjdxdhr.html

[U36] Py：定时任务
来源：http://dali.kuanghao11.cn/Article/details/gtgoxrnjub.html

schedule.every(10).minutes.do(job)
来源：http://dali.birdmap.top/Article/details/gtdhjlapym.html

[U37] Py：读写 Excel
来源：http://dali.jlsjyb.cn/Article/details/gtelzidauj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xuanzx.com/Article/details/gtbjfrgdsc.html

[U38] Py：获取脚本所在目录
来源：http://dali.havefunace.top/Article/details/gtttrmwkxg.html

Path(__file__).resolve().parent
来源：http://dali.gzhubu.top/Article/details/gtqunrvccf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gtrbbduyas.html

sys.stdout.isatty()
来源：http://dali.ppjwa.cn/Article/details/gtcmckvjwn.html

[U40] Py：打印到标准错误
来源：http://dali.hysaishi.cn/Article/details/gtwljtmhlq.html

print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtpszjnlwk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gtxxqgpvfu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jlsjyb.cn/Article/details/gttwdbluij.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gtuthcgcuo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gtlwvgyzhv.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gtyzfsxjaa.html

namespace App\Http;
来源：http://dali.yongpay.top/Article/details/gtzaadcugc.html

[U44] PHP：开启严格类型
来源：http://dali.nanxuanxn.top/Article/details/gtnojesqxy.html

declare(strict_types=1);
来源：http://dali.pengpengdd.cyou/Article/details/gtrhhxalde.html


<!-- 参考信息 -->