代发 wailian999

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gtclhggftc.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gtpvamvszw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtiuirprkv.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtyiooodwc.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gthcpenzsh.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gtfgvcztrq.html

#endif
来源：http://dali.sysykeji.top/Article/details/gtqijegxbs.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtbwejesiz.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gtxoezznfn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtvbezcoco.html

[S32] C++：字符串
来源：http://dali.gogol.net.cn/Article/details/gtyeaimoor.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gttqxvcfan.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gtwldetdyx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gtxgehxgbt.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtmvanaybw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gtirjvnddj.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gtddthhrzi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtpbstykmb.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtxjpuiymr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtciwpylbp.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gtimbsvfwo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.vqdsnc.cn/Article/details/gtbovzfzif.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gtlvhzapxw.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtncmtfomo.html

[S39] C++：自定义比较器排序
来源：http://dali.fengsongda.top/Article/details/gtzgodqwfj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gtuenlrnjo.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gtcdvgxpkx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gtigvsrycq.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gtrqcrxqyg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.havefunace.top/Article/details/gttmmvkzlq.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gtebdevhqg.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtwneszigl.html

[S43] C++：智能指针
来源：http://dali.nanxinkj.top/Article/details/gtnyqzkczs.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gtxxusfege.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gtmkwisywv.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbalheigk.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtmcinavaz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtawgboeqz.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gtrcfcwatb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.vqdsnc.cn/Article/details/gtmydmoaph.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gtbipqclhq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtvjywsqhr.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqtijvjd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gtkzikurir.html

while (std::getline(in, line)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtcvtxyuck.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtikkmeljd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtxyektecj.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gthlaumwzf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtzrheoxcg.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtdryfxink.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gtxeyvcvrx.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtymfzypns.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gtzpucvfda.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gtlaiyjbjb.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtslygynsn.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gtxfmdnxax.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gtqcrudssh.html

[S55] C++：结构化绑定
来源：http://dali.bjfxy.top/Article/details/gtwqualqpu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gtvjbxhovg.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtwdbctbwu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtyfmoqqjy.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtaxlzmtuf.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gtpuemjznr.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gtszcxgtas.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtjmfujclt.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtkbldyzhr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtouzvcxup.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtmzwncijt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gtgscupffe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtncmmihcf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtjcucpqrz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtleyrjime.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtcleizxpl.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gttgfvywdb.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gttqnvywud.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gtsjvqlcfu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gtuzfltrss.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtfxfwxceg.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gtyrtefnyd.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtvmjcxpxd.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtybmgtome.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gtmexfxtek.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtwsxoeuzj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtdrctneiw.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtuhqllssn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.svipenyu.cn/Article/details/gtfuphpiyr.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gtoxjwvhli.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtfwutsiym.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtlxfzpbtr.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gtygvdpejp.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gtixbmyffc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gtimvgmxoz.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gtwrmayvvv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gtccjhkuya.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gtunfelzac.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtoaniibab.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gttiadeaoi.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gtglxtlaby.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gtgmgmhncx.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtbdbgejoq.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxuvgxvk.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gtltmlcaji.html

[T16] Swift：Hello World
来源：http://dali.yuxming.cn/Article/details/gtonyogbyr.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtugbfyvhn.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gtvaqgendz.html

var a = 1;  let b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtlipqsbnk.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtelhsczdm.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtkrqpgopl.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtdbaahszu.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gtzqplqycq.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtqolpxsxv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gttoyaqkeu.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gtnglzfdrz.html

for x in a { print(x) }
来源：http://dali.cheryme.top/Article/details/gtvrzctahz.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtyuazebdd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gteecmugox.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gtcfawxxcx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gtbnvtexmr.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotvbignt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gthxxmqvsy.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtrhgvup.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gtxttiwysv.html

[T26] Swift：类与重写
来源：http://dali.mhx1999.top/Article/details/gtxkdjzvtm.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtiwawhxsh.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gtajziricl.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtkzuhgxfx.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gtnwhlqscl.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gtxidslzly.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gteufjcdno.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gtxphihqqx.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gtusgfmbmc.html

protocol Shape { func area() -> Double }
来源：http://dali.smart0.xyz/Article/details/gtwvyhmgbz.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtabbdnpgj.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gttvphanrq.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtdopuplgk.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gtxukoewiw.html

[T33] Lua：表（数组）
来源：http://dali.316326.xyz/Article/details/gtbtjkygbh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gtrkzszvzb.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gtjxmdctrd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.9152youxi.cn/Article/details/gtckaehcxa.html

[T35] Lua：字典表
来源：http://dali.shuidangran.top/Article/details/gttwedtksm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtiutgkuot.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gtgpcunqid.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gtkddfgxnx.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazewbwbz.html

"a" .. "b"
来源：http://dali.meibo888.top/Article/details/gttoxnpliw.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gtvvenzsgl.html

if x > 0 then print("正") end
来源：http://dali.jinqigfzy.top/Article/details/gtytbigdaw.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtumeowhqh.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiesyxhra.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gtajkqvxil.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtbjhjjsob.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gtccmtwunn.html

print "Hello\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtdrdtikiu.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gtodimefwl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gtpjchamua.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gtggkwzvtr.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gttdqyipjc.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gtomkkrxsr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhixingplan.top/Article/details/gtcjmuxrou.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gtqnuogyda.html

for my $x (@arr) { print $x; }
来源：http://dali.tian-w.cn/Article/details/gtnfcekibt.html

[T46] Perl：哈希操作
来源：http://dali.cqqwz.cn/Article/details/gtwiyrhjvw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gtxgvnghrj.html

[T47] Perl：正则捕获
来源：http://dali.yanxiufei.cn/Article/details/gtxkjgwsrp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gotoacloud.top/Article/details/gtmyxxdiua.html

[T48] Perl：正则替换
来源：http://dali.bjfxy.top/Article/details/gtkvpiovuh.html

$s =~ s/old/new/g;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbuesahl.html

[T49] Perl：函数
来源：http://dali.gzhubu.top/Article/details/gtxlqusetb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtmklajsqg.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtwxdjyiah.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxinkj.top/Article/details/gtjjbrpram.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gttnvzatsv.html

[T51] Scala：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfokmvof.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtkylrrfnn.html

[T52] Scala：变量
来源：http://dali.guannengcc.top/Article/details/gtvjbdsvke.html

val a = 1;  var b = 2
来源：http://dali.yvedp.cn/Article/details/gtoterfzbg.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtvggcpnnw.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtqripyzpd.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gtlvpasusw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlvyjkubw.html

[T55] Scala：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtmlezqbgv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenzaomai.com/Article/details/gtydwcgdam.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gtolxrbgaw.html

case class User(name: String, age: Int)
来源：http://dali.cashguo.top/Article/details/gtgbjknyba.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtyopkhtyw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtaowrwjac.html

[T58] Scala：函数定义
来源：http://dali.yongpay.top/Article/details/gtejuvaxix.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gtjtpcfmuk.html

[T59] Scala：循环
来源：http://dali.shuidangran.top/Article/details/gtugtyxlku.html

for (i <- 1 to 10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpaysxvm.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gtgmeibldp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnqzz.top/Article/details/gtsfnjgzmi.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthychlidx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtbkgajnax.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgtmcxvce.html

[U01] Py：创建虚拟环境
来源：http://dali.9152youxi.cn/Article/details/gtawrobrve.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gtnogfofbb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shangyingyoupin.top/Article/details/gtusvqknjs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gtahlrmdgo.html

[U03] Py：加载 .env 配置
来源：http://dali.redwolf501.top/Article/details/gtevmxipie.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gtumaiokzi.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gtzswsqdhs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gotoacloud.top/Article/details/gtmsleejta.html

[U05] Py：列表去重且保序
来源：http://dali.sysykeji.top/Article/details/gtlmjxcgff.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtnjlnmhka.html

[U06] Py：合并两个字典
来源：http://dali.mhx1999.top/Article/details/gtummnrmij.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gtcpsbmlkh.html

[U07] Py：反转字典键值
来源：http://dali.sweek.top/Article/details/gtwrngicbr.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzeccryh.html

[U08] Py：展平二维列表
来源：http://dali.ydzc1.top/Article/details/gtxseslvaq.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gthvsikyef.html

[U09] Py：字典取最大值的键
来源：http://dali.nwbrower.top/Article/details/gtqitblcgk.html

max(d, key=d.get)
来源：http://dali.yueranfly.top/Article/details/gterupwmiq.html

[U10] Py：按值排序字典
来源：http://dali.snrcjt.cn/Article/details/gtvwxqilus.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cqqwz.cn/Article/details/gtbfpfahmf.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtakjygikj.html

(x * 2 for x in arr)
来源：http://dali.hnxiangtu.top/Article/details/gtfbnbzzks.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cucudq.cn/Article/details/gtihmifkau.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gtfplncvtw.html

[U13] Py：固定长度队列
来源：http://dali.daria6918.cn/Article/details/gteppirxuu.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gtluebjuog.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpghbkdbp.html

defaultdict(list)
来源：http://dali.zycfv.cn/Article/details/gtithrlhnr.html

[U15] Py：高精度计时
来源：http://dali.smart0.xyz/Article/details/gturbilzlv.html

t = time.perf_counter()
来源：http://dali.bjfxy.top/Article/details/gtinngbaje.html

[U16] Py：命令行参数解析
来源：http://dali.ybcxt.top/Article/details/gtcfjgecnz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daria6918.cn/Article/details/gtafncstuj.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtuujishmc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258.top/Article/details/gtbvgcxlse.html

[U18] Py：预编译正则
来源：http://dali.xuetiantiany.cn/Article/details/gtzabrcivz.html

pat = re.compile(r"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtocxvburo.html

[U19] Py：正则替换带回调
来源：http://dali.nwbrower.top/Article/details/gtzzpfhjue.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gtecmsgekk.html

[U20] Py：缓存函数结果
来源：http://dali.zhongyouzk.top/Article/details/gtdpjydsjm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guowangkeji.top/Article/details/gtleobsfrl.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gtqdhxshzl.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gtzkbsdijx.html

[U22] Py：矩阵转置
来源：http://dali.gaohongyu789.top/Article/details/gtakwthvdz.html

list(zip(*m))
来源：http://dali.jqgufenzy.top/Article/details/gtagtlgxnb.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtvpmzzvyv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yangfankeji.com/Article/details/gtzbzfqyim.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyibnvan.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtmwdbhxqx.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxinkj.top/Article/details/gtmbirzcep.html

csv.DictReader(f)
来源：http://dali.jlsjyb.cn/Article/details/gtxzicvyka.html

[U26] Py：并发下载
来源：http://dali.kuanghao11.cn/Article/details/gtmrheqaqj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yangfankeji.com/Article/details/gtgqpjtiiw.html

[U27] Py：异步 HTTP
来源：http://dali.sweek.top/Article/details/gtihuycusd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gtzruqgtmw.html

[U28] Py：类型别名
来源：http://dali.wangdashe.top/Article/details/gtrhdjybyh.html

UserId = int
来源：http://dali.xylfe.cn/Article/details/gtfnmlyyid.html

[U29] Py：属性校验
来源：http://dali.jinqigfzy.top/Article/details/gtpcuflxei.html

@property 与 @x.setter 配合
来源：http://dali.andypj.xyz/Article/details/gtjvmqiivk.html

[U30] Py：数据类
来源：http://dali.yongpay.top/Article/details/gtrdgydfsb.html

@dataclass(slots=True)
来源：http://dali.cqqwz.cn/Article/details/gtlgamwzce.html

[U31] Py：单测
来源：http://dali.gotoacloud.top/Article/details/gtmtnpvrok.html

python -m pytest -q
来源：http://dali.vqdsnc.cn/Article/details/gtpzzikobn.html

[U32] Py：代码格式化
来源：http://dali.andypj.xyz/Article/details/gturkeufqt.html

ruff format . && ruff check --fix .
来源：http://dali.yonumen.top/Article/details/gtxqoiddmk.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gtbexblynr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yuanzhike.top/Article/details/gtbyvsxnoz.html

[U34] Py：判断编码
来源：http://dali.cdnleiting.top/Article/details/gtxehzwfvr.html

chardet.detect(raw)
来源：http://dali.yvedp.cn/Article/details/gtlvkzlcfy.html

[U35] Py：发送邮件
来源：http://dali.bjfxy.top/Article/details/gtfbjucuxy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhengqikj.top/Article/details/gtwobcckop.html

[U36] Py：定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylmyikxo.html

schedule.every(10).minutes.do(job)
来源：http://dali.9152youxi.cn/Article/details/gtcwnqhvhb.html

[U37] Py：读写 Excel
来源：http://dali.sweek.top/Article/details/gtrtxsvjli.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guowangkeji.top/Article/details/gtjvgddmaj.html

[U38] Py：获取脚本所在目录
来源：http://dali.c1oappe.top/Article/details/gturgtfmqn.html

Path(__file__).resolve().parent
来源：http://dali.quarkkingdee.top/Article/details/gtmczyxixh.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtarrcddhi.html

sys.stdout.isatty()
来源：http://dali.wangdashe.top/Article/details/gtwbqzkebb.html

[U40] Py：打印到标准错误
来源：http://dali.yuxming.cn/Article/details/gtzwukxfot.html

print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gttrhijenc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jyoumei.cn/Article/details/gtqumvztnd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhengqikj.top/Article/details/gtzfiobbza.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gogol.net.cn/Article/details/gtdsachhdj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxuanxn.top/Article/details/gtipaesvun.html

[U43] PHP：声明命名空间
来源：http://dali.jyoumei.cn/Article/details/gtbisgpaqx.html

namespace App\Http;
来源：http://dali.sxryk.cn/Article/details/gtrxrjlycc.html

[U44] PHP：开启严格类型
来源：http://dali.yuxming.cn/Article/details/gtuyobomxe.html

declare(strict_types=1);
来源：http://dali.sweek.top/Article/details/gtjvoeoozw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yueranfly.top/Article/details/gtnbumqbjk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfiosadi.html

[U46] PHP：可空类型
来源：http://dali.yongpay.top/Article/details/gtumnfgeae.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gtudplhwey.html

[U47] PHP：联合类型
来源：http://dali.c1oappe.top/Article/details/gtetorxkja.html

int|string $id
来源：http://dali.tanke756.top/Article/details/gtenrfrayx.html

[U48] PHP：纯枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtobtfgpie.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nwbrower.top/Article/details/gtddhecrgl.html

[U49] PHP：只读属性
来源：http://dali.cheryme.top/Article/details/gtznqychhy.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gtuazvihmc.html

[U50] PHP：构造器属性提升
来源：http://dali.ehwqpu.com/Article/details/gttbbeubwj.html

public function __construct(private int $id) {}
来源：http://dali.9152youxi.cn/Article/details/gtzmbarofd.html

[U51] PHP：数组解构
来源：http://dali.feifeiyinyue.top/Article/details/gtdfdquafq.html

[$a, $b] = $arr;
来源：http://dali.yanxiufei.cn/Article/details/gtsnpjijvh.html

[U52] PHP：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gtafoczski.html

$double = fn($x) => $x * 2;
来源：http://dali.zdqjudy.top/Article/details/gtcuwznidr.html


<!-- 参考信息 -->