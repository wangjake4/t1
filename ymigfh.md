代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gteiwuyxvl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gtzynudeks.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gtzctdfvdj.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gtgbtetltd.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtjvyzfntj.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gtgenkkgfu.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtsmyiqygc.html

void inc(int &x) { ++x; }
来源：http://dali.ivvv.top/Article/details/gtktscjvuz.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gtzsugtzgy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gtsgjdlkmc.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gtwbgetooj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gtlykseynv.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gtcrlzvdzz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtpmlolnti.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtaqizrluq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.iojbl.cn/Article/details/gtchopxmgm.html

while (std::getline(in, line)) { }
来源：http://dali.daria6918.cn/Article/details/gtpucfwbyr.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtyvjhckuu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gtrhppfquu.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtexemqpza.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtqybebbat.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gtrrfkspju.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gtlcwqqjzz.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtymedsnpd.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gtctvlxwso.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtokybuptg.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gtgyvmeiqc.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtfopzgnef.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtezmnkfax.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gtuwgvryrj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtcvjqtkvx.html

[S56] C++：optional
来源：http://dali.shzxlz.cn/Article/details/gtnapclsfc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gtpyvptdrn.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gtwzqlptyp.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gtrhthhuld.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gtfymnnhug.html

namespace ns { int f() { return 1; } }
来源：http://dali.guowangkeji.top/Article/details/gtmymvhqzu.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gtsajayouc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gtfkduplfb.html

[S60] C++：遍历并删除元素
来源：http://dali.xylfe.cn/Article/details/gtdggynijs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtodbcycqb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpqqcmqrp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtncxxabra.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwvlpjoop.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtucfbjkpm.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtyrigjrmu.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gtunyquodo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gtpuxbfzov.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtbdohnjqm.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtmdvbvmtz.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtnqisezhw.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtmnyosler.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoebsyil.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gtenxowwyy.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gtfxadmqzz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gtxzxujwaa.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtbvnmrghk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gtovdfadop.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtaikzxctd.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gttzpbofuh.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbclydtwx.html

fun String.exclaim() = this + "!"
来源：http://dali.yuxming.cn/Article/details/gtbgjumnqt.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gtymfzhkfx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtzdzlujvr.html

[T11] Kotlin：协程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyflyjtf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gtijdgecyb.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gtoidwslxd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtgzyapdto.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtzyevntum.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gtloydohfu.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gttgohuwxn.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtzcdapwft.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gtonklwtfs.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gtbwgbdsob.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gtbxlvtgvs.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtjkzmmnhb.html

[T17] Swift：变量与常量
来源：http://dali.cashguo.top/Article/details/gtahjixcjf.html

var a = 1;  let b = 2
来源：http://dali.yj20258888.top/Article/details/gtkwhlgdsb.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtrjmqhbuu.html

"值: \(b)"
来源：http://dali.ehwqpu.com/Article/details/gtvlpwpbkg.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gtlbcofpot.html

if let n = opt { print(n) }
来源：http://dali.hnqzz.top/Article/details/gtcvsiqout.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gtfrbcueoa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gtgbrqdinn.html

[T21] Swift：遍历
来源：http://dali.hysaishi.cn/Article/details/gtvrecsivf.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtrgbcteem.html

[T22] Swift：字典
来源：http://dali.meibo888.top/Article/details/gtpczcnfzp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gteezmuvij.html

[T23] Swift：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnvdkdqt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gthpiiqgog.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gtuwzbyjwv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gtafedftsd.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gtdklfbnhr.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtwarsjcwe.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtpumimsyj.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gtkgvlilvo.html

[T27] Swift：错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtgbiigoyi.html

do { try f() } catch { print(error) }
来源：http://dali.snrcjt.cn/Article/details/gtzkxyeneb.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtrxjbxlpd.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtuhpnnqur.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gtumkvjifv.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtegtemjjw.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtybtbgzyo.html

protocol Shape { func area() -> Double }
来源：http://dali.smart0.xyz/Article/details/gtmbfraaiw.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gtoibjcwve.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtqxgjdijt.html

[T32] Lua：局部变量
来源：http://dali.zycfv.cn/Article/details/gtvhsjizlo.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gtnnxlsuya.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtljkzhjwe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.havefunace.top/Article/details/gtxmvlcpif.html

[T34] Lua：遍历表
来源：http://dali.xziqi.cn/Article/details/gthorndjtp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gtgvknjaut.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gtfjuitqbq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gtjdmspspr.html

[T36] Lua：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtqmicpxcy.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gtzbwspwqv.html

[T37] Lua：字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtnclpskwm.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gtkwqugeml.html

[T38] Lua：条件
来源：http://dali.iojbl.cn/Article/details/gtxoqanbxv.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtyhbvbnvt.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtqnygbgdm.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gtzrnigpsd.html

[T40] Lua：元表
来源：http://dali.sxryk.cn/Article/details/gtopxkhtud.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtetqyobfy.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gtolfpwmvu.html

print "Hello\n";
来源：http://dali.andypj.xyz/Article/details/gtfidyydwj.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtjcpmwlpf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cqqwz.cn/Article/details/gtklnxpefd.html

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtaglwcips.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtqrmqhkjc.html

[T44] Perl：条件
来源：http://dali.yueranfly.top/Article/details/gtwafjayae.html

if ($a > 0) { print "正"; }
来源：http://dali.yuxming.cn/Article/details/gtqgdlqode.html

[T45] Perl：数组遍历
来源：http://dali.yuanzhike.top/Article/details/gtnoyrplrj.html

for my $x (@arr) { print $x; }
来源：http://dali.ybcxt.top/Article/details/gtbruytbnw.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtgxpnqkhf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtbvkbyjwy.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpheyifwy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gtwpcqdbin.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtmckddskk.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gtjakzhtqi.html

[T49] Perl：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtafefgmvo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtrlrribnr.html

[T50] Perl：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtnsxxgnkp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtqvylxeoz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtnbbfjpxy.html

[T51] Scala：Hello World
来源：http://dali.mhx1999.top/Article/details/gtqaadzbhv.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfnucyqy.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtfgblnggz.html

val a = 1;  var b = 2
来源：http://dali.sxryk.cn/Article/details/gtlcvwiash.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gttcnkwfuz.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gtmmlwutlx.html

[T54] Scala：集合映射
来源：http://dali.fengsongda.top/Article/details/gtpgycttlb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtxllgweep.html

[T55] Scala：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtscanzudh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gtkscztskz.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gtdjhztyzl.html

case class User(name: String, age: Int)
来源：http://dali.aizwys.cn/Article/details/gtuvihlwrp.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtloibsxls.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtwsyhtine.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvogtogbo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gtldlpgswv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gtfckgncyh.html

for (i <- 1 to 10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtzxxrtupk.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtbcsctjei.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dashuyun.cn/Article/details/gtfjwhpyrl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqchgwswq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yvedp.cn/Article/details/gtoybkcvcy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkbhbdxuq.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gtvllctfrf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gtcoqxvnjw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gtfxmwflth.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnxiangtu.top/Article/details/gtoeqgabwb.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gtjjsteuul.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gtvkdtvrot.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gtaxmredkj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gtuqlkbcwq.html

[U05] Py：列表去重且保序
来源：http://dali.smart0.xyz/Article/details/gtxtxbtygj.html

list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtsintmqau.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gtmyufilms.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gtwttsrygc.html

[U07] Py：反转字典键值
来源：http://dali.gzhubu.top/Article/details/gtmttvbhat.html

{v: k for k, v in d.items()}
来源：http://dali.snrcjt.cn/Article/details/gticlkgkui.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexqkmpze.html

[y for x in nested for y in x]
来源：http://dali.snrcjt.cn/Article/details/gtrsocpytl.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gtwjqsdngv.html

max(d, key=d.get)
来源：http://dali.chenzaomai.com/Article/details/gtgcwcoxcw.html

[U10] Py：按值排序字典
来源：http://dali.cashguo.top/Article/details/gtzgpelfzf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yvedp.cn/Article/details/gtoeybevwe.html

[U11] Py：生成器表达式
来源：http://dali.fzhhl.top/Article/details/gtjmqizudw.html

(x * 2 for x in arr)
来源：http://dali.zdqjudy.top/Article/details/gtfmxmaqsl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.vqdsnc.cn/Article/details/gtazyhcjwa.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gtxmshqoep.html

[U13] Py：固定长度队列
来源：http://dali.yanxiufei.cn/Article/details/gtrgdpnwzs.html

deque(maxlen=10)
来源：http://dali.yuanzhike.top/Article/details/gtjedjydvx.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gtafvekxtr.html

defaultdict(list)
来源：http://dali.vqdsnc.cn/Article/details/gtesnnwboo.html

[U15] Py：高精度计时
来源：http://dali.hywenlv.cn/Article/details/gtdgvvliek.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gtifxlfelr.html

[U16] Py：命令行参数解析
来源：http://dali.sxryk.cn/Article/details/gtirlvcgfn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuanzhike.top/Article/details/gtyqjvnsxu.html

[U17] Py：初始化日志
来源：http://dali.quarkkingdee.top/Article/details/gtnrbbdwqt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pengpengdd.cyou/Article/details/gtbctkmson.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gtvxeevuet.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtwjxsjrlj.html

[U19] Py：正则替换带回调
来源：http://dali.jiagoushi.top/Article/details/gtwrbvdpmc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgufenzy.top/Article/details/gtqkvkhdgs.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gtjeryhmsd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj202588.top/Article/details/gttikeqmne.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gtfcahfrll.html

@contextlib.contextmanager
来源：http://dali.havefunace.top/Article/details/gtjuzvutuu.html

[U22] Py：矩阵转置
来源：http://dali.yj20258.top/Article/details/gtnjcoacif.html

list(zip(*m))
来源：http://dali.yueranfly.top/Article/details/gthfrxhftu.html

[U23] Py：分块读取大文件
来源：http://dali.316326.xyz/Article/details/gtnxnlncic.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ppjwa.cn/Article/details/gtgljnwlfy.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gtfnmdkljw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtoferhoon.html

[U25] Py：CSV 按字典读
来源：http://dali.jyoumei.cn/Article/details/gtnunrbjct.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gtkdtqkuqi.html

[U26] Py：并发下载
来源：http://dali.jinqigfzy.top/Article/details/gtsxozdldt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxuanxn.top/Article/details/gtsxyhjqgx.html

[U27] Py：异步 HTTP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxvrkxlf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.meibo888.top/Article/details/gtmbialmuy.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gtljcxpfbs.html

UserId = int
来源：http://dali.cqqwz.cn/Article/details/gtuodtjeoc.html

[U29] Py：属性校验
来源：http://dali.haohaochexian.top/Article/details/gtrsjlvjzs.html

@property 与 @x.setter 配合
来源：http://dali.pycfn.com/Article/details/gtbzodeyuk.html

[U30] Py：数据类
来源：http://dali.tanke756.top/Article/details/gtaoupbwpk.html

@dataclass(slots=True)
来源：http://dali.tianlin.xyz/Article/details/gtsrwsfkpk.html

[U31] Py：单测
来源：http://dali.feifeiyinyue.top/Article/details/gtecegtxcv.html

python -m pytest -q
来源：http://dali.c1oappe.top/Article/details/gtggvttnzt.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gtxlqocyrj.html

ruff format . && ruff check --fix .
来源：http://dali.xylfe.cn/Article/details/gtinlsdemy.html

[U33] Py：打包发布
来源：http://dali.shuidangran.top/Article/details/gtriikdevw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jiagoushi.top/Article/details/gtkolbdsmi.html

[U34] Py：判断编码
来源：http://dali.cucudq.cn/Article/details/gtgxdmdrrj.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gtbhzybajw.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtjmfmnuhe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shzxlz.cn/Article/details/gtfrgbapfu.html

[U36] Py：定时任务
来源：http://dali.cucudq.cn/Article/details/gtkagspzqm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gtnymnhmfd.html

[U37] Py：读写 Excel
来源：http://dali.yj20258888.top/Article/details/gtzolgnbnh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.vqdsnc.cn/Article/details/gtshkxdonp.html

[U38] Py：获取脚本所在目录
来源：http://dali.aizwys.cn/Article/details/gtdrufrqew.html

Path(__file__).resolve().parent
来源：http://dali.bjfxy.top/Article/details/gtweawncqm.html

[U39] Py：判断是否在交互环境
来源：http://dali.jiagoushi.top/Article/details/gtemzmibks.html

sys.stdout.isatty()
来源：http://dali.yuanzhike.top/Article/details/gtxzvpdjjn.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gtpmaiktka.html

print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtrhqsmepz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cdnleiting.top/Article/details/gtjojblacg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tian-w.cn/Article/details/gtefoexmfr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.dianchejie.cn/Article/details/gtpqjcjdpm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guowangkeji.top/Article/details/gtdyanvuzq.html

[U43] PHP：声明命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtmbtzgksm.html

namespace App\Http;
来源：http://dali.zhaomingkeji.xyz/Article/details/gterezlowr.html

[U44] PHP：开启严格类型
来源：http://dali.yj20258888.top/Article/details/gtpgmqatni.html

declare(strict_types=1);
来源：http://dali.zhongyouzk.top/Article/details/gtlmixrrio.html

[U45] PHP：类型声明与返回类型
来源：http://dali.vqdsnc.cn/Article/details/gtfjcudhzp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gthovqjmxu.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gtanijqyip.html

?string $name = null
来源：http://dali.gogol.net.cn/Article/details/gtyatdvknk.html

[U47] PHP：联合类型
来源：http://dali.yj202588.top/Article/details/gtbmuetbxm.html

int|string $id
来源：http://dali.redwolf501.top/Article/details/gthzsqnjky.html

[U48] PHP：纯枚举
来源：http://dali.hysaishi.cn/Article/details/gtjirmirgo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gogol.net.cn/Article/details/gtxwdqmsqg.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gtwwyrfldr.html

public readonly string $name
来源：http://dali.ivvv.top/Article/details/gtagpznipo.html

[U50] PHP：构造器属性提升
来源：http://dali.ivvv.top/Article/details/gttkcioxpn.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gtdajddcrc.html

[U51] PHP：数组解构
来源：http://dali.cqqwz.cn/Article/details/gtwakcpxha.html

[$a, $b] = $arr;
来源：http://dali.hongshengwenyu.top/Article/details/gtfgsphowz.html

[U52] PHP：箭头函数
来源：http://dali.ivvv.top/Article/details/gtekfzmdkl.html

$double = fn($x) => $x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtjkzjhmyr.html

[U53] PHP：空合并运算符
来源：http://dali.9152youxi.cn/Article/details/gtmdwykejf.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxinkj.top/Article/details/gtkbgavliy.html

[U54] PHP：空安全调用
来源：http://dali.xinyue.icu/Article/details/gtfbojuoin.html

$obj?->method()
来源：http://dali.wangshuangyany.cn/Article/details/gtwhagcrtg.html

[U55] PHP：match 表达式
来源：http://dali.bjfxy.top/Article/details/gtqrlwyiqv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtzjwznrsp.html

[U56] PHP：命名参数
来源：http://dali.guannengcc.top/Article/details/gttojzzqvz.html

f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtsrrvvwbr.html

[U57] PHP：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtevgbdcml.html

"值: {$a}"
来源：http://dali.hnxiangtu.top/Article/details/gtlsvipjym.html

[U58] PHP：数组三件套
来源：http://dali.smart0.xyz/Article/details/gtdmrmdbjf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ehwqpu.com/Article/details/gtyaciootr.html

[U59] PHP：自定义排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdtgxypr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtufpckuvb.html

[U60] PHP：JSON 编解码
来源：http://dali.ybcxt.top/Article/details/gtmpocbypj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtwdcpfcjr.html

[U61] PHP：正则
来源：http://dali.jiagoushi.top/Article/details/gtpmbghkmz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtdlsexdff.html

[U62] PHP：日期对象
来源：http://dali.zhoulong.xyz/Article/details/gtsvjuqgnf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmgsicnn.html

[U63] PHP：文件读写
来源：http://dali.zhengqikj.top/Article/details/gtfqaiyijd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ivvv.top/Article/details/gttbctekmi.html

[U64] PHP：目录遍历
来源：http://dali.dashuyun.cn/Article/details/gtoagypege.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhongyouzk.top/Article/details/gtkvehjmgh.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gtuyyuhaky.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtuxfyjqpd.html

[U66] PHP：设置 Cookie
来源：http://dali.hfpthk.cn/Article/details/gtnzjbikns.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ivvv.top/Article/details/gthxdbgmez.html


<!-- 参考信息 -->