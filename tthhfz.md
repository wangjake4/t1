代发 wailian999

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gtgsersglg.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gtmfjnumyt.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksgpnzpa.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gthhzpopee.html

#include <iostream>
来源：http://dali.cdnleiting.top/Article/details/gtaggxhkoh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvwaemuk.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gthkhejkcc.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gtbidwgvtn.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblkhfuoe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gtwfikdvsh.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtkslqzoyp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gtjhhyoowf.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gtyenwotxt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtmrjgylnw.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtjbacchin.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtifwosoby.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtlejssxkv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gtdxkyxlja.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtzeljcsch.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gtycwcojra.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtcpkrhsjd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gtyjihcknd.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gthkngrykq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtpusalvux.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtsjkxfdfr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gtiqgqbwhm.html

[S42] C++：继承与虚函数
来源：http://dali.fzhhl.top/Article/details/gtvhnaglqf.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gtmispjpir.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtchkuwuat.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gtfcqqkgch.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtpfklrcdb.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtemjzbpel.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtrtwondpv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtgrgyfsut.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuhjxvqi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gtaputtwxp.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gtfcsuoeoc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gtcdtdwgkr.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtxhmtrtfz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtofftgyrv.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtksyikydy.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gtudorjcbn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gtefscqija.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtmrxfoaai.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbvhelqv.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gtneotkyiu.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gtmhvxrouz.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gtwdqmvetr.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtljaztlgp.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gtwwekdxzk.html

std::vector<int> w = std::move(v);
来源：http://dali.tian-w.cn/Article/details/gtjevnxelt.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtabcmpniq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtrhidichw.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtmnbelffq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gtbuqqvbrg.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gtndkpyxul.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gtuaiivlex.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtzdwrhdab.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtiyhxcobb.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtocpomtei.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gtpaernzlv.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gtnhdsjjmp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gtxpaofczj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtzcfyqcqr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gtitutthpi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbprzrxma.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gttaseuvul.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtadgoyzlw.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtllfptxat.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtzexypwpe.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtrxdmegql.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gtacimpdnl.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gtpcypzpvo.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtrfhlyach.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gtznhzaguo.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtenxddevn.html

[T05] Kotlin：when 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsufpnfqo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pycfn.com/Article/details/gtgxzqwrne.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gtwsjeeqxy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugsrphvo.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtfkvzdovw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtglklktwq.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gtrppfrcxw.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixnraxci.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtgzwymckt.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gteiebjdjx.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gtzgidwbqn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiojxuitn.html

[T11] Kotlin：协程
来源：http://dali.cashguo.top/Article/details/gtawirwkdd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gtlddpekqb.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmemtqdoi.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtajziswmw.html

[T13] Kotlin：只读 Map
来源：http://dali.hywenlv.cn/Article/details/gtpmgasdvj.html

val m = mapOf("a" to 1)
来源：http://dali.c1oappe.top/Article/details/gtrzomkfyk.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtdlsoqtda.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzihxzlrr.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gtcoflqrct.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtbdwgbhvn.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtjelmuoeh.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtklecbogc.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gtffdxxlwl.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gtighnqlep.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtxdkyseqi.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtjfilmxsw.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gtstvsnrpk.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gtzndakshf.html

[T20] Swift：数组操作
来源：http://dali.ydzc1.top/Article/details/gtxydpxbmj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gtscfpdonh.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gtsqgllgng.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyjyjuhh.html

[T22] Swift：字典
来源：http://dali.chenlongwang.top/Article/details/gthhwaopfw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gtsfzrekgh.html

[T23] Swift：函数
来源：http://dali.cucudq.cn/Article/details/gtlhzilphg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtwpskeyjq.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gtlbjhgpth.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtipeqkpbm.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gtwyrxejpp.html

struct P { var x: Int }
来源：http://dali.zhengqikj.top/Article/details/gtgsosltkx.html

[T26] Swift：类与重写
来源：http://dali.shangyingyoupin.top/Article/details/gtwnyodqye.html

class A: Base { override func f() {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtzqscyfrq.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gtohhmxapa.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gtiyvruczd.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gtgvorftnj.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gtretimzdu.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtivmobjdi.html

guard let x = opt else { return }
来源：http://dali.chenzaomai.com/Article/details/gtpxwaopnb.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gtbumczbhf.html

protocol Shape { func area() -> Double }
来源：http://dali.hnxiangtu.top/Article/details/gterqhketn.html

[T31] Lua：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtjlgmcoyd.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtazzvwbai.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gtzkbajmfy.html

local a = 1
来源：http://dali.vqdsnc.cn/Article/details/gtezvibxox.html

[T33] Lua：表（数组）
来源：http://dali.nanxuanxn.top/Article/details/gtshjixrwz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gtdrmihynx.html

[T34] Lua：遍历表
来源：http://dali.daxiang520.top/Article/details/gtechmnjeg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjkchpnx.html

[T35] Lua：字典表
来源：http://dali.vqdsnc.cn/Article/details/gtfaphvnof.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gtjewqmztl.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gtewueyvjo.html

function add(a, b) return a + b end
来源：http://dali.zhoulong.xyz/Article/details/gtghynznnr.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtrzomlhyr.html

"a" .. "b"
来源：http://dali.yueranfly.top/Article/details/gtfljwhgpz.html

[T38] Lua：条件
来源：http://dali.jianghu66.top/Article/details/gtqskdbhut.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gtgizjgzok.html

[T39] Lua：模式匹配
来源：http://dali.fengsongda.top/Article/details/gtlduvjpay.html

string.find(s, "%d+")
来源：http://dali.jlsjyb.cn/Article/details/gtwihbmwgv.html

[T40] Lua：元表
来源：http://dali.jinqigufen.top/Article/details/gtgxkzhgyx.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gtwuyaaekl.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gthpfvyfuu.html

print "Hello\n";
来源：http://dali.yangfankeji.com/Article/details/gtffjhtntl.html

[T42] Perl：变量类型
来源：http://dali.yuanzhike.top/Article/details/gtvxlxrmvv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gtextcotmt.html

[T43] Perl：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtemtvorif.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gttsiydtfa.html

[T44] Perl：条件
来源：http://dali.daria6918.cn/Article/details/gtunwoezrq.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gtmhishull.html

[T45] Perl：数组遍历
来源：http://dali.cdnleiting.top/Article/details/gtbmbetvzb.html

for my $x (@arr) { print $x; }
来源：http://dali.c1oappe.top/Article/details/gtlyhecahk.html

[T46] Perl：哈希操作
来源：http://dali.shzxlz.cn/Article/details/gtjklzxzsg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gtsnbqfriy.html

[T47] Perl：正则捕获
来源：http://dali.cqqwz.cn/Article/details/gtrypcexwe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gthnkbbvwe.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gtxosevoos.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtpkybmcro.html

[T49] Perl：函数
来源：http://dali.haohaochexian.top/Article/details/gtszxudqsw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gthglxcblm.html

[T50] Perl：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtzohwqsxs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gtggbxkskg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtvbbblbid.html

[T51] Scala：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtaeoquibw.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtihjohjtd.html

[T52] Scala：变量
来源：http://dali.zycfv.cn/Article/details/gtgxbjgylu.html

val a = 1;  var b = 2
来源：http://dali.cdnleiting.top/Article/details/gtlycrtmhr.html

[T53] Scala：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtruaxsrud.html

s"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgtxidda.html

[T54] Scala：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gthxxvurlu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigfzy.top/Article/details/gthdobcpdk.html

[T55] Scala：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtgivfbgth.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yangfankeji.com/Article/details/gtbfapbrtn.html

[T56] Scala：样例类
来源：http://dali.cdnleiting.top/Article/details/gtyurrbnxc.html

case class User(name: String, age: Int)
来源：http://dali.yuxming.cn/Article/details/gtnlbqjivw.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtqlrezumd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daxiang520.top/Article/details/gtshklswxn.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtgbytvjob.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.quarkkingdee.top/Article/details/gtdfqpjtiy.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gtntrtpmgc.html

for (i <- 1 to 10) println(i)
来源：http://dali.ivvv.top/Article/details/gtxgvxpwys.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gtxapbzhdr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gttpcqacif.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtracyvefl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxecsgjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjlvrkbgd.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gtqoyfqxpv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gtagobjgil.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhiwuduotai.top/Article/details/gtkvtfikff.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dashuyun.cn/Article/details/gtvztjjylp.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigufen.top/Article/details/gthxgzsqpy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gtzefkhzox.html

[U04] Py：变量调试打印
来源：http://dali.tian-w.cn/Article/details/gtixmxggod.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shangyingyoupin.top/Article/details/gtxokgouuh.html

[U05] Py：列表去重且保序
来源：http://dali.hywenlv.cn/Article/details/gtkwaqsnyj.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtaiedpkat.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gtlmiekypm.html

{**a, **b}
来源：http://dali.gotoacloud.top/Article/details/gttbczcfsl.html

[U07] Py：反转字典键值
来源：http://dali.chenlongwang.top/Article/details/gtorvmpsxp.html

{v: k for k, v in d.items()}
来源：http://dali.hywenlv.cn/Article/details/gtltejooef.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gtnqrpzigi.html

[y for x in nested for y in x]
来源：http://dali.fengsongda.top/Article/details/gtdhmujoye.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gtqnjwxxjt.html

max(d, key=d.get)
来源：http://dali.jqgufenzy.top/Article/details/gtdgshtbsn.html

[U10] Py：按值排序字典
来源：http://dali.ydzc1.top/Article/details/gtupoxmlpq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhongyouzk.top/Article/details/gtebogyxor.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gtkuhaeqhw.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gttfwcehdz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnxiangtu.top/Article/details/gtlooszuvs.html

Counter(arr).most_common(3)
来源：http://dali.jiagoushi.top/Article/details/gtjohmrwvs.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gtxuyuomdt.html

deque(maxlen=10)
来源：http://dali.cucudq.cn/Article/details/gtzunretcc.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gtdeuwlayc.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtlizscaba.html

[U15] Py：高精度计时
来源：http://dali.jianghu66.top/Article/details/gtcdxjapjr.html

t = time.perf_counter()
来源：http://dali.smart0.xyz/Article/details/gtdawyfxkz.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gtmofslulw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gtsrnitfmv.html

[U17] Py：初始化日志
来源：http://dali.gzhubu.top/Article/details/gtgownexyw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gthpvmehqq.html

[U18] Py：预编译正则
来源：http://dali.zycfv.cn/Article/details/gtiiajdsho.html

pat = re.compile(r"\d+")
来源：http://dali.pycfn.com/Article/details/gtwlnkhewc.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gtyslnmdhh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gtuqttywme.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gtbwsxwojy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxinkj.top/Article/details/gtfnnqwqyz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zycfv.cn/Article/details/gtchfmquwh.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gtezhorlel.html

[U22] Py：矩阵转置
来源：http://dali.chenlongwang.top/Article/details/gtihsyioqi.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gtgapdpull.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gtmdredmxo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gtbitevrux.html

[U24] Py：路径操作
来源：http://dali.jianghu66.top/Article/details/gtzyvltmdk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtvelxgefy.html

[U25] Py：CSV 按字典读
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegbckgxf.html

csv.DictReader(f)
来源：http://dali.xuanzx.com/Article/details/gtpkgrgzsw.html

[U26] Py：并发下载
来源：http://dali.shzxlz.cn/Article/details/gtdarjvuke.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sxryk.cn/Article/details/gtrlcceajr.html

[U27] Py：异步 HTTP
来源：http://dali.yangfankeji.com/Article/details/gtzeuwesvm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.vqdsnc.cn/Article/details/gtphpjiqgk.html

[U28] Py：类型别名
来源：http://dali.xylfe.cn/Article/details/gtrnvaepbc.html

UserId = int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtcmlvjp.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gtosxnyqlr.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gtwrxjatyy.html

[U30] Py：数据类
来源：http://dali.jiagoushi.top/Article/details/gtsizkmssj.html

@dataclass(slots=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtfiaxnfji.html

[U31] Py：单测
来源：http://dali.yj20258888.top/Article/details/gtpxsqtone.html

python -m pytest -q
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwojxpjb.html

[U32] Py：代码格式化
来源：http://dali.hfpthk.cn/Article/details/gtjlykmhia.html

ruff format . && ruff check --fix .
来源：http://dali.chenlongwang.top/Article/details/gtokbnxzps.html

[U33] Py：打包发布
来源：http://dali.ppjwa.cn/Article/details/gtowlgfeeb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhongyouzk.top/Article/details/gtwdvmogbf.html

[U34] Py：判断编码
来源：http://dali.yuanzhike.top/Article/details/gtndnpxhtz.html

chardet.detect(raw)
来源：http://dali.feifeiyinyue.top/Article/details/gtrfhliuze.html

[U35] Py：发送邮件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqpntxmm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cashguo.top/Article/details/gthkgtqyjp.html

[U36] Py：定时任务
来源：http://dali.jqgfzy.top/Article/details/gtjowrrtln.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhongyouzk.top/Article/details/gtjiwbluur.html

[U37] Py：读写 Excel
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvimxvxo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tianlin.xyz/Article/details/gttxgtejbr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gtqvtnpspt.html

Path(__file__).resolve().parent
来源：http://dali.yvedp.cn/Article/details/gteuyhyedy.html

[U39] Py：判断是否在交互环境
来源：http://dali.sysykeji.top/Article/details/gtsbeoyhop.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gtrklrxutc.html

[U40] Py：打印到标准错误
来源：http://dali.mhx1999.top/Article/details/gtdnugrmll.html

print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtzyyrrjzr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gtlbpwizrz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.redwolf501.top/Article/details/gtbxqftvhq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gtomxzjjuk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzasephtd.html

[U43] PHP：声明命名空间
来源：http://dali.jianghu66.top/Article/details/gtvibsqlzp.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gthdgvvtig.html

[U44] PHP：开启严格类型
来源：http://dali.hywenlv.cn/Article/details/gtzqakgsim.html

declare(strict_types=1);
来源：http://dali.xinyue.icu/Article/details/gtisnynyjr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gtzcmxlrzv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqbsvvqw.html

[U46] PHP：可空类型
来源：http://dali.ivvv.top/Article/details/gtvvsrshun.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gtixbzrtps.html

[U47] PHP：联合类型
来源：http://dali.quarkkingdee.top/Article/details/gtcczggaph.html

int|string $id
来源：http://dali.gogol.net.cn/Article/details/gtzoadluel.html

[U48] PHP：纯枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsdcptff.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cucudq.cn/Article/details/gtoxfgjbwx.html

[U49] PHP：只读属性
来源：http://dali.hfpthk.cn/Article/details/gtckszceoq.html

public readonly string $name
来源：http://dali.pengpengdd.cyou/Article/details/gtnzqxgkbm.html

[U50] PHP：构造器属性提升
来源：http://dali.cheryme.top/Article/details/gtjipcrctj.html

public function __construct(private int $id) {}
来源：http://dali.nwbrower.top/Article/details/gtpaxwfsaj.html

[U51] PHP：数组解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwiukovd.html

[$a, $b] = $arr;
来源：http://dali.quarkkingdee.top/Article/details/gtgyuhlpat.html

[U52] PHP：箭头函数
来源：http://dali.wangdashe.top/Article/details/gtwybiltvi.html

$double = fn($x) => $x * 2;
来源：http://dali.hywenlv.cn/Article/details/gtwftqisng.html

[U53] PHP：空合并运算符
来源：http://dali.cheryme.top/Article/details/gtjmxmyvjp.html

$v = $a ?? $b ?? "default";
来源：http://dali.9152youxi.cn/Article/details/gtvknnrpnq.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gtrjfwuxam.html

$obj?->method()
来源：http://dali.sysykeji.top/Article/details/gtmxeimglh.html


<!-- 参考信息 -->