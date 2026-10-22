代发 wailian999

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gt2oqfzrujq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gt2dbatvapk.html

[S34] C++：遍历 vector
来源：http://dali.snrcjt.cn/Article/details/gt2hrupkrud.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwmvshbc.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jeepqzsd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgllamrf.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvdzqmyx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2wxqaaeaa.html

[S37] C++：set
来源：http://dali.c1oappe.top/Article/details/gt2ytbtryey.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gt2zmdpwsoa.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gt2lvyxqkmn.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gt2qyhklanp.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljbrwgeq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gt2qqnmvqit.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gt2bvepigoq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gt2kllhnwcb.html

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2rgbeapow.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdaecrcf.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gt2yvyaqkjy.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gt2njwzadla.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gt2stausqsh.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gt2fjzifxon.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gt2mwzunmsg.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2safnwlat.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gt2hxsazhmp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gt2xwjxkgsb.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gt2pnvgdole.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2neazpxxx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gt2jgdzgevz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gt2tzeksmlg.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2sqjihmaq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkgxgpug.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukmycmwy.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtfixzq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gt2elysmvwt.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gt2bgmvpetm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2wapzwenz.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gt2dwptaesi.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gt2iouxfhcv.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gt2gnxmqqmg.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gt2ufajivhq.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gt2pzaxvyle.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gt2qfjaietp.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gt2ehhqmugf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwdhhrjb.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2otfhodxs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gt2nilnbtso.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gt2tfwihals.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gt2lthimcxr.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsfwvqxl.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gt2qbravwcz.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gt2mjttxruo.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gt2ffwmpsie.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnlurxuu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gt2aluibyjj.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2qbqgtivt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpkdgdyf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rruleago.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gt2hnzyosun.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ovrsfdff.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2upfzdhkj.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2rzeomvai.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gt2kusjjxmk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gt2ldmyosex.html

[T03] Kotlin：字符串模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqqmlulr.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gt2alekiden.html

[T04] Kotlin：空安全
来源：http://dali.fzhhl.top/Article/details/gt2fdmwtjgj.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gt2jkvejnlz.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adindboc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gt2tbbtejrw.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gt2hhssqluo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gt2cappfzzy.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gt2uqtmlfxf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shuidangran.top/Article/details/gt2yantqbfq.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gt2bthikwow.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2qkyzezbb.html

[T09] Kotlin：扩展函数
来源：http://dali.iojbl.cn/Article/details/gt2wyzkqdui.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gt2ktswyddt.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gt2kgzcdlpb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tanke756.top/Article/details/gt2efwthcrb.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gt2uuljywei.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gt2rpzehgdl.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gt2oclmvjgl.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vddngyuv.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gt2sfebbdhy.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gt2wlxamnzu.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gt2akupnidr.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gt2vhqxqlpg.html

[T15] Kotlin：接口
来源：http://dali.dashuyun.cn/Article/details/gt2nroxrhej.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2lvhpgyqi.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2zyjtkzte.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2vvmuffhj.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gt2qpeeckpl.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzoqzeol.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhpcescu.html

"值: \(b)"
来源：http://dali.ydzc1.top/Article/details/gt2rpqfjouy.html

[T19] Swift：可选绑定
来源：http://dali.haohaochexian.top/Article/details/gt2oilyhajh.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gt2ebvsubny.html

[T20] Swift：数组操作
来源：http://dali.birdmap.top/Article/details/gt2pddtrvop.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sysykeji.top/Article/details/gt2nsuyxidd.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gt2xtmnphcj.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gt2kcqlytxj.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gt2ywqsimbw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gt2uxkdqwtj.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmyzvstc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjtwzlye.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gt2wikryhkx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2iuammmnk.html

[T25] Swift：结构体
来源：http://dali.jiagoushi.top/Article/details/gt2udeebnis.html

struct P { var x: Int }
来源：http://dali.hnqzz.top/Article/details/gt2cfvxswvg.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gt2myhvxaqw.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gt2wpedynvh.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gt2hslruwhv.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gt2svbrndoy.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gt2fmyueidc.html

enum Color { case red, green }
来源：http://dali.ybcxt.top/Article/details/gt2bvlarmas.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gt2vsehytbe.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gt2edrmqoii.html

[T30] Swift：协议
来源：http://dali.sxryk.cn/Article/details/gt2ivyjpboh.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gt2bxbzewgv.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gt2krztkdgp.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vngqslvh.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gt2ovphxfon.html

local a = 1
来源：http://dali.tianlin.xyz/Article/details/gt2bammithl.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iohragpn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gt2ouxncuzz.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gt2qfdtajbw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gt2uvbwecux.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kimnzngw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2iauewbff.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gt2jorezhqn.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gt2dxuhpgpo.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gt2vxhdbidv.html

"a" .. "b"
来源：http://dali.nanxuanxn.top/Article/details/gt2nphxmdxj.html

[T38] Lua：条件
来源：http://dali.c1oappe.top/Article/details/gt2dwaxnaut.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gt2skkayqls.html

[T39] Lua：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2zycplnjj.html

string.find(s, "%d+")
来源：http://dali.ehwqpu.com/Article/details/gt2hzghdkqr.html

[T40] Lua：元表
来源：http://dali.tianlin.xyz/Article/details/gt2hoywkivs.html

setmetatable({}, { __index = base })
来源：http://dali.mhx1999.top/Article/details/gt2rornbbbh.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2yvewihpa.html

print "Hello\n";
来源：http://dali.dashuyun.cn/Article/details/gt2bmbfzksb.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avkjcmcz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gt2iysibnwf.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkfphwrh.html

"值: $a"
来源：http://dali.iojbl.cn/Article/details/gt2yvngtwol.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gt2tsjizawz.html

if ($a > 0) { print "正"; }
来源：http://dali.yueranfly.top/Article/details/gt2ndgailqs.html

[T45] Perl：数组遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmlfyvxh.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gt2bdhzdlhj.html

[T46] Perl：哈希操作
来源：http://dali.jiagoushi.top/Article/details/gt2vcphrunb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258.top/Article/details/gt2txoqlasn.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gt2ygwnbgbw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gt2ggrvpvlk.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gt2gssiiekp.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gt2sggqvmnk.html

[T49] Perl：函数
来源：http://dali.tianlin.xyz/Article/details/gt2rxzxdawy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vkhldqss.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2vjuyakrl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ybcxt.top/Article/details/gt2jxgbmyoc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gt2kbwbsofv.html

[T51] Scala：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2themxnpz.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvaygurp.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gt2zebmmqhj.html

val a = 1;  var b = 2
来源：http://dali.dianchejie.cn/Article/details/gt2sfkuadpb.html

[T53] Scala：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gt2axbkugwc.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gt2tdkdrexi.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gt2solsmhjp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gt2wixzutvj.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gt2xyqczrit.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gt2acstwofu.html

[T56] Scala：样例类
来源：http://dali.mhx1999.top/Article/details/gt2jfueoijx.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gt2ilstxtzk.html

[T57] Scala：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ovgjxmpq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gt2nhfmjxhv.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gt2oleendzt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2zkngmmuf.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gt2bpkmuijw.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gt2bfirlpub.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gt2jbovhwpg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigfzy.top/Article/details/gt2iawyuevp.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2pifvvvqy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2fupjxdtt.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2xdlawrpr.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gt2wdfmblic.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gt2yfmhywax.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2roywosrn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gt2zxazlcgx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvypacl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gt2ccxoykxn.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gt2yrakaaxe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gt2hdwtjgzc.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gt2vadorwug.html

list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2yfthwewt.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gt2oaghxbab.html

{**a, **b}
来源：http://dali.cashguo.top/Article/details/gt2ndcbyfsp.html

[U07] Py：反转字典键值
来源：http://dali.hnxiangtu.top/Article/details/gt2lhznjfeu.html

{v: k for k, v in d.items()}
来源：http://dali.zhengqikj.top/Article/details/gt2nvyrjqln.html

[U08] Py：展平二维列表
来源：http://dali.gzhubu.top/Article/details/gt2muplsinw.html

[y for x in nested for y in x]
来源：http://dali.ivvv.top/Article/details/gt2euzcwyol.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iyzkmyko.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gt2yjjlfxhe.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gt2iuqvuhbc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fengsongda.top/Article/details/gt2owsfrpxr.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2raebovrm.html

(x * 2 for x in arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbgkemra.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cashguo.top/Article/details/gt2uyxtkmsy.html

Counter(arr).most_common(3)
来源：http://dali.tanke756.top/Article/details/gt2kejdnxdv.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gt2xdhmtoxe.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gt2dwsplpfa.html

[U14] Py：分组收集到列表
来源：http://dali.ydzc1.top/Article/details/gt2oaxkanhb.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gt2dcoqipfl.html

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gt2vnlsuskb.html

t = time.perf_counter()
来源：http://dali.mhx1999.top/Article/details/gt2hgnfcgsg.html

[U16] Py：命令行参数解析
来源：http://dali.zhengqikj.top/Article/details/gt2wfmgqylc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbobgabe.html

[U17] Py：初始化日志
来源：http://dali.smart0.xyz/Article/details/gt2fdpcwadg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj202588.top/Article/details/gt2iqtubzkq.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gt2jgwbdbvy.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gt2pfcibzqa.html

[U19] Py：正则替换带回调
来源：http://dali.yongpay.top/Article/details/gt2uuupimwd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gt2iuzsiegb.html

[U20] Py：缓存函数结果
来源：http://dali.nwbrower.top/Article/details/gt2eiwoyvtq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ppjwa.cn/Article/details/gt2zkvvmohh.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangdashe.top/Article/details/gt2qznggyfu.html

@contextlib.contextmanager
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuurwqol.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gt2kgehjjan.html

list(zip(*m))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrdxqfbm.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gt2atdilyby.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gt2gonipkkb.html

[U24] Py：路径操作
来源：http://dali.gotoacloud.top/Article/details/gt2olsqdiop.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gt2jvqrdhte.html

[U25] Py：CSV 按字典读
来源：http://dali.daxiang520.top/Article/details/gt2welpabnr.html

csv.DictReader(f)
来源：http://dali.daria6918.cn/Article/details/gt2vnvovger.html

[U26] Py：并发下载
来源：http://dali.316326.xyz/Article/details/gt2kdzlnroj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.meibo888.top/Article/details/gt2sildohuc.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigufen.top/Article/details/gt2induifvw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.redwolf501.top/Article/details/gt2dpanxfns.html

[U28] Py：类型别名
来源：http://dali.dianchejie.cn/Article/details/gt2mjitgpnq.html

UserId = int
来源：http://dali.shangyingyoupin.top/Article/details/gt2zscvsjeb.html

[U29] Py：属性校验
来源：http://dali.quarkkingdee.top/Article/details/gt2aqbygolo.html

@property 与 @x.setter 配合
来源：http://dali.yanxiufei.cn/Article/details/gt2ngdifsgy.html

[U30] Py：数据类
来源：http://dali.hnqzz.top/Article/details/gt2kaqfoxjd.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gt2mwjmozbq.html

[U31] Py：单测
来源：http://dali.gzhubu.top/Article/details/gt2iwvtibmc.html

python -m pytest -q
来源：http://dali.jqgfzy.top/Article/details/gt2enoxskha.html

[U32] Py：代码格式化
来源：http://dali.cdnleiting.top/Article/details/gt2jvqclhew.html

ruff format . && ruff check --fix .
来源：http://dali.ehwqpu.com/Article/details/gt2xiaaswpz.html

[U33] Py：打包发布
来源：http://dali.fengsongda.top/Article/details/gt2cnvxgssx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zycfv.cn/Article/details/gt2fzdmohlt.html

[U34] Py：判断编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vajezjgx.html

chardet.detect(raw)
来源：http://dali.xziqi.cn/Article/details/gt2htrrzvep.html

[U35] Py：发送邮件
来源：http://dali.daxiang520.top/Article/details/gt2ieefzboa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guannengcc.top/Article/details/gt2durvqlkf.html

[U36] Py：定时任务
来源：http://dali.zdqjudy.top/Article/details/gt2wmkhphzf.html

schedule.every(10).minutes.do(job)
来源：http://dali.meibo888.top/Article/details/gt2qkwhzjpt.html

[U37] Py：读写 Excel
来源：http://dali.yvedp.cn/Article/details/gt2totuntdt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangshuangyany.cn/Article/details/gt2omhluple.html

[U38] Py：获取脚本所在目录
来源：http://dali.haohaochexian.top/Article/details/gt2fnoomdig.html

Path(__file__).resolve().parent
来源：http://dali.kuanghao11.cn/Article/details/gt2bxskasjo.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gt2wqkqzust.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjurjuej.html

[U40] Py：打印到标准错误
来源：http://dali.daria6918.cn/Article/details/gt2gwurrxcl.html

print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gt2igekbxmb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xinyue.icu/Article/details/gt2ytefjuva.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2byzivoac.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.0kj1m.cn/Article/details/gt2dnmhbpqs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itsvyaue.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lurcznjx.html

namespace App\Http;
来源：http://dali.hammf.cn/Article/details/gt2sqipnqkw.html

[U44] PHP：开启严格类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdniqaoo.html

declare(strict_types=1);
来源：http://dali.tanke756.top/Article/details/gt2boberwst.html

[U45] PHP：类型声明与返回类型
来源：http://dali.birdmap.top/Article/details/gt2bjukcfrc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2edfxwsxf.html

[U46] PHP：可空类型
来源：http://dali.chenlongwang.top/Article/details/gt2zlgfyvxx.html

?string $name = null
来源：http://dali.zhengqikj.top/Article/details/gt2rprosbiu.html

[U47] PHP：联合类型
来源：http://dali.yanxiufei.cn/Article/details/gt2norwaldj.html

int|string $id
来源：http://dali.tanke756.top/Article/details/gt2kcefbuyz.html

[U48] PHP：纯枚举
来源：http://dali.fengsongda.top/Article/details/gt2nwgdgoiw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gt2knwbedwg.html

[U49] PHP：只读属性
来源：http://dali.jlsjyb.cn/Article/details/gt2jiiaenbv.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gt2tsdvpzse.html

[U50] PHP：构造器属性提升
来源：http://dali.dashuyun.cn/Article/details/gt2qkbtgjax.html

public function __construct(private int $id) {}
来源：http://dali.jianghu66.top/Article/details/gt2rseykrkg.html

[U51] PHP：数组解构
来源：http://dali.tian-w.cn/Article/details/gt2zuvkkbss.html

[$a, $b] = $arr;
来源：http://dali.gotoacloud.top/Article/details/gt2rowozdhl.html

[U52] PHP：箭头函数
来源：http://dali.hammf.cn/Article/details/gt2ssfbicld.html

$double = fn($x) => $x * 2;
来源：http://dali.cashguo.top/Article/details/gt2jvfhwwlm.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258.top/Article/details/gt2mhsighoe.html

$v = $a ?? $b ?? "default";
来源：http://dali.0kj1m.cn/Article/details/gt2xoiufaol.html

[U54] PHP：空安全调用
来源：http://dali.gotoacloud.top/Article/details/gt2keilusrv.html

$obj?->method()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqsthfis.html

[U55] PHP：match 表达式
来源：http://dali.dianchejie.cn/Article/details/gt2sogzdssw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tanke756.top/Article/details/gt2kbezxhxr.html

[U56] PHP：命名参数
来源：http://dali.c1oappe.top/Article/details/gt2couqjxmw.html

f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2sovlmotz.html

[U57] PHP：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2nugklcam.html

"值: {$a}"
来源：http://dali.hnxiangtu.top/Article/details/gt2puzdjedw.html

[U58] PHP：数组三件套
来源：http://dali.yuanzhike.top/Article/details/gt2kjoazjat.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppisnvwt.html


<!-- 参考信息 -->