代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gtbmpbahpj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gtsuqmspjw.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gtusviskqk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkernzya.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gtmszkpeak.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gtvnwqehbe.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtabfsngqs.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gtapgekqkp.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gtbqsjyldl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gtersdpfja.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdnafcvf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gtueoetiqu.html

[S47] C++：结构化绑定遍历
来源：http://dali.dianchejie.cn/Article/details/gtqiqfagbq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gttszfeawo.html

[S48] C++：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtwijrdrjo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlcfeyam.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtcjovsegv.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gtjavacrpd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gtvwogtbfm.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtmnxlukkb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtufbxbuvw.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtncmvhbbm.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtdrzfhccu.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqeuqaib.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gtotfmhvcg.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gtfceinodv.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258.top/Article/details/gtqvwhnwuy.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gtjjucwucg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtwariwzjl.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gtcrirrgsx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtoawduncj.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtazxoplsu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gtydkxhwzs.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gtneequyxz.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtydeuvlpq.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gttrladzfd.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtqlmktxtv.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gtgaqjplbo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspdpnfmr.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtrnioogpr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtifrwdpcn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtguzxigsp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtfajohadn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwbbafxjl.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvxtrwss.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoluvsgzl.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtkhctbxlg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gtlbjifprg.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsgfjcxq.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtrpxolsrz.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gtmkgwddmg.html

val n: String? = null;  n?.length
来源：http://dali.zycfv.cn/Article/details/gteofgypse.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtafilzuzr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtzdtyieen.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtipqxllxr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjaguifb.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gtvbcrssds.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gtdmkwgrrg.html

[T08] Kotlin：数据类
来源：http://dali.iojbl.cn/Article/details/gttqtmjxfj.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gthfqimldc.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gtxoiexmod.html

fun String.exclaim() = this + "!"
来源：http://dali.sweek.top/Article/details/gtufrnkzpa.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtrionlgji.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtzqbkxcba.html

[T11] Kotlin：协程
来源：http://dali.cashguo.top/Article/details/gtokxbwqsq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gteyvbyimq.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtklqvxmrh.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gthkfwnkiy.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gtsihctizu.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gtnridfqut.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtlurgikjy.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gteohegdvw.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gtbfxlytfz.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gtxwwzwsnd.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtztrdxidw.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdjzfgwx.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gtzsduugus.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gtmbbunfsm.html

[T18] Swift：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtukfqomvs.html

"值: \(b)"
来源：http://dali.ydzc1.top/Article/details/gtqntfxxhj.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gtvrcqbtjt.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gtaisnkgyb.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gtdyjzopca.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.0kj1m.cn/Article/details/gtuzhyozxb.html

[T21] Swift：遍历
来源：http://dali.andypj.xyz/Article/details/gteaueibkq.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gtbsktxbbj.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gtfqqqcyvw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gtrslgyfqd.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gtvdchlvww.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.316326.xyz/Article/details/gtbtrngwog.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gtuqvazees.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtywdppfkg.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gtsoafknhl.html

struct P { var x: Int }
来源：http://dali.yongpay.top/Article/details/gtdkpytpbi.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gttqvgsnem.html

class A: Base { override func f() {} }
来源：http://dali.yangfankeji.com/Article/details/gtpkrfbxme.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gtxjzyvlur.html

do { try f() } catch { print(error) }
来源：http://dali.shzxlz.cn/Article/details/gtaemnjejn.html

[T28] Swift：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtmtzrmufp.html

enum Color { case red, green }
来源：http://dali.yvedp.cn/Article/details/gtfuoaglas.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtffckywkw.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gtvyznrcpq.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gtvybkedyv.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtajzflqsw.html

[T31] Lua：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtckpnydqp.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtimmyhliy.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gtmpzlwdzs.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtwjxyvzhm.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtbijwsyno.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.andypj.xyz/Article/details/gtsyoitbdl.html

[T34] Lua：遍历表
来源：http://dali.hfpthk.cn/Article/details/gtjhljjjal.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gtakewfnwh.html

[T35] Lua：字典表
来源：http://dali.jiagoushi.top/Article/details/gthiyyyqxz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtejmlynij.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gttlgdkfid.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtojkcsaqh.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gtsstedzjf.html

"a" .. "b"
来源：http://dali.cdnleiting.top/Article/details/gtscfgjknr.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszjscikz.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyydvxmao.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gtskippxqx.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gtbifagwkj.html

[T40] Lua：元表
来源：http://dali.tanke756.top/Article/details/gthnxkzduj.html

setmetatable({}, { __index = base })
来源：http://dali.ppjwa.cn/Article/details/gtuzrnwgvt.html

[T41] Perl：Hello World
来源：http://dali.yj202588.top/Article/details/gtorlcstqi.html

print "Hello\n";
来源：http://dali.ehwqpu.com/Article/details/gtyenafqxs.html

[T42] Perl：变量类型
来源：http://dali.nanxuanxn.top/Article/details/gtpziuizec.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtaeqvfkki.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gtpzfsfkcg.html

"值: $a"
来源：http://dali.yongpay.top/Article/details/gthdpcrsxm.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gtfmigmzip.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtneffzzwq.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gteqkzqowd.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gtmltmmvol.html

[T46] Perl：哈希操作
来源：http://dali.hnxiangtu.top/Article/details/gtvqrougms.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dianchejie.cn/Article/details/gthwyuxkng.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gthtzibdhu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgfzy.top/Article/details/gtaktorkad.html

[T48] Perl：正则替换
来源：http://dali.cheryme.top/Article/details/gtnnmajgxp.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gtnsqglvnw.html

[T49] Perl：函数
来源：http://dali.meibo888.top/Article/details/gtdrneyqgx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtygujiysk.html

[T50] Perl：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtqtuxlyoa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuetiantiany.cn/Article/details/gttfzudilt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.birdmap.top/Article/details/gtmpnvdvpz.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsisslmj.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtmcrorbyf.html

[T52] Scala：变量
来源：http://dali.316326.xyz/Article/details/gtywpbmhph.html

val a = 1;  var b = 2
来源：http://dali.redwolf501.top/Article/details/gtdpaadpxd.html

[T53] Scala：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtydmjwgrx.html

s"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtgaiptduk.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gtmdfmyugm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xziqi.cn/Article/details/gtkumqetck.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtouncnbwu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gtvjpwmotn.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gtxlmfundk.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gtyjtelgiv.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtmregznhv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gtkxwosvuk.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gtlumixadq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gtjbammdds.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gtfvwdoavc.html

for (i <- 1 to 10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtodphiwdb.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtawqsfdmu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gtjyjviqha.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdueeskhv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gterspjxin.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthhnraatc.html

[U01] Py：创建虚拟环境
来源：http://dali.pengpengdd.cyou/Article/details/gtkomwmmnu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gtktkxumte.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dianchejie.cn/Article/details/gtvzwhyclt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.haohaochexian.top/Article/details/gtbykhbkcd.html

[U03] Py：加载 .env 配置
来源：http://dali.ppjwa.cn/Article/details/gtzwibnelt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gtipkwytmy.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gtwloizesy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gtdmrchwdi.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gtgkeziiyy.html

list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtmtcnbqni.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gttfkwuzpg.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gtahkoseis.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gtpfgwtwwm.html

{v: k for k, v in d.items()}
来源：http://dali.sufxvd.cn/Article/details/gtiiydkpni.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gtdhakyoyx.html

[y for x in nested for y in x]
来源：http://dali.zdqjudy.top/Article/details/gtdzpusabe.html

[U09] Py：字典取最大值的键
来源：http://dali.zhoulong.xyz/Article/details/gtloduntvi.html

max(d, key=d.get)
来源：http://dali.yj202588.top/Article/details/gttjwsabti.html

[U10] Py：按值排序字典
来源：http://dali.fzhhl.top/Article/details/gtczkqaxlm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ivvv.top/Article/details/gtwbivzgnd.html

[U11] Py：生成器表达式
来源：http://dali.guannengcc.top/Article/details/gtvtqfvhnc.html

(x * 2 for x in arr)
来源：http://dali.xziqi.cn/Article/details/gthuwhjzex.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gtaaumxnrj.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gtrnldvgew.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gtotcrrauq.html

deque(maxlen=10)
来源：http://dali.zycfv.cn/Article/details/gtqsmiykru.html

[U14] Py：分组收集到列表
来源：http://dali.c1oappe.top/Article/details/gtvemdqlsh.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhktagnn.html

[U15] Py：高精度计时
来源：http://dali.shzxlz.cn/Article/details/gtqyymihsr.html

t = time.perf_counter()
来源：http://dali.pycfn.com/Article/details/gtetaopgwb.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gtfqswyjwz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yanxiufei.cn/Article/details/gtjcfenikp.html

[U17] Py：初始化日志
来源：http://dali.ppjwa.cn/Article/details/gtbenwylel.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxuanxn.top/Article/details/gtpfdakplu.html

[U18] Py：预编译正则
来源：http://dali.yanxiufei.cn/Article/details/gtzewnppeq.html

pat = re.compile(r"\d+")
来源：http://dali.zdqjudy.top/Article/details/gttrenyaia.html

[U19] Py：正则替换带回调
来源：http://dali.hongshengwenyu.top/Article/details/gtyyiyuzvh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jianghu66.top/Article/details/gtnkqoytco.html

[U20] Py：缓存函数结果
来源：http://dali.smart0.xyz/Article/details/gtlflmdghx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cdnleiting.top/Article/details/gtqmzxtnvd.html

[U21] Py：自定义上下文管理器
来源：http://dali.ppjwa.cn/Article/details/gtnsikanwy.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gtkzvcobkf.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gtxqghhyqw.html

list(zip(*m))
来源：http://dali.andypj.xyz/Article/details/gtthyxmfhk.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gtpwvubdwf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gtiazzqbzf.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gtglvtoept.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gtixzsaxnw.html

[U25] Py：CSV 按字典读
来源：http://dali.c1oappe.top/Article/details/gtukwsezbe.html

csv.DictReader(f)
来源：http://dali.chenlongwang.top/Article/details/gtamrtvyqv.html

[U26] Py：并发下载
来源：http://dali.xinyue.icu/Article/details/gtniozpakd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbjwvmcv.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gtycdmqrfw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuanzhike.top/Article/details/gtbdscmzqk.html

[U28] Py：类型别名
来源：http://dali.cashguo.top/Article/details/gtgzheeucf.html

UserId = int
来源：http://dali.hywenlv.cn/Article/details/gtxyoridsg.html

[U29] Py：属性校验
来源：http://dali.birdmap.top/Article/details/gtuqegaoia.html

@property 与 @x.setter 配合
来源：http://dali.svipenyu.cn/Article/details/gtqnnotdfo.html

[U30] Py：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gtcmcjazza.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gtcceerjuy.html

[U31] Py：单测
来源：http://dali.cheryme.top/Article/details/gtgailgakl.html

python -m pytest -q
来源：http://dali.aibaodan.cn/Article/details/gtqjvtgkon.html

[U32] Py：代码格式化
来源：http://dali.andypj.xyz/Article/details/gtkplhbpdf.html

ruff format . && ruff check --fix .
来源：http://dali.hysaishi.cn/Article/details/gtizrqpmfy.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gtnincmemo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gogol.net.cn/Article/details/gthuqkmwrk.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gttfihibhn.html

chardet.detect(raw)
来源：http://dali.c1oappe.top/Article/details/gtqmrvbwmp.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gtlmrjdbcx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwlryhik.html

[U36] Py：定时任务
来源：http://dali.jianghu66.top/Article/details/gtyclbjsbe.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenlongwang.top/Article/details/gthjdqraun.html

[U37] Py：读写 Excel
来源：http://dali.jyoumei.cn/Article/details/gtppqbzzpg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aizwys.cn/Article/details/gtwwwgzhks.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrksvqyv.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gtnqudtbeb.html

[U39] Py：判断是否在交互环境
来源：http://dali.jianghu66.top/Article/details/gtnhmagxen.html

sys.stdout.isatty()
来源：http://dali.quarkkingdee.top/Article/details/gtkkwjxfvn.html

[U40] Py：打印到标准错误
来源：http://dali.jianghu66.top/Article/details/gtztmsxxdc.html

print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtoyuepxxj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.quarkkingdee.top/Article/details/gtivfovlau.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zycfv.cn/Article/details/gtbivhakks.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gtrlfcrhgu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hammf.cn/Article/details/gtylkiatgo.html

[U43] PHP：声明命名空间
来源：http://dali.jqgfzy.top/Article/details/gtfafrrput.html

namespace App\Http;
来源：http://dali.jqgfzy.top/Article/details/gtitmvjxon.html

[U44] PHP：开启严格类型
来源：http://dali.cdnleiting.top/Article/details/gtpdvauikt.html

declare(strict_types=1);
来源：http://dali.chenzaomai.com/Article/details/gtsjnskmmw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.snrcjt.cn/Article/details/gtfsrteznc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtkcmvnfbi.html

[U46] PHP：可空类型
来源：http://dali.bjfxy.top/Article/details/gtvwqhhpml.html

?string $name = null
来源：http://dali.nwbrower.top/Article/details/gtdjwcrmiu.html

[U47] PHP：联合类型
来源：http://dali.chenlongwang.top/Article/details/gtjqeuxtnu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gtmcqexjtc.html

[U48] PHP：纯枚举
来源：http://dali.ydzc1.top/Article/details/gtnojyabte.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dashuyun.cn/Article/details/gtakegxryt.html

[U49] PHP：只读属性
来源：http://dali.jinqigfzy.top/Article/details/gtgbeoofaf.html

public readonly string $name
来源：http://dali.iojbl.cn/Article/details/gtpwjbjffy.html

[U50] PHP：构造器属性提升
来源：http://dali.vqdsnc.cn/Article/details/gtwvgwvgtu.html

public function __construct(private int $id) {}
来源：http://dali.cqqwz.cn/Article/details/gtpvgyibfs.html

[U51] PHP：数组解构
来源：http://dali.snrcjt.cn/Article/details/gtpitdhyjb.html

[$a, $b] = $arr;
来源：http://dali.redwolf501.top/Article/details/gtbqotbfzr.html

[U52] PHP：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gtinqzcsoe.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gtszscrrmb.html

[U53] PHP：空合并运算符
来源：http://dali.feifeiyinyue.top/Article/details/gttcfjrqrk.html

$v = $a ?? $b ?? "default";
来源：http://dali.cdnleiting.top/Article/details/gtmiyxtaqh.html

[U54] PHP：空安全调用
来源：http://dali.iojbl.cn/Article/details/gtuwnoznbc.html

$obj?->method()
来源：http://dali.yangfankeji.com/Article/details/gtkxodfxqj.html

[U55] PHP：match 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtvpaxgpdw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwcedrky.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gthhlshyiw.html

f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtlrnhtnja.html

[U57] PHP：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtpcqxpujf.html

"值: {$a}"
来源：http://dali.0kj1m.cn/Article/details/gtpkqmglpc.html

[U58] PHP：数组三件套
来源：http://dali.nwbrower.top/Article/details/gtajpzxhgw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtiaarhxwq.html

[U59] PHP：自定义排序
来源：http://dali.cashguo.top/Article/details/gthgnnyexb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtohpsfxdp.html

[U60] PHP：JSON 编解码
来源：http://dali.sysykeji.top/Article/details/gtxiqaduzu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jiagoushi.top/Article/details/gtsaqobjlw.html

[U61] PHP：正则
来源：http://dali.wangshuangyany.cn/Article/details/gtzpuzpitu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtfrzvitoq.html

[U62] PHP：日期对象
来源：http://dali.cheryme.top/Article/details/gtpmuyuofs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xziqi.cn/Article/details/gtuerxlpdr.html

[U63] PHP：文件读写
来源：http://dali.nanxuanxn.top/Article/details/gtxyrqwkpg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangtech.top/Article/details/gtipfhazqs.html

[U64] PHP：目录遍历
来源：http://dali.jinqigfzy.top/Article/details/gtykkuhnyv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangshuangyany.cn/Article/details/gtdnoiwney.html

[U65] PHP：会话
来源：http://dali.hnqzz.top/Article/details/gtxjkhisja.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtcvqqyyfr.html

[U66] PHP：设置 Cookie
来源：http://dali.xziqi.cn/Article/details/gtsgxkvdav.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.vqdsnc.cn/Article/details/gtvwglclai.html


<!-- 参考信息 -->