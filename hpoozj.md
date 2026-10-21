代发 wailian999

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtlhruzhfc.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gtbduyudhj.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gtqtqvadql.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtbqdwjndf.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtakubqwbg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gtgcnnrjgc.html

[S32] C++：字符串
来源：http://dali.sysykeji.top/Article/details/gtftcpzyac.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtpkjsiotc.html

[S33] C++：vector 增删
来源：http://dali.sxryk.cn/Article/details/gtfqdkniip.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtyqnipgnb.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gtumawabvy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gtmisagjhb.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gtvsfaxyxg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtxyjokyqs.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gtfcgprebc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtmxcifcsl.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtkaockfcn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtzubdsbdh.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpnmnhkm.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtmppafmrs.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtresxwjpe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gtjicepleo.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gttrudmecg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtnmclhfmt.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtxqqchahk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gtbbjqixxp.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtgxuxevgx.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gttihrxbfl.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gthmidpfke.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gtbkxjlkua.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtwrdmuwwr.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gtztpscelr.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtwsheskqe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlkarfmp.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gtpxgxlcaj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gtjxrjridv.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gtfdsfgqnf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gtxijwcllo.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtpmzrkybq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gtshwnjson.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gtjqeabylc.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gtbzkshtqp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gteeidftoi.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtonxaseen.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gteiivinoe.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gtlmywdzxb.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gtxxigwitv.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtjcwpojrx.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gteqrsnxrf.html

[S53] C++：移动语义
来源：http://dali.aibaodan.cn/Article/details/gtdcymsfju.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gtixzblops.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtcweubdbz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtjjmjbysn.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gtyqsxwwcc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gtybcvmfvg.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gtpeycdstq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gtzpcudbzz.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gtssfepusn.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtowxkvzrl.html

[S58] C++：命名空间
来源：http://dali.fengsongda.top/Article/details/gtlxfuyljz.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gtifwdtfie.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtalmfuzto.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gteghyfwqj.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gtgyjqzmpe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gtcacpbozt.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgsqapmtl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gtnimmovaw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtckusvsll.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gtnzipjssl.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtuxkfzcja.html

[T02] Kotlin：变量
来源：http://dali.shuidangran.top/Article/details/gtxffompch.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtzikzhact.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtefoednqx.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtjsbbrkfd.html

[T04] Kotlin：空安全
来源：http://dali.hnxiangtu.top/Article/details/gtilsivffx.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtynbhqywd.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtmrlxdgxi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gtenvmwsln.html

[T06] Kotlin：集合映射
来源：http://dali.316326.xyz/Article/details/gtsjvdloyv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtbdvmwoni.html

[T07] Kotlin：集合过滤
来源：http://dali.tanke756.top/Article/details/gtnjiapjzn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gtdipsexjo.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtiuwwrqol.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gthdndbtbp.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gtlhhrxplc.html

fun String.exclaim() = this + "!"
来源：http://dali.cqqwz.cn/Article/details/gtzmgwjvfe.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gtpnmkyxkx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gtavuimfbs.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gtmiirydjz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gtdzetjpsm.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtuukkrnjc.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gthahpwxtx.html

[T13] Kotlin：只读 Map
来源：http://dali.sxryk.cn/Article/details/gtjjxoynpk.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvaebleac.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtupbebcxr.html

for (i in 1..10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtttyartqr.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gtkxaeoliy.html

interface Shape { fun area(): Double }
来源：http://dali.tanke756.top/Article/details/gthjykjtki.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtgspgxfou.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtmsynychi.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gtvibltczi.html

var a = 1;  let b = 2
来源：http://dali.snrcjt.cn/Article/details/gtkrmhizle.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtezsodwvp.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtvsiymjmu.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtifnytsrk.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gtuhncllmn.html

[T20] Swift：数组操作
来源：http://dali.fzhhl.top/Article/details/gtlpwfhiqb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gtyoiejyeo.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gtovlukrie.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gtkxfnjofs.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtbspqmeyn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtyygksnop.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gthwuibcbt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gtwznwxmfk.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtebisdwah.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtwaimflqk.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gtqsprbihl.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtgctxcmmt.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gtpqvzlwik.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gtwtektduw.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gtukolgiin.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtmwxsdumk.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gtxxstoheg.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gtznyqebqb.html

[T29] Swift：guard 提前返回
来源：http://dali.quarkkingdee.top/Article/details/gtuyozvaep.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gtegpchgpe.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gtyzurgjik.html

protocol Shape { func area() -> Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtvejlkstr.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gtqwsnyaxu.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gttvxaxnsc.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gtrilblsfg.html

local a = 1
来源：http://dali.sweek.top/Article/details/gthntpryvo.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gtllwewqkr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gtbbxwzwam.html

[T34] Lua：遍历表
来源：http://dali.shangyingyoupin.top/Article/details/gtgpdbymdx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenlongwang.top/Article/details/gtfjlbcvbe.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gtapwhepte.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gotoacloud.top/Article/details/gtqaixseih.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gtbzqertmd.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gtouucsgbm.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gtrujcgjry.html

"a" .. "b"
来源：http://dali.nwbrower.top/Article/details/gtjwahppij.html

[T38] Lua：条件
来源：http://dali.wangshuangyany.cn/Article/details/gtinuzlnlt.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gtwwbhcyql.html

[T39] Lua：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtdamzvvqg.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gtznpxtvih.html

[T40] Lua：元表
来源：http://dali.chenzaomai.com/Article/details/gtxtrpdydj.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gttzalxzgv.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gtyoblgbvo.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gtjhkqsnuw.html

[T42] Perl：变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gtaaotyseq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.birdmap.top/Article/details/gtdojuwaqa.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtwcdmuzdw.html

"值: $a"
来源：http://dali.yj202588.top/Article/details/gtpovqctlc.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtstggemea.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gtjzfxhrkl.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkxzlsmq.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gtcnheladh.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gthtfcbqkl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gtxpznygjw.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gtjfqbsjoj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpceaxxwb.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdjtvxme.html

$s =~ s/old/new/g;
来源：http://dali.0kj1m.cn/Article/details/gtfczdjerc.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gtailpagli.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtzehepeqd.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtgrrqldhv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gtbofbwnvr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtadutyomd.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtevlffzjl.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtumduemir.html

[T52] Scala：变量
来源：http://dali.cdnleiting.top/Article/details/gtgapfcykp.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtdaaxwukx.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtduminmbg.html

s"值: $b"
来源：http://dali.pycfn.com/Article/details/gtehvgxygf.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtdsqigxao.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigufen.top/Article/details/gtgczvzreh.html

[T55] Scala：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtghwqwbvd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xinyue.icu/Article/details/gtireebwsj.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gtttjaayva.html

case class User(name: String, age: Int)
来源：http://dali.tanke756.top/Article/details/gtamfbzyok.html

[T57] Scala：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gtoalkbzde.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gtlzhhflsd.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gtivggitzc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxuanxn.top/Article/details/gthmugovyt.html

[T59] Scala：循环
来源：http://dali.gogol.net.cn/Article/details/gtnhxfgvmw.html

for (i <- 1 to 10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtqfpstsnu.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gttaudojpw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xylfe.cn/Article/details/gttulpswta.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttjmanqru.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gtouutygzn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbwujtrvh.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpihvysgn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yangfankeji.com/Article/details/gtbaypihjs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gtywoxlxfj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhengqikj.top/Article/details/gtyydzkibs.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtexpasulq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gtutznxqvf.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gtmjuphomi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gthaffvtai.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtfyouiexk.html

list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gtbquwicvk.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdjtlirg.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafjzqvev.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmsomqkw.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdgbskhr.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gtilhhcxre.html

[y for x in nested for y in x]
来源：http://dali.jianghu66.top/Article/details/gtnsdmlllk.html

[U09] Py：字典取最大值的键
来源：http://dali.yonumen.top/Article/details/gtbztwnrgl.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gtkjeutqdl.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gthymwrbym.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guannengcc.top/Article/details/gtmitznujg.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gtxhhekpmw.html

(x * 2 for x in arr)
来源：http://dali.gaohongyu789.top/Article/details/gtnmfwecuv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xylfe.cn/Article/details/gtznfvopyt.html

Counter(arr).most_common(3)
来源：http://dali.guannengcc.top/Article/details/gtyhkauylg.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gtxyqwrgim.html

deque(maxlen=10)
来源：http://dali.zycfv.cn/Article/details/gtadsejale.html

[U14] Py：分组收集到列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcoxkezj.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtumyoyano.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gtowgtnccu.html

t = time.perf_counter()
来源：http://dali.snrcjt.cn/Article/details/gtlwcaslvo.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklsyjoeo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258.top/Article/details/gtvaoqkxpk.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gtgqynckar.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hywenlv.cn/Article/details/gtwrxeahoa.html

[U18] Py：预编译正则
来源：http://dali.fengsongda.top/Article/details/gtbdgkccjb.html

pat = re.compile(r"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtwwqajzhm.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gtfgdjrypz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yanxiufei.cn/Article/details/gtmmvfxrvu.html

[U20] Py：缓存函数结果
来源：http://dali.c1oappe.top/Article/details/gtqqscjfdr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yvedp.cn/Article/details/gturjiqvsb.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gtcndxrvsh.html

@contextlib.contextmanager
来源：http://dali.quarkkingdee.top/Article/details/gteclxuuzm.html

[U22] Py：矩阵转置
来源：http://dali.gogol.net.cn/Article/details/gtddsqirsz.html

list(zip(*m))
来源：http://dali.snrcjt.cn/Article/details/gtfwztxayv.html

[U23] Py：分块读取大文件
来源：http://dali.xuanzx.com/Article/details/gtlvrcynsg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gotoacloud.top/Article/details/gtloczqdgt.html

[U24] Py：路径操作
来源：http://dali.sufxvd.cn/Article/details/gtdqqolqma.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjmrxdgh.html

[U25] Py：CSV 按字典读
来源：http://dali.hnxiangtu.top/Article/details/gthsrykwfo.html

csv.DictReader(f)
来源：http://dali.jinghuilouyu.cn/Article/details/gtefpcmqfe.html

[U26] Py：并发下载
来源：http://dali.andypj.xyz/Article/details/gtumoijqem.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guowangkeji.top/Article/details/gttttjrfqu.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwfelgpo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.havefunace.top/Article/details/gtxnlcrwtd.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gtgwjvcfyd.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gtuivlsxxf.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gtzjndxpcl.html

@property 与 @x.setter 配合
来源：http://dali.ivvv.top/Article/details/gtwlckyqsi.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gthecdzsol.html

@dataclass(slots=True)
来源：http://dali.mhx1999.top/Article/details/gtilytduad.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gtpuhcfven.html

python -m pytest -q
来源：http://dali.cdnleiting.top/Article/details/gthvimtnmn.html

[U32] Py：代码格式化
来源：http://dali.nwbrower.top/Article/details/gtmrmsgbfp.html

ruff format . && ruff check --fix .
来源：http://dali.hammf.cn/Article/details/gtmbyclhad.html

[U33] Py：打包发布
来源：http://dali.nanxuanxn.top/Article/details/gtcekxgqqi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gtiicclzkq.html

[U34] Py：判断编码
来源：http://dali.smart0.xyz/Article/details/gtocnaqmwi.html

chardet.detect(raw)
来源：http://dali.nanxinkj.top/Article/details/gtqfadrqra.html

[U35] Py：发送邮件
来源：http://dali.tian-w.cn/Article/details/gtxjrruczj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gtdqfeshkb.html

[U36] Py：定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfrjtlos.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhongyouzk.top/Article/details/gtlmhnbecj.html

[U37] Py：读写 Excel
来源：http://dali.sufxvd.cn/Article/details/gtxweusucc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shzxlz.cn/Article/details/gtnubleews.html

[U38] Py：获取脚本所在目录
来源：http://dali.pycfn.com/Article/details/gtwioeymxi.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gtxgowcmko.html

[U39] Py：判断是否在交互环境
来源：http://dali.yangfankeji.com/Article/details/gtwdcxxqcw.html

sys.stdout.isatty()
来源：http://dali.xuetiantiany.cn/Article/details/gtwktevlmh.html

[U40] Py：打印到标准错误
来源：http://dali.pengpengdd.cyou/Article/details/gtcarnagxw.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gttjyxrlve.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gotoacloud.top/Article/details/gtsmpgdwvy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbyshkrw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gtqgcnbnqd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxuanxn.top/Article/details/gtyzdsvwwz.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gtssmieqdl.html

namespace App\Http;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbzmzcab.html

[U44] PHP：开启严格类型
来源：http://dali.wangshuangyany.cn/Article/details/gtccrnzpgg.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gtwsuobtec.html

[U45] PHP：类型声明与返回类型
来源：http://dali.bjfxy.top/Article/details/gthoswuhpp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtqkzexgfh.html

[U46] PHP：可空类型
来源：http://dali.nanxinkj.top/Article/details/gtszwwumdk.html

?string $name = null
来源：http://dali.aibaodan.cn/Article/details/gtktlbnueg.html

[U47] PHP：联合类型
来源：http://dali.xuanzx.com/Article/details/gtphvnnpxu.html

int|string $id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdniomxso.html

[U48] PHP：纯枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhnxbxvv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guowangkeji.top/Article/details/gtexvrqshw.html

[U49] PHP：只读属性
来源：http://dali.hfpthk.cn/Article/details/gthiztoldo.html

public readonly string $name
来源：http://dali.xylfe.cn/Article/details/gtltbvadbe.html

[U50] PHP：构造器属性提升
来源：http://dali.ivvv.top/Article/details/gtbagirpcw.html

public function __construct(private int $id) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsalxszhz.html

[U51] PHP：数组解构
来源：http://dali.nanxinkj.top/Article/details/gtocyyvosa.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gtoysscvzm.html

[U52] PHP：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gthtkmylwz.html

$double = fn($x) => $x * 2;
来源：http://dali.cashguo.top/Article/details/gtpdsstufy.html

[U53] PHP：空合并运算符
来源：http://dali.sweek.top/Article/details/gtcmhouebz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gtowsrtbjt.html

[U54] PHP：空安全调用
来源：http://dali.iojbl.cn/Article/details/gtcxmswnkd.html

$obj?->method()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkiglutz.html


<!-- 参考信息 -->