代发 wailian999

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gtkfixmnkn.html

#define X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtidlcsled.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtsrxjjwkm.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnhwldqz.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gtkuzguyhu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gtzcrfjywv.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtvibgfhet.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gtcwoedzwg.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtyrujspjj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhixingplan.top/Article/details/gtsbxeskiu.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtjjtvmuih.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gtizephhcf.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtwgxgjlaf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtqudthjbi.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gtbxjukrwr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtgrsyaqxk.html

[S37] C++：set
来源：http://dali.bjfxy.top/Article/details/gttjymdxms.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gtxajgleuk.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gtnpweuvkl.html

std::sort(v.begin(), v.end());
来源：http://dali.ivvv.top/Article/details/gtkfkqtxkf.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtidhzbxfl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gtsfsrxgsf.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gtqsdkahaj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtzwuytxvw.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtydyuyyhn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ppjwa.cn/Article/details/gtpjflpzsa.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gtswrcewga.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gtwmqysrxa.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gtwhfkhgas.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtsgxvnwbq.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gtkysgajib.html

void inc(int &x) { ++x; }
来源：http://dali.ivvv.top/Article/details/gtvuajavkc.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gtzrfrlshp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtckkgpqpc.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gtuaaoxhfo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gtkyldcbzb.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gtmmkqbjkx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jlsjyb.cn/Article/details/gtxhqjrahk.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtphadiydw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxonmmmal.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtkvbnbdkg.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gtlpmobdas.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gttuyzjksa.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gtsvsrzyks.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gthquljinh.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtwrsezqcm.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gtpybzlxxc.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gteoojllus.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gtwzjqnbnu.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gtswbmsvxd.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gtactcapir.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtrfluoums.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmiklxqnw.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gtohfvrpab.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtaucmyudf.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gtnvmcsljb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gtwfaptecb.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gtavulsvdi.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtpwuhep.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gtgjctwcpd.html

namespace ns { int f() { return 1; } }
来源：http://dali.iojbl.cn/Article/details/gtfnbllnrp.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gtuymhqtss.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtcbiwcmyy.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gtewhykozj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtofwvcfgk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtivroxddv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gtkmvymtgc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtglzarzvk.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gtqgxjwfnb.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtykslxfuq.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gtysosjzvx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gtsrjjvezt.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtyssncacq.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtnmkcpihy.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gtuaaaqzej.html

val n: String? = null;  n?.length
来源：http://dali.smart0.xyz/Article/details/gttamgoqio.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtymriyfbg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtlkzierow.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtqjienlbc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtntngkoms.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtezasvuzz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gtwrmgtfdx.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbkwczsy.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gtmwlovpsb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtjvrgvr.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gtnlwrxseh.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gtjpzfwnql.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gthsbkrtql.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gtjlooobzk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gtbrcvvkii.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gttegjwoxu.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtpkallgba.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gtjshxuala.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gtkkdpdobg.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gtdkpnbfkx.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtjlwwqcnh.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjnlnowc.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gtbexagnmg.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gtwghprgts.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnbzewbd.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gttdsjldbz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtciyvrqqn.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtnutzrcah.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gtdlinphvy.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gtfciduqhj.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gtvsykotkp.html

[T20] Swift：数组操作
来源：http://dali.hnxiangtu.top/Article/details/gthpczzhpt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gtoopeazrx.html

[T21] Swift：遍历
来源：http://dali.ivvv.top/Article/details/gtvwsuzygr.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gtnbczjmay.html

[T22] Swift：字典
来源：http://dali.yuanzhike.top/Article/details/gtkowljvcb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.316326.xyz/Article/details/gtrqzpkfqs.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtfjbnnmiu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gtfytrpfjr.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gtsizabkhr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtqjjyvywb.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gtuybznque.html

struct P { var x: Int }
来源：http://dali.daria6918.cn/Article/details/gtkmdzyplz.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtzsjiwevy.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtyspjezvw.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtiujxvyle.html

do { try f() } catch { print(error) }
来源：http://dali.xziqi.cn/Article/details/gtfmxhommc.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtdyovdehk.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gtpnsgpvsg.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtpsyeahpt.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gtkgcfimvp.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbazmzltw.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gtjhznaurz.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtbnlpxqrn.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtubdmawvg.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtygoekmzo.html

local a = 1
来源：http://dali.yuanzhike.top/Article/details/gtspomomql.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gtbwxfeplx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gtztqspyox.html

[T34] Lua：遍历表
来源：http://dali.zhiwuduotai.top/Article/details/gtdcobsrae.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtgugoabkz.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gtfkbexfck.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtmqensvrk.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gtwudaqufj.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtsixrlvof.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtkbwqpwho.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gthqganipg.html

[T38] Lua：条件
来源：http://dali.cheryme.top/Article/details/gtypeoavdy.html

if x > 0 then print("正") end
来源：http://dali.jinqigfzy.top/Article/details/gtftrvgqye.html

[T39] Lua：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtyzicddso.html

string.find(s, "%d+")
来源：http://dali.tian-w.cn/Article/details/gtohijosvp.html

[T40] Lua：元表
来源：http://dali.ybcxt.top/Article/details/gtzfikxoac.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gtgasdwhql.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtlfydzezs.html

print "Hello\n";
来源：http://dali.0kj1m.cn/Article/details/gtgxojwvls.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtobscecpo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dianchejie.cn/Article/details/gturtrwfds.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gtwcihmpfy.html

"值: $a"
来源：http://dali.haohaochexian.top/Article/details/gthszvwuyo.html

[T44] Perl：条件
来源：http://dali.sufxvd.cn/Article/details/gtlfddobqp.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjsiczrp.html

[T45] Perl：数组遍历
来源：http://dali.jlsjyb.cn/Article/details/gtayktbxqb.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gtymdlluiq.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gtavqkorhw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtykigchgc.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gthfufxcdq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gtbdnxmida.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gtoveluxar.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gtfcwutjrr.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gtmpwebtrx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtbkxbakeu.html

[T50] Perl：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtyjjwdmvf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuanzx.com/Article/details/gtpxdjydkt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnvktqzhp.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtxodhcjuw.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtjvetiskr.html

[T52] Scala：变量
来源：http://dali.ydzc1.top/Article/details/gtsvzvgwwr.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqlsttfs.html

[T53] Scala：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtoqblnoxe.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtsggoskde.html

[T54] Scala：集合映射
来源：http://dali.xuanzx.com/Article/details/gtuyhxkpoz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gtdmranuhy.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtvtiegkhu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jyoumei.cn/Article/details/gtniephrjc.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gtxygdugdp.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gthqaotzzz.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtbmmljkjn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhzbdcpd.html

[T58] Scala：函数定义
来源：http://dali.chenjidiqi.icu/Article/details/gtvksqypok.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtplfrddwh.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gtnblcnajo.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gtgxxzmqch.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gtkljxfdcs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhengqikj.top/Article/details/gtfudighct.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdxtddtoc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gthvffwooi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtywhsvovm.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gtvffdlldt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gtwgglcope.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hfpthk.cn/Article/details/gtntvirbgj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuxming.cn/Article/details/gtfmymgfhy.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gtlghwptcu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gtxpgzabdf.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtfnincnhk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tianlin.xyz/Article/details/gtkgewnrjk.html

[U05] Py：列表去重且保序
来源：http://dali.yj202588.top/Article/details/gtirmuxcrg.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtdlxjjauk.html

[U06] Py：合并两个字典
来源：http://dali.tanke756.top/Article/details/gtiqvxkbvx.html

{**a, **b}
来源：http://dali.zdqjudy.top/Article/details/gtdmrldpcv.html

[U07] Py：反转字典键值
来源：http://dali.yuxming.cn/Article/details/gtpblmxaxj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gtxqppwnih.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gtpozavnmq.html

[y for x in nested for y in x]
来源：http://dali.sysykeji.top/Article/details/gtwtfntuum.html

[U09] Py：字典取最大值的键
来源：http://dali.jiagoushi.top/Article/details/gteinirtni.html

max(d, key=d.get)
来源：http://dali.snrcjt.cn/Article/details/gtsoxalozn.html

[U10] Py：按值排序字典
来源：http://dali.zhiwuduotai.top/Article/details/gtbzfimvxh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.meibo888.top/Article/details/gtxjqactlk.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gtcpofjinm.html

(x * 2 for x in arr)
来源：http://dali.shzxlz.cn/Article/details/gtklmtngzc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ehwqpu.com/Article/details/gtychxhsea.html

Counter(arr).most_common(3)
来源：http://dali.redwolf501.top/Article/details/gtaxbeqcis.html

[U13] Py：固定长度队列
来源：http://dali.hysaishi.cn/Article/details/gtozrkehnj.html

deque(maxlen=10)
来源：http://dali.yanxiufei.cn/Article/details/gtxbzfetqf.html

[U14] Py：分组收集到列表
来源：http://dali.meibo888.top/Article/details/gtqkogrhkj.html

defaultdict(list)
来源：http://dali.c1oappe.top/Article/details/gtvpfrorhp.html

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gtbgypcmjf.html

t = time.perf_counter()
来源：http://dali.kuanghao11.cn/Article/details/gtargawkve.html

[U16] Py：命令行参数解析
来源：http://dali.ybcxt.top/Article/details/gtrikbvxor.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtzsjcqakc.html

[U17] Py：初始化日志
来源：http://dali.meibo888.top/Article/details/gtjbjrtpvt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxinkj.top/Article/details/gtpqpqjfsn.html

[U18] Py：预编译正则
来源：http://dali.redwolf501.top/Article/details/gtydeuwgpu.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gtsrjtlvyk.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gttzoeynal.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gtqsfizcxr.html

[U20] Py：缓存函数结果
来源：http://dali.cqqwz.cn/Article/details/gtljuolthj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhiwuduotai.top/Article/details/gthfxkjsvq.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuanzhike.top/Article/details/gtmczegxze.html

@contextlib.contextmanager
来源：http://dali.chenlongwang.top/Article/details/gtkdkwmivk.html

[U22] Py：矩阵转置
来源：http://dali.zhengqikj.top/Article/details/gtlxtosonp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gtswsfykiu.html

[U23] Py：分块读取大文件
来源：http://dali.yongpay.top/Article/details/gtifkbawzr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ehwqpu.com/Article/details/gtrhgtjkko.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gtddcsivgf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxohvaufh.html

[U25] Py：CSV 按字典读
来源：http://dali.shzxlz.cn/Article/details/gtpdppfetu.html

csv.DictReader(f)
来源：http://dali.jianghu66.top/Article/details/gtdpssyxsy.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gtvxvjbfpu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yvedp.cn/Article/details/gtgyyvoknw.html

[U27] Py：异步 HTTP
来源：http://dali.zhoulong.xyz/Article/details/gtopgpwqhq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aibaodan.cn/Article/details/gtdbogvbze.html

[U28] Py：类型别名
来源：http://dali.zhongyouzk.top/Article/details/gtrxloabov.html

UserId = int
来源：http://dali.jqgufenzy.top/Article/details/gtqoapxqnl.html

[U29] Py：属性校验
来源：http://dali.shuidangran.top/Article/details/gtcrrjpvca.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gtstrdkxiq.html

[U30] Py：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlupmgkpg.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gtvlhwobmp.html

[U31] Py：单测
来源：http://dali.hnxiangtu.top/Article/details/gtqfzaamkl.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gtcxazuqlr.html

[U32] Py：代码格式化
来源：http://dali.ybcxt.top/Article/details/gtlitlvagi.html

ruff format . && ruff check --fix .
来源：http://dali.jqgufenzy.top/Article/details/gtquxeggrk.html

[U33] Py：打包发布
来源：http://dali.daxiang520.top/Article/details/gtryhdmzfy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gtymwokysx.html

[U34] Py：判断编码
来源：http://dali.daxiang520.top/Article/details/gtxkqldvbm.html

chardet.detect(raw)
来源：http://dali.sweek.top/Article/details/gtghsnkssz.html

[U35] Py：发送邮件
来源：http://dali.aibaodan.cn/Article/details/gtslreaiig.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hfpthk.cn/Article/details/gtxerzdzaf.html

[U36] Py：定时任务
来源：http://dali.zhixingplan.top/Article/details/gtmjgbudcl.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigfzy.top/Article/details/gtpbhdwsai.html

[U37] Py：读写 Excel
来源：http://dali.ydzc1.top/Article/details/gtocnatqyn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuanzhike.top/Article/details/gtawdzhfux.html

[U38] Py：获取脚本所在目录
来源：http://dali.cqqwz.cn/Article/details/gttiwzjksg.html

Path(__file__).resolve().parent
来源：http://dali.wangdashe.top/Article/details/gtskvusssc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhongyouzk.top/Article/details/gtgtgzhmtm.html

sys.stdout.isatty()
来源：http://dali.yj202588.top/Article/details/gtxygmvzic.html

[U40] Py：打印到标准错误
来源：http://dali.bjfxy.top/Article/details/gtackieyfq.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtthjwlyez.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.c1oappe.top/Article/details/gtfhpkxwsk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shuidangran.top/Article/details/gtawswdwjh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fengsongda.top/Article/details/gtwcbujuaf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pycfn.com/Article/details/gtlzmepent.html

[U43] PHP：声明命名空间
来源：http://dali.zycfv.cn/Article/details/gtkengdonp.html

namespace App\Http;
来源：http://dali.yj202588.top/Article/details/gtbfvrwcsi.html

[U44] PHP：开启严格类型
来源：http://dali.nanxuanxn.top/Article/details/gtahhhjqlf.html

declare(strict_types=1);
来源：http://dali.gogol.net.cn/Article/details/gtscwosvjo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.snrcjt.cn/Article/details/gtvlkywkcz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtlcjrbsgh.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gtjiuumbwp.html

?string $name = null
来源：http://dali.aibaodan.cn/Article/details/gtkcduwehi.html

[U47] PHP：联合类型
来源：http://dali.jqgfzy.top/Article/details/gtjnamfvge.html

int|string $id
来源：http://dali.pengpengdd.cyou/Article/details/gtlghmbiwi.html

[U48] PHP：纯枚举
来源：http://dali.chenzaomai.com/Article/details/gtxweyhhbn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwyqmezym.html

[U49] PHP：只读属性
来源：http://dali.jqgufenzy.top/Article/details/gtmhtxzkhn.html

public readonly string $name
来源：http://dali.c1oappe.top/Article/details/gtqrsjebgs.html

[U50] PHP：构造器属性提升
来源：http://dali.cqqwz.cn/Article/details/gthwpkyftw.html

public function __construct(private int $id) {}
来源：http://dali.bjfxy.top/Article/details/gtlgrkjuso.html

[U51] PHP：数组解构
来源：http://dali.dianchejie.cn/Article/details/gtltipibvk.html

[$a, $b] = $arr;
来源：http://dali.xuanzx.com/Article/details/gtkjvpxuvy.html

[U52] PHP：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gteryreyye.html

$double = fn($x) => $x * 2;
来源：http://dali.tianlin.xyz/Article/details/gtxjszhlaf.html

[U53] PHP：空合并运算符
来源：http://dali.birdmap.top/Article/details/gtydkyfiyc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhnnzqjp.html

[U54] PHP：空安全调用
来源：http://dali.yueranfly.top/Article/details/gtfagjwmtk.html

$obj?->method()
来源：http://dali.guowangkeji.top/Article/details/gtizcbuhpb.html


<!-- 参考信息 -->