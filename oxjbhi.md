代发 wailian999

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gtspakrcxb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gthirbtrgt.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gtsbdicynb.html

std::sort(v.begin(), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtifiwjjdj.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gtcauqgeor.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtajobpdar.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtawymimxd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gtohcjpggk.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtluirryba.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtjcwcjbxu.html

[S42] C++：继承与虚函数
来源：http://dali.yongpay.top/Article/details/gtdlbxnqac.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gtsbnnqnmf.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiiljagwh.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gthukkdtsn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtoluorbek.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gtpwlqzdms.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtffxokvci.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gtkzwywfwx.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtlklpvjtz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqjmsdav.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtewhhpbwm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gtqqkegaed.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtlznvfouk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtcarthptw.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gtmeoxvteu.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gtwdcsbrmg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gtipadxtqu.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gtcxzvrnhv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtfzucxidz.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtwjpktvjt.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gthdkflvwu.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtgjtzxtcs.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gttnktyphz.html

[S53] C++：移动语义
来源：http://dali.aibaodan.cn/Article/details/gthsysdkyn.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gtiwkwazdu.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gtljmpqluc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtttpwbtnp.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtyvvaolvv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtxqqbhsue.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtmpmxjdzz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gtyxuurnjp.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gtvimdneqc.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gtpdhezfas.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gtxhowqwix.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwvjkssn.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gtyroteoxl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtkxdmgzrs.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtbwratllz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gtcbdaitdd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtprpbvune.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtucgpoopk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdcfbuubk.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtcmukvagi.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtjyqubcyr.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gtupkusuof.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jiagoushi.top/Article/details/gtevfczoko.html

[T03] Kotlin：字符串模板
来源：http://dali.hammf.cn/Article/details/gtadcmpkom.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gterrjmmqu.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gtgyxovpak.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gtvcdztfod.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtudyjziwn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gtjtdrltxu.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gtbvruapbw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtkxfjqsan.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtaoibghuv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtdkpkrxym.html

[T08] Kotlin：数据类
来源：http://dali.cqqwz.cn/Article/details/gtpfyceqzo.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtowrgnbkw.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gtyxqxjwpj.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gtkflzvqmn.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gtrrgjuoem.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gtpggehmjz.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gtyvcjojah.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gtuoecirhe.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gtygiuzbra.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtnkpbbgdl.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gtblzlmcvj.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gtbzsuvvib.html

[T14] Kotlin：循环
来源：http://dali.tanke756.top/Article/details/gtboqrnlhk.html

for (i in 1..10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtwhsojokm.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gtxnacfbdw.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtdabpyapk.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gtmusecznq.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtfmvfftvo.html

[T17] Swift：变量与常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpahybfog.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtxhlltgfm.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtnkwuckba.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gtzixnoxoo.html

[T19] Swift：可选绑定
来源：http://dali.jqgfzy.top/Article/details/gtgpdrwksu.html

if let n = opt { print(n) }
来源：http://dali.yonumen.top/Article/details/gtcklvipjf.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtkycpzqeu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gtqkyreafx.html

[T21] Swift：遍历
来源：http://dali.hnxiangtu.top/Article/details/gtqspoekbe.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gtxndqotxi.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtroyeusoi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtwivjneyv.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtbcvitytn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gtlkanatlv.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtrejhcpss.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtdizsmily.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gtmzicxtzp.html

struct P { var x: Int }
来源：http://dali.dianchejie.cn/Article/details/gtkmvglgfc.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gtecwditbi.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gtopclefnx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtiascmsdp.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaywmuxj.html

[T28] Swift：枚举
来源：http://dali.zdqjudy.top/Article/details/gtevjcvfje.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtetehubsy.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gtcmrwzglc.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtnzadjzsx.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtifexdgpc.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gtygubwyhp.html

[T31] Lua：Hello World
来源：http://dali.daria6918.cn/Article/details/gtixieavif.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtvwvfslcz.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtyfklpvil.html

local a = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeileyed.html

[T33] Lua：表（数组）
来源：http://dali.ehwqpu.com/Article/details/gtnqxybuzn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gtgswswvge.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gtakwucgsu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gtkcyfevji.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gtugnljstp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gtkyzenytk.html

[T36] Lua：函数
来源：http://dali.yangfankeji.com/Article/details/gtwwrnqlot.html

function add(a, b) return a + b end
来源：http://dali.hammf.cn/Article/details/gtzglylawg.html

[T37] Lua：字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtojlbufqu.html

"a" .. "b"
来源：http://dali.tian-w.cn/Article/details/gtnxovhggo.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtjrqdwasl.html

if x > 0 then print("正") end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkedworcm.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrxwiwpl.html

string.find(s, "%d+")
来源：http://dali.hammf.cn/Article/details/gtqyjaqwcx.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gtiygjaskq.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gtwnlvrnzu.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtbfzhiujl.html

print "Hello\n";
来源：http://dali.guannengcc.top/Article/details/gtsubkhavj.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gtxmxlqgzs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtymebldtd.html

[T43] Perl：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtbghbgjvq.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gteetyriaq.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtsxyodkkw.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtrfmjbnby.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gtxnzthzcq.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gtwgrjsczj.html

[T46] Perl：哈希操作
来源：http://dali.yuanzhike.top/Article/details/gttimqwrqe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gtzcvupabm.html

[T47] Perl：正则捕获
来源：http://dali.yangfankeji.com/Article/details/gtbrzzpsfn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlruzlzjz.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gtzddelixq.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gtxjskxbvd.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gtmurqefhv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gttszojawt.html

[T50] Perl：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtcfuxgkax.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gtseshtsnx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yueranfly.top/Article/details/gtzpjjkafn.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtsptkvxum.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtvwvllwim.html

[T52] Scala：变量
来源：http://dali.316326.xyz/Article/details/gttfeshnxa.html

val a = 1;  var b = 2
来源：http://dali.jyoumei.cn/Article/details/gtjaxwlmhu.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtbpcjqewd.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtutuvkogh.html

[T54] Scala：集合映射
来源：http://dali.cashguo.top/Article/details/gtzejlneto.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtyioqxfmo.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsixfdxb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gtuwwfvoon.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gttqvqhxvb.html

case class User(name: String, age: Int)
来源：http://dali.yj20258888.top/Article/details/gtijjccibd.html

[T57] Scala：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtvyusiakn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gttpkwwohj.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gtiblnaeaw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gtjjzfarbp.html

[T59] Scala：循环
来源：http://dali.c1oappe.top/Article/details/gtnhomhqoy.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtofnytncb.html

[T60] Scala：折叠
来源：http://dali.guannengcc.top/Article/details/gtrrshzmvy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtplcmeieb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtuofbiwcg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gtiyhxjgmk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyyeikmro.html

[U01] Py：创建虚拟环境
来源：http://dali.ydzc1.top/Article/details/gtabhlgcfh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gtekbiyjdp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sufxvd.cn/Article/details/gtpqvtujfd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gtzbuggkte.html

[U03] Py：加载 .env 配置
来源：http://dali.zdqjudy.top/Article/details/gtkokvfcpu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xylfe.cn/Article/details/gtecdbkmtp.html

[U04] Py：变量调试打印
来源：http://dali.pengpengdd.cyou/Article/details/gtmyalsauw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.mhx1999.top/Article/details/gtpdnqqxvq.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gtabaxgakp.html

list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtzhzaietn.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gttebeqktj.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gthejgkpsb.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gtotjlqyxh.html

{v: k for k, v in d.items()}
来源：http://dali.sufxvd.cn/Article/details/gtanoeupub.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtuiteegfu.html

[y for x in nested for y in x]
来源：http://dali.nwbrower.top/Article/details/gtpqrnjfon.html

[U09] Py：字典取最大值的键
来源：http://dali.nwbrower.top/Article/details/gtgsmwhilf.html

max(d, key=d.get)
来源：http://dali.yueranfly.top/Article/details/gtwbvwxrjc.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gtyekowujl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shzxlz.cn/Article/details/gtrcdivpfg.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gtrienqnyk.html

(x * 2 for x in arr)
来源：http://dali.ybcxt.top/Article/details/gttspeeqdz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhengqikj.top/Article/details/gttkcacahk.html

Counter(arr).most_common(3)
来源：http://dali.yj20258888.top/Article/details/gtwrxpjmbo.html

[U13] Py：固定长度队列
来源：http://dali.quarkkingdee.top/Article/details/gtbkvtvkyf.html

deque(maxlen=10)
来源：http://dali.feifeiyinyue.top/Article/details/gtpmgisovz.html

[U14] Py：分组收集到列表
来源：http://dali.haohaochexian.top/Article/details/gtqassdomq.html

defaultdict(list)
来源：http://dali.yongpay.top/Article/details/gturqjbqlg.html

[U15] Py：高精度计时
来源：http://dali.gaohongyu789.top/Article/details/gtrnphdiiq.html

t = time.perf_counter()
来源：http://dali.xinyue.icu/Article/details/gtawiarqjw.html

[U16] Py：命令行参数解析
来源：http://dali.gogol.net.cn/Article/details/gtnmmppzjk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gtopnblfnu.html

[U17] Py：初始化日志
来源：http://dali.aizwys.cn/Article/details/gtjgtqbgvv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gtinrcbwgd.html

[U18] Py：预编译正则
来源：http://dali.nanxinkj.top/Article/details/gtxmpwybva.html

pat = re.compile(r"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaicuqye.html

[U19] Py：正则替换带回调
来源：http://dali.yj202588.top/Article/details/gtxdvnkkrx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gtzshjxrlj.html

[U20] Py：缓存函数结果
来源：http://dali.vqdsnc.cn/Article/details/gttckfffqd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gtvsopztiv.html

[U21] Py：自定义上下文管理器
来源：http://dali.vqdsnc.cn/Article/details/gtchsgxszk.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gtnlrqjarc.html

[U22] Py：矩阵转置
来源：http://dali.smart0.xyz/Article/details/gtqhecdhuc.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gtojxhopei.html

[U23] Py：分块读取大文件
来源：http://dali.shangyingyoupin.top/Article/details/gtdqlujqme.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiggpvvao.html

[U24] Py：路径操作
来源：http://dali.hfpthk.cn/Article/details/gtajjdjqkg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gthggpnqos.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxinkj.top/Article/details/gtdltoilzb.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gtrsdbnwoi.html

[U26] Py：并发下载
来源：http://dali.sufxvd.cn/Article/details/gtfpwjobte.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sxryk.cn/Article/details/gtluvuruvj.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gtlgotaigf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhengqikj.top/Article/details/gtjelzflda.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gtcilcqplf.html

UserId = int
来源：http://dali.yj202588.top/Article/details/gtagqzfqbl.html

[U29] Py：属性校验
来源：http://dali.xuanzx.com/Article/details/gtpgnxolsc.html

@property 与 @x.setter 配合
来源：http://dali.jqgfzy.top/Article/details/gtpncyezew.html

[U30] Py：数据类
来源：http://dali.birdmap.top/Article/details/gtclgqbvwb.html

@dataclass(slots=True)
来源：http://dali.hysaishi.cn/Article/details/gtizgzjgfw.html

[U31] Py：单测
来源：http://dali.9152youxi.cn/Article/details/gttahutgrk.html

python -m pytest -q
来源：http://dali.aibaodan.cn/Article/details/gtcusccrfq.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtvgomnubf.html

ruff format . && ruff check --fix .
来源：http://dali.zdqjudy.top/Article/details/gtiwgobvot.html

[U33] Py：打包发布
来源：http://dali.nanxinkj.top/Article/details/gttlhjasnz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjxfybdh.html

[U34] Py：判断编码
来源：http://dali.hfpthk.cn/Article/details/gtadrhyiqc.html

chardet.detect(raw)
来源：http://dali.hongshengwenyu.top/Article/details/gtfvwclnzl.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gtlmdkvneo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgfzy.top/Article/details/gtxhqckali.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gtqdahmves.html

schedule.every(10).minutes.do(job)
来源：http://dali.xylfe.cn/Article/details/gtrvfgqvul.html

[U37] Py：读写 Excel
来源：http://dali.shangyingyoupin.top/Article/details/gtysipwqpu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nanxinkj.top/Article/details/gtoqotiqgg.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenjidiqi.icu/Article/details/gtmxzayluz.html

Path(__file__).resolve().parent
来源：http://dali.xziqi.cn/Article/details/gtlzoneehn.html

[U39] Py：判断是否在交互环境
来源：http://dali.shangyingyoupin.top/Article/details/gtivdrxili.html

sys.stdout.isatty()
来源：http://dali.tanke756.top/Article/details/gtujncldfo.html

[U40] Py：打印到标准错误
来源：http://dali.cqqwz.cn/Article/details/gtabrhpwev.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtqezahyzf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258888.top/Article/details/gtnofxpzyg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gtnntwkwyn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinghuilouyu.cn/Article/details/gtujgwhtqe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shzxlz.cn/Article/details/gtpbwmcqep.html

[U43] PHP：声明命名空间
来源：http://dali.chenlongwang.top/Article/details/gtvyzlllqb.html

namespace App\Http;
来源：http://dali.jianghu66.top/Article/details/gtoshpqppt.html

[U44] PHP：开启严格类型
来源：http://dali.nanxinkj.top/Article/details/gttvqstguz.html

declare(strict_types=1);
来源：http://dali.xuanzx.com/Article/details/gttpfjhryy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gtwoglpsps.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtztfcxdbm.html

[U46] PHP：可空类型
来源：http://dali.zdqjudy.top/Article/details/gtrmovboqr.html

?string $name = null
来源：http://dali.sweek.top/Article/details/gtugklbcbp.html

[U47] PHP：联合类型
来源：http://dali.ybcxt.top/Article/details/gtjplskjar.html

int|string $id
来源：http://dali.sxryk.cn/Article/details/gtuhplsvvp.html

[U48] PHP：纯枚举
来源：http://dali.zhongyouzk.top/Article/details/gtxbiqbplc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cheryme.top/Article/details/gttjobbgta.html

[U49] PHP：只读属性
来源：http://dali.ehwqpu.com/Article/details/gtgdptkptx.html

public readonly string $name
来源：http://dali.daria6918.cn/Article/details/gtenwwruna.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaquazyfz.html

public function __construct(private int $id) {}
来源：http://dali.yj202588.top/Article/details/gtfsqqjego.html

[U51] PHP：数组解构
来源：http://dali.xziqi.cn/Article/details/gtlniqimml.html

[$a, $b] = $arr;
来源：http://dali.ppjwa.cn/Article/details/gtcrhrxwuq.html

[U52] PHP：箭头函数
来源：http://dali.sweek.top/Article/details/gtqqjnnbjv.html

$double = fn($x) => $x * 2;
来源：http://dali.nwbrower.top/Article/details/gtytwdvprl.html

[U53] PHP：空合并运算符
来源：http://dali.hammf.cn/Article/details/gtybivnckm.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnqzz.top/Article/details/gtvxqcdonz.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gttidirsoz.html

$obj?->method()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvpuoybo.html

[U55] PHP：match 表达式
来源：http://dali.xylfe.cn/Article/details/gtqdofsepg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cucudq.cn/Article/details/gtqoozwbuw.html

[U56] PHP：命名参数
来源：http://dali.gogol.net.cn/Article/details/gtuvfmznzy.html

f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtpjkvyggm.html

[U57] PHP：字符串插值
来源：http://dali.sweek.top/Article/details/gtdsfeuksi.html

"值: {$a}"
来源：http://dali.vqdsnc.cn/Article/details/gtprunordl.html

[U58] PHP：数组三件套
来源：http://dali.haohaochexian.top/Article/details/gtptqbyejv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenlongwang.top/Article/details/gtbwcdhegd.html

[U59] PHP：自定义排序
来源：http://dali.yueranfly.top/Article/details/gtcaevlpde.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtijebntic.html

[U60] PHP：JSON 编解码
来源：http://dali.sufxvd.cn/Article/details/gtarhedyvo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtsiiruqmv.html

[U61] PHP：正则
来源：http://dali.chenjidiqi.icu/Article/details/gtzuzrfjsa.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtdtumudlj.html

[U62] PHP：日期对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiwjhbpw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinghuilouyu.cn/Article/details/gthrsinndi.html


<!-- 参考信息 -->