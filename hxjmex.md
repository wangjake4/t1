代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtjlvpiduc.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gthftpxwjw.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtroyfhpnz.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gtdoykcvir.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtykgkqjaj.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gtxoaqvfec.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtobglmjjf.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gtzatnuhrw.html

static int counter = 0;
来源：http://dali.guannengcc.top/Article/details/gtyyxguqrt.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtrpdkmild.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtvbyghwab.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gttpjxqksa.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukrefhmu.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbishfiv.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gturxjpdvp.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtlhqdvqmd.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gtrgnsnhkk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtoemidtyb.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtkycsixgo.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtjaqibkvm.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gtbnmzhvhh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sweek.top/Article/details/gttzcxrjzo.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtxkpyyodd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtsmlkulaz.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gthbxegkyw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gteuqexhct.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gtnlqevsvk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtfsswfpxx.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gtdetnjndf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gtcfsflfyt.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gtudrwjcig.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gtovrnlidn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtktoaezrn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gtmeqbjfyn.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gtorpzeqyf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gtqlnhgbmj.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtzwzhqxgb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtoamyeypm.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtzgcxrfor.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gthfrvdstt.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtpvsuthvl.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj202588.top/Article/details/gtruhefqjc.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gturdwvwxx.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelfidbwz.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtlssojhqr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gtljjbijiu.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gtnbjgkwcb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gtcsqkrrsc.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gtqcdwgnvm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gtledjtfdb.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtaccoryjg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gthpstsfft.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gthjiebqna.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gthynutlkh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtfcoqsiyn.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gtluedaavz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtlpdtdncd.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtycureouw.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gtdwnralfc.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtvwsjczcu.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gtdnwkgibj.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmhfsitq.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtedjmitgi.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gtykyndwfw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtszjadgyr.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gtmrvuvgga.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gtgeljuxfh.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gtuzpynxee.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxsuswhn.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gtqsttwfcz.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gthamtmfqo.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqsllmyj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gtzwvuwowz.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gtphsaugzv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtjzfjzgcg.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gtzkpohypc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtcuqoeggu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdxxztbba.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtlzxwfwqb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtcxfkdssu.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtatgizloy.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtydjsdrva.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gthftuczmc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtqoqknvfm.html

[T03] Kotlin：字符串模板
来源：http://dali.cucudq.cn/Article/details/gtebeojvwj.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtszagnowk.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gtorltpynt.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtdzbemdyl.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gtdygopqba.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtglywpwfj.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gtwdsoccrr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtwvmdsude.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtlinjbvla.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtensvollh.html

[T08] Kotlin：数据类
来源：http://dali.cqqwz.cn/Article/details/gtjiwteisg.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtdtnlrd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gteokdudev.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gtpjsyqyqe.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtqnbakhka.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.haohaochexian.top/Article/details/gtrdsdxpyd.html

[T11] Kotlin：协程
来源：http://dali.cqqwz.cn/Article/details/gtbtlhvtel.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gtluxxdcuq.html

[T12] Kotlin：解构声明
来源：http://dali.yj202588.top/Article/details/gtaskhkltg.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtpgactxem.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflncjeng.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtfepdewze.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtdkbsbetm.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtyxnbpcah.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtressbwgd.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gthvzqziqs.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtzohkbzsn.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtaahjobtw.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gtanakqhyu.html

var a = 1;  let b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtqtpgcjrj.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtfzfydkem.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gtwpuwbmnj.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gtjmoifnkd.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gtaexjbqjg.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gtbdqzzpve.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.c1oappe.top/Article/details/gtawarirye.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gthfsruupl.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gtylrpnyxp.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytpqoetx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxuanxn.top/Article/details/gtljmexzcw.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gtxutzrkvz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtxbnxwoma.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gteowfxfzw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtxjbkqgak.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gtcjqqhztb.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gthokdlstq.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gtdeylwufo.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gtahlidrph.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gtpjffnqsq.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gtlmmadpdw.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gtxdrwweom.html

enum Color { case red, green }
来源：http://dali.jqgfzy.top/Article/details/gtgqxklefm.html

[T29] Swift：guard 提前返回
来源：http://dali.sufxvd.cn/Article/details/gtavmqnsoj.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gtpcokftum.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gteftdhiii.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gteluhbtgx.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtjlngobnj.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtdnhlfvkp.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtpyvhcbmq.html

local a = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtxxjijiky.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhlfbqpl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gtkhjlluqr.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gtegkoktqu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokzjjaip.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gttnkmaubq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gtsqwqvjau.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gthdixpeyj.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopxlaost.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtcplxhefz.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gtwopsujyr.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrkedrkv.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gtkzgnrdnn.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtkrtdcqvg.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtfwdegcht.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gtiazwsmas.html

setmetatable({}, { __index = base })
来源：http://dali.chenzaomai.com/Article/details/gtnuebaltr.html

[T41] Perl：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtatnlopzs.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gtohprjsep.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtalvrcxsz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ybcxt.top/Article/details/gtnfekxjmm.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gtnrrgmmhe.html

"值: $a"
来源：http://dali.cdnleiting.top/Article/details/gtfkbcijsq.html

[T44] Perl：条件
来源：http://dali.xinyue.icu/Article/details/gtnaaseqvt.html

if ($a > 0) { print "正"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsfrivjgt.html

[T45] Perl：数组遍历
来源：http://dali.hnqzz.top/Article/details/gtusorslrg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gtxavnfyjn.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gtoknobehi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gtusfbssnr.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gtxvlwnczv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnmctxsop.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gturjpbyrm.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gtethgbimx.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gtpiftppeu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtzluhjvby.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtlodobcuj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yonumen.top/Article/details/gtehvpvzcw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxwxwkcgc.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtcawsyivh.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtlwqzdemz.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovmufgzf.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gtetytyece.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsvqgmjk.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtrwltwwws.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gtkvdqdhje.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sysykeji.top/Article/details/gtifetdzqp.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gttwhsoeih.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtbtvnhntv.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gtlnjurtdh.html

case class User(name: String, age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtwrxrhrbs.html

[T57] Scala：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtddmoyyet.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gtymlmjihv.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gtognxejtx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgufenzy.top/Article/details/gtsvackmzn.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gtwmvqyzdg.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtumdqtpsg.html

[T60] Scala：折叠
来源：http://dali.dianchejie.cn/Article/details/gtintenign.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gtbspstepg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtycfmolls.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gtsgflcbsx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gteumadied.html

[U01] Py：创建虚拟环境
来源：http://dali.ehwqpu.com/Article/details/gttzeolfkt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gtffaxwfie.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gtlycduhio.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guowangkeji.top/Article/details/gtbshbzixu.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gtlmuzbvra.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtegmkjzlw.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gtcvsghasp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gticmtzwpq.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigufen.top/Article/details/gtysrzmmos.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtffirvnpe.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gtgrnzypjh.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gtoitjikqn.html

[U07] Py：反转字典键值
来源：http://dali.aibaodan.cn/Article/details/gtogvahdix.html

{v: k for k, v in d.items()}
来源：http://dali.tian-w.cn/Article/details/gtzhecphyf.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gtfoeuaxhf.html

[y for x in nested for y in x]
来源：http://dali.fengsongda.top/Article/details/gtyxrshxqs.html

[U09] Py：字典取最大值的键
来源：http://dali.cheryme.top/Article/details/gtfstbxani.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gtvkvbyxub.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gteglfskfi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gtzcdezsyp.html

[U11] Py：生成器表达式
来源：http://dali.redwolf501.top/Article/details/gtujabfnop.html

(x * 2 for x in arr)
来源：http://dali.xziqi.cn/Article/details/gtfwzzhxdr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.redwolf501.top/Article/details/gtbdytwtxc.html

Counter(arr).most_common(3)
来源：http://dali.andypj.xyz/Article/details/gtoawsxnzh.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gtgxwkpgbw.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gtnqwitxrz.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqdnaiqm.html

defaultdict(list)
来源：http://dali.yangfankeji.com/Article/details/gtsptooumo.html

[U15] Py：高精度计时
来源：http://dali.cashguo.top/Article/details/gtnzhnoaky.html

t = time.perf_counter()
来源：http://dali.gzhubu.top/Article/details/gtnhoftsyt.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gtjejaylea.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtzqwqep.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gtwniyhsbd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gthodabaoc.html

[U18] Py：预编译正则
来源：http://dali.havefunace.top/Article/details/gtmzwbizho.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gtequdtche.html

[U19] Py：正则替换带回调
来源：http://dali.dianchejie.cn/Article/details/gtvkvqsfet.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.andypj.xyz/Article/details/gtbvnrgdwm.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gtdakvhufs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.havefunace.top/Article/details/gtoehcdhap.html

[U21] Py：自定义上下文管理器
来源：http://dali.pengpengdd.cyou/Article/details/gtwbsjhwyo.html

@contextlib.contextmanager
来源：http://dali.tian-w.cn/Article/details/gtuekneucv.html

[U22] Py：矩阵转置
来源：http://dali.ppjwa.cn/Article/details/gtaadtikyf.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gtnaqfxsst.html

[U23] Py：分块读取大文件
来源：http://dali.fengsongda.top/Article/details/gtniaevnan.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gtddqrogbf.html

[U24] Py：路径操作
来源：http://dali.zdqjudy.top/Article/details/gtjzfqvfbn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtdzkdbspd.html

[U25] Py：CSV 按字典读
来源：http://dali.cqqwz.cn/Article/details/gtebskxpll.html

csv.DictReader(f)
来源：http://dali.cdnleiting.top/Article/details/gtszsnftos.html

[U26] Py：并发下载
来源：http://dali.yanxiufei.cn/Article/details/gtlndrvosx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenlongwang.top/Article/details/gtrdpajtuz.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gtuhmelyko.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gtkddactjf.html

[U28] Py：类型别名
来源：http://dali.shangyingyoupin.top/Article/details/gtymahzkqk.html

UserId = int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopepdmwl.html

[U29] Py：属性校验
来源：http://dali.0kj1m.cn/Article/details/gtcfvqqxgi.html

@property 与 @x.setter 配合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisrjynnr.html

[U30] Py：数据类
来源：http://dali.yuanzhike.top/Article/details/gtnzjsiero.html

@dataclass(slots=True)
来源：http://dali.daria6918.cn/Article/details/gtxyolyapi.html

[U31] Py：单测
来源：http://dali.c1oappe.top/Article/details/gtqcnfgmlo.html

python -m pytest -q
来源：http://dali.vqdsnc.cn/Article/details/gtqkhjfwuo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gtnvqjkify.html

ruff format . && ruff check --fix .
来源：http://dali.ybcxt.top/Article/details/gttpkqleup.html

[U33] Py：打包发布
来源：http://dali.havefunace.top/Article/details/gteiwsnifp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcdtgwuk.html

[U34] Py：判断编码
来源：http://dali.yj20258888.top/Article/details/gtmhbhgnij.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gtsmbypxjm.html

[U35] Py：发送邮件
来源：http://dali.meibo888.top/Article/details/gtctuhkzgj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yangfankeji.com/Article/details/gtfbdqxpet.html

[U36] Py：定时任务
来源：http://dali.xziqi.cn/Article/details/gtnendgrgb.html

schedule.every(10).minutes.do(job)
来源：http://dali.iojbl.cn/Article/details/gtlgedgosq.html

[U37] Py：读写 Excel
来源：http://dali.ehwqpu.com/Article/details/gtvvgntemu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shzxlz.cn/Article/details/gtvmyukvou.html

[U38] Py：获取脚本所在目录
来源：http://dali.tianlin.xyz/Article/details/gtwgeqfjax.html

Path(__file__).resolve().parent
来源：http://dali.yj20258.top/Article/details/gtubdvuubp.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj202588.top/Article/details/gtktmzzimg.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gtlxacpesq.html

[U40] Py：打印到标准错误
来源：http://dali.c1oappe.top/Article/details/gtyxmmekxd.html

print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtuvikvano.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sweek.top/Article/details/gtgbtziilv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhiwuduotai.top/Article/details/gttwfznlmy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.smart0.xyz/Article/details/gtidrhktck.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yueranfly.top/Article/details/gtkelosrdw.html

[U43] PHP：声明命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtpudohkqc.html

namespace App\Http;
来源：http://dali.jqgfzy.top/Article/details/gtpvkjglko.html

[U44] PHP：开启严格类型
来源：http://dali.redwolf501.top/Article/details/gtcujhqjdb.html

declare(strict_types=1);
来源：http://dali.hnxiangtu.top/Article/details/gtwfxqttbn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gtoqeupflm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoernofza.html

[U46] PHP：可空类型
来源：http://dali.yonumen.top/Article/details/gtkkszhphe.html

?string $name = null
来源：http://dali.shzxlz.cn/Article/details/gtlvshtjmx.html

[U47] PHP：联合类型
来源：http://dali.smart0.xyz/Article/details/gtzpczqwml.html

int|string $id
来源：http://dali.jiagoushi.top/Article/details/gtgqckhjje.html

[U48] PHP：纯枚举
来源：http://dali.chenjidiqi.icu/Article/details/gthdhvzhtf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258.top/Article/details/gtnvlzcrln.html


<!-- 参考信息 -->