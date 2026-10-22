代发 wailian999

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gthipbegho.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnsxykcg.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtsfmufmic.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtkntsjtfc.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gtkpbudhok.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gtzgxcocqx.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gtpcnejzhr.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtyqiydjhq.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtcxavlzeu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtflkwplle.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtllvmmgkh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sxryk.cn/Article/details/gtmniwwysb.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaqjkjzm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gogol.net.cn/Article/details/gtqyigqdvh.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gtuqdlxpbr.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gtznkfjgfl.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtypyukdip.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gttxsuhrxw.html

[S44] C++：引用传参
来源：http://dali.9152youxi.cn/Article/details/gtjtpkfbvb.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gtdhdhzqjq.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtgelupefh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gtgvfkzmkl.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gtyqdcnbkd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gtohaqffbd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gtassskajc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gtsoognatb.html

[S48] C++：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtkcbfrsgo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtqxfisjyn.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtckfmgmlz.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gttawkzsux.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmezarbkl.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtlusootyc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtbfuffjsc.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtvriewrel.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtqszxymxi.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gtxfjmaayg.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtpqcycheb.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gtsntqdbag.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gtyoziprhh.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkmcehmu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtykyfwnjc.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtpnsikpcx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtjazjknkv.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtowjculkm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtlebrhnny.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtgswmnihs.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gtqsizjaxa.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gtljmousfa.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttiihrqok.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gtpmytdzhe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gtouaeprou.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtqmuarfdb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtpvbpwuxd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbnwlftyd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gtkrufkahf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtltqbgemh.html

[T01] Kotlin：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtiittaazt.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtbvfuvpfy.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtoljcykaq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gtrqijndyr.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxqtmgqx.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtvhlssejm.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gttsczhmvv.html

val n: String? = null;  n?.length
来源：http://dali.zhongyouzk.top/Article/details/gtrbgfpsxp.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtveijpkgd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxmqlxbx.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtmogxyklk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtjblbnwmj.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtscxztgpo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtzlcigyiq.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gtmtyfqayu.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtnxmwlkqd.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gtyhfcfiwg.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdosxagng.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gtubzutscg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gteudseaqr.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuucpente.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gtrgimoaaj.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtybhsjfvl.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtpcgvnwqm.html

[T13] Kotlin：只读 Map
来源：http://dali.0kj1m.cn/Article/details/gtngosmmmq.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtvrkdgmmm.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtcloderzz.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtqalaznia.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtuhrcnuuq.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gtpiwrxiip.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtusxipekj.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtplgwbppr.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtgidytwgc.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtyyjdbhka.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtzdkkzird.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gtvazeyggx.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gtrsuzckwn.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gtxtefyxjt.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gtggygidjv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gtusipomaj.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsicryxf.html

for x in a { print(x) }
来源：http://dali.yj20258.top/Article/details/gtvsjehmgh.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gtetxgiiur.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gtldnxwjtp.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtzsrpefsm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gthnmjznet.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtzaedeggp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtgbltrbyc.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gtqsxnfbcg.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gtjbvvahdn.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gtvundvlpx.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gtonwkixxt.html

[T27] Swift：错误处理
来源：http://dali.pycfn.com/Article/details/gthkyvsfud.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gtljjznyhi.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtuwpysmeu.html

enum Color { case red, green }
来源：http://dali.316326.xyz/Article/details/gtmgmabusq.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtgktkhkbi.html

guard let x = opt else { return }
来源：http://dali.bjfxy.top/Article/details/gtsfpvzhtr.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtpixrkuut.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtdeyyswbq.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gtnokqpxav.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtfwugxmlo.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gttdfsejby.html

local a = 1
来源：http://dali.tianlin.xyz/Article/details/gtiaasgqni.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gtzkxhozom.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gtknjguzje.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gthhinmwri.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.iojbl.cn/Article/details/gtooxaixxv.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gtldendouj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gtfbbwfdak.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gttkmxcunh.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gtxwtikfge.html

[T37] Lua：字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtrbmanunk.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gtxvptltwu.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gtrqfvirsd.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gtewvvvxty.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtwmfrdsck.html

string.find(s, "%d+")
来源：http://dali.fengsongda.top/Article/details/gtgauqroyf.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnlkwhsn.html

setmetatable({}, { __index = base })
来源：http://dali.yueranfly.top/Article/details/gtfhypfpyn.html

[T41] Perl：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsksfhlk.html

print "Hello\n";
来源：http://dali.zhixingplan.top/Article/details/gtlfaruvht.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gtvttuvcek.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gtyeybbhqy.html

[T43] Perl：字符串插值
来源：http://dali.xuanzx.com/Article/details/gthlnwbjmr.html

"值: $a"
来源：http://dali.yvedp.cn/Article/details/gtzrzsqzwk.html

[T44] Perl：条件
来源：http://dali.ivvv.top/Article/details/gtbispgfos.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gttmodcglz.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gtkauyovhc.html

for my $x (@arr) { print $x; }
来源：http://dali.meibo888.top/Article/details/gtqetrhdsg.html

[T46] Perl：哈希操作
来源：http://dali.zhengqikj.top/Article/details/gtstixqbxc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cheryme.top/Article/details/gtcrjksbhp.html

[T47] Perl：正则捕获
来源：http://dali.cheryme.top/Article/details/gtwtzzuiyw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtullwraza.html

[T48] Perl：正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtcomjjivg.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gtuynpgxrw.html

[T49] Perl：函数
来源：http://dali.xylfe.cn/Article/details/gtvldszkrt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtmysqtyqn.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtqqqhqnio.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gzhubu.top/Article/details/gtztjzmbfg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gtzoukwsbt.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtkzaionzo.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtndijyudw.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtxqpnfyue.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtrtwasjza.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtgnnzygdn.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtlanleqcb.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtbddzigkz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpurghqdx.html

[T55] Scala：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtrghqxzhg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gtbfutkofu.html

[T56] Scala：样例类
来源：http://dali.ybcxt.top/Article/details/gtzmxnnswa.html

case class User(name: String, age: Int)
来源：http://dali.sweek.top/Article/details/gtvbqvacle.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtexdmfyyk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zycfv.cn/Article/details/gtegbfuqwz.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gtfalywxxq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gtvrmsvomh.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gtnujwlpzv.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtzcfjoscc.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gtydvxaqcj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangshuangyany.cn/Article/details/gtxmtbnezw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtizbrllys.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtytkwgxeu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtarxeofrm.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gtbdrajjfi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gtcfqxohpk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gtovgwrosw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtmwewkwav.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gtzqjgmixw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenjidiqi.icu/Article/details/gteqznpmjp.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gtvpflrpvv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.meibo888.top/Article/details/gtjirtjaxn.html

[U05] Py：列表去重且保序
来源：http://dali.redwolf501.top/Article/details/gtadjssomg.html

list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtacbgmmfo.html

[U06] Py：合并两个字典
来源：http://dali.zhiwuduotai.top/Article/details/gtbcasfqlu.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gtescgkoop.html

[U07] Py：反转字典键值
来源：http://dali.hnqzz.top/Article/details/gtgpprouqo.html

{v: k for k, v in d.items()}
来源：http://dali.yj202588.top/Article/details/gtmoppgzvg.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gtoqqtnauq.html

[y for x in nested for y in x]
来源：http://dali.cheryme.top/Article/details/gtpdylxxfj.html

[U09] Py：字典取最大值的键
来源：http://dali.smart0.xyz/Article/details/gtnrhlgtxi.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhnadmnb.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gtoleoahsc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbukorajo.html

[U11] Py：生成器表达式
来源：http://dali.c1oappe.top/Article/details/gtwubrjbqg.html

(x * 2 for x in arr)
来源：http://dali.xinyue.icu/Article/details/gtfsscgwha.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gtlnuxvhai.html

Counter(arr).most_common(3)
来源：http://dali.svipenyu.cn/Article/details/gtgkkvpguz.html

[U13] Py：固定长度队列
来源：http://dali.shzxlz.cn/Article/details/gtuqyeytvg.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gtbqwuuacp.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gtcgbgnsnf.html

defaultdict(list)
来源：http://dali.zhoulong.xyz/Article/details/gtiltogdhm.html

[U15] Py：高精度计时
来源：http://dali.shangyingyoupin.top/Article/details/gtkzmbcona.html

t = time.perf_counter()
来源：http://dali.jianghu66.top/Article/details/gtiljdgkri.html

[U16] Py：命令行参数解析
来源：http://dali.haohaochexian.top/Article/details/gtyngphkkc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fengsongda.top/Article/details/gtkdqflsxc.html

[U17] Py：初始化日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsznjrfl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ivvv.top/Article/details/gtltlefzmw.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gtxtcgcwrk.html

pat = re.compile(r"\d+")
来源：http://dali.cqqwz.cn/Article/details/gttxqlncvi.html

[U19] Py：正则替换带回调
来源：http://dali.jlsjyb.cn/Article/details/gtyqelnauw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ehwqpu.com/Article/details/gtxxycqgcs.html

[U20] Py：缓存函数结果
来源：http://dali.shuidangran.top/Article/details/gtjijqkksj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhoulong.xyz/Article/details/gtlzfhsitw.html

[U21] Py：自定义上下文管理器
来源：http://dali.gzhubu.top/Article/details/gthugrpgai.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gtzlkizoal.html

[U22] Py：矩阵转置
来源：http://dali.zhoulong.xyz/Article/details/gtnzeditis.html

list(zip(*m))
来源：http://dali.jqgufenzy.top/Article/details/gtikwguaig.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gtbralwotq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenlongwang.top/Article/details/gtfuejomic.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtnppldubj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtptydywgh.html

[U25] Py：CSV 按字典读
来源：http://dali.316326.xyz/Article/details/gtwxrlefrv.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtzpwzttnv.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gttabxifsu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shuidangran.top/Article/details/gtxgufdlrg.html

[U27] Py：异步 HTTP
来源：http://dali.dashuyun.cn/Article/details/gtzsxsibnl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuetiantiany.cn/Article/details/gtlmyjighq.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gtcghkjnoi.html

UserId = int
来源：http://dali.pengpengdd.cyou/Article/details/gtomzdatdn.html

[U29] Py：属性校验
来源：http://dali.mhx1999.top/Article/details/gtoucogcfh.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gtvfoxivlm.html

[U30] Py：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gtedxrmhmc.html

@dataclass(slots=True)
来源：http://dali.daxiang520.top/Article/details/gtjdkblrdj.html

[U31] Py：单测
来源：http://dali.xylfe.cn/Article/details/gtmqpuhgmo.html

python -m pytest -q
来源：http://dali.jqgfzy.top/Article/details/gtwlvautuj.html

[U32] Py：代码格式化
来源：http://dali.chenlongwang.top/Article/details/gtqefkfyjr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gtbzpbqjyy.html

[U33] Py：打包发布
来源：http://dali.shuidangran.top/Article/details/gtbowvsllb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gtixvulfwv.html

[U34] Py：判断编码
来源：http://dali.cdnleiting.top/Article/details/gtnempkcbh.html

chardet.detect(raw)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeyozbmh.html

[U35] Py：发送邮件
来源：http://dali.chenzaomai.com/Article/details/gtoqxixyme.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hysaishi.cn/Article/details/gtypusphji.html

[U36] Py：定时任务
来源：http://dali.yongpay.top/Article/details/gtyxifzuee.html

schedule.every(10).minutes.do(job)
来源：http://dali.cdnleiting.top/Article/details/gtkbxgvapw.html

[U37] Py：读写 Excel
来源：http://dali.birdmap.top/Article/details/gtcnlmbzgs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gotoacloud.top/Article/details/gtkaccubtq.html

[U38] Py：获取脚本所在目录
来源：http://dali.cqqwz.cn/Article/details/gtdmxwaanx.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjgmzulx.html

[U39] Py：判断是否在交互环境
来源：http://dali.haohaochexian.top/Article/details/gtmpemxbfy.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gtephweole.html

[U40] Py：打印到标准错误
来源：http://dali.yangfankeji.com/Article/details/gtjsisxqun.html

print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gteflmqsxg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.haohaochexian.top/Article/details/gtfpvzwyfs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yueranfly.top/Article/details/gtnmyofied.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhiwuduotai.top/Article/details/gtapowwklx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ppjwa.cn/Article/details/gtfvuujttc.html

[U43] PHP：声明命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtnrujrpiw.html

namespace App\Http;
来源：http://dali.nwbrower.top/Article/details/gtrebbbpvm.html

[U44] PHP：开启严格类型
来源：http://dali.iojbl.cn/Article/details/gtlvngqutk.html

declare(strict_types=1);
来源：http://dali.xuanzx.com/Article/details/gtxfjmnjrh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj202588.top/Article/details/gtsbmdwmbm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtlqygbqcr.html

[U46] PHP：可空类型
来源：http://dali.jiagoushi.top/Article/details/gtjxxijhfc.html

?string $name = null
来源：http://dali.shuidangran.top/Article/details/gtfejvbdgn.html

[U47] PHP：联合类型
来源：http://dali.fengsongda.top/Article/details/gtxxvtifvn.html

int|string $id
来源：http://dali.guowangkeji.top/Article/details/gtbaehkikp.html

[U48] PHP：纯枚举
来源：http://dali.yuxming.cn/Article/details/gtrunqktkb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pycfn.com/Article/details/gtpcdgfjza.html

[U49] PHP：只读属性
来源：http://dali.yongpay.top/Article/details/gtpzpxkbpi.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gtjldfykzb.html

[U50] PHP：构造器属性提升
来源：http://dali.fzhhl.top/Article/details/gtxeclkhdm.html

public function __construct(private int $id) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtehzbfkpa.html

[U51] PHP：数组解构
来源：http://dali.316326.xyz/Article/details/gtitfvqplz.html

[$a, $b] = $arr;
来源：http://dali.hfpthk.cn/Article/details/gtnfmyuzwo.html

[U52] PHP：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gtaaqljabh.html

$double = fn($x) => $x * 2;
来源：http://dali.svipenyu.cn/Article/details/gtrflfgyei.html

[U53] PHP：空合并运算符
来源：http://dali.jiagoushi.top/Article/details/gtffhkarwh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhongyouzk.top/Article/details/gtdbyueyav.html

[U54] PHP：空安全调用
来源：http://dali.wangdashe.top/Article/details/gtfrlfbrzc.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gtdffkxhrl.html

[U55] PHP：match 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhhhbbbp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenlongwang.top/Article/details/gtznkqbqcb.html

[U56] PHP：命名参数
来源：http://dali.aibaodan.cn/Article/details/gtgnvqafeu.html

f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtgsbzswci.html

[U57] PHP：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtdddhvblr.html

"值: {$a}"
来源：http://dali.gogol.net.cn/Article/details/gtjukexwnc.html

[U58] PHP：数组三件套
来源：http://dali.0kj1m.cn/Article/details/gtbjvgqmzu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fzhhl.top/Article/details/gtkxfhtjnd.html

[U59] PHP：自定义排序
来源：http://dali.jianghu66.top/Article/details/gtsxrxdmzf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtmszqhodj.html

[U60] PHP：JSON 编解码
来源：http://dali.kuanghao11.cn/Article/details/gtjtlqdkwx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gtjwgqrzon.html


<!-- 参考信息 -->