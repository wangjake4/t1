代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gtnlrshotm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqigaxjen.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtgziokaxg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gttfwxiyvi.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtlbmjnodi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gtaflaqjdy.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gtgcutsbat.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtfasjanhs.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtemdoexlp.html

auto p = std::make_unique<int>(5);
来源：http://dali.xziqi.cn/Article/details/gtbednopwb.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gtfyozwxka.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtlqmwhluo.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gtxnjgjkhl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gthkrffkjb.html

[S46] C++：函数模板
来源：http://dali.yj20258.top/Article/details/gtefyvkkfm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gttwekntuw.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gtjrpzpaju.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtplfzyrtq.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtfhpaiwie.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtumybhsly.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gtvqvwsspk.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gtdbyhbjpe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gtlynxhpgc.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gttdzgeqno.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedlclnsy.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gtkqehzkpy.html

static_cast<double>(a) / b
来源：http://dali.yuxming.cn/Article/details/gtmfoamdpq.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtzgztbjyh.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtsyjlcaxm.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtbhcedwbu.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gthvecmdvv.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gtxpacqrow.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtqqirzkep.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtfhbomvlz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkgsbdes.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gtuubwuftb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxuanxn.top/Article/details/gtwwvkbeke.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gtawuoeove.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gtdocqejku.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtiknreglr.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gtxufgrxep.html

[S59] C++：静态断言
来源：http://dali.nwbrower.top/Article/details/gtgwzlbjzt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gtkmksithk.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gtqlucchfj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ivvv.top/Article/details/gthumcxxij.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtnreivwij.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gttccdafcn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtocqhsjqf.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gtrcsjgxdg.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtgyhcwwbe.html

[T02] Kotlin：变量
来源：http://dali.jqgufenzy.top/Article/details/gtllytvwmy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gtqcqrfruj.html

[T03] Kotlin：字符串模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuvnvvfn.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtucggmtca.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gtoflvvpfr.html

val n: String? = null;  n?.length
来源：http://dali.daxiang520.top/Article/details/gtqwucbodx.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gteyoxafaf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtideseonu.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtqmujabsr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtrjxmcgtm.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtliedzbpo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtstbvlocr.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gthbmcpuqc.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtowkfdjer.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyfimspg.html

fun String.exclaim() = this + "!"
来源：http://dali.guannengcc.top/Article/details/gtjgltexpy.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gtiesoaqvv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cdnleiting.top/Article/details/gtegmxxvpm.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gtwodoupku.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gtqaitaloa.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gtqsuzgwbe.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gtjnymcscm.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gtyttfamsy.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gtbfrynffa.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtyspiptxd.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtdhawgint.html

[T15] Kotlin：接口
来源：http://dali.fzhhl.top/Article/details/gtryofipuo.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtzjnvfvyj.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gteetgffmo.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtozpdgavs.html

[T17] Swift：变量与常量
来源：http://dali.zycfv.cn/Article/details/gthplahzdh.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gtwxmdnlhy.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtnrdwyfzy.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtgxvvjzsz.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gtgyvnxvoa.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gtkpfzkdse.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gtfzfwiunp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gtelhhxdls.html

[T21] Swift：遍历
来源：http://dali.9152youxi.cn/Article/details/gttkyxlpya.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gtvjtucqti.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gtyliqbjue.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gtxvdjudxo.html

[T23] Swift：函数
来源：http://dali.hnqzz.top/Article/details/gtjmhzdhvi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gtmafgmsqs.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gtphzhdmsh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtlvistfbf.html

[T25] Swift：结构体
来源：http://dali.mhx1999.top/Article/details/gtasxaoqrd.html

struct P { var x: Int }
来源：http://dali.ybcxt.top/Article/details/gtqgfznlyo.html

[T26] Swift：类与重写
来源：http://dali.xuetiantiany.cn/Article/details/gtnzqixiov.html

class A: Base { override func f() {} }
来源：http://dali.cashguo.top/Article/details/gtwsjwvmcg.html

[T27] Swift：错误处理
来源：http://dali.daxiang520.top/Article/details/gtxkqozuhq.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigufen.top/Article/details/gtqgeohjle.html

[T28] Swift：枚举
来源：http://dali.yj20258888.top/Article/details/gtjyxcplhr.html

enum Color { case red, green }
来源：http://dali.hammf.cn/Article/details/gtygktabjt.html

[T29] Swift：guard 提前返回
来源：http://dali.svipenyu.cn/Article/details/gtvxoczdwa.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gtimpisrqa.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gtuvvppdqa.html

protocol Shape { func area() -> Double }
来源：http://dali.hnxiangtu.top/Article/details/gtenfaffda.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gtlhujxtyo.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtgcgecqxu.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gtlyqqkwme.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gtahlmhbak.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gtifijrzth.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gtkydngwzv.html

[T34] Lua：遍历表
来源：http://dali.ivvv.top/Article/details/gtpssymcaj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtgrdhaljv.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gticmjctpm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gteflusdsn.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gteyocgpum.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gteufsumeq.html

[T37] Lua：字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtnqphasjl.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gtyjdgsgvr.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gtexdpqjly.html

if x > 0 then print("正") end
来源：http://dali.xziqi.cn/Article/details/gtevairbmg.html

[T39] Lua：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtivlqhzro.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtmehwdgie.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gthdrembqm.html

setmetatable({}, { __index = base })
来源：http://dali.316326.xyz/Article/details/gtwxqcdrhh.html

[T41] Perl：Hello World
来源：http://dali.bjfxy.top/Article/details/gtnwntarcu.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtdwqemngi.html

[T42] Perl：变量类型
来源：http://dali.yonumen.top/Article/details/gtbdygndyj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xylfe.cn/Article/details/gtwrexepab.html

[T43] Perl：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtxkozeymf.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gtwztqcgnj.html

[T44] Perl：条件
来源：http://dali.hysaishi.cn/Article/details/gtfnbguqzu.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gtmhepgjyb.html

[T45] Perl：数组遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtyzsvutlq.html

for my $x (@arr) { print $x; }
来源：http://dali.hnxiangtu.top/Article/details/gtmjutzetg.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gtggjeinuf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daria6918.cn/Article/details/gttezatxmi.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gtxcezxbjh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gtqjwphisg.html

[T48] Perl：正则替换
来源：http://dali.redwolf501.top/Article/details/gtgdwdecxw.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gtpdszglvz.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gtldzobowu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtiokagkcy.html

[T50] Perl：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtrfgjoflo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gtcvzszoeu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gtwjdnrzdv.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtrmkxegoh.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gticotwign.html

[T52] Scala：变量
来源：http://dali.gzhubu.top/Article/details/gtksxfagca.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gtquusyslk.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtoybzzxoj.html

s"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtlkbiwvmi.html

[T54] Scala：集合映射
来源：http://dali.smart0.xyz/Article/details/gtxsytusmt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gtkqigejqi.html

[T55] Scala：集合过滤
来源：http://dali.ivvv.top/Article/details/gtswrdzsnz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gtsfueghje.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangtech.top/Article/details/gtczpkvsyu.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gthcvgpctf.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gthkmfksfw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuanzhike.top/Article/details/gtcjzaxdhv.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gtrxwsuecx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ydzc1.top/Article/details/gtlrxulxac.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gtjxrdcyjy.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtuauptkzj.html

[T60] Scala：折叠
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhgjjmgw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gtavoqevpp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqfciznrv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gtvtwnanip.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkvonpssu.html

[U01] Py：创建虚拟环境
来源：http://dali.tianlin.xyz/Article/details/gtfhjyhouu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gtjyysgwfh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gthhvwljez.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sweek.top/Article/details/gttjqjwhsc.html

[U03] Py：加载 .env 配置
来源：http://dali.guannengcc.top/Article/details/gtjjmsuudt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ehwqpu.com/Article/details/gtexfdunpw.html

[U04] Py：变量调试打印
来源：http://dali.cashguo.top/Article/details/gtjwajvibd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gtuczznnht.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvmedvrx.html

list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtosxfonam.html

[U06] Py：合并两个字典
来源：http://dali.bjfxy.top/Article/details/gtqfaodnxp.html

{**a, **b}
来源：http://dali.dashuyun.cn/Article/details/gtrtxydufz.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gtnbbuvelk.html

{v: k for k, v in d.items()}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtmfvyxv.html

[U08] Py：展平二维列表
来源：http://dali.ppjwa.cn/Article/details/gtqbpwapaq.html

[y for x in nested for y in x]
来源：http://dali.meibo888.top/Article/details/gtpeqsicyq.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gtsyykanwd.html

max(d, key=d.get)
来源：http://dali.jqgfzy.top/Article/details/gtcnzdrmkr.html

[U10] Py：按值排序字典
来源：http://dali.zhiwuduotai.top/Article/details/gtruygvita.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guannengcc.top/Article/details/gtiomhpulh.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gtknsmtkyv.html

(x * 2 for x in arr)
来源：http://dali.havefunace.top/Article/details/gtedjiqwhc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.feifeiyinyue.top/Article/details/gtlqklgnof.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gtfzqpgfpe.html

[U13] Py：固定长度队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtonywdcus.html

deque(maxlen=10)
来源：http://dali.wangshuangyany.cn/Article/details/gtuxzxfdtu.html

[U14] Py：分组收集到列表
来源：http://dali.0kj1m.cn/Article/details/gtcadbkndq.html

defaultdict(list)
来源：http://dali.hnxiangtu.top/Article/details/gthxsntmbg.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gtjafsizjt.html

t = time.perf_counter()
来源：http://dali.zhoulong.xyz/Article/details/gtbywqpeul.html

[U16] Py：命令行参数解析
来源：http://dali.snrcjt.cn/Article/details/gtmmjnwrnc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gtzwczokbj.html

[U17] Py：初始化日志
来源：http://dali.wangdashe.top/Article/details/gtzchrohlh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.bjfxy.top/Article/details/gtqbesllie.html

[U18] Py：预编译正则
来源：http://dali.dashuyun.cn/Article/details/gtsoanhizi.html

pat = re.compile(r"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtoxlkmvkl.html

[U19] Py：正则替换带回调
来源：http://dali.zhongyouzk.top/Article/details/gtrpvsvioh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.316326.xyz/Article/details/gtoftommqz.html

[U20] Py：缓存函数结果
来源：http://dali.daria6918.cn/Article/details/gtbyplhhvk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gtiefmjohb.html

[U21] Py：自定义上下文管理器
来源：http://dali.jyoumei.cn/Article/details/gtayueucig.html

@contextlib.contextmanager
来源：http://dali.cashguo.top/Article/details/gtlhbtmntg.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gtoqzphaho.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gtaqnrqdnj.html

[U23] Py：分块读取大文件
来源：http://dali.vqdsnc.cn/Article/details/gtncbbotnb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikxihonm.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gtrokmdpyl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtaeogjfor.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gtjtkiqdtc.html

csv.DictReader(f)
来源：http://dali.cucudq.cn/Article/details/gtkgimqjfz.html

[U26] Py：并发下载
来源：http://dali.xinyue.icu/Article/details/gtfzjcjbou.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhixingplan.top/Article/details/gtegtcspmo.html

[U27] Py：异步 HTTP
来源：http://dali.yvedp.cn/Article/details/gthlajixlk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tanke756.top/Article/details/gtjnuwqrys.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gtgshzwfjd.html

UserId = int
来源：http://dali.redwolf501.top/Article/details/gtlcwhideg.html

[U29] Py：属性校验
来源：http://dali.gotoacloud.top/Article/details/gtmwxaifpv.html

@property 与 @x.setter 配合
来源：http://dali.hywenlv.cn/Article/details/gtxliymmcn.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gtwvgxpabw.html

@dataclass(slots=True)
来源：http://dali.fengsongda.top/Article/details/gtayojopuq.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gthgbldnux.html

python -m pytest -q
来源：http://dali.9152youxi.cn/Article/details/gtjikhcnkt.html

[U32] Py：代码格式化
来源：http://dali.hysaishi.cn/Article/details/gtytyiehjv.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gtohhebdlt.html

[U33] Py：打包发布
来源：http://dali.quarkkingdee.top/Article/details/gtbqgnxjkj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cdnleiting.top/Article/details/gtlcuvvvqy.html

[U34] Py：判断编码
来源：http://dali.yj20258888.top/Article/details/gtpnyfzizd.html

chardet.detect(raw)
来源：http://dali.jinqigfzy.top/Article/details/gtdpwtjjtg.html

[U35] Py：发送邮件
来源：http://dali.vqdsnc.cn/Article/details/gtiyssdgey.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sysykeji.top/Article/details/gttrwajfjh.html

[U36] Py：定时任务
来源：http://dali.cqqwz.cn/Article/details/gthecnpdfx.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrungbyuv.html

[U37] Py：读写 Excel
来源：http://dali.chenzaomai.com/Article/details/gtzjbgnuuy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.vqdsnc.cn/Article/details/gtjmgbnhiq.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenjidiqi.icu/Article/details/gthibhebte.html

Path(__file__).resolve().parent
来源：http://dali.quarkkingdee.top/Article/details/gtgtoychee.html

[U39] Py：判断是否在交互环境
来源：http://dali.guowangkeji.top/Article/details/gtqxygjbak.html

sys.stdout.isatty()
来源：http://dali.jinyuanbaomall.cn/Article/details/gteeqrxnuc.html

[U40] Py：打印到标准错误
来源：http://dali.chenjidiqi.icu/Article/details/gtyjmwlhfa.html

print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtvkgowotm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gtcgbwjoay.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.andypj.xyz/Article/details/gttdzrneeg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hysaishi.cn/Article/details/gtmnvcjehn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jianghu66.top/Article/details/gtxyccqweb.html

[U43] PHP：声明命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtbuovsxid.html

namespace App\Http;
来源：http://dali.haohaochexian.top/Article/details/gtqcotyzsz.html

[U44] PHP：开启严格类型
来源：http://dali.birdmap.top/Article/details/gtlmywxhaf.html

declare(strict_types=1);
来源：http://dali.ivvv.top/Article/details/gtjmkfuzic.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ydzc1.top/Article/details/gtlfpjptoz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtwpcyckql.html

[U46] PHP：可空类型
来源：http://dali.sufxvd.cn/Article/details/gtpmhlilbu.html

?string $name = null
来源：http://dali.cqqwz.cn/Article/details/gtzxsgbgqn.html

[U47] PHP：联合类型
来源：http://dali.zhengqikj.top/Article/details/gtupldepky.html

int|string $id
来源：http://dali.yuanzhike.top/Article/details/gtigfaskxd.html

[U48] PHP：纯枚举
来源：http://dali.pycfn.com/Article/details/gtqinqmdim.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkybltma.html

[U49] PHP：只读属性
来源：http://dali.cqqwz.cn/Article/details/gtazmowxat.html

public readonly string $name
来源：http://dali.tian-w.cn/Article/details/gtqyrqbezr.html

[U50] PHP：构造器属性提升
来源：http://dali.jinqigufen.top/Article/details/gtytbccnec.html

public function __construct(private int $id) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbewmempx.html

[U51] PHP：数组解构
来源：http://dali.xinyue.icu/Article/details/gtbhanyujd.html

[$a, $b] = $arr;
来源：http://dali.ppjwa.cn/Article/details/gtovlpnyzk.html

[U52] PHP：箭头函数
来源：http://dali.ivvv.top/Article/details/gtjaxfwlgj.html

$double = fn($x) => $x * 2;
来源：http://dali.yangfankeji.com/Article/details/gtvugphtcf.html

[U53] PHP：空合并运算符
来源：http://dali.nanxinkj.top/Article/details/gtbplrzrrb.html

$v = $a ?? $b ?? "default";
来源：http://dali.tian-w.cn/Article/details/gtxfvqqabb.html

[U54] PHP：空安全调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqavoedrj.html

$obj?->method()
来源：http://dali.haohaochexian.top/Article/details/gtwyfndclb.html

[U55] PHP：match 表达式
来源：http://dali.tanke756.top/Article/details/gtrlgwfvpo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.9152youxi.cn/Article/details/gthhyfahov.html

[U56] PHP：命名参数
来源：http://dali.yvedp.cn/Article/details/gtjgjwdhjz.html

f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtzuftqcfe.html

[U57] PHP：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtnojfssga.html

"值: {$a}"
来源：http://dali.guowangkeji.top/Article/details/gtmvidsyyl.html

[U58] PHP：数组三件套
来源：http://dali.gotoacloud.top/Article/details/gtbbnzcrfr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtpzclfyys.html

[U59] PHP：自定义排序
来源：http://dali.daxiang520.top/Article/details/gtsxtqonta.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtuxqocsav.html

[U60] PHP：JSON 编解码
来源：http://dali.jiagoushi.top/Article/details/gtosmuupbn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ivvv.top/Article/details/gtukzqvzei.html

[U61] PHP：正则
来源：http://dali.hammf.cn/Article/details/gtntrsqwfg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtqtcgfyrx.html

[U62] PHP：日期对象
来源：http://dali.iojbl.cn/Article/details/gtfqhteixx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jiagoushi.top/Article/details/gtuztqvsbj.html

[U63] PHP：文件读写
来源：http://dali.jqgufenzy.top/Article/details/gtrrtmyfyn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.svipenyu.cn/Article/details/gtrjqimlrz.html

[U64] PHP：目录遍历
来源：http://dali.jianghu66.top/Article/details/gtlqkcocfi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gogol.net.cn/Article/details/gtjkouerzx.html


<!-- 参考信息 -->