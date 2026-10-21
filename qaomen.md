代发 wailian999

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtgutzwelh.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gtghitkqiz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtzqhsejqj.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gtbhwtbrkq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtaqoioumj.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gtkvgyqxvf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gtgotrorln.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtuewjjcfu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gtnmosjojv.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gtkzdkidlv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtcnhvazct.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gtbhvpncmh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gtaantgrrk.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gtwojfmbaq.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gtryfxhtav.html

[S26] C：内存清零
来源：http://dali.ehwqpu.com/Article/details/gtrhfdnlgc.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gtksgjadkp.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gtbybixdvd.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtnwjowzhj.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtwuejsfwv.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gthoaqcpoh.html

[S29] C：变参函数
来源：http://dali.hnxiangtu.top/Article/details/gtcgrytqfv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gtlswyhtnh.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtsnikibmi.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtqxfzvihd.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gtmnqmtnxk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gtbluunubo.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gteynhteqv.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gtdkhewhbe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtrfvzfnsg.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gtuxhndank.html

std::string s = "hi";  s += "!";
来源：http://dali.hnqzz.top/Article/details/gthxmjxsoo.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtsoegalou.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gtkuixesqz.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtwqxmcnsn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gtnafyolhw.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gtcbnpldyb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtuevpbunz.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gthnqouqnl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtgyobucnk.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gtidcalmhy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtvgawvooj.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtticgoxly.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gttoqgwotd.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtxphvgalm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gtljthcmhz.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gtvcnuarth.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtimvogkry.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtqtwktdkt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtqdkehqom.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gtakviukay.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gtapfpklel.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gtrrybsirn.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gthuzqmxjk.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gthxdgdxum.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtxurkiffd.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gtcfwgoaua.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gtzxecbqaq.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtupgvexqo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.iojbl.cn/Article/details/gtentyrcwz.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtuthdznam.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtqwebmsol.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gttmophcuj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtyizmlper.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtvlamtodf.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoijjngi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gtujbhntgy.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gtrdfnkvoh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtdevgxzft.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gthjzadjub.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtlafjxljf.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gtuaopzklg.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtjcshkzwd.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gtptsgdkjf.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gtpyenrvjj.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gtaridrkpn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gtzjkewpzf.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtgvpdxxdt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gtskvsunjf.html

[S56] C++：optional
来源：http://dali.kuanghao11.cn/Article/details/gtzokdqbqm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcscjgykk.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gtsxpdeelp.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpzjtcwd.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtudyrzkmf.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtjmmsbafy.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gtwacqpcey.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtwxzakzwl.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtrmyyxryu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtigatxvfg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtctpsrrbb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtzupbxkez.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtetrravjo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtwqijyznn.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtqkskpwvg.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtnjxygzyn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gtbhugdyfr.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gtjjfurnbh.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtyfnwqyqk.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gtmnlbgltl.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gtcmfnunpb.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpdumscy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gtwmztcmsx.html

[T06] Kotlin：集合映射
来源：http://dali.316326.xyz/Article/details/gtybzwmgda.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yueranfly.top/Article/details/gtwkgypysv.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtgnsryjvt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtugwaszbb.html

[T08] Kotlin：数据类
来源：http://dali.gzhubu.top/Article/details/gtpicthdrs.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gtccayhouo.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gtjbdlkldu.html

fun String.exclaim() = this + "!"
来源：http://dali.dashuyun.cn/Article/details/gtyikacvro.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gtenmmxbug.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtxettoaoo.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gtlgxqhqcu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykxinpau.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258888.top/Article/details/gtkzvhsuaq.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtpxoenjrd.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtfzcjtmnb.html

val m = mapOf("a" to 1)
来源：http://dali.hywenlv.cn/Article/details/gtnjwrwkax.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gtfmoqhfid.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gtpvkwxkyg.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gtqgnevmfi.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gttdfzbjgw.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gtuaobqjrl.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gthouigljz.html

[T17] Swift：变量与常量
来源：http://dali.hongshengwenyu.top/Article/details/gtsxavvfjb.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxkjhhhm.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcktypydm.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtwzeocthh.html

[T19] Swift：可选绑定
来源：http://dali.sysykeji.top/Article/details/gtymazetcx.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gtnedhqtdx.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gtjyginjix.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gtdksrrdgh.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gtplqbybjz.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gtycnntzxu.html

[T22] Swift：字典
来源：http://dali.shuidangran.top/Article/details/gtapwlsmwr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgufenzy.top/Article/details/gtljpajutr.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gtlvkvuxyq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gtmpdwpuik.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gtocaykldv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtxxrnuldk.html

[T25] Swift：结构体
来源：http://dali.gaohongyu789.top/Article/details/gtmeakaywd.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gtfokscmja.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gtjthxagom.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrdjkekr.html

[T27] Swift：错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtpuvxwlpo.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gtwefpldjr.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gtkzsalyfn.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gtqvvcounb.html

[T29] Swift：guard 提前返回
来源：http://dali.daria6918.cn/Article/details/gtqmwycmyh.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gtyzczwlqg.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gtrvsiqsjq.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gtbwgdqniu.html

[T31] Lua：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtxkapeooa.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtlsjzbgem.html

[T32] Lua：局部变量
来源：http://dali.shuidangran.top/Article/details/gtryjmvyiz.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gtkdduwywd.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gtyrsdyind.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtwzdysyfl.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gtqpwfoagy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gtsvgjkues.html

[T35] Lua：字典表
来源：http://dali.fengsongda.top/Article/details/gtfkskvjvc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtfloazzoc.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtfrvgjjnw.html

function add(a, b) return a + b end
来源：http://dali.zdqjudy.top/Article/details/gtfpfqxenw.html

[T37] Lua：字符串拼接
来源：http://dali.sxryk.cn/Article/details/gtgycukboh.html

"a" .. "b"
来源：http://dali.redwolf501.top/Article/details/gtamaqycyj.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gtaxlhmtxd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gtgplhxbgu.html

[T39] Lua：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtqttzvgle.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gtrzgbctav.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gteoxltbpf.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gtfqnwclze.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtudmbzsln.html

print "Hello\n";
来源：http://dali.xinyue.icu/Article/details/gtbapvmdrf.html

[T42] Perl：变量类型
来源：http://dali.xziqi.cn/Article/details/gtlmjchesm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxinkj.top/Article/details/gtxwcxqvco.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtmimdojaf.html

"值: $a"
来源：http://dali.yj202588.top/Article/details/gtibfknjxn.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gtdshcsrwx.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtlkacfvdy.html

[T45] Perl：数组遍历
来源：http://dali.ehwqpu.com/Article/details/gtfnrghcok.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gttvatyjjx.html

[T46] Perl：哈希操作
来源：http://dali.yvedp.cn/Article/details/gtjfzgejvd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yangfankeji.com/Article/details/gthxodgudx.html

[T47] Perl：正则捕获
来源：http://dali.feifeiyinyue.top/Article/details/gtgfntstow.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdirmuty.html

[T48] Perl：正则替换
来源：http://dali.chenlongwang.top/Article/details/gtwpoedpen.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gtkrnbakzy.html

[T49] Perl：函数
来源：http://dali.tianlin.xyz/Article/details/gtdktejbmc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtzkdsvvzp.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtzwlpkoez.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gtxmjbgsat.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtzfvepypa.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gtngcgbata.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtqasykiwu.html

[T52] Scala：变量
来源：http://dali.nwbrower.top/Article/details/gtrvwcswva.html

val a = 1;  var b = 2
来源：http://dali.haohaochexian.top/Article/details/gtwtllvadf.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtnegrsxmq.html

s"值: $b"
来源：http://dali.fzhhl.top/Article/details/gtahifegce.html

[T54] Scala：集合映射
来源：http://dali.iojbl.cn/Article/details/gtlmtfeazx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuxming.cn/Article/details/gtqzrgtkfs.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gtwuvjphyw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtjntpebdw.html

[T56] Scala：样例类
来源：http://dali.yanxiufei.cn/Article/details/gtrjswygsy.html

case class User(name: String, age: Int)
来源：http://dali.aizwys.cn/Article/details/gtpnkatjoq.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtfkvbzptg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gtpbxzlwtr.html

[T58] Scala：函数定义
来源：http://dali.hammf.cn/Article/details/gtaaimqnng.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gtezjlrwix.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gtffqslalt.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtthbcackq.html

[T60] Scala：折叠
来源：http://dali.yongpay.top/Article/details/gtskbwnjvn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gthhkicfjj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtbhbkshes.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtishxdjgc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtogponqep.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtnkuckycr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258.top/Article/details/gtppfhdojb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gtqzylhdmm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aizwys.cn/Article/details/gttchwagwp.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gtwpoaodwu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqymdwfmc.html

[U04] Py：变量调试打印
来源：http://dali.fengsongda.top/Article/details/gtehyydafv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gtorehtdyx.html

[U05] Py：列表去重且保序
来源：http://dali.ybcxt.top/Article/details/gtobqzvfrc.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtyyokvjhx.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gtqddjwnrm.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gtuutisvvz.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxupgkxh.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangtech.top/Article/details/gtljrttioc.html

[U08] Py：展平二维列表
来源：http://dali.tianlin.xyz/Article/details/gtlwxkudaw.html

[y for x in nested for y in x]
来源：http://dali.xuanzx.com/Article/details/gtjafodrsv.html

[U09] Py：字典取最大值的键
来源：http://dali.chenzaomai.com/Article/details/gtlouogrxm.html

max(d, key=d.get)
来源：http://dali.jqgufenzy.top/Article/details/gtvglesesh.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gtfolukimx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhixingplan.top/Article/details/gtqlksrmka.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gtuhipgbpu.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcachpnv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aibaodan.cn/Article/details/gtstjxrfml.html

Counter(arr).most_common(3)
来源：http://dali.yuanzhike.top/Article/details/gtabrhnfnj.html

[U13] Py：固定长度队列
来源：http://dali.yj202588.top/Article/details/gtouwkjgin.html

deque(maxlen=10)
来源：http://dali.shangyingyoupin.top/Article/details/gtyfdrqnsr.html

[U14] Py：分组收集到列表
来源：http://dali.jqgfzy.top/Article/details/gtburloegl.html

defaultdict(list)
来源：http://dali.zhixingplan.top/Article/details/gtvsmobmxs.html

[U15] Py：高精度计时
来源：http://dali.cheryme.top/Article/details/gtaeesgxvd.html

t = time.perf_counter()
来源：http://dali.jyoumei.cn/Article/details/gtivifhseu.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258888.top/Article/details/gtekpnfdwe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.mhx1999.top/Article/details/gtudpmeyrm.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gtkafhhvgq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yongpay.top/Article/details/gturvuohpu.html

[U18] Py：预编译正则
来源：http://dali.0kj1m.cn/Article/details/gtxhvqtzfu.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gttlhkntfu.html

[U19] Py：正则替换带回调
来源：http://dali.nanxinkj.top/Article/details/gtfzodujdn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gtjyeolszv.html

[U20] Py：缓存函数结果
来源：http://dali.feifeiyinyue.top/Article/details/gtpuawnafc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pycfn.com/Article/details/gtcptntuhd.html

[U21] Py：自定义上下文管理器
来源：http://dali.hammf.cn/Article/details/gtnbyiekui.html

@contextlib.contextmanager
来源：http://dali.cashguo.top/Article/details/gtprgwawug.html

[U22] Py：矩阵转置
来源：http://dali.feifeiyinyue.top/Article/details/gtucmbgkfg.html

list(zip(*m))
来源：http://dali.jyoumei.cn/Article/details/gtkrcsvsau.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtlfbfbyrz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gtckkqkjym.html

[U24] Py：路径操作
来源：http://dali.jqgufenzy.top/Article/details/gtaztwizoa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtiwltwntj.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigfzy.top/Article/details/gtrphumpcb.html

csv.DictReader(f)
来源：http://dali.quarkkingdee.top/Article/details/gtjawjwfxg.html

[U26] Py：并发下载
来源：http://dali.sxryk.cn/Article/details/gtdgvwrmvk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.c1oappe.top/Article/details/gtsgjtsuki.html

[U27] Py：异步 HTTP
来源：http://dali.dashuyun.cn/Article/details/gtywvsbeqs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gotoacloud.top/Article/details/gtqsjpflte.html

[U28] Py：类型别名
来源：http://dali.chenjidiqi.icu/Article/details/gtstkhmwfb.html

UserId = int
来源：http://dali.jyoumei.cn/Article/details/gtyqprnozq.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gtcdlxfzsv.html

@property 与 @x.setter 配合
来源：http://dali.cucudq.cn/Article/details/gtlbrrgake.html

[U30] Py：数据类
来源：http://dali.c1oappe.top/Article/details/gtanwndavu.html

@dataclass(slots=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtzuvpdyoi.html

[U31] Py：单测
来源：http://dali.havefunace.top/Article/details/gtcelqdhkl.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gttyzgfkwi.html

[U32] Py：代码格式化
来源：http://dali.shuidangran.top/Article/details/gtkihmmzqx.html

ruff format . && ruff check --fix .
来源：http://dali.haohaochexian.top/Article/details/gtsiagngys.html

[U33] Py：打包发布
来源：http://dali.sxryk.cn/Article/details/gtwdxbrjna.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbckigie.html

[U34] Py：判断编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsnjbjru.html

chardet.detect(raw)
来源：http://dali.haohaochexian.top/Article/details/gtddvvxoac.html

[U35] Py：发送邮件
来源：http://dali.cashguo.top/Article/details/gtqlokqxtn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ppjwa.cn/Article/details/gtryulriss.html

[U36] Py：定时任务
来源：http://dali.redwolf501.top/Article/details/gtqmxsnlvy.html

schedule.every(10).minutes.do(job)
来源：http://dali.meibo888.top/Article/details/gtiygmtkvy.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gtxcaweacf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhixingplan.top/Article/details/gtsqlkkebt.html

[U38] Py：获取脚本所在目录
来源：http://dali.snrcjt.cn/Article/details/gtdxbwfrtb.html

Path(__file__).resolve().parent
来源：http://dali.fzhhl.top/Article/details/gtbzdihiov.html

[U39] Py：判断是否在交互环境
来源：http://dali.havefunace.top/Article/details/gtrqezvfxp.html

sys.stdout.isatty()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwbstpbh.html

[U40] Py：打印到标准错误
来源：http://dali.pycfn.com/Article/details/gtxjsoifsq.html

print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtikzqbrqo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sxryk.cn/Article/details/gtbaszhdes.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gtzprbnzxf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yvedp.cn/Article/details/gtknhthpir.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprmrlzwr.html


<!-- 参考信息 -->