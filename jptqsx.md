代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtzqtxoslo.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gtwlefvszc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtpotkzqvz.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gteqbljips.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gtffbynnjz.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gtkfvchqvm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gtkxyakfri.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtkirrcnuu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gtduhutkjs.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gticoxbctg.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gtdeahhiwe.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gtmjhaexfe.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gtuounxuvv.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtxzyobmfa.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtmsetfbio.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gtmmkdbfco.html

static int counter = 0;
来源：http://dali.hnxiangtu.top/Article/details/gtbndcbkdk.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtbumssnqo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gtptwpzkxn.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gtkeslmbzt.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtzxrpoirp.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gtktfqpnwv.html

#endif
来源：http://dali.yj20258888.top/Article/details/gttvztuxhh.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtqzydnukv.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gtyqrpdlvu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fengsongda.top/Article/details/gtkwfxlldw.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gtmcburpej.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gtumkogusf.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtqjvtjwts.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gtzwgclsfr.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gtmsfyrruy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258888.top/Article/details/gtgpxkntyc.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtngqtkqsw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtexlvolfq.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtrehliecr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtvxyzqddz.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gtwfrowavg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gtibyxlccd.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gtdarrxsjf.html

std::sort(v.begin(), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtmhzebhri.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtgwmeuvbw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yangfankeji.com/Article/details/gtuhmuyzof.html

[S40] C++：查找元素
来源：http://dali.zhoulong.xyz/Article/details/gtmlxrncpc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gttiqfijdx.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtapihtogx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gthpcpnbwa.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gtzsazzrlb.html

class B : public Base { public: void f() override {} };
来源：http://dali.aizwys.cn/Article/details/gtjkoasymb.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gtnzkabvih.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gtuuceawmx.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyfffvad.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gtqnxgpgzq.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtuodjxvih.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gttdckudda.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gtnnfyyqwd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gtkpfjxfkj.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gtcpernivd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtlthshzze.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtqrnfheum.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gtdfdxasut.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gtndjqgeqc.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gtjxfxsxuq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gtczydtrqb.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtkoqqveqd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtnwwygsir.html

[S51] C++：显式类型转换
来源：http://dali.xylfe.cn/Article/details/gtkiaaggkc.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvilcajlj.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtqsgspyos.html

int size() const noexcept { return n_; }
来源：http://dali.redwolf501.top/Article/details/gthuolzkuv.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtowdtmsrh.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gtrkltmvok.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gtukbgawnc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gtswuwkjlu.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gtnlxmpqwq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgufenzy.top/Article/details/gtdgihpqde.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtgermmdpa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjxcqlocd.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gtjhrrswew.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtoqotfpag.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gthamjnypf.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtlkzllzmf.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gtbhygqmwf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zycfv.cn/Article/details/gtfitzuwxp.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtappkmoos.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gttwfqpfcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxydjhbku.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtikdwapev.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtpcsowvxg.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gtqilaylqp.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtangpbsql.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gtjmrbibhg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gtpnelnofd.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtqcopbyrh.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsknypjhx.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gttkgrxsmf.html

val n: String? = null;  n?.length
来源：http://dali.guowangkeji.top/Article/details/gtuswpbgwy.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtipmnsugd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gtcxadzcgg.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtgmqdjuro.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtijmkajul.html

[T07] Kotlin：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gtzntyalbo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenzaomai.com/Article/details/gtatqxvsvc.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gttrzrdrxx.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtfnxsxfol.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gtoraidrqf.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gtpuchjywa.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gtaevdpcbm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuyaboke.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gthbelbzey.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gtunampeau.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gtuodweupm.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtouyeelpj.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gthetyypuq.html

val m = mapOf("a" to 1)
来源：http://dali.chenlongwang.top/Article/details/gtrqlwvdrl.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gthcwncygk.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtmghscyzp.html

[T15] Kotlin：接口
来源：http://dali.jqgfzy.top/Article/details/gtewpjygwf.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gtgtwsyolm.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtnpaefccu.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtgqiuqykj.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gtnbzowpdi.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtpbwuomlj.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtlohhqlll.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtkayrktam.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gtycmzfhzg.html

if let n = opt { print(n) }
来源：http://dali.yangfankeji.com/Article/details/gtwtnktptb.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gtkoyovxlc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gteqcalvel.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gtmzcgodnp.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gtndvlrytg.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gtdbydtxqd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtdkzhsmnb.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtvwxhkrmy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtzwylieln.html

[T24] Swift：闭包
来源：http://dali.wangdashe.top/Article/details/gtvtqovbla.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtqbvcrwmr.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gtxexeqtba.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gtkkjggewa.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gtovuihflc.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gtqamklomw.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtovtmmnic.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gtawsekamp.html

[T28] Swift：枚举
来源：http://dali.jyoumei.cn/Article/details/gtkxvgapbx.html

enum Color { case red, green }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwxgsmmo.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gtqjcjsmpi.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gtblaqaogx.html

[T30] Swift：协议
来源：http://dali.jqgufenzy.top/Article/details/gtsbdowbzk.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gtkvtbkysp.html

[T31] Lua：Hello World
来源：http://dali.smart0.xyz/Article/details/gtkuittcio.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtgeinmcrk.html

[T32] Lua：局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtbblxeqqk.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtyvbmwlei.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gtmfvsgmem.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.smart0.xyz/Article/details/gtwbeubhxv.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gtddtrhphr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pycfn.com/Article/details/gtceutdivw.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtqyacnggs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtxrnafraz.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gtuacqkdfi.html

function add(a, b) return a + b end
来源：http://dali.hongshengwenyu.top/Article/details/gtiyxrwyio.html

[T37] Lua：字符串拼接
来源：http://dali.sxryk.cn/Article/details/gtkiaealpj.html

"a" .. "b"
来源：http://dali.yueranfly.top/Article/details/gtduwbnepi.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gtrcbbljhx.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gtntwmyehu.html

[T39] Lua：模式匹配
来源：http://dali.andypj.xyz/Article/details/gttboyvssy.html

string.find(s, "%d+")
来源：http://dali.jqgfzy.top/Article/details/gtadeedkmj.html

[T40] Lua：元表
来源：http://dali.svipenyu.cn/Article/details/gtvsuzacdj.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkajkiqnn.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsfezydk.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gtekeccppa.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpihymzzq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gtkizbmgfj.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gthwejqfyy.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxjqygsp.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gtnvgqlxqm.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258888.top/Article/details/gtouuhwrej.html

[T45] Perl：数组遍历
来源：http://dali.aibaodan.cn/Article/details/gtjinfeyqj.html

for my $x (@arr) { print $x; }
来源：http://dali.andypj.xyz/Article/details/gtpidpsyrk.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtgztwfphb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gtoidakijp.html

[T47] Perl：正则捕获
来源：http://dali.jiagoushi.top/Article/details/gtebciexsr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj202588.top/Article/details/gtdqxyqtds.html

[T48] Perl：正则替换
来源：http://dali.gogol.net.cn/Article/details/gtywkigeib.html

$s =~ s/old/new/g;
来源：http://dali.svipenyu.cn/Article/details/gtvfazpwkl.html

[T49] Perl：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtnftkiwpx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtyqblnjko.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gttgxntaej.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnxiangtu.top/Article/details/gtqizmfrbc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenlongwang.top/Article/details/gtezfiqerk.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtftowzvbk.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtahclmdfe.html

[T52] Scala：变量
来源：http://dali.ppjwa.cn/Article/details/gtgiaowlwo.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gtehgurmzv.html

[T53] Scala：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtuecoxkgr.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtmfdietjk.html

[T54] Scala：集合映射
来源：http://dali.hammf.cn/Article/details/gtinpcgsvq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fzhhl.top/Article/details/gtxereibrr.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gtdrfqhlfl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gtinsuhauf.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gtyvjagiql.html

case class User(name: String, age: Int)
来源：http://dali.havefunace.top/Article/details/gtuiygbrxb.html

[T57] Scala：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtafwhweti.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gtmcnuwhzo.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gtkxlwezsj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xinyue.icu/Article/details/gtrhjdeggi.html

[T59] Scala：循环
来源：http://dali.hammf.cn/Article/details/gtonhqrtah.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gticzhxypi.html

[T60] Scala：折叠
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhnckglb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cashguo.top/Article/details/gteegsrasj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnycsphlu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gtzhqzhsji.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxjdgfntn.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gtvptayqsv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gtywtgqeut.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfxyayjz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtvbfowqqb.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtsbaypeti.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gtjrxmbeol.html

[U04] Py：变量调试打印
来源：http://dali.andypj.xyz/Article/details/gtnphcssqs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258.top/Article/details/gtyavemamy.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigufen.top/Article/details/gtldbdzrnj.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gteuohptad.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gtfyadwjfj.html

{**a, **b}
来源：http://dali.ybcxt.top/Article/details/gtccjflbwu.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gtqbueuthw.html

{v: k for k, v in d.items()}
来源：http://dali.sufxvd.cn/Article/details/gtvkcizese.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gtyvfagrcq.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gtvvutwgkm.html

[U09] Py：字典取最大值的键
来源：http://dali.xinyue.icu/Article/details/gtvezlipix.html

max(d, key=d.get)
来源：http://dali.hammf.cn/Article/details/gtzblbhogk.html

[U10] Py：按值排序字典
来源：http://dali.nanxinkj.top/Article/details/gtrkwwpxca.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhoulong.xyz/Article/details/gtoluxtbao.html

[U11] Py：生成器表达式
来源：http://dali.hongshengwenyu.top/Article/details/gttatcmpbk.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gtypmzimkj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gtagkpuoku.html

Counter(arr).most_common(3)
来源：http://dali.ehwqpu.com/Article/details/gtcojgeatf.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gtfdzdmywo.html

deque(maxlen=10)
来源：http://dali.zhengqikj.top/Article/details/gtwicfbnis.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gtqunejqra.html

defaultdict(list)
来源：http://dali.jianghu66.top/Article/details/gtyhuqdsgc.html

[U15] Py：高精度计时
来源：http://dali.yj202588.top/Article/details/gtjviuciqk.html

t = time.perf_counter()
来源：http://dali.jiagoushi.top/Article/details/gtmyodlgjm.html

[U16] Py：命令行参数解析
来源：http://dali.zycfv.cn/Article/details/gtaxmogjdb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj202588.top/Article/details/gtbxwdmnej.html

[U17] Py：初始化日志
来源：http://dali.sxryk.cn/Article/details/gtuspvmdxt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.quarkkingdee.top/Article/details/gtmimbjszt.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gtplojaifx.html

pat = re.compile(r"\d+")
来源：http://dali.aibaodan.cn/Article/details/gthszvknft.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gtladwagaw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrqqhytmc.html

[U20] Py：缓存函数结果
来源：http://dali.sysykeji.top/Article/details/gtlcjfjvnc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shuidangran.top/Article/details/gtrllgeovb.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gtjanglbbo.html

@contextlib.contextmanager
来源：http://dali.daria6918.cn/Article/details/gtgltlbvgj.html

[U22] Py：矩阵转置
来源：http://dali.yj202588.top/Article/details/gtbhojbcjm.html

list(zip(*m))
来源：http://dali.tianlin.xyz/Article/details/gtklvbkgje.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtrmqzekzb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fzhhl.top/Article/details/gtzstgolfc.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtlxktajtk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtbeyvxdwa.html

[U25] Py：CSV 按字典读
来源：http://dali.jlsjyb.cn/Article/details/gtoxguimho.html

csv.DictReader(f)
来源：http://dali.shzxlz.cn/Article/details/gtajkkuzoh.html

[U26] Py：并发下载
来源：http://dali.hywenlv.cn/Article/details/gthxdgczpo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gthxhryxdf.html

[U27] Py：异步 HTTP
来源：http://dali.chenzaomai.com/Article/details/gtjujcwdpm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhiwuduotai.top/Article/details/gtwjqceogs.html

[U28] Py：类型别名
来源：http://dali.iojbl.cn/Article/details/gtyvqvnemg.html

UserId = int
来源：http://dali.gotoacloud.top/Article/details/gtyttwkvpx.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gtvsdhaqrr.html

@property 与 @x.setter 配合
来源：http://dali.cdnleiting.top/Article/details/gtnprheqfm.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gtcwgxogjb.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gtpxnxurrt.html

[U31] Py：单测
来源：http://dali.ehwqpu.com/Article/details/gtovuhfnwy.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gtjixlnpct.html

[U32] Py：代码格式化
来源：http://dali.0kj1m.cn/Article/details/gtuprgctfe.html

ruff format . && ruff check --fix .
来源：http://dali.hnqzz.top/Article/details/gtkapsqgiq.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gtvuedtsqp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuetiantiany.cn/Article/details/gtupuqzchl.html

[U34] Py：判断编码
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqppdcxf.html

chardet.detect(raw)
来源：http://dali.ppjwa.cn/Article/details/gtytxnveok.html

[U35] Py：发送邮件
来源：http://dali.chenjidiqi.icu/Article/details/gtkatymvkw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.bjfxy.top/Article/details/gtxaqnnkpi.html

[U36] Py：定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gthuzhtzgc.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gtdcxdlxpu.html

[U37] Py：读写 Excel
来源：http://dali.hnqzz.top/Article/details/gtftyomrlo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.haohaochexian.top/Article/details/gthdmlfkjh.html

[U38] Py：获取脚本所在目录
来源：http://dali.ydzc1.top/Article/details/gtbtbgyroz.html

Path(__file__).resolve().parent
来源：http://dali.yj202588.top/Article/details/gtazbfzukr.html

[U39] Py：判断是否在交互环境
来源：http://dali.jianghu66.top/Article/details/gttkrgoovo.html

sys.stdout.isatty()
来源：http://dali.hongshengwenyu.top/Article/details/gtsqszpiml.html

[U40] Py：打印到标准错误
来源：http://dali.tianlin.xyz/Article/details/gtoszfqkjc.html

print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtntjahema.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zdqjudy.top/Article/details/gtbvlafsrd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuxming.cn/Article/details/gtfnahnqxu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hammf.cn/Article/details/gtzeksyrfq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuanzhike.top/Article/details/gtmvahueok.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqzgpvru.html

namespace App\Http;
来源：http://dali.iojbl.cn/Article/details/gtaddzdfka.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gtmadvtdhf.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gtlakcxvtg.html


<!-- 参考信息 -->