代发 wailian999

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtfcepgedz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gtfzfnvqjo.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gthyzzcion.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gtjissjvym.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtducqlgyx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtuokpkldj.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gtofhunbmh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtxtxzhhyo.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gtibysuuuf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gtpvouwgtr.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gtjhvlveqg.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtudihpysi.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtdopdsysg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtjctwzwls.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gtuayskyfv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gtoeytzzxx.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtbpxmosxw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiapifta.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtuggnbxah.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gtzqlzdfhz.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gtcqmjhgnw.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gtbjnhyxnr.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtrifjvfkx.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikvdikyg.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtqgbjjufw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gtshlsuvom.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtuwwbhoxm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gttwteeite.html

[S47] C++：结构化绑定遍历
来源：http://dali.316326.xyz/Article/details/gtnmnidicm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtkpriyujk.html

[S48] C++：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtkmeccopy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtuxyvvslp.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtfdahkohu.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gtdjbmrlsp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtyafpfykd.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtesdqkvue.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtzhkihzsr.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gtrxpqlrou.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtgkhojcyq.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gttefzqvcx.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtjsmquzai.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtnkzhqtoo.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gtlcgvjfbl.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gtetkxawyf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibgudjmw.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gtqcfdzgnb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtqprvdbnh.html

[S56] C++：optional
来源：http://dali.shzxlz.cn/Article/details/gtgpjldmrp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gtupokapzq.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gtspvflgsr.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gtkkiasafw.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtxdfgnueb.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtkyzisohf.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gtnbycamjp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtgbzkqacn.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gtjjmryowb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gteprevdtu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjrpofyl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtqnrvbmst.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtdsppfmlr.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtenttgjeg.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtnedffurj.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuerkupks.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jiagoushi.top/Article/details/gthetsdyow.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtfuhygzle.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtpfdksmum.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gtkpghnzcc.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gtucstiert.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtjoafnslx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gttsqydyvq.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtejgajwhr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtjmixxerw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtkocopbxz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gttglwgvrl.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gtkkxisnup.html

data class User(val name: String, val age: Int)
来源：http://dali.jianghu66.top/Article/details/gtbhpafwfd.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gttygodccy.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gtreqauxpp.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gtndppwoxf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gtfbhggaju.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gtholjgqkt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gtpnzwukae.html

[T12] Kotlin：解构声明
来源：http://dali.ybcxt.top/Article/details/gtdjijmbnl.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtpkefpocc.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzothtvd.html

val m = mapOf("a" to 1)
来源：http://dali.sysykeji.top/Article/details/gtokcfknti.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gttdznlmmt.html

for (i in 1..10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtagwhtuag.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gtguxuckae.html

interface Shape { fun area(): Double }
来源：http://dali.ppjwa.cn/Article/details/gtviwhjmyd.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtilmbywzw.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwukejvc.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gtolvrtzjo.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gtqljzfwuv.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtfnmqovem.html

"值: \(b)"
来源：http://dali.zdqjudy.top/Article/details/gtdaaiyxor.html

[T19] Swift：可选绑定
来源：http://dali.chenzaomai.com/Article/details/gtcnydvddt.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gtymtaossn.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gthawipjqr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gtsyfkobhx.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gtkosptefp.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gtgdrtgqnz.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtsjcowkkq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtllwbrypf.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gtjqfnajrn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gthysalixr.html

[T24] Swift：闭包
来源：http://dali.chenjidiqi.icu/Article/details/gtfxtgeusn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daxiang520.top/Article/details/gtieutfkos.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gtemuwopsd.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gtipwnotcv.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyrksmve.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gtgpdxcacb.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtitimbieo.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gtknojelje.html

[T28] Swift：枚举
来源：http://dali.hammf.cn/Article/details/gtlniophis.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gtktpeolgb.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gtciuiddbo.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gtddxeuaqh.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtubhiiexp.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtwyxbnknp.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtxcdiassm.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gthiivbjps.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gtzctpwgex.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gtmkljdise.html

[T33] Lua：表（数组）
来源：http://dali.shzxlz.cn/Article/details/gtskeljmri.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gtkkjlffdp.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtrpgnwjyf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gtmljiicsf.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtezxslsle.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gtrsoklgbv.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gtcvmqlpkt.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gtzggjqkkn.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtsnfchkop.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gttcvuvudl.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gtdkddvhpm.html

if x > 0 then print("正") end
来源：http://dali.nwbrower.top/Article/details/gtdfiieuzy.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gttnonzfba.html

string.find(s, "%d+")
来源：http://dali.316326.xyz/Article/details/gtfmhbqhpa.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtuynjcqel.html

setmetatable({}, { __index = base })
来源：http://dali.0kj1m.cn/Article/details/gtxpeymzgg.html

[T41] Perl：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtgdwbomov.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gtjkgldshe.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gteugxgevq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtxpquqpnl.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtkemorgtx.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gtlkimcwka.html

[T44] Perl：条件
来源：http://dali.nwbrower.top/Article/details/gtuoxgrfup.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gtidsavpns.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gtfioywjvo.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgfzy.top/Article/details/gtvchckvab.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gttsqbbpxq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxigvjntz.html

[T47] Perl：正则捕获
来源：http://dali.zhoulong.xyz/Article/details/gtwxycjbwy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvosvhjuz.html

[T48] Perl：正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtrnrlqbrc.html

$s =~ s/old/new/g;
来源：http://dali.shangyingyoupin.top/Article/details/gttxmovkmv.html

[T49] Perl：函数
来源：http://dali.xinyue.icu/Article/details/gtfyweupmn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtagpodtgb.html

[T50] Perl：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtksfyfpxg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gtpxaponww.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenlongwang.top/Article/details/gtfqrrhzvc.html

[T51] Scala：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtxdvyrkqi.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gtkzmoxppy.html

[T52] Scala：变量
来源：http://dali.xuanzx.com/Article/details/gtpfdoqcga.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gtpuqjybml.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtrqisbfct.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtzzyjyrqk.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gtuermzzxg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenlongwang.top/Article/details/gtvrijdgcp.html

[T55] Scala：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtqcpbcdvo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.vqdsnc.cn/Article/details/gtrngleefv.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gtmxpslqsd.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtlwujggpz.html

[T57] Scala：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtlpyjogqq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtkphbceym.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtbxiirane.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gtxpacuuhg.html

[T59] Scala：循环
来源：http://dali.snrcjt.cn/Article/details/gtfkjzrkap.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtqddpzbwa.html

[T60] Scala：折叠
来源：http://dali.yangfankeji.com/Article/details/gtpxzirpip.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gtonzolumd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtohkgexlm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gtaucbrbyf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttggdwkzw.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrogihck.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gtsokcgonz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gtbhobybux.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj202588.top/Article/details/gtsqvlwlgp.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gtcfgwmglv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangkeji.top/Article/details/gturhhrmix.html

[U04] Py：变量调试打印
来源：http://dali.jianghu66.top/Article/details/gtybqsuvmu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gtczfrgvcn.html

[U05] Py：列表去重且保序
来源：http://dali.sweek.top/Article/details/gtzsvdvxea.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtowxnodlv.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gtvtlaeoth.html

{**a, **b}
来源：http://dali.haohaochexian.top/Article/details/gtmvrkiuxu.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntljkqyn.html

{v: k for k, v in d.items()}
来源：http://dali.tian-w.cn/Article/details/gtbmgjfofv.html

[U08] Py：展平二维列表
来源：http://dali.cqqwz.cn/Article/details/gtjdocsebo.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gtmwfhuiwd.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gtwzbszkds.html

max(d, key=d.get)
来源：http://dali.zhengqikj.top/Article/details/gthojgpgab.html

[U10] Py：按值排序字典
来源：http://dali.sufxvd.cn/Article/details/gtmamkpapk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hammf.cn/Article/details/gtbnsrjuzz.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gtzgymeoln.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gtevtvpbun.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuetiantiany.cn/Article/details/gtoxctmivd.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtnozkqiax.html

[U13] Py：固定长度队列
来源：http://dali.daria6918.cn/Article/details/gtecpfpioq.html

deque(maxlen=10)
来源：http://dali.jinqigufen.top/Article/details/gtrlpgteka.html

[U14] Py：分组收集到列表
来源：http://dali.yj202588.top/Article/details/gtejbuxlbs.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtwfuxpsef.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gtpgmizmtr.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gtrffkgotd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gtaiaczlfz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sweek.top/Article/details/gtwhesztkh.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gtvgencmjf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gtfgvtwfvc.html

[U18] Py：预编译正则
来源：http://dali.gzhubu.top/Article/details/gtkbolmuvh.html

pat = re.compile(r"\d+")
来源：http://dali.tanke756.top/Article/details/gtakiavshm.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gtbcuqqdwr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.redwolf501.top/Article/details/gtgentgrfg.html

[U20] Py：缓存函数结果
来源：http://dali.iojbl.cn/Article/details/gtbjsgdinp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gtwbztajiw.html

[U21] Py：自定义上下文管理器
来源：http://dali.yvedp.cn/Article/details/gtcmurebpz.html

@contextlib.contextmanager
来源：http://dali.xinyue.icu/Article/details/gtrnxpfqkv.html

[U22] Py：矩阵转置
来源：http://dali.pycfn.com/Article/details/gtnlmtbrkp.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gtnidqhoxw.html

[U23] Py：分块读取大文件
来源：http://dali.aizwys.cn/Article/details/gtaiqscizi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuanzx.com/Article/details/gtvmewslgv.html

[U24] Py：路径操作
来源：http://dali.c1oappe.top/Article/details/gtlnnjdqhc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtoebrhazd.html

[U25] Py：CSV 按字典读
来源：http://dali.chenzaomai.com/Article/details/gtsgexopty.html

csv.DictReader(f)
来源：http://dali.xuetiantiany.cn/Article/details/gtqxuzqaih.html

[U26] Py：并发下载
来源：http://dali.0kj1m.cn/Article/details/gtqwcgwngk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwxjymcs.html

[U27] Py：异步 HTTP
来源：http://dali.xuetiantiany.cn/Article/details/gtoqgmsmzx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.birdmap.top/Article/details/gticgaynek.html

[U28] Py：类型别名
来源：http://dali.wangshuangyany.cn/Article/details/gtgnlbovrx.html

UserId = int
来源：http://dali.guowangkeji.top/Article/details/gtvowatlzg.html

[U29] Py：属性校验
来源：http://dali.zycfv.cn/Article/details/gttwyftrzq.html

@property 与 @x.setter 配合
来源：http://dali.cdnleiting.top/Article/details/gtrabqimby.html

[U30] Py：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gtnnmnhdmm.html

@dataclass(slots=True)
来源：http://dali.haohaochexian.top/Article/details/gtpukvneto.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gtshzfjqnt.html

python -m pytest -q
来源：http://dali.gaohongyu789.top/Article/details/gtdxogielo.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gtplkbaejv.html

ruff format . && ruff check --fix .
来源：http://dali.kuanghao11.cn/Article/details/gtvcjktasg.html

[U33] Py：打包发布
来源：http://dali.svipenyu.cn/Article/details/gtvvatwtbj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tian-w.cn/Article/details/gtudehikop.html

[U34] Py：判断编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkimikyiz.html

chardet.detect(raw)
来源：http://dali.cdnleiting.top/Article/details/gtwgwsybnd.html

[U35] Py：发送邮件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuebknaoi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shzxlz.cn/Article/details/gtxzqlnznj.html

[U36] Py：定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtmqxnsaeo.html

schedule.every(10).minutes.do(job)
来源：http://dali.gotoacloud.top/Article/details/gttqkipege.html

[U37] Py：读写 Excel
来源：http://dali.hnxiangtu.top/Article/details/gtoqfjtwff.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhongyouzk.top/Article/details/gtriaiqmhu.html

[U38] Py：获取脚本所在目录
来源：http://dali.c1oappe.top/Article/details/gtsdeeskbk.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gtjfljwhsw.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gtafvwstug.html

sys.stdout.isatty()
来源：http://dali.sxryk.cn/Article/details/gtxxniaiss.html

[U40] Py：打印到标准错误
来源：http://dali.316326.xyz/Article/details/gtmagkwgtz.html

print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtltejkslf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.quarkkingdee.top/Article/details/gtnqamxklt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.iojbl.cn/Article/details/gtjmxzrcwx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ivvv.top/Article/details/gtmvrwxvqq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.smart0.xyz/Article/details/gtoydewhqe.html

[U43] PHP：声明命名空间
来源：http://dali.316326.xyz/Article/details/gtijbcabah.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gtgxekdugb.html

[U44] PHP：开启严格类型
来源：http://dali.gogol.net.cn/Article/details/gthryftjiv.html

declare(strict_types=1);
来源：http://dali.gogol.net.cn/Article/details/gtqaviuydu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cdnleiting.top/Article/details/gtkmrdznxz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtwmzudotj.html

[U46] PHP：可空类型
来源：http://dali.yj20258888.top/Article/details/gtpbstfmxg.html

?string $name = null
来源：http://dali.nanxinkj.top/Article/details/gtrhoshtku.html

[U47] PHP：联合类型
来源：http://dali.316326.xyz/Article/details/gtfxealrno.html

int|string $id
来源：http://dali.jianghu66.top/Article/details/gtallxkqll.html

[U48] PHP：纯枚举
来源：http://dali.cheryme.top/Article/details/gttnrvstib.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zycfv.cn/Article/details/gtqyeeewhl.html

[U49] PHP：只读属性
来源：http://dali.redwolf501.top/Article/details/gtoegmjkvc.html

public readonly string $name
来源：http://dali.yonumen.top/Article/details/gtvtzdbazn.html

[U50] PHP：构造器属性提升
来源：http://dali.mhx1999.top/Article/details/gtlhlolbni.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnhlznwrx.html

[U51] PHP：数组解构
来源：http://dali.pengpengdd.cyou/Article/details/gtasoqcfad.html

[$a, $b] = $arr;
来源：http://dali.xinyue.icu/Article/details/gtjhtqpsci.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtgvydnqjr.html

$double = fn($x) => $x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gtzthhcyab.html

[U53] PHP：空合并运算符
来源：http://dali.jyoumei.cn/Article/details/gtfphlfmpo.html

$v = $a ?? $b ?? "default";
来源：http://dali.jianghu66.top/Article/details/gtmdpkzbmj.html

[U54] PHP：空安全调用
来源：http://dali.xuanzx.com/Article/details/gtbfnhojnc.html

$obj?->method()
来源：http://dali.mhx1999.top/Article/details/gtyaqjojqf.html

[U55] PHP：match 表达式
来源：http://dali.shzxlz.cn/Article/details/gtdrwrnimy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehuzdhxr.html

[U56] PHP：命名参数
来源：http://dali.shuidangran.top/Article/details/gtjsoglsrk.html

f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtefswsdwb.html

[U57] PHP：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtqfftyset.html

"值: {$a}"
来源：http://dali.meibo888.top/Article/details/gtluokrzdb.html

[U58] PHP：数组三件套
来源：http://dali.hywenlv.cn/Article/details/gtqbwcpnbr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jqgfzy.top/Article/details/gtjnwnkvvt.html


<!-- 参考信息 -->