代发 wailian999

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gtuhkrguuy.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gtekouypnw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtcyvmmkpv.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gtwubxckps.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtxedfwwwz.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixrzezhx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gthultpxqm.html

[S22] C：字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtlexlgmpc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtvljijjyg.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gttblgsduy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gtxryugrmu.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gtmnblxstl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gtxhepejqj.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gtlsjaiwiw.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gtxbxukmpb.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gtliqgbvjc.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gtvtkvmhrh.html

[S27] C：定义常量
来源：http://dali.jinqigufen.top/Article/details/gtvrgevwfk.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtiafeyqls.html

[S28] C：静态变量
来源：http://dali.0kj1m.cn/Article/details/gtpqaikoyp.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtowispylk.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gtjuailjld.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gtepmgbfxp.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gtsnfhxfux.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gtfkunoqez.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkroiktr.html

#endif
来源：http://dali.meibo888.top/Article/details/gtvliikcjm.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gtauevsdrd.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtrvxqfktf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gtgzfxsxwc.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtgwvxxnre.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtmdlfbreo.html

[S33] C++：vector 增删
来源：http://dali.yj202588.top/Article/details/gtxmjrbjax.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gtihydamid.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gtglhjhchm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gtxbbqhmkj.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtfhanvfba.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtjxitndnt.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtrrrsheay.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcghvoby.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvtustcp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gthpytsyal.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gtsnerxlhq.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtagwakdfp.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gtqoogskjc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gtbpsghtsw.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gtrnhbalpt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yonumen.top/Article/details/gtatkduhig.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gtktqbsfoo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gtemalyswm.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gtwbjuefok.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtihmzvazj.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gtcckjxgkc.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtnbqvyqrh.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gtwjkctyjy.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtmuqdhrsk.html

[S45] C++：lambda
来源：http://dali.jinqigfzy.top/Article/details/gtaexfffuf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gtzgpoylqa.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gtsvymofkp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gtoayzpbnp.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gtikfmbzsp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gtohfobryg.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtoymgvtxx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gtdiwixwei.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtolabeqvn.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gtszxesxdy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gtpdokrbyr.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gtabhtyilh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtjgzcbybu.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtwsqtpfeo.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gtarpwefby.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gtofmpndaj.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gtxkachbae.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtfmjxizik.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gtncrjfdoz.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtcpmbytfw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gtrprqtdyq.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtpkklrrml.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gthocbtdps.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gtjojfdhqf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gtnmljdvfk.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gtocfbqmyu.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtsseyrjpu.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gtzbgzebuc.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gtyhnjmsck.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gtjactpqre.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gtolxqneju.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtrjjwqxnd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gttjkfpoxi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbaiyteah.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtrovqsnpu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtczqjbebw.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtdruukuvx.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtaiheiepv.html

[T02] Kotlin：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbaqvdcp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gtouwnyaff.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gtyzoedxkc.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gttzkgfhdl.html

[T04] Kotlin：空安全
来源：http://dali.feifeiyinyue.top/Article/details/gtsljuxuem.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gtjcyoqfjr.html

[T05] Kotlin：when 表达式
来源：http://dali.xuanzx.com/Article/details/gtjtfletll.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gtuttzhuqu.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gthdghhmle.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gtgipggvyv.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtogugowzy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gtdjumxdzo.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gtouvrfyza.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtjdqfuqqa.html

[T09] Kotlin：扩展函数
来源：http://dali.ivvv.top/Article/details/gtrbfrrpfa.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gtkdlrwoef.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gtqfyhpoyt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtvrhxjlql.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtjebcgkuj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gtaptelbjb.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtmulyjlxg.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtjogigvqc.html

[T13] Kotlin：只读 Map
来源：http://dali.ppjwa.cn/Article/details/gtulqshovl.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqladenuj.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gticzfsmrj.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtnsjqscuj.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gtahxjckjl.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtqxbiqqjz.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtsirslvbb.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtuzttmkqo.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gtzivhoirs.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gtymcayjeq.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtfsdlkjzi.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkydjctfv.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtpozexeyy.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gtruuvmkqs.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gtqugmiryq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gtgrcbbajb.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtazuajaqg.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gtzvjeyggm.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gtimreemvg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gtratxsnoh.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtxkhardme.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtmzwbsexp.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gtbqixmdoe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gtbgqlqudz.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtjqkbvjvi.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gtuilgdkwz.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtbgbdnzcc.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gtmttjobcb.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabdrayvh.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gtspthmsfy.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gtmtcwghwr.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gtlxmksfcm.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtmujgpmrk.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpzbixkj.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gtqwweavfx.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gtzwkmiybc.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtosdmbqgd.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtnuevdhod.html

[T32] Lua：局部变量
来源：http://dali.sxryk.cn/Article/details/gtxxylglmu.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gtdqqizvfc.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gtjtikgeta.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gtksleezob.html

[T34] Lua：遍历表
来源：http://dali.guannengcc.top/Article/details/gtxikfabht.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gtrjjnbpxo.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gtkcviqtgi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ppjwa.cn/Article/details/gtiqegigct.html

[T36] Lua：函数
来源：http://dali.haohaochexian.top/Article/details/gtdnxqpoqw.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gtmhvahdvq.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtljaszlpb.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtupxdcgrw.html

[T38] Lua：条件
来源：http://dali.andypj.xyz/Article/details/gtepdmrlvc.html

if x > 0 then print("正") end
来源：http://dali.yanxiufei.cn/Article/details/gtnnvgfmsz.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gtsmdpekta.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gtxfaymlyr.html

[T40] Lua：元表
来源：http://dali.gotoacloud.top/Article/details/gtqwjwbots.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gtsfzxsmqs.html

[T41] Perl：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtmwrdpvfa.html

print "Hello\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtczfuthej.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzzkzjjw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gtrxjuxlee.html

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gttdytbyth.html

"值: $a"
来源：http://dali.jqgufenzy.top/Article/details/gthyddhgnl.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gtekfguiuw.html

if ($a > 0) { print "正"; }
来源：http://dali.yj202588.top/Article/details/gtwvhgatms.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtxneekcmj.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gtukyvfmjf.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxcsrogg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gtwcazzpyv.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtxpczhcgk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aibaodan.cn/Article/details/gtfnuurvdy.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gtxsyfdrsb.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gtxpunzyng.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtnmetwsxc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtplaepouu.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtgaaayvvr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gthegjvtza.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gtukexotle.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gtxvtxqgkc.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtjedzvqdn.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gtcubmngii.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtlnyqhief.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtgwkgntic.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtmorjzqfc.html

[T54] Scala：集合映射
来源：http://dali.birdmap.top/Article/details/gthxwyvfcg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.haohaochexian.top/Article/details/gtdyaefyek.html

[T55] Scala：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtsbfydkqf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gtyhiffxgu.html

[T56] Scala：样例类
来源：http://dali.cucudq.cn/Article/details/gtouofiiyy.html

case class User(name: String, age: Int)
来源：http://dali.xuanzx.com/Article/details/gtgongniln.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gthwliotrd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gtmwfkuezh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gtowrbpaul.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gttdbiiviy.html

[T59] Scala：循环
来源：http://dali.dianchejie.cn/Article/details/gtfasjynuw.html

for (i <- 1 to 10) println(i)
来源：http://dali.havefunace.top/Article/details/gtyiibkkba.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gtvhsytexk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdvldpbg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjnowbyaz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtvzdynudn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmtsmnljw.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gtnnpmjqrz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxuanxn.top/Article/details/gtpbprbyrs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhixingplan.top/Article/details/gtflbxthqd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfwufqim.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtegadjdtk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hfpthk.cn/Article/details/gtkwvckmki.html

[U04] Py：变量调试打印
来源：http://dali.gaohongyu789.top/Article/details/gtlivmxipa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.feifeiyinyue.top/Article/details/gtzwjnihhe.html

[U05] Py：列表去重且保序
来源：http://dali.cdnleiting.top/Article/details/gtzrwgxllt.html

list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtuwbdlljs.html

[U06] Py：合并两个字典
来源：http://dali.gotoacloud.top/Article/details/gtmaqtccwx.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gtemidgrva.html

[U07] Py：反转字典键值
来源：http://dali.birdmap.top/Article/details/gtbdltmlft.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gtlhcccikv.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gtupifvufj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gtnfjntbiw.html

[U09] Py：字典取最大值的键
来源：http://dali.0kj1m.cn/Article/details/gtgvilrzwa.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gtkxngszkr.html

[U10] Py：按值排序字典
来源：http://dali.cucudq.cn/Article/details/gtzdrxcykw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gthnbyorka.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gtgfbfmpyb.html

(x * 2 for x in arr)
来源：http://dali.jyoumei.cn/Article/details/gtbskphttd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxinkj.top/Article/details/gtfjjwdoef.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gtvfsoizsi.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gtirvcnlnu.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gtrbdekhbj.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gtfufoxjcq.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gtzhltkrbv.html

[U15] Py：高精度计时
来源：http://dali.hnqzz.top/Article/details/gthdjjlizu.html

t = time.perf_counter()
来源：http://dali.havefunace.top/Article/details/gtflggdvxw.html

[U16] Py：命令行参数解析
来源：http://dali.hnqzz.top/Article/details/gtvoarohcm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gtvpkabjsu.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtvjpuzrur.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zdqjudy.top/Article/details/gtknvxmatw.html

[U18] Py：预编译正则
来源：http://dali.9152youxi.cn/Article/details/gtheztlwvy.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gtcjmuzrat.html

[U19] Py：正则替换带回调
来源：http://dali.mhx1999.top/Article/details/gtigeqvjwx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hammf.cn/Article/details/gttphxrina.html

[U20] Py：缓存函数结果
来源：http://dali.shzxlz.cn/Article/details/gtcckbmhhg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nwbrower.top/Article/details/gtyzcqlpzj.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxuanxn.top/Article/details/gtcssnlpyy.html

@contextlib.contextmanager
来源：http://dali.xylfe.cn/Article/details/gtwtfiopyo.html

[U22] Py：矩阵转置
来源：http://dali.yj202588.top/Article/details/gtfvmtzjhn.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gtdkwnpolv.html

[U23] Py：分块读取大文件
来源：http://dali.hfpthk.cn/Article/details/gtvvhmmkph.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.redwolf501.top/Article/details/gtgwwhtvvb.html

[U24] Py：路径操作
来源：http://dali.daria6918.cn/Article/details/gtrpvahndg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gternzwyvo.html

[U25] Py：CSV 按字典读
来源：http://dali.chenzaomai.com/Article/details/gtwdakibzk.html

csv.DictReader(f)
来源：http://dali.fzhhl.top/Article/details/gtecylvqik.html

[U26] Py：并发下载
来源：http://dali.dianchejie.cn/Article/details/gtwmzowkan.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gtoryhccte.html

[U27] Py：异步 HTTP
来源：http://dali.cdnleiting.top/Article/details/gtlcebsxvz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gthsaqffud.html

[U28] Py：类型别名
来源：http://dali.xuanzx.com/Article/details/gtbphmhdwh.html

UserId = int
来源：http://dali.yonumen.top/Article/details/gtixuszgld.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gtbjwekfmx.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gtamwczllt.html

[U30] Py：数据类
来源：http://dali.yj20258.top/Article/details/gtbevxgfhl.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gtmzsmdcjo.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gtykzjbasv.html

python -m pytest -q
来源：http://dali.zhoulong.xyz/Article/details/gttdxxlhbd.html

[U32] Py：代码格式化
来源：http://dali.tianlin.xyz/Article/details/gtiussqpvb.html

ruff format . && ruff check --fix .
来源：http://dali.jqgufenzy.top/Article/details/gthnpyangv.html

[U33] Py：打包发布
来源：http://dali.iojbl.cn/Article/details/gtijipeqxc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258.top/Article/details/gtfetdzhud.html

[U34] Py：判断编码
来源：http://dali.yuanzhike.top/Article/details/gtgbxlkirf.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gtpbfonzch.html

[U35] Py：发送邮件
来源：http://dali.quarkkingdee.top/Article/details/gtvjqhwmwn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjtkwron.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gtxoaucaxr.html

schedule.every(10).minutes.do(job)
来源：http://dali.hysaishi.cn/Article/details/gtctymugun.html

[U37] Py：读写 Excel
来源：http://dali.redwolf501.top/Article/details/gtcycdvfol.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cqqwz.cn/Article/details/gtgiaaxpfa.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuanzx.com/Article/details/gtlynbctzg.html

Path(__file__).resolve().parent
来源：http://dali.sysykeji.top/Article/details/gtqkzhjozb.html

[U39] Py：判断是否在交互环境
来源：http://dali.jlsjyb.cn/Article/details/gtuhvipurl.html

sys.stdout.isatty()
来源：http://dali.nanxinkj.top/Article/details/gtchdxcqta.html

[U40] Py：打印到标准错误
来源：http://dali.ppjwa.cn/Article/details/gtuxkkfefd.html

print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtarbxfsdd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cdnleiting.top/Article/details/gtykvwgifk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cashguo.top/Article/details/gtgpcqdrvo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.pycfn.com/Article/details/gtdmnnmaiv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.havefunace.top/Article/details/gtfuuprltx.html


<!-- 参考信息 -->