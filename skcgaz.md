代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gtjpvjxviv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gthbhqzqyi.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gtdenudbuk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gteupadnwp.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtavxjvmfk.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gtfmelfofg.html

[S44] C++：引用传参
来源：http://dali.9152youxi.cn/Article/details/gtpnelxgde.html

void inc(int &x) { ++x; }
来源：http://dali.shuidangran.top/Article/details/gtuxqhlkxq.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gtlxasojqh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtdrvfdwll.html

[S46] C++：函数模板
来源：http://dali.wangdashe.top/Article/details/gtpplxlsid.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gtzydsnvph.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gtqkafaroc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gtljahcfgp.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgtzmqio.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtfhaorj.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gtudadazpr.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gtgboauycn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gtjsvuizqj.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gtmarcqugt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gttivcvcnf.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtskkttxkf.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gtzcdulqla.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gtrkpdxywy.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gtdsflbuyh.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gtruxjbkfc.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gtpcwfafuu.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gttfzbhnfv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gtiyqqxmom.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gteoejhdvc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gtyheocain.html

[S56] C++：optional
来源：http://dali.hnxiangtu.top/Article/details/gttmcivgyy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gttaagupjl.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtuubvhdrv.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtuhxobuok.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gtoekqteas.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gteaizibby.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gtiwwvnpbr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gtwscrvfoh.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gtxqohyebp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sxryk.cn/Article/details/gtvtqwzkwj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtyqmghqrx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtcdscwalb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnrvmzoae.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gtglquhhih.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwzxapgw.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtwlaaxwsd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdfrmkin.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gtyzpbrrze.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gtslrhmozz.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gtaodryzyw.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gtmbxlhnwz.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtcfncriap.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtauuuguzz.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtkkfkzwaf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtnsmebksd.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtxzghabkt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gtqjyqnhac.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gttztrhxot.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtfebkqbmh.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gtgskfmzwy.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gtlyvxwtwk.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gtvcdkfzhi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gtkfapjdil.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gtskgkckjd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gtbtvgkjld.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gtgetfenxx.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtrieqhavq.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gtufhbadji.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gtrqwpmadk.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtygqkgkbj.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtcnoaxhgt.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gtxrabwiic.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtgyxidhif.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtfghscgxg.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtlyctidje.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gtegpjxjzn.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtedrhswsb.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtafoaceub.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gtmjvdzlsu.html

[T19] Swift：可选绑定
来源：http://dali.ybcxt.top/Article/details/gtffvbizzo.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gtmyqcigzv.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gtnxpmcqec.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gtzmbnkgzs.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gtmbfmgloq.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gtfdqvnytu.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gtwgxpeijx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gtwpufzggk.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtfhdxcqpm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtoiqdtpps.html

[T24] Swift：闭包
来源：http://dali.nwbrower.top/Article/details/gtirvscmtw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtfbcqwbnu.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gtfmdbmoay.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gteexyzkei.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtmdtegbpm.html

class A: Base { override func f() {} }
来源：http://dali.316326.xyz/Article/details/gtsduidypi.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gtubpavzlg.html

do { try f() } catch { print(error) }
来源：http://dali.nanxuanxn.top/Article/details/gtcujkhify.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gtkbuuvpan.html

enum Color { case red, green }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhixiwwr.html

[T29] Swift：guard 提前返回
来源：http://dali.chenzaomai.com/Article/details/gtszbglxea.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtlqkozsdb.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gtgrjzfkaj.html

protocol Shape { func area() -> Double }
来源：http://dali.ppjwa.cn/Article/details/gttggfyuqo.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtkcmdgtts.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtpbcrxdfa.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtdvxrhbax.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtaocozcks.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gteyvdqsax.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zdqjudy.top/Article/details/gtvgiawgyb.html

[T34] Lua：遍历表
来源：http://dali.shuidangran.top/Article/details/gtuozfwgkz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gtsfzcoksh.html

[T35] Lua：字典表
来源：http://dali.jinghuilouyu.cn/Article/details/gtedvymuyd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtjhxecvaz.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gtpospsyjv.html

function add(a, b) return a + b end
来源：http://dali.hammf.cn/Article/details/gtiktubbsm.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtjkjclvrf.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gtgxqdpbzz.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gtlnjxsodc.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gtgmahlarl.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtitzwhhow.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gtnpdpduvv.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gtdyyagatj.html

setmetatable({}, { __index = base })
来源：http://dali.yueranfly.top/Article/details/gtzyfcatrk.html

[T41] Perl：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtwzqnickw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gtpfkmevrw.html

[T42] Perl：变量类型
来源：http://dali.hfpthk.cn/Article/details/gteltwecjm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gtwvnhaomn.html

[T43] Perl：字符串插值
来源：http://dali.ivvv.top/Article/details/gtvtsmfjtn.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gtsuiigvit.html

[T44] Perl：条件
来源：http://dali.tanke756.top/Article/details/gthyuyavag.html

if ($a > 0) { print "正"; }
来源：http://dali.0kj1m.cn/Article/details/gtlmzycjmz.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtusaciwkf.html

for my $x (@arr) { print $x; }
来源：http://dali.yangfankeji.com/Article/details/gtnfpwijyb.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gtijvrkape.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gttvgcahif.html

[T47] Perl：正则捕获
来源：http://dali.pengpengdd.cyou/Article/details/gtbnahahls.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gtxpfaqdsr.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gttsgmcikz.html

$s =~ s/old/new/g;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvfqabcn.html

[T49] Perl：函数
来源：http://dali.ivvv.top/Article/details/gtydctmsao.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtyvxvmppv.html

[T50] Perl：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtojyexujp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.9152youxi.cn/Article/details/gtchbvhkzs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtphmchuxp.html

[T51] Scala：Hello World
来源：http://dali.xinyue.icu/Article/details/gtdoziuahc.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtbdgxlnkb.html

[T52] Scala：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbsniliw.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtoysghsdk.html

[T53] Scala：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtbdkbiegh.html

s"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtglxqfddj.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtdfkxninw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sufxvd.cn/Article/details/gttiilztob.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtjelovtkx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daxiang520.top/Article/details/gtlcatkjnl.html

[T56] Scala：样例类
来源：http://dali.sweek.top/Article/details/gtiecxralj.html

case class User(name: String, age: Int)
来源：http://dali.yonumen.top/Article/details/gtfzxjmetw.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtbbrnkjcv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gtohzectnw.html

[T58] Scala：函数定义
来源：http://dali.chenzaomai.com/Article/details/gtfygfkgkv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtuhsoxmqa.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtbvnaxpqd.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtnqwpieou.html

[T60] Scala：折叠
来源：http://dali.jinghuilouyu.cn/Article/details/gtmacqnjvg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiqhmcoo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtguoeoayl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gtcifwtxed.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gturdvslvo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gtxyillyji.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgfzy.top/Article/details/gtgntpsrvg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.snrcjt.cn/Article/details/gtodievljn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtddjlnspq.html

[U03] Py：加载 .env 配置
来源：http://dali.jyoumei.cn/Article/details/gtdxzminch.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwhxotan.html

[U04] Py：变量调试打印
来源：http://dali.guannengcc.top/Article/details/gtcvcuejkl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfjwcnjw.html

[U05] Py：列表去重且保序
来源：http://dali.chenlongwang.top/Article/details/gtrhepbevx.html

list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gtqomrqzel.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gtcsttrfij.html

{**a, **b}
来源：http://dali.gzhubu.top/Article/details/gtttzscjyj.html

[U07] Py：反转字典键值
来源：http://dali.sweek.top/Article/details/gtnzpsqedn.html

{v: k for k, v in d.items()}
来源：http://dali.dianchejie.cn/Article/details/gtkmwggybc.html

[U08] Py：展平二维列表
来源：http://dali.hfpthk.cn/Article/details/gtogqlehxh.html

[y for x in nested for y in x]
来源：http://dali.xinyue.icu/Article/details/gtnraubqax.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gtamezoswq.html

max(d, key=d.get)
来源：http://dali.guannengcc.top/Article/details/gtdmqgkltw.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gtlhgebaph.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gtziljwrwk.html

[U11] Py：生成器表达式
来源：http://dali.yj20258.top/Article/details/gtivuuygkk.html

(x * 2 for x in arr)
来源：http://dali.zhixingplan.top/Article/details/gtxuqutmvo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gtpibqkqin.html

Counter(arr).most_common(3)
来源：http://dali.vqdsnc.cn/Article/details/gtnfjqoxfn.html

[U13] Py：固定长度队列
来源：http://dali.bjfxy.top/Article/details/gtrgcrmbyy.html

deque(maxlen=10)
来源：http://dali.ybcxt.top/Article/details/gtyipaaspz.html

[U14] Py：分组收集到列表
来源：http://dali.jiagoushi.top/Article/details/gtugacawiz.html

defaultdict(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgoqpesi.html

[U15] Py：高精度计时
来源：http://dali.havefunace.top/Article/details/gtiztevwnl.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gtqffbstyg.html

[U16] Py：命令行参数解析
来源：http://dali.zhoulong.xyz/Article/details/gtdugheych.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ydzc1.top/Article/details/gtbjzgufnj.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gtsyoaugsx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xylfe.cn/Article/details/gtrmyaxida.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gtdbxdcple.html

pat = re.compile(r"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtuoicpxkt.html

[U19] Py：正则替换带回调
来源：http://dali.chenjidiqi.icu/Article/details/gtmkqifqcx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.mhx1999.top/Article/details/gtvaucxjdq.html

[U20] Py：缓存函数结果
来源：http://dali.yueranfly.top/Article/details/gthxhvfhjw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gtvgbrnhxy.html

[U21] Py：自定义上下文管理器
来源：http://dali.cdnleiting.top/Article/details/gtjizieksj.html

@contextlib.contextmanager
来源：http://dali.chenzaomai.com/Article/details/gtqvqwxkua.html

[U22] Py：矩阵转置
来源：http://dali.svipenyu.cn/Article/details/gtdqgiygrs.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gtdjrlodya.html

[U23] Py：分块读取大文件
来源：http://dali.yuanzhike.top/Article/details/gtyukmrcki.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dashuyun.cn/Article/details/gtcbsosxma.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gtimzofrys.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtjvjcwtsd.html

[U25] Py：CSV 按字典读
来源：http://dali.9152youxi.cn/Article/details/gtoixqsujn.html

csv.DictReader(f)
来源：http://dali.cheryme.top/Article/details/gtpnaxxhfu.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gtierjafwt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gtxjdiqbie.html

[U27] Py：异步 HTTP
来源：http://dali.vqdsnc.cn/Article/details/gtpzxcuihl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daxiang520.top/Article/details/gtnhdotoww.html

[U28] Py：类型别名
来源：http://dali.svipenyu.cn/Article/details/gtcudmmnkp.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gtnyuayqlw.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gtkwcjzljy.html

@property 与 @x.setter 配合
来源：http://dali.hysaishi.cn/Article/details/gtlsfapemh.html

[U30] Py：数据类
来源：http://dali.ybcxt.top/Article/details/gtytyoxkkl.html

@dataclass(slots=True)
来源：http://dali.sxryk.cn/Article/details/gtsashpjjy.html

[U31] Py：单测
来源：http://dali.ivvv.top/Article/details/gtxspjjpuj.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gtdtsaozno.html

[U32] Py：代码格式化
来源：http://dali.wangdashe.top/Article/details/gtumybdbot.html

ruff format . && ruff check --fix .
来源：http://dali.sufxvd.cn/Article/details/gtzpiqnmvo.html

[U33] Py：打包发布
来源：http://dali.yanxiufei.cn/Article/details/gtrktgkpop.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.birdmap.top/Article/details/gtajmeqfnu.html

[U34] Py：判断编码
来源：http://dali.birdmap.top/Article/details/gtcxkqogwr.html

chardet.detect(raw)
来源：http://dali.guannengcc.top/Article/details/gtymoqnsok.html

[U35] Py：发送邮件
来源：http://dali.ppjwa.cn/Article/details/gtdujrqoju.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gtexdwzsin.html

[U36] Py：定时任务
来源：http://dali.ydzc1.top/Article/details/gtgrhtlcrw.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxinkj.top/Article/details/gtdgbyaure.html

[U37] Py：读写 Excel
来源：http://dali.meibo888.top/Article/details/gtahbihkct.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ydzc1.top/Article/details/gtiehqjxnl.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gtkujhzqfa.html

Path(__file__).resolve().parent
来源：http://dali.316326.xyz/Article/details/gtpxlozthk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhixingplan.top/Article/details/gtwwpemnoj.html

sys.stdout.isatty()
来源：http://dali.pengpengdd.cyou/Article/details/gtilsmiulv.html

[U40] Py：打印到标准错误
来源：http://dali.vqdsnc.cn/Article/details/gtekyahzay.html

print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtincfihkv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.smart0.xyz/Article/details/gthtlieqcr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ppjwa.cn/Article/details/gtedefyulq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.birdmap.top/Article/details/gtcpmhdvzj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigfzy.top/Article/details/gtcyeoetvv.html

[U43] PHP：声明命名空间
来源：http://dali.jianghu66.top/Article/details/gtajmillan.html

namespace App\Http;
来源：http://dali.kuanghao11.cn/Article/details/gtgipqxtde.html

[U44] PHP：开启严格类型
来源：http://dali.yangfankeji.com/Article/details/gtwolforag.html

declare(strict_types=1);
来源：http://dali.jinqigufen.top/Article/details/gtbzviocym.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gtjbzxrvut.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtwvklcjlk.html

[U46] PHP：可空类型
来源：http://dali.jlsjyb.cn/Article/details/gtyvgvsvez.html

?string $name = null
来源：http://dali.xinyue.icu/Article/details/gtunrjlhuu.html

[U47] PHP：联合类型
来源：http://dali.0kj1m.cn/Article/details/gtekbdpwkw.html

int|string $id
来源：http://dali.bjfxy.top/Article/details/gtutrawgvk.html

[U48] PHP：纯枚举
来源：http://dali.xuanzx.com/Article/details/gtskblnqpk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aizwys.cn/Article/details/gtisjtkvns.html

[U49] PHP：只读属性
来源：http://dali.zhoulong.xyz/Article/details/gtipyafikl.html

public readonly string $name
来源：http://dali.daxiang520.top/Article/details/gtjemcumxs.html

[U50] PHP：构造器属性提升
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgjpjsfe.html

public function __construct(private int $id) {}
来源：http://dali.svipenyu.cn/Article/details/gtfasfhqaf.html

[U51] PHP：数组解构
来源：http://dali.aizwys.cn/Article/details/gtixbytriq.html

[$a, $b] = $arr;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmvaelah.html

[U52] PHP：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtjprluots.html

$double = fn($x) => $x * 2;
来源：http://dali.fzhhl.top/Article/details/gtmtllgbxd.html

[U53] PHP：空合并运算符
来源：http://dali.jlsjyb.cn/Article/details/gtxhfrzlvm.html

$v = $a ?? $b ?? "default";
来源：http://dali.meibo888.top/Article/details/gtimuzxbqf.html

[U54] PHP：空安全调用
来源：http://dali.xuetiantiany.cn/Article/details/gtzhyczbkw.html

$obj?->method()
来源：http://dali.sxryk.cn/Article/details/gtwpltpfou.html

[U55] PHP：match 表达式
来源：http://dali.jianghu66.top/Article/details/gtrnkugmhm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gtjogclgyj.html

[U56] PHP：命名参数
来源：http://dali.daria6918.cn/Article/details/gtcnteqhxo.html

f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtwljuxzoy.html

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtbxbaqdgt.html

"值: {$a}"
来源：http://dali.gzhubu.top/Article/details/gtybukyecy.html

[U58] PHP：数组三件套
来源：http://dali.sufxvd.cn/Article/details/gtxucccelq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.c1oappe.top/Article/details/gtiphhjlvq.html

[U59] PHP：自定义排序
来源：http://dali.gogol.net.cn/Article/details/gtgepzvszf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gtjwryhxzx.html

[U60] PHP：JSON 编解码
来源：http://dali.ppjwa.cn/Article/details/gtjotodpoz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yongpay.top/Article/details/gtlfqtsogt.html

[U61] PHP：正则
来源：http://dali.jiagoushi.top/Article/details/gttimlbhke.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtndrqhfwo.html

[U62] PHP：日期对象
来源：http://dali.ppjwa.cn/Article/details/gthvdkoxtz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tian-w.cn/Article/details/gtzewmxeek.html

[U63] PHP：文件读写
来源：http://dali.jiagoushi.top/Article/details/gthcxkhrlr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtveykkono.html

[U64] PHP：目录遍历
来源：http://dali.zhongyouzk.top/Article/details/gtnmuohxdf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.0kj1m.cn/Article/details/gtyfiqnywk.html

[U65] PHP：会话
来源：http://dali.zhengqikj.top/Article/details/gtaxtahsle.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtjrbfessc.html

[U66] PHP：设置 Cookie
来源：http://dali.yj202588.top/Article/details/gtwjkucslb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovjykjan.html


<!-- 参考信息 -->