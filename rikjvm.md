代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtscgxsves.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fzhhl.top/Article/details/gtgpandlqt.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gteqqreiqx.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gtxkltoppv.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gtokrhzayk.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtovjoth.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gtnsfadlqr.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtsytzreqw.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gtaokvrgui.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gtwmfejbjb.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gtpxqvfnia.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gtbyhndaay.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gtktsuyrcq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangdashe.top/Article/details/gttgpyaxpm.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtwjhfvsmc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gtuftubwyl.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbtduigl.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtbxbhsxih.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gtslatdmbm.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gtrukbccap.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gtfhedleyv.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gtjshdvkiy.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gttdblhlgn.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gtqtduykpb.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gtfctobaji.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtmcjnzpoj.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gthqnecazu.html

[S54] C++：异常处理
来源：http://dali.jqgufenzy.top/Article/details/gtyybxohdv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ivvv.top/Article/details/gtrxhglfou.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhkgkmxt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gtmodqpbht.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gtvpzvenou.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dianchejie.cn/Article/details/gtlnlrpenx.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gtpmdxsjkj.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gtgqhoqkec.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtrptpttlq.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gtfofewkbp.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtlwcrtufi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gtufwzplif.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gteinothkc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtssddlbuv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtegdiwjaa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gtykebmgpg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzzfrngmw.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtggkgmcsf.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoijudsgp.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtzalwdtpp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtugwkdlad.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gtgpiudppw.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtwfebtoxg.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtisittisx.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gtcqwrenef.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gtgfrmrein.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gtsbciafpa.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtrrewwnil.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gtynjmlahb.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtsvkpyplf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gtznkqynhp.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gtxsllzsxz.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtlwhjfqoh.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gttivvauyc.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gtdzwjolmr.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gtbiaduhxp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtgdwggtxu.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gtsvuymkyk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gtsydsaflv.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gtoghqbydl.html

val (a, b) = Pair(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtbtwfhqfo.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtohemzcch.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtnxjydiqg.html

[T14] Kotlin：循环
来源：http://dali.guannengcc.top/Article/details/gtgdfvotov.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtjmyrtonk.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gtsooibbpn.html

interface Shape { fun area(): Double }
来源：http://dali.zhiwuduotai.top/Article/details/gtyxmeiglv.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtmtkemmjy.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtyqsefhzm.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gtdapglgca.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gtrrexnzmi.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gtgmlanjgb.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gtteeinbyc.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gtonzkzayl.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gtwaotisip.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhcxywmn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gthxdxsgex.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtlknsidbo.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcxmlppz.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gtxeitpyxj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gtvuraqepl.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gttaxfcdqg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hfpthk.cn/Article/details/gtnbwvxtva.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gtjrjtdkme.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtxwouyzkv.html

[T25] Swift：结构体
来源：http://dali.yj20258888.top/Article/details/gtcpfoeefb.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gtkrnkarwp.html

[T26] Swift：类与重写
来源：http://dali.chenlongwang.top/Article/details/gtklihnynh.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtuaaypjmg.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gtnkqnqiij.html

do { try f() } catch { print(error) }
来源：http://dali.yonumen.top/Article/details/gtqmmkrdbu.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gtlermeara.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gtpdruifur.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gtwstclchv.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtxipzxaai.html

[T30] Swift：协议
来源：http://dali.tanke756.top/Article/details/gtqnowqzdl.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gtafbeyoos.html

[T31] Lua：Hello World
来源：http://dali.chenlongwang.top/Article/details/gteqassxbk.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtevzscnqi.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gtvaroqjsq.html

local a = 1
来源：http://dali.jlsjyb.cn/Article/details/gtwnuedhdg.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gtualdvjlx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zdqjudy.top/Article/details/gtnjykmkdw.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilihtyub.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gtknifethm.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gtbndkjgvv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtdljityhd.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gtixcczyzy.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtrybkklxn.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtxabgztwl.html

"a" .. "b"
来源：http://dali.smart0.xyz/Article/details/gtxedadxtt.html

[T38] Lua：条件
来源：http://dali.ybcxt.top/Article/details/gtkayxajyl.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gtbjxinapp.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtmphzifhn.html

string.find(s, "%d+")
来源：http://dali.hfpthk.cn/Article/details/gtpjqeokqz.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gtdptbhryn.html

setmetatable({}, { __index = base })
来源：http://dali.zycfv.cn/Article/details/gtrzpmvfdc.html

[T41] Perl：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtkihsoawv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gtgfrgzxbh.html

[T42] Perl：变量类型
来源：http://dali.jlsjyb.cn/Article/details/gtyngsblgh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtorbcacut.html

[T43] Perl：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtalkcldnv.html

"值: $a"
来源：http://dali.jqgufenzy.top/Article/details/gthyfopint.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gthilknzyj.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gtyytymekm.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gthrstozes.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gtkvdvatpr.html

[T46] Perl：哈希操作
来源：http://dali.xinyue.icu/Article/details/gtgwjvojpb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.c1oappe.top/Article/details/gtwusrenwb.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gtaemarclo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxuanxn.top/Article/details/gtlosufzgm.html

[T48] Perl：正则替换
来源：http://dali.zhoulong.xyz/Article/details/gttxihzoxk.html

$s =~ s/old/new/g;
来源：http://dali.fengsongda.top/Article/details/gtntxmnrwh.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gtofphpsbm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gthloltlbu.html

[T50] Perl：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtsimfhpvq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuanzx.com/Article/details/gtmeqkhiow.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cqqwz.cn/Article/details/gtheaemepn.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gtyuyktaga.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtxpxyoldz.html

[T52] Scala：变量
来源：http://dali.gzhubu.top/Article/details/gthgqiijcz.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gtqtwsmeto.html

[T53] Scala：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtuirimazi.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtvahyhbkw.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpdmsxwg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dashuyun.cn/Article/details/gtkjbyypze.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtzjpzgycx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gtoffhrthr.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gtgxnimmnm.html

case class User(name: String, age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtinrbjlpz.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gteftpaafc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258.top/Article/details/gtwlqimzbs.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gtzdcrcmwa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqmqftfo.html

[T59] Scala：循环
来源：http://dali.tian-w.cn/Article/details/gtdnvakayi.html

for (i <- 1 to 10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtobqllwui.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gtpjfhsxes.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ydzc1.top/Article/details/gtbrktcwbv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsfkhkrmn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtbudoshtf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtufdkxwxr.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gtdzivgohu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gttfapfvho.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jianghu66.top/Article/details/gtlplinbhp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gtolsmygww.html

[U03] Py：加载 .env 配置
来源：http://dali.guannengcc.top/Article/details/gtrvglwfip.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sufxvd.cn/Article/details/gtkkamaxio.html

[U04] Py：变量调试打印
来源：http://dali.yuxming.cn/Article/details/gtfdwvndfr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ivvv.top/Article/details/gtjlogoson.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gtkpcvsuro.html

list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtannfrlpk.html

[U06] Py：合并两个字典
来源：http://dali.nanxinkj.top/Article/details/gtrchbcffv.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gthooqbdna.html

[U07] Py：反转字典键值
来源：http://dali.c1oappe.top/Article/details/gtrhygfool.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gtqagnnvjy.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtsoyopyvi.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gtqhzjuwds.html

[U09] Py：字典取最大值的键
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhrnerty.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gtomdmzebt.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtbmythgeo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gtmsuyrojj.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtzhjywoat.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gtomgehzis.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gtsusorwdy.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtmdfovsaw.html

[U13] Py：固定长度队列
来源：http://dali.sufxvd.cn/Article/details/gtedkjaxgz.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gtrqdmkxur.html

[U14] Py：分组收集到列表
来源：http://dali.gogol.net.cn/Article/details/gtyhlkppuu.html

defaultdict(list)
来源：http://dali.yuanzhike.top/Article/details/gtblsufmmy.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gtxjpqnauc.html

t = time.perf_counter()
来源：http://dali.hfpthk.cn/Article/details/gtzktqqcdf.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gtofadhfpv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gthnwzsiiv.html

[U17] Py：初始化日志
来源：http://dali.jiagoushi.top/Article/details/gtiaaipahu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbywixfv.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gtnqovwfva.html

pat = re.compile(r"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtjdsxdgae.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gtkolysadx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyskryci.html

[U20] Py：缓存函数结果
来源：http://dali.sysykeji.top/Article/details/gtstqqsddw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cashguo.top/Article/details/gtnwrtauzm.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gtwuvymowq.html

@contextlib.contextmanager
来源：http://dali.hnqzz.top/Article/details/gtzngrdaui.html

[U22] Py：矩阵转置
来源：http://dali.ivvv.top/Article/details/gthrtsnzej.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gtayuveznm.html

[U23] Py：分块读取大文件
来源：http://dali.yueranfly.top/Article/details/gtzurvoqyo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhozomtr.html

[U24] Py：路径操作
来源：http://dali.iojbl.cn/Article/details/gtnwvjocob.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gtwpdfibss.html

[U25] Py：CSV 按字典读
来源：http://dali.aibaodan.cn/Article/details/gtatimaysj.html

csv.DictReader(f)
来源：http://dali.meibo888.top/Article/details/gtxjwrrpqn.html

[U26] Py：并发下载
来源：http://dali.daria6918.cn/Article/details/gtdhpngzst.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hywenlv.cn/Article/details/gtrdklcdyo.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gtyutibcvt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.redwolf501.top/Article/details/gtsiikntvt.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gtjmndzmng.html

UserId = int
来源：http://dali.nwbrower.top/Article/details/gtczdqovjw.html

[U29] Py：属性校验
来源：http://dali.wangdashe.top/Article/details/gtxxzpasbx.html

@property 与 @x.setter 配合
来源：http://dali.316326.xyz/Article/details/gtfpxlhefr.html

[U30] Py：数据类
来源：http://dali.jqgfzy.top/Article/details/gtwzmxrlii.html

@dataclass(slots=True)
来源：http://dali.daria6918.cn/Article/details/gttjtmihjx.html

[U31] Py：单测
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezyebhrb.html

python -m pytest -q
来源：http://dali.smart0.xyz/Article/details/gtuioajuhg.html

[U32] Py：代码格式化
来源：http://dali.zhengqikj.top/Article/details/gtnpasefxj.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfxzpogz.html

[U33] Py：打包发布
来源：http://dali.tianlin.xyz/Article/details/gtmbdexdas.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gtqmgdeqbc.html

[U34] Py：判断编码
来源：http://dali.tianlin.xyz/Article/details/gtivrflqxi.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gttnkzarkw.html

[U35] Py：发送邮件
来源：http://dali.wangdashe.top/Article/details/gtbcjvtddi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sweek.top/Article/details/gtlwecqhte.html

[U36] Py：定时任务
来源：http://dali.shuidangran.top/Article/details/gtojvdhhtm.html

schedule.every(10).minutes.do(job)
来源：http://dali.hongshengwenyu.top/Article/details/gtkiwewogc.html

[U37] Py：读写 Excel
来源：http://dali.316326.xyz/Article/details/gtzyrwtvbk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sweek.top/Article/details/gthpiluolw.html

[U38] Py：获取脚本所在目录
来源：http://dali.ehwqpu.com/Article/details/gtejwxvaep.html

Path(__file__).resolve().parent
来源：http://dali.0kj1m.cn/Article/details/gtwpwccljm.html

[U39] Py：判断是否在交互环境
来源：http://dali.svipenyu.cn/Article/details/gtylxloiup.html

sys.stdout.isatty()
来源：http://dali.jqgufenzy.top/Article/details/gtnrisenaj.html

[U40] Py：打印到标准错误
来源：http://dali.hnxiangtu.top/Article/details/gtqsgvdiaw.html

print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtcfetgqbn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhixingplan.top/Article/details/gtcuoxfiwj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangdashe.top/Article/details/gtvtcwndmq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmzujmsn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtortzynoz.html

[U43] PHP：声明命名空间
来源：http://dali.sufxvd.cn/Article/details/gtigguhkmg.html

namespace App\Http;
来源：http://dali.sxryk.cn/Article/details/gtxilallul.html

[U44] PHP：开启严格类型
来源：http://dali.yueranfly.top/Article/details/gtuyyeabeo.html

declare(strict_types=1);
来源：http://dali.andypj.xyz/Article/details/gtbwxaxbhc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gtxfhxoviu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gthbuhmqck.html

[U46] PHP：可空类型
来源：http://dali.yj20258888.top/Article/details/gtidwxnmuk.html

?string $name = null
来源：http://dali.yangfankeji.com/Article/details/gtevaibwfp.html

[U47] PHP：联合类型
来源：http://dali.wangshuangyany.cn/Article/details/gthxskwmnl.html

int|string $id
来源：http://dali.hongshengwenyu.top/Article/details/gttvpwfzst.html

[U48] PHP：纯枚举
来源：http://dali.xylfe.cn/Article/details/gtvxjigoxe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dashuyun.cn/Article/details/gtsuvdnbgg.html

[U49] PHP：只读属性
来源：http://dali.feifeiyinyue.top/Article/details/gtzgcouawy.html

public readonly string $name
来源：http://dali.meibo888.top/Article/details/gtbalcjjbe.html

[U50] PHP：构造器属性提升
来源：http://dali.birdmap.top/Article/details/gtqtbcmvpy.html

public function __construct(private int $id) {}
来源：http://dali.sweek.top/Article/details/gtfamgmlit.html

[U51] PHP：数组解构
来源：http://dali.0kj1m.cn/Article/details/gtoobotfip.html

[$a, $b] = $arr;
来源：http://dali.xuanzx.com/Article/details/gttiivtnud.html

[U52] PHP：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gttenhcbuk.html

$double = fn($x) => $x * 2;
来源：http://dali.zycfv.cn/Article/details/gtjegxiiyj.html

[U53] PHP：空合并运算符
来源：http://dali.gotoacloud.top/Article/details/gtiubpfwql.html

$v = $a ?? $b ?? "default";
来源：http://dali.redwolf501.top/Article/details/gtrpsevkse.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gtpkxvkeqv.html

$obj?->method()
来源：http://dali.hongshengwenyu.top/Article/details/gtgrjkgozk.html

[U55] PHP：match 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnljumti.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gtykrribob.html

[U56] PHP：命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtorisyhln.html

f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtcqduwkrd.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtvzxxyock.html

"值: {$a}"
来源：http://dali.xuanzx.com/Article/details/gttowcdvnv.html

[U58] PHP：数组三件套
来源：http://dali.aizwys.cn/Article/details/gtuyckjmns.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gttuwqwsly.html

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gtkftagqvl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtaorsizsf.html

[U60] PHP：JSON 编解码
来源：http://dali.tian-w.cn/Article/details/gtuamhmgcm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gtcomezsss.html

[U61] PHP：正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmeiogpmx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtfonyvnkc.html

[U62] PHP：日期对象
来源：http://dali.wangdashe.top/Article/details/gthypnokxz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gogol.net.cn/Article/details/gtnnaffbgf.html

[U63] PHP：文件读写
来源：http://dali.sweek.top/Article/details/gtkgpkadoc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fengsongda.top/Article/details/gttvfzfgxu.html

[U64] PHP：目录遍历
来源：http://dali.jinqigufen.top/Article/details/gtdligrvyh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jyoumei.cn/Article/details/gthpgesxqb.html

[U65] PHP：会话
来源：http://dali.guannengcc.top/Article/details/gtktqymvas.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtvfzbnmyk.html

[U66] PHP：设置 Cookie
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhiczpuz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ybcxt.top/Article/details/gtylldplnj.html


<!-- 参考信息 -->