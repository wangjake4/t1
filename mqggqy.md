代发 wailian999

#ifndef X_H
来源：http://dali.zdqjudy.top/Article/details/gtbyezzdin.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gtlpptjbjg.html

#endif
来源：http://dali.chenjidiqi.icu/Article/details/gtzptxpmwa.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtveuutvgh.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtcgtpucww.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gtxjempeue.html

[S32] C++：字符串
来源：http://dali.yuxming.cn/Article/details/gtnzgngypm.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gtdzdwkebz.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtyibnfjzb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtavshummh.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gtxlcmptln.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtavdzoebu.html

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gtesxvqqzu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtcdzxptpb.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gtnoidonmk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtxjoyvoxg.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtlrjoccyf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtpntsfedt.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gtyeamvemy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtaluvjjuc.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtvadgcbxy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtehthifxq.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgvljfaa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtavjopxyd.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gtolkcxpll.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtgviesijj.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gtwnxcktlp.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfmznmbj.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtjfegozmc.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtaogbqtqr.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtxmydijoj.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoltpycqi.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtgvenrzvl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangshuangyany.cn/Article/details/gttdhlihtn.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gtresewqxd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcmlufdgm.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gthukmhkfb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnxiangtu.top/Article/details/gtvbwzolmj.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtanmquyin.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gtiiigvxue.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtznwtynde.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtgsssqqrh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gtwzkayxed.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gtfpypgspd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtwqvillgt.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtjencvern.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtfwplrwyj.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gtxdlhnkwh.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtpntncirc.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtilgzoiue.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtlsyasvfp.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gtsvnhjgxz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gtgwmomjni.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtunpezwzc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtiuknqkzh.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gttxoeyhox.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtucsbzmch.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gthecskpwo.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gtbmbkroke.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gtvogklgjt.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gtxuokplpw.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gtecdkdtou.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gtyrbhepvc.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gtkuczpxog.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtxlufuwqr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlibcznzb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gthcuhskpk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtlodjejch.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gtqkbwgtnh.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtcaaadein.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gtzlbcoxii.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gtylrvskjm.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtqipmuewd.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfisjrcly.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjtimzdt.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtrbhszwhh.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gthawrwdja.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yonumen.top/Article/details/gtxakicdvy.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtjaarzmeh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcxogmnp.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtxmfzqrfs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtpyaodbyv.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gtzcuzxgtg.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gtudxumtob.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gtlsautsio.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gtrrgcqsff.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtwukatltm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yvedp.cn/Article/details/gtkrrtbyfo.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtnraidnrp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gttodviwtj.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtdrhyatft.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtvvdafaaa.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gtghcuutqy.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtxalaawka.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gthkgbjoel.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gteqqagtbk.html

[T15] Kotlin：接口
来源：http://dali.jqgufenzy.top/Article/details/gtugxmjdml.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqqkfefd.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gteqqruoqx.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtnngqrpcw.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gtvhbzvrkn.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtcbglwmly.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqpqjhdq.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gthhjljnco.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gtzwyjsafp.html

if let n = opt { print(n) }
来源：http://dali.hfpthk.cn/Article/details/gtjbolcrqa.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gtbsfzyydv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gtkrqdsuuf.html

[T21] Swift：遍历
来源：http://dali.yvedp.cn/Article/details/gtybrsuquf.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtrmlunfqk.html

[T22] Swift：字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabedehfk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdnxxgzt.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gtafsxteix.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gtkyrpbguf.html

[T24] Swift：闭包
来源：http://dali.nwbrower.top/Article/details/gththfkmpl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtfsjhwuch.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmsceahe.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gtsnywhumm.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtwsqguhhd.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaodxzfl.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmoakluxi.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gttwqyvxhw.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gtocprxflg.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gtgzytjiyd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtwkqfgpyf.html

guard let x = opt else { return }
来源：http://dali.xziqi.cn/Article/details/gtbdmfbxun.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gtylqwonue.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gtopdkrngb.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtyqltsudx.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtepnufxdo.html

[T32] Lua：局部变量
来源：http://dali.birdmap.top/Article/details/gtponhpxkh.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtgdrpawni.html

[T33] Lua：表（数组）
来源：http://dali.birdmap.top/Article/details/gtfbjzotlp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtdluxfpsf.html

[T34] Lua：遍历表
来源：http://dali.xziqi.cn/Article/details/gtatkxsnro.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gtorvuvrmy.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtedvmyjga.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtgfkyhqmi.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpblnjpcz.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gtparqxzyb.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskwrixxb.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gtzziwxflt.html

[T38] Lua：条件
来源：http://dali.ydzc1.top/Article/details/gtttkkllrc.html

if x > 0 then print("正") end
来源：http://dali.bjfxy.top/Article/details/gtmvchpypd.html

[T39] Lua：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtbarbpibq.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gtwzanodra.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gtcsywmekw.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gtveqqoufu.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtzpfgsnzq.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtacwtmioa.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gtcsutevqr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtylozjenu.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtkxyhnpyc.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gtixxadaua.html

[T44] Perl：条件
来源：http://dali.yvedp.cn/Article/details/gtpopdronb.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gtgcwipblk.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gtbppsfrqh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gtdhmlftcn.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gtrvdvvpzu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdhhndkkg.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gtlezkluts.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.svipenyu.cn/Article/details/gtpzvxqwhj.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gtlggjgtni.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gtfzbcsivd.html

[T49] Perl：函数
来源：http://dali.0kj1m.cn/Article/details/gtqadappjb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaupqtert.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gttdmocxyi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gtlgsddxon.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gtpikjjclk.html

[T51] Scala：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtqdfvpueq.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtfcvfizio.html

[T52] Scala：变量
来源：http://dali.birdmap.top/Article/details/gtlntsskxp.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gtemvfhnhk.html

[T53] Scala：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtihixwewh.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtcupknfjk.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtpmcsbsiv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtgxhwfnms.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtvxlxeybb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hywenlv.cn/Article/details/gtzopbxxpc.html

[T56] Scala：样例类
来源：http://dali.iojbl.cn/Article/details/gtdfhculyh.html

case class User(name: String, age: Int)
来源：http://dali.dashuyun.cn/Article/details/gthrgbxfxh.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gtbadmvquc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gtbxijkaaj.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gtutsosrcd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmmatdfg.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gteoqfzjwx.html

for (i <- 1 to 10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtvsuwzfzw.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtlnymbkgn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yvedp.cn/Article/details/gtseebzktr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxqeprelk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gtpolbxslr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwgrfsyku.html

[U01] Py：创建虚拟环境
来源：http://dali.aibaodan.cn/Article/details/gtxhficyuk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.316326.xyz/Article/details/gtkainlswx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtnpzqdrbo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtavbfkviq.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gtyjabzqvv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xinyue.icu/Article/details/gtpsamcmcf.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gttatmiowt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cqqwz.cn/Article/details/gtwzxdxesp.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gtsanxtkzb.html

list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gthmfwyosu.html

[U06] Py：合并两个字典
来源：http://dali.hammf.cn/Article/details/gtwhgnelzu.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gtrschtxqj.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gtoneezpxf.html

{v: k for k, v in d.items()}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgkonnfw.html

[U08] Py：展平二维列表
来源：http://dali.yuanzhike.top/Article/details/gtlunygvxl.html

[y for x in nested for y in x]
来源：http://dali.yangfankeji.com/Article/details/gteewywvow.html

[U09] Py：字典取最大值的键
来源：http://dali.xylfe.cn/Article/details/gtizsjzgkq.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gtbouvgjvn.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gtobismzpc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hywenlv.cn/Article/details/gtefgxpeuy.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtyfufydbh.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gtxjpqvkqe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yanxiufei.cn/Article/details/gttmialgbn.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gtlcuaobkn.html

[U13] Py：固定长度队列
来源：http://dali.jqgufenzy.top/Article/details/gtdivickfr.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gtllnqmfwo.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gtoipdjdcm.html

defaultdict(list)
来源：http://dali.iojbl.cn/Article/details/gtchioosdu.html

[U15] Py：高精度计时
来源：http://dali.wangdashe.top/Article/details/gtzggctgzr.html

t = time.perf_counter()
来源：http://dali.xuanzx.com/Article/details/gtacqwdsrl.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigufen.top/Article/details/gtrznyaupq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj202588.top/Article/details/gteafnrcmn.html

[U17] Py：初始化日志
来源：http://dali.yueranfly.top/Article/details/gtldepeeoc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyemksthx.html

[U18] Py：预编译正则
来源：http://dali.yj20258888.top/Article/details/gtfklqnkwe.html

pat = re.compile(r"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzxamqma.html

[U19] Py：正则替换带回调
来源：http://dali.zhiwuduotai.top/Article/details/gtsgpucshy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtugqjozlx.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gtuoqqnwtn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yangfankeji.com/Article/details/gtnndptuqs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhiwuduotai.top/Article/details/gtlmjruqph.html

@contextlib.contextmanager
来源：http://dali.hongshengwenyu.top/Article/details/gtfrqougpg.html

[U22] Py：矩阵转置
来源：http://dali.9152youxi.cn/Article/details/gtpdpnqekm.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gtrabbdiaw.html

[U23] Py：分块读取大文件
来源：http://dali.meibo888.top/Article/details/gtqkwejsne.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigfzy.top/Article/details/gtuzxccoox.html

[U24] Py：路径操作
来源：http://dali.mhx1999.top/Article/details/gtmzrbqgcs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtszvvaikt.html

[U25] Py：CSV 按字典读
来源：http://dali.yuanzhike.top/Article/details/gtwsloyave.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gtnydbsfwf.html

[U26] Py：并发下载
来源：http://dali.yongpay.top/Article/details/gtkfejjlow.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hammf.cn/Article/details/gtrpnxxxpa.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gtkwuihzmz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.havefunace.top/Article/details/gtwxvcymov.html

[U28] Py：类型别名
来源：http://dali.jianghu66.top/Article/details/gthmbtlnjm.html

UserId = int
来源：http://dali.havefunace.top/Article/details/gtyvmjwwhu.html

[U29] Py：属性校验
来源：http://dali.haohaochexian.top/Article/details/gtsqhjvsyh.html

@property 与 @x.setter 配合
来源：http://dali.nanxuanxn.top/Article/details/gtgwxoyerd.html

[U30] Py：数据类
来源：http://dali.yj20258.top/Article/details/gtrjhooymy.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gtsusgvcbf.html

[U31] Py：单测
来源：http://dali.feifeiyinyue.top/Article/details/gtqgtufmka.html

python -m pytest -q
来源：http://dali.jinqigfzy.top/Article/details/gtavegbfuk.html

[U32] Py：代码格式化
来源：http://dali.c1oappe.top/Article/details/gtnqfmiskb.html

ruff format . && ruff check --fix .
来源：http://dali.gogol.net.cn/Article/details/gtbpbpqple.html

[U33] Py：打包发布
来源：http://dali.yuanzhike.top/Article/details/gtyfuirxsu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zycfv.cn/Article/details/gtrzgypuzr.html

[U34] Py：判断编码
来源：http://dali.yj20258.top/Article/details/gtuashyaxz.html

chardet.detect(raw)
来源：http://dali.yj20258.top/Article/details/gtzclcnaxe.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gtqtdwtmmw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gtwgbkodsn.html

[U36] Py：定时任务
来源：http://dali.tian-w.cn/Article/details/gtlsuxgfft.html

schedule.every(10).minutes.do(job)
来源：http://dali.sufxvd.cn/Article/details/gtuhvjatli.html

[U37] Py：读写 Excel
来源：http://dali.chenlongwang.top/Article/details/gteggqaatr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.svipenyu.cn/Article/details/gtjfjvvoaa.html

[U38] Py：获取脚本所在目录
来源：http://dali.feifeiyinyue.top/Article/details/gtslwsnusx.html

Path(__file__).resolve().parent
来源：http://dali.pycfn.com/Article/details/gtbgagkcao.html

[U39] Py：判断是否在交互环境
来源：http://dali.fengsongda.top/Article/details/gttrsnlnih.html

sys.stdout.isatty()
来源：http://dali.jyoumei.cn/Article/details/gtokscneqx.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gtxubupooj.html

print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gtpbnhwxnq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gtcpwxmevy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dianchejie.cn/Article/details/gthpvaeldu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aizwys.cn/Article/details/gtqexvwcyd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xylfe.cn/Article/details/gtwvyfsqhr.html

[U43] PHP：声明命名空间
来源：http://dali.ehwqpu.com/Article/details/gtbxgcnkvx.html

namespace App\Http;
来源：http://dali.zhoulong.xyz/Article/details/gthmyztdrp.html

[U44] PHP：开启严格类型
来源：http://dali.wangshuangyany.cn/Article/details/gtzlioibpn.html

declare(strict_types=1);
来源：http://dali.hnqzz.top/Article/details/gtetofnefd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sweek.top/Article/details/gtgelixxoj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtearjuexx.html

[U46] PHP：可空类型
来源：http://dali.pycfn.com/Article/details/gtitdhzlkr.html

?string $name = null
来源：http://dali.fengsongda.top/Article/details/gtlhrbafyv.html

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gtkxlrraxu.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gtrejhwvio.html

[U48] PHP：纯枚举
来源：http://dali.shuidangran.top/Article/details/gtcjmomfuz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.quarkkingdee.top/Article/details/gtkodcgxeb.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gtwgfjotsy.html

public readonly string $name
来源：http://dali.xinyue.icu/Article/details/gththwvqpe.html

[U50] PHP：构造器属性提升
来源：http://dali.chenzaomai.com/Article/details/gtwztcwsdc.html

public function __construct(private int $id) {}
来源：http://dali.ivvv.top/Article/details/gtavkbnxsn.html

[U51] PHP：数组解构
来源：http://dali.snrcjt.cn/Article/details/gtikfqseop.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gtqfhxxwyv.html

[U52] PHP：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gtknjqawnr.html

$double = fn($x) => $x * 2;
来源：http://dali.cqqwz.cn/Article/details/gtwwfwrjbu.html

[U53] PHP：空合并运算符
来源：http://dali.ybcxt.top/Article/details/gtuvjudsas.html

$v = $a ?? $b ?? "default";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgwljoia.html

[U54] PHP：空安全调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoazzlmue.html

$obj?->method()
来源：http://dali.jinqigufen.top/Article/details/gtkeebikdw.html


<!-- 参考信息 -->