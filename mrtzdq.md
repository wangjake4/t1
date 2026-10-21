代发 wailian999

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtsnioaguw.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gtzkfcamkb.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtmuzmsg.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtpsiuvriu.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtbholgldt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gteckciopc.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gthckvtuca.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gtzxctikwt.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gteqgfiviv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtjkgxukon.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gtwciueawo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gtwxmumnwq.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gtmqlnrnim.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobhiakin.html

[S36] C++：unordered_map
来源：http://dali.xinyue.icu/Article/details/gtjuavljhr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtxclpvswt.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gtqsudlhcr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gtzrquqtdr.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtkvxoeezx.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gtzrtovokm.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gtmdngrtbf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigufen.top/Article/details/gtmxgnaahg.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtigmwgcff.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtgvloppuj.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gtqnszpjlf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gteetiqrkb.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gtlgqmzkwj.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtkuvnosop.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtxlmmqkvq.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtlemtqzso.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtpboccnip.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtczkhunbe.html

[S45] C++：lambda
来源：http://dali.ppjwa.cn/Article/details/gtwpvavlvs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gtjkbncorg.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtuoxmuglz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gthbjnvdbt.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gthowksjlq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gtnrzkxqzh.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtwtndrdri.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gtalxcwfij.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtotzmyvih.html

[S49] C++：写文件
来源：http://dali.jianghu66.top/Article/details/gtlwkgvtdy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gtpbsxzdew.html

[S50] C++：格式化数字
来源：http://dali.xuanzx.com/Article/details/gtqguizghv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtbanvnugq.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gtmvqpiqha.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gtiuonvyjm.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtoulpszlg.html

int size() const noexcept { return n_; }
来源：http://dali.zhongyouzk.top/Article/details/gtgetvacgl.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijewufpm.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gticxhvmxl.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangtech.top/Article/details/gthmqhxzoh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzujpiroe.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gtnkkbkulj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gtfmfrogbt.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtzkawehhj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtdsazzero.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gtgwwfvwtn.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gtbjdnithm.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gtoaorpqce.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gtmisplwht.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtiqprkjfl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gteiblbefq.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gtvjoosoas.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gttgxvjhan.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttzusmncw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtdbkxgior.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcojcgzy.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdsvwdgs.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtkksujxac.html

[T02] Kotlin：变量
来源：http://dali.sufxvd.cn/Article/details/gtzwhbkvzp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.c1oappe.top/Article/details/gtmmxnqsyo.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtelcakahd.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtdakfytid.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gticrekmqv.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtqybqprih.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtapwvwglg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gtznunivme.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdurqykpu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gtvvwkrpve.html

[T07] Kotlin：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtxbigxlrr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtbuklstum.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gtfcwydcxw.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtdvmuaqgt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtccwwvwym.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtumzznemi.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtpwqqpvbi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gtngkndmat.html

[T11] Kotlin：协程
来源：http://dali.andypj.xyz/Article/details/gtrfbudrzj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cucudq.cn/Article/details/gtjnfvgjil.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gttpvmkwlj.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gthqrvbshk.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwkdcboc.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gtyuxttrlc.html

[T14] Kotlin：循环
来源：http://dali.yuxming.cn/Article/details/gthailnyfm.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnfvhnjw.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gtmgtrrzcx.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gtazubiwzn.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtcldrjfdi.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtluprorqr.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gtllnqlzrw.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtegyyncxj.html

[T18] Swift：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtodudfzds.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gtsikwzpdc.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gtlvtgkpls.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gthnzjurrl.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtngmnhrhn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gtvjidiixs.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gtjkknhnef.html

for x in a { print(x) }
来源：http://dali.yonumen.top/Article/details/gttwdwdzwo.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gtkfhgsmap.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzvcaebr.html

[T23] Swift：函数
来源：http://dali.zhengqikj.top/Article/details/gtbsfxbtbo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gtojtneonl.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gtxtycjrrz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtqabgwtok.html

[T25] Swift：结构体
来源：http://dali.kuanghao11.cn/Article/details/gtvgrkmpda.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gtqrvlkbys.html

[T26] Swift：类与重写
来源：http://dali.jianghu66.top/Article/details/gtxzylryjv.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gtcjypfzjj.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gtbqocjuts.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtttdshisc.html

[T28] Swift：枚举
来源：http://dali.316326.xyz/Article/details/gtemfdyxoc.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gtolgxaipv.html

[T29] Swift：guard 提前返回
来源：http://dali.zycfv.cn/Article/details/gtuntlftce.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gtsfatkahl.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gtchzivsnb.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gtglkebitu.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtpraukomb.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtxtbqdypp.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtlteyisam.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gtsvdrwyit.html

[T33] Lua：表（数组）
来源：http://dali.yanxiufei.cn/Article/details/gtfwabhlyh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gtxvsalkxf.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gtlzzvwugi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gtvtenkiko.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gtbkqwjkqc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gtgebhkoym.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gtbbzjraip.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtlmhyzpji.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtgywlubee.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gtxfflqkvg.html

[T38] Lua：条件
来源：http://dali.iojbl.cn/Article/details/gtmfporjnw.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gtgmmigxft.html

[T39] Lua：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwljtxot.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gtmbexjeju.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gtcjzrzlvo.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gtyaaqbmuh.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gtwzqczggb.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gtqshkctxl.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gthktuenqa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fengsongda.top/Article/details/gtvvxkbhou.html

[T43] Perl：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtegwfcjzy.html

"值: $a"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnorhlwg.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gtjpdxrhqx.html

if ($a > 0) { print "正"; }
来源：http://dali.nwbrower.top/Article/details/gtuqvxrgcc.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzgktcbp.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gthyxwfvpm.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gtcfwhzccu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gtyywrdzdw.html

[T47] Perl：正则捕获
来源：http://dali.cdnleiting.top/Article/details/gtaitlmytm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gtogxvsnxd.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gtmobzaius.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtiphtmfvg.html

[T49] Perl：函数
来源：http://dali.hywenlv.cn/Article/details/gtrnncytuy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtzysvzdrc.html

[T50] Perl：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtzkophulj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yonumen.top/Article/details/gtbzonyhnx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pycfn.com/Article/details/gtyjzjnzsg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtaqqtpejg.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gthvxhwznr.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gtrmxbjgbl.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtydpznqju.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gtvnyjlvfo.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtwbhdnwfe.html

[T54] Scala：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtjtukowwa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.vqdsnc.cn/Article/details/gttxoakhkm.html

[T55] Scala：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gtqqgubpmu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtqrcrtszz.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gthpnvzryv.html

case class User(name: String, age: Int)
来源：http://dali.cashguo.top/Article/details/gtymqndrrd.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtzdifuzhf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gtobwrwaeh.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gtdmpaqpyp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gtrpzjjpyr.html

[T59] Scala：循环
来源：http://dali.hongshengwenyu.top/Article/details/gtuielgyur.html

for (i <- 1 to 10) println(i)
来源：http://dali.yongpay.top/Article/details/gtilmxhilp.html

[T60] Scala：折叠
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaabcjvbz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfzjqqwl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtilprzinl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gtpntgdbti.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjlbokzbn.html

[U01] Py：创建虚拟环境
来源：http://dali.smart0.xyz/Article/details/gtxlgrmvka.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gtlbiwwskz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtudgrkzyh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tianlin.xyz/Article/details/gtomooqdxd.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gtphfsgapv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gzhubu.top/Article/details/gtlbipumvc.html

[U04] Py：变量调试打印
来源：http://dali.wangdashe.top/Article/details/gtxusirnki.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gtuispeklf.html

[U05] Py：列表去重且保序
来源：http://dali.gotoacloud.top/Article/details/gtsmrojndt.html

list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gtifdqjizh.html

[U06] Py：合并两个字典
来源：http://dali.tian-w.cn/Article/details/gtlxhadplg.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gtxptedggj.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtciibxuyb.html

{v: k for k, v in d.items()}
来源：http://dali.smart0.xyz/Article/details/gtrswrdemy.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gtnecpntip.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gtqbenqfmn.html

[U09] Py：字典取最大值的键
来源：http://dali.svipenyu.cn/Article/details/gtqnylonjg.html

max(d, key=d.get)
来源：http://dali.hysaishi.cn/Article/details/gtbzcqijxf.html

[U10] Py：按值排序字典
来源：http://dali.ehwqpu.com/Article/details/gthssnrkwq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gtsiwrrhfb.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gthgobnlly.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gtrcloftgf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gtlwpawysr.html

Counter(arr).most_common(3)
来源：http://dali.gzhubu.top/Article/details/gtzuciyzeh.html

[U13] Py：固定长度队列
来源：http://dali.yuanzhike.top/Article/details/gtiwaubouf.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gtnzfnujgg.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gtbxptxkxp.html

defaultdict(list)
来源：http://dali.fzhhl.top/Article/details/gtabtlrtya.html

[U15] Py：高精度计时
来源：http://dali.birdmap.top/Article/details/gttmmbvitg.html

t = time.perf_counter()
来源：http://dali.ivvv.top/Article/details/gtlwbgygje.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258.top/Article/details/gtzxwjjaby.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gtsjlxovwo.html

[U17] Py：初始化日志
来源：http://dali.wangdashe.top/Article/details/gtvcsvmrju.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gtidffycaw.html

[U18] Py：预编译正则
来源：http://dali.gzhubu.top/Article/details/gttjodtzzf.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gtjgclgvjh.html

[U19] Py：正则替换带回调
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgvvblwm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hammf.cn/Article/details/gtcpavbhtv.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gtapgytpyy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gaohongyu789.top/Article/details/gtccldgops.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhiwuduotai.top/Article/details/gtljetfzjg.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gtwgpnijlm.html

[U22] Py：矩阵转置
来源：http://dali.tian-w.cn/Article/details/gtqshyowxq.html

list(zip(*m))
来源：http://dali.dianchejie.cn/Article/details/gttebfrnpi.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gtrswzukie.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gtebhofefd.html

[U24] Py：路径操作
来源：http://dali.zycfv.cn/Article/details/gtyqxtwufz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtjcbtvzza.html

[U25] Py：CSV 按字典读
来源：http://dali.fzhhl.top/Article/details/gtncfiprpu.html

csv.DictReader(f)
来源：http://dali.sweek.top/Article/details/gtffinfzdj.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gtfwqqonnz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgfzy.top/Article/details/gthasdfdbg.html

[U27] Py：异步 HTTP
来源：http://dali.yanxiufei.cn/Article/details/gtdvjoilxf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hammf.cn/Article/details/gttuegsuii.html

[U28] Py：类型别名
来源：http://dali.hywenlv.cn/Article/details/gtrmyrzbqg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gtaopqxwqt.html

[U29] Py：属性校验
来源：http://dali.aizwys.cn/Article/details/gtmnzynwod.html

@property 与 @x.setter 配合
来源：http://dali.yj20258.top/Article/details/gticaufhmv.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gtpoykoaim.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gtedfqszsu.html

[U31] Py：单测
来源：http://dali.xylfe.cn/Article/details/gtbyjqzjfm.html

python -m pytest -q
来源：http://dali.yvedp.cn/Article/details/gtavgyansx.html

[U32] Py：代码格式化
来源：http://dali.daxiang520.top/Article/details/gtylyehnop.html

ruff format . && ruff check --fix .
来源：http://dali.hnqzz.top/Article/details/gtlsticlro.html

[U33] Py：打包发布
来源：http://dali.zdqjudy.top/Article/details/gtcplmattk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.iojbl.cn/Article/details/gtnxlztdhk.html

[U34] Py：判断编码
来源：http://dali.sufxvd.cn/Article/details/gtreuttgmh.html

chardet.detect(raw)
来源：http://dali.dianchejie.cn/Article/details/gtppzokodx.html

[U35] Py：发送邮件
来源：http://dali.xuanzx.com/Article/details/gtsxitoibw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guannengcc.top/Article/details/gtdocmztav.html

[U36] Py：定时任务
来源：http://dali.ybcxt.top/Article/details/gthjjognjy.html

schedule.every(10).minutes.do(job)
来源：http://dali.xylfe.cn/Article/details/gtablzeifm.html

[U37] Py：读写 Excel
来源：http://dali.hysaishi.cn/Article/details/gtytxpckwo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nanxinkj.top/Article/details/gtzgmamalr.html

[U38] Py：获取脚本所在目录
来源：http://dali.ivvv.top/Article/details/gtesxtwdlw.html

Path(__file__).resolve().parent
来源：http://dali.gaohongyu789.top/Article/details/gttdoiurrw.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gtxljprnok.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gtznkcovrd.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gtzipjuxur.html

print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtqbudcbqo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvocatve.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ivvv.top/Article/details/gtdkepobua.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenlongwang.top/Article/details/gtjqlflenp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gtljuwpzbi.html

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gtoxbabsvm.html

namespace App\Http;
来源：http://dali.yj20258888.top/Article/details/gtmmfjtuaw.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gtydprmkeq.html

declare(strict_types=1);
来源：http://dali.sxryk.cn/Article/details/gtgndfotnp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigufen.top/Article/details/gtjsrhrkcj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtffgiomcr.html

[U46] PHP：可空类型
来源：http://dali.redwolf501.top/Article/details/gtoqnalfua.html

?string $name = null
来源：http://dali.shuidangran.top/Article/details/gtwkunyykv.html

[U47] PHP：联合类型
来源：http://dali.jqgfzy.top/Article/details/gtnqlfvdft.html

int|string $id
来源：http://dali.jinqigufen.top/Article/details/gtvqhiatjh.html

[U48] PHP：纯枚举
来源：http://dali.yuxming.cn/Article/details/gttcjfzigm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guowangkeji.top/Article/details/gtmxcksfem.html

[U49] PHP：只读属性
来源：http://dali.sysykeji.top/Article/details/gtyymfyurc.html

public readonly string $name
来源：http://dali.nanxinkj.top/Article/details/gtjrxphhrw.html

[U50] PHP：构造器属性提升
来源：http://dali.hfpthk.cn/Article/details/gtcxlrkhdr.html

public function __construct(private int $id) {}
来源：http://dali.aibaodan.cn/Article/details/gtcrdibkwm.html

[U51] PHP：数组解构
来源：http://dali.nwbrower.top/Article/details/gtwqxnhsps.html

[$a, $b] = $arr;
来源：http://dali.yj202588.top/Article/details/gtcbopnjrn.html

[U52] PHP：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjnsbssw.html

$double = fn($x) => $x * 2;
来源：http://dali.nwbrower.top/Article/details/gtlzkxbnez.html

[U53] PHP：空合并运算符
来源：http://dali.kuanghao11.cn/Article/details/gtkwxbbfms.html

$v = $a ?? $b ?? "default";
来源：http://dali.fengsongda.top/Article/details/gthkciivtu.html

[U54] PHP：空安全调用
来源：http://dali.wangdashe.top/Article/details/gtaqqvppow.html

$obj?->method()
来源：http://dali.jianghu66.top/Article/details/gtcuxrssse.html


<!-- 参考信息 -->