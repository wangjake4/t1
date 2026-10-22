代发 wailian999

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gtlozjxicr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gtaraojkxl.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtyanilnaf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhengqikj.top/Article/details/gtrcrffmrf.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtpqjdctga.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gtievdwlac.html

[S34] C++：遍历 vector
来源：http://dali.nanxinkj.top/Article/details/gtlzptfxxn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gtosyysncc.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gtdfpkdxip.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtbsiioqck.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gtsptctbfd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtoluedfgu.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gtoqpjsgsj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsncafjzp.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gtiuurfzhk.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtektobmjq.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtsgbgovzb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gtkveorayi.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtapstjquo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtqrqvydge.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtcgcodzai.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ppjwa.cn/Article/details/gtssioqhqb.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gtyuxznsgd.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gtddqsniau.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gtffhbshem.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtelbvfgme.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gtinxltabe.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gthheodjpw.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtivusmcet.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gtjsdhfcsu.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvenybgrz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gtmxtdrwcv.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gtorpsnqzy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gthqybbxbk.html

[S48] C++：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtiwqipigw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtyjxqdvya.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gtmkkufcbe.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtxgqpvozz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtqvgftteu.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gttvingnjp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtweylcrem.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gtpiebhhtd.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtqnatwtcm.html

[S52] C++：const 与 noexcept
来源：http://dali.xinyue.icu/Article/details/gtlydbchil.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gtcpfujqmx.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gtnaejpjda.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gtyoqntbqv.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gtdzppbxfd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtrkebmhqu.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gtuagktnpb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cucudq.cn/Article/details/gtxdghwasw.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gtiqtyhtaz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.feifeiyinyue.top/Article/details/gtylexlysb.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gtwtsuoihf.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtoplumpqm.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtvplwsgfi.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtqaorcvxg.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gtkrtncjoi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gtzttaibcr.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtlelhsvqk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtsmrapiey.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwryvazza.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gtxgvdipoc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtulffleoa.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtbvasafbv.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtcckhlmht.html

[T02] Kotlin：变量
来源：http://dali.xinyue.icu/Article/details/gtyupnuswx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtqzlxxfea.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gtdayabyps.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtwfbfyppf.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gthqjajucv.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gtxswkpojs.html

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gtyxlvuito.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gtzoysprfu.html

[T06] Kotlin：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtxdrfsvhj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtxsyrxlpb.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gthjbeaqru.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gteggeddjd.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gtbrnzjiyv.html

data class User(val name: String, val age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtbxhzavkz.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtubxsrrft.html

fun String.exclaim() = this + "!"
来源：http://dali.pycfn.com/Article/details/gtiwdlulkv.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gttwjbrwjb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtqretiduu.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gtdmzqjxxq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gtdtlwjgbx.html

[T12] Kotlin：解构声明
来源：http://dali.c1oappe.top/Article/details/gtnvjlqrcu.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtbbudbzva.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gtnxkqgvaq.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gtqcucpzpf.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcooaxyq.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtbyedjddp.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gtvtredulb.html

interface Shape { fun area(): Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmvkuhof.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gtzdltmeon.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gttjmduzso.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtbluyaxhf.html

var a = 1;  let b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtdtageswh.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gttyyarlvo.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtflxcwhpd.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gtqusmozel.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gthljlebph.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gteqyqntwy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gtygzugohl.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gtqlztpcib.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gtrsmxsjtt.html

[T22] Swift：字典
来源：http://dali.redwolf501.top/Article/details/gtnlgnpaup.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gtnthfvehg.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gteojojdvt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtapgmkzgw.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtlrgmqgfs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtzlivalfc.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gtsbgwypdo.html

struct P { var x: Int }
来源：http://dali.shuidangran.top/Article/details/gtchsmnphw.html

[T26] Swift：类与重写
来源：http://dali.aibaodan.cn/Article/details/gtzmosxygv.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtyszgydxe.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gtjrindayc.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gtbxwvckgp.html

[T28] Swift：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpgcymbc.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gtpyzgddou.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gtdsfrvxwj.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gtdxsezgyp.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnmejrfu.html

protocol Shape { func area() -> Double }
来源：http://dali.vqdsnc.cn/Article/details/gttvkznfua.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtabayqblm.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtobsiwjdl.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtnrqofskx.html

local a = 1
来源：http://dali.zhongyouzk.top/Article/details/gttaexllfo.html

[T33] Lua：表（数组）
来源：http://dali.yongpay.top/Article/details/gtbljaiddt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tanke756.top/Article/details/gtvnedkynq.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gtbtyxlodd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gthxhtkere.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gtaoafgtjz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtbpxpiuhz.html

[T36] Lua：函数
来源：http://dali.0kj1m.cn/Article/details/gtfuohbgro.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gtxgthwlfw.html

[T37] Lua：字符串拼接
来源：http://dali.cucudq.cn/Article/details/gteptjntyt.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gtzzhdwzqm.html

[T38] Lua：条件
来源：http://dali.ybcxt.top/Article/details/gtoiewbpay.html

if x > 0 then print("正") end
来源：http://dali.yj20258.top/Article/details/gtpqpbjnbl.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gtrowudumi.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gtojeduahg.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gtaamhsqjx.html

setmetatable({}, { __index = base })
来源：http://dali.yvedp.cn/Article/details/gtakzbmcbp.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gtcwyfspsb.html

print "Hello\n";
来源：http://dali.yj20258.top/Article/details/gtxftjjvar.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gtyhldjbhu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gtmeaywihp.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhupveca.html

"值: $a"
来源：http://dali.pengpengdd.cyou/Article/details/gtoskvxxuq.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gtltwqdvow.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtgdulyqof.html

[T45] Perl：数组遍历
来源：http://dali.yuanzhike.top/Article/details/gtvafwwiym.html

for my $x (@arr) { print $x; }
来源：http://dali.yonumen.top/Article/details/gtrkzfvvgz.html

[T46] Perl：哈希操作
来源：http://dali.hnxiangtu.top/Article/details/gtsfpduafz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtaqiqgjbc.html

[T47] Perl：正则捕获
来源：http://dali.hongshengwenyu.top/Article/details/gtlzmwczgr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenzaomai.com/Article/details/gtcoynhnpf.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtjstjyoip.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gtrqzswoes.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gtwvidvbki.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtjgdlsrqx.html

[T50] Perl：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gthdvjwnmw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuanzx.com/Article/details/gtxgegnpbw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hammf.cn/Article/details/gtgnpqxpqv.html

[T51] Scala：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtmypgymlc.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtwjzexoeu.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gtdqemigxx.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gtlvwhufax.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gtbrfmirjh.html

s"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtrwekupcv.html

[T54] Scala：集合映射
来源：http://dali.tanke756.top/Article/details/gtkajgsiaw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daxiang520.top/Article/details/gtawknpdkc.html

[T55] Scala：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtbtswbfqi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.svipenyu.cn/Article/details/gtnrtmprxh.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gtvitxdtyr.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gtrmemrvpl.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gtdtnwugjs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gtlrywkrfi.html

[T58] Scala：函数定义
来源：http://dali.meibo888.top/Article/details/gtszjhbftc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gtvrwcnspd.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gtnavbbymo.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtrkvzzksk.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gtbbwmopeu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cashguo.top/Article/details/gtxgcsyehm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzsxnhwbm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gtmkowpjnn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvkofnghy.html

[U01] Py：创建虚拟环境
来源：http://dali.svipenyu.cn/Article/details/gtngnmjtus.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gtbvdjnync.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gtxgdefdjf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gtnqlupagr.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gtatkmsuvx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtnjdezfcf.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gtznbkbecg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gtmgbpdgon.html

[U05] Py：列表去重且保序
来源：http://dali.quarkkingdee.top/Article/details/gtevbhmtvq.html

list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtyrszdywq.html

[U06] Py：合并两个字典
来源：http://dali.dashuyun.cn/Article/details/gtwjjxhrfa.html

{**a, **b}
来源：http://dali.zycfv.cn/Article/details/gtciybwfnm.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gtoifhfubs.html

{v: k for k, v in d.items()}
来源：http://dali.zhoulong.xyz/Article/details/gtinpgezaf.html

[U08] Py：展平二维列表
来源：http://dali.andypj.xyz/Article/details/gtycerpgvn.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gtgpsrqbwp.html

[U09] Py：字典取最大值的键
来源：http://dali.0kj1m.cn/Article/details/gtwasdyppr.html

max(d, key=d.get)
来源：http://dali.xziqi.cn/Article/details/gtkdghssft.html

[U10] Py：按值排序字典
来源：http://dali.gaohongyu789.top/Article/details/gttefcokwv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gtclgtsilg.html

[U11] Py：生成器表达式
来源：http://dali.pycfn.com/Article/details/gtdzxxvlnc.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gtpjeehqrc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tian-w.cn/Article/details/gtcnpblcjh.html

Counter(arr).most_common(3)
来源：http://dali.yj20258888.top/Article/details/gtbmmquhfu.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gtjlqdrzzv.html

deque(maxlen=10)
来源：http://dali.chenjidiqi.icu/Article/details/gtpejaimww.html

[U14] Py：分组收集到列表
来源：http://dali.jqgufenzy.top/Article/details/gtohqbxrhe.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gtieussapo.html

[U15] Py：高精度计时
来源：http://dali.gotoacloud.top/Article/details/gtpkxzjsvy.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gtpzkekzua.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gtdesmmjws.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xinyue.icu/Article/details/gttbpvxmzs.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gtmusikaza.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xinyue.icu/Article/details/gtwuoicatw.html

[U18] Py：预编译正则
来源：http://dali.yangfankeji.com/Article/details/gtewcsflfn.html

pat = re.compile(r"\d+")
来源：http://dali.zycfv.cn/Article/details/gtkskxzghm.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gtrmdiarjs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gtfdvudxos.html

[U20] Py：缓存函数结果
来源：http://dali.daria6918.cn/Article/details/gtgalplfgj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gtmiiutiav.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gtfsfqaeyn.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gtvvkbyzlx.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gtusptjxzb.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gtdzvfdazk.html

[U23] Py：分块读取大文件
来源：http://dali.feifeiyinyue.top/Article/details/gtriudyeqf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gtcsgjvnvn.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gttxclkmht.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtlcuolhiy.html

[U25] Py：CSV 按字典读
来源：http://dali.andypj.xyz/Article/details/gtjkvadczf.html

csv.DictReader(f)
来源：http://dali.havefunace.top/Article/details/gtgeabhest.html

[U26] Py：并发下载
来源：http://dali.ehwqpu.com/Article/details/gtrmbsezif.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gtyamvmutb.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gtnqbqomwr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gtfqvjtywe.html

[U28] Py：类型别名
来源：http://dali.cqqwz.cn/Article/details/gtyiwuwclk.html

UserId = int
来源：http://dali.yonumen.top/Article/details/gtzeebdsjo.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gtlbgmsdza.html

@property 与 @x.setter 配合
来源：http://dali.jinqigufen.top/Article/details/gtomngbuox.html

[U30] Py：数据类
来源：http://dali.ppjwa.cn/Article/details/gtvntecqqt.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gtjmlyqmzi.html

[U31] Py：单测
来源：http://dali.c1oappe.top/Article/details/gtzillqaaq.html

python -m pytest -q
来源：http://dali.guowangkeji.top/Article/details/gtxrifmfgg.html

[U32] Py：代码格式化
来源：http://dali.aibaodan.cn/Article/details/gttgqljqhf.html

ruff format . && ruff check --fix .
来源：http://dali.zdqjudy.top/Article/details/gtypttqtrj.html

[U33] Py：打包发布
来源：http://dali.jqgfzy.top/Article/details/gtwtvlmjea.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gtajwvvoqk.html

[U34] Py：判断编码
来源：http://dali.0kj1m.cn/Article/details/gtwsywnsog.html

chardet.detect(raw)
来源：http://dali.cqqwz.cn/Article/details/gtwvvybegf.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gtfngrovzn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258.top/Article/details/gtdikgxzij.html

[U36] Py：定时任务
来源：http://dali.svipenyu.cn/Article/details/gttlvapiuj.html

schedule.every(10).minutes.do(job)
来源：http://dali.fzhhl.top/Article/details/gtojncdpxr.html

[U37] Py：读写 Excel
来源：http://dali.zycfv.cn/Article/details/gtsfsxjtkc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangtech.top/Article/details/gtcipxpgpp.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangshuangyany.cn/Article/details/gtbhgdguaw.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gthrbqyqkk.html

[U39] Py：判断是否在交互环境
来源：http://dali.pengpengdd.cyou/Article/details/gtdhrckqyt.html

sys.stdout.isatty()
来源：http://dali.hongshengwenyu.top/Article/details/gtmtzsczxr.html

[U40] Py：打印到标准错误
来源：http://dali.vqdsnc.cn/Article/details/gtmdfcfdem.html

print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gttevlrefo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ppjwa.cn/Article/details/gtvvazibji.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sufxvd.cn/Article/details/gthmxweriq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.0kj1m.cn/Article/details/gttaaalooa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gtintsxner.html

[U43] PHP：声明命名空间
来源：http://dali.fengsongda.top/Article/details/gtwcudpuqx.html

namespace App\Http;
来源：http://dali.zdqjudy.top/Article/details/gteyuuzeik.html

[U44] PHP：开启严格类型
来源：http://dali.nanxinkj.top/Article/details/gteurgmldx.html

declare(strict_types=1);
来源：http://dali.daxiang520.top/Article/details/gthtuxobpj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgfzy.top/Article/details/gtdnfymbeb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtspgatpfk.html

[U46] PHP：可空类型
来源：http://dali.shuidangran.top/Article/details/gtkldbdpwn.html

?string $name = null
来源：http://dali.jqgfzy.top/Article/details/gtpzqyrcty.html

[U47] PHP：联合类型
来源：http://dali.wangshuangyany.cn/Article/details/gtmbxoatws.html

int|string $id
来源：http://dali.hnxiangtu.top/Article/details/gtgxzwtome.html

[U48] PHP：纯枚举
来源：http://dali.jyoumei.cn/Article/details/gtekaqqqqd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tanke756.top/Article/details/gtjhyqrmkk.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gtxngvnsph.html

public readonly string $name
来源：http://dali.gzhubu.top/Article/details/gtupkqvjbh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrubsdacx.html

public function __construct(private int $id) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthwnspfep.html

[U51] PHP：数组解构
来源：http://dali.dianchejie.cn/Article/details/gtkxuzmpzl.html

[$a, $b] = $arr;
来源：http://dali.fengsongda.top/Article/details/gtynczccpi.html

[U52] PHP：箭头函数
来源：http://dali.redwolf501.top/Article/details/gtylrcbded.html

$double = fn($x) => $x * 2;
来源：http://dali.birdmap.top/Article/details/gtuojgxfwh.html

[U53] PHP：空合并运算符
来源：http://dali.feifeiyinyue.top/Article/details/gtrhqjziqy.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuetiantiany.cn/Article/details/gtuwczhkbm.html

[U54] PHP：空安全调用
来源：http://dali.sxryk.cn/Article/details/gtbvqyquuh.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gttcdbackc.html

[U55] PHP：match 表达式
来源：http://dali.guowangkeji.top/Article/details/gtcioivmlh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gtopujsniv.html

[U56] PHP：命名参数
来源：http://dali.nanxinkj.top/Article/details/gtgwnjlguy.html

f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtgjogjuel.html


<!-- 参考信息 -->