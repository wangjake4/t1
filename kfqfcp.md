代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gtserkdvtb.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gthjyyqhdi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gttantgvpo.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gtntdeqiqm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtbbjpyrhx.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gtvypisush.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gtctfkqdbe.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gthriiukuw.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gtqjshyofm.html

[S27] C：定义常量
来源：http://dali.jqgfzy.top/Article/details/gtrttheyrb.html

const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtndhezori.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtziceddsc.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gtycfnnvdq.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtuopdusio.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gthtgighur.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gtmtgvqszd.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtjbkctiue.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gtbkjyslsx.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gtncqaocra.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtzfvwqadg.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gtqdnauqyi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtemqtgaah.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gtvolsjwna.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gtkfxqqupt.html

[S33] C++：vector 增删
来源：http://dali.hongshengwenyu.top/Article/details/gtnbdtbmhk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gtfafreslw.html

[S34] C++：遍历 vector
来源：http://dali.dianchejie.cn/Article/details/gtpfyvtsre.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtqjvaahia.html

[S35] C++：map
来源：http://dali.hnxiangtu.top/Article/details/gtkppyvric.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtaesxnzmn.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtphcsnfke.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtgbduhzyj.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gtljasuhpn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtnholzift.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gtflbanwfe.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtezxwkqld.html

[S39] C++：自定义比较器排序
来源：http://dali.ehwqpu.com/Article/details/gtawxdfvmr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtglnwejgp.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gtxgapweam.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtgpsyekox.html

[S41] C++：类与构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtraputivt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gtruvyytjp.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtmcqgqhhf.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gtbmoxurob.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gtulpokyka.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gtmvqvdodb.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gtdykroaaz.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtgecevyfa.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtscqccynz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtpvgfpuhx.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gtazpuxchu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtfusrtamk.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtjedxfqlh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gtaxehunya.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkftyqboi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gtalvzvtna.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtadowusqs.html

[S49] C++：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gthquevxmq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gthenbwasn.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gtbeskhhdm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtxqzqaslp.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsoldiae.html

static_cast<double>(a) / b
来源：http://dali.zhongyouzk.top/Article/details/gtpwpojspr.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtijneiqsw.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gtrebdkmau.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtvojcpmtx.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtaylehnwr.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gtxphydvqr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gteesunqjw.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtmjiggpfb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtmsnzbhne.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtjeiwxxdz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gtzqzlgsis.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtvdqbblto.html

constexpr int N = 10;
来源：http://dali.316326.xyz/Article/details/gtwwcssqnb.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopqqxoaj.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtodwdacda.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gtjaggjrac.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtcfkutyee.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gtnxqogpcq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gthunmihrd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtysoqqwhs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtsmdutxmd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdouawumq.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtksmwujaj.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtapkxuufx.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gtzczsinfp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtekmdachs.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gtjamdveuk.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtdqaewrdj.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgftlwmd.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gtobubbfgq.html

[T05] Kotlin：when 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtmdcbfamm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktxkpktm.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtsobnbwta.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.iojbl.cn/Article/details/gtffdvyyos.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gtnskpdksi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpvprmcn.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtfybxhrjp.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtpvsiycwl.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gtbsqtifsd.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gtcqlnxtcy.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtkqxjckwi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtnqfsscjy.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtzugnvksp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cucudq.cn/Article/details/gtnztxjixn.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gtqqraobqy.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtahzluzzx.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgfzy.top/Article/details/gtuojnugju.html

val m = mapOf("a" to 1)
来源：http://dali.chenlongwang.top/Article/details/gtzrncxglf.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gttrquhvth.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtofpkwsmk.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtziezefhj.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtnkjhxtzy.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtzzhfukqt.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtqnfqugzv.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gtxqwkmpss.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtiagnzkwr.html

[T18] Swift：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtbwvwwsou.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gtudiinllf.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gtaheizgzi.html

if let n = opt { print(n) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsozdhmvq.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gtawbbjxux.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigfzy.top/Article/details/gtnidlljfh.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gtsbyvbxjh.html

for x in a { print(x) }
来源：http://dali.andypj.xyz/Article/details/gtrysaqzmp.html

[T22] Swift：字典
来源：http://dali.wangshuangyany.cn/Article/details/gtaifrzpyk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gtrlsvlehm.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gtsfjvomuw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtqgfzmtsu.html

[T24] Swift：闭包
来源：http://dali.yongpay.top/Article/details/gtvbhkkjuv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtrejievni.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gtcgifmioq.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gttcxjazpo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gtwwbpoxms.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gtrrtqkane.html

[T27] Swift：错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlopxyled.html

do { try f() } catch { print(error) }
来源：http://dali.snrcjt.cn/Article/details/gtuhbpxvac.html

[T28] Swift：枚举
来源：http://dali.zhengqikj.top/Article/details/gtwozgthlw.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gthzdqlend.html

[T29] Swift：guard 提前返回
来源：http://dali.shuidangran.top/Article/details/gtjrxqvocs.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtzeqzjzbb.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtrtkvzacw.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtaifbvqpi.html

[T31] Lua：Hello World
来源：http://dali.pycfn.com/Article/details/gtxcgswgvq.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtosjmguui.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gtyhcqadfb.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtiroaulwv.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtauanyhsq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gtbglwjrfo.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtrbvuputa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shuidangran.top/Article/details/gtqduinsom.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gtniyyfrvo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gtoquhydzd.html

[T36] Lua：函数
来源：http://dali.jinqigfzy.top/Article/details/gtegbkhepk.html

function add(a, b) return a + b end
来源：http://dali.mhx1999.top/Article/details/gtkrkmktfq.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvxjpvzw.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gtigvsopcg.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gtprhmhghf.html

if x > 0 then print("正") end
来源：http://dali.hnqzz.top/Article/details/gtcmpjcgye.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtsttdmfgp.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtiayvhsco.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gtuzczmojj.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gtjuvpxmho.html

[T41] Perl：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtwpeczuby.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtopcqjtsc.html

[T42] Perl：变量类型
来源：http://dali.jlsjyb.cn/Article/details/gtgfsceliv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigfzy.top/Article/details/gtrvkeqzmt.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gttqaayaac.html

"值: $a"
来源：http://dali.yvedp.cn/Article/details/gtmpzgjxgy.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtmcgebnil.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwykcclpx.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gtpljhfoij.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gtbicgwvan.html

[T46] Perl：哈希操作
来源：http://dali.aizwys.cn/Article/details/gtzpxsrqfo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gtpyingemn.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gtbnbxdfqz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhongyouzk.top/Article/details/gtbtvoofsx.html

[T48] Perl：正则替换
来源：http://dali.birdmap.top/Article/details/gtnzrxrfwn.html

$s =~ s/old/new/g;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdngdqefe.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gtcgjjqetp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtmordietn.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtvxchzsad.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gtmgfygivt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gtrlvdwbcs.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gtpkerlidw.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtfcvcjpgh.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gtgtbxkcwe.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gtbbfaiydp.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtdoaagtju.html

s"值: $b"
来源：http://dali.cheryme.top/Article/details/gtarilivck.html

[T54] Scala：集合映射
来源：http://dali.hnqzz.top/Article/details/gtwpfomfru.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtexxisdsm.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtzwzjwlyy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gtxfdotaou.html

[T56] Scala：样例类
来源：http://dali.jianghu66.top/Article/details/gtxvxaamgx.html

case class User(name: String, age: Int)
来源：http://dali.yongpay.top/Article/details/gtymmmvmcf.html

[T57] Scala：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtneobnbdn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gtnkxfrkzm.html

[T58] Scala：函数定义
来源：http://dali.sufxvd.cn/Article/details/gtwauogqth.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gtuomagtwv.html

[T59] Scala：循环
来源：http://dali.ybcxt.top/Article/details/gtnlouiaye.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtgolbjkrp.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gtvivroxwb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fengsongda.top/Article/details/gtcdnexmhv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqvuwiinp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gtsxknarbn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwsoqidlq.html

[U01] Py：创建虚拟环境
来源：http://dali.9152youxi.cn/Article/details/gtglvhcilw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxkeuupw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zycfv.cn/Article/details/gtgaudklji.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gtgdempjbc.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtxjmhausj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtbfibmlys.html

[U04] Py：变量调试打印
来源：http://dali.jqgfzy.top/Article/details/gthqorkipi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sweek.top/Article/details/gtpczdwhrj.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gtulrlavnd.html

list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gteknueicm.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gtpqxjkvtj.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtcbnqorvm.html

[U07] Py：反转字典键值
来源：http://dali.yj202588.top/Article/details/gtmrtjuemm.html

{v: k for k, v in d.items()}
来源：http://dali.yj202588.top/Article/details/gtmzkwlfhr.html

[U08] Py：展平二维列表
来源：http://dali.zycfv.cn/Article/details/gtylpvgdwg.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtvxiykovn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhongyouzk.top/Article/details/gthflctwng.html

max(d, key=d.get)
来源：http://dali.kuanghao11.cn/Article/details/gtmkdyvmrb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gtbmkydtdm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenlongwang.top/Article/details/gtxpkflsam.html

[U11] Py：生成器表达式
来源：http://dali.sxryk.cn/Article/details/gtmailihxm.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteegicfjy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gtlswffdju.html

Counter(arr).most_common(3)
来源：http://dali.chenlongwang.top/Article/details/gtdmckzcul.html

[U13] Py：固定长度队列
来源：http://dali.nanxinkj.top/Article/details/gtrymtxtby.html

deque(maxlen=10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyulqsttw.html

[U14] Py：分组收集到列表
来源：http://dali.yueranfly.top/Article/details/gtiebjrlgl.html

defaultdict(list)
来源：http://dali.tian-w.cn/Article/details/gtefzdgxqo.html

[U15] Py：高精度计时
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjpmlstt.html

t = time.perf_counter()
来源：http://dali.kuanghao11.cn/Article/details/gtuxpwrbir.html

[U16] Py：命令行参数解析
来源：http://dali.pengpengdd.cyou/Article/details/gtakfuatll.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zycfv.cn/Article/details/gtgnaantjf.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gtzkfaumhg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangdashe.top/Article/details/gthnjevhib.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gtektbbofc.html

pat = re.compile(r"\d+")
来源：http://dali.jianghu66.top/Article/details/gtxhscynol.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gtrdisdkhc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gtzqrllmoi.html

[U20] Py：缓存函数结果
来源：http://dali.sufxvd.cn/Article/details/gtntpdpues.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenlongwang.top/Article/details/gtmccvlafg.html

[U21] Py：自定义上下文管理器
来源：http://dali.svipenyu.cn/Article/details/gttinbilsj.html

@contextlib.contextmanager
来源：http://dali.jinqigfzy.top/Article/details/gthdeycmda.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gtsdqvrfjb.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gtuauvjemp.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gtkjmaxdfx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gzhubu.top/Article/details/gtwqfwwtcv.html

[U24] Py：路径操作
来源：http://dali.tian-w.cn/Article/details/gtoipbxwtd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gtmwwtozct.html

[U25] Py：CSV 按字典读
来源：http://dali.yj202588.top/Article/details/gtrxsxlqja.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gtdlexrymr.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmaarwhbr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yongpay.top/Article/details/gtsldgegft.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gtlqsnqmbf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj202588.top/Article/details/gtgoaujgep.html

[U28] Py：类型别名
来源：http://dali.nanxinkj.top/Article/details/gteydcqzrn.html

UserId = int
来源：http://dali.hysaishi.cn/Article/details/gtbcwgwbmb.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gtqdxhdquv.html

@property 与 @x.setter 配合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkkmgfjt.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gtddunsxkc.html

@dataclass(slots=True)
来源：http://dali.jqgfzy.top/Article/details/gtzuwapsav.html

[U31] Py：单测
来源：http://dali.aizwys.cn/Article/details/gtohskirwm.html

python -m pytest -q
来源：http://dali.tanke756.top/Article/details/gtymydpuhp.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtcdubucml.html

ruff format . && ruff check --fix .
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpclclty.html

[U33] Py：打包发布
来源：http://dali.hongshengwenyu.top/Article/details/gtwqduunod.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zycfv.cn/Article/details/gtjpcotxqy.html

[U34] Py：判断编码
来源：http://dali.zhiwuduotai.top/Article/details/gtkjrggnzf.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gtpqshxmqj.html

[U35] Py：发送邮件
来源：http://dali.svipenyu.cn/Article/details/gtpxiorpor.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hysaishi.cn/Article/details/gtlrshvvbp.html

[U36] Py：定时任务
来源：http://dali.chenlongwang.top/Article/details/gtmmmwwlns.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqrykiki.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gtmvuahdma.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj202588.top/Article/details/gtndsruwfb.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangshuangyany.cn/Article/details/gtvgolxjab.html

Path(__file__).resolve().parent
来源：http://dali.shuidangran.top/Article/details/gtbpqsyifz.html

[U39] Py：判断是否在交互环境
来源：http://dali.shuidangran.top/Article/details/gtsjqafceb.html

sys.stdout.isatty()
来源：http://dali.yj202588.top/Article/details/gtnfurdvto.html

[U40] Py：打印到标准错误
来源：http://dali.shzxlz.cn/Article/details/gtrlsjhjda.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtntqgjqte.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbmhwoof.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjnhlgoa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnxiangtu.top/Article/details/gtjksmewkp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenzaomai.com/Article/details/gtzbbkcfdi.html

[U43] PHP：声明命名空间
来源：http://dali.aibaodan.cn/Article/details/gtrlxgusua.html

namespace App\Http;
来源：http://dali.jinqigufen.top/Article/details/gthhgmqyge.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gtsakjggas.html

declare(strict_types=1);
来源：http://dali.guowangkeji.top/Article/details/gtwywbnatv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenzaomai.com/Article/details/gtvsixfzrw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtpdssmtsc.html

[U46] PHP：可空类型
来源：http://dali.shangyingyoupin.top/Article/details/gtjyubrels.html

?string $name = null
来源：http://dali.nanxinkj.top/Article/details/gtqlwrshzj.html


<!-- 参考信息 -->