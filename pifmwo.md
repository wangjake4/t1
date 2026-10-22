代发 wailian999

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gt2avxgsdvi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gt2mxrtrpua.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gt2wrsclqvi.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gt2dhmzmqzj.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gt2uzazprjz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gt2tooxragw.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmqepbpc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gt2jajsrczx.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gt2hxqonbjc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2opmorgwf.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gt2jmfzklqh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2vswfwkpw.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gt2nndalexs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gt2ytyhkeue.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gt2nlfspdyi.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gt2jvuerjka.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gt2zogzgkat.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gt2tnttehhf.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gt2vzesdnrk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2xktmldlq.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2xyiubwxz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gt2dpzwrzem.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gt2yoylsqud.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gt2ksxscxsp.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gt2oqckdfhi.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gt2cbhxkzha.html

[S44] C++：引用传参
来源：http://dali.shzxlz.cn/Article/details/gt2epiriaxk.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gt2qlkcqwuc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnqhrkr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gt2ypbuqszt.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gt2guqhmybv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gt2pwdmogis.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gt2wfcohidg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gt2laakycjg.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2mgjgksge.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gt2uooaqsoj.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gt2nigsrwvq.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gt2xmvzxrlz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gt2boovjbeg.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsqbkwmu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2gbpcntnq.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gt2kwtlalnj.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gt2zlfeqxtt.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gt2xrpzyzmo.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebxyqfwf.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gt2eajprepj.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gt2zzjykytx.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gt2legomhhy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gt2wcevmlho.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gt2ddtwfjxr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zycfv.cn/Article/details/gt2rybfnmda.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grahnpje.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gt2dkpwjfyr.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qivwgvmh.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gt2ymwvtknh.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gt2jxkwtxfa.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2lxzwvbho.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gt2vjcmxsnu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gt2bglcsldg.html

[S60] C++：遍历并删除元素
来源：http://dali.xylfe.cn/Article/details/gt2vmbexgyl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gt2wqhimtua.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2tbcfkkbe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gt2agvlymdj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rpgrediv.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqytyjtt.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2nqapupst.html

[T02] Kotlin：变量
来源：http://dali.guannengcc.top/Article/details/gt2yytaceuw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gt2xercpwze.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gt2tleskibz.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gt2fkgdtkvx.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gt2klngjvmg.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gt2vhmadgpl.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2jxlgkzzx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zdqjudy.top/Article/details/gt2rfzgxiwr.html

[T06] Kotlin：集合映射
来源：http://dali.birdmap.top/Article/details/gt2dqyqnfaj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2gwfnxpfd.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gt2zyazougz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gt2fuzwmksn.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gt2cxpgtnhb.html

data class User(val name: String, val age: Int)
来源：http://dali.fzhhl.top/Article/details/gt2vqprwmca.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gt2ieoljgxt.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gt2qisduzgu.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gt2joyfkcol.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gt2vtygifsx.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gt2fcgxjdkm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gt2jkkarrtc.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gt2hdkpdygj.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2wjycusvg.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytgzbsyj.html

val m = mapOf("a" to 1)
来源：http://dali.aizwys.cn/Article/details/gt2spqxmizw.html

[T14] Kotlin：循环
来源：http://dali.daria6918.cn/Article/details/gt2bjmxqqna.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2lbyijgjy.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gt2oeqrcxnr.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gt2gjbtmphk.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gt2tcizpbln.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2syouqrjs.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gt2hpdpcecr.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2rxaylduz.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gt2cluyeybf.html

"值: \(b)"
来源：http://dali.guowangkeji.top/Article/details/gt2qtjctxpg.html

[T19] Swift：可选绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zarcoaxc.html

if let n = opt { print(n) }
来源：http://dali.hnqzz.top/Article/details/gt2gzipdhgv.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gt2njsptcyo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gt2fmelansj.html

[T21] Swift：遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2djgedyau.html

for x in a { print(x) }
来源：http://dali.shuidangran.top/Article/details/gt2xxiquyeo.html

[T22] Swift：字典
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utwuqkpu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gt2ujlmqvtn.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gt2spvwsdlj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gt2zjynnohw.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gt2qxhhgdva.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2sbvaaooj.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gt2ismrdmny.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kippccik.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gt2hyyxtghb.html

class A: Base { override func f() {} }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmykouyn.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gt2regcgyox.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmnqcpbf.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gt2dfpmdziz.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxkuswgf.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gt2gxeptpxx.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gt2vsyxhzlk.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gt2ncroybhw.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gt2nvyscdtn.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2qdodxslo.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2mandskvz.html

[T32] Lua：局部变量
来源：http://dali.chenlongwang.top/Article/details/gt2alqttybf.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2gokwcgme.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gt2ursfoqsr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqdwiwcc.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gt2auosljct.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gt2ahtmdpps.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gt2ugsswxtw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gt2thptjafw.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gt2jcwezpwu.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovmqnqjo.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258888.top/Article/details/gt2ogftjkrq.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gt2peyyipac.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gt2axemafnq.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gt2pacjqago.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gt2ahvvdqny.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gt2ufyefgqh.html

[T40] Lua：元表
来源：http://dali.jlsjyb.cn/Article/details/gt2zxxcamom.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gt2toxibkmn.html

[T41] Perl：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppkapgxo.html

print "Hello\n";
来源：http://dali.hfpthk.cn/Article/details/gt2hmdgqomp.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gt2phdmjhsp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gt2vjeiaqel.html

[T43] Perl：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdavtgfy.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gt2dkycyqjg.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gt2okdtstud.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2djyphnvj.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gt2ysychujr.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxinkj.top/Article/details/gt2jtyviwvo.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gt2mnqezpfo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuanzhike.top/Article/details/gt2jqrgrqvd.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gt2agzflfjm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gt2uncikbgu.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbojplcx.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gt2rutumbsz.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gt2jmrqlscf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gt2uaugqcqd.html

[T50] Perl：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2mtvncjsf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fengsongda.top/Article/details/gt2pykvduzq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gt2ebgcvljq.html

[T51] Scala：Hello World
来源：http://dali.yj20258.top/Article/details/gt2mbgwrtsu.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gt2polpulzk.html

[T52] Scala：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwnnamun.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrmqocxy.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttwvwpwk.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxyxcwgc.html

[T54] Scala：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gt2hqvgepbh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gt2xgqilcbp.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2knbxrfeg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daxiang520.top/Article/details/gt2flrpftxe.html

[T56] Scala：样例类
来源：http://dali.havefunace.top/Article/details/gt2zuligbeb.html

case class User(name: String, age: Int)
来源：http://dali.nwbrower.top/Article/details/gt2gfqmrjwv.html

[T57] Scala：模式匹配
来源：http://dali.fengsongda.top/Article/details/gt2tmptbdxo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gt2siowlops.html

[T58] Scala：函数定义
来源：http://dali.9152youxi.cn/Article/details/gt2ynaqyruu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigfzy.top/Article/details/gt2teaulgez.html

[T59] Scala：循环
来源：http://dali.yangfankeji.com/Article/details/gt2dkapwhzt.html

for (i <- 1 to 10) println(i)
来源：http://dali.sysykeji.top/Article/details/gt2uazdooqc.html

[T60] Scala：折叠
来源：http://dali.nanxinkj.top/Article/details/gt2donmluzv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sweek.top/Article/details/gt2oytjgmhf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2vcrwkofs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2iszmypks.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2xawqdsck.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gt2ekjddwqn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.316326.xyz/Article/details/gt2jyhiiqxt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gt2zcyywokp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.redwolf501.top/Article/details/gt2udbsggbg.html

[U03] Py：加载 .env 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgwlyicq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzaibbdj.html

[U04] Py：变量调试打印
来源：http://dali.ppjwa.cn/Article/details/gt2zliqkxjw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gt2lntecxli.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258.top/Article/details/gt2ghldyhuq.html

list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gt2todlnrop.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gt2exltvafq.html

{**a, **b}
来源：http://dali.tanke756.top/Article/details/gt2xnlecycq.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcslywnb.html

{v: k for k, v in d.items()}
来源：http://dali.redwolf501.top/Article/details/gt2wwijoeai.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gt2fsejehku.html

[y for x in nested for y in x]
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvkzyltt.html

[U09] Py：字典取最大值的键
来源：http://dali.redwolf501.top/Article/details/gt2dhhczzfv.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gt2nyzhfsnt.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gt2xhjglvwv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yonumen.top/Article/details/gt2ttramtmx.html

[U11] Py：生成器表达式
来源：http://dali.zhixingplan.top/Article/details/gt2phmjrypz.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gt2hpuoqrmx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gt2oqwykayz.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gt2bsabandu.html

[U13] Py：固定长度队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovzjxlua.html

deque(maxlen=10)
来源：http://dali.hfpthk.cn/Article/details/gt2szbtqnfl.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gt2cdlzzmih.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gt2vmoyerfq.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gt2cymugggz.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gt2rgoubzsr.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gt2lxyplqar.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpgawtlt.html

[U17] Py：初始化日志
来源：http://dali.mhx1999.top/Article/details/gt2dhfryksp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.0kj1m.cn/Article/details/gt2yrervayw.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gt2xrilqxid.html

pat = re.compile(r"\d+")
来源：http://dali.zycfv.cn/Article/details/gt2ycrpcooo.html

[U19] Py：正则替换带回调
来源：http://dali.mhx1999.top/Article/details/gt2rkaiauak.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gt2tcavpclv.html

[U20] Py：缓存函数结果
来源：http://dali.nanxuanxn.top/Article/details/gt2ewudavon.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yvedp.cn/Article/details/gt2dvhboned.html

[U21] Py：自定义上下文管理器
来源：http://dali.xziqi.cn/Article/details/gt2wwsamuqr.html

@contextlib.contextmanager
来源：http://dali.hnqzz.top/Article/details/gt2fmvsmykv.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gt2djumitcv.html

list(zip(*m))
来源：http://dali.yj20258.top/Article/details/gt2tfpbnejp.html

[U23] Py：分块读取大文件
来源：http://dali.yanxiufei.cn/Article/details/gt2zoimblfm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2djhisqsq.html

[U24] Py：路径操作
来源：http://dali.hammf.cn/Article/details/gt2jwtqgkhb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gt2tujvrmgw.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gt2duzncotz.html

csv.DictReader(f)
来源：http://dali.chenzaomai.com/Article/details/gt2kdxmxzco.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gt2qjneduwx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fitxprhz.html

[U27] Py：异步 HTTP
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkglobwh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.meibo888.top/Article/details/gt2psgexoxx.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gt2tfbapqan.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpflqnuj.html

[U29] Py：属性校验
来源：http://dali.zhiwuduotai.top/Article/details/gt2viozgbtw.html

@property 与 @x.setter 配合
来源：http://dali.zdqjudy.top/Article/details/gt2uldomtbv.html

[U30] Py：数据类
来源：http://dali.gaohongyu789.top/Article/details/gt2hxmyxdjf.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gt2uvaocmmr.html

[U31] Py：单测
来源：http://dali.zhengqikj.top/Article/details/gt2xzxvkums.html

python -m pytest -q
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylqjiuzn.html

[U32] Py：代码格式化
来源：http://dali.zycfv.cn/Article/details/gt2fdwamfry.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gt2nbfgidvd.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emgogrdb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gt2scxyhoxa.html

[U34] Py：判断编码
来源：http://dali.yj20258.top/Article/details/gt2rzwwgcmj.html

chardet.detect(raw)
来源：http://dali.iojbl.cn/Article/details/gt2savcjrsq.html

[U35] Py：发送邮件
来源：http://dali.zhixingplan.top/Article/details/gt2vmybqayv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.kuanghao11.cn/Article/details/gt2ufdshxsw.html

[U36] Py：定时任务
来源：http://dali.sysykeji.top/Article/details/gt2axsaauln.html

schedule.every(10).minutes.do(job)
来源：http://dali.sufxvd.cn/Article/details/gt2dcecqyrl.html

[U37] Py：读写 Excel
来源：http://dali.aibaodan.cn/Article/details/gt2uyyazpoz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zdqjudy.top/Article/details/gt2ttjqjewm.html

[U38] Py：获取脚本所在目录
来源：http://dali.sweek.top/Article/details/gt2dzvskxht.html

Path(__file__).resolve().parent
来源：http://dali.yuxming.cn/Article/details/gt2cklopsal.html

[U39] Py：判断是否在交互环境
来源：http://dali.cqqwz.cn/Article/details/gt2fogdhlop.html

sys.stdout.isatty()
来源：http://dali.ivvv.top/Article/details/gt2imvnixbe.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gt2cngpdiob.html

print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gt2sxhtwiek.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guowangkeji.top/Article/details/gt2rfjfgrcw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwhwngbq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpzohnlh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigfzy.top/Article/details/gt2ftvmbaca.html

[U43] PHP：声明命名空间
来源：http://dali.yuanzhike.top/Article/details/gt2xjbdxdrz.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gt2ljugpzhz.html

[U44] PHP：开启严格类型
来源：http://dali.nanxuanxn.top/Article/details/gt2fomjealt.html

declare(strict_types=1);
来源：http://dali.shuidangran.top/Article/details/gt2ukqfzdhq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gt2pvdvkkwd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2pxgpdmah.html

[U46] PHP：可空类型
来源：http://dali.yj20258888.top/Article/details/gt2nmbnytrv.html

?string $name = null
来源：http://dali.havefunace.top/Article/details/gt2dwupkgmk.html

[U47] PHP：联合类型
来源：http://dali.hammf.cn/Article/details/gt2ztqpylct.html

int|string $id
来源：http://dali.hfpthk.cn/Article/details/gt2aaabckzg.html

[U48] PHP：纯枚举
来源：http://dali.tanke756.top/Article/details/gt2zcnzkslg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nwbrower.top/Article/details/gt2fbbqmryw.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gt2jvfxugca.html

public readonly string $name
来源：http://dali.meibo888.top/Article/details/gt2kqncxswm.html

[U50] PHP：构造器属性提升
来源：http://dali.hammf.cn/Article/details/gt2wutkrxna.html

public function __construct(private int $id) {}
来源：http://dali.jinqigufen.top/Article/details/gt2plgflhln.html

[U51] PHP：数组解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpzqusxo.html

[$a, $b] = $arr;
来源：http://dali.fengsongda.top/Article/details/gt2dauupstc.html

[U52] PHP：箭头函数
来源：http://dali.gzhubu.top/Article/details/gt2cpynjzdf.html

$double = fn($x) => $x * 2;
来源：http://dali.shuidangran.top/Article/details/gt2dhoqbmih.html

[U53] PHP：空合并运算符
来源：http://dali.jianghu66.top/Article/details/gt2xvrjkvlj.html

$v = $a ?? $b ?? "default";
来源：http://dali.fengsongda.top/Article/details/gt2ujxcdfuw.html

[U54] PHP：空安全调用
来源：http://dali.xziqi.cn/Article/details/gt2vvkuoqvx.html

$obj?->method()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spqjkijt.html

[U55] PHP：match 表达式
来源：http://dali.yj20258.top/Article/details/gt2ocxxekpz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqbccnmx.html

[U56] PHP：命名参数
来源：http://dali.cashguo.top/Article/details/gt2nbzrojki.html

f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2bdvwzfqv.html


<!-- 参考信息 -->