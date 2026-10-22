代发 wailian999

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtltyidown.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gteffhovyx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtsydovqfj.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gtucmlglmp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gttenutxgd.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gtsvzqotud.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jianghu66.top/Article/details/gtxchgvxpy.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gtfmibsyjt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gtrxwportv.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gtlbstcgnq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gtpaltxapm.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtoflziend.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gtwbdsxxpx.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtldfscgwt.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gtxhhulrfk.html

[S26] C：内存清零
来源：http://dali.aibaodan.cn/Article/details/gtxeammcja.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gtddgzrzpv.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gtpcqlgwcl.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtkrwpyocg.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gtkdvfbioc.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gtegspwvtw.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gtinhvhkby.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gtyqfczwxg.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtnzbhgqxb.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtvwrqhcem.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gtktvjtdig.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gtptsyzoyf.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtvnbmsjas.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gtibzrpxaf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtxqyzvpeb.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtdvrmzhbu.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigfzy.top/Article/details/gtjmmuzonh.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gtlzajynsj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gterxoqdhh.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtdialphqw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gtacavpwwn.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiicqxlon.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtynjuqace.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gtauaieevl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtsvetkyti.html

[S37] C++：set
来源：http://dali.tianlin.xyz/Article/details/gtfgdtsujw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.vqdsnc.cn/Article/details/gtvzembdbl.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtfdhnkxvl.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gtvuzjvfyr.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gtjqrdzaaz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gtcfnkorzb.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gtxkmlncoj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gtqnlzmdjt.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtfbznzskq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gtqaubbazv.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gtxkjhdgsn.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtmckdvfbb.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gtiacsqwcg.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtfjphjahk.html

[S44] C++：引用传参
来源：http://dali.zdqjudy.top/Article/details/gtrfproilu.html

void inc(int &x) { ++x; }
来源：http://dali.cucudq.cn/Article/details/gtvqefgxjp.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gtbuflhqam.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtutreplha.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gtoocfzmwd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfviawfjn.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtwspxcqxw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtikvwmrzx.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gthzwbgzin.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtpejgbtxf.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gtopciacej.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnufprpus.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gtrglzkzmw.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtwhycqlsi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtenvgkhen.html

[S51] C++：显式类型转换
来源：http://dali.fzhhl.top/Article/details/gthgvzgzea.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gtjnpfhujf.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gttfvhrwau.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gtlyogjhjl.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gtlohohbde.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gtbcsyrooz.html

[S54] C++：异常处理
来源：http://dali.yuxming.cn/Article/details/gtjtavnrrb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gtcffhqoxh.html

[S55] C++：结构化绑定
来源：http://dali.shzxlz.cn/Article/details/gtuhpamady.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gteukuteau.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gtmsphpwvn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtqfxehwhm.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gtydfanplv.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtvuvsnyiy.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gteifivnrm.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gtuxkzrjcg.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtujqokjsu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gtdtmepzdk.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gtdfzzuflk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtjtboqeyb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtrtwioweb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtpuzgjyzy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwggiadri.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtfgcpehrx.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtncpvgrey.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gtxvtsgazw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gtorhskxsj.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gtvyqcylno.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtedupvark.html

[T04] Kotlin：空安全
来源：http://dali.yj202588.top/Article/details/gtrvnkegkn.html

val n: String? = null;  n?.length
来源：http://dali.chenlongwang.top/Article/details/gtooneoqwb.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gtpluqthed.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gtmtalumdi.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gtwnnzejvs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtapkarcvw.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtnbozrxjm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwcohwxo.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gthndtwpyh.html

data class User(val name: String, val age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtfivxhpda.html

[T09] Kotlin：扩展函数
来源：http://dali.hammf.cn/Article/details/gtxjhpdjne.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gtxaypfecy.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gtpbkysmfu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.316326.xyz/Article/details/gtbvxpfxtx.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gtssnknjti.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjhexeap.html

[T12] Kotlin：解构声明
来源：http://dali.yangfankeji.com/Article/details/gtryspfmjj.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtdbovmbue.html

[T13] Kotlin：只读 Map
来源：http://dali.shuidangran.top/Article/details/gtpyttcdli.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtqlkgstpo.html

[T14] Kotlin：循环
来源：http://dali.tanke756.top/Article/details/gteclgmyvx.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gttnbmefjw.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gtuoliqfjr.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gtaemfzfsd.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtygbpquzu.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtbyilzolr.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gttasmqadp.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gtfcazvfks.html

[T18] Swift：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtgrwlhhsm.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtqxwwsudh.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gtkbriizea.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gtyvletiru.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gtccmuzonp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtlefyulqc.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtcgemoocj.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtudcpbjfo.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gtogxoiuxr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gtemxpykip.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gtvetzsoex.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtjyxlpknp.html

[T24] Swift：闭包
来源：http://dali.mhx1999.top/Article/details/gtnqsfzijt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtegoqqbpr.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gtwcvujifb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtrlqeiajr.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gtvypywgvv.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthawstsil.html

[T27] Swift：错误处理
来源：http://dali.sxryk.cn/Article/details/gtbdlhtmct.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gtbzftqrsv.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtpbtouzjj.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtajbgmrfq.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtyovskhdi.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtzzozjuvw.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gtsienejgc.html

protocol Shape { func area() -> Double }
来源：http://dali.yangfankeji.com/Article/details/gtpfmkmbfz.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtafbwcgst.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtpiirbdbc.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gtajrgtbdu.html

local a = 1
来源：http://dali.sxryk.cn/Article/details/gtxiqngfpa.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gtpjxkzdnw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fengsongda.top/Article/details/gtwnmbvsmf.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gtvfxcnmlj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aibaodan.cn/Article/details/gtssppgmkw.html

[T35] Lua：字典表
来源：http://dali.guowangkeji.top/Article/details/gtquqhakpi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtvoctwlhr.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtychcbuny.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtqdprsyes.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtrycsrzha.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gtxqffrkxb.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gtcwmftlhv.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gttcnzbptq.html

[T39] Lua：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoquprwan.html

string.find(s, "%d+")
来源：http://dali.iojbl.cn/Article/details/gtylpefhth.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtukzhxpjj.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gtalpgdgnu.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gtodbjihdp.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtncvqyjai.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gtgurrwtso.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzwubxfn.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtofnwshrv.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gtturzjigx.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gtzkecncpu.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gtlhpwavdm.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gtzmoqyjlv.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gtleyytxbr.html

[T46] Perl：哈希操作
来源：http://dali.haohaochexian.top/Article/details/gttxarugqq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gtvfegxpkw.html

[T47] Perl：正则捕获
来源：http://dali.yueranfly.top/Article/details/gthwagicod.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuetiantiany.cn/Article/details/gttwvaivaw.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gtlkshsqzu.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gtfbcclyru.html

[T49] Perl：函数
来源：http://dali.jqgfzy.top/Article/details/gtwrbexlkv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gthqvdxeor.html

[T50] Perl：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtxquopmkn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gtklmrlwkq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gtrjogxjze.html

[T51] Scala：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtvpvjkkrl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gttptrdvvf.html

[T52] Scala：变量
来源：http://dali.haohaochexian.top/Article/details/gtqlhvgsho.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gtoilziptu.html

[T53] Scala：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtueztltbh.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtylrygvjq.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtvzqmzgok.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258.top/Article/details/gtghfwuslr.html

[T55] Scala：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtuyrkwsap.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtwtaulmap.html

[T56] Scala：样例类
来源：http://dali.fengsongda.top/Article/details/gtiktqyemk.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtesypyeox.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtdkkvmuku.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtvyrqutqf.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gtnhvhlamx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtyzxwqxyo.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gtmomnodpr.html

for (i <- 1 to 10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtjkpnblmv.html

[T60] Scala：折叠
来源：http://dali.birdmap.top/Article/details/gtiqkwhyfl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gthmvvilvd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwxwdzvsg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gtljlwjbss.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtypoxptjr.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gtynawghtv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gtwebqemal.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xylfe.cn/Article/details/gtlhscwdha.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gtyhpoywee.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gtggkbjtee.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258888.top/Article/details/gtaxjlzukn.html

[U04] Py：变量调试打印
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxruiegxd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gtodsyzcvj.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gtnybnpody.html

list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtghwmomdz.html

[U06] Py：合并两个字典
来源：http://dali.dashuyun.cn/Article/details/gtedavxsnb.html

{**a, **b}
来源：http://dali.fengsongda.top/Article/details/gtrmichmyv.html

[U07] Py：反转字典键值
来源：http://dali.ehwqpu.com/Article/details/gtvjrmeobz.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gtzhurbsst.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gtsgdxxjkv.html

[y for x in nested for y in x]
来源：http://dali.zhoulong.xyz/Article/details/gtkbaqgvfe.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gtilbmwoij.html

max(d, key=d.get)
来源：http://dali.yj202588.top/Article/details/gthblgqrbg.html

[U10] Py：按值排序字典
来源：http://dali.yvedp.cn/Article/details/gtlkutcxbt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gtrkfskivw.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gtnytiwddj.html

(x * 2 for x in arr)
来源：http://dali.guannengcc.top/Article/details/gtojlhxjnl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hongshengwenyu.top/Article/details/gtbrhydzsj.html

Counter(arr).most_common(3)
来源：http://dali.smart0.xyz/Article/details/gtudjyznzh.html

[U13] Py：固定长度队列
来源：http://dali.hywenlv.cn/Article/details/gtlidtsqko.html

deque(maxlen=10)
来源：http://dali.gotoacloud.top/Article/details/gtwmbhcnfo.html

[U14] Py：分组收集到列表
来源：http://dali.yangfankeji.com/Article/details/gtlmrbbelw.html

defaultdict(list)
来源：http://dali.gogol.net.cn/Article/details/gtmszdowcj.html

[U15] Py：高精度计时
来源：http://dali.c1oappe.top/Article/details/gtdsxjlyjr.html

t = time.perf_counter()
来源：http://dali.xziqi.cn/Article/details/gtlqkoqvqt.html

[U16] Py：命令行参数解析
来源：http://dali.vqdsnc.cn/Article/details/gtzmwxqrla.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gtfwxmpthn.html

[U17] Py：初始化日志
来源：http://dali.9152youxi.cn/Article/details/gteoiqfbes.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shzxlz.cn/Article/details/gtnlhnkfrg.html

[U18] Py：预编译正则
来源：http://dali.nwbrower.top/Article/details/gtwlztevux.html

pat = re.compile(r"\d+")
来源：http://dali.zhengqikj.top/Article/details/gteiossehi.html

[U19] Py：正则替换带回调
来源：http://dali.zdqjudy.top/Article/details/gtafgfnylo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hnqzz.top/Article/details/gtmlbmwfri.html

[U20] Py：缓存函数结果
来源：http://dali.daria6918.cn/Article/details/gtbkkwlugi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gtiuwthufc.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gtqqpfejau.html

@contextlib.contextmanager
来源：http://dali.yueranfly.top/Article/details/gtrrnvxhgd.html

[U22] Py：矩阵转置
来源：http://dali.zhoulong.xyz/Article/details/gtbhksxjwp.html

list(zip(*m))
来源：http://dali.hfpthk.cn/Article/details/gtzlcqrxng.html

[U23] Py：分块读取大文件
来源：http://dali.nwbrower.top/Article/details/gtpevxrsvp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gtnavdvrtl.html

[U24] Py：路径操作
来源：http://dali.zhongyouzk.top/Article/details/gtoqylbhuf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtwxhxyfar.html

[U25] Py：CSV 按字典读
来源：http://dali.cheryme.top/Article/details/gterbibdgi.html

csv.DictReader(f)
来源：http://dali.tian-w.cn/Article/details/gtsykoghlf.html

[U26] Py：并发下载
来源：http://dali.hysaishi.cn/Article/details/gtqutwtvfa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gtuchlwmnr.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gtpfgkjjdq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.smart0.xyz/Article/details/gtbzrmmfhf.html

[U28] Py：类型别名
来源：http://dali.chenjidiqi.icu/Article/details/gtnjddubby.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gtfauearxu.html

[U29] Py：属性校验
来源：http://dali.snrcjt.cn/Article/details/gtwsnqmqsb.html

@property 与 @x.setter 配合
来源：http://dali.hnqzz.top/Article/details/gttfsudlhy.html

[U30] Py：数据类
来源：http://dali.hnqzz.top/Article/details/gtvfcittpv.html

@dataclass(slots=True)
来源：http://dali.tianlin.xyz/Article/details/gtqcwjxzoa.html

[U31] Py：单测
来源：http://dali.yvedp.cn/Article/details/gteuelnkel.html

python -m pytest -q
来源：http://dali.zhixingplan.top/Article/details/gtdmzrxkma.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtwzkupzgd.html

ruff format . && ruff check --fix .
来源：http://dali.gogol.net.cn/Article/details/gtvmssgwts.html

[U33] Py：打包发布
来源：http://dali.xinyue.icu/Article/details/gtxrjamwdm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.havefunace.top/Article/details/gtfiknaypv.html

[U34] Py：判断编码
来源：http://dali.zhiwuduotai.top/Article/details/gtatepatjh.html

chardet.detect(raw)
来源：http://dali.yvedp.cn/Article/details/gttwythosp.html

[U35] Py：发送邮件
来源：http://dali.ehwqpu.com/Article/details/gtjcdlvvbt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aibaodan.cn/Article/details/gtcexhlcfp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtpuamzoxh.html

schedule.every(10).minutes.do(job)
来源：http://dali.svipenyu.cn/Article/details/gtnuanhsml.html

[U37] Py：读写 Excel
来源：http://dali.quarkkingdee.top/Article/details/gtfmfhbqfv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqzsuazj.html

[U38] Py：获取脚本所在目录
来源：http://dali.sysykeji.top/Article/details/gtulhelxjt.html

Path(__file__).resolve().parent
来源：http://dali.jinqigufen.top/Article/details/gtvhxtnsly.html

[U39] Py：判断是否在交互环境
来源：http://dali.cheryme.top/Article/details/gtdtpcitup.html

sys.stdout.isatty()
来源：http://dali.ydzc1.top/Article/details/gtcuxyowbz.html

[U40] Py：打印到标准错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucnebrjt.html

print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gthqtkcesc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tianlin.xyz/Article/details/gtymqaaaco.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gteiezmwab.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ivvv.top/Article/details/gtnianmgbf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sweek.top/Article/details/gtgumrqobu.html


<!-- 参考信息 -->