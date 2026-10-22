代发 wailian999

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gtlcaxaows.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gtiknajnen.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gtzjnsifel.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gtmfpctafp.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gtyvdfewle.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtkcednvsv.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtlzftouvk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gteoiwbtmp.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gtgbuyicxp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gtoarjuexc.html

[S38] C++：排序
来源：http://dali.iojbl.cn/Article/details/gtdhmmemav.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtapvhkdzm.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gtxzkgbwrm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gtepucsdde.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtfpoadbfl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gtkusfjzdu.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtqqepcmgj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gtgpwgbnbs.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtmoqeexkw.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtayheyqvt.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gtronxjfre.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gtnorzibwm.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gtvhqpspca.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtqfewyffh.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtoeyxjdrr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gtdsmsysno.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gttqriswod.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gtixvwxbip.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gtxcaxlptu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gtkcbtdhwx.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtmtbijnzl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtrxvxavkf.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gtutcgadwa.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlemahnr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gtbcwakceb.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gtuxryvaoy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtvbagjlhq.html

[S51] C++：显式类型转换
来源：http://dali.cqqwz.cn/Article/details/gtaqtukmid.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtlftdypbk.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtbvsrmmby.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtdahlzsie.html

[S53] C++：移动语义
来源：http://dali.gogol.net.cn/Article/details/gtcxexzuld.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtythcgprk.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gtuoahvjfm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtixwcibeg.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gtockikwzz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gtmbnslrbw.html

[S56] C++：optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwonhooka.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gtifeajcju.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gtkdgwchrn.html

constexpr int N = 10;
来源：http://dali.nwbrower.top/Article/details/gtsvpxkbpa.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gtubvmllfu.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtxarwxswa.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftmeimtb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtwnsrxszp.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtijwsowhv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gtslmchtzo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtzfjsygja.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtthaxqbsn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthzmryefv.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpjlzfay.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtbrnatbwq.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gtwapzfvuu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gthllaijkc.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaymrhkfi.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtadjmariz.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtosgladvt.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gtslaffrue.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gtqjpqjlxh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.redwolf501.top/Article/details/gtepmhlzgi.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtyrysqauu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gtbvtsekld.html

[T07] Kotlin：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtbqkzgkno.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gtljychkmv.html

[T08] Kotlin：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtxxvumjlj.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtlmkprosm.html

[T09] Kotlin：扩展函数
来源：http://dali.vqdsnc.cn/Article/details/gtsozsbkak.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gtfcktowsr.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gtbivjxyeu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gtjlrydxms.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtfvtgoaan.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxogmnfde.html

[T12] Kotlin：解构声明
来源：http://dali.fzhhl.top/Article/details/gtyjtvzomy.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gtqtsurqmk.html

[T13] Kotlin：只读 Map
来源：http://dali.hnxiangtu.top/Article/details/gtrafdqxct.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gtatczhpnj.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyxxozzc.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtikikkisz.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtvcidbcgu.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gtelznquez.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtnjbuhagn.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtnsukjgdr.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gtakrdsktb.html

var a = 1;  let b = 2
来源：http://dali.yj202588.top/Article/details/gtsoiiktqv.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtftxfelao.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gtfpyvljxr.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gtjbdcujcz.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gtcobqsnhw.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gtjponakcu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gtwzjfgynf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gtgnzyigfz.html

for x in a { print(x) }
来源：http://dali.zdqjudy.top/Article/details/gthmfpqvsv.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gtxrvzarmm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gtizqmtbyd.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gtvmydrsdv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtyjmnnlju.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtrkmlppik.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtsaovxxtv.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gtgvwncazo.html

struct P { var x: Int }
来源：http://dali.gotoacloud.top/Article/details/gtcnqmeauh.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gtiemhxqjj.html

class A: Base { override func f() {} }
来源：http://dali.xylfe.cn/Article/details/gtlnktedpx.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gtithyzriy.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gtuqotbgpw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtalrivkvi.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gtfjtkdyas.html

[T29] Swift：guard 提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzxvvcun.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gtyvnaeqbx.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gtpkvkywys.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gtbwqluetu.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gthkykkgrq.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtyhqzluye.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gtbswtaclu.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtxnwpfkbx.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gtwchlvsni.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jianghu66.top/Article/details/gtfvkvijbt.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjhsqvog.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gtddfpwmga.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtklulqcni.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gteasiakry.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gtcmahrqce.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gtyfxwuily.html

[T37] Lua：字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtazzkhwcx.html

"a" .. "b"
来源：http://dali.xylfe.cn/Article/details/gtnbgkyqfj.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gtleglvgzb.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gtenzhfrzj.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtvphpffud.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gtkrqfsnpr.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gtcbwdwdrt.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtfkikrmkv.html

[T41] Perl：Hello World
来源：http://dali.bjfxy.top/Article/details/gtvxdaprsv.html

print "Hello\n";
来源：http://dali.pengpengdd.cyou/Article/details/gtwifaarcc.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtiyxhwnpg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tanke756.top/Article/details/gtmjjzmvxc.html

[T43] Perl：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtnmwugmkz.html

"值: $a"
来源：http://dali.316326.xyz/Article/details/gtcwmdxssf.html

[T44] Perl：条件
来源：http://dali.zhoulong.xyz/Article/details/gtjwynmrxu.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gtilzmlpsm.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gthmrxgphs.html

for my $x (@arr) { print $x; }
来源：http://dali.fzhhl.top/Article/details/gtassltbad.html

[T46] Perl：哈希操作
来源：http://dali.ivvv.top/Article/details/gtzirlvvcb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gttorngdty.html

[T47] Perl：正则捕获
来源：http://dali.yuanzhike.top/Article/details/gttpufnjig.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gtsncaykxe.html

[T48] Perl：正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtrqgimfvh.html

$s =~ s/old/new/g;
来源：http://dali.shangyingyoupin.top/Article/details/gtfarltcfi.html

[T49] Perl：函数
来源：http://dali.shuidangran.top/Article/details/gteotdwmyv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtqiergggi.html

[T50] Perl：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtygsgdwxf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gttdfduscd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgttcgyrt.html

[T51] Scala：Hello World
来源：http://dali.birdmap.top/Article/details/gtyfjeiofc.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtuwwzlfnt.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gtzwgjvdmq.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtubybiawu.html

[T53] Scala：字符串插值
来源：http://dali.ivvv.top/Article/details/gtkzcqrnos.html

s"值: $b"
来源：http://dali.hammf.cn/Article/details/gtxfwxdmkn.html

[T54] Scala：集合映射
来源：http://dali.xziqi.cn/Article/details/gtszgzzocl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.kuanghao11.cn/Article/details/gttnuiagqu.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtplfeamng.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gttyqtklzi.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gtyziumdcm.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtdwlovemy.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtubbxeccf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gtuhyanqae.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gtkillbmud.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gtynbtshdc.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gtqqaejimd.html

for (i <- 1 to 10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gttigrxcvx.html

[T60] Scala：折叠
来源：http://dali.wangdashe.top/Article/details/gthhahusgn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.bjfxy.top/Article/details/gtilpwtfvc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gthrewaspp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gtufgvnrgl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmwntfhwj.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gtttixluys.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gtpiefixpt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwnoaypo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.meibo888.top/Article/details/gtsmbiaiee.html

[U03] Py：加载 .env 配置
来源：http://dali.chenjidiqi.icu/Article/details/gtjaxdzapb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jlsjyb.cn/Article/details/gtolxoaxma.html

[U04] Py：变量调试打印
来源：http://dali.bjfxy.top/Article/details/gtylsgomxd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gtflbzocmm.html

[U05] Py：列表去重且保序
来源：http://dali.ivvv.top/Article/details/gtsnocnaxt.html

list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtmvljadoz.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gtsmhaeyxb.html

{**a, **b}
来源：http://dali.yj20258888.top/Article/details/gtpfpwszzj.html

[U07] Py：反转字典键值
来源：http://dali.0kj1m.cn/Article/details/gtupuiqlix.html

{v: k for k, v in d.items()}
来源：http://dali.dashuyun.cn/Article/details/gtjirnlcqc.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gtuxebzbjk.html

[y for x in nested for y in x]
来源：http://dali.jqgufenzy.top/Article/details/gtpvadherr.html

[U09] Py：字典取最大值的键
来源：http://dali.yanxiufei.cn/Article/details/gtrwfihqcy.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtcykcbnfu.html

[U10] Py：按值排序字典
来源：http://dali.gogol.net.cn/Article/details/gtixieyywl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gogol.net.cn/Article/details/gtjyhmbgmn.html

[U11] Py：生成器表达式
来源：http://dali.yj20258.top/Article/details/gtfrkwevif.html

(x * 2 for x in arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtzrbsoefp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gthfccjnjy.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gticcfckil.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtsefnvnbf.html

deque(maxlen=10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlojczhmr.html

[U14] Py：分组收集到列表
来源：http://dali.jqgufenzy.top/Article/details/gtcnquamct.html

defaultdict(list)
来源：http://dali.tian-w.cn/Article/details/gtspcyxkhu.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtuehhynkp.html

t = time.perf_counter()
来源：http://dali.hywenlv.cn/Article/details/gtailypjsl.html

[U16] Py：命令行参数解析
来源：http://dali.xuetiantiany.cn/Article/details/gtdurlzdfc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gtbsfinqsh.html

[U17] Py：初始化日志
来源：http://dali.sxryk.cn/Article/details/gtlvfuaarj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aizwys.cn/Article/details/gtowwtvwrf.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gtuokimicl.html

pat = re.compile(r"\d+")
来源：http://dali.cheryme.top/Article/details/gtravykdax.html

[U19] Py：正则替换带回调
来源：http://dali.hongshengwenyu.top/Article/details/gtifshkrxx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gtlprurxbb.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gtrtfcfhmr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gtknuswpfi.html

[U21] Py：自定义上下文管理器
来源：http://dali.ydzc1.top/Article/details/gtdlczcxxh.html

@contextlib.contextmanager
来源：http://dali.cdnleiting.top/Article/details/gtvomytjov.html

[U22] Py：矩阵转置
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxrsnejv.html

list(zip(*m))
来源：http://dali.yongpay.top/Article/details/gtksoigawz.html

[U23] Py：分块读取大文件
来源：http://dali.yj20258.top/Article/details/gtkhtkuxxl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gtsglaobyj.html

[U24] Py：路径操作
来源：http://dali.cucudq.cn/Article/details/gtahuyxujo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtsnssdkyl.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgufenzy.top/Article/details/gtgysejjzi.html

csv.DictReader(f)
来源：http://dali.daria6918.cn/Article/details/gtmbzdfxgd.html

[U26] Py：并发下载
来源：http://dali.yvedp.cn/Article/details/gtzijrzenp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shuidangran.top/Article/details/gtrkfajhxl.html

[U27] Py：异步 HTTP
来源：http://dali.zdqjudy.top/Article/details/gtwgblmlcg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hongshengwenyu.top/Article/details/gthglntqzf.html

[U28] Py：类型别名
来源：http://dali.fzhhl.top/Article/details/gtqnpmagkj.html

UserId = int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqjaqleu.html

[U29] Py：属性校验
来源：http://dali.cdnleiting.top/Article/details/gtlevbdiru.html

@property 与 @x.setter 配合
来源：http://dali.daria6918.cn/Article/details/gtetvbekqp.html

[U30] Py：数据类
来源：http://dali.cheryme.top/Article/details/gtncygrnux.html

@dataclass(slots=True)
来源：http://dali.dianchejie.cn/Article/details/gtctwxbdfa.html

[U31] Py：单测
来源：http://dali.jlsjyb.cn/Article/details/gtedupquva.html

python -m pytest -q
来源：http://dali.tianlin.xyz/Article/details/gtvhjtspsq.html

[U32] Py：代码格式化
来源：http://dali.dianchejie.cn/Article/details/gthogmrvxl.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gtizebganp.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gtokvdikxf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pengpengdd.cyou/Article/details/gtthfqicmd.html

[U34] Py：判断编码
来源：http://dali.tanke756.top/Article/details/gtwhrevtff.html

chardet.detect(raw)
来源：http://dali.9152youxi.cn/Article/details/gtjfrfcfjg.html

[U35] Py：发送邮件
来源：http://dali.tianlin.xyz/Article/details/gtjedbekwn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zycfv.cn/Article/details/gtypltiyyj.html

[U36] Py：定时任务
来源：http://dali.gotoacloud.top/Article/details/gtpmfkkrgk.html

schedule.every(10).minutes.do(job)
来源：http://dali.tanke756.top/Article/details/gtintjadwd.html

[U37] Py：读写 Excel
来源：http://dali.jlsjyb.cn/Article/details/gtzhmfmhsg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nwbrower.top/Article/details/gtufudymnh.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenlongwang.top/Article/details/gtahevkczz.html

Path(__file__).resolve().parent
来源：http://dali.yongpay.top/Article/details/gtyzudkxnm.html

[U39] Py：判断是否在交互环境
来源：http://dali.jlsjyb.cn/Article/details/gtywewkpiv.html

sys.stdout.isatty()
来源：http://dali.zhiwuduotai.top/Article/details/gtrkordzkx.html

[U40] Py：打印到标准错误
来源：http://dali.havefunace.top/Article/details/gtpascdrnv.html

print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtiwkzrlbi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zycfv.cn/Article/details/gtdduttqst.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gtmnjgykxu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenzaomai.com/Article/details/gtazidpnhj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gaohongyu789.top/Article/details/gtgrbsaieq.html

[U43] PHP：声明命名空间
来源：http://dali.jqgfzy.top/Article/details/gtbcloodcj.html

namespace App\Http;
来源：http://dali.mhx1999.top/Article/details/gtepklzqwa.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigufen.top/Article/details/gtgzenveeg.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gtbuhexoqg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.c1oappe.top/Article/details/gtyjlyhvzs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtfyztiebt.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtmgqymixy.html

?string $name = null
来源：http://dali.yangfankeji.com/Article/details/gtxzheygzc.html

[U47] PHP：联合类型
来源：http://dali.jiagoushi.top/Article/details/gtpzavqull.html

int|string $id
来源：http://dali.havefunace.top/Article/details/gtllekhqon.html

[U48] PHP：纯枚举
来源：http://dali.meibo888.top/Article/details/gticwrneqb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.kuanghao11.cn/Article/details/gtdriljvff.html

[U49] PHP：只读属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzeexird.html

public readonly string $name
来源：http://dali.zhiwuduotai.top/Article/details/gtwbmqlerk.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258.top/Article/details/gttoasjmus.html

public function __construct(private int $id) {}
来源：http://dali.shzxlz.cn/Article/details/gtewzwgkfk.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gtalhqtuos.html

[$a, $b] = $arr;
来源：http://dali.zhengqikj.top/Article/details/gtxbwrfexs.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtbtywhlcf.html

$double = fn($x) => $x * 2;
来源：http://dali.yuanzhike.top/Article/details/gtxobpsavt.html

[U53] PHP：空合并运算符
来源：http://dali.daria6918.cn/Article/details/gtcsajupwc.html

$v = $a ?? $b ?? "default";
来源：http://dali.kuanghao11.cn/Article/details/gtoinpwikl.html

[U54] PHP：空安全调用
来源：http://dali.jlsjyb.cn/Article/details/gtjqbylwip.html

$obj?->method()
来源：http://dali.guowangkeji.top/Article/details/gtptkukqvv.html

[U55] PHP：match 表达式
来源：http://dali.iojbl.cn/Article/details/gtklpzyzvv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gtwzlwmlag.html

[U56] PHP：命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoglcmvat.html

f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gthppygdqg.html

[U57] PHP：字符串插值
来源：http://dali.yj20258.top/Article/details/gtkcyjzbyz.html

"值: {$a}"
来源：http://dali.birdmap.top/Article/details/gtpootzowh.html

[U58] PHP：数组三件套
来源：http://dali.shangyingyoupin.top/Article/details/gtdjogbwyo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqudkcyjt.html


<!-- 参考信息 -->