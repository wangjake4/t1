代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtmxtexprp.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtjyuwxcba.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gteintnfyf.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gthhxvthuq.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gtgtcmsznk.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gtzlohlpyp.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoksytrg.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gtbkftemeg.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtmzdfscko.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gtvenkoghr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gttqczmuzx.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gtngsovwxq.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gthqvxohox.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtaslbfyjm.html

#endif
来源：http://dali.sweek.top/Article/details/gtfiqkzeru.html

[S31] C++：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtgqwgqbyg.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gtttehtozs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gttdeoazdo.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtqeocansr.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gtedvfupoo.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gtzdawxroj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtafowquxg.html

[S34] C++：遍历 vector
来源：http://dali.meibo888.top/Article/details/gtnkzoacya.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtplbybmsr.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gtjwuxrfbu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtloybvtjz.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gthfshvafi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtpytpijli.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gtrxdewmto.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gtsrejhhtm.html

[S38] C++：排序
来源：http://dali.tian-w.cn/Article/details/gtxcsycxds.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtanhwmdbv.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gtsvbtrmqj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gttediripn.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtmphohisn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtqplrayqa.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gtwkrvdorc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtucvdqerd.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gtjmpzprjw.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtcwwmqzsz.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtugcxyegt.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj202588.top/Article/details/gtbvlcqbat.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gtvbizyqli.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtlzansppp.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gtryqfbqox.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gtyjhrhwav.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gtaobywfpu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gtccjyrqiu.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gtnsoekpdf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtdirvjsvs.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtrzbjhlqu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gtbupakgli.html

while (std::getline(in, line)) { }
来源：http://dali.yonumen.top/Article/details/gtdsxrrxsh.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtxakdrolf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gtfqfhrges.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gtzpzifpyg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtfipahbth.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gtsadspntx.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtplfgamcr.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gthdmidvdn.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtourctpqi.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gttusweqns.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtuofaflqq.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gtvohnngmc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.quarkkingdee.top/Article/details/gtdmlpvdwu.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtpozqjowe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gtomaumrpb.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtqmrzznhd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtohrrjlif.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gtgehreoda.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtkpoqilaf.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gtbbmatdnx.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gtxcneoxsk.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gtvqweygun.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gtcvztvciw.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gtdqkjizxf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gtjwzrvukg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfmdkeshg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtyrmzskpl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrdkxavro.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gtbkrdgemh.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gtlawnpitf.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gthymtnrdf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gtdvbmgetp.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gtbewdkvyd.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtrwdrhqmp.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtcwioxeei.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gtsywbgzpw.html

[T05] Kotlin：when 表达式
来源：http://dali.ehwqpu.com/Article/details/gteyqynqvw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtwoowplvb.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtueclituy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gtgsitffkl.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtfisxqpdo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpdwzzdh.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtxhfezfpf.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtbmxdsncs.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gttxnmhpjb.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gtmodifteq.html

[T10] Kotlin：默认参数
来源：http://dali.mhx1999.top/Article/details/gtrodqocaw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtbcoalvne.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gtxxwrdzlx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gtddpotuyq.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gtlaaozpth.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtqevereib.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gtwxjyreby.html

val m = mapOf("a" to 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqmugpbl.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gtqieyoefg.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gtrfijdswg.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gtyphscrux.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtjtmrmqgo.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gtveehnvuf.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtgmmaqrjg.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gtkwlxiwod.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gteeoifzug.html

[T18] Swift：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxknwowlu.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gteuyevehm.html

[T19] Swift：可选绑定
来源：http://dali.guannengcc.top/Article/details/gtkulrjwcd.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gtfwjspzgz.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gtimrpilfn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangdashe.top/Article/details/gtpxohtasf.html

[T21] Swift：遍历
来源：http://dali.sysykeji.top/Article/details/gtubezxpqe.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gtkmrhruih.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gtvtxetxps.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gtvnvhvjju.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gtbjoiehcl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtupwplfpx.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gtbkevtvez.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gtxlpdxfor.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gttehmzsla.html

struct P { var x: Int }
来源：http://dali.jlsjyb.cn/Article/details/gtdjvbxqls.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtokggjzig.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtvvecgqck.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtoliisqbn.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gtvwgwxfmk.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gtwsznsfig.html

enum Color { case red, green }
来源：http://dali.gotoacloud.top/Article/details/gtlvhdmsgn.html

[T29] Swift：guard 提前返回
来源：http://dali.sxryk.cn/Article/details/gtxmmhxozp.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gtfgjurrfp.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gtcwhetsqs.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gtsgfzbnnc.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gtusbbwzca.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtdjmabodq.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gtwsvnfzkb.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gtunkzlpre.html

[T33] Lua：表（数组）
来源：http://dali.birdmap.top/Article/details/gtycckaupj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gtnxnrlgqw.html

[T34] Lua：遍历表
来源：http://dali.daria6918.cn/Article/details/gthlgumrhq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gtesjvagdp.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gtkibvnvmw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtjpuykogt.html

[T36] Lua：函数
来源：http://dali.yuxming.cn/Article/details/gtvdtgqsek.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtdanuvwvq.html

[T37] Lua：字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtgzfmzbht.html

"a" .. "b"
来源：http://dali.feifeiyinyue.top/Article/details/gtyxixfzqu.html

[T38] Lua：条件
来源：http://dali.yuxming.cn/Article/details/gtnqppzpyw.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gtfpdxuoct.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtqvvkwlmz.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gtunnsjzke.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gtdsfieccg.html

setmetatable({}, { __index = base })
来源：http://dali.hywenlv.cn/Article/details/gtuokxdshc.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gtreqlqhwn.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gtobgzajeu.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gttutpcwnl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtcbdjzetd.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtbawkhvsn.html

"值: $a"
来源：http://dali.zhixingplan.top/Article/details/gtlxxhcjeu.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gtrmpjjqac.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtwukmxans.html

[T45] Perl：数组遍历
来源：http://dali.yuanzhike.top/Article/details/gtuhjmuvpy.html

for my $x (@arr) { print $x; }
来源：http://dali.hammf.cn/Article/details/gtzwtxorke.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gtzgjizvgh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigfzy.top/Article/details/gtrzpbvyym.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtvtkevlss.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gtwyeogccj.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gtwjwyeoor.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gtbstugowo.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gtnoaszwtw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtzzcmsqum.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtowzqvmqq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hammf.cn/Article/details/gthhiefomr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gtpgyhzhok.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gtyslqyutc.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gteragbwfb.html

[T52] Scala：变量
来源：http://dali.zhongyouzk.top/Article/details/gtcnwqvlgb.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gtwnzsekrd.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gtrbfwuyii.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtdbxmfxfw.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtbedvtrwz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aibaodan.cn/Article/details/gtqgerzuwx.html

[T55] Scala：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtxwdmgimc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtbpxqkvih.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gtnlwawnec.html

case class User(name: String, age: Int)
来源：http://dali.birdmap.top/Article/details/gtngqpwzeh.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtlmrcdulm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtmwyksxbm.html

[T58] Scala：函数定义
来源：http://dali.guannengcc.top/Article/details/gtfzucehlg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gtizpgtblc.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gtzzkocoxk.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrodxndh.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtobawxnrx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtnflsoekq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtexvvzjne.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hongshengwenyu.top/Article/details/gttsnigziu.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdotkospu.html

[U01] Py：创建虚拟环境
来源：http://dali.jyoumei.cn/Article/details/gttsrxrdml.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqcpxwup.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gtpyxgljas.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhoulong.xyz/Article/details/gtvnoxkctu.html

[U03] Py：加载 .env 配置
来源：http://dali.hysaishi.cn/Article/details/gtbiduxjam.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gtssfuxnjo.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gtfvcgxrww.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sufxvd.cn/Article/details/gtxnqvwzwy.html

[U05] Py：列表去重且保序
来源：http://dali.chenjidiqi.icu/Article/details/gtlvxwzecm.html

list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtwykrrfkt.html

[U06] Py：合并两个字典
来源：http://dali.0kj1m.cn/Article/details/gtwmumedbf.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gtupyhbkpy.html

[U07] Py：反转字典键值
来源：http://dali.ehwqpu.com/Article/details/gtzeswzdzm.html

{v: k for k, v in d.items()}
来源：http://dali.cdnleiting.top/Article/details/gtsgajpmyf.html

[U08] Py：展平二维列表
来源：http://dali.haohaochexian.top/Article/details/gtzjlfuuvp.html

[y for x in nested for y in x]
来源：http://dali.zhongyouzk.top/Article/details/gtwqhefzyw.html

[U09] Py：字典取最大值的键
来源：http://dali.nwbrower.top/Article/details/gtojtefbax.html

max(d, key=d.get)
来源：http://dali.guannengcc.top/Article/details/gtebvcjqxs.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gtlwgixwgj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gtuzjpeumz.html

[U11] Py：生成器表达式
来源：http://dali.zhoulong.xyz/Article/details/gtwjdzulpe.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtynjsmtil.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ybcxt.top/Article/details/gtfhiadkvt.html

Counter(arr).most_common(3)
来源：http://dali.cheryme.top/Article/details/gtpahbgzrq.html

[U13] Py：固定长度队列
来源：http://dali.hammf.cn/Article/details/gthhsyhmzg.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gtlfkiykia.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdrbakzk.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gtxribiihg.html

[U15] Py：高精度计时
来源：http://dali.yongpay.top/Article/details/gtudugbloc.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gtrrlsjsvp.html

[U16] Py：命令行参数解析
来源：http://dali.nanxinkj.top/Article/details/gtmibgztqn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yonumen.top/Article/details/gtwxspqtbh.html

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gtivsqqnwa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnqzz.top/Article/details/gtrtzqpjdx.html

[U18] Py：预编译正则
来源：http://dali.dashuyun.cn/Article/details/gtwqzrmgmn.html

pat = re.compile(r"\d+")
来源：http://dali.xuanzx.com/Article/details/gtdghqnswb.html

[U19] Py：正则替换带回调
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnsvfbmj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuccomxye.html

[U20] Py：缓存函数结果
来源：http://dali.feifeiyinyue.top/Article/details/gtydkebybm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cucudq.cn/Article/details/gtxdeejkek.html

[U21] Py：自定义上下文管理器
来源：http://dali.c1oappe.top/Article/details/gtstimqqeq.html

@contextlib.contextmanager
来源：http://dali.andypj.xyz/Article/details/gtsgvinhrm.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gtqkyhorjz.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gtsajontvo.html

[U23] Py：分块读取大文件
来源：http://dali.zhoulong.xyz/Article/details/gtdibuehqk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gticailozv.html

[U24] Py：路径操作
来源：http://dali.iojbl.cn/Article/details/gtxeoosylm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtdjlgtjts.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gtnxisapbm.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmanzjfyj.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gtscyrwyuf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzwtbsqc.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigfzy.top/Article/details/gtygjpoosm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrewlqvx.html

[U28] Py：类型别名
来源：http://dali.shzxlz.cn/Article/details/gtsbepkkui.html

UserId = int
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjzjjnol.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gtgsttvqkx.html

@property 与 @x.setter 配合
来源：http://dali.zdqjudy.top/Article/details/gtuxtrcnaf.html

[U30] Py：数据类
来源：http://dali.ybcxt.top/Article/details/gtfijzxgbq.html

@dataclass(slots=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmgewayc.html

[U31] Py：单测
来源：http://dali.hongshengwenyu.top/Article/details/gtpcdgscaf.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtwacucgyx.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtavnbcfcy.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gtvyktgbkc.html

[U33] Py：打包发布
来源：http://dali.yonumen.top/Article/details/gtwpqjdpio.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gtjvfwdblt.html

[U34] Py：判断编码
来源：http://dali.sweek.top/Article/details/gtiypawjln.html

chardet.detect(raw)
来源：http://dali.quarkkingdee.top/Article/details/gtkzgqosij.html

[U35] Py：发送邮件
来源：http://dali.yonumen.top/Article/details/gtntdyunnh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.c1oappe.top/Article/details/gtkkvhxucw.html

[U36] Py：定时任务
来源：http://dali.c1oappe.top/Article/details/gtxjkljxtm.html

schedule.every(10).minutes.do(job)
来源：http://dali.yangfankeji.com/Article/details/gtuojhqoxz.html

[U37] Py：读写 Excel
来源：http://dali.yvedp.cn/Article/details/gtalgfeszz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hongshengwenyu.top/Article/details/gtbadnxoxw.html

[U38] Py：获取脚本所在目录
来源：http://dali.ivvv.top/Article/details/gtwcosqloa.html

Path(__file__).resolve().parent
来源：http://dali.jqgfzy.top/Article/details/gtesndamsv.html

[U39] Py：判断是否在交互环境
来源：http://dali.yangfankeji.com/Article/details/gtdgmzhxzq.html

sys.stdout.isatty()
来源：http://dali.aibaodan.cn/Article/details/gtaseuwhmz.html

[U40] Py：打印到标准错误
来源：http://dali.gaohongyu789.top/Article/details/gtiphrdbgv.html

print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtfqizhkzf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.feifeiyinyue.top/Article/details/gtwbccpprt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.snrcjt.cn/Article/details/gtpyoivvri.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cashguo.top/Article/details/gtheckrvps.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.c1oappe.top/Article/details/gtfyeztbny.html

[U43] PHP：声明命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtutooqfoe.html

namespace App\Http;
来源：http://dali.hnqzz.top/Article/details/gtsmkcpcli.html

[U44] PHP：开启严格类型
来源：http://dali.zhengqikj.top/Article/details/gtmyxyuwac.html

declare(strict_types=1);
来源：http://dali.andypj.xyz/Article/details/gtcrntnaid.html

[U45] PHP：类型声明与返回类型
来源：http://dali.redwolf501.top/Article/details/gtsgurbozs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtnediwnbo.html

[U46] PHP：可空类型
来源：http://dali.cucudq.cn/Article/details/gttjmochkz.html

?string $name = null
来源：http://dali.svipenyu.cn/Article/details/gtuqwfnzvf.html

[U47] PHP：联合类型
来源：http://dali.yonumen.top/Article/details/gtgqrkgjbj.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gtrtrsoktk.html

[U48] PHP：纯枚举
来源：http://dali.9152youxi.cn/Article/details/gtjpqkdyfg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yonumen.top/Article/details/gtumckknih.html


<!-- 参考信息 -->