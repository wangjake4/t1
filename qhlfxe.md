代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gtwendvkvi.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtjgupehlb.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gtasnlljyk.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gtsunlcqoy.html

memset(a, 0, sizeof a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsplvtey.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gtjtwdplxs.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtxtglvedt.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtcmyeiicu.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gtkjnxbtiv.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gtcumgdamc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtdzuzmukt.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtgpnokiwq.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gtknkknvyh.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gtaxnqgmlh.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gtsecopndm.html

[S31] C++：Hello World
来源：http://dali.hnqzz.top/Article/details/gtxwklcvfz.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtsbohywph.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaqeemhx.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gtfwmxqowx.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibqvvauw.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscbgffco.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gttqhklixg.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gthnadstup.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gtpucxdfzh.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gtzjnqcbcn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gthcxkozlb.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gtdeceumks.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtailcnwnc.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gtlqaacvkm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtnswjjsjj.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gtmpsexrxm.html

std::sort(v.begin(), v.end());
来源：http://dali.sysykeji.top/Article/details/gtzczbqwlj.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldoahzct.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gtccagokhf.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gtlslwppca.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gtwjirgnzy.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gtnojcjbaa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtdnwqnxmz.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gteaxhdunj.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlygpekdb.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gtvnkjjzuq.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gtluswkikh.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gtexwvxlev.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gtbtlpbkca.html

[S45] C++：lambda
来源：http://dali.gzhubu.top/Article/details/gtpwspkguw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gttnmavmvr.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtgfnextqr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gtyzmymnhx.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtvwyktzse.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtytbokhbv.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtvuyhrnjh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtrxsvgcov.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gtupellupn.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gthmzvkqsw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gthcdzbxox.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gtsdcwvawm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtnbgowdqq.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gtdtntwbar.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gtrwzwuflj.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gtgxfqyxix.html

int size() const noexcept { return n_; }
来源：http://dali.wangdashe.top/Article/details/gtmuwqgjxa.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtvdrvtbjf.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgufenzy.top/Article/details/gtqbhqkjlh.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gtuxuixuzr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtxyukxoin.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gtfufptywl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gtmvfqanyh.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gtocsccllf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gtwbpbeeqc.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtfvtcrzjw.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtxbuywvhy.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gteuufnbmg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gtqfrvpfxp.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gtmzzsqnmv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gtukhxpdtq.html

[S60] C++：遍历并删除元素
来源：http://dali.cashguo.top/Article/details/gtrtuvghbf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtifmcsazh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkfuzumbx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtfktogkur.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlaoquysj.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gtibbfnmht.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtebashtri.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gtthwtwtnr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtuelssbij.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gthmnqaqxc.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtfouzemrf.html

[T04] Kotlin：空安全
来源：http://dali.yonumen.top/Article/details/gttxfasswn.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gtgduhljmy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtuzqzboju.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gttlwtabqc.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gtythbnvtx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszbwzyco.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtazwmuemr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gtrsqmdkhb.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtdepqdsgd.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtxqhiwhtz.html

[T09] Kotlin：扩展函数
来源：http://dali.cqqwz.cn/Article/details/gtitzvsiuj.html

fun String.exclaim() = this + "!"
来源：http://dali.xziqi.cn/Article/details/gtzzmgyqzz.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtafkfnqxc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gtfsmlivlk.html

[T11] Kotlin：协程
来源：http://dali.xylfe.cn/Article/details/gtwnlphpvq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pycfn.com/Article/details/gtxomujytn.html

[T12] Kotlin：解构声明
来源：http://dali.ehwqpu.com/Article/details/gtneivcfhh.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumaiarqv.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gtmupyctvu.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtobsgswuy.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gtbzzrczhb.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gtbtqyarub.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszhipjkx.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gtawvveucv.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtittclqqa.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtyzmgjvwm.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gtiuhbrrjx.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gtdgdwgacg.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtfdohutwo.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gtzvotpsea.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gtfpvxegjo.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtkccguara.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gtmwtzefre.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gtyoucejyy.html

[T21] Swift：遍历
来源：http://dali.yvedp.cn/Article/details/gtdunxtonc.html

for x in a { print(x) }
来源：http://dali.ehwqpu.com/Article/details/gtdlnbpdyl.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gtcbrzwgpi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtzvpbimdy.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gtmnfsbnmw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gtbahryejn.html

[T24] Swift：闭包
来源：http://dali.snrcjt.cn/Article/details/gtgsvyrynj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtpzvmzksv.html

[T25] Swift：结构体
来源：http://dali.ivvv.top/Article/details/gtdmtoyavz.html

struct P { var x: Int }
来源：http://dali.gotoacloud.top/Article/details/gtaxuebtdt.html

[T26] Swift：类与重写
来源：http://dali.zycfv.cn/Article/details/gtutqamkeo.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtrccepfwx.html

[T27] Swift：错误处理
来源：http://dali.yj20258.top/Article/details/gtlhyybibg.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gttlpgfebw.html

[T28] Swift：枚举
来源：http://dali.yuanzhike.top/Article/details/gtlfzhqulp.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gtrdotqadh.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gtyhzbgcdy.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtfksimbbv.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtjpgfniah.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtasrovnax.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gtewnikbum.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtzsoetrcx.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gtsuawjkzr.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gtanneiqhs.html

[T33] Lua：表（数组）
来源：http://dali.zhiwuduotai.top/Article/details/gttxqsbmll.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gzhubu.top/Article/details/gtrqhuncdg.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gtrkjaaeij.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gtfpofzfwb.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtjftfntks.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sysykeji.top/Article/details/gtvjkubujj.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gtviuqkcdf.html

function add(a, b) return a + b end
来源：http://dali.cheryme.top/Article/details/gtabnpfanq.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlajvjkb.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gtlotdcezl.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gtmhzvbyue.html

if x > 0 then print("正") end
来源：http://dali.chenzaomai.com/Article/details/gtklrwiqld.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gttcgvbosf.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gtlkdfeglr.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gtssmggkxl.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gtaqcmxjta.html

[T41] Perl：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtccxzdszt.html

print "Hello\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtzajjbpik.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhtpwrhl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dianchejie.cn/Article/details/gtarzehmcc.html

[T43] Perl：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtmfknijlm.html

"值: $a"
来源：http://dali.cheryme.top/Article/details/gtlyzyuiyp.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gtmvhqxxbm.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtblgmwkte.html

[T45] Perl：数组遍历
来源：http://dali.vqdsnc.cn/Article/details/gtiqblkwwz.html

for my $x (@arr) { print $x; }
来源：http://dali.mhx1999.top/Article/details/gtnympppuk.html

[T46] Perl：哈希操作
来源：http://dali.jlsjyb.cn/Article/details/gtwmskauho.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gtbveswnld.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gtvdupmsaf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gtbbvtpoqq.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtslhnfflb.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gtjpoaasmq.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewkysnhp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtehvfslna.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtbojqnqbc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gtvozbgpwc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtprmkgbzf.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtpzrexvlt.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtkmoispeb.html

[T52] Scala：变量
来源：http://dali.nanxinkj.top/Article/details/gtwunyxoze.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gttggpzmti.html

[T53] Scala：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtqvccnllc.html

s"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtztznupqa.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtxlovudpf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gttarldtjn.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtsbuvddff.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yongpay.top/Article/details/gtygrxhzwt.html

[T56] Scala：样例类
来源：http://dali.cheryme.top/Article/details/gtqmmdlrvg.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gthauhrtai.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gtecgzzdls.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtdzmqrtem.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gtbcnjmyzw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.havefunace.top/Article/details/gtglpiwpwg.html

[T59] Scala：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtuboqbzjy.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtcxsjdexg.html

[T60] Scala：折叠
来源：http://dali.zhiwuduotai.top/Article/details/gtujuigoqi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sweek.top/Article/details/gthendihwk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwudjgyds.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtlovelviu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxwdzlyip.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gtossnjvwp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gtdktkvkqh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.haohaochexian.top/Article/details/gtbuscizdh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gtomitytvc.html

[U03] Py：加载 .env 配置
来源：http://dali.redwolf501.top/Article/details/gtaarabcjt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hysaishi.cn/Article/details/gtialwlihg.html

[U04] Py：变量调试打印
来源：http://dali.kuanghao11.cn/Article/details/gtfoupogbq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.smart0.xyz/Article/details/gthjlnuzeb.html

[U05] Py：列表去重且保序
来源：http://dali.xinyue.icu/Article/details/gtfyjnozlj.html

list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtecykfdtg.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gtjtefkitl.html

{**a, **b}
来源：http://dali.meibo888.top/Article/details/gtdtakwymw.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gtqcxhlkxu.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gtpzqsldvo.html

[U08] Py：展平二维列表
来源：http://dali.daxiang520.top/Article/details/gtvevcbsbi.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gtdiyygtiy.html

[U09] Py：字典取最大值的键
来源：http://dali.vqdsnc.cn/Article/details/gtowttbnhk.html

max(d, key=d.get)
来源：http://dali.jyoumei.cn/Article/details/gtcsbckcii.html

[U10] Py：按值排序字典
来源：http://dali.ydzc1.top/Article/details/gtunthdcwz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gtczvhzmmy.html

[U11] Py：生成器表达式
来源：http://dali.gzhubu.top/Article/details/gtzdnfmcya.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gtotqojzio.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gttariecrl.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzpwnaus.html

[U13] Py：固定长度队列
来源：http://dali.cheryme.top/Article/details/gtzbcwubbn.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfayttgvp.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gtrahwgunr.html

defaultdict(list)
来源：http://dali.wangdashe.top/Article/details/gtjyuvlooq.html

[U15] Py：高精度计时
来源：http://dali.feifeiyinyue.top/Article/details/gtvuiekife.html

t = time.perf_counter()
来源：http://dali.smart0.xyz/Article/details/gtrxdilpao.html

[U16] Py：命令行参数解析
来源：http://dali.jqgufenzy.top/Article/details/gtjaztgfri.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyjhgpqk.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegvspnxh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gtvblsktjy.html

[U18] Py：预编译正则
来源：http://dali.sufxvd.cn/Article/details/gtqgigmpmb.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258.top/Article/details/gtkwqjjwdf.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gtxiejbvci.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuanzx.com/Article/details/gtthjurfah.html

[U20] Py：缓存函数结果
来源：http://dali.jqgufenzy.top/Article/details/gtwmveuogs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtdxoklcnz.html

[U21] Py：自定义上下文管理器
来源：http://dali.yangfankeji.com/Article/details/gtaouyhpaa.html

@contextlib.contextmanager
来源：http://dali.shuidangran.top/Article/details/gtbgkzgqzx.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gtypocaira.html

list(zip(*m))
来源：http://dali.daxiang520.top/Article/details/gtswwhrsmq.html

[U23] Py：分块读取大文件
来源：http://dali.sysykeji.top/Article/details/gtudxywcyv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gtfvtzyatc.html

[U24] Py：路径操作
来源：http://dali.guowangkeji.top/Article/details/gtcktheime.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtaggllswt.html

[U25] Py：CSV 按字典读
来源：http://dali.ivvv.top/Article/details/gtspfwxpvf.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeqqqfnl.html

[U26] Py：并发下载
来源：http://dali.zhongyouzk.top/Article/details/gtnolydirg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangshuangyany.cn/Article/details/gtquzllxan.html

[U27] Py：异步 HTTP
来源：http://dali.shuidangran.top/Article/details/gtyyhhrijh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gteweyolml.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gtertnwlau.html

UserId = int
来源：http://dali.hfpthk.cn/Article/details/gtgzzcgaxi.html

[U29] Py：属性校验
来源：http://dali.hammf.cn/Article/details/gtfollzxwh.html

@property 与 @x.setter 配合
来源：http://dali.aizwys.cn/Article/details/gtlaokpxev.html

[U30] Py：数据类
来源：http://dali.cheryme.top/Article/details/gtljzgbqpu.html

@dataclass(slots=True)
来源：http://dali.chenzaomai.com/Article/details/gtplutffot.html

[U31] Py：单测
来源：http://dali.yuanzhike.top/Article/details/gtdlidzxgf.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomiomlpk.html

[U32] Py：代码格式化
来源：http://dali.fengsongda.top/Article/details/gtsfghwqkb.html

ruff format . && ruff check --fix .
来源：http://dali.shzxlz.cn/Article/details/gtzfkbvybs.html

[U33] Py：打包发布
来源：http://dali.jqgfzy.top/Article/details/gttgyaewzt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gtahdrbidh.html

[U34] Py：判断编码
来源：http://dali.jyoumei.cn/Article/details/gtwzpqdmkp.html

chardet.detect(raw)
来源：http://dali.yj20258.top/Article/details/gtkpaegfsb.html

[U35] Py：发送邮件
来源：http://dali.zhongyouzk.top/Article/details/gtzohnrfho.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hongshengwenyu.top/Article/details/gtmclezqtl.html

[U36] Py：定时任务
来源：http://dali.smart0.xyz/Article/details/gttubciogo.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gtrrxjzbpc.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gtaakvehmi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnxiangtu.top/Article/details/gtjfsqpepe.html

[U38] Py：获取脚本所在目录
来源：http://dali.shzxlz.cn/Article/details/gtxrdwosiy.html

Path(__file__).resolve().parent
来源：http://dali.andypj.xyz/Article/details/gtqywlfmkl.html

[U39] Py：判断是否在交互环境
来源：http://dali.guannengcc.top/Article/details/gtollzbzrr.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gtfffqywzz.html

[U40] Py：打印到标准错误
来源：http://dali.gzhubu.top/Article/details/gtyasykeuh.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gtxtozuiuj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.quarkkingdee.top/Article/details/gtrpyumflk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.snrcjt.cn/Article/details/gthyuyltbl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.kuanghao11.cn/Article/details/gtrkyqrram.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pycfn.com/Article/details/gtcaiesujz.html

[U43] PHP：声明命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtbvoojowj.html

namespace App\Http;
来源：http://dali.hysaishi.cn/Article/details/gthjeobqay.html

[U44] PHP：开启严格类型
来源：http://dali.havefunace.top/Article/details/gtjkahstoe.html

declare(strict_types=1);
来源：http://dali.yj20258.top/Article/details/gtmermlant.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhongyouzk.top/Article/details/gtgeaatcqz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtfmackkng.html

[U46] PHP：可空类型
来源：http://dali.xuanzx.com/Article/details/gtuohtxfxb.html

?string $name = null
来源：http://dali.hnxiangtu.top/Article/details/gtljtmbjmr.html

[U47] PHP：联合类型
来源：http://dali.hysaishi.cn/Article/details/gtvnhdhnrz.html

int|string $id
来源：http://dali.zhengqikj.top/Article/details/gtcpcvrboa.html

[U48] PHP：纯枚举
来源：http://dali.jqgufenzy.top/Article/details/gtlyqbtruy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xylfe.cn/Article/details/gtrngpqwqg.html


<!-- 参考信息 -->