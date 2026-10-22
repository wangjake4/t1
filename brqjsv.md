代发 wailian999

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gt2spaplcke.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gt2toxwvhrc.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gt2wowajlmi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gt2yjudhnmm.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gt2prooqxif.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebhxilxd.html

[S34] C++：遍历 vector
来源：http://dali.ppjwa.cn/Article/details/gt2hrjrmlps.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gt2nbvfqqtl.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gt2reiznnwa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2lsmumfdo.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gt2dxmfuonc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2vhwllfgx.html

[S37] C++：set
来源：http://dali.cdnleiting.top/Article/details/gt2oiwaigwe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gt2kbukbfkk.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gt2qulfnyor.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gt2jwcnogge.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gt2fdyejkse.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gt2mdpvgttu.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gt2guidatzt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gt2qcgzxeru.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gt2hnetzbpw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gt2xhewtsbk.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gt2gtkcpjjf.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gt2xxmnbkhu.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gt2ovjhuamj.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gt2dayxudnd.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gt2zunnbqjy.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gt2fkdzbqez.html

[S45] C++：lambda
来源：http://dali.yuanzhike.top/Article/details/gt2jqkuevwy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnfeaplo.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gt2alceybyn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvvmrvwk.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gt2sgwiutsc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gt2akhpxrji.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2bbfkpezz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gt2eipfxcgq.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gt2cjxrghsv.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gt2xrkeebdk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gt2xvpxpjca.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwgprafo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2yvdklagz.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gt2zbocnnje.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gt2vkskdpxs.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gt2znkhfjhw.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gt2bgwpdtoi.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gt2btkcjkli.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gt2loubgdke.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2swsxklvp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gt2tjlrhoqw.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gt2fmxdohjz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gt2pubghrxp.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gt2gkavxvzo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2iboffbge.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gt2brtfyrjs.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2funhmpkv.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gt2vpaglkyd.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgeurxsz.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gt2ioxxwwkd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gt2yplxxylp.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gt2omvlngiw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2maiqdxek.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2aagwvzub.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gt2mewoxkne.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkpfupot.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wiceodca.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2vrrxonjy.html

[T02] Kotlin：变量
来源：http://dali.xuanzx.com/Article/details/gt2sjkcsswt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gt2txzgyycx.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gt2erwartmo.html

"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gt2vyjrzbid.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gt2wrrvqnxz.html

val n: String? = null;  n?.length
来源：http://dali.yonumen.top/Article/details/gt2nyzgmdqi.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gt2ehvpnxta.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gt2dpmieibw.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gt2rrltglil.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2faogteqr.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gt2rchtyacf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2bcmrzgkb.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gt2xumyblup.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gt2hbxbotpo.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gt2scfupaba.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gt2cagaaygi.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gt2zdzmchmu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gt2eiiyzcnk.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gt2asjhiouy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gt2rsfrdyax.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gt2dovfbwww.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xgdjcixe.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gt2esfbikkc.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gt2pxabnftb.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqaecvxh.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gt2zbcayfnm.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gt2himoidvp.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gt2ugaijngq.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2dygdqzyz.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2mqknqdxx.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yifxxshe.html

var a = 1;  let b = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2srqdfluy.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gt2ryduzsrl.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmlrkuyc.html

[T19] Swift：可选绑定
来源：http://dali.ivvv.top/Article/details/gt2ctipoouv.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gt2qlyoqunl.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gt2rlnadsdo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuxming.cn/Article/details/gt2okymawfi.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2ozcxwvvx.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gt2jisnjisy.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccycvcak.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyfpimor.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2edyjacyy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gt2bfiwewjm.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gt2aednbtlb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gt2wenqywqh.html

[T25] Swift：结构体
来源：http://dali.316326.xyz/Article/details/gt2rwdsfwir.html

struct P { var x: Int }
来源：http://dali.ybcxt.top/Article/details/gt2mdeetdap.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjalropn.html

class A: Base { override func f() {} }
来源：http://dali.cheryme.top/Article/details/gt2jbsfewlb.html

[T27] Swift：错误处理
来源：http://dali.fengsongda.top/Article/details/gt2ldmwkrji.html

do { try f() } catch { print(error) }
来源：http://dali.hywenlv.cn/Article/details/gt2nhoolzjc.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gt2slupehdz.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gt2jfdyjdsj.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gt2uafjsyaa.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gt2wryvbwyi.html

[T30] Swift：协议
来源：http://dali.aibaodan.cn/Article/details/gt2abnwicax.html

protocol Shape { func area() -> Double }
来源：http://dali.hnxiangtu.top/Article/details/gt2mihlcxld.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2iiydoemv.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2knemldrq.html

[T32] Lua：局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2tofokdgi.html

local a = 1
来源：http://dali.quarkkingdee.top/Article/details/gt2egwbpjmn.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gt2jcapwiut.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aizwys.cn/Article/details/gt2mjixqshq.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gt2tctijdpc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gt2cqrspbet.html

[T35] Lua：字典表
来源：http://dali.hywenlv.cn/Article/details/gt2pclzpfsv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zycfv.cn/Article/details/gt2yczewzze.html

[T36] Lua：函数
来源：http://dali.tianlin.xyz/Article/details/gt2jlgwqqut.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbtnzrqp.html

[T37] Lua：字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gt2lmdmisyp.html

"a" .. "b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csvnkbzt.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gt2qcklbzjp.html

if x > 0 then print("正") end
来源：http://dali.bjfxy.top/Article/details/gt2fvinhjvb.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2peceaixf.html

string.find(s, "%d+")
来源：http://dali.chenlongwang.top/Article/details/gt2dnzoousd.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gt2updfttkh.html

setmetatable({}, { __index = base })
来源：http://dali.chenlongwang.top/Article/details/gt2drdlztta.html

[T41] Perl：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2odekrsfw.html

print "Hello\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wilwovys.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gt2oykwrpes.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkwafozp.html

[T43] Perl：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2ctrskrdt.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gt2rynvuhvn.html

[T44] Perl：条件
来源：http://dali.jqgfzy.top/Article/details/gt2rlbqfwdg.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gt2fztkcpfu.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gt2xodpjiwz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2axhbkwkb.html

[T46] Perl：哈希操作
来源：http://dali.quarkkingdee.top/Article/details/gt2exxwhgdw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gt2iieshnvm.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gt2sfeyizld.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xzshaqiz.html

[T48] Perl：正则替换
来源：http://dali.wangdashe.top/Article/details/gt2wczsvsjg.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gt2gesyehrf.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2wgjmdkyt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2qtiwjvun.html

[T50] Perl：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2elrqbilv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.redwolf501.top/Article/details/gt2gjftsszr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gt2phrcytvq.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2gltafisj.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2vihixwog.html

[T52] Scala：变量
来源：http://dali.zhoulong.xyz/Article/details/gt2zkmclpij.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2xnagbpxi.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2uthvlpti.html

s"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gt2dfhpfwtv.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gt2yswvvlhd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gt2mgmphctn.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2skbvjspp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gt2zzqrgulk.html

[T56] Scala：样例类
来源：http://dali.kuanghao11.cn/Article/details/gt2szpwcypr.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gt2okzvgodc.html

[T57] Scala：模式匹配
来源：http://dali.xylfe.cn/Article/details/gt2slbsnfvo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkyyshjl.html

[T58] Scala：函数定义
来源：http://dali.jinqigfzy.top/Article/details/gt2usrqroia.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.quarkkingdee.top/Article/details/gt2wmtcbnwt.html

[T59] Scala：循环
来源：http://dali.yangfankeji.com/Article/details/gt2ymxnuhcn.html

for (i <- 1 to 10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2twivavfu.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gt2qsovlcta.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gt2eyagbonn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2tanlpmdv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yvedp.cn/Article/details/gt2fjwddlfi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2xhutalpt.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxinkj.top/Article/details/gt2oqnicsqw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gt2faaxizii.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gt2dgzjvchg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gt2lxfawtaq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhoulong.xyz/Article/details/gt2ewmbijsr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gt2ajodkfyw.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gt2yxutzkvk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oweuyfdo.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gt2duanjrmp.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2lubuvdyb.html

[U06] Py：合并两个字典
来源：http://dali.jyoumei.cn/Article/details/gt2elawaffz.html

{**a, **b}
来源：http://dali.316326.xyz/Article/details/gt2adkqssxk.html

[U07] Py：反转字典键值
来源：http://dali.tian-w.cn/Article/details/gt2qmtrurfh.html

{v: k for k, v in d.items()}
来源：http://dali.birdmap.top/Article/details/gt2ucrivhpv.html

[U08] Py：展平二维列表
来源：http://dali.haohaochexian.top/Article/details/gt2jobhecsq.html

[y for x in nested for y in x]
来源：http://dali.redwolf501.top/Article/details/gt2lpbvjsnu.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gt2vvjbsomy.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gt2nhoynhha.html

[U10] Py：按值排序字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ooolgjdl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gt2pkyoxaio.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gt2vhdlocqg.html

(x * 2 for x in arr)
来源：http://dali.yuanzhike.top/Article/details/gt2hzpdvuua.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuanzx.com/Article/details/gt2zcacoiaj.html

Counter(arr).most_common(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qisrovmp.html

[U13] Py：固定长度队列
来源：http://dali.jqgufenzy.top/Article/details/gt2wrfrhups.html

deque(maxlen=10)
来源：http://dali.ivvv.top/Article/details/gt2hpvuohjc.html

[U14] Py：分组收集到列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmeqsbxp.html

defaultdict(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rafvvjyr.html

[U15] Py：高精度计时
来源：http://dali.hysaishi.cn/Article/details/gt2lxcrajdu.html

t = time.perf_counter()
来源：http://dali.svipenyu.cn/Article/details/gt2hcncfkng.html

[U16] Py：命令行参数解析
来源：http://dali.yonumen.top/Article/details/gt2wdsouqzc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gt2aadiqpec.html

[U17] Py：初始化日志
来源：http://dali.jinqigfzy.top/Article/details/gt2jhjusalt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xziqi.cn/Article/details/gt2skqnkejy.html

[U18] Py：预编译正则
来源：http://dali.jinqigfzy.top/Article/details/gt2tmvgfwcw.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gt2mochvphz.html

[U19] Py：正则替换带回调
来源：http://dali.fzhhl.top/Article/details/gt2rbclywfr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gogol.net.cn/Article/details/gt2gdolfwew.html

[U20] Py：缓存函数结果
来源：http://dali.gaohongyu789.top/Article/details/gt2eckacpjc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuanzhike.top/Article/details/gt2dxjmacay.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhiwuduotai.top/Article/details/gt2jswncpgu.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gt2kyzddzyv.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gt2gbmojcpf.html

list(zip(*m))
来源：http://dali.hnxiangtu.top/Article/details/gt2eexpxlya.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gt2vllocvjz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zdqjudy.top/Article/details/gt2pulqrbda.html

[U24] Py：路径操作
来源：http://dali.yj20258.top/Article/details/gt2hiiitxne.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gt2xnbdmyjp.html

[U25] Py：CSV 按字典读
来源：http://dali.smart0.xyz/Article/details/gt2hnkqxolo.html

csv.DictReader(f)
来源：http://dali.cdnleiting.top/Article/details/gt2flpgjptl.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gt2zvoaixcv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tian-w.cn/Article/details/gt2rjhpveiv.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gt2qsxxerdr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ppjwa.cn/Article/details/gt2vrxiooho.html

[U28] Py：类型别名
来源：http://dali.shuidangran.top/Article/details/gt2nlkohrii.html

UserId = int
来源：http://dali.xziqi.cn/Article/details/gt2maxvpngc.html

[U29] Py：属性校验
来源：http://dali.jlsjyb.cn/Article/details/gt2vfnloseq.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqynvipn.html

[U30] Py：数据类
来源：http://dali.yvedp.cn/Article/details/gt2usyxuzsm.html

@dataclass(slots=True)
来源：http://dali.ppjwa.cn/Article/details/gt2ssriihjl.html

[U31] Py：单测
来源：http://dali.c1oappe.top/Article/details/gt2dunmkcze.html

python -m pytest -q
来源：http://dali.feifeiyinyue.top/Article/details/gt2djcshajl.html

[U32] Py：代码格式化
来源：http://dali.hysaishi.cn/Article/details/gt2weoebfwp.html

ruff format . && ruff check --fix .
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxlhwmqj.html

[U33] Py：打包发布
来源：http://dali.sxryk.cn/Article/details/gt2ittnwulz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.mhx1999.top/Article/details/gt2roitkjxl.html

[U34] Py：判断编码
来源：http://dali.mhx1999.top/Article/details/gt2ggplmvow.html

chardet.detect(raw)
来源：http://dali.zhengqikj.top/Article/details/gt2zsvjzqyi.html

[U35] Py：发送邮件
来源：http://dali.zdqjudy.top/Article/details/gt2wzrefwpo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gzhubu.top/Article/details/gt2wahnllla.html

[U36] Py：定时任务
来源：http://dali.kuanghao11.cn/Article/details/gt2uolasvhi.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gt2escauyqe.html

[U37] Py：读写 Excel
来源：http://dali.ehwqpu.com/Article/details/gt2hafbbbas.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gotoacloud.top/Article/details/gt2vbwmaqyr.html

[U38] Py：获取脚本所在目录
来源：http://dali.mhx1999.top/Article/details/gt2vhiuueus.html

Path(__file__).resolve().parent
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzlsdgvv.html

[U39] Py：判断是否在交互环境
来源：http://dali.hammf.cn/Article/details/gt2vwubdxep.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgnpmzne.html

[U40] Py：打印到标准错误
来源：http://dali.yueranfly.top/Article/details/gt2yixukuwn.html

print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gt2yuaietet.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuetiantiany.cn/Article/details/gt2etkrtxme.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgxweahf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gt2cicthrzr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.birdmap.top/Article/details/gt2dqyzvgsf.html

[U43] PHP：声明命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgkuxwhs.html

namespace App\Http;
来源：http://dali.iojbl.cn/Article/details/gt2usbtyyyx.html

[U44] PHP：开启严格类型
来源：http://dali.nanxuanxn.top/Article/details/gt2kldlmrqv.html

declare(strict_types=1);
来源：http://dali.iojbl.cn/Article/details/gt2pidwhrww.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fengsongda.top/Article/details/gt2hjukpbuh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2ooyagded.html

[U46] PHP：可空类型
来源：http://dali.zhoulong.xyz/Article/details/gt2tjqkiuoj.html

?string $name = null
来源：http://dali.andypj.xyz/Article/details/gt2rxlunihd.html

[U47] PHP：联合类型
来源：http://dali.cheryme.top/Article/details/gt2taalxmni.html

int|string $id
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkdochek.html

[U48] PHP：纯枚举
来源：http://dali.cdnleiting.top/Article/details/gt2rtqhcdoy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.svipenyu.cn/Article/details/gt2rrrwmftk.html

[U49] PHP：只读属性
来源：http://dali.dianchejie.cn/Article/details/gt2gpajuhbz.html

public readonly string $name
来源：http://dali.ybcxt.top/Article/details/gt2nagxvmbi.html

[U50] PHP：构造器属性提升
来源：http://dali.dianchejie.cn/Article/details/gt2tkrqwhli.html

public function __construct(private int $id) {}
来源：http://dali.sweek.top/Article/details/gt2aisojjlz.html

[U51] PHP：数组解构
来源：http://dali.yvedp.cn/Article/details/gt2ktqxszcp.html

[$a, $b] = $arr;
来源：http://dali.cucudq.cn/Article/details/gt2gkxkpfmc.html

[U52] PHP：箭头函数
来源：http://dali.mhx1999.top/Article/details/gt2qlotjoty.html

$double = fn($x) => $x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exbjsuwd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rwclcqla.html

$v = $a ?? $b ?? "default";
来源：http://dali.daxiang520.top/Article/details/gt2cgpuspsc.html

[U54] PHP：空安全调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgpddcia.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gt2flouqjof.html

[U55] PHP：match 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmntjfnj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gt2rsgyjeen.html

[U56] PHP：命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2evshikvy.html

f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2dkzxrney.html


<!-- 参考信息 -->