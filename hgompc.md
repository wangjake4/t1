代发 wailian999

[S37] C++：set
来源：http://dali.quarkkingdee.top/Article/details/gtygvaltvt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gtndaoseqm.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtegjqfbix.html

std::sort(v.begin(), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtqmvutaid.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gtkcddscvz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gtbethocmv.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxmmmkcb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtepyknzth.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtvlytgmcj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtgahadozr.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gtwuldfidw.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtfipximti.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gtvewztugb.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtcdjpbyqn.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gthpffurgu.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtfwlcvlaz.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtrlsqnxxn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtodrlsw.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gtelvpkbkm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hysaishi.cn/Article/details/gtxvnhrngl.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gtlwkuzpnv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gtltxsssby.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtqnuqzpfn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gtaywpuzku.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtpndseglq.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gttrfkhwzm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtrubqrpvj.html

[S50] C++：格式化数字
来源：http://dali.feifeiyinyue.top/Article/details/gtnfdbltyk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gtcjqjezus.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gtchencagv.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtgblxnvtr.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtirgmelqa.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtxdsnaiiv.html

[S53] C++：移动语义
来源：http://dali.gzhubu.top/Article/details/gtyrvabnhg.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtfyznjeyj.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gtxchqfgtl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtjzkqqomv.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gtinoocrpt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gtomodvpnn.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gtixhhbnsz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtkajvhbdz.html

[S57] C++：编译期常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfzcsjrk.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtcdwsctit.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtnbkhciyb.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gtnvwlnhzc.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtyckkqbqp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gtrtandvpj.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gtdynbdupn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtzgseuloj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtufstvpqt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtczgqlqal.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtylbzrytv.html

[T01] Kotlin：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtecufigsd.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtsuvmlcfj.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtxupdtrqe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gtjwvegsix.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258888.top/Article/details/gtkevagysf.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtoyfqbvot.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtooazjfrt.html

val n: String? = null;  n?.length
来源：http://dali.nanxinkj.top/Article/details/gtdxgytypj.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gtlrvazpar.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gtkodrbkjd.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gtmabtuczx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtlpicpvyk.html

[T07] Kotlin：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gtjlojprwb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtjtqglscd.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtnkkkjzit.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtxsooqxpv.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtehmjxrci.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gthysuhwaf.html

[T10] Kotlin：默认参数
来源：http://dali.jianghu66.top/Article/details/gtfumbukrx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtkbdokitj.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gtymatzqgu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.vqdsnc.cn/Article/details/gtizxutvzb.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gtifdanclh.html

val (a, b) = Pair(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtvhwjuqml.html

[T13] Kotlin：只读 Map
来源：http://dali.ppjwa.cn/Article/details/gtpogzsfdp.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gtebupasrb.html

[T14] Kotlin：循环
来源：http://dali.xuanzx.com/Article/details/gtafdiqwol.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjahirdeu.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gtsxkobqso.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gtkjpemdqr.html

[T16] Swift：Hello World
来源：http://dali.gogol.net.cn/Article/details/gthlfrraiy.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtnsmyrlye.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtsrgqtdhs.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gtihthooud.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtgwgzliks.html

"值: \(b)"
来源：http://dali.yueranfly.top/Article/details/gtvwlzpzqj.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjwlghoe.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gtcezxsxdo.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gthnyhtinb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtdhrmdclp.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gtluzfomig.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gtjfnfoidv.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gtyogqsacw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtrxmklkgc.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gtfyxcdrep.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gtwnopjqxf.html

[T24] Swift：闭包
来源：http://dali.0kj1m.cn/Article/details/gtgookqrpf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtmumywflb.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gtveykgcxo.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gtzjwocfoe.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gtolyomtyo.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gtzuiuqewk.html

[T27] Swift：错误处理
来源：http://dali.guannengcc.top/Article/details/gtillkkpmy.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gtyjpwzxkk.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gttjqextju.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtxrhuxctl.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gttfsicolz.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gtdumffqir.html

[T30] Swift：协议
来源：http://dali.pycfn.com/Article/details/gtxymuqime.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtmsvtgqrz.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gtafohretj.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbnibloo.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gtaeftpiiq.html

local a = 1
来源：http://dali.fzhhl.top/Article/details/gtpkmfyjmd.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gteblnzkea.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gzhubu.top/Article/details/gtnwfjyrjd.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gtfaxsijll.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgreultws.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gtzdlozoid.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cqqwz.cn/Article/details/gtblatvywe.html

[T36] Lua：函数
来源：http://dali.ydzc1.top/Article/details/gtsthypttx.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gtfndaqhqq.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtpurkvvii.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gtbbdbclll.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gteeqoqkpp.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtmnwuebfq.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtjciltvug.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gtnzclzqon.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gtryqhzflo.html

setmetatable({}, { __index = base })
来源：http://dali.yueranfly.top/Article/details/gtnwjidmaj.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtipqzzelw.html

print "Hello\n";
来源：http://dali.zhoulong.xyz/Article/details/gtoczhtcpn.html

[T42] Perl：变量类型
来源：http://dali.nanxinkj.top/Article/details/gtveeyfkfl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhongyouzk.top/Article/details/gtgbqihlyl.html

[T43] Perl：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtofrnmpqq.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gtimmcylpl.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtiejdapli.html

if ($a > 0) { print "正"; }
来源：http://dali.jlsjyb.cn/Article/details/gtavwcwfvc.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gtomnjkjza.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtqacobyja.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gtczcapfem.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gtasmkwhcn.html

[T47] Perl：正则捕获
来源：http://dali.kuanghao11.cn/Article/details/gtsrsmoovz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gtywndvpwb.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gtvcyovpsx.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gtihtkipyv.html

[T49] Perl：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsvqjqkt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtdubriyvz.html

[T50] Perl：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtczaugkdt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ybcxt.top/Article/details/gtcuzurkmk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tian-w.cn/Article/details/gtqtbnmaom.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtiwgocfkv.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtggfcbpgr.html

[T52] Scala：变量
来源：http://dali.cqqwz.cn/Article/details/gtrpswacxb.html

val a = 1;  var b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtxzmzws.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtcgqdmfng.html

s"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtmiophper.html

[T54] Scala：集合映射
来源：http://dali.pycfn.com/Article/details/gtebprvwwm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.iojbl.cn/Article/details/gteebugsxb.html

[T55] Scala：集合过滤
来源：http://dali.daria6918.cn/Article/details/gttbshjtcy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigfzy.top/Article/details/gtfwapbvjw.html

[T56] Scala：样例类
来源：http://dali.zhengqikj.top/Article/details/gtqpjjrlhm.html

case class User(name: String, age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtbbacpfqa.html

[T57] Scala：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtatpckkel.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtpqfkoedh.html

[T58] Scala：函数定义
来源：http://dali.hysaishi.cn/Article/details/gtqsektidm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gtfotcrgyb.html

[T59] Scala：循环
来源：http://dali.fzhhl.top/Article/details/gteefescyd.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtycduhvvb.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gtclbswgce.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gtxbvuotwh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvxfrpiv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gttvidwifz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtuwdskrfz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gtibxvlkyt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sweek.top/Article/details/gtxcdifanj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ehwqpu.com/Article/details/gtmtafzlni.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gtkbaqshja.html

[U03] Py：加载 .env 配置
来源：http://dali.jlsjyb.cn/Article/details/gtqllcqvoq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gtcgeumqoi.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gtqqlcrxob.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangshuangyany.cn/Article/details/gtnhsrrmyo.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gtumapiwqd.html

list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtehkksdre.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluffkvmp.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gtaivvgaza.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmkqjmau.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gtflfowque.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gtffqpmjyj.html

[y for x in nested for y in x]
来源：http://dali.yangfankeji.com/Article/details/gtgzlnngvj.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtklntwwhk.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gtdqpaobnr.html

[U10] Py：按值排序字典
来源：http://dali.yvedp.cn/Article/details/gtlvhtjsjj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aibaodan.cn/Article/details/gtiycqujvg.html

[U11] Py：生成器表达式
来源：http://dali.dashuyun.cn/Article/details/gtilglrbba.html

(x * 2 for x in arr)
来源：http://dali.sxryk.cn/Article/details/gtoaamrbce.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gtezkfmxoo.html

Counter(arr).most_common(3)
来源：http://dali.sxryk.cn/Article/details/gtkpljicjv.html

[U13] Py：固定长度队列
来源：http://dali.sxryk.cn/Article/details/gtprvfcvjz.html

deque(maxlen=10)
来源：http://dali.zhongyouzk.top/Article/details/gttltjznwx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gtgopqbcnq.html

defaultdict(list)
来源：http://dali.bjfxy.top/Article/details/gtrjhorsws.html

[U15] Py：高精度计时
来源：http://dali.xuetiantiany.cn/Article/details/gtbnuwzqzg.html

t = time.perf_counter()
来源：http://dali.jinqigfzy.top/Article/details/gtbsnkdaaw.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gtfrccwgeq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gtitjrqxqb.html

[U17] Py：初始化日志
来源：http://dali.birdmap.top/Article/details/gthyasgfby.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnpexvpa.html

[U18] Py：预编译正则
来源：http://dali.nwbrower.top/Article/details/gtndijewvv.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gtjirqxoxo.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gtkjwpegcq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigufen.top/Article/details/gthdllxffv.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gtgnhzsvsw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.andypj.xyz/Article/details/gtjvuvaoys.html

[U21] Py：自定义上下文管理器
来源：http://dali.xziqi.cn/Article/details/gtbxxovyyc.html

@contextlib.contextmanager
来源：http://dali.zhengqikj.top/Article/details/gtnuiypilo.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gtgilcebfh.html

list(zip(*m))
来源：http://dali.iojbl.cn/Article/details/gtcggppdmh.html

[U23] Py：分块读取大文件
来源：http://dali.pengpengdd.cyou/Article/details/gtfyayzgmk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gtudyutqmw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gtgifbmmsm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtghdomfjm.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gtollwizkb.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gtvoucxfvc.html

[U26] Py：并发下载
来源：http://dali.yueranfly.top/Article/details/gtjjadzvmr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jianghu66.top/Article/details/gtmaiumjjk.html

[U27] Py：异步 HTTP
来源：http://dali.zhixingplan.top/Article/details/gtkzyctbpb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gtehkegwij.html

[U28] Py：类型别名
来源：http://dali.9152youxi.cn/Article/details/gtsyotbqnu.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gtejjctrya.html

[U29] Py：属性校验
来源：http://dali.yangfankeji.com/Article/details/gttcerfkol.html

@property 与 @x.setter 配合
来源：http://dali.haohaochexian.top/Article/details/gthaicuzfw.html

[U30] Py：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gtvnhytniw.html

@dataclass(slots=True)
来源：http://dali.meibo888.top/Article/details/gtuawgsrub.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gtjzfwblot.html

python -m pytest -q
来源：http://dali.cashguo.top/Article/details/gtlxnuxpmc.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gtuoddsdvl.html

ruff format . && ruff check --fix .
来源：http://dali.hywenlv.cn/Article/details/gtpkgoekzw.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclbyvhfj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gtotekbqlx.html

[U34] Py：判断编码
来源：http://dali.chenzaomai.com/Article/details/gtozavotsj.html

chardet.detect(raw)
来源：http://dali.316326.xyz/Article/details/gtejdevdvn.html

[U35] Py：发送邮件
来源：http://dali.hnxiangtu.top/Article/details/gttjkgdqak.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yanxiufei.cn/Article/details/gtdniraflf.html

[U36] Py：定时任务
来源：http://dali.daria6918.cn/Article/details/gtujbhiobf.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangdashe.top/Article/details/gtlokdcwmq.html

[U37] Py：读写 Excel
来源：http://dali.hywenlv.cn/Article/details/gtmqutdioq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shangyingyoupin.top/Article/details/gtlihvyori.html

[U38] Py：获取脚本所在目录
来源：http://dali.mhx1999.top/Article/details/gthlvnapod.html

Path(__file__).resolve().parent
来源：http://dali.zycfv.cn/Article/details/gtffiahkak.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gtakjvndkk.html

sys.stdout.isatty()
来源：http://dali.yangfankeji.com/Article/details/gtvoyttgon.html

[U40] Py：打印到标准错误
来源：http://dali.meibo888.top/Article/details/gtcsskqlvn.html

print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtskzoofrc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shzxlz.cn/Article/details/gtkxzmylbi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cashguo.top/Article/details/gtjltswuhz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.kuanghao11.cn/Article/details/gtvqpgyvbi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgfzy.top/Article/details/gtqfhofjgc.html

[U43] PHP：声明命名空间
来源：http://dali.wangdashe.top/Article/details/gtkjxtxvgj.html

namespace App\Http;
来源：http://dali.sxryk.cn/Article/details/gtqdlxpyba.html

[U44] PHP：开启严格类型
来源：http://dali.andypj.xyz/Article/details/gtmgokzuix.html

declare(strict_types=1);
来源：http://dali.ydzc1.top/Article/details/gtnrbriywo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdozxzqzc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtnloarupw.html

[U46] PHP：可空类型
来源：http://dali.yj202588.top/Article/details/gtwizdsxzs.html

?string $name = null
来源：http://dali.quarkkingdee.top/Article/details/gtwofbguwb.html

[U47] PHP：联合类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtansilpqz.html

int|string $id
来源：http://dali.cashguo.top/Article/details/gtudzpxjhf.html

[U48] PHP：纯枚举
来源：http://dali.iojbl.cn/Article/details/gtqpskusqo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gaohongyu789.top/Article/details/gtjeqpsvkr.html

[U49] PHP：只读属性
来源：http://dali.shuidangran.top/Article/details/gtahzydqaf.html

public readonly string $name
来源：http://dali.shzxlz.cn/Article/details/gtpydgkbab.html

[U50] PHP：构造器属性提升
来源：http://dali.aibaodan.cn/Article/details/gtgaeikjlv.html

public function __construct(private int $id) {}
来源：http://dali.gzhubu.top/Article/details/gtuoiangdw.html

[U51] PHP：数组解构
来源：http://dali.vqdsnc.cn/Article/details/gtztxzadxi.html

[$a, $b] = $arr;
来源：http://dali.daria6918.cn/Article/details/gtnktxerxs.html

[U52] PHP：箭头函数
来源：http://dali.sysykeji.top/Article/details/gteqydydox.html

$double = fn($x) => $x * 2;
来源：http://dali.pycfn.com/Article/details/gtebnmitgm.html

[U53] PHP：空合并运算符
来源：http://dali.iojbl.cn/Article/details/gtkmtknyfb.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoemlmlzh.html

[U54] PHP：空安全调用
来源：http://dali.sysykeji.top/Article/details/gtscplmycg.html

$obj?->method()
来源：http://dali.smart0.xyz/Article/details/gtqgvxtoum.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gtkadhunku.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtdhnzvhtz.html

[U56] PHP：命名参数
来源：http://dali.fzhhl.top/Article/details/gtjnzxbnsw.html

f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtikjgtyna.html

[U57] PHP：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxmladyl.html

"值: {$a}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmpljfvm.html

[U58] PHP：数组三件套
来源：http://dali.tian-w.cn/Article/details/gtucdkxhtd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtlbmxtcvq.html

[U59] PHP：自定义排序
来源：http://dali.dashuyun.cn/Article/details/gtackqrutv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtustpldfv.html

[U60] PHP：JSON 编解码
来源：http://dali.guannengcc.top/Article/details/gtzhpyuzat.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zycfv.cn/Article/details/gtvshsshtf.html

[U61] PHP：正则
来源：http://dali.meibo888.top/Article/details/gttigmeyta.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtxouatqar.html

[U62] PHP：日期对象
来源：http://dali.hfpthk.cn/Article/details/gtqwtqybcv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ydzc1.top/Article/details/gtjpwvzgxi.html


<!-- 参考信息 -->