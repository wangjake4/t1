代发 wailian999

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gtduumhycy.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gtsmcxtnxj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtuwpfjwhg.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtyoguexgj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtkqlrvxec.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtkkdzreum.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtlgbkgvpl.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gtalonwnlx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gtahltheks.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtbdriaucq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gtwfejbwuk.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gtgcuexiwf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gtjznpnwzz.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gtcmlmvywb.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtvyvcbldm.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gtgcadsqde.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtrqzpnila.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gtbutqrqan.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtxckplogi.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtsnthavlp.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtjxubephk.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gtpvtjwwvn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtfstkrcva.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gtjamvdszd.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdewebfd.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtqdlimzsp.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gtlhbadoyr.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gtqxlanktu.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtbnbxsber.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtuyjgxyul.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gtljbljbwz.html

std::string s = "hi";  s += "!";
来源：http://dali.aibaodan.cn/Article/details/gtcazeiavk.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gtxexrkaab.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtswqmybzu.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gtkiezqvqg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gtpzswccje.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gtzweeqmcx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtwqndbdfp.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtnkvrpmsl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtcefijmky.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtfhqmpctl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gtzyblpnuh.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gtigsvrpjr.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gtgohetygc.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gtltvbpotu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpcxlyoz.html

[S40] C++：查找元素
来源：http://dali.havefunace.top/Article/details/gtmtmjtazf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtzxkbjgcc.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtgkccrkdg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gthmpbzwvu.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gtnghlsbex.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gtkxtrubmv.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtqfcxxcio.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gttvnvbmte.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gtqazjivrg.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtljwbvmpn.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gtnigrfiaf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gtndcuncws.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtdfaocpiz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtvrqyladg.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gtocrwktdo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gtrbknjagg.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtgiahothr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxuanxn.top/Article/details/gtvbsghfeb.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gtmgpwvghc.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gtkrxtnygo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtofdhhegy.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gtcgqwoqgi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtdpgptvua.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtykkvvbqw.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gtxlzjeamj.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjcnetiy.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gthxmbwixs.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gtqnpbeijp.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtnvtomomt.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gtggsmcgzt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ydzc1.top/Article/details/gtocnlkrie.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gtsrhdmbmz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gttdavtdgh.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrobjxpnm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gtekitzoyy.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gtrfgqlori.html

constexpr int N = 10;
来源：http://dali.cdnleiting.top/Article/details/gtzpspkxrt.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwczpxnvt.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gttedoulfa.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gthmktwnkr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gttsvptcws.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtoymnfhtz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtjgfwmscg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjpwylgqo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gtzfvrznio.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrpizqfbg.html

[T01] Kotlin：Hello World
来源：http://dali.smart0.xyz/Article/details/gtrvghtrnk.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtquagkacf.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtlqsovnik.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gtmiauqwag.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gtjeyofnny.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gttsritfpz.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gtukffsghg.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gtadzwhvkk.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtogpuscoh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtlgerlqlo.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtozmoqjun.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtmfblpbxs.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtsixcwgpj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gtgconttaj.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gtrnnkrvmp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtemoiifwp.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gtbkzhqbty.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtanofubtd.html

[T10] Kotlin：默认参数
来源：http://dali.mhx1999.top/Article/details/gtehjisjrn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtblopaowx.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtsyuvnyrx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gtpsfbfjti.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gtcyaubtqv.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtovjopbkf.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gthpwsejnx.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtvdijbthz.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtupqurlvx.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtdeafiwyk.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gtwnaxgbuu.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtidlcadpv.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtogjsgxsz.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtlhrbbrlo.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuyfzufc.html

var a = 1;  let b = 2
来源：http://dali.haohaochexian.top/Article/details/gtptboryvv.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtrubwlsho.html

"值: \(b)"
来源：http://dali.chenzaomai.com/Article/details/gtthshqgbt.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gtoywayjek.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gtfpxracgb.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gtuwytldpl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gtcdjkzukw.html

[T21] Swift：遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtiwdqdlgs.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gtlcvggtfv.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfezbscez.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtxryyponk.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gtnormmulq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cheryme.top/Article/details/gtenukdzop.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gtcijrgavt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtrunnfiyf.html

[T25] Swift：结构体
来源：http://dali.nanxinkj.top/Article/details/gtokfhqbvn.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtydgqreck.html

[T26] Swift：类与重写
来源：http://dali.feifeiyinyue.top/Article/details/gtpvxrwqni.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gtfxjunwsd.html

[T27] Swift：错误处理
来源：http://dali.yj20258.top/Article/details/gtwstursbi.html

do { try f() } catch { print(error) }
来源：http://dali.tanke756.top/Article/details/gtwmqkprcj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtkjrbsslh.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gtcsishexo.html

[T29] Swift：guard 提前返回
来源：http://dali.yvedp.cn/Article/details/gtdvnzldcm.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gtlmlmqxce.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gtenvwqzzj.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgfzy.top/Article/details/gtpqkirwzr.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtpfpfhpdo.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtrzqxujeb.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gtkvnpvfdc.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gthfrvredm.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtbyuzyzgg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gtitfoxvds.html

[T34] Lua：遍历表
来源：http://dali.9152youxi.cn/Article/details/gtoztzcijz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yueranfly.top/Article/details/gthojeuily.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gtijnafkdc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gtulwkjpmz.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gtofqjrauz.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjtlojhd.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gtrvitzguz.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtoutttknf.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gtnbhmtzyl.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqivpusad.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtnawxtoil.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gtwmnicxfp.html

[T40] Lua：元表
来源：http://dali.tanke756.top/Article/details/gtbiawpdvb.html

setmetatable({}, { __index = base })
来源：http://dali.iojbl.cn/Article/details/gtmojkcsmd.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtflcatzzp.html

print "Hello\n";
来源：http://dali.jqgufenzy.top/Article/details/gtuuzzechd.html

[T42] Perl：变量类型
来源：http://dali.svipenyu.cn/Article/details/gtzblrycsq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gtfnwnhbuw.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtgvlkjnpu.html

"值: $a"
来源：http://dali.yongpay.top/Article/details/gtmjjwrvdw.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gttpexxxka.html

if ($a > 0) { print "正"; }
来源：http://dali.nwbrower.top/Article/details/gtvvwntsem.html

[T45] Perl：数组遍历
来源：http://dali.sweek.top/Article/details/gtwsvrtdsg.html

for my $x (@arr) { print $x; }
来源：http://dali.daria6918.cn/Article/details/gtijfhgzvn.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtklusgnnv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gtzgcvsitu.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gtmljwonux.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtndpplqwe.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gtfpsiwvlg.html

$s =~ s/old/new/g;
来源：http://dali.xinyue.icu/Article/details/gtausmclee.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gtumezeyhc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdebuxwch.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtqynvlomd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gtafhwpyne.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xziqi.cn/Article/details/gtntckavyg.html

[T51] Scala：Hello World
来源：http://dali.nwbrower.top/Article/details/gtpqqkxbon.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtfzieqsyt.html

[T52] Scala：变量
来源：http://dali.jqgufenzy.top/Article/details/gtqdouaain.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gtcxrcxeop.html

[T53] Scala：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gttutelbrb.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtxwoskyjy.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gtexebqfwt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzjdftsr.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gtyuyznpvx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gtqbpiwvng.html

[T56] Scala：样例类
来源：http://dali.zhengqikj.top/Article/details/gtqzefdfrq.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizssroya.html

[T57] Scala：模式匹配
来源：http://dali.xinyue.icu/Article/details/gthsipjkaq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gtcnfdoegz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gtsubhjrgj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pycfn.com/Article/details/gtkzigvuxh.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gttnnutkns.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtpbaugrvz.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gtheaxfrsr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gtyznwwupk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtklvpixqs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gtineylunc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdepdxcyh.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gtlrjojntn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gtskqvrwam.html

[U02] Py：导出 / 安装依赖
来源：http://dali.iojbl.cn/Article/details/gtaxxdfxfs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.haohaochexian.top/Article/details/gtgfybxpoa.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gttrnortof.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gtoebsitdq.html

[U04] Py：变量调试打印
来源：http://dali.gaohongyu789.top/Article/details/gtzawuiezg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gtvyqhsmfx.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlygrabtj.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtrwrpaaar.html

[U06] Py：合并两个字典
来源：http://dali.jianghu66.top/Article/details/gtqbvgujrs.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gthzwxipzy.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtooylygxf.html

{v: k for k, v in d.items()}
来源：http://dali.redwolf501.top/Article/details/gtqmtinkri.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gtigjhicqu.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gtmyhnrtbm.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gtyrrfviqm.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gtpuwcmfnf.html

[U10] Py：按值排序字典
来源：http://dali.svipenyu.cn/Article/details/gtiamgzkmd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gtlpetabsb.html

[U11] Py：生成器表达式
来源：http://dali.snrcjt.cn/Article/details/gtcijserjd.html

(x * 2 for x in arr)
来源：http://dali.yj202588.top/Article/details/gtpjhwpgmt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fengsongda.top/Article/details/gtcoaljzce.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtrnouzjul.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gtxliedlso.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gtapwbjcct.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gtstjhobru.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gtpiapscbb.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gtpmkixntp.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcowbyqtb.html

[U16] Py：命令行参数解析
来源：http://dali.hnxiangtu.top/Article/details/gtufdptiro.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xylfe.cn/Article/details/gtnmtmzmuc.html

[U17] Py：初始化日志
来源：http://dali.mhx1999.top/Article/details/gtihfytzse.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtqlvhpasx.html

[U18] Py：预编译正则
来源：http://dali.nanxuanxn.top/Article/details/gtbenvlqml.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gtwzlcpowi.html

[U19] Py：正则替换带回调
来源：http://dali.shuidangran.top/Article/details/gtyyrfklnf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgufenzy.top/Article/details/gtmceluldn.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gthddotjtm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gtomidogzl.html

[U21] Py：自定义上下文管理器
来源：http://dali.shangyingyoupin.top/Article/details/gtmixtfxvu.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gtuasygucg.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gttkkwdhrl.html

list(zip(*m))
来源：http://dali.wangshuangyany.cn/Article/details/gtiifycteh.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gtbrxuitjl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.316326.xyz/Article/details/gtmxweienb.html

[U24] Py：路径操作
来源：http://dali.xuanzx.com/Article/details/gtdxjakadk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gthccyzint.html

[U25] Py：CSV 按字典读
来源：http://dali.zhixingplan.top/Article/details/gtkgdkfrnv.html

csv.DictReader(f)
来源：http://dali.zhiwuduotai.top/Article/details/gtwzhpahcb.html

[U26] Py：并发下载
来源：http://dali.cheryme.top/Article/details/gtapvxojme.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fengsongda.top/Article/details/gtwjezqgbp.html

[U27] Py：异步 HTTP
来源：http://dali.hnxiangtu.top/Article/details/gthuhbbwlj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuanzhike.top/Article/details/gtijtsddpc.html

[U28] Py：类型别名
来源：http://dali.dashuyun.cn/Article/details/gtiwwvnvnu.html

UserId = int
来源：http://dali.snrcjt.cn/Article/details/gtokwsavsj.html

[U29] Py：属性校验
来源：http://dali.guannengcc.top/Article/details/gtowxhkiwz.html

@property 与 @x.setter 配合
来源：http://dali.nanxinkj.top/Article/details/gtvedyaegy.html

[U30] Py：数据类
来源：http://dali.nanxinkj.top/Article/details/gtwiaegfui.html

@dataclass(slots=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtelrntreb.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gtzvxdcpol.html

python -m pytest -q
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzumooru.html

[U32] Py：代码格式化
来源：http://dali.9152youxi.cn/Article/details/gtifilksnv.html

ruff format . && ruff check --fix .
来源：http://dali.cashguo.top/Article/details/gtqlscfgjy.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfxfhtyy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanlonqtl.html

[U34] Py：判断编码
来源：http://dali.yangfankeji.com/Article/details/gtdwjtnqug.html

chardet.detect(raw)
来源：http://dali.jinqigufen.top/Article/details/gtwrxdyzie.html

[U35] Py：发送邮件
来源：http://dali.zhixingplan.top/Article/details/gtikbxpbbh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xuanzx.com/Article/details/gtjiakhqns.html

[U36] Py：定时任务
来源：http://dali.0kj1m.cn/Article/details/gtngtbfvfp.html

schedule.every(10).minutes.do(job)
来源：http://dali.hammf.cn/Article/details/gtckxricsh.html

[U37] Py：读写 Excel
来源：http://dali.hnqzz.top/Article/details/gtsnkdpzmj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gtqrergchm.html

[U38] Py：获取脚本所在目录
来源：http://dali.guowangkeji.top/Article/details/gtazcrnrny.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gtspkxdkfp.html

[U39] Py：判断是否在交互环境
来源：http://dali.feifeiyinyue.top/Article/details/gtzgydgivh.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gtvjnyukcp.html

[U40] Py：打印到标准错误
来源：http://dali.wangshuangyany.cn/Article/details/gtpxiiwnij.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gttjetuyhs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnxiangtu.top/Article/details/gtzdkntqzt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shangyingyoupin.top/Article/details/gtapaqszib.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yonumen.top/Article/details/gtyrpekjrb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.andypj.xyz/Article/details/gtprpxnirx.html


<!-- 参考信息 -->