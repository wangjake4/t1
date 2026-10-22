代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtklmfyaqb.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtlhdsjbuc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtddammecl.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtiwcuxieg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gtrjprmpfa.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gtdvhggity.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtsdgwkmoq.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gteiabsjvj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtpbzzfnse.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gtmsipfugs.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gtytkeiwkk.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtjogglets.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gtawcahuum.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuzjbdwz.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtfczbvriz.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtpghpqfjq.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtylijzjdo.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gtoeoabvau.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtbkwemses.html

[S30] C：头文件保护
来源：http://dali.hnxiangtu.top/Article/details/gtxokagapo.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gtvlgwziwv.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtbnagihdi.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtinwzzojb.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtaytgabol.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gttorheaig.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtshyyuszd.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtmcpanhsb.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gtzluhgiph.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gttpmtfxrt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtdpxbelto.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtpltjxmhz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gtnreicger.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtuzjlruoh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtezumakot.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gtfkbaupcq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtzjnsdlts.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gtbouwlsit.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tianlin.xyz/Article/details/gtgygikbst.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtlydeofrv.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gtvaeudhcr.html

[S39] C++：自定义比较器排序
来源：http://dali.yueranfly.top/Article/details/gtagyjozhd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhjwyypu.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gtxrpsehsg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gtyseezmbo.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gtwuwcgchs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gteosfiytw.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtbrwlfbuv.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gtcggzrttp.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gtbdomldbx.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gtpavfctxa.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtakgvyxyl.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gthpgcnbyg.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gttuhdkhby.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gtzhvwmtmi.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtzfnpfsfv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gtgnzsfybn.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtxasbwwth.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtemzepfaw.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtwblkaprj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gtjbiduczg.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtmnimwqed.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtkdcmvuet.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtikqandtg.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtbtgaihiv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtthyhkxgp.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gteppbxlvq.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtogsasggn.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzcyicpd.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gtddhrvkap.html

[S53] C++：移动语义
来源：http://dali.tanke756.top/Article/details/gtrnqcimwk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gttcvfuetd.html

[S54] C++：异常处理
来源：http://dali.yj20258.top/Article/details/gthvenukzd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtpfxbcnrq.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gtennsdsdv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gtkvhcolkk.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtxfmqoope.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtpxtnmukf.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpoffdiu.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gtnrbaraxn.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtsfyjumag.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gtkzazbwpv.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtyvndtpaa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gtztagxodt.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigufen.top/Article/details/gtbgacqlbh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.mhx1999.top/Article/details/gtskicdxyn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtokioqane.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtdeagqdtu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttevpfcsb.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtcdgihmzo.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtkzscgtwz.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gtezwdkkau.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gtbsqiokjj.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gtyouzikob.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gtpiqcpvkt.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gtgnwkabxz.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gtbugnbxlc.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gtwkholloh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aizwys.cn/Article/details/gtjyvzzngl.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtzyyafmmq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtzxurujre.html

[T07] Kotlin：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gtrhiufsrd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gtabrshokv.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gtsxszejkq.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gtjhultqnr.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gtnxrclkbb.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gtcxmzkrat.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gtuzfvmpee.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gtnbdjsqrp.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gtkzsraghp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gthxmnlpbs.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtlfagqlno.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtkwonvohk.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gtxgltkhgo.html

val m = mapOf("a" to 1)
来源：http://dali.sysykeji.top/Article/details/gthiqacbow.html

[T14] Kotlin：循环
来源：http://dali.yj20258888.top/Article/details/gteadqocio.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtgrpfzphx.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtipnntfyy.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtftcgsxje.html

[T16] Swift：Hello World
来源：http://dali.ivvv.top/Article/details/gtfgwezpwe.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtqezycfvm.html

[T17] Swift：变量与常量
来源：http://dali.jinqigufen.top/Article/details/gthmghncez.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gtdeiydiep.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtroipottw.html

"值: \(b)"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrrofdem.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gtasnhizpl.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gthtvrzxzg.html

[T20] Swift：数组操作
来源：http://dali.jiagoushi.top/Article/details/gtipodamff.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtohgxkaoj.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gthcgywbts.html

for x in a { print(x) }
来源：http://dali.gogol.net.cn/Article/details/gtwlptzucy.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gtsdjefxvi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gtbaclnppt.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqklmshf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtovyejiac.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gtqcqzbacd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ivvv.top/Article/details/gtowyzctbo.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiipcvkl.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gtnmhjhqmq.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtfjwttppg.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gtoxqwpsoz.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gtgichihjo.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gtowqavqka.html

[T28] Swift：枚举
来源：http://dali.shzxlz.cn/Article/details/gtztxytvtt.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gtgjmjxzna.html

[T29] Swift：guard 提前返回
来源：http://dali.jiagoushi.top/Article/details/gtjsfclvxe.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteseyziho.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gtxzlgqbbu.html

protocol Shape { func area() -> Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtpizzgqii.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gtcnrpqpzu.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtjbbzsqyv.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtuktjylcu.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjktreifp.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gtrrzvafom.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sxryk.cn/Article/details/gtrzuuyedz.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtwxkdvzmw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shzxlz.cn/Article/details/gtxkmyuikj.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gtrtpwitvv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dianchejie.cn/Article/details/gtbvlfmfzj.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gttfbwwlln.html

function add(a, b) return a + b end
来源：http://dali.redwolf501.top/Article/details/gtlnjdlzlv.html

[T37] Lua：字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtlsypnmzj.html

"a" .. "b"
来源：http://dali.hnqzz.top/Article/details/gtogupjvqs.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gtmkgxjssq.html

if x > 0 then print("正") end
来源：http://dali.daxiang520.top/Article/details/gtzziujgka.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtynsrmcom.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtrcuacmhd.html

[T40] Lua：元表
来源：http://dali.yj20258.top/Article/details/gtckgnlnwj.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtrlinpeag.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtqwmrnyka.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gtzqetduio.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtxicqxuqm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gtwgxfoizv.html

[T43] Perl：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtutlgbrrh.html

"值: $a"
来源：http://dali.zdqjudy.top/Article/details/gtsroiyveg.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtphmqqxfr.html

if ($a > 0) { print "正"; }
来源：http://dali.haohaochexian.top/Article/details/gtiqonktlq.html

[T45] Perl：数组遍历
来源：http://dali.yuanzhike.top/Article/details/gtcewftumi.html

for my $x (@arr) { print $x; }
来源：http://dali.daria6918.cn/Article/details/gtaevaupte.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gtwcgaepyy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yangfankeji.com/Article/details/gtmesiudfj.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gtoohcaszb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dianchejie.cn/Article/details/gtzmmdqroh.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gtigcfqmii.html

$s =~ s/old/new/g;
来源：http://dali.fzhhl.top/Article/details/gttaazskbz.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtqlkmwqsi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtwkwlooxb.html

[T50] Perl：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gttndrgtxl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.iojbl.cn/Article/details/gtnzmhsvzl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gtnrnesrzn.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtqxlejott.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtgnzgwioy.html

[T52] Scala：变量
来源：http://dali.meibo888.top/Article/details/gtxfzzozes.html

val a = 1;  var b = 2
来源：http://dali.9152youxi.cn/Article/details/gtnrlbexpj.html

[T53] Scala：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtjlamwmam.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gtnsxhnxqu.html

[T54] Scala：集合映射
来源：http://dali.fzhhl.top/Article/details/gtrwlakqfp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenlongwang.top/Article/details/gtkhwsyerq.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtxhhfvywe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gtkvcmlqdt.html

[T56] Scala：样例类
来源：http://dali.jinqigfzy.top/Article/details/gtypdnbyit.html

case class User(name: String, age: Int)
来源：http://dali.cucudq.cn/Article/details/gteonsiaby.html

[T57] Scala：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtdrpyyqjt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtmgipfvrx.html

[T58] Scala：函数定义
来源：http://dali.tanke756.top/Article/details/gtkbeviqhn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gtwlzmmfgm.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gtzzryivgj.html

for (i <- 1 to 10) println(i)
来源：http://dali.cashguo.top/Article/details/gtjhqwzmtr.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gtiahpwkmd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gtizqizfbf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtymzadxqu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexennxaq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqeirkefa.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gtdtgzouvn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.iojbl.cn/Article/details/gteurnqwkz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gtssxnbann.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwzufxrf.html

[U03] Py：加载 .env 配置
来源：http://dali.dashuyun.cn/Article/details/gtirjczpyd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangtech.top/Article/details/gtswkjjvsl.html

[U04] Py：变量调试打印
来源：http://dali.hnqzz.top/Article/details/gtyqhxuekj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fengsongda.top/Article/details/gtpdrnghop.html

[U05] Py：列表去重且保序
来源：http://dali.birdmap.top/Article/details/gtzecolwcn.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtowvumcdu.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gtnbmugauj.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gtgijfjgpi.html

[U07] Py：反转字典键值
来源：http://dali.mhx1999.top/Article/details/gtdcbqpluq.html

{v: k for k, v in d.items()}
来源：http://dali.wangshuangyany.cn/Article/details/gthuhlxfos.html

[U08] Py：展平二维列表
来源：http://dali.hfpthk.cn/Article/details/gtzldgzlsa.html

[y for x in nested for y in x]
来源：http://dali.xziqi.cn/Article/details/gtecejklws.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gtlzznjylr.html

max(d, key=d.get)
来源：http://dali.yanxiufei.cn/Article/details/gtksvcuabu.html

[U10] Py：按值排序字典
来源：http://dali.yj20258.top/Article/details/gtedqbnonq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ydzc1.top/Article/details/gthgklrbda.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gtwukzzsxt.html

(x * 2 for x in arr)
来源：http://dali.xinyue.icu/Article/details/gtqgoygxlp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gtzdelzbog.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtjvpaicwn.html

[U13] Py：固定长度队列
来源：http://dali.ehwqpu.com/Article/details/gthgtbyrxj.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gtpafgaxmo.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gtvqytftay.html

defaultdict(list)
来源：http://dali.zhengqikj.top/Article/details/gtggpzoscn.html

[U15] Py：高精度计时
来源：http://dali.hywenlv.cn/Article/details/gtpanyhkss.html

t = time.perf_counter()
来源：http://dali.ydzc1.top/Article/details/gthjvbudli.html

[U16] Py：命令行参数解析
来源：http://dali.jqgfzy.top/Article/details/gtrpbbeztt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gtjklhhwir.html

[U17] Py：初始化日志
来源：http://dali.jianghu66.top/Article/details/gtrpxnxrdo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.haohaochexian.top/Article/details/gtmjavphkp.html

[U18] Py：预编译正则
来源：http://dali.cashguo.top/Article/details/gteqphvfuw.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtwhnxhdva.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gtamvohqum.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgufenzy.top/Article/details/gtjttfsrrz.html

[U20] Py：缓存函数结果
来源：http://dali.aizwys.cn/Article/details/gtklhsgluk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gtcujvurad.html

[U21] Py：自定义上下文管理器
来源：http://dali.cucudq.cn/Article/details/gthhmzddvr.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gtqosbfvmw.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gtvwmarrbo.html

list(zip(*m))
来源：http://dali.jlsjyb.cn/Article/details/gtexiwlhze.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gtuwwjbkpt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.vqdsnc.cn/Article/details/gtezoooeyb.html

[U24] Py：路径操作
来源：http://dali.gaohongyu789.top/Article/details/gtzufkieff.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtfjvpianm.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gtspecvlgb.html

csv.DictReader(f)
来源：http://dali.cdnleiting.top/Article/details/gtlrpttsia.html

[U26] Py：并发下载
来源：http://dali.chenlongwang.top/Article/details/gtvigapzsi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ppjwa.cn/Article/details/gtgxxpdgba.html

[U27] Py：异步 HTTP
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhyjypim.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sysykeji.top/Article/details/gtnziunyfm.html

[U28] Py：类型别名
来源：http://dali.tanke756.top/Article/details/gtddsmnyvl.html

UserId = int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqwfzbtr.html

[U29] Py：属性校验
来源：http://dali.sweek.top/Article/details/gtalqmzkos.html

@property 与 @x.setter 配合
来源：http://dali.redwolf501.top/Article/details/gtbfmhdoxi.html

[U30] Py：数据类
来源：http://dali.ybcxt.top/Article/details/gtxciptfwv.html

@dataclass(slots=True)
来源：http://dali.tanke756.top/Article/details/gtpqbgheyr.html

[U31] Py：单测
来源：http://dali.xuanzx.com/Article/details/gtqzuzdwjs.html

python -m pytest -q
来源：http://dali.aibaodan.cn/Article/details/gtjqxetdcw.html

[U32] Py：代码格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtshfgiwtq.html

ruff format . && ruff check --fix .
来源：http://dali.quarkkingdee.top/Article/details/gtyletgjeo.html

[U33] Py：打包发布
来源：http://dali.shuidangran.top/Article/details/gtewtzetyk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.meibo888.top/Article/details/gtvokhhmdy.html

[U34] Py：判断编码
来源：http://dali.daria6918.cn/Article/details/gtkzdnnfzr.html

chardet.detect(raw)
来源：http://dali.yj20258.top/Article/details/gttqwrzgjs.html

[U35] Py：发送邮件
来源：http://dali.yj202588.top/Article/details/gtfaamwazj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gtudatupkt.html

[U36] Py：定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtgmksxipg.html

schedule.every(10).minutes.do(job)
来源：http://dali.9152youxi.cn/Article/details/gtdycfueyh.html

[U37] Py：读写 Excel
来源：http://dali.sufxvd.cn/Article/details/gtsgimingn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gtsjsnurap.html

[U38] Py：获取脚本所在目录
来源：http://dali.guannengcc.top/Article/details/gtrfuksdvz.html

Path(__file__).resolve().parent
来源：http://dali.yueranfly.top/Article/details/gtjlubaflm.html

[U39] Py：判断是否在交互环境
来源：http://dali.daria6918.cn/Article/details/gtnfdbchzo.html

sys.stdout.isatty()
来源：http://dali.gogol.net.cn/Article/details/gtunqbfjns.html

[U40] Py：打印到标准错误
来源：http://dali.daxiang520.top/Article/details/gtahdbhbaw.html

print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtwqjuqbyw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gtoxhrjxga.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yanxiufei.cn/Article/details/gtrpxpbptv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gtokkuvnhw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xylfe.cn/Article/details/gtmjswotfu.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gtudygoolt.html

namespace App\Http;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidfcgyeh.html

[U44] PHP：开启严格类型
来源：http://dali.zycfv.cn/Article/details/gtaklthmeg.html

declare(strict_types=1);
来源：http://dali.gzhubu.top/Article/details/gtmpdcgqkp.html


<!-- 参考信息 -->