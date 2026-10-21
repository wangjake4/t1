代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtcjupcvih.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gteafgxptu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gtnoajsrkh.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtolvhxiiw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gteklsvbza.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtlmumefby.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ybcxt.top/Article/details/gthpgyaiaq.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtladxyerl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gtlzyanhrp.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gtvymvgehs.html

memcpy(dst, src, n);
来源：http://dali.sweek.top/Article/details/gtpnyaerlv.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gtawaindue.html

memset(a, 0, sizeof a);
来源：http://dali.ybcxt.top/Article/details/gtvcnacton.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gtvbdgyzpk.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gttajifbqe.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gtrlhpmtsr.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtmnwuehxn.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiudiyctn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gthktprxln.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gtcowzdvhk.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtlrhagyjg.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gtrgwtnzaz.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtswakgnot.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gtrcpgjccb.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gtayhmzjfr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gtfxfoujkd.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gtalbbdrdt.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gtetrfpmsu.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtvnnzcyee.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gtyxfariok.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtxbnmlzdv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gtqklavbih.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtidfadlru.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtvzqfmiwa.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtmhxdoujk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtixsbengu.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtcracenqf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtbxkbaxbq.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufgubvfv.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtmsgssmko.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gtmlqnnxed.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gtxjlicmix.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gtlktmkjfe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthptbthpm.html

[S41] C++：类与构造函数
来源：http://dali.redwolf501.top/Article/details/gtcnvajxsv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gtymvpdzwu.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtlecgdibb.html

class B : public Base { public: void f() override {} };
来源：http://dali.cucudq.cn/Article/details/gtkcmesxcn.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gtovvnsixc.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gteqlfpbot.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzppuwwhm.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltyntfcq.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gtkmryemkr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gtqggrgsft.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtphxumwzj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtnvkevggs.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gtfjahialy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gtydcjbnop.html

[S48] C++：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxprqxsz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtqoqiziet.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gtbuvobotx.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gtsxwrstzz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gtlfzffqdn.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtmouxzpyv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtwsihywoc.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gtumpurnvv.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gtiqpnzfaj.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gthnzfyjny.html

int size() const noexcept { return n_; }
来源：http://dali.nanxinkj.top/Article/details/gtxbtzmglg.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gtgwtztewz.html

std::vector<int> w = std::move(v);
来源：http://dali.0kj1m.cn/Article/details/gtyxpvsixo.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gtozguutmn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtbzetsuep.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gtvyfhzcpt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtyujfkqva.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gtiueqzjph.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gtueiqgfuu.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtjjvhxtxq.html

constexpr int N = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtuatbmrcx.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gtxhczkvfe.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtfzusypzn.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gtialkgiba.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gtlsvhnrbb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtnfbccwbt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gtjujwkadr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfntttusg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gtuemufxsd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtuzgnmqaw.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtxyjngpse.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtxylloomu.html

[T02] Kotlin：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftnztbes.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gtockdknol.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtneiscfiu.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtebuozylw.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gtrmcydcvn.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gtpvultilb.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtckvazpyp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gtqhsodtem.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtqrzyrcrb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtbwgfbkxs.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtwqusgcrw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtvoftdade.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gtryvbkkbi.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gtfbjlisom.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gtxzbqggby.html

fun String.exclaim() = this + "!"
来源：http://dali.yongpay.top/Article/details/gthmzqjjqz.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtmgrhxxxe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gtyawvdrth.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gtivtgbkdf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtbxvguemq.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtxiabueox.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtsyuylcvx.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gtcbgkjplo.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gtzbtubxmm.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtdeddccvp.html

for (i in 1..10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtvzxokpbd.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gtzfgiyihi.html

interface Shape { fun area(): Double }
来源：http://dali.ppjwa.cn/Article/details/gtrkicsixj.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtbxntxgzd.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtaedxbmxx.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gtsfrnpexf.html

var a = 1;  let b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtnpyrpqro.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtqkvfjsgz.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gtarksaywx.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gtsocckhmn.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcanyhpjn.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gtzmgsnosb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gtlwflaqxc.html

[T21] Swift：遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtgpzilwdx.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtwohhfgfg.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtsuxrtfcq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gtcmugkgcq.html

[T23] Swift：函数
来源：http://dali.zdqjudy.top/Article/details/gttyvxwsvo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yonumen.top/Article/details/gtduvaehln.html

[T24] Swift：闭包
来源：http://dali.c1oappe.top/Article/details/gtsrosezer.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtvqrbbmis.html

[T25] Swift：结构体
来源：http://dali.gogol.net.cn/Article/details/gtgmykvsfx.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtobltqapm.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gtqvxdwdlt.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoognkwtl.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjahinqsq.html

do { try f() } catch { print(error) }
来源：http://dali.yonumen.top/Article/details/gtpnutrgyn.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gtbwkhfjua.html

enum Color { case red, green }
来源：http://dali.jinqigfzy.top/Article/details/gtrmdgbhzn.html

[T29] Swift：guard 提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtkopbimfj.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gtlbbugkjh.html

[T30] Swift：协议
来源：http://dali.guannengcc.top/Article/details/gtvslsqgzk.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjzqxjnu.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtdwshpxlo.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtigtbxasb.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gtlntpploh.html

local a = 1
来源：http://dali.ybcxt.top/Article/details/gttosfgsle.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkdjjssz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gtcilygykg.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gtokoymzvs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtkxysxqfi.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gtqycefcyn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shuidangran.top/Article/details/gtunfymvkw.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtlqbdjbyw.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gtziaiywdz.html

[T37] Lua：字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmzolqcc.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gtmucispnb.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gtcvacxabf.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gtfefxjihq.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtrmwjecov.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gtxskmbrwy.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gtdhircgjs.html

setmetatable({}, { __index = base })
来源：http://dali.vqdsnc.cn/Article/details/gttwlnayfz.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtuhtvzdvd.html

print "Hello\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtxkbdxcdg.html

[T42] Perl：变量类型
来源：http://dali.dianchejie.cn/Article/details/gtrznzjwho.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gtqodagbdb.html

[T43] Perl：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gthhjsjvns.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gtttlzzxct.html

[T44] Perl：条件
来源：http://dali.yj20258888.top/Article/details/gtdgovfbta.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gttuhqnfln.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gtrunkexid.html

for my $x (@arr) { print $x; }
来源：http://dali.xinyue.icu/Article/details/gtximbkjcr.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyjqmvmd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuanzx.com/Article/details/gtrmehvoud.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gtrprvbxoj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnqzz.top/Article/details/gtsctcfrcm.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtjemerwcx.html

$s =~ s/old/new/g;
来源：http://dali.xuanzx.com/Article/details/gthbhjwhtm.html

[T49] Perl：函数
来源：http://dali.jqgfzy.top/Article/details/gtgqubljlq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtbbybczrf.html

[T50] Perl：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtpkudacpc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gtsnbjepfc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gtrbvdpoiy.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gttxvbjxky.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtzodlkmmv.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gtlqnrtacu.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gtlmunmuxq.html

[T53] Scala：字符串插值
来源：http://dali.havefunace.top/Article/details/gtijjfkdro.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtupiftqxe.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtskexcvxf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.0kj1m.cn/Article/details/gtfteyolvu.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtxgpsapoo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gtziebephl.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gtlahlwyzd.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtkpxwncdr.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtqlqensuz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.bjfxy.top/Article/details/gtpwcqjswl.html

[T58] Scala：函数定义
来源：http://dali.xuanzx.com/Article/details/gtmsuoylho.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtebqkihng.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtyxmpnorw.html

for (i <- 1 to 10) println(i)
来源：http://dali.sxryk.cn/Article/details/gthponxfkn.html

[T60] Scala：折叠
来源：http://dali.yonumen.top/Article/details/gtlmywolsq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtqkoeococ.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtyvmituzw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqctbtjo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzbtxkmcm.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gtepoluhxm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.feifeiyinyue.top/Article/details/gtugxmmdwm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yueranfly.top/Article/details/gtcdjxfnug.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhixingplan.top/Article/details/gtxrmwqrzk.html

[U03] Py：加载 .env 配置
来源：http://dali.yuxming.cn/Article/details/gtcumnujxw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cdnleiting.top/Article/details/gtvgfkbeqf.html

[U04] Py：变量调试打印
来源：http://dali.snrcjt.cn/Article/details/gthbccllii.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gaohongyu789.top/Article/details/gtctocpuey.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gttrnrzfoj.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtwkndzcvo.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gtrsnxiwrp.html

{**a, **b}
来源：http://dali.jyoumei.cn/Article/details/gteirvzpcy.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gtjrbdwomo.html

{v: k for k, v in d.items()}
来源：http://dali.yongpay.top/Article/details/gttcpupiua.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gtptoastvn.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gtldydarav.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gtkgnmhpvo.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gtsresxhsg.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gtwhghbcji.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gtlepdmwmr.html

[U11] Py：生成器表达式
来源：http://dali.yj20258888.top/Article/details/gtghzctdsx.html

(x * 2 for x in arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcoiprra.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sxryk.cn/Article/details/gtlmwhgvcs.html

Counter(arr).most_common(3)
来源：http://dali.yuanzhike.top/Article/details/gtdsgvmtmb.html

[U13] Py：固定长度队列
来源：http://dali.gogol.net.cn/Article/details/gtggdilupr.html

deque(maxlen=10)
来源：http://dali.vqdsnc.cn/Article/details/gtshzifyws.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gteaijrjkl.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gtnzqvavmb.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gtokjyplil.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gtyofpttvo.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigfzy.top/Article/details/gtvrxyhyik.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gtxluarrkx.html

[U17] Py：初始化日志
来源：http://dali.c1oappe.top/Article/details/gtfeyxuzlv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gtgnyedwos.html

[U18] Py：预编译正则
来源：http://dali.yonumen.top/Article/details/gtzqqcxmrj.html

pat = re.compile(r"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzgqgtys.html

[U19] Py：正则替换带回调
来源：http://dali.birdmap.top/Article/details/gtmhirsmcj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gtcmglgrue.html

[U20] Py：缓存函数结果
来源：http://dali.pycfn.com/Article/details/gtuwhmhpbn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cucudq.cn/Article/details/gtljcjcuhn.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gtqwqtsdum.html

@contextlib.contextmanager
来源：http://dali.9152youxi.cn/Article/details/gteddztpva.html

[U22] Py：矩阵转置
来源：http://dali.ybcxt.top/Article/details/gtrspsuvbx.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gtfsrpzsrm.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gtihlwgqji.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuanzx.com/Article/details/gtccnvsvmx.html

[U24] Py：路径操作
来源：http://dali.ppjwa.cn/Article/details/gtfsqksxqg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gthwyzgpzy.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gtyqnvksmr.html

csv.DictReader(f)
来源：http://dali.kuanghao11.cn/Article/details/gtgdyxkyje.html

[U26] Py：并发下载
来源：http://dali.mhx1999.top/Article/details/gtxqrdfkea.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.c1oappe.top/Article/details/gtiizgwjmk.html

[U27] Py：异步 HTTP
来源：http://dali.yueranfly.top/Article/details/gtfsarrkhg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yangfankeji.com/Article/details/gtqqxlpijv.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gtcnvclgud.html

UserId = int
来源：http://dali.yj20258888.top/Article/details/gtzwgqyvuf.html

[U29] Py：属性校验
来源：http://dali.9152youxi.cn/Article/details/gtoqmyqecc.html

@property 与 @x.setter 配合
来源：http://dali.chenzaomai.com/Article/details/gtpzhllrsh.html

[U30] Py：数据类
来源：http://dali.0kj1m.cn/Article/details/gttqljehui.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiqodkmc.html

[U31] Py：单测
来源：http://dali.yonumen.top/Article/details/gtalowucwe.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gtasnjvcod.html

[U32] Py：代码格式化
来源：http://dali.svipenyu.cn/Article/details/gtpclvhzhg.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gtwfxuaxfz.html

[U33] Py：打包发布
来源：http://dali.andypj.xyz/Article/details/gthvszpqsp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shangyingyoupin.top/Article/details/gtdpxqrryf.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gthzvfjhpk.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gtetgsleyo.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gtidvfsyei.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.vqdsnc.cn/Article/details/gtlhvwggdc.html

[U36] Py：定时任务
来源：http://dali.sxryk.cn/Article/details/gtqxzcdyvw.html

schedule.every(10).minutes.do(job)
来源：http://dali.daxiang520.top/Article/details/gtgklpbgif.html

[U37] Py：读写 Excel
来源：http://dali.c1oappe.top/Article/details/gtvmdciczk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hongshengwenyu.top/Article/details/gtursnpbyu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhoulong.xyz/Article/details/gtwtragjfu.html

Path(__file__).resolve().parent
来源：http://dali.shangyingyoupin.top/Article/details/gtvwnpzhup.html

[U39] Py：判断是否在交互环境
来源：http://dali.shangyingyoupin.top/Article/details/gtxvsrhdfg.html

sys.stdout.isatty()
来源：http://dali.quarkkingdee.top/Article/details/gtqqgevyxr.html

[U40] Py：打印到标准错误
来源：http://dali.jiagoushi.top/Article/details/gtsviogphj.html

print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmwlgefa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.9152youxi.cn/Article/details/gtrjqxehaw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigufen.top/Article/details/gtpwcsutrd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.pycfn.com/Article/details/gtovqlddht.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yonumen.top/Article/details/gtdcddtoot.html

[U43] PHP：声明命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gttopdwlwz.html

namespace App\Http;
来源：http://dali.yj20258888.top/Article/details/gtcihbfaeg.html

[U44] PHP：开启严格类型
来源：http://dali.vqdsnc.cn/Article/details/gtrhihvzlm.html

declare(strict_types=1);
来源：http://dali.yueranfly.top/Article/details/gtuiutmdnz.html


<!-- 参考信息 -->