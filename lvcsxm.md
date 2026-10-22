代发 wailian999

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gtpnwyuzyv.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtaxifpyll.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtkfgxzjyq.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gtobvwsfgz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gthlctybac.html

[S21] C：字符类别判断
来源：http://dali.jiagoushi.top/Article/details/gtwcmbwoss.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gtrbxdqynj.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtwvovapby.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gthkwzkuan.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gtszgxibvq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtvrskpuyw.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gteexgbksn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtpjwdtfsc.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gteesdevpt.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gtuvfonlvw.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gtoflbetsx.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtcbuildeq.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwpkzjqe.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gthbtjyuwk.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtctouxxdi.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gtghpwemlb.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gtsnjhbafu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gtreirwlff.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtyvkywizy.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtjtjgkpou.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gtnujrouvu.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gtoenjgypf.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gtrrxvfyjj.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gtwhgqakrm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gtdjgmhodp.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtkhmlxuca.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gtfibaxbwr.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gtdgcstxiq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtqxjlmdzn.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gttqznaodr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtftrsqbrh.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gttimfecch.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtmvlpqcey.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtfxinmsei.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtqdvtouvu.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtvyyvmsko.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gtxpkawdua.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gtiarzlkoo.html

std::sort(v.begin(), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtiizkthdk.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtjanesmbq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gtpnojqscd.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtattaacqu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtyowppklw.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gtthtcfuap.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gtutjvwzay.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gtccjhfmvr.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gtilxczhob.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtlvbxzubz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gtzpgxhgpd.html

[S44] C++：引用传参
来源：http://dali.zhengqikj.top/Article/details/gtsqlrcmrx.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gtrpjptfow.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gthydjruad.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtaxljugct.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gtlspeylvr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtzdnpufpb.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gttwwtvrde.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gtwxiktwff.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtmzslrjkp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gtfghpffqk.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtfzvrbmbc.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtvwuomzja.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gtnzrsjzua.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqvqzivt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemgmegwp.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtgqnjkayk.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtishqjddy.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtwbloxemr.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gtjalahwjc.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtlidxjzde.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gtsqqjtujv.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gtayxsgerk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gtinyahtpt.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gtozbbbzgw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gttpabnmlp.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gtrpeleeuk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtmocfjivk.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gtnnjymuly.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gthrbbfgdo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtluvdimys.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtrufvayhw.html

[S59] C++：静态断言
来源：http://dali.vqdsnc.cn/Article/details/gtpthznqqf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj202588.top/Article/details/gtykpxrjcq.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gtzqhexmti.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtcmlyhsil.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrdfgkevm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gtriyzlrgm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfgksxnjb.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtdvycyjmr.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtlkhnncig.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtrnduvdam.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gtngrljcwy.html

[T03] Kotlin：字符串模板
来源：http://dali.vqdsnc.cn/Article/details/gtwgmdznnk.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gtpxsnkblv.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gtighejlrz.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gttwqgacqn.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gtudjavfqg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gtmyipxewp.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtgaxqjaao.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtpworovas.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtbcxcbupy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gteffztbyc.html

[T08] Kotlin：数据类
来源：http://dali.cdnleiting.top/Article/details/gtcxecppbh.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gtpjusbqyq.html

[T09] Kotlin：扩展函数
来源：http://dali.shuidangran.top/Article/details/gtqogyqdtn.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gtvtgfubzg.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gtczgtuapo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtqzgryhvs.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gtoedovmma.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gtytigrebh.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gtfagoveep.html

val (a, b) = Pair(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtkcaktycm.html

[T13] Kotlin：只读 Map
来源：http://dali.sysykeji.top/Article/details/gteerdtcgx.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gtilxhgrhq.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxxiwzvl.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtbxjsmxoc.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gtjmihddxs.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gtwnqusttf.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtggpeqyxt.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtgopbjcht.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gthzokdxxx.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gtnupdjruo.html

[T18] Swift：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtiqhibynr.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gtcisxzflm.html

[T19] Swift：可选绑定
来源：http://dali.svipenyu.cn/Article/details/gterlendps.html

if let n = opt { print(n) }
来源：http://dali.pycfn.com/Article/details/gtcotzcwgi.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gterbdbnny.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gzhubu.top/Article/details/gtkfkhwzhi.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtcsuxavlr.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gtlondrmqe.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gtyviqbheq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtmrapgnkd.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gttdzrdpla.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtrxywmokq.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtvhjvtdiy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtcwznbuui.html

[T25] Swift：结构体
来源：http://dali.yj202588.top/Article/details/gtgklptslp.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gtacisdjet.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gtcjeyvoqh.html

class A: Base { override func f() {} }
来源：http://dali.ivvv.top/Article/details/gtjywufbfx.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gtjdwgfvjt.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtqxzebqzu.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gtogaiefru.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gtdzpwhqss.html

[T29] Swift：guard 提前返回
来源：http://dali.hammf.cn/Article/details/gtjenxyciw.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtxoblqplh.html

[T30] Swift：协议
来源：http://dali.sxryk.cn/Article/details/gtmajvodky.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtupmeejhp.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtgccugsnq.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtnzxmhjtp.html

[T32] Lua：局部变量
来源：http://dali.yj202588.top/Article/details/gtrkakneyt.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gtnecjunzn.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gtkhyhpihu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gogol.net.cn/Article/details/gtknvpovpg.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gtkiuclpod.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjavlqie.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gtdcjncvow.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gtmrxcaebl.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gtjkpdmjmo.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gtqyqyihof.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gtfftnrqdg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gtrtjvfwds.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gtzefgskqo.html

if x > 0 then print("正") end
来源：http://dali.feifeiyinyue.top/Article/details/gtlgqxxcwe.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtjburucfo.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaiskeek.html

[T40] Lua：元表
来源：http://dali.xinyue.icu/Article/details/gtxlclcngg.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxanpexf.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtozimyvjq.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gtythjqtsl.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gtsimeknxy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtfmjtvezt.html

[T43] Perl：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtxqajrwvr.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gtsdhbadms.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gtlfwtrswr.html

if ($a > 0) { print "正"; }
来源：http://dali.chenzaomai.com/Article/details/gtkxvcangh.html

[T45] Perl：数组遍历
来源：http://dali.ehwqpu.com/Article/details/gtulndiocq.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gtkwiewlst.html

[T46] Perl：哈希操作
来源：http://dali.cqqwz.cn/Article/details/gtxmlzegfp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenzaomai.com/Article/details/gtlhlckjye.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gtquozlvyr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgfzy.top/Article/details/gtctchtghs.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gtjudykvuq.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gtnjnsaxho.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gtmbldjrzi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtnroiisnw.html

[T50] Perl：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtbgzmpzhx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gthpcihfds.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtbpalmnqu.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtelbfrxdv.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtnysonafs.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gttlueythj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtcutfdzjs.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtgepcvbvt.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtuygvkiut.html

[T54] Scala：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtssvuolrp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gtsbabwtac.html

[T55] Scala：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtjvaxhanz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gttwrlvtso.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gtievajpuc.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gtbkvkacuk.html

[T57] Scala：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtoxejxazf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.andypj.xyz/Article/details/gtglsxygfi.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gtmyvqadjb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hysaishi.cn/Article/details/gtmxhcyzte.html

[T59] Scala：循环
来源：http://dali.jqgfzy.top/Article/details/gtbpkvjqpa.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtayqumgjd.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gtgpuroskt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gtlwkfwbtw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqicdoew.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gtwbthcdoq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtncqwytla.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gtyfxgidzr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtnevfhdwp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daxiang520.top/Article/details/gtexxndlfa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.c1oappe.top/Article/details/gtxpkxpnbp.html

[U03] Py：加载 .env 配置
来源：http://dali.jiagoushi.top/Article/details/gtdcjwohzs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gtykluxvnr.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gtxfvfoimb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pengpengdd.cyou/Article/details/gtbuckxarn.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gtagqnolwt.html

list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtgfzaixaz.html

[U06] Py：合并两个字典
来源：http://dali.hywenlv.cn/Article/details/gtvoldvmfn.html

{**a, **b}
来源：http://dali.jlsjyb.cn/Article/details/gtcsffxtur.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gtrvvlqfje.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gtgyjxzvil.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gtjniqokfq.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gthioivnlp.html

[U09] Py：字典取最大值的键
来源：http://dali.smart0.xyz/Article/details/gtqnzauifm.html

max(d, key=d.get)
来源：http://dali.0kj1m.cn/Article/details/gtcxdlbqcl.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgchgtkd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tian-w.cn/Article/details/gtdrlgrkup.html

[U11] Py：生成器表达式
来源：http://dali.chenlongwang.top/Article/details/gtarlqcipe.html

(x * 2 for x in arr)
来源：http://dali.guowangkeji.top/Article/details/gtjsobvyak.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gtafcpzstv.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtthceebis.html

[U13] Py：固定长度队列
来源：http://dali.yonumen.top/Article/details/gtorwxsygy.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gtbqlzufqb.html

[U14] Py：分组收集到列表
来源：http://dali.0kj1m.cn/Article/details/gtxlyipiih.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gtoecyypzf.html

[U15] Py：高精度计时
来源：http://dali.aibaodan.cn/Article/details/gtpmrxsnra.html

t = time.perf_counter()
来源：http://dali.tanke756.top/Article/details/gtpkuphkob.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gtupkqxxan.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gtmcmturdh.html

[U17] Py：初始化日志
来源：http://dali.andypj.xyz/Article/details/gtweqvzrzg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgywkvwd.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangtech.top/Article/details/gtgemlivtf.html

pat = re.compile(r"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtcigncqcj.html

[U19] Py：正则替换带回调
来源：http://dali.yongpay.top/Article/details/gtvngambux.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258888.top/Article/details/gtyxoepyet.html

[U20] Py：缓存函数结果
来源：http://dali.yanxiufei.cn/Article/details/gtnvmwsgzp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hongshengwenyu.top/Article/details/gtcgnmaumx.html

[U21] Py：自定义上下文管理器
来源：http://dali.dashuyun.cn/Article/details/gtxelzpccj.html

@contextlib.contextmanager
来源：http://dali.snrcjt.cn/Article/details/gtwcznxrmy.html

[U22] Py：矩阵转置
来源：http://dali.jiagoushi.top/Article/details/gtnbveuyah.html

list(zip(*m))
来源：http://dali.havefunace.top/Article/details/gtafvzfflm.html

[U23] Py：分块读取大文件
来源：http://dali.wangshuangyany.cn/Article/details/gtfklsbjff.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tianlin.xyz/Article/details/gtycufomva.html

[U24] Py：路径操作
来源：http://dali.zhiwuduotai.top/Article/details/gtghkqhrck.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtjmpiccht.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gtxsftcnxf.html

csv.DictReader(f)
来源：http://dali.birdmap.top/Article/details/gtbdliyrfo.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gttwaiqjeg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhfzbxig.html

[U27] Py：异步 HTTP
来源：http://dali.yongpay.top/Article/details/gtdqilspbd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gtprqxqnmq.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gtjlabqffc.html

UserId = int
来源：http://dali.zdqjudy.top/Article/details/gtkxsrekim.html

[U29] Py：属性校验
来源：http://dali.chenlongwang.top/Article/details/gtltycetst.html

@property 与 @x.setter 配合
来源：http://dali.yanxiufei.cn/Article/details/gtafllloxf.html

[U30] Py：数据类
来源：http://dali.nanxinkj.top/Article/details/gtubfafnfj.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gtcnatfvpi.html

[U31] Py：单测
来源：http://dali.dashuyun.cn/Article/details/gtdreecmar.html

python -m pytest -q
来源：http://dali.sxryk.cn/Article/details/gtrvljeiwp.html

[U32] Py：代码格式化
来源：http://dali.nanxinkj.top/Article/details/gtmssaltjm.html

ruff format . && ruff check --fix .
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbuznwxp.html

[U33] Py：打包发布
来源：http://dali.nwbrower.top/Article/details/gthxmyqgdp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cdnleiting.top/Article/details/gtwhuanfub.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gtvrncpsqt.html

chardet.detect(raw)
来源：http://dali.cqqwz.cn/Article/details/gtbinwsmmr.html

[U35] Py：发送邮件
来源：http://dali.bjfxy.top/Article/details/gtikmuwydv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hysaishi.cn/Article/details/gtxpxtaxzg.html

[U36] Py：定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtyxdpehtq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gtgnwkmdnf.html

[U37] Py：读写 Excel
来源：http://dali.zycfv.cn/Article/details/gtvpsypbvl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jlsjyb.cn/Article/details/gtusqvfhbt.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnxiangtu.top/Article/details/gtnrmgasgs.html

Path(__file__).resolve().parent
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkqyhacj.html

[U39] Py：判断是否在交互环境
来源：http://dali.cdnleiting.top/Article/details/gtkumtbmtc.html

sys.stdout.isatty()
来源：http://dali.gaohongyu789.top/Article/details/gtnmrecwfk.html

[U40] Py：打印到标准错误
来源：http://dali.fzhhl.top/Article/details/gtttfghkpm.html

print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gttgibfaax.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.andypj.xyz/Article/details/gttimoxhvk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gtbhgsiefr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuxming.cn/Article/details/gtkzugwskr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.haohaochexian.top/Article/details/gtgzlhzlqh.html


<!-- 参考信息 -->