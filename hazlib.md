代发 wailian999

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtzpjoxalt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtinfzzqaj.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gtndiqrfyx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gtzpugttnp.html

[S35] C++：map
来源：http://dali.hnxiangtu.top/Article/details/gtboodjjya.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtptwaeqxf.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gthmeqxydh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtaoxomaed.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtrakoctoy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gtgvekgacn.html

[S38] C++：排序
来源：http://dali.sxryk.cn/Article/details/gtupjufrqr.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtcdnzhtqm.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gtmmujhcve.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtlqyxqjzx.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtrgfxcjhe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gtirecmdxh.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gtpmnbqowt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtugdwwhuu.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gtgmfymyip.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gtsqggbste.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gtwlryrhyp.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtetqtohkq.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gtzxkwpvul.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gtciucqove.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtliagynmr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtkpdfmrlq.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gtvpjvuirl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gtuqartzgd.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtyvwsvcbj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtpgcxnils.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtxvfookoj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtkhbvkbvs.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtfbigebak.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtrnuchobh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gtxdwacrvf.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gtptgzzuvk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtkoagmldg.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gthuejhewa.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gtijxxogke.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gtobnrxaya.html

int size() const noexcept { return n_; }
来源：http://dali.sweek.top/Article/details/gtuewwqiqg.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtdtnijdhb.html

std::vector<int> w = std::move(v);
来源：http://dali.ppjwa.cn/Article/details/gtumtbyaho.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gtihywwmck.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gtfzxegkpz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gtzdjelbvh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtxlpwardo.html

[S56] C++：optional
来源：http://dali.hnxiangtu.top/Article/details/gtajxlfpwj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gtwlvmnezr.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtpbqfldyd.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtnwhqlfem.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtjbtixqyk.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtwxaejifv.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gtfjurdwct.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtdqlwynzz.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gtdihbiqlz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gttbzjksyw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtequibgeh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gtroabxscl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdpgmmfkv.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtltqefnue.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtocvusqpj.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtzklspppr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gtbwryjemy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gthdxkgopm.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtmllglsgn.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtoolshssj.html

val n: String? = null;  n?.length
来源：http://dali.guowangkeji.top/Article/details/gtaqarqfbo.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gtqvvpatzz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gttkutnybj.html

[T06] Kotlin：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtybpeljkb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gteszmjcbk.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtlljqqcaq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtnidmjviw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gthpialuxn.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gtnpfcexrp.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtappsppry.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtczsjelsi.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gtezgsrgkv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gtpkbhtaua.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gthrbtzsrd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtkuhzshoc.html

[T12] Kotlin：解构声明
来源：http://dali.ybcxt.top/Article/details/gtklbbotdy.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyywrtabp.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gtjjtloyqu.html

val m = mapOf("a" to 1)
来源：http://dali.yangfankeji.com/Article/details/gtgiujvkne.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gtyvxwhmkj.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtrrjzlxsd.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gtawmucasy.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gthhdldqbf.html

[T16] Swift：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtzkwsjnwo.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtjufqxtob.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtopjvcint.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtgpuucxtx.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtpiwatlge.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gtmrdhmmul.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gtosqhjakk.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gtnqckvqvk.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gtdgrjdvyy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgojalga.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gtqwmtttdt.html

for x in a { print(x) }
来源：http://dali.yonumen.top/Article/details/gtscscnuro.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gtdbhpadhg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtcdkrwyzk.html

[T23] Swift：函数
来源：http://dali.chenlongwang.top/Article/details/gtqggmdhbh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsytbmvqv.html

[T24] Swift：闭包
来源：http://dali.birdmap.top/Article/details/gtdbuqxibr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtoamrikvh.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtwxdisjej.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtxywcgtlr.html

[T26] Swift：类与重写
来源：http://dali.c1oappe.top/Article/details/gtngqsrleg.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gtjkflnsfw.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gtqqvzwxqd.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gtvjetbqnc.html

[T28] Swift：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtyrgdjwff.html

enum Color { case red, green }
来源：http://dali.smart0.xyz/Article/details/gtjjvqxofl.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gtrekteyil.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtakqtnlci.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gtayyqclsx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhengqikj.top/Article/details/gtyhkzdvhg.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gtlfxyhnyg.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddhthoyw.html

[T32] Lua：局部变量
来源：http://dali.jqgfzy.top/Article/details/gtbvocnzgs.html

local a = 1
来源：http://dali.ydzc1.top/Article/details/gtxuaywypj.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgdijubo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gtomfdutfy.html

[T34] Lua：遍历表
来源：http://dali.fengsongda.top/Article/details/gthpiugfpt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gtmeovcglt.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyhpsorq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gtaqdrcgac.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gtlqolqsmo.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gtfbdgtwhj.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gtxpydutdg.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gtsimsqbry.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gtysbjvslz.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gtzhsbievs.html

[T39] Lua：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtisaxhtqg.html

string.find(s, "%d+")
来源：http://dali.yuxming.cn/Article/details/gtrvvkxzdi.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gteqbwqgti.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gtgpcpchfx.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gtcazyzutv.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtcuxarmft.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gtkgxcegnf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gtjpownopf.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtrstpajvd.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gttyyjhgop.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gtzbtftehl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gtxjahujnt.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gtabqiffxx.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gtxxpjvcvj.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtrxzjehiy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtmelopndj.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gtukonnjub.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbhgkaah.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvwbtfxl.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtwjkgosqg.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtronakayn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gthnkjavag.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gthzmzqfet.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yonumen.top/Article/details/gtptlvezre.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yongpay.top/Article/details/gtspamcano.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gtluwxypxq.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtgczvzlos.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gtvgayqpau.html

val a = 1;  var b = 2
来源：http://dali.sxryk.cn/Article/details/gtdnxqpjke.html

[T53] Scala：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtvttqjhwb.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtqekghpxv.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gtvbtrkzjm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guowangkeji.top/Article/details/gtwticdlwg.html

[T55] Scala：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtkzfcfdtk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtshqmziuv.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gtuqguoria.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gttfabaynn.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtqdstbeow.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gtwljmwepv.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gtmsqkceuq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtrbucrzkv.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gtkfxcljmj.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtcfgmwswl.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gtodwdoymv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zdqjudy.top/Article/details/gtjiodugon.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtllbyalvb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gtfsvmonvo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfepuudtm.html

[U01] Py：创建虚拟环境
来源：http://dali.fengsongda.top/Article/details/gtgdyzjenn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gtcobjqefc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ehwqpu.com/Article/details/gtvqxrusph.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenzaomai.com/Article/details/gthivnczqv.html

[U03] Py：加载 .env 配置
来源：http://dali.0kj1m.cn/Article/details/gtdrvjakox.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ydzc1.top/Article/details/gtkwowtwyc.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtmdsrgqro.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gotoacloud.top/Article/details/gtrdvqmfgf.html

[U05] Py：列表去重且保序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimrtadqz.html

list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtjkuukkhm.html

[U06] Py：合并两个字典
来源：http://dali.jqgfzy.top/Article/details/gtgdrzsoxh.html

{**a, **b}
来源：http://dali.cucudq.cn/Article/details/gtokpegplc.html

[U07] Py：反转字典键值
来源：http://dali.feifeiyinyue.top/Article/details/gtxfejpemv.html

{v: k for k, v in d.items()}
来源：http://dali.wangshuangyany.cn/Article/details/gtpsvvyrfd.html

[U08] Py：展平二维列表
来源：http://dali.dianchejie.cn/Article/details/gtuawyapcg.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gtuqhoednq.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjaqxqdf.html

max(d, key=d.get)
来源：http://dali.dianchejie.cn/Article/details/gtvpymwcsy.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gtfzpcbtsb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gtomwcejom.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gtlmpvvgjr.html

(x * 2 for x in arr)
来源：http://dali.gaohongyu789.top/Article/details/gttdxaowly.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gtkflbayab.html

Counter(arr).most_common(3)
来源：http://dali.yanxiufei.cn/Article/details/gtvanzhrkg.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gtipncsyub.html

deque(maxlen=10)
来源：http://dali.dashuyun.cn/Article/details/gteonpodlr.html

[U14] Py：分组收集到列表
来源：http://dali.xziqi.cn/Article/details/gtyhaawovf.html

defaultdict(list)
来源：http://dali.jinqigufen.top/Article/details/gtkhdhtarv.html

[U15] Py：高精度计时
来源：http://dali.cashguo.top/Article/details/gtfaaeifer.html

t = time.perf_counter()
来源：http://dali.dashuyun.cn/Article/details/gtcpudodky.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gtrbfmycpm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gtsielyhqd.html

[U17] Py：初始化日志
来源：http://dali.jyoumei.cn/Article/details/gtkzpoxfmx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daxiang520.top/Article/details/gtqxftfjav.html

[U18] Py：预编译正则
来源：http://dali.hnqzz.top/Article/details/gtypmlxtux.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gttduqgqhl.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gtvzxaubca.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangshuangyany.cn/Article/details/gtxlfgrmhe.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gtwhsdnpyi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gtwxlumpyx.html

[U21] Py：自定义上下文管理器
来源：http://dali.shangyingyoupin.top/Article/details/gtwfizfcle.html

@contextlib.contextmanager
来源：http://dali.xziqi.cn/Article/details/gtmnnondud.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gtyjrzvpaa.html

list(zip(*m))
来源：http://dali.yuxming.cn/Article/details/gtbbgvlsoc.html

[U23] Py：分块读取大文件
来源：http://dali.yueranfly.top/Article/details/gttcgsvbxg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigufen.top/Article/details/gtxbgumobs.html

[U24] Py：路径操作
来源：http://dali.xuanzx.com/Article/details/gtamqmbcdi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrweyskns.html

[U25] Py：CSV 按字典读
来源：http://dali.daxiang520.top/Article/details/gtylhurxvz.html

csv.DictReader(f)
来源：http://dali.jyoumei.cn/Article/details/gtornwishx.html

[U26] Py：并发下载
来源：http://dali.quarkkingdee.top/Article/details/gtibrdzzon.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jianghu66.top/Article/details/gtnkrlmclp.html

[U27] Py：异步 HTTP
来源：http://dali.ydzc1.top/Article/details/gtqqlgtqsp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gtaobisczm.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gtpekspsmn.html

UserId = int
来源：http://dali.xuetiantiany.cn/Article/details/gtxpjtkixm.html

[U29] Py：属性校验
来源：http://dali.9152youxi.cn/Article/details/gtzziyemgz.html

@property 与 @x.setter 配合
来源：http://dali.pengpengdd.cyou/Article/details/gtauyaqosj.html

[U30] Py：数据类
来源：http://dali.cashguo.top/Article/details/gttspnusmn.html

@dataclass(slots=True)
来源：http://dali.cashguo.top/Article/details/gtsgxwlphh.html

[U31] Py：单测
来源：http://dali.chenzaomai.com/Article/details/gtyrlyvfik.html

python -m pytest -q
来源：http://dali.nanxinkj.top/Article/details/gtnmbsnxug.html

[U32] Py：代码格式化
来源：http://dali.gotoacloud.top/Article/details/gtkusjwonr.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gtvorxrfww.html

[U33] Py：打包发布
来源：http://dali.hnxiangtu.top/Article/details/gtisxjykak.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cdnleiting.top/Article/details/gtgpvzorur.html

[U34] Py：判断编码
来源：http://dali.meibo888.top/Article/details/gtnutajgim.html

chardet.detect(raw)
来源：http://dali.zhixingplan.top/Article/details/gtncwexpbb.html

[U35] Py：发送邮件
来源：http://dali.fengsongda.top/Article/details/gtezhuegrc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jyoumei.cn/Article/details/gtqkmpywyp.html

[U36] Py：定时任务
来源：http://dali.sufxvd.cn/Article/details/gtbgwbohvs.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gtprcplzpz.html

[U37] Py：读写 Excel
来源：http://dali.xuetiantiany.cn/Article/details/gtkrtgzwxq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.smart0.xyz/Article/details/gtrfmowowo.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenjidiqi.icu/Article/details/gtldzkuynj.html

Path(__file__).resolve().parent
来源：http://dali.cdnleiting.top/Article/details/gtiizevdax.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangshuangyany.cn/Article/details/gtvypcmlaf.html

sys.stdout.isatty()
来源：http://dali.cucudq.cn/Article/details/gtmcgrqamu.html

[U40] Py：打印到标准错误
来源：http://dali.svipenyu.cn/Article/details/gthlbyuapi.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtaxkwrscx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gttdgeulse.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dianchejie.cn/Article/details/gtecifynef.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hfpthk.cn/Article/details/gtorsxwzbj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvxawobc.html

[U43] PHP：声明命名空间
来源：http://dali.jyoumei.cn/Article/details/gtzswuhykt.html

namespace App\Http;
来源：http://dali.kuanghao11.cn/Article/details/gtxlzjgdih.html

[U44] PHP：开启严格类型
来源：http://dali.haohaochexian.top/Article/details/gtewxopxwd.html

declare(strict_types=1);
来源：http://dali.ivvv.top/Article/details/gtknagnfui.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xinyue.icu/Article/details/gtwjmtnvos.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtieslsrgw.html

[U46] PHP：可空类型
来源：http://dali.yongpay.top/Article/details/gtedagsdjf.html

?string $name = null
来源：http://dali.hysaishi.cn/Article/details/gtbkqozxoy.html

[U47] PHP：联合类型
来源：http://dali.jlsjyb.cn/Article/details/gtqvvhkoan.html

int|string $id
来源：http://dali.smart0.xyz/Article/details/gtxfzymfxq.html

[U48] PHP：纯枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtcxloirui.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoulfmiuv.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gtyaceqdvp.html

public readonly string $name
来源：http://dali.gogol.net.cn/Article/details/gtilkqgckw.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gtqmbprwre.html

public function __construct(private int $id) {}
来源：http://dali.hfpthk.cn/Article/details/gtoykrbupg.html

[U51] PHP：数组解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqkigouy.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gtnoaeeefc.html

[U52] PHP：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gtobaexaqs.html

$double = fn($x) => $x * 2;
来源：http://dali.ehwqpu.com/Article/details/gtqiagvdtu.html

[U53] PHP：空合并运算符
来源：http://dali.shzxlz.cn/Article/details/gteyrrkmuy.html

$v = $a ?? $b ?? "default";
来源：http://dali.dianchejie.cn/Article/details/gtncwyagnd.html

[U54] PHP：空安全调用
来源：http://dali.jinqigufen.top/Article/details/gtvflvtrwi.html

$obj?->method()
来源：http://dali.sxryk.cn/Article/details/gtlcytfkig.html

[U55] PHP：match 表达式
来源：http://dali.jqgfzy.top/Article/details/gtxkyzpjdp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sysykeji.top/Article/details/gtqacvfrxz.html

[U56] PHP：命名参数
来源：http://dali.yj20258888.top/Article/details/gtfspnegbc.html

f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtwbbmvpbr.html

[U57] PHP：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlqdcspu.html

"值: {$a}"
来源：http://dali.hfpthk.cn/Article/details/gtrgvmlmjt.html

[U58] PHP：数组三件套
来源：http://dali.yuanzhike.top/Article/details/gtfesgogpw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtfifoymws.html


<!-- 参考信息 -->