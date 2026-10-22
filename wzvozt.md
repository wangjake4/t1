代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gtujkclfqs.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtqdjiztcw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtkzhabegq.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtgenxejxc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gtbjrmtprz.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gtlovdddnk.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtmpumkdir.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gtycyomlnb.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gtxtqaqqhz.html

[S27] C：定义常量
来源：http://dali.iojbl.cn/Article/details/gtupofnoyu.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtmskrenwp.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gttavimvwx.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtolwhbnum.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtgejltoji.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gtmquckkpr.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtheqnexfa.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gtdjwgzfpe.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gtsahclsgm.html

#endif
来源：http://dali.nwbrower.top/Article/details/gttqvhjjow.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtybchtdzs.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gtawkrtjgp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtswhjablh.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtarikpwok.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gtquqblsgg.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtyidykiki.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtkusasavw.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gtqrokycrq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gthznhxqvj.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvywctjt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtyimkcmuy.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtfqvvjygt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtcmxiylli.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtdhoioaes.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtjyfsnvey.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gthyogzjfb.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtqhfweyqg.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtouaxwrho.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjrlmcri.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gtqdchwpnu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gtievqfacj.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gtazhvtido.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtqgqmuoem.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gttwqtyfnh.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gttrdqulpq.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gtlbtlsrww.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gtwumngszg.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gtoosdjqyk.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtnicmrloe.html

[S45] C++：lambda
来源：http://dali.xylfe.cn/Article/details/gtiduojhgq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gtcglymmrj.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gtcvhnvfys.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gttjdrbrjt.html

[S47] C++：结构化绑定遍历
来源：http://dali.daria6918.cn/Article/details/gtdblkdbpc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtvmhtnyue.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtdnqeevct.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtbpormvvr.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gtlhgvjege.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtdegixtzv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtwzxhvamk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gtsrhntksy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gtnhwhxziv.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtqsehmpsd.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtgpkigios.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtbxanrkde.html

int size() const noexcept { return n_; }
来源：http://dali.pycfn.com/Article/details/gtzvzfisja.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtuvrtljex.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gtsyxxsntf.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gtyofbjces.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtadfbequu.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtfhnzyvsy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtqgxjhqoi.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gtovctsxib.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gtuxkmpwer.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gtdmrwgshi.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gtkrcoxbvu.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtmppwbbhb.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtltdjedrv.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gtlhettmrg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gthprbsdos.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gtqcdmjhuv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtnuxwsgiw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwqefkark.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gtwiycroje.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtuuqlqcak.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gttppyumus.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtfhkljwoi.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtbtqtveuw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gtspcuhevh.html

[T03] Kotlin：字符串模板
来源：http://dali.cucudq.cn/Article/details/gtfamtlsil.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtundezhmx.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gtjoofxbuf.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gttddojvwm.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtqofqwzuz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gtdhhlwlne.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtjuhlazve.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gtnyhouawi.html

[T07] Kotlin：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtmgnxykzt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gtkswtbois.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gtyyxtevft.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtsqumgdax.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtcnicxqiy.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gtkjyelkio.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtsnerqhxb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gtzwklhdst.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gtbwvowgrf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cucudq.cn/Article/details/gtucdvcudc.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gtttlpjpic.html

val (a, b) = Pair(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtvbrcdxmm.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gttwvelvjn.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gtaozbirni.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gteqcoafgx.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gtmzukkkci.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtllcnfpcf.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtsyzobkut.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtxmbuwthn.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtncjabmub.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtoasnaqez.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gtyesvwwur.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtcucfantw.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gtllnfujbd.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gtwrxhlilo.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gtuayhahqu.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gttrtwvbut.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gtelnuftje.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtzisfgapq.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gtstzvqidx.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gtiqqtbklm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gtbxwwkucn.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gtrfwwbabz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gtowqhqwzs.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gtliuyrsqj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtnzoaimor.html

[T25] Swift：结构体
来源：http://dali.yuanzhike.top/Article/details/gtwbkymtpx.html

struct P { var x: Int }
来源：http://dali.havefunace.top/Article/details/gtopgivwgt.html

[T26] Swift：类与重写
来源：http://dali.redwolf501.top/Article/details/gtxscuzwlb.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtgzqvlphw.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtuvmqtwde.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gtjtvgcmif.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtdpoxdyck.html

enum Color { case red, green }
来源：http://dali.316326.xyz/Article/details/gtllrlwnln.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtbwynhzmj.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gtrxjtnlgx.html

[T30] Swift：协议
来源：http://dali.pycfn.com/Article/details/gtqncgifzz.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqsznyhr.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtixuctnll.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gthtggyvai.html

[T32] Lua：局部变量
来源：http://dali.tanke756.top/Article/details/gtrkbsqubj.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gtupjafuga.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumazrirn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sxryk.cn/Article/details/gttbpxvcek.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gtmkjgmfnd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtwauyhaqy.html

[T35] Lua：字典表
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfkypxmj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtgsnrmcxg.html

[T36] Lua：函数
来源：http://dali.hnqzz.top/Article/details/gtxqukogry.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gtinwincoo.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtcdjkhgnv.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gtiosordgs.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gtmhgabjte.html

if x > 0 then print("正") end
来源：http://dali.meibo888.top/Article/details/gtybgquigq.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gttamjdzbi.html

string.find(s, "%d+")
来源：http://dali.tian-w.cn/Article/details/gtmrszqlel.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtngxpuxwr.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gtyoqlzttx.html

[T41] Perl：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtclxcirkw.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtjtmtaadw.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gtbtczmhjf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gtnuwkkftj.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtuqaejilb.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gtfcnirpeh.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gtswoggpcw.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtgjybyrsm.html

[T45] Perl：数组遍历
来源：http://dali.quarkkingdee.top/Article/details/gtmmatgijn.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gtqdlgsmji.html

[T46] Perl：哈希操作
来源：http://dali.xinyue.icu/Article/details/gthkcjvtna.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gtimoamxfx.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gthsqmivpv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gtpatxukue.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gtqpuwjihz.html

$s =~ s/old/new/g;
来源：http://dali.0kj1m.cn/Article/details/gtfptwlpjy.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gtfgtbfkan.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gthwenuikk.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtydzizsrd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shangyingyoupin.top/Article/details/gtwqpuhkwf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtvpdvzmii.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gtqmcacbgy.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotozbljy.html

[T52] Scala：变量
来源：http://dali.fengsongda.top/Article/details/gtiebbsvbg.html

val a = 1;  var b = 2
来源：http://dali.wangdashe.top/Article/details/gtmkdfcmot.html

[T53] Scala：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtmhhlfyhp.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtdsopnupj.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gtbokaehhf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258.top/Article/details/gtjlfozamp.html

[T55] Scala：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gttdyyyooh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gtlmsvizuo.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gttqamamaw.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gtoamsfqxx.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gttvhaykog.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtcztkvzvz.html

[T58] Scala：函数定义
来源：http://dali.hammf.cn/Article/details/gtzlrvcujo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoiblecos.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gtdorvbnve.html

for (i <- 1 to 10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtefrnsuta.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gtungwwqbx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhongyouzk.top/Article/details/gtjcmudefv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnkmnyrhy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gtflytkylh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcdbbnnc.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gtbkmyvoxc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ppjwa.cn/Article/details/gtajwwfglz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xinyue.icu/Article/details/gtxkhysuky.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gtpfmoahaw.html

[U03] Py：加载 .env 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtfqolmlhy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tianlin.xyz/Article/details/gtqbritqeo.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gtqwskqizl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gtfbzpnpey.html

[U05] Py：列表去重且保序
来源：http://dali.dashuyun.cn/Article/details/gtrmsrljyg.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtghvsypsq.html

[U06] Py：合并两个字典
来源：http://dali.hnqzz.top/Article/details/gthbmdpsyn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gtbeiftvws.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gtcvpgtlhs.html

{v: k for k, v in d.items()}
来源：http://dali.wangshuangyany.cn/Article/details/gtstppsejo.html

[U08] Py：展平二维列表
来源：http://dali.hfpthk.cn/Article/details/gtgbynmbep.html

[y for x in nested for y in x]
来源：http://dali.xylfe.cn/Article/details/gtqxidmawh.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gtqiznlocj.html

max(d, key=d.get)
来源：http://dali.xuetiantiany.cn/Article/details/gtupomdgfa.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gtfjthapqt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.kuanghao11.cn/Article/details/gtfolvxlmf.html

[U11] Py：生成器表达式
来源：http://dali.chenzaomai.com/Article/details/gtjgeoancl.html

(x * 2 for x in arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtznplyicq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gtjuxwiyyl.html

Counter(arr).most_common(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtdlzavywi.html

[U13] Py：固定长度队列
来源：http://dali.shangyingyoupin.top/Article/details/gtwimmvmjg.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gtarwnobkp.html

[U14] Py：分组收集到列表
来源：http://dali.xziqi.cn/Article/details/gtufgaskba.html

defaultdict(list)
来源：http://dali.fzhhl.top/Article/details/gtfnjhzkgr.html

[U15] Py：高精度计时
来源：http://dali.mhx1999.top/Article/details/gtumkxmhda.html

t = time.perf_counter()
来源：http://dali.bjfxy.top/Article/details/gtozopdthp.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gtuiqkpaxj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.haohaochexian.top/Article/details/gttkihnlvc.html

[U17] Py：初始化日志
来源：http://dali.cheryme.top/Article/details/gtrzdktuqm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jyoumei.cn/Article/details/gtfdpvfkzo.html

[U18] Py：预编译正则
来源：http://dali.9152youxi.cn/Article/details/gtteksuxpr.html

pat = re.compile(r"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtrkoqyjwt.html

[U19] Py：正则替换带回调
来源：http://dali.hongshengwenyu.top/Article/details/gtapxthfpd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.redwolf501.top/Article/details/gtgerqvooa.html

[U20] Py：缓存函数结果
来源：http://dali.zhengqikj.top/Article/details/gtpoboqqmt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shzxlz.cn/Article/details/gtcddrgmkb.html

[U21] Py：自定义上下文管理器
来源：http://dali.snrcjt.cn/Article/details/gtfbelyhtc.html

@contextlib.contextmanager
来源：http://dali.wangdashe.top/Article/details/gttgbhbuee.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gtmbspykmu.html

list(zip(*m))
来源：http://dali.c1oappe.top/Article/details/gtutzgmala.html

[U23] Py：分块读取大文件
来源：http://dali.guowangkeji.top/Article/details/gtffrpvvpd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yangfankeji.com/Article/details/gtjfusiiqs.html

[U24] Py：路径操作
来源：http://dali.kuanghao11.cn/Article/details/gtcizbaacj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtwmbwshvf.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gttxkwbzki.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtbhdgpllk.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gtrpkasmso.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xziqi.cn/Article/details/gtbjyqavfj.html

[U27] Py：异步 HTTP
来源：http://dali.ybcxt.top/Article/details/gtskhqpkch.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dianchejie.cn/Article/details/gtmlmtyanb.html

[U28] Py：类型别名
来源：http://dali.yangfankeji.com/Article/details/gtmmhbzogv.html

UserId = int
来源：http://dali.redwolf501.top/Article/details/gtfmkqvodn.html

[U29] Py：属性校验
来源：http://dali.jinqigfzy.top/Article/details/gtggeqyiiv.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyjqilnk.html

[U30] Py：数据类
来源：http://dali.ppjwa.cn/Article/details/gtizxxdukp.html

@dataclass(slots=True)
来源：http://dali.cucudq.cn/Article/details/gtairuklzk.html

[U31] Py：单测
来源：http://dali.nanxuanxn.top/Article/details/gtzpkuinkw.html

python -m pytest -q
来源：http://dali.dianchejie.cn/Article/details/gtmxikeghf.html

[U32] Py：代码格式化
来源：http://dali.fengsongda.top/Article/details/gtafaeqvqq.html

ruff format . && ruff check --fix .
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrrutkyu.html

[U33] Py：打包发布
来源：http://dali.tian-w.cn/Article/details/gtelnhcssw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yanxiufei.cn/Article/details/gtmrqvwlqm.html

[U34] Py：判断编码
来源：http://dali.shuidangran.top/Article/details/gtbjdnjwfk.html

chardet.detect(raw)
来源：http://dali.shzxlz.cn/Article/details/gtyifkcvnd.html

[U35] Py：发送邮件
来源：http://dali.yj202588.top/Article/details/gtwbeupxjt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnxiangtu.top/Article/details/gtmgpokehx.html

[U36] Py：定时任务
来源：http://dali.fengsongda.top/Article/details/gtrnemndct.html

schedule.every(10).minutes.do(job)
来源：http://dali.hongshengwenyu.top/Article/details/gtiuaheanf.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gtgimqkyad.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhongyouzk.top/Article/details/gtfcepzfph.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj202588.top/Article/details/gtyiqirajr.html

Path(__file__).resolve().parent
来源：http://dali.birdmap.top/Article/details/gtdiasedtd.html

[U39] Py：判断是否在交互环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhsfqdbf.html

sys.stdout.isatty()
来源：http://dali.snrcjt.cn/Article/details/gtchalhsip.html

[U40] Py：打印到标准错误
来源：http://dali.ybcxt.top/Article/details/gttpcpkbwk.html

print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtdvmvugqw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfdndrrr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yonumen.top/Article/details/gtxhafedsw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gotoacloud.top/Article/details/gtmhsgxsgu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gzhubu.top/Article/details/gttjfvyhof.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gtdthazpfy.html

namespace App\Http;
来源：http://dali.ybcxt.top/Article/details/gtjkvsyymx.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gtzzlbionp.html

declare(strict_types=1);
来源：http://dali.zhoulong.xyz/Article/details/gtxtyorwin.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dianchejie.cn/Article/details/gtfbjignkw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodrfqnsq.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhhnaonb.html

?string $name = null
来源：http://dali.c1oappe.top/Article/details/gtipmagojs.html


<!-- 参考信息 -->