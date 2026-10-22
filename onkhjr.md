代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmfsfkww.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnisgjtfj.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gtzdyizzzp.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gtxblunxod.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtaqzzeyhk.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gttxkipajd.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtluhpcmwu.html

[S28] C：静态变量
来源：http://dali.svipenyu.cn/Article/details/gtrugggcwp.html

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gtjfecvltd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gttdzzfezt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gtmrgjxwzt.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gtvnmrvmle.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gtgrzykmvc.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gtftaidhwd.html

#endif
来源：http://dali.daxiang520.top/Article/details/gtgowtcmwa.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtgebcwpsn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gtclluukxa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gtyexmmrsl.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmegyzsql.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtmaaqwpus.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtyvkvjrbq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gtrfpdvyon.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gtgwekjujj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aibaodan.cn/Article/details/gtbytpgpmd.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gthqwtqpar.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gthhmjmicy.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gtsgatdbsg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuzlczfv.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gtnhglrgeg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gttzwnczhv.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gthbvuegie.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtyxnmqvpp.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtiqffxnbz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dashuyun.cn/Article/details/gtkmcwzkue.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtaxcfcqig.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gtuhorjpgs.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gtlzfascdk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gtzfvosjij.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gtryuhvbac.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gtgloqyhqg.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtoddqudyb.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gtisvzfrxn.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtikkauomg.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gtdopdtziu.html

[S45] C++：lambda
来源：http://dali.yj202588.top/Article/details/gtncaohltc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gtsqrqangk.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gtqipwmhdf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gtixevtbji.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gtznxxbwjo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtegvyfqaw.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtohxuifga.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gtxlwdoslp.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gttubqrjjz.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtvfryfseq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gttltzcguq.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gtfzvssqqt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtokxsjbtk.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gtswboucun.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gtifrybsba.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gtxesadwch.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gtdxvgrhqa.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gtshkshmlc.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gtuhtrduhu.html

[S54] C++：异常处理
来源：http://dali.hywenlv.cn/Article/details/gthtfnllap.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gtrcvsgrfo.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gtheaardfe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtrqbgfbno.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gtxhiaosoz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkigsnqi.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtzfcfvpdi.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gthrrstyvf.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtppiprjtc.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtlnpxhdsl.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gtkykpxgrx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gtirhowkub.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gtynnosmac.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtdkzzixnl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfafyqard.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnsagelq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttxvpjuqa.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtflzxdatv.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtcbzqqmox.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gthadujmdf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtjgyceqmw.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtiqqacvpe.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtjkkjzuis.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtzjwyryae.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtantkawlm.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadmfxndg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdpvsfrv.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gtvdygzcnh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtzvazpckp.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtevpwmpix.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtglotajnc.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gttzjtnord.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gtfmypzbmi.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gtaucknijb.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gtefefxrpp.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtilmcdvga.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gthsctzgif.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gthmkpiwza.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gtrfoeruxj.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtlksnqeor.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtkvolmoow.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gtkzqlmihh.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gtlmmqebol.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtkeihsjwi.html

for (i in 1..10) println(i)
来源：http://dali.yongpay.top/Article/details/gtdmzzrjsw.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusgjfwum.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gtpuhbegui.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtsnpmsoax.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtrukmoumm.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gtjclrzvkb.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gtephjzyuz.html

[T18] Swift：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtzjmddahu.html

"值: \(b)"
来源：http://dali.guowangkeji.top/Article/details/gtbenanvch.html

[T19] Swift：可选绑定
来源：http://dali.jqgfzy.top/Article/details/gtxhryovut.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gtqqwrtyod.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtpecvpamy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtlrhezgdt.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gtorbqxwcg.html

for x in a { print(x) }
来源：http://dali.sufxvd.cn/Article/details/gtnalyriem.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtddlxlzwd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gtnzcjzldp.html

[T23] Swift：函数
来源：http://dali.dashuyun.cn/Article/details/gtuteuwelz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cheryme.top/Article/details/gtxkgbkxfy.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gtigvrkuid.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtggpujkyp.html

[T25] Swift：结构体
来源：http://dali.jiagoushi.top/Article/details/gtvnpszsbr.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gtubercjuu.html

[T26] Swift：类与重写
来源：http://dali.chenjidiqi.icu/Article/details/gtqrxotbjw.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gtiavyoefl.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gtcnwovzrk.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocihopgl.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtlmqlhptf.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gtroghumpt.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gtjivhqzzu.html

guard let x = opt else { return }
来源：http://dali.bjfxy.top/Article/details/gtpjklnogt.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gtsjtorazu.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gtbhvnrept.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtobwkkeww.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtxryjimil.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gtuldtwhnr.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gtuhfpnvwj.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gthldzmuaw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.smart0.xyz/Article/details/gtqtvmbifv.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gtoycoclva.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangdashe.top/Article/details/gtzlpuqijk.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gtpwwpuzic.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gtlmikmqsj.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gthzwyepxq.html

function add(a, b) return a + b end
来源：http://dali.ivvv.top/Article/details/gtyqlthlgj.html

[T37] Lua：字符串拼接
来源：http://dali.yonumen.top/Article/details/gtmtqabnpz.html

"a" .. "b"
来源：http://dali.smart0.xyz/Article/details/gtwksuhcze.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gtzsrkjtau.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtatvaibri.html

[T39] Lua：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gttxumfvlk.html

string.find(s, "%d+")
来源：http://dali.tianlin.xyz/Article/details/gtvmxvfdnb.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gtkozrvdvv.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gtiubqylyz.html

[T41] Perl：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtkbzcqtwn.html

print "Hello\n";
来源：http://dali.zhixingplan.top/Article/details/gtubwmlmdb.html

[T42] Perl：变量类型
来源：http://dali.nwbrower.top/Article/details/gtulrutiyr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtzjidrvmd.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gtcoczghqt.html

"值: $a"
来源：http://dali.pycfn.com/Article/details/gtpnzjpzip.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gtbouqrfyd.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gtkvfmapxn.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtxowhhtkr.html

for my $x (@arr) { print $x; }
来源：http://dali.fengsongda.top/Article/details/gtxyzooqkk.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gtvtcpftyu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gtaszsjtbl.html

[T47] Perl：正则捕获
来源：http://dali.sweek.top/Article/details/gtwvosycqb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gtaeuereeh.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gtgftjifzl.html

$s =~ s/old/new/g;
来源：http://dali.yj20258888.top/Article/details/gtsubicmhv.html

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gtliifmrxq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gthzjdzacx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtelaudnqo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gtjnqbepbv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gterxyvmal.html

[T51] Scala：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtcxmybtht.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gthzjtqlui.html

[T52] Scala：变量
来源：http://dali.jinqigufen.top/Article/details/gtlsxibpob.html

val a = 1;  var b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsviuplzl.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtyieviyga.html

s"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtusqukzah.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtblfunbvw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cqqwz.cn/Article/details/gtpkrkvurp.html

[T55] Scala：集合过滤
来源：http://dali.cashguo.top/Article/details/gtfqsinlfb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daxiang520.top/Article/details/gtlrdyzhmu.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gtprthdcpj.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gtdxwkjeuc.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtuvtwedvy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guannengcc.top/Article/details/gtxprzpqxd.html

[T58] Scala：函数定义
来源：http://dali.sufxvd.cn/Article/details/gtsmoncmrc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gogol.net.cn/Article/details/gtlglpuupp.html

[T59] Scala：循环
来源：http://dali.jqgfzy.top/Article/details/gtwfsbfhva.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtpcwhhcpo.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gtunnlsksi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangshuangyany.cn/Article/details/gtqkeqkzjx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpnzklvvi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gtpetprznw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkwwliwwd.html

[U01] Py：创建虚拟环境
来源：http://dali.redwolf501.top/Article/details/gtnqcpgxbw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gzhubu.top/Article/details/gtfyuruewb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gtszqddqcf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sufxvd.cn/Article/details/gtxlqxtoms.html

[U03] Py：加载 .env 配置
来源：http://dali.yj202588.top/Article/details/gtnxhbqxtf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtupylgrhz.html

[U04] Py：变量调试打印
来源：http://dali.chenzaomai.com/Article/details/gtqunrnqra.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gtouzgexqg.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gtzndjyvan.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gthhivbvwc.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gtotegukbx.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gtxadqfnaj.html

[U07] Py：反转字典键值
来源：http://dali.ehwqpu.com/Article/details/gtbjptmmjo.html

{v: k for k, v in d.items()}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgyowadi.html

[U08] Py：展平二维列表
来源：http://dali.guannengcc.top/Article/details/gtlxuknhmk.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gttnhfmusc.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangtech.top/Article/details/gtevudunox.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gtxzcxvmzo.html

[U10] Py：按值排序字典
来源：http://dali.svipenyu.cn/Article/details/gtknvpvziv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fengsongda.top/Article/details/gtcwyfbjyw.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gtchgdfatd.html

(x * 2 for x in arr)
来源：http://dali.jqgufenzy.top/Article/details/gtbqovsmfh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258888.top/Article/details/gtqltwjrtn.html

Counter(arr).most_common(3)
来源：http://dali.xinyue.icu/Article/details/gtscinuvhh.html

[U13] Py：固定长度队列
来源：http://dali.chenjidiqi.icu/Article/details/gtejmxkznt.html

deque(maxlen=10)
来源：http://dali.fengsongda.top/Article/details/gtpdhgrttb.html

[U14] Py：分组收集到列表
来源：http://dali.gotoacloud.top/Article/details/gtbfwayleq.html

defaultdict(list)
来源：http://dali.zhengqikj.top/Article/details/gtcrtqnzsp.html

[U15] Py：高精度计时
来源：http://dali.nanxinkj.top/Article/details/gtcjtgnbbi.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gtvbdhpqhe.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gtewfschrn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jlsjyb.cn/Article/details/gttbshknzs.html

[U17] Py：初始化日志
来源：http://dali.ydzc1.top/Article/details/gtbdwgphgb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjerhrln.html

[U18] Py：预编译正则
来源：http://dali.dianchejie.cn/Article/details/gtalwwinld.html

pat = re.compile(r"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtnslaulku.html

[U19] Py：正则替换带回调
来源：http://dali.zycfv.cn/Article/details/gtksirlctz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xinyue.icu/Article/details/gtdumryilu.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gtgcgellgy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigfzy.top/Article/details/gtqufkyukb.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenzaomai.com/Article/details/gtxjeieozn.html

@contextlib.contextmanager
来源：http://dali.guowangkeji.top/Article/details/gtihgdksrh.html

[U22] Py：矩阵转置
来源：http://dali.iojbl.cn/Article/details/gtzihjrqxh.html

list(zip(*m))
来源：http://dali.jinqigufen.top/Article/details/gtjcgyuurz.html

[U23] Py：分块读取大文件
来源：http://dali.yangfankeji.com/Article/details/gtikwsxlcg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.daria6918.cn/Article/details/gtlzckpyhp.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gtzogwwhhv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtxgwuxocg.html

[U25] Py：CSV 按字典读
来源：http://dali.hysaishi.cn/Article/details/gtjszgabhl.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gtqdparmmh.html

[U26] Py：并发下载
来源：http://dali.sxryk.cn/Article/details/gtvaqotmas.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ppjwa.cn/Article/details/gtgovsemsb.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gtybzdrwrh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuanzx.com/Article/details/gtpyoibrrw.html

[U28] Py：类型别名
来源：http://dali.feifeiyinyue.top/Article/details/gtnymxphba.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gtpngigjnu.html

[U29] Py：属性校验
来源：http://dali.0kj1m.cn/Article/details/gtvwvqgbmv.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gtkiiusdui.html

[U30] Py：数据类
来源：http://dali.vqdsnc.cn/Article/details/gtxgkbhhno.html

@dataclass(slots=True)
来源：http://dali.yj20258888.top/Article/details/gtmmpkrmgx.html

[U31] Py：单测
来源：http://dali.nanxuanxn.top/Article/details/gtavygrpdz.html

python -m pytest -q
来源：http://dali.cucudq.cn/Article/details/gtbvpysrwt.html

[U32] Py：代码格式化
来源：http://dali.snrcjt.cn/Article/details/gtcihhvoow.html

ruff format . && ruff check --fix .
来源：http://dali.jlsjyb.cn/Article/details/gtsrghtdap.html

[U33] Py：打包发布
来源：http://dali.jlsjyb.cn/Article/details/gtlxikahdl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhengqikj.top/Article/details/gtjztwkfqn.html

[U34] Py：判断编码
来源：http://dali.jinqigufen.top/Article/details/gtpnmnxwbv.html

chardet.detect(raw)
来源：http://dali.quarkkingdee.top/Article/details/gtydxtntdi.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gtysrgdkrb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gtoybpujem.html

[U36] Py：定时任务
来源：http://dali.birdmap.top/Article/details/gtbbvqeayh.html

schedule.every(10).minutes.do(job)
来源：http://dali.haohaochexian.top/Article/details/gtvxapwswo.html

[U37] Py：读写 Excel
来源：http://dali.c1oappe.top/Article/details/gtzospuupi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cdnleiting.top/Article/details/gtptvjxwqk.html

[U38] Py：获取脚本所在目录
来源：http://dali.cqqwz.cn/Article/details/gtmjqeieop.html

Path(__file__).resolve().parent
来源：http://dali.nanxuanxn.top/Article/details/gtdfjjfnsb.html

[U39] Py：判断是否在交互环境
来源：http://dali.smart0.xyz/Article/details/gtehxgtrgx.html

sys.stdout.isatty()
来源：http://dali.ydzc1.top/Article/details/gttpyjnmty.html

[U40] Py：打印到标准错误
来源：http://dali.yangfankeji.com/Article/details/gtngjpjbrh.html

print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtmgfvksou.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.9152youxi.cn/Article/details/gtlzdycqbw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cdnleiting.top/Article/details/gtcpwxrgvq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hammf.cn/Article/details/gteuicoyll.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shuidangran.top/Article/details/gtcbonctsp.html

[U43] PHP：声明命名空间
来源：http://dali.yongpay.top/Article/details/gtewtrdgfv.html

namespace App\Http;
来源：http://dali.gaohongyu789.top/Article/details/gtgcstpfyd.html

[U44] PHP：开启严格类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfmeqgmg.html

declare(strict_types=1);
来源：http://dali.jyoumei.cn/Article/details/gtqxdjwrrz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gtarlovdyb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwektvjmd.html

[U46] PHP：可空类型
来源：http://dali.ydzc1.top/Article/details/gtdgenalxx.html

?string $name = null
来源：http://dali.jinqigufen.top/Article/details/gtxqrgcxdt.html

[U47] PHP：联合类型
来源：http://dali.daxiang520.top/Article/details/gtfxzpvtde.html

int|string $id
来源：http://dali.zdqjudy.top/Article/details/gtulmcmxet.html

[U48] PHP：纯枚举
来源：http://dali.jqgfzy.top/Article/details/gttjvvrwop.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ivvv.top/Article/details/gtgcaodbun.html


<!-- 参考信息 -->