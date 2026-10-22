代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gt2ijyccjfb.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gt2ruxcrwfj.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2rdrjmpvu.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gt2xiqaitzp.html

static int counter = 0;
来源：http://dali.xylfe.cn/Article/details/gt2jfjzdbbq.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gt2dbitzuqr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gt2dqbbjzuz.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gt2cbebxkaf.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gt2eakzehqa.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2klxwzfeu.html

#endif
来源：http://dali.jianghu66.top/Article/details/gt2tjmedwsf.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2torqiusw.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gt2bktrcdwk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gt2hnkrlmki.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gt2pbvnbhjn.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gt2llgxemvo.html

[S33] C++：vector 增删
来源：http://dali.gzhubu.top/Article/details/gt2mqulacdl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2dvbqimwj.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gt2vaqhwbbo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gt2kwggwtfg.html

[S35] C++：map
来源：http://dali.cqqwz.cn/Article/details/gt2ayopdxlq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2fkbpgecc.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gt2qxjpmpvg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2psfqitjo.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gt2zptdjtmw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gt2jdtaxbly.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gt2jwhkeuvt.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2ahpnjzxv.html

[S39] C++：自定义比较器排序
来源：http://dali.fengsongda.top/Article/details/gt2tjdtkbuf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gt2ypjxkluo.html

[S40] C++：查找元素
来源：http://dali.gogol.net.cn/Article/details/gt2cfghwaoz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blvgtzai.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gt2xjqozesb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gt2gnxnxdqe.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gt2mrtuzjyo.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gt2hfaemtwt.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gt2smikdblw.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gt2trgdfeww.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gt2ylafzhwm.html

void inc(int &x) { ++x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2uyodwcqt.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gt2lvtwyeip.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gt2ttpogkml.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqehcica.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2akgclzfc.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcgmmvlg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gt2ifkdsakv.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2vndkgneu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gt2pcxozbgq.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfkmisyu.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2gibebwjb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gt2sipucdvp.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmxfikdo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2njvxhime.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gt2qudergie.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gt2blkceomm.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gt2ptbnpyse.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gt2uvxkfecz.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gt2oclcqkqs.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gt2hxiwjhcm.html

[S54] C++：异常处理
来源：http://dali.quarkkingdee.top/Article/details/gt2gubbwlds.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gt2sacmawsy.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gt2lifsdppz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gt2oapryknx.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gt2mrqerhas.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gt2aapcgalm.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gt2dxkqmbfs.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2ksvumbis.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gt2uvjptjpd.html

namespace ns { int f() { return 1; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2beychmrj.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gt2xxyxyptm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gt2svyepdgh.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gt2ztpfjiei.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnctcjxy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqqpowyk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gt2jqqqbzzj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2hmhhrpsz.html

[T01] Kotlin：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2dilmuejn.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2cllusutq.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gt2mrrjohby.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgufenzy.top/Article/details/gt2arbtdyxz.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gt2fyvprkdp.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gt2magocrtw.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gt2cjrlktzf.html

val n: String? = null;  n?.length
来源：http://dali.gzhubu.top/Article/details/gt2wklhpxrv.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gt2cpunyhjh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gt2xdamalxn.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gt2qgryrbgv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2gctndkwj.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2ouwxyypv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gt2dbjlfqls.html

[T08] Kotlin：数据类
来源：http://dali.iojbl.cn/Article/details/gt2zcecggfr.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gt2gpxejjww.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gt2xyurivlc.html

fun String.exclaim() = this + "!"
来源：http://dali.sweek.top/Article/details/gt2zbfywxof.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gt2lqpldzbh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.316326.xyz/Article/details/gt2kofpyuip.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gt2behicgoq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzejptt.html

[T12] Kotlin：解构声明
来源：http://dali.c1oappe.top/Article/details/gt2hxblbrnx.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2itgdsmyk.html

[T13] Kotlin：只读 Map
来源：http://dali.316326.xyz/Article/details/gt2cydshvdn.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gt2isdjwjww.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gt2soqoqblz.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gt2nuiufsyl.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gt2vgpgrfao.html

interface Shape { fun area(): Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mjxgxjhm.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2zcgqokma.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2uiyokqdp.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2nefprgid.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfapbcex.html

[T18] Swift：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2nyhkchew.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gt2wbfnittj.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gt2hcprtyha.html

if let n = opt { print(n) }
来源：http://dali.gaohongyu789.top/Article/details/gt2bupdawqm.html

[T20] Swift：数组操作
来源：http://dali.ehwqpu.com/Article/details/gt2lweoxuyd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gt2wawfptdh.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2gwiignpl.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gt2jxbxcqvb.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gt2wznibrhe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gt2hkbyjkcy.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gt2uehigmim.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gt2snyxmsgq.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gt2auliqudk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zuwqofig.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gt2rrrmjpza.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gt2dafwcsxe.html

[T26] Swift：类与重写
来源：http://dali.chenjidiqi.icu/Article/details/gt2davwcwqk.html

class A: Base { override func f() {} }
来源：http://dali.aibaodan.cn/Article/details/gt2vmlnevnb.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssggrxzr.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gt2lnjnynhm.html

[T28] Swift：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfyduval.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gt2tebuxggd.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gt2amctgnue.html

guard let x = opt else { return }
来源：http://dali.ybcxt.top/Article/details/gt2nlshgvyx.html

[T30] Swift：协议
来源：http://dali.cqqwz.cn/Article/details/gt2drffsthg.html

protocol Shape { func area() -> Double }
来源：http://dali.ppjwa.cn/Article/details/gt2frutwvin.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2oqrzxnxz.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gt2oqgohgft.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgrsnlox.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gt2xtiscssj.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gt2xxnkdtfu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gt2alrwrdst.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gt2waambiqi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gt2yxhccniz.html

[T35] Lua：字典表
来源：http://dali.ivvv.top/Article/details/gt2lzyixfdx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gt2rxdzfhvi.html

[T36] Lua：函数
来源：http://dali.aizwys.cn/Article/details/gt2tsmgkpte.html

function add(a, b) return a + b end
来源：http://dali.yvedp.cn/Article/details/gt2kzzqvxao.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gt2sozbivrs.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gt2wyzuosli.html

[T38] Lua：条件
来源：http://dali.yanxiufei.cn/Article/details/gt2eqkncstz.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gt2napibxfa.html

[T39] Lua：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2jgvttcwn.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gt2yetzhutv.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gt2uidqybcd.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gt2jtshmlwd.html

[T41] Perl：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2zehcvvym.html

print "Hello\n";
来源：http://dali.andypj.xyz/Article/details/gt2xigiiofc.html

[T42] Perl：变量类型
来源：http://dali.chenzaomai.com/Article/details/gt2llnyfcib.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yangfankeji.com/Article/details/gt2naiitenm.html

[T43] Perl：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2uikmtzcu.html

"值: $a"
来源：http://dali.cheryme.top/Article/details/gt2nbwnsjys.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gt2tkszovdi.html

if ($a > 0) { print "正"; }
来源：http://dali.9152youxi.cn/Article/details/gt2kstrgyhs.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2butpxzfm.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gt2iczzsodb.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gt2ghsgjbby.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gt2nsljuotb.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gt2yzrxkbiu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gt2udhscuwn.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gt2ywkwtcso.html

$s =~ s/old/new/g;
来源：http://dali.xinyue.icu/Article/details/gt2kjetasor.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gt2faguynpb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2olvieeym.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2ugryqsua.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gt2zxynsequ.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xatbinoz.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2ncjizxwk.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2xryfhnvk.html

[T52] Scala：变量
来源：http://dali.chenzaomai.com/Article/details/gt2dqvplxho.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gt2cssijqdz.html

[T53] Scala：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2mdikicjs.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gt2tcfebzgk.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gt2mqkkotvb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gt2obkdruzj.html

[T55] Scala：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gt2echwtfjv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gt2bplzwyiy.html

[T56] Scala：样例类
来源：http://dali.snrcjt.cn/Article/details/gt2dqsjuzfl.html

case class User(name: String, age: Int)
来源：http://dali.shzxlz.cn/Article/details/gt2swjwphlz.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gt2lydkckap.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hysaishi.cn/Article/details/gt2kxhcgbax.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gt2fslsdsrm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2lkrljygr.html

[T59] Scala：循环
来源：http://dali.iojbl.cn/Article/details/gt2tojivcyk.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gt2vsktjtdw.html

[T60] Scala：折叠
来源：http://dali.sufxvd.cn/Article/details/gt2msdecqgi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gt2txmqhcbm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bcydzekg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gt2xocmndiv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2acvbgkcv.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gt2pvizbdlv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ivvv.top/Article/details/gt2nszlmqod.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gt2iywuscqa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cqqwz.cn/Article/details/gt2ypnjmuty.html

[U03] Py：加载 .env 配置
来源：http://dali.jyoumei.cn/Article/details/gt2obesdrom.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.mhx1999.top/Article/details/gt2fhbtedpv.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gt2ltmimmcn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangshuangyany.cn/Article/details/gt2iflvulaz.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmginnry.html

list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gt2gokjjmit.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhgrlcpr.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gt2gjvjmggd.html

[U07] Py：反转字典键值
来源：http://dali.jinqigfzy.top/Article/details/gt2hauighax.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykzfgrfm.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qkmbdesf.html

[y for x in nested for y in x]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjzhouoe.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gt2utdozjmm.html

max(d, key=d.get)
来源：http://dali.hongshengwenyu.top/Article/details/gt2neheufdh.html

[U10] Py：按值排序字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2vesyhxym.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gt2yitjvrjr.html

[U11] Py：生成器表达式
来源：http://dali.hysaishi.cn/Article/details/gt2pcujjsem.html

(x * 2 for x in arr)
来源：http://dali.shzxlz.cn/Article/details/gt2phvuggta.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hammf.cn/Article/details/gt2hqetetuo.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gt2ycprktfd.html

[U13] Py：固定长度队列
来源：http://dali.mhx1999.top/Article/details/gt2njvjxane.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gt2tgolxxmv.html

[U14] Py：分组收集到列表
来源：http://dali.shzxlz.cn/Article/details/gt2dnafnvgn.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gt2mcwvcjmt.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gt2juvwabbo.html

t = time.perf_counter()
来源：http://dali.ehwqpu.com/Article/details/gt2qxuzbjwa.html

[U16] Py：命令行参数解析
来源：http://dali.sxryk.cn/Article/details/gt2qbeubznr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gt2gsosdfej.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gt2biaxnant.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258.top/Article/details/gt2whrzxula.html

[U18] Py：预编译正则
来源：http://dali.xinyue.icu/Article/details/gt2pbwhcgeh.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gt2hmdowrls.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gt2nsfmlgab.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gt2wudvnesw.html

[U20] Py：缓存函数结果
来源：http://dali.fengsongda.top/Article/details/gt2zrjzqxaz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohwpflbu.html

[U21] Py：自定义上下文管理器
来源：http://dali.cqqwz.cn/Article/details/gt2yljjfbii.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gt2kfyetyfv.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gt2yfrnledq.html

list(zip(*m))
来源：http://dali.iojbl.cn/Article/details/gt2emriixcx.html

[U23] Py：分块读取大文件
来源：http://dali.hysaishi.cn/Article/details/gt2aogmxbfs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxjfbnvn.html

[U24] Py：路径操作
来源：http://dali.hfpthk.cn/Article/details/gt2thawtijx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gt2kqzyiwoi.html

[U25] Py：CSV 按字典读
来源：http://dali.yj202588.top/Article/details/gt2jrgqjrcp.html

csv.DictReader(f)
来源：http://dali.zdqjudy.top/Article/details/gt2pxztwqwa.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gt2excwduja.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cheryme.top/Article/details/gt2zjvnpqrh.html

[U27] Py：异步 HTTP
来源：http://dali.guowangkeji.top/Article/details/gt2gevyqhis.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gt2cimkxyhr.html

[U28] Py：类型别名
来源：http://dali.redwolf501.top/Article/details/gt2goucmeor.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gt2yvnzqemg.html

[U29] Py：属性校验
来源：http://dali.316326.xyz/Article/details/gt2afrhjqfb.html

@property 与 @x.setter 配合
来源：http://dali.gzhubu.top/Article/details/gt2maxtunwf.html

[U30] Py：数据类
来源：http://dali.sxryk.cn/Article/details/gt2rxuaxgzl.html

@dataclass(slots=True)
来源：http://dali.guannengcc.top/Article/details/gt2hycngzfc.html

[U31] Py：单测
来源：http://dali.zdqjudy.top/Article/details/gt2yobtdmth.html

python -m pytest -q
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvttiwmu.html

[U32] Py：代码格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2najaxemc.html

ruff format . && ruff check --fix .
来源：http://dali.daria6918.cn/Article/details/gt2fnywqqpy.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gt2mecdosae.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.smart0.xyz/Article/details/gt2mcessvpy.html

[U34] Py：判断编码
来源：http://dali.yvedp.cn/Article/details/gt2hknuenrw.html

chardet.detect(raw)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfuaqmug.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gt2zysezcry.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aibaodan.cn/Article/details/gt2ykrhucix.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2cldjxpli.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigufen.top/Article/details/gt2mbugawfe.html

[U37] Py：读写 Excel
来源：http://dali.dashuyun.cn/Article/details/gt2otexepzr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fzhhl.top/Article/details/gt2froeuwew.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfaaasue.html

Path(__file__).resolve().parent
来源：http://dali.yj20258888.top/Article/details/gt2nxlxwwmz.html

[U39] Py：判断是否在交互环境
来源：http://dali.svipenyu.cn/Article/details/gt2tzzvuqua.html

sys.stdout.isatty()
来源：http://dali.cdnleiting.top/Article/details/gt2fucapyuu.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gt2wowohlwk.html

print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gt2ubkxqjks.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gaohongyu789.top/Article/details/gt2sxmdasdd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqpxubwf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.snrcjt.cn/Article/details/gt2hdenguqn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hammf.cn/Article/details/gt2ahjdkgcg.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gt2zlxdvqns.html

namespace App\Http;
来源：http://dali.zdqjudy.top/Article/details/gt2gbqetprm.html

[U44] PHP：开启严格类型
来源：http://dali.snrcjt.cn/Article/details/gt2sfdcwqkz.html

declare(strict_types=1);
来源：http://dali.jinqigfzy.top/Article/details/gt2szcffwqa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztmlxujb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2pwomyvcg.html

[U46] PHP：可空类型
来源：http://dali.fzhhl.top/Article/details/gt2zvkupnbw.html

?string $name = null
来源：http://dali.meibo888.top/Article/details/gt2lerlpvns.html

[U47] PHP：联合类型
来源：http://dali.sxryk.cn/Article/details/gt2fdqeykqs.html

int|string $id
来源：http://dali.jianghu66.top/Article/details/gt2sptlkqat.html

[U48] PHP：纯枚举
来源：http://dali.fzhhl.top/Article/details/gt2qytcsvvp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shuidangran.top/Article/details/gt2yspgvatr.html

[U49] PHP：只读属性
来源：http://dali.yvedp.cn/Article/details/gt2miihzhfo.html

public readonly string $name
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxhmrvia.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gt2aoceebhx.html

public function __construct(private int $id) {}
来源：http://dali.yangfankeji.com/Article/details/gt2qijkytjb.html


<!-- 参考信息 -->