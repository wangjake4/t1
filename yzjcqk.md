代发 wailian999

#include <iostream>
来源：http://dali.zhoulong.xyz/Article/details/gtrkthjhbw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.smart0.xyz/Article/details/gtmnrnfudz.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtaejoewxe.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtiwgqjeby.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gtmcxmocmp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gtazxzomvr.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtnebzmeax.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyxeulbnm.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gtxmrqpskb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtojesgfth.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gtyzsxoftf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtdwgtbzmc.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gtvhnpfmbs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtlgltatxg.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtbhdfolxz.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqkrsigj.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtzqmxntft.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gtcwmkidut.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaqojtxn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeujmynk.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtndvvenvs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtzcalfcuh.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtktodapkg.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenlongwang.top/Article/details/gtawavyute.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtgbbfjwjg.html

auto p = std::make_unique<int>(5);
来源：http://dali.daxiang520.top/Article/details/gtpskkkicl.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtrshdjadg.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gtiysjiyab.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtvpcajipo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.9152youxi.cn/Article/details/gtjuawsezy.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gtkctgqsep.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtmgsyhezr.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gtjbeoxusx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtxwnptwtf.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtfdzmwoji.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gtgyfjqpaw.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtaekjwrsr.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gtmnyntklh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gtafhtunsc.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gtajtmmmqo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzqtuzie.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtdnudelni.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gtasiluwzc.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtxqlihzql.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gteqbdujic.html

[S53] C++：移动语义
来源：http://dali.chenjidiqi.icu/Article/details/gtfpmubefa.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gtsylndjql.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtnttiyuoo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtrylqtmnh.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtqugqonhl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtnepbulxc.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtsyolmpme.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtcpgurnkd.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gtvpfwjoqn.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnzzaxna.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtfdqmahij.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gteviyzmuw.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtiobazggs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtqsthsibk.html

[S60] C++：遍历并删除元素
来源：http://dali.bjfxy.top/Article/details/gtcjfeyrgs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtfmieanxt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtznesgkln.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtpawaawqa.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfjuimdqi.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtqxdlqbwj.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtwlekgrty.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtmkjxmwoz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.smart0.xyz/Article/details/gtdbavfbbl.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtmargxzqn.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtccxjdfin.html

[T04] Kotlin：空安全
来源：http://dali.xuetiantiany.cn/Article/details/gtwxvfwkon.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvhmihkc.html

[T05] Kotlin：when 表达式
来源：http://dali.xziqi.cn/Article/details/gtewojfjyy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gtpnloemkw.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtokrtusnq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtchjsshvs.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gtiqikthsq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtbfjzvyoy.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gtxqrekqan.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtyecgnf.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gtebcyeyht.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gtqqejnzzh.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gtbwygects.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtnzkdkpwy.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gthpsjmcxz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gtqewtayvd.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzklpfsv.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtjgbospll.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gtdzuxmmkp.html

val m = mapOf("a" to 1)
来源：http://dali.vqdsnc.cn/Article/details/gtfgdudfzb.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gtbaqgwdmx.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtwcudzuat.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gtqbdkulny.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gtlnmuplwh.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gtkkxqmwpz.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtapfswjko.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gtgwiwqyek.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gtamrangmk.html

[T18] Swift：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtbipjtafn.html

"值: \(b)"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptwjdetu.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphkkawgh.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gtdbtejugr.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gtoecgjdsa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gthmqxsmxc.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gtdbemwutr.html

for x in a { print(x) }
来源：http://dali.daria6918.cn/Article/details/gtnrlmdwqj.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gtiziqnoib.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gtbbxjrgpf.html

[T23] Swift：函数
来源：http://dali.chenlongwang.top/Article/details/gtawvkxfgk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.meibo888.top/Article/details/gtuowddrsv.html

[T24] Swift：闭包
来源：http://dali.dashuyun.cn/Article/details/gtnkwbxxrg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtdcxfzvwl.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtjjzfcdlf.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gtlqnjrtfk.html

[T26] Swift：类与重写
来源：http://dali.redwolf501.top/Article/details/gtgogszkxn.html

class A: Base { override func f() {} }
来源：http://dali.shuidangran.top/Article/details/gtovksqicb.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gtfzsybxop.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauxgyyqm.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gthekhgrfk.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gtnmtjgejq.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gtvocwemol.html

guard let x = opt else { return }
来源：http://dali.chenjidiqi.icu/Article/details/gtxidcpzjd.html

[T30] Swift：协议
来源：http://dali.tanke756.top/Article/details/gtsfsgvpwk.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gtykqzgtmm.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gtqhcjsmkf.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtqowiceuw.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtdvxkafyz.html

local a = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtnizbsygl.html

[T33] Lua：表（数组）
来源：http://dali.sxryk.cn/Article/details/gtuqwcomex.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gtmylydfev.html

[T34] Lua：遍历表
来源：http://dali.fzhhl.top/Article/details/gtwwvxgkap.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gtmthritxg.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtwcbmvwqo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtxbprvdes.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gtxarbsddj.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gtpzfbxbto.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtmyrzgchu.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtcgkhmmtn.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gtpaybyhfy.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gtjkyhetmt.html

[T39] Lua：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtiqqrrlso.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gtwlheryoq.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtoqklonwj.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtkssumntr.html

[T41] Perl：Hello World
来源：http://dali.sysykeji.top/Article/details/gtkfvgmndg.html

print "Hello\n";
来源：http://dali.havefunace.top/Article/details/gtwwalwbsq.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gtuumnyweo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gtnkocjsdv.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gtncofdlka.html

"值: $a"
来源：http://dali.vqdsnc.cn/Article/details/gthkytczxc.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtlpbvvheo.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjrjwlav.html

[T45] Perl：数组遍历
来源：http://dali.yuxming.cn/Article/details/gtasykdjcw.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gtpukkwrpj.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gtyyqiiqeq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gtwdbgmrpp.html

[T47] Perl：正则捕获
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdgiasoz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfbrcxgik.html

[T48] Perl：正则替换
来源：http://dali.redwolf501.top/Article/details/gtocugfspx.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gtyrjmmgik.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gtstnnatcy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gthdglkrql.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtfhizteeb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gtsiuidnbh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsjcqjahs.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjndksgi.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtkzswukbi.html

[T52] Scala：变量
来源：http://dali.xuanzx.com/Article/details/gtnwizspog.html

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtjupveeyi.html

[T53] Scala：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtppfnlsqg.html

s"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtygcunjio.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtgvohjrco.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuspyxbg.html

[T55] Scala：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtrrlijzla.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gtbcpquluq.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gtmalhdslt.html

case class User(name: String, age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtmpuozkpo.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gtbskpzqwp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtglxsqqmo.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstrpnkze.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gtcvojggjs.html

[T59] Scala：循环
来源：http://dali.quarkkingdee.top/Article/details/gtwpgyuvbh.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtkkscbrcv.html

[T60] Scala：折叠
来源：http://dali.tianlin.xyz/Article/details/gtnsgvbrui.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gtpbgkibvc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxpwvycy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtrfptslaa.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfvoofhid.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gthpstsazk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gtkfwwclsg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gtogqtdqtd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cqqwz.cn/Article/details/gtjypjsvjf.html

[U03] Py：加载 .env 配置
来源：http://dali.hnxiangtu.top/Article/details/gtlkfqovkm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gogol.net.cn/Article/details/gtspqmhqxu.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gtwslbekau.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gtxpzjoxla.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gtylhlguyg.html

list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gttzdmgeqs.html

[U06] Py：合并两个字典
来源：http://dali.jqgufenzy.top/Article/details/gtqbnafqis.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gtsvwzccwy.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gtdevhaxmn.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gtpdvivzuw.html

[U08] Py：展平二维列表
来源：http://dali.jqgufenzy.top/Article/details/gtmtowjeoa.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrvekpnc.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gtcdtexuqi.html

max(d, key=d.get)
来源：http://dali.nwbrower.top/Article/details/gtsbgamrnr.html

[U10] Py：按值排序字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpyxovbo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxinkj.top/Article/details/gtlsftgaul.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gtfqhcqsbm.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gtmgffjsje.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jyoumei.cn/Article/details/gtralnzjwo.html

Counter(arr).most_common(3)
来源：http://dali.shzxlz.cn/Article/details/gtrclcyfjg.html

[U13] Py：固定长度队列
来源：http://dali.ydzc1.top/Article/details/gtenuvjbxh.html

deque(maxlen=10)
来源：http://dali.chenlongwang.top/Article/details/gtwfgftkyq.html

[U14] Py：分组收集到列表
来源：http://dali.jqgufenzy.top/Article/details/gtnjkbboeb.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gtcbnemife.html

[U15] Py：高精度计时
来源：http://dali.cheryme.top/Article/details/gtvmrkyoxs.html

t = time.perf_counter()
来源：http://dali.zdqjudy.top/Article/details/gtrzieivvw.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gteuawkrnt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gtkanswyum.html

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gtyjkewvyj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgwyroct.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtioxfrdpo.html

pat = re.compile(r"\d+")
来源：http://dali.aizwys.cn/Article/details/gtkhyrevtm.html

[U19] Py：正则替换带回调
来源：http://dali.hnqzz.top/Article/details/gtdtouhnyr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gtmwygsgcd.html

[U20] Py：缓存函数结果
来源：http://dali.svipenyu.cn/Article/details/gtjhbmesbj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cashguo.top/Article/details/gtybbckghv.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangshuangyany.cn/Article/details/gtgfgfzspc.html

@contextlib.contextmanager
来源：http://dali.jiagoushi.top/Article/details/gtiktfeupz.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gtpghcpaov.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gtenlxidnz.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigfzy.top/Article/details/gtczxjbzbz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtsoqholsl.html

[U24] Py：路径操作
来源：http://dali.gaohongyu789.top/Article/details/gtftovsufh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtivxitsvc.html

[U25] Py：CSV 按字典读
来源：http://dali.tianlin.xyz/Article/details/gtxhlrqoxs.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtsnitjosd.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtutspppxh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gtsufvlyxh.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gtxztinmkg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hfpthk.cn/Article/details/gtkzlqfjsz.html

[U28] Py：类型别名
来源：http://dali.dashuyun.cn/Article/details/gtumwezkkt.html

UserId = int
来源：http://dali.gogol.net.cn/Article/details/gtgnqlqime.html

[U29] Py：属性校验
来源：http://dali.hongshengwenyu.top/Article/details/gtqwhevqpz.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gtcodtikkp.html

[U30] Py：数据类
来源：http://dali.zycfv.cn/Article/details/gtdofmbzgp.html

@dataclass(slots=True)
来源：http://dali.gzhubu.top/Article/details/gtlkjsnvka.html

[U31] Py：单测
来源：http://dali.gogol.net.cn/Article/details/gtnmveoncx.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gtgleedkgj.html

[U32] Py：代码格式化
来源：http://dali.snrcjt.cn/Article/details/gtloarepic.html

ruff format . && ruff check --fix .
来源：http://dali.shangyingyoupin.top/Article/details/gtqfpkfqnd.html

[U33] Py：打包发布
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjevezajj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dashuyun.cn/Article/details/gtzlqhrnpd.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gtrmbrekiz.html

chardet.detect(raw)
来源：http://dali.ehwqpu.com/Article/details/gtysbptpii.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtoclgieuw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gtszuksayr.html

[U36] Py：定时任务
来源：http://dali.yangfankeji.com/Article/details/gtvdaevpti.html

schedule.every(10).minutes.do(job)
来源：http://dali.cqqwz.cn/Article/details/gtglywpanq.html

[U37] Py：读写 Excel
来源：http://dali.svipenyu.cn/Article/details/gttbaxklsx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ivvv.top/Article/details/gtrcsayodq.html

[U38] Py：获取脚本所在目录
来源：http://dali.c1oappe.top/Article/details/gtnykyadve.html

Path(__file__).resolve().parent
来源：http://dali.gogol.net.cn/Article/details/gtrwgktqlr.html

[U39] Py：判断是否在交互环境
来源：http://dali.tianlin.xyz/Article/details/gtvlicpgxs.html

sys.stdout.isatty()
来源：http://dali.jianghu66.top/Article/details/gtjwlujlac.html

[U40] Py：打印到标准错误
来源：http://dali.hnxiangtu.top/Article/details/gtaykvwvnl.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtdlyafard.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shangyingyoupin.top/Article/details/gtaikcpboy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gtmppsxduw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gtbevosyxo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fzhhl.top/Article/details/gtzxjyeual.html

[U43] PHP：声明命名空间
来源：http://dali.ydzc1.top/Article/details/gtuufjhvci.html

namespace App\Http;
来源：http://dali.daxiang520.top/Article/details/gtqmafxboj.html

[U44] PHP：开启严格类型
来源：http://dali.ivvv.top/Article/details/gtwbbburfz.html

declare(strict_types=1);
来源：http://dali.nanxuanxn.top/Article/details/gtitzjlnei.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shzxlz.cn/Article/details/gtkqlczkox.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtbdgxvlxx.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gthbibnokz.html

?string $name = null
来源：http://dali.pycfn.com/Article/details/gtwimxprag.html

[U47] PHP：联合类型
来源：http://dali.sxryk.cn/Article/details/gtihpddvwx.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gtecsgpzeq.html

[U48] PHP：纯枚举
来源：http://dali.yvedp.cn/Article/details/gtqdoxzpsw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.bjfxy.top/Article/details/gtzogejzhz.html

[U49] PHP：只读属性
来源：http://dali.xinyue.icu/Article/details/gtmzftmbob.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gtihwrisgf.html

[U50] PHP：构造器属性提升
来源：http://dali.feifeiyinyue.top/Article/details/gtoaewmgjv.html

public function __construct(private int $id) {}
来源：http://dali.nanxuanxn.top/Article/details/gtavvtcyzg.html

[U51] PHP：数组解构
来源：http://dali.jiagoushi.top/Article/details/gtefekflcg.html

[$a, $b] = $arr;
来源：http://dali.aibaodan.cn/Article/details/gthrcwbbbe.html

[U52] PHP：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gtsrabdlti.html

$double = fn($x) => $x * 2;
来源：http://dali.tanke756.top/Article/details/gtpyntcjqe.html

[U53] PHP：空合并运算符
来源：http://dali.zhoulong.xyz/Article/details/gtpdfsgcqz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zdqjudy.top/Article/details/gtxwiexmqn.html

[U54] PHP：空安全调用
来源：http://dali.tanke756.top/Article/details/gtgywleznz.html

$obj?->method()
来源：http://dali.ivvv.top/Article/details/gtdjytewyf.html

[U55] PHP：match 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwfqshkg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.fzhhl.top/Article/details/gtcootynan.html

[U56] PHP：命名参数
来源：http://dali.gotoacloud.top/Article/details/gtkzagjpox.html

f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtuxybiihd.html


<!-- 参考信息 -->