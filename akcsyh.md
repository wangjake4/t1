代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gt2zmciuhzg.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxurxlzy.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gt2qxhehgeh.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gt2ptgxbkxy.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gt2kiflqxhu.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gt2ybcjftid.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2tunwvtxv.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gt2huodzwfa.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gt2mtkzghks.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gt2xnczltpu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gt2zzznosdc.html

[S30] C：头文件保护
来源：http://dali.yongpay.top/Article/details/gt2yyjhujlb.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gt2zfzybgnr.html

#define X_H
来源：http://dali.gogol.net.cn/Article/details/gt2ffldseqn.html

#endif
来源：http://dali.fzhhl.top/Article/details/gt2hbtjxslq.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gt2zisuysow.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gt2ozyqhdav.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gt2adlccszi.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gt2shrfqipg.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gt2ktdzzbyg.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gt2hhotxbly.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gt2phzexiig.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gt2luxogpll.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gt2etqoaooo.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gt2qtfxjpyw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2fkgpuzio.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2aliuyoga.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eibznakw.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gt2xxvjofgp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gt2tkrxtbet.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gt2owwwfwot.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gt2lfylffre.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2duvgwmwl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gt2uwahztpv.html

[S40] C++：查找元素
来源：http://dali.zhoulong.xyz/Article/details/gt2kssfeztg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gt2bvytpzcn.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfxprvak.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gt2mauwnhqi.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gt2ddorbmuh.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gt2desitybn.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gt2yndxsben.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2ophknerq.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijgcrjrz.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gt2cjdocmso.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gt2vwmxwtbn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxfglvlr.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gt2skdysryt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gt2sjoutdfq.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gt2miyyreff.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gt2wuzmtfof.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2npeegrkb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gt2dvwnrete.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bituwtzt.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjnnqyke.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gt2wxsnuadc.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gt2auzkqrxm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2fwlkujks.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gt2ggcrbtci.html

static_cast<double>(a) / b
来源：http://dali.daxiang520.top/Article/details/gt2pejbjwmp.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gt2kkstquhl.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gt2vsxyjwtm.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gt2xuynutco.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gljjawqc.html

[S54] C++：异常处理
来源：http://dali.shzxlz.cn/Article/details/gt2xhqgetij.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.havefunace.top/Article/details/gt2giajdbcv.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gt2jhlmbdkz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2srnfgjdl.html

[S56] C++：optional
来源：http://dali.cucudq.cn/Article/details/gt2dkhasmpo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dedershv.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gt2fczgokex.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gt2eyfxgveb.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gt2kjzvecdg.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gt2gbwoqtwy.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gt2fjilqdwh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gt2nngvcknm.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gt2vyovqahw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gt2aymalmhb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2dhmttrmu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gt2vniqcsdi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycwuzkip.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2dzwxwmmi.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slafwwsb.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gt2libzzknv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gt2askslkob.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlwhdoth.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gt2mrkmcovo.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gt2wyjhkthm.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gt2kbjtvuum.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gt2nskfrrye.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gt2mjdwcszv.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gt2sanfzjjn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2fgziijqu.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyyxnens.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gt2mspypiud.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gt2swdgfmto.html

data class User(val name: String, val age: Int)
来源：http://dali.yuxming.cn/Article/details/gt2keakbslk.html

[T09] Kotlin：扩展函数
来源：http://dali.guowangkeji.top/Article/details/gt2sjsiuoid.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gt2siligaqg.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gt2zrbahsqj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gt2hzelfgki.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gt2hmivexyt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gt2ocdssobm.html

[T12] Kotlin：解构声明
来源：http://dali.guannengcc.top/Article/details/gt2onoyizdt.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2malokimv.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpowlsdv.html

val m = mapOf("a" to 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2zuadqgbq.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gt2miwanbwm.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gt2qsghymau.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gt2glprcrgj.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gt2aosfsvcl.html

[T16] Swift：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2gnxnaivg.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2blksvcos.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gt2megblvuv.html

var a = 1;  let b = 2
来源：http://dali.redwolf501.top/Article/details/gt2jbxnhqpf.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2vgoveuhy.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gt2tyqfwyeu.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gt2kwxfxxvg.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2deloqbvj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2txrktzih.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.0kj1m.cn/Article/details/gt2plmveryz.html

[T21] Swift：遍历
来源：http://dali.meibo888.top/Article/details/gt2gtrepmet.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgsxsmyk.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2plbpgtwq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gt2auqinumd.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lyqlxxmt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gt2xjnzfcis.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gt2qhfbvgff.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daxiang520.top/Article/details/gt2bmrwaiid.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gt2gtyoqbsh.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gt2lchfjnng.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gt2paoahepm.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gt2sveeualh.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gt2rcqrntwp.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gt2motiykxt.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gt2yxhetzwo.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gt2qrkleegu.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gt2xfhtyopf.html

guard let x = opt else { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sbsoiknq.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gt2zbaxfgya.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gt2airjpfts.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gt2rsvrrxof.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2spkgqsuj.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2podssloy.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gt2ycwkzkea.html

[T33] Lua：表（数组）
来源：http://dali.nanxinkj.top/Article/details/gt2pqohynlt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gt2msifpffe.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gt2stzbxsxa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gt2njgnkigg.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gt2hwrjypua.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bokhtuss.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gt2hioumynx.html

function add(a, b) return a + b end
来源：http://dali.jinqigufen.top/Article/details/gt2elnmeeti.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gt2wuqsgjap.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gt2dcilfwgc.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gt2zqlvhhzv.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gt2yeatvnow.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gt2bebagcjo.html

string.find(s, "%d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2dvrhlfpt.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gt2hmlhnybf.html

setmetatable({}, { __index = base })
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwelndpo.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2wrlhiwsx.html

print "Hello\n";
来源：http://dali.gogol.net.cn/Article/details/gt2bzanxtew.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gt2pxncdlqs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.bjfxy.top/Article/details/gt2ktgpbdmf.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2nqretpth.html

"值: $a"
来源：http://dali.yvedp.cn/Article/details/gt2vnsvhzpv.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gt2fcfbekso.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gt2ydxiwukd.html

[T45] Perl：数组遍历
来源：http://dali.dianchejie.cn/Article/details/gt2upzgcnzl.html

for my $x (@arr) { print $x; }
来源：http://dali.hysaishi.cn/Article/details/gt2ndzdunge.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gt2arhvugzs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kidhktku.html

[T47] Perl：正则捕获
来源：http://dali.9152youxi.cn/Article/details/gt2eabkdnrb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnqzz.top/Article/details/gt2lkawqzqg.html

[T48] Perl：正则替换
来源：http://dali.xziqi.cn/Article/details/gt2mdbbxmib.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gt2kfzfgvap.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2twvgzgvk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2zxjxkxjq.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2yssfsdxf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gt2snpuvnwd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guannengcc.top/Article/details/gt2tjntfvvm.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2smnpplvt.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gt2ymniqbtc.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbwaseev.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gt2bvbrzbfy.html

[T53] Scala：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2ewcxfvim.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gt2cfhdrtag.html

[T54] Scala：集合映射
来源：http://dali.smart0.xyz/Article/details/gt2lfpcjlxb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guannengcc.top/Article/details/gt2jjncaktv.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2trkzmqhk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2vrrdhnks.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gt2sxozurht.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gt2fdtavltz.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gt2dgtnuoib.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hysaishi.cn/Article/details/gt2trvgfiom.html

[T58] Scala：函数定义
来源：http://dali.zhongyouzk.top/Article/details/gt2vlvcfewv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.quarkkingdee.top/Article/details/gt2bxkrhqyt.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2yzhfqmcc.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gt2yllharti.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gt2uabzrmen.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gt2mhgzbupt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ghppfsvp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gt2lhddsiso.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2uwigolcj.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gt2nikzkare.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gt2rdxxgsbg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgliuzgc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ybcxt.top/Article/details/gt2mbkqlvhu.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gt2mvjfyzhh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhixingplan.top/Article/details/gt2qclxxqvm.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gt2yodgpksw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sufxvd.cn/Article/details/gt2bczkkwhl.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcocvjmc.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzekwdvi.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gt2iidtcasd.html

{**a, **b}
来源：http://dali.zycfv.cn/Article/details/gt2tjnztgbh.html

[U07] Py：反转字典键值
来源：http://dali.cdnleiting.top/Article/details/gt2iupieknb.html

{v: k for k, v in d.items()}
来源：http://dali.cdnleiting.top/Article/details/gt2wsqeavqe.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gt2xojjkgsu.html

[y for x in nested for y in x]
来源：http://dali.shzxlz.cn/Article/details/gt2oeavbmqa.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gt2ivgxwwxw.html

max(d, key=d.get)
来源：http://dali.birdmap.top/Article/details/gt2uxaxtltz.html

[U10] Py：按值排序字典
来源：http://dali.guowangkeji.top/Article/details/gt2mghmkjdt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shzxlz.cn/Article/details/gt2kkgtzcpn.html

[U11] Py：生成器表达式
来源：http://dali.c1oappe.top/Article/details/gt2zrykhzso.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gt2zslmifsk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gt2vzvocuaj.html

Counter(arr).most_common(3)
来源：http://dali.0kj1m.cn/Article/details/gt2grvbajns.html

[U13] Py：固定长度队列
来源：http://dali.bjfxy.top/Article/details/gt2bgwssctn.html

deque(maxlen=10)
来源：http://dali.jqgufenzy.top/Article/details/gt2mzcwgsls.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2klueogtc.html

defaultdict(list)
来源：http://dali.ydzc1.top/Article/details/gt2zvpwuqur.html

[U15] Py：高精度计时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysvctcoj.html

t = time.perf_counter()
来源：http://dali.shzxlz.cn/Article/details/gt2efpuzzvz.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gt2mitomehu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gt2rrguhczb.html

[U17] Py：初始化日志
来源：http://dali.yj202588.top/Article/details/gt2jwtivfdl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnqhljtx.html

[U18] Py：预编译正则
来源：http://dali.cucudq.cn/Article/details/gt2bdwxxnur.html

pat = re.compile(r"\d+")
来源：http://dali.cucudq.cn/Article/details/gt2aaijlscj.html

[U19] Py：正则替换带回调
来源：http://dali.yuanzhike.top/Article/details/gt2ghwysbcp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2azufuwpq.html

[U20] Py：缓存函数结果
来源：http://dali.dashuyun.cn/Article/details/gt2aostidcz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxinkj.top/Article/details/gt2aetwxuul.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gt2xnspyalo.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gt2kxiepuyp.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gt2wpabzkss.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gt2rrdgingt.html

[U23] Py：分块读取大文件
来源：http://dali.pycfn.com/Article/details/gt2erawxsaq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gt2ejujawhm.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qezsvqqc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gt2naozwpwz.html

[U25] Py：CSV 按字典读
来源：http://dali.smart0.xyz/Article/details/gt2whdjkvzd.html

csv.DictReader(f)
来源：http://dali.yonumen.top/Article/details/gt2wzcvvolq.html

[U26] Py：并发下载
来源：http://dali.gaohongyu789.top/Article/details/gt2tzhhfgpa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gt2lmxownqt.html

[U27] Py：异步 HTTP
来源：http://dali.tian-w.cn/Article/details/gt2gfyfmkvs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.mhx1999.top/Article/details/gt2wlmffgsl.html

[U28] Py：类型别名
来源：http://dali.kuanghao11.cn/Article/details/gt2szaikqmf.html

UserId = int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kafdpvir.html

[U29] Py：属性校验
来源：http://dali.tianlin.xyz/Article/details/gt2ihfhlrcc.html

@property 与 @x.setter 配合
来源：http://dali.zycfv.cn/Article/details/gt2grwmtmwa.html

[U30] Py：数据类
来源：http://dali.jqgfzy.top/Article/details/gt2tygcvjgn.html

@dataclass(slots=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2scbxfuuj.html

[U31] Py：单测
来源：http://dali.guowangkeji.top/Article/details/gt2tgllkfpb.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gt2amfzfdxc.html

[U32] Py：代码格式化
来源：http://dali.aizwys.cn/Article/details/gt2awhvufcq.html

ruff format . && ruff check --fix .
来源：http://dali.xylfe.cn/Article/details/gt2xmhvktlz.html

[U33] Py：打包发布
来源：http://dali.316326.xyz/Article/details/gt2kppquzli.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gt2axnylleg.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gt2gibgutcl.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gt2bceqheiz.html

[U35] Py：发送邮件
来源：http://dali.yuanzhike.top/Article/details/gt2yqeanomp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sufxvd.cn/Article/details/gt2gtexaort.html

[U36] Py：定时任务
来源：http://dali.hnqzz.top/Article/details/gt2vlfiizgv.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gt2uijiqjke.html

[U37] Py：读写 Excel
来源：http://dali.jinqigfzy.top/Article/details/gt2iqliaxjb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.havefunace.top/Article/details/gt2xmlavean.html

[U38] Py：获取脚本所在目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixbxaedt.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gt2prywxfcj.html

[U39] Py：判断是否在交互环境
来源：http://dali.shzxlz.cn/Article/details/gt2phtfdxpm.html

sys.stdout.isatty()
来源：http://dali.cheryme.top/Article/details/gt2pphvkwdf.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gt2djnzhwqd.html

print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gt2rbexpjnw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gt2ufpoqhyg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cheryme.top/Article/details/gt2wfcwvfax.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sffrahcv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aizwys.cn/Article/details/gt2jedvwkho.html

[U43] PHP：声明命名空间
来源：http://dali.nanxuanxn.top/Article/details/gt2xfebgalx.html

namespace App\Http;
来源：http://dali.fzhhl.top/Article/details/gt2zlwecnas.html

[U44] PHP：开启严格类型
来源：http://dali.yueranfly.top/Article/details/gt2vksvgpwu.html

declare(strict_types=1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxvnsfvi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhongyouzk.top/Article/details/gt2uluknnpk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yjknwddb.html

[U46] PHP：可空类型
来源：http://dali.xziqi.cn/Article/details/gt2cppvtdpx.html

?string $name = null
来源：http://dali.tianlin.xyz/Article/details/gt2qdtihefy.html

[U47] PHP：联合类型
来源：http://dali.tianlin.xyz/Article/details/gt2kgaexdgu.html

int|string $id
来源：http://dali.yangfankeji.com/Article/details/gt2jaqmkpjw.html

[U48] PHP：纯枚举
来源：http://dali.yonumen.top/Article/details/gt2chbotlsq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbxpoewx.html


<!-- 参考信息 -->