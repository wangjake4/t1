代发 wailian999

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gtfbzoxsay.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gtnuolszdv.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gtuodpfigm.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigeutyuq.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gtkceafuse.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gtxaifowsd.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtwbiemzjd.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfubtjav.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gticowizkh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gtkukwfbdh.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtdbgbdtfi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gtbiguntqk.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtnckkaihi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtoppyhzqx.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtleazebbs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtcehsmklt.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtulvbgciz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gtaohekzcs.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtaeqlsfgv.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtyotyxjhd.html

[S39] C++：自定义比较器排序
来源：http://dali.cashguo.top/Article/details/gtjeyuiipl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtfzenfhlu.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gtgiafohph.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlobfqvh.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtonyzurzb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtlfmuyras.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtqzzsptrx.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtjvbemjhi.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gtcknuzyrs.html

auto p = std::make_unique<int>(5);
来源：http://dali.havefunace.top/Article/details/gtelevqhnw.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gtkccurrib.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gtlntmrsjo.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtomyvzybr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gtnybvasfa.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtwhiysdjd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hysaishi.cn/Article/details/gtcdsrypsu.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtlmgmpret.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtmzzeiiuj.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtkviiwtfl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gttwznswfk.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtxozezfls.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gtvjsiktec.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gthnczlgli.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gtbpsykebu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gttrrkezlj.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtczwvuggo.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gtdxorgehq.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gtyttngebv.html

int size() const noexcept { return n_; }
来源：http://dali.daria6918.cn/Article/details/gtvzzugdtq.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gtftiwlcfj.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gtihulfbdn.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtwmjihjbg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gthrhphejm.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtwtoatxmw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gtjydjisze.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtvxankgjv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dianchejie.cn/Article/details/gtwtoevfzw.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gtcqexydlx.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtfulitfjm.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtvqshfjtp.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gtomfmbbdn.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gtpeefnaqw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtslncucld.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtkanatjue.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gtxbwyzuae.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthrloqqhm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gtfsakhiiz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgyxxhtjg.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gtluxnoeef.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtziticosa.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gtoojjhxbe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtkeshfupz.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gtwysfryzj.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtkafbcgqh.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtaqwqobos.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtvlitlwrh.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gtzxhaouoy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtnhsvnevz.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtxafeasjq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtqmvnwysf.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbylzpufi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtlkeefhll.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtoxhzdqyf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtvihgwvyg.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gtbwbcazwr.html

fun String.exclaim() = this + "!"
来源：http://dali.cdnleiting.top/Article/details/gtbimrlftc.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gtgogqpqwp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gtlbszdkll.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gtyjfcwabk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gtekrxndiu.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gtmlxosnqv.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtbuaaeoey.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtuwyxpgtq.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gtzkehzqlz.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gtonbwrdcw.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gtpxcjzhec.html

[T15] Kotlin：接口
来源：http://dali.mhx1999.top/Article/details/gtqiommnbp.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gtqhxfhzzd.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gtercjhwkj.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtcktsarin.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gtyzvbriqo.html

var a = 1;  let b = 2
来源：http://dali.yj202588.top/Article/details/gtgakoooun.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtgxwqttyi.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gtoawixtsc.html

[T19] Swift：可选绑定
来源：http://dali.shuidangran.top/Article/details/gttcgingfr.html

if let n = opt { print(n) }
来源：http://dali.ppjwa.cn/Article/details/gtotzzzlvr.html

[T20] Swift：数组操作
来源：http://dali.daria6918.cn/Article/details/gtignxveyc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cqqwz.cn/Article/details/gtmhdxyijq.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gtfqaedzjh.html

for x in a { print(x) }
来源：http://dali.yj202588.top/Article/details/gtcjlutidp.html

[T22] Swift：字典
来源：http://dali.gogol.net.cn/Article/details/gtkpwcmqbs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gtategohal.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gtgiopznjf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtwagvprhw.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gtcyhfuumu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtdbqkinhp.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtmddqxgbq.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gtkvmcfgtw.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gtgxeirdsb.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gtydwarcxj.html

[T27] Swift：错误处理
来源：http://dali.zhixingplan.top/Article/details/gtcwxyfxkf.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gthkscmoye.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gtkrqhsdgd.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gtioiclcnl.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gtkxbthbdf.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gtatomuqgq.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gtepvkchmj.html

protocol Shape { func area() -> Double }
来源：http://dali.quarkkingdee.top/Article/details/gtizjpgbic.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gttfbflysz.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtrzgmfghf.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gtyngrtgjj.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtruylwuuc.html

[T33] Lua：表（数组）
来源：http://dali.bjfxy.top/Article/details/gtkymjlhew.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gttolbsyil.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtsuqxeusa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gtvadurzny.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gtiwikoxjh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.snrcjt.cn/Article/details/gtmculiurf.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gticvtofmm.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjefxxaf.html

[T37] Lua：字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtahcjrpqo.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gtpoezludw.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gtzfddjztm.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtoymnxadm.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtzoupfmts.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gtgkdowijb.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gtznmgdzpj.html

setmetatable({}, { __index = base })
来源：http://dali.yanxiufei.cn/Article/details/gtnqrkgbfl.html

[T41] Perl：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtmbmyjghd.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtsdyrwizw.html

[T42] Perl：变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbapffcc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnqzz.top/Article/details/gtnerlknaq.html

[T43] Perl：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtvbkskrwa.html

"值: $a"
来源：http://dali.xuanzx.com/Article/details/gtjbtcgfgk.html

[T44] Perl：条件
来源：http://dali.wangshuangyany.cn/Article/details/gtrjpnytli.html

if ($a > 0) { print "正"; }
来源：http://dali.zhixingplan.top/Article/details/gthhplczqf.html

[T45] Perl：数组遍历
来源：http://dali.zdqjudy.top/Article/details/gtcmvnyzhi.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxktcnxe.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gtslwyhlqy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gtmvwermhr.html

[T47] Perl：正则捕获
来源：http://dali.aibaodan.cn/Article/details/gtnlvnhidv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtairpsyvm.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gtzmtkowdb.html

$s =~ s/old/new/g;
来源：http://dali.snrcjt.cn/Article/details/gtmobcevjo.html

[T49] Perl：函数
来源：http://dali.quarkkingdee.top/Article/details/gtulygjfia.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtznmfdsiq.html

[T50] Perl：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtsvwkzeer.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jianghu66.top/Article/details/gtlchnumcf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtvjxurkmo.html

[T51] Scala：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtjrtawgsn.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtfdntajne.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gtogkiqebd.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtlaituorx.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtbdbdiprv.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtkdurkdau.html

[T54] Scala：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtwbjyavew.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkyzuzjv.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlxhhmbm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwlnvbis.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gtmfwreguf.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtgnmansxr.html

[T57] Scala：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gtlvvmqhyf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigufen.top/Article/details/gtmhkgkmww.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gtojeysrou.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.quarkkingdee.top/Article/details/gtehzezgfd.html

[T59] Scala：循环
来源：http://dali.aizwys.cn/Article/details/gtqshmerpp.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtcekfnkrs.html

[T60] Scala：折叠
来源：http://dali.pycfn.com/Article/details/gtzvhusszl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tian-w.cn/Article/details/gtrbgtmxxu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkwflvxbb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gtixqfecgi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmnawdiys.html

[U01] Py：创建虚拟环境
来源：http://dali.hongshengwenyu.top/Article/details/gtcrmztkjy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.kuanghao11.cn/Article/details/gtpubkuxwf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtwvdbgtpt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gtoyikbpvy.html

[U03] Py：加载 .env 配置
来源：http://dali.yj202588.top/Article/details/gtwopygjyl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangdashe.top/Article/details/gtxrziqlaj.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gtdqhvclya.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ivvv.top/Article/details/gtirqafqus.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gtpdgxnsxv.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtlwvdkxvz.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gtjneudoph.html

{**a, **b}
来源：http://dali.fzhhl.top/Article/details/gtlfvizktm.html

[U07] Py：反转字典键值
来源：http://dali.chenjidiqi.icu/Article/details/gtjmutodwq.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gtkjgqeekc.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gtmafwsmhd.html

[y for x in nested for y in x]
来源：http://dali.shangyingyoupin.top/Article/details/gtgmtzsqcv.html

[U09] Py：字典取最大值的键
来源：http://dali.iojbl.cn/Article/details/gtpcgkvoww.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gtvyduxpib.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gtowwpejut.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gtyojferjc.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gtvxodhulj.html

(x * 2 for x in arr)
来源：http://dali.zdqjudy.top/Article/details/gtirrvlvdi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgufenzy.top/Article/details/gtcpzpmqoq.html

Counter(arr).most_common(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtpmsueeag.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gtnzmrkdwp.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gtbaqetxxd.html

[U14] Py：分组收集到列表
来源：http://dali.shuidangran.top/Article/details/gtklxztppe.html

defaultdict(list)
来源：http://dali.gogol.net.cn/Article/details/gtvyjdicpx.html

[U15] Py：高精度计时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzegtjcxb.html

t = time.perf_counter()
来源：http://dali.yvedp.cn/Article/details/gtdskmgelx.html

[U16] Py：命令行参数解析
来源：http://dali.jiagoushi.top/Article/details/gtpqpnowhf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangshuangyany.cn/Article/details/gtsdskxrdi.html

[U17] Py：初始化日志
来源：http://dali.yongpay.top/Article/details/gtuunvqsfd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuanzx.com/Article/details/gtgmbdhimw.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusiocksp.html

pat = re.compile(r"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtubwruidk.html

[U19] Py：正则替换带回调
来源：http://dali.guannengcc.top/Article/details/gtfhipjhpv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.smart0.xyz/Article/details/gtgzsgainu.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gtmhbcpisr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnqzz.top/Article/details/gtcnxtbxxw.html

[U21] Py：自定义上下文管理器
来源：http://dali.bjfxy.top/Article/details/gtsaresxfd.html

@contextlib.contextmanager
来源：http://dali.gotoacloud.top/Article/details/gtyjidqsvu.html

[U22] Py：矩阵转置
来源：http://dali.yanxiufei.cn/Article/details/gtktliltrv.html

list(zip(*m))
来源：http://dali.yuxming.cn/Article/details/gttipznlqt.html

[U23] Py：分块读取大文件
来源：http://dali.daxiang520.top/Article/details/gtkdhgsehq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nwbrower.top/Article/details/gtauaelrux.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gtizdiylfd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtumkvcjne.html

[U25] Py：CSV 按字典读
来源：http://dali.andypj.xyz/Article/details/gtogndquvf.html

csv.DictReader(f)
来源：http://dali.gotoacloud.top/Article/details/gtgicwjqia.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gtytvqubay.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hysaishi.cn/Article/details/gtyfkdsmjd.html

[U27] Py：异步 HTTP
来源：http://dali.gzhubu.top/Article/details/gticlxvsrk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbimxope.html

[U28] Py：类型别名
来源：http://dali.sxryk.cn/Article/details/gtlqavycvy.html

UserId = int
来源：http://dali.fengsongda.top/Article/details/gtvqxjwyyx.html

[U29] Py：属性校验
来源：http://dali.ydzc1.top/Article/details/gtgiibkmuk.html

@property 与 @x.setter 配合
来源：http://dali.chenzaomai.com/Article/details/gtvdradlhe.html

[U30] Py：数据类
来源：http://dali.jqgfzy.top/Article/details/gtlbcgileh.html

@dataclass(slots=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjefhxdz.html

[U31] Py：单测
来源：http://dali.wangshuangyany.cn/Article/details/gtrqfiakcv.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gtswravyru.html

[U32] Py：代码格式化
来源：http://dali.dianchejie.cn/Article/details/gtysnrzfph.html

ruff format . && ruff check --fix .
来源：http://dali.ydzc1.top/Article/details/gtzqpxrwan.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gtynpmchxg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuetiantiany.cn/Article/details/gtghlpbrpf.html

[U34] Py：判断编码
来源：http://dali.andypj.xyz/Article/details/gtfdoaufxc.html

chardet.detect(raw)
来源：http://dali.aibaodan.cn/Article/details/gtgvrhimpb.html

[U35] Py：发送邮件
来源：http://dali.zhixingplan.top/Article/details/gtonbeezuz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.birdmap.top/Article/details/gtmcuvyhlh.html

[U36] Py：定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gtsgjyxiej.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gtnnxubofu.html

[U37] Py：读写 Excel
来源：http://dali.xylfe.cn/Article/details/gtidbkqzas.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pengpengdd.cyou/Article/details/gtfowxvazj.html

[U38] Py：获取脚本所在目录
来源：http://dali.dianchejie.cn/Article/details/gtxxldsduk.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdulofhr.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtgljhqqer.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gtqzxxlbyn.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigufen.top/Article/details/gtklxannfw.html

print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtowvyukyl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.smart0.xyz/Article/details/gtghkgfwqx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xylfe.cn/Article/details/gtfoyhnotv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fengsongda.top/Article/details/gtmfujwxdm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuetiantiany.cn/Article/details/gtcmzegmfu.html

[U43] PHP：声明命名空间
来源：http://dali.sysykeji.top/Article/details/gtmvyyoefb.html

namespace App\Http;
来源：http://dali.havefunace.top/Article/details/gtgoiqywdq.html

[U44] PHP：开启严格类型
来源：http://dali.vqdsnc.cn/Article/details/gtibsfpfuo.html

declare(strict_types=1);
来源：http://dali.jinqigufen.top/Article/details/gtngvgfcej.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenjidiqi.icu/Article/details/gtzdrmvxxe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtbaadvieq.html

[U46] PHP：可空类型
来源：http://dali.hysaishi.cn/Article/details/gtnimlbxpn.html

?string $name = null
来源：http://dali.hysaishi.cn/Article/details/gtoefjclxt.html

[U47] PHP：联合类型
来源：http://dali.redwolf501.top/Article/details/gtqzyjtbmu.html

int|string $id
来源：http://dali.daria6918.cn/Article/details/gtvcmcfkhh.html

[U48] PHP：纯枚举
来源：http://dali.feifeiyinyue.top/Article/details/gttoblwqhd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdolselio.html

[U49] PHP：只读属性
来源：http://dali.meibo888.top/Article/details/gtzqqrwguq.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gttbudrhbh.html

[U50] PHP：构造器属性提升
来源：http://dali.jlsjyb.cn/Article/details/gtvdsltlhz.html

public function __construct(private int $id) {}
来源：http://dali.jinqigufen.top/Article/details/gtgtkuythx.html

[U51] PHP：数组解构
来源：http://dali.redwolf501.top/Article/details/gtzrjesmkn.html

[$a, $b] = $arr;
来源：http://dali.ehwqpu.com/Article/details/gthemzcixm.html

[U52] PHP：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gtupopdvzn.html

$double = fn($x) => $x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtsdttvhml.html

[U53] PHP：空合并运算符
来源：http://dali.ybcxt.top/Article/details/gtgxesbuoa.html

$v = $a ?? $b ?? "default";
来源：http://dali.yonumen.top/Article/details/gtpfmhlkgb.html

[U54] PHP：空安全调用
来源：http://dali.nwbrower.top/Article/details/gtsaiekxnk.html

$obj?->method()
来源：http://dali.jinghuilouyu.cn/Article/details/gttrbkljgj.html


<!-- 参考信息 -->