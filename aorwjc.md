代发 wailian999

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzcvrjex.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtbgwbitjn.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gtgbevlznq.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gtktllrjzd.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gtnfiokygk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtwrcnltay.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtjdwwxwlp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gtrxadisrn.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gtpxdfndxz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gtuymrjnla.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtpnfyiwoi.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtppnyyxam.html

[S43] C++：智能指针
来源：http://dali.dashuyun.cn/Article/details/gtogbkolqd.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gtrvceffol.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtmcylfaij.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gtwnemsvxk.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqkvtrow.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtlbozdfix.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtbuhswunf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gtkyfvmjsd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtqmzneumq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuxming.cn/Article/details/gtlnhrksbr.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtvsjhrkxh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gthowsfsgr.html

while (std::getline(in, line)) { }
来源：http://dali.daria6918.cn/Article/details/gtoeiarfzt.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtybgecesv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtcztcbauu.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gtpmhfwfpg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtxsdqnabf.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gtrjzztgzj.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gttmxgnksa.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtamkpxfsl.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gticysiecr.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gthfldywnr.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtvuetfyzp.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gtwklgumrn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtgeyfnuoc.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtjzamkdhc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gtdtgvzlam.html

[S56] C++：optional
来源：http://dali.zdqjudy.top/Article/details/gtblfxuhcb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxjmcxtkp.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gtmceszmve.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtoxiqoopq.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gtizebnhaz.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gtjgfrywop.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gtlmbydzba.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gttnqtnmbh.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtjphpaspu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtygsdfgzl.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmxrxkysf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gtcjskagfu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbjxbewv.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gtwihompsy.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtofpigukc.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtvqurzwbf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtmwapbffc.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtxgmuqagv.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtxjubpgpv.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gtnpjkhbdz.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtfnjjdyek.html

[T05] Kotlin：when 表达式
来源：http://dali.tian-w.cn/Article/details/gteyvxorme.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zdqjudy.top/Article/details/gtrzsocdyc.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtjmewkjdk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtxfeicjrv.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtlokspxbn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gthyqumdbr.html

[T08] Kotlin：数据类
来源：http://dali.daxiang520.top/Article/details/gtbfyyvpuz.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtrfqnwgzm.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gtvctcwdaa.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gtxlzebulu.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gtdbdijaue.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gtbtxproau.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gtzakztcyj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gtdtxehfpt.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtwmpuycjo.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtrjutrwkw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelctaoxk.html

val m = mapOf("a" to 1)
来源：http://dali.gaohongyu789.top/Article/details/gtdmvifvxc.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gthmomejhz.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtjauumzgq.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gtnnlbcccm.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtdfdvaxfp.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtiljybmdv.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtxrzuferw.html

[T17] Swift：变量与常量
来源：http://dali.cqqwz.cn/Article/details/gtduwkcnpf.html

var a = 1;  let b = 2
来源：http://dali.redwolf501.top/Article/details/gtgzqdydbv.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gttdkklzkq.html

"值: \(b)"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkygnxohb.html

[T19] Swift：可选绑定
来源：http://dali.ybcxt.top/Article/details/gtoitghfxq.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtvlwxxdpt.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtgttovyvc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gtjquqofkq.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gtudynwgzi.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjhmjtrj.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gttwarlabx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtcfeinuxg.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtetxcigjy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtygilymdx.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gtpcyuyhea.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtfodheyti.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gtxejfsvnq.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gtsbtuyaax.html

[T26] Swift：类与重写
来源：http://dali.aibaodan.cn/Article/details/gtrskmnrjh.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gtmiuhbznv.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gtablyzbzh.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtxorlyxhb.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gtjgbgdomb.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtqnbgcwim.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtgadvrlke.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gtfntmktpp.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gtgffdrrdq.html

protocol Shape { func area() -> Double }
来源：http://dali.xziqi.cn/Article/details/gtifqxpiry.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtkihjlrsu.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtayxmmlby.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gtqzoyudyh.html

local a = 1
来源：http://dali.aibaodan.cn/Article/details/gtiqyzguzn.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gttqvmsdce.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gtvwbchwha.html

[T34] Lua：遍历表
来源：http://dali.ydzc1.top/Article/details/gtfoogvera.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.feifeiyinyue.top/Article/details/gtydhhuqtg.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gtvkdhvgsh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gtalccxwkg.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtahfxmhuw.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gtzvnfvlvb.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtoivdgflf.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtrhnkausv.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gtffiozbtz.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gtedrlakpw.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtfpxmpcdu.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gtiwaqiazs.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtkpkvwagq.html

setmetatable({}, { __index = base })
来源：http://dali.shuidangran.top/Article/details/gtzhthbkyx.html

[T41] Perl：Hello World
来源：http://dali.yongpay.top/Article/details/gtxqydrpby.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gtxozikelv.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfksvzvv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yonumen.top/Article/details/gthtqplqwk.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtsnnlgbqc.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gtojkfoxha.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtngfcuydl.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtifwlgvqw.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gtvhgtezys.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gtfugllshq.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gtfzusanpp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxpzpllrk.html

[T47] Perl：正则捕获
来源：http://dali.daxiang520.top/Article/details/gtoklgjcbv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gtgadyggqb.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtnhrksgvv.html

$s =~ s/old/new/g;
来源：http://dali.vqdsnc.cn/Article/details/gtlniwsiyz.html

[T49] Perl：函数
来源：http://dali.pycfn.com/Article/details/gtndxfrwir.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtuugfcqvo.html

[T50] Perl：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gttbcwxfbf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gzhubu.top/Article/details/gtfzwruurm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gtjzigpweo.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gtwqkvbbld.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtgamhprxs.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gttoqdfthw.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gtdqpqtjvd.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gtoxvmerja.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtoypkjapq.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtmqmtpbmq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtnbrdawpf.html

[T55] Scala：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtzocpaegl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yueranfly.top/Article/details/gtncmxsyqq.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gtyubvsvyr.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gtdyoedohw.html

[T57] Scala：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtrsskvnbp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gtihtqeitz.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gtqiyjbtyv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnqzz.top/Article/details/gtrbdoyuby.html

[T59] Scala：循环
来源：http://dali.yangfankeji.com/Article/details/gtfshxgwmu.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjntcnyhn.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gtfndbtadt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.birdmap.top/Article/details/gtplyxqklg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbelypnim.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtkuyifvem.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyohlcjos.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gtsympwpuw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnxiangtu.top/Article/details/gtbntkxwrj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gtuduopzre.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gtkeetziwr.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtggdytwrl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhiwuduotai.top/Article/details/gtlktyvfuw.html

[U04] Py：变量调试打印
来源：http://dali.yonumen.top/Article/details/gtghfpvtff.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gtrhmyivoe.html

[U05] Py：列表去重且保序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaztvqcp.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtypbtkuzx.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gtogkymxpv.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gtsiqgzmkt.html

[U07] Py：反转字典键值
来源：http://dali.gzhubu.top/Article/details/gtybobygts.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gttcjarcvr.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gtjullojgj.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gtrpmrucez.html

[U09] Py：字典取最大值的键
来源：http://dali.fzhhl.top/Article/details/gtvjebkmih.html

max(d, key=d.get)
来源：http://dali.jianghu66.top/Article/details/gttebitldm.html

[U10] Py：按值排序字典
来源：http://dali.shangyingyoupin.top/Article/details/gtyfxcrgeu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gtnckktxnu.html

[U11] Py：生成器表达式
来源：http://dali.chenlongwang.top/Article/details/gtcpxqcybv.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gttoqkceae.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxinkj.top/Article/details/gtlziippjp.html

Counter(arr).most_common(3)
来源：http://dali.yueranfly.top/Article/details/gtrgkozbna.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gtdclayhef.html

deque(maxlen=10)
来源：http://dali.gaohongyu789.top/Article/details/gtiskkolkw.html

[U14] Py：分组收集到列表
来源：http://dali.chenzaomai.com/Article/details/gtduqzpayy.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gtntlmaatc.html

[U15] Py：高精度计时
来源：http://dali.jinqigufen.top/Article/details/gtnyvybbtf.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gtravjpmjc.html

[U16] Py：命令行参数解析
来源：http://dali.dashuyun.cn/Article/details/gtpubclipw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gtdhwjwfwe.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gtypzloyiv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cashguo.top/Article/details/gtwafgihnq.html

[U18] Py：预编译正则
来源：http://dali.zdqjudy.top/Article/details/gtuyaivsja.html

pat = re.compile(r"\d+")
来源：http://dali.meibo888.top/Article/details/gtpacyhunr.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gtdvpgpvcc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbopjrga.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigufen.top/Article/details/gtwqtnutis.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cqqwz.cn/Article/details/gttdoiwvre.html

[U21] Py：自定义上下文管理器
来源：http://dali.tianlin.xyz/Article/details/gtdechoceg.html

@contextlib.contextmanager
来源：http://dali.jlsjyb.cn/Article/details/gthdukvfsi.html

[U22] Py：矩阵转置
来源：http://dali.ybcxt.top/Article/details/gthdjmegot.html

list(zip(*m))
来源：http://dali.haohaochexian.top/Article/details/gtgueadeoc.html

[U23] Py：分块读取大文件
来源：http://dali.nanxuanxn.top/Article/details/gtqtypnzlp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gotoacloud.top/Article/details/gtkypaivxh.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtlyfhejjw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtninzfkgj.html

[U25] Py：CSV 按字典读
来源：http://dali.shuidangran.top/Article/details/gtgpznvsop.html

csv.DictReader(f)
来源：http://dali.mhx1999.top/Article/details/gtyhzvqqzy.html

[U26] Py：并发下载
来源：http://dali.mhx1999.top/Article/details/gtzprcogiv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtougjzpie.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigfzy.top/Article/details/gtbkjhutfr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.iojbl.cn/Article/details/gtejaoffnu.html

[U28] Py：类型别名
来源：http://dali.ehwqpu.com/Article/details/gttuujlwpx.html

UserId = int
来源：http://dali.zdqjudy.top/Article/details/gtbrqbraoj.html

[U29] Py：属性校验
来源：http://dali.0kj1m.cn/Article/details/gterrriemm.html

@property 与 @x.setter 配合
来源：http://dali.ppjwa.cn/Article/details/gtmzwfzqhh.html

[U30] Py：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtgtcjeqgg.html

@dataclass(slots=True)
来源：http://dali.tian-w.cn/Article/details/gtuedmmygz.html

[U31] Py：单测
来源：http://dali.aibaodan.cn/Article/details/gtvpfrxrzh.html

python -m pytest -q
来源：http://dali.sxryk.cn/Article/details/gtfenfjiyj.html

[U32] Py：代码格式化
来源：http://dali.yj202588.top/Article/details/gtqngazgdl.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gthddiqkrw.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gtzxmvkzia.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.kuanghao11.cn/Article/details/gtylllxqfj.html

[U34] Py：判断编码
来源：http://dali.zhongyouzk.top/Article/details/gtjyizvuht.html

chardet.detect(raw)
来源：http://dali.chenjidiqi.icu/Article/details/gtvcaqdsrz.html

[U35] Py：发送邮件
来源：http://dali.hongshengwenyu.top/Article/details/gtqswlojeb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cucudq.cn/Article/details/gtymbhsave.html

[U36] Py：定时任务
来源：http://dali.yj20258.top/Article/details/gtotwabwhq.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigufen.top/Article/details/gtlgdwmuct.html

[U37] Py：读写 Excel
来源：http://dali.xuanzx.com/Article/details/gtlhlecixs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.birdmap.top/Article/details/gtsmbjrtdb.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcupsyam.html

Path(__file__).resolve().parent
来源：http://dali.shuidangran.top/Article/details/gtfeelpwmc.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxuanxn.top/Article/details/gtgzgfcvyr.html

sys.stdout.isatty()
来源：http://dali.zycfv.cn/Article/details/gtjfwlelnt.html

[U40] Py：打印到标准错误
来源：http://dali.dianchejie.cn/Article/details/gtwypuybya.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gticzoccmg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guannengcc.top/Article/details/gtclgdkjnu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhengqikj.top/Article/details/gtsvljwseh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinghuilouyu.cn/Article/details/gttckikmqr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzqeecvj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtfbwgrilk.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gtxalchyuy.html

[U44] PHP：开启严格类型
来源：http://dali.meibo888.top/Article/details/gtyaiehhmr.html

declare(strict_types=1);
来源：http://dali.quarkkingdee.top/Article/details/gtordbtkof.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hammf.cn/Article/details/gtjvbaxcxh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtpxspqvhf.html

[U46] PHP：可空类型
来源：http://dali.havefunace.top/Article/details/gtkfepwmcw.html

?string $name = null
来源：http://dali.yongpay.top/Article/details/gtdoccddge.html

[U47] PHP：联合类型
来源：http://dali.tianlin.xyz/Article/details/gtnulxtatt.html

int|string $id
来源：http://dali.havefunace.top/Article/details/gtpbceiuor.html

[U48] PHP：纯枚举
来源：http://dali.cashguo.top/Article/details/gtzsrwldbj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.birdmap.top/Article/details/gtnhkqjvpe.html

[U49] PHP：只读属性
来源：http://dali.jyoumei.cn/Article/details/gtlvfujanb.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gtvyffelam.html

[U50] PHP：构造器属性提升
来源：http://dali.jyoumei.cn/Article/details/gtdzcnrnvo.html

public function __construct(private int $id) {}
来源：http://dali.yangfankeji.com/Article/details/gtahmfdcds.html

[U51] PHP：数组解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszdtwiqp.html

[$a, $b] = $arr;
来源：http://dali.yanxiufei.cn/Article/details/gtqtbrpdlo.html

[U52] PHP：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gtcxvsbdql.html

$double = fn($x) => $x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgnedgpu.html

[U53] PHP：空合并运算符
来源：http://dali.sweek.top/Article/details/gtlilvyqjr.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxinkj.top/Article/details/gtgecacmlg.html

[U54] PHP：空安全调用
来源：http://dali.xziqi.cn/Article/details/gtlvzzdhdh.html

$obj?->method()
来源：http://dali.pycfn.com/Article/details/gtfitobweu.html

[U55] PHP：match 表达式
来源：http://dali.cashguo.top/Article/details/gtglcxlmey.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ybcxt.top/Article/details/gtpwiphyzd.html

[U56] PHP：命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtgpmfulye.html

f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtxwhgfega.html

[U57] PHP：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtuztwgjum.html

"值: {$a}"
来源：http://dali.zycfv.cn/Article/details/gtfwsisdoc.html

[U58] PHP：数组三件套
来源：http://dali.fzhhl.top/Article/details/gtkzacefyn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.0kj1m.cn/Article/details/gtdfddfhso.html

[U59] PHP：自定义排序
来源：http://dali.sysykeji.top/Article/details/gtobzteolb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gttrmjxtdf.html

[U60] PHP：JSON 编解码
来源：http://dali.mhx1999.top/Article/details/gtsivilmge.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtdxzifzsa.html

[U61] PHP：正则
来源：http://dali.sxryk.cn/Article/details/gtukqypkue.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtzaqbzomu.html

[U62] PHP：日期对象
来源：http://dali.9152youxi.cn/Article/details/gtfeazyjhl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yueranfly.top/Article/details/gtbytqgrgf.html


<!-- 参考信息 -->