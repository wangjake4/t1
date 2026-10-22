代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gthsjbwpfl.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gtpnrgnrng.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtowufnnhn.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gtbiczkdhu.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtkluolhom.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gtrlbzxfqt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gtlopsfeev.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtcinchfwe.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtcfyvryfk.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gtrxmiuzsq.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtbgqgmuiy.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtuehhnfdd.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gtezejbiqt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtegclfqpc.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkculbco.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gtxqswsdrp.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqdshthu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gtcjjolssb.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gtawvlsoet.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjrzshzc.html

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gtphbhhqjw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtwkznvswk.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtmwfwzwhh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtxzkvoccu.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtgzadcsph.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkixxtler.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtwyctvthf.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gtariolzqo.html

[S39] C++：自定义比较器排序
来源：http://dali.yueranfly.top/Article/details/gtcllzbupc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtvevftpgg.html

[S40] C++：查找元素
来源：http://dali.yj20258888.top/Article/details/gtehlxilbq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gtwrcxmrfb.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnoygvffz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gtkwhzkuav.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gtolrkuptl.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gtoyzwwaks.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gttlkxxtrh.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gtoekzpjtc.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtolceknwv.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gtqwpgixcc.html

[S45] C++：lambda
来源：http://dali.zycfv.cn/Article/details/gtghwucvic.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.9152youxi.cn/Article/details/gteqdhgagl.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gthweynaoq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gttiebwlah.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gtghiiwzbu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gthweikkci.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtlcdehubk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gtetrsewiw.html

while (std::getline(in, line)) { }
来源：http://dali.mhx1999.top/Article/details/gteedpycms.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gthdrjqfgr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gtsztkvaqd.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtdqabcjqa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtizitasqo.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gtvhcbunld.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtxpbjzyes.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtltbkdmfv.html

int size() const noexcept { return n_; }
来源：http://dali.yanxiufei.cn/Article/details/gtcmufpqoq.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtfsxuyigj.html

std::vector<int> w = std::move(v);
来源：http://dali.0kj1m.cn/Article/details/gtcmuffgaz.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsmuruos.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zycfv.cn/Article/details/gtawswwkgs.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gtgbpugiqu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtwrxfftst.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gtllycmigc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzrdqmrv.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gtkpzytlqh.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtfnkxhpkr.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gtvsseltan.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gtadljtbrk.html

[S59] C++：静态断言
来源：http://dali.guowangkeji.top/Article/details/gtpwyqelwm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gteljcggrl.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtgpbmihvp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gtmwbbfpkt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsxfgczb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtibaxcyrp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthrotzdaq.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtevluuvjz.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtcvzlaxiu.html

[T02] Kotlin：变量
来源：http://dali.xinyue.icu/Article/details/gtwcrnsexf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gtfwpswfdi.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gtkyscxnum.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtsoudldrq.html

[T04] Kotlin：空安全
来源：http://dali.kuanghao11.cn/Article/details/gtigkzbioo.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gtclbudyoo.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtuetmkkoz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gtfccptahe.html

[T06] Kotlin：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtstlmakzy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtmmppfaeb.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gthdixgpxh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gtodrkpqhe.html

[T08] Kotlin：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gtkmgcyvxy.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtkrbzpums.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gtojyizpkz.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtzukvsaud.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gttozyszsq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtlouacdvc.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gtlbbxxxfg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gttnejaqad.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtlimnxhew.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gtgdvxuejb.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gtvpyoitqn.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gthkepiebt.html

[T14] Kotlin：循环
来源：http://dali.xuanzx.com/Article/details/gtwdyskdex.html

for (i in 1..10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtgctsctgj.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gtrynsqgjx.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gtsdtfadto.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gttrdwtduv.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckxxlill.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gtsibqmtsp.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gtcesqelcx.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtidgprflc.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gteynepvnj.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtjyrcqysm.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gtwaodhdmv.html

[T20] Swift：数组操作
来源：http://dali.jqgufenzy.top/Article/details/gtjfkubejw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gtsmvadonx.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtueamsmbf.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gtxffjcdax.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtgzepepie.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtnmxlcmpu.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhcdqjdr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cheryme.top/Article/details/gtqhhrledn.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtmhwfiwwk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtrqdhavpt.html

[T25] Swift：结构体
来源：http://dali.nanxinkj.top/Article/details/gtchunfuie.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gtgsdulbsh.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gtxwwygfao.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gtrxulcbey.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gtwfazlaod.html

do { try f() } catch { print(error) }
来源：http://dali.chenzaomai.com/Article/details/gtkqcxjpdf.html

[T28] Swift：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtohodduei.html

enum Color { case red, green }
来源：http://dali.feifeiyinyue.top/Article/details/gtbvpaufdz.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gtclhyobpw.html

guard let x = opt else { return }
来源：http://dali.xziqi.cn/Article/details/gtggochxsk.html

[T30] Swift：协议
来源：http://dali.hnxiangtu.top/Article/details/gtngqtsnls.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gtabgcpwdy.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gthhuzozim.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgodtjyui.html

[T32] Lua：局部变量
来源：http://dali.birdmap.top/Article/details/gtnsirygiu.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gtboddvaxb.html

[T33] Lua：表（数组）
来源：http://dali.c1oappe.top/Article/details/gtddwsowii.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gtbrlxfbwc.html

[T34] Lua：遍历表
来源：http://dali.hnxiangtu.top/Article/details/gtzneqjccz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhongyouzk.top/Article/details/gtolnfljoc.html

[T35] Lua：字典表
来源：http://dali.zhiwuduotai.top/Article/details/gtssqsufzh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gtklxpjsiz.html

[T36] Lua：函数
来源：http://dali.iojbl.cn/Article/details/gtrtzprxkr.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtwfenrcxl.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gtpiykddxx.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gtcppecuhg.html

[T38] Lua：条件
来源：http://dali.cdnleiting.top/Article/details/gtutwwquof.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gthyobhfho.html

[T39] Lua：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtlsbcaqkp.html

string.find(s, "%d+")
来源：http://dali.dianchejie.cn/Article/details/gtguorjieu.html

[T40] Lua：元表
来源：http://dali.zycfv.cn/Article/details/gtxoryjesi.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gtrhkktmgn.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gtlusuzpfb.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gtwomcjmxm.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gtyjbrhuoe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gtkemidxxb.html

[T43] Perl：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdufulie.html

"值: $a"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhmnlpxf.html

[T44] Perl：条件
来源：http://dali.tanke756.top/Article/details/gtkcxmsise.html

if ($a > 0) { print "正"; }
来源：http://dali.xziqi.cn/Article/details/gthtflgbtq.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gtkcmeubgm.html

for my $x (@arr) { print $x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtojmgshsj.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gtdbyjhwbw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gaohongyu789.top/Article/details/gtqfhohtgn.html

[T47] Perl：正则捕获
来源：http://dali.daxiang520.top/Article/details/gtujiqxhjn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxhvaszht.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gtwwncxyot.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtnzkadgmf.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gtfrvbatrp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gthckmnzfv.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtuqvrvhim.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gtpkvuinhl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gtqogrqnvp.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtptlahern.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtdixzznsc.html

[T52] Scala：变量
来源：http://dali.sxryk.cn/Article/details/gtvedgvege.html

val a = 1;  var b = 2
来源：http://dali.zycfv.cn/Article/details/gtrkgkygzc.html

[T53] Scala：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtqidqrdfc.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gtqbdrhqmm.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gtzgsgsvjh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gtqscacxnh.html

[T55] Scala：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtblcaeeod.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgfzy.top/Article/details/gtipbstjpi.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gtkswaewhu.html

case class User(name: String, age: Int)
来源：http://dali.wangdashe.top/Article/details/gtpizoufnj.html

[T57] Scala：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtejbmnecc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipnxavqx.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gtbuvhzjyk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gtyosyvkye.html

[T59] Scala：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtujtcyfis.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtjqazlsjc.html

[T60] Scala：折叠
来源：http://dali.tian-w.cn/Article/details/gtaduvzrvv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daria6918.cn/Article/details/gtzzuvlpfm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthazuzway.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtruiozzta.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtimomobnt.html

[U01] Py：创建虚拟环境
来源：http://dali.daxiang520.top/Article/details/gtefxwyvcr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gtmthprzjm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gtvsrujgmg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhixingplan.top/Article/details/gtxxlbtvdj.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtfsitwhay.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.kuanghao11.cn/Article/details/gteyzmakzu.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtsnucakuc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.c1oappe.top/Article/details/gtourquvyx.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtdulhrrhf.html

list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gttlkpikbt.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gtohwjzska.html

{**a, **b}
来源：http://dali.hammf.cn/Article/details/gtgnmdjmpk.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gtswwtoahs.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthskkslqx.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpdabdcb.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gtgcjxhdhg.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gtypqxqaix.html

max(d, key=d.get)
来源：http://dali.wangdashe.top/Article/details/gtrjhxusss.html

[U10] Py：按值排序字典
来源：http://dali.yuanzhike.top/Article/details/gtfcxypjji.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gtvhtqtqlj.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gtjqunkfay.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gtycsxaupn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.kuanghao11.cn/Article/details/gtzxfyzyju.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtklwndrhn.html

[U13] Py：固定长度队列
来源：http://dali.gaohongyu789.top/Article/details/gtdegtwddi.html

deque(maxlen=10)
来源：http://dali.nanxinkj.top/Article/details/gtdkrfbozx.html

[U14] Py：分组收集到列表
来源：http://dali.chenlongwang.top/Article/details/gteatijyra.html

defaultdict(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtuuldupts.html

[U15] Py：高精度计时
来源：http://dali.hfpthk.cn/Article/details/gtennmozbj.html

t = time.perf_counter()
来源：http://dali.daxiang520.top/Article/details/gtcixfjwox.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gtwozhdeik.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxabewlm.html

[U17] Py：初始化日志
来源：http://dali.iojbl.cn/Article/details/gthgidikfv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgfzy.top/Article/details/gtkpcljtwd.html

[U18] Py：预编译正则
来源：http://dali.havefunace.top/Article/details/gtgnrwvhbc.html

pat = re.compile(r"\d+")
来源：http://dali.shuidangran.top/Article/details/gtwfmhhrlk.html

[U19] Py：正则替换带回调
来源：http://dali.tianlin.xyz/Article/details/gtbjfanivf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuanzx.com/Article/details/gtvsrsmytk.html

[U20] Py：缓存函数结果
来源：http://dali.c1oappe.top/Article/details/gthswpmgzq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sysykeji.top/Article/details/gtevdikvnd.html

[U21] Py：自定义上下文管理器
来源：http://dali.pengpengdd.cyou/Article/details/gtlqsgafbl.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gtcnxnfluw.html

[U22] Py：矩阵转置
来源：http://dali.snrcjt.cn/Article/details/gtpywhvhzi.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gtjwmcuaxi.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gtsdjgbwzm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gtihmoaivl.html

[U24] Py：路径操作
来源：http://dali.yonumen.top/Article/details/gtvccxjhrb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtpkrvaldk.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gtyufuviwf.html

csv.DictReader(f)
来源：http://dali.havefunace.top/Article/details/gtclkrxsev.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gtdhdlkbqa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gtfohtplfs.html

[U27] Py：异步 HTTP
来源：http://dali.hammf.cn/Article/details/gttnculogm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yonumen.top/Article/details/gtvxkuuqro.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtiiqjteuo.html

UserId = int
来源：http://dali.zhixingplan.top/Article/details/gtxymdvhdq.html

[U29] Py：属性校验
来源：http://dali.cucudq.cn/Article/details/gthiigdwpw.html

@property 与 @x.setter 配合
来源：http://dali.sxryk.cn/Article/details/gtegplrtns.html

[U30] Py：数据类
来源：http://dali.sxryk.cn/Article/details/gtgopturrh.html

@dataclass(slots=True)
来源：http://dali.0kj1m.cn/Article/details/gtwwwbrxkd.html

[U31] Py：单测
来源：http://dali.vqdsnc.cn/Article/details/gtvnxpmfhy.html

python -m pytest -q
来源：http://dali.feifeiyinyue.top/Article/details/gtdnpqyobw.html

[U32] Py：代码格式化
来源：http://dali.zhongyouzk.top/Article/details/gtekfizbqi.html

ruff format . && ruff check --fix .
来源：http://dali.jiagoushi.top/Article/details/gtfiyvuqaj.html

[U33] Py：打包发布
来源：http://dali.zhiwuduotai.top/Article/details/gtvpqqbxlg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.smart0.xyz/Article/details/gthxcfylma.html

[U34] Py：判断编码
来源：http://dali.meibo888.top/Article/details/gtzolqaxpb.html

chardet.detect(raw)
来源：http://dali.ydzc1.top/Article/details/gtlxslfqnt.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gtrqqhicdw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahpdwdwx.html

[U36] Py：定时任务
来源：http://dali.gogol.net.cn/Article/details/gtpahknmri.html

schedule.every(10).minutes.do(job)
来源：http://dali.vqdsnc.cn/Article/details/gtvkdneohn.html

[U37] Py：读写 Excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeeqfkcg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.quarkkingdee.top/Article/details/gtematbckp.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnqzz.top/Article/details/gtjdonlvhr.html

Path(__file__).resolve().parent
来源：http://dali.yuanzhike.top/Article/details/gtqifjvlfn.html

[U39] Py：判断是否在交互环境
来源：http://dali.hysaishi.cn/Article/details/gtkiqkdkpb.html

sys.stdout.isatty()
来源：http://dali.zhixingplan.top/Article/details/gtefvcaidu.html

[U40] Py：打印到标准错误
来源：http://dali.ivvv.top/Article/details/gtvcwtydih.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosklrzju.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbqclfmg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.kuanghao11.cn/Article/details/gtcqggrsuy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.0kj1m.cn/Article/details/gtoiudllcs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigfzy.top/Article/details/gtvldlakuz.html

[U43] PHP：声明命名空间
来源：http://dali.daxiang520.top/Article/details/gtywtofgsu.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gtrxkijibl.html

[U44] PHP：开启严格类型
来源：http://dali.ybcxt.top/Article/details/gtqqdkqygw.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gthfyimzqt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gtripchrnm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gttbcsppbd.html

[U46] PHP：可空类型
来源：http://dali.ybcxt.top/Article/details/gtrjzrmwcz.html

?string $name = null
来源：http://dali.yongpay.top/Article/details/gtwpsdvdgr.html

[U47] PHP：联合类型
来源：http://dali.pycfn.com/Article/details/gtwpzbzbmh.html

int|string $id
来源：http://dali.ehwqpu.com/Article/details/gtoyesvxes.html

[U48] PHP：纯枚举
来源：http://dali.nanxuanxn.top/Article/details/gtcxbgwela.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtentwztjl.html

[U49] PHP：只读属性
来源：http://dali.daxiang520.top/Article/details/gtrfnbkiwk.html

public readonly string $name
来源：http://dali.guannengcc.top/Article/details/gtpzbrxtsp.html

[U50] PHP：构造器属性提升
来源：http://dali.ybcxt.top/Article/details/gtzlfgmypp.html

public function __construct(private int $id) {}
来源：http://dali.cucudq.cn/Article/details/gtsxerximq.html


<!-- 参考信息 -->