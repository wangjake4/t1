代发 wailian999

#ifndef X_H
来源：http://dali.yonumen.top/Article/details/gt2ehkbwqik.html

#define X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmvrwqlg.html

#endif
来源：http://dali.yueranfly.top/Article/details/gt2llkfbjmy.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dayxuigm.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gt2yxdhwewy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gt2iypxqqsh.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gt2nefdwkwf.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gt2wofqbdbo.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gt2ixnfqaan.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gt2ovvrdabc.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gt2jfjtqnua.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gt2rahyzwtm.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gt2uhswcfnh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2qskuzzjg.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gt2wlwmancu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yeuctehp.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gt2pegblhft.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gt2hzskvskw.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gt2wmzstqsk.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gt2sofodrkp.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2erlbvhqm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gt2nszsaqhn.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gt2sqmjdpye.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sxryk.cn/Article/details/gt2hzwyktbx.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2qvtgmivh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gt2ctcttyoz.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gt2edrlpqac.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gt2afkukekz.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gt2zrbbhgcg.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fwtqxndr.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gt2rkvvugmu.html

void inc(int &x) { ++x; }
来源：http://dali.andypj.xyz/Article/details/gt2ktdiwvtj.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gt2xablihwu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znnjjgws.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gt2xelsqyza.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gt2vqldlcsv.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gt2iyjyfcas.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkhyjngj.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2yhuzbhzd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gt2qtgnozty.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gt2akmqlxxs.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gt2plhnyxez.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwdketme.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gt2girligrp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2daivofqr.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpyqhtte.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gt2yfajmmuv.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gt2qosysjph.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gt2mogtmrat.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gt2nmusszyu.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gt2dhvkywmc.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gt2vqscgaza.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.havefunace.top/Article/details/gt2cfjjhowo.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gt2covxjrvj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fifctooj.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gt2mhfxlury.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wxgpqpsj.html

[S57] C++：编译期常量
来源：http://dali.sxryk.cn/Article/details/gt2eupbogau.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gt2ddgxuhca.html

[S58] C++：命名空间
来源：http://dali.fengsongda.top/Article/details/gt2xkhxmqvq.html

namespace ns { int f() { return 1; } }
来源：http://dali.guannengcc.top/Article/details/gt2daopifdl.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gt2oohxkunj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gt2ebxglccw.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gt2jdqhrwcj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gt2lobxiatr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2lkvzuami.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gt2byqxjeks.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ymhwvpsy.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2ueotxmrm.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2uabzuysw.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gt2qlsxgvma.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gt2hyoqnvfk.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gt2sinlrhkm.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfkegnwo.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gt2makvydme.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gt2zjilbgwo.html

[T05] Kotlin：when 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsrsuzja.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gt2aztlulxd.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gt2jsarvnff.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2koqxckxv.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gt2vyyviovm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gt2lwayheic.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gt2zhybnlnq.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2zlvqjhbz.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gt2anhhiydw.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngffqtmj.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gt2gyvcfdum.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvywvpfe.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gt2mpdhxbdn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gt2kwkmisby.html

[T12] Kotlin：解构声明
来源：http://dali.nanxinkj.top/Article/details/gt2ustfxjxr.html

val (a, b) = Pair(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2lccebscs.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gt2icgjxbsh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2evrquxdw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2elbqywul.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nryhtxrt.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gt2eosthdxt.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gt2kxvpximh.html

[T16] Swift：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysptbzql.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gt2zvhapolj.html

[T17] Swift：变量与常量
来源：http://dali.jinqigufen.top/Article/details/gt2ezwysoim.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gt2qpeiuyyk.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gt2xpqvcdij.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gt2moyoayvs.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gt2fcvrohzu.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gt2pzlfqmre.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gt2yhjmovik.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnadnwlg.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkiurhkl.html

for x in a { print(x) }
来源：http://dali.daxiang520.top/Article/details/gt2jmyrchtk.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gt2xdgxygcu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpicrwik.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gt2qxrtfoeh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2qiwhrwzf.html

[T24] Swift：闭包
来源：http://dali.yvedp.cn/Article/details/gt2uuqrzdsi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2ocdizocs.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gt2uxkhlzdt.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdobuzup.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gt2bbeoagbx.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aitxekod.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gt2yypkfkky.html

do { try f() } catch { print(error) }
来源：http://dali.jqgufenzy.top/Article/details/gt2cnxogymv.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gt2vlaaxgud.html

enum Color { case red, green }
来源：http://dali.andypj.xyz/Article/details/gt2iekvqegl.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgufenzy.top/Article/details/gt2owakfymb.html

guard let x = opt else { return }
来源：http://dali.daria6918.cn/Article/details/gt2bjunjmcd.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkrqhwyw.html

protocol Shape { func area() -> Double }
来源：http://dali.jiagoushi.top/Article/details/gt2rmsernts.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2qewkkbrb.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2cuypcvqq.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gt2yqmvqrsu.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gt2rjdgmhjx.html

[T33] Lua：表（数组）
来源：http://dali.xinyue.icu/Article/details/gt2tyhximty.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgfzy.top/Article/details/gt2zkzzcdxk.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gt2nsidiilr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gt2fepfjwrn.html

[T35] Lua：字典表
来源：http://dali.jinqigfzy.top/Article/details/gt2aklgwtkl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gt2apcvmsyb.html

[T36] Lua：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2andoqmrn.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gt2xlugsbjp.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gt2npvvfmpw.html

"a" .. "b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgsnukcs.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gt2rflfzzqh.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gt2rzuxorsn.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gt2qbkwgrjd.html

string.find(s, "%d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npvuwqwg.html

[T40] Lua：元表
来源：http://dali.sxryk.cn/Article/details/gt2iwbtidkz.html

setmetatable({}, { __index = base })
来源：http://dali.daxiang520.top/Article/details/gt2edveazwe.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2ceumspev.html

print "Hello\n";
来源：http://dali.ppjwa.cn/Article/details/gt2ucedcjno.html

[T42] Perl：变量类型
来源：http://dali.aibaodan.cn/Article/details/gt2cwzkwinj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2bdqehytd.html

[T43] Perl：字符串插值
来源：http://dali.fengsongda.top/Article/details/gt2kbcrlqks.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gt2dnbnllpv.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wczilwvl.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gt2hvqvyvbl.html

[T45] Perl：数组遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2jnxxvvwe.html

for my $x (@arr) { print $x; }
来源：http://dali.meibo888.top/Article/details/gt2xihmlqeu.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gt2zxrveirt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gt2uusmpvca.html

[T47] Perl：正则捕获
来源：http://dali.cdnleiting.top/Article/details/gt2ytcxhtij.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gt2phbqwebz.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gt2sfghydjw.html

$s =~ s/old/new/g;
来源：http://dali.chenjidiqi.icu/Article/details/gt2eavrlcaf.html

[T49] Perl：函数
来源：http://dali.ppjwa.cn/Article/details/gt2hjcrfuxu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2ilbmpooq.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2jhkdhxoe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gt2gpsfccvu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ehwqpu.com/Article/details/gt2viifpzdk.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2fqhcqppk.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gt2rdojatay.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gt2bmslftbq.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2dtqlphnb.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2jesbohdi.html

s"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gt2catehydn.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgfgzhtg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gt2ixrctwyc.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2lkkbyeaz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2kbrczfbc.html

[T56] Scala：样例类
来源：http://dali.nanxinkj.top/Article/details/gt2fylbfprp.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2hqljxzly.html

[T57] Scala：模式匹配
来源：http://dali.iojbl.cn/Article/details/gt2jdlvtpmo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzepdnei.html

[T58] Scala：函数定义
来源：http://dali.ivvv.top/Article/details/gt2owrpiuzs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gt2qhtxoqry.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gt2feitfonl.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gt2ofsfhdvo.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gt2qlurpheg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cucudq.cn/Article/details/gt2yrkdwvoh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2wsaanvvt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gt2hdjhrprg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2gxiazxsd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhengqikj.top/Article/details/gt2agtmngjn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxinkj.top/Article/details/gt2wxyucsix.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gt2vtrandrt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qwfeuskt.html

[U03] Py：加载 .env 配置
来源：http://dali.9152youxi.cn/Article/details/gt2kofsjxnc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfumhwtl.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gt2dtlxfqez.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxvgvnmj.html

[U05] Py：列表去重且保序
来源：http://dali.birdmap.top/Article/details/gt2orewclrn.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2mgfqqrpd.html

[U06] Py：合并两个字典
来源：http://dali.sxryk.cn/Article/details/gt2mvfkfgkt.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gt2rmkltpvy.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gt2hbcypeff.html

{v: k for k, v in d.items()}
来源：http://dali.daria6918.cn/Article/details/gt2ikkogzla.html

[U08] Py：展平二维列表
来源：http://dali.shzxlz.cn/Article/details/gt2ucfpijpj.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gt2xuowkack.html

[U09] Py：字典取最大值的键
来源：http://dali.9152youxi.cn/Article/details/gt2bfpzljed.html

max(d, key=d.get)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2koavzgjp.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gt2qrcdjjlr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gt2edlavmyy.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gt2cbigmfqq.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gt2xauagitt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gt2mcbllnvm.html

Counter(arr).most_common(3)
来源：http://dali.tianlin.xyz/Article/details/gt2gokdzqtf.html

[U13] Py：固定长度队列
来源：http://dali.shzxlz.cn/Article/details/gt2hklcdhbi.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gt2ccqtviyy.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mldgoecm.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gt2uvclycoc.html

[U15] Py：高精度计时
来源：http://dali.ehwqpu.com/Article/details/gt2xnrjmkam.html

t = time.perf_counter()
来源：http://dali.316326.xyz/Article/details/gt2whmjatrr.html

[U16] Py：命令行参数解析
来源：http://dali.svipenyu.cn/Article/details/gt2thesfexw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gt2jtnslhgx.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gt2xlvughcj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yueranfly.top/Article/details/gt2wopcofrz.html

[U18] Py：预编译正则
来源：http://dali.hfpthk.cn/Article/details/gt2jmgspyma.html

pat = re.compile(r"\d+")
来源：http://dali.meibo888.top/Article/details/gt2lutuxgmb.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gt2xfjnjufz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gt2pnlqqmwl.html

[U20] Py：缓存函数结果
来源：http://dali.birdmap.top/Article/details/gt2hrksryqw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hadunbvh.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenlongwang.top/Article/details/gt2thrwubnb.html

@contextlib.contextmanager
来源：http://dali.zhixingplan.top/Article/details/gt2bbkarnbv.html

[U22] Py：矩阵转置
来源：http://dali.hnxiangtu.top/Article/details/gt2ribnjzqz.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gt2hlfrahde.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gt2zblzxcgo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aibaodan.cn/Article/details/gt2ygzfkmbd.html

[U24] Py：路径操作
来源：http://dali.cucudq.cn/Article/details/gt2wszpafmf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogbyqfmd.html

[U25] Py：CSV 按字典读
来源：http://dali.aibaodan.cn/Article/details/gt2nkmhrvfk.html

csv.DictReader(f)
来源：http://dali.0kj1m.cn/Article/details/gt2iwjucujg.html

[U26] Py：并发下载
来源：http://dali.jlsjyb.cn/Article/details/gt2cjwctkgl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmomgax.html

[U27] Py：异步 HTTP
来源：http://dali.tian-w.cn/Article/details/gt2upokukke.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xziqi.cn/Article/details/gt2atzyfgdl.html

[U28] Py：类型别名
来源：http://dali.wangshuangyany.cn/Article/details/gt2cteidbsn.html

UserId = int
来源：http://dali.dashuyun.cn/Article/details/gt2eojszbrv.html

[U29] Py：属性校验
来源：http://dali.xinyue.icu/Article/details/gt2rescctkm.html

@property 与 @x.setter 配合
来源：http://dali.guannengcc.top/Article/details/gt2edwmmvag.html

[U30] Py：数据类
来源：http://dali.dashuyun.cn/Article/details/gt2adsggwqn.html

@dataclass(slots=True)
来源：http://dali.yonumen.top/Article/details/gt2pototoua.html

[U31] Py：单测
来源：http://dali.guannengcc.top/Article/details/gt2tbxgofyn.html

python -m pytest -q
来源：http://dali.cheryme.top/Article/details/gt2cuqfomyk.html

[U32] Py：代码格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2exbsugxe.html

ruff format . && ruff check --fix .
来源：http://dali.smart0.xyz/Article/details/gt2wnftszpt.html

[U33] Py：打包发布
来源：http://dali.tianlin.xyz/Article/details/gt2qybdqhpm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhixingplan.top/Article/details/gt2qxplfvzu.html

[U34] Py：判断编码
来源：http://dali.ppjwa.cn/Article/details/gt2fpylzqzp.html

chardet.detect(raw)
来源：http://dali.c1oappe.top/Article/details/gt2tzeiasgx.html

[U35] Py：发送邮件
来源：http://dali.ydzc1.top/Article/details/gt2xcfbckcx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gzhubu.top/Article/details/gt2eboybhil.html

[U36] Py：定时任务
来源：http://dali.jyoumei.cn/Article/details/gt2ztochaad.html

schedule.every(10).minutes.do(job)
来源：http://dali.shuidangran.top/Article/details/gt2dylkxiuc.html

[U37] Py：读写 Excel
来源：http://dali.jinqigfzy.top/Article/details/gt2rcefnmyo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guowangkeji.top/Article/details/gt2gbmrdofn.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2udlhlhtc.html

Path(__file__).resolve().parent
来源：http://dali.havefunace.top/Article/details/gt2pfmlqrlm.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gt2ggbnvnbt.html

sys.stdout.isatty()
来源：http://dali.aizwys.cn/Article/details/gt2fljxmngn.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gt2fxokcyfs.html

print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocdeyype.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pycfn.com/Article/details/gt2xxvxodlk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhongyouzk.top/Article/details/gt2uwxphffh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpigdhnd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnxiangtu.top/Article/details/gt2nfjnmwmg.html

[U43] PHP：声明命名空间
来源：http://dali.snrcjt.cn/Article/details/gt2txyzftga.html

namespace App\Http;
来源：http://dali.cucudq.cn/Article/details/gt2vrlwhfwa.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gt2evhjndfx.html

declare(strict_types=1);
来源：http://dali.yonumen.top/Article/details/gt2ssirpohr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258888.top/Article/details/gt2kjaufeya.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2ormhhzcu.html

[U46] PHP：可空类型
来源：http://dali.haohaochexian.top/Article/details/gt2apdybryg.html

?string $name = null
来源：http://dali.andypj.xyz/Article/details/gt2qdmuiqqs.html

[U47] PHP：联合类型
来源：http://dali.yj20258888.top/Article/details/gt2ugircmxw.html

int|string $id
来源：http://dali.birdmap.top/Article/details/gt2okoffpcp.html

[U48] PHP：纯枚举
来源：http://dali.yvedp.cn/Article/details/gt2fqgmtaaa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuanzx.com/Article/details/gt2rgcuvnbn.html

[U49] PHP：只读属性
来源：http://dali.xinyue.icu/Article/details/gt2eukppzvk.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gemftkxp.html

[U50] PHP：构造器属性提升
来源：http://dali.cheryme.top/Article/details/gt2rpjqgfca.html

public function __construct(private int $id) {}
来源：http://dali.fzhhl.top/Article/details/gt2dqahuyad.html

[U51] PHP：数组解构
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebuvtoxh.html

[$a, $b] = $arr;
来源：http://dali.nanxinkj.top/Article/details/gt2eodlwduq.html

[U52] PHP：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gt2vmgduiwv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzydqwnj.html

[U53] PHP：空合并运算符
来源：http://dali.daxiang520.top/Article/details/gt2attrvyqp.html

$v = $a ?? $b ?? "default";
来源：http://dali.daxiang520.top/Article/details/gt2ookaqvdx.html

[U54] PHP：空安全调用
来源：http://dali.daxiang520.top/Article/details/gt2xjtlbrbb.html

$obj?->method()
来源：http://dali.tanke756.top/Article/details/gt2vzldnvrv.html


<!-- 参考信息 -->