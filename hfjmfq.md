代发 wailian999

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gt2wgezbqqg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2sdsotkpv.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gt2njfkelvk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2lvbjddyw.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gt2qjoumhmh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gt2aifndvbw.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gt2ugjxyhmp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwedynz.html

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gt2mzywbymb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gt2vnnifyxr.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gt2cpnkmmif.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gt2dzhzpamh.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gt2zkjpleri.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gt2jhospiut.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gt2fvvbxrwc.html

class B : public Base { public: void f() override {} };
来源：http://dali.tian-w.cn/Article/details/gt2czunsugf.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gt2brelhlll.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gt2crrrtdto.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gt2xbosofzd.html

void inc(int &x) { ++x; }
来源：http://dali.yj202588.top/Article/details/gt2misbizat.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gt2zcfrmggz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjxmzzwn.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gt2owhkmdxs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gt2oyoqpmmm.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gt2cnkqvdrw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gt2zozljfkf.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2tudizowb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gt2mwuxjart.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2kbsdkgsu.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gt2hbztgrjd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gt2tnaomjxk.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2vsvogmoo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctscpjxn.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gt2meqgnxmt.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gt2ximvrnyk.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gt2ydmwkvds.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gt2scjeslch.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gt2nhbmfyji.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gt2suggonvb.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gt2khjudulu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gt2gxinpbhf.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2bmssqvbp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2fpujkoxd.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gt2qzofnsgz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gt2qticcrxy.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gt2homlfnoy.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gt2kqfnuxme.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejefarxf.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gt2zyklexls.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gt2retzbtfx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gt2yojnehxu.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2thsmqopt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2ongowgau.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2xvzoagkn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gt2utoboxyv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2oeldcnbs.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2ndbltdch.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2gdcvlkmk.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gt2pwcpzybp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gt2mbhpctno.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gt2ogijsgvs.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gt2gczuqmfo.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gt2jqwnylhq.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gt2hoqyjgif.html

[T05] Kotlin：when 表达式
来源：http://dali.xuanzx.com/Article/details/gt2lugzzwbd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtdkxqrd.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gt2hqbwyctm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqnyimsh.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gt2rpqowsiq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gt2fjtltvel.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gt2kxexykcl.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2aubjpcfq.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gt2gfnaoqab.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gt2gscnrxpc.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gt2maahbvys.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gt2mhdcdoik.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gt2wrvzntht.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gt2ujvtraca.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gt2wviodpas.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2vbkgzwsu.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmrbpcxf.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwinrxxn.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gt2qrhrmqot.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gt2dkmrgkyf.html

[T15] Kotlin：接口
来源：http://dali.havefunace.top/Article/details/gt2jewuipfp.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gt2gojfmznu.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aftsklcn.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2tvgtsopg.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcsosoxw.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2kwyaqphe.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2ltpbtpxc.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gt2idelnzua.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gt2gprtldqi.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gt2anupdjrg.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gt2equkxsgv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gt2qmfdhiuq.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhhniklg.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gt2prafhilx.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gt2ihqamqmo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gt2egmtixvn.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gt2relmpbiy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gt2kxfixzkx.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gt2kxlthpvo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2igmkxnpd.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gt2sfvjhebq.html

struct P { var x: Int }
来源：http://dali.dianchejie.cn/Article/details/gt2funiepfk.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gt2vacxgmrx.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gt2ioqtxmhs.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gt2rkkyzzte.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gt2dbxphoco.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gt2yzvlbvgs.html

enum Color { case red, green }
来源：http://dali.tanke756.top/Article/details/gt2sgryvrok.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gt2mzfmwgxk.html

guard let x = opt else { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psmvoest.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gt2wrnehcso.html

protocol Shape { func area() -> Double }
来源：http://dali.jiagoushi.top/Article/details/gt2ruqdsung.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2mgayfcpl.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2qttelegb.html

[T32] Lua：局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2bcptyfyr.html

local a = 1
来源：http://dali.sufxvd.cn/Article/details/gt2glacajbn.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zanekbya.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gt2vswnnzfi.html

[T34] Lua：遍历表
来源：http://dali.xziqi.cn/Article/details/gt2hrxqztrh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gt2vffypnbb.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gt2qmlqeshj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtaluhbo.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2rufniexh.html

function add(a, b) return a + b end
来源：http://dali.zhiwuduotai.top/Article/details/gt2disdijbe.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2alxiwsmg.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gt2dyogwjbt.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2wapzqyoe.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gt2cwsxjcid.html

[T39] Lua：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2gujgbrqn.html

string.find(s, "%d+")
来源：http://dali.hammf.cn/Article/details/gt2inrqtlbt.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gt2dxmhkxjf.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twgvnjca.html

[T41] Perl：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2ipmwsaby.html

print "Hello\n";
来源：http://dali.hnqzz.top/Article/details/gt2mplosvqe.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gt2fnelblqn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gt2fisjvekz.html

[T43] Perl：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2vjrwqmzj.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gt2zugkrdzp.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gt2mufmkjed.html

if ($a > 0) { print "正"; }
来源：http://dali.jiagoushi.top/Article/details/gt2utmexbkd.html

[T45] Perl：数组遍历
来源：http://dali.hysaishi.cn/Article/details/gt2pcoaubhn.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gt2tzxowiyn.html

[T46] Perl：哈希操作
来源：http://dali.yongpay.top/Article/details/gt2qgsdpzsb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rsrseiuk.html

[T47] Perl：正则捕获
来源：http://dali.jqgufenzy.top/Article/details/gt2bbvbxmsc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gt2aganotvc.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gt2yhaphqgb.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gt2sdxvyyzc.html

[T49] Perl：函数
来源：http://dali.xziqi.cn/Article/details/gt2xsupiyid.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2oyttjdcq.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2bqzumivg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gt2epjmpmxm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gt2fvsskilq.html

[T51] Scala：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2ienrfrxt.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2dyoekpbo.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gt2qxsqunzl.html

val a = 1;  var b = 2
来源：http://dali.hfpthk.cn/Article/details/gt2ipckrxqj.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gt2ocyndadz.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctozsxwh.html

[T54] Scala：集合映射
来源：http://dali.daxiang520.top/Article/details/gt2pvtgpthe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gt2luxgudjd.html

[T55] Scala：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efktclnn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guannengcc.top/Article/details/gt2oceolbzw.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gt2nrouvfoz.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gt2otnrhxti.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2iyjuakuw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnnxldtk.html

[T58] Scala：函数定义
来源：http://dali.316326.xyz/Article/details/gt2osmvhafm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigfzy.top/Article/details/gt2gwdznbjk.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrqlqshe.html

for (i <- 1 to 10) println(i)
来源：http://dali.redwolf501.top/Article/details/gt2sevetbrl.html

[T60] Scala：折叠
来源：http://dali.iojbl.cn/Article/details/gt2oroxwnah.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ouuylesd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2hluughyj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2bsiqcgqx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzmxbxsb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gt2snhyeglt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.bjfxy.top/Article/details/gt2vccypbni.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuxming.cn/Article/details/gt2birymzhc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2myvjpacw.html

[U03] Py：加载 .env 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2arvnvegq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gt2gmuzynfm.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gt2tubdzxac.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.haohaochexian.top/Article/details/gt2vqwiiefo.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohsyvszf.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gt2siqucyqd.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvldjiby.html

{**a, **b}
来源：http://dali.daxiang520.top/Article/details/gt2roipsevw.html

[U07] Py：反转字典键值
来源：http://dali.guowangkeji.top/Article/details/gt2xebeyjsg.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gt2kxvaxoah.html

[U08] Py：展平二维列表
来源：http://dali.xziqi.cn/Article/details/gt2mufsqzug.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gt2lfojuvch.html

[U09] Py：字典取最大值的键
来源：http://dali.yangfankeji.com/Article/details/gt2apitrozq.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gt2fekhjoaw.html

[U10] Py：按值排序字典
来源：http://dali.yongpay.top/Article/details/gt2laanbrwz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijplnoru.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gt2vnapwaaf.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gt2twnndnhb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhoulong.xyz/Article/details/gt2fwivhhxl.html

Counter(arr).most_common(3)
来源：http://dali.ehwqpu.com/Article/details/gt2amdmbhcy.html

[U13] Py：固定长度队列
来源：http://dali.svipenyu.cn/Article/details/gt2ahujuxsi.html

deque(maxlen=10)
来源：http://dali.yj202588.top/Article/details/gt2omwwmjqo.html

[U14] Py：分组收集到列表
来源：http://dali.bjfxy.top/Article/details/gt2nxqznvnw.html

defaultdict(list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mltftzkh.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gt2fnkasprl.html

t = time.perf_counter()
来源：http://dali.dianchejie.cn/Article/details/gt2iwcvpbwd.html

[U16] Py：命令行参数解析
来源：http://dali.xylfe.cn/Article/details/gt2egthrpvs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.9152youxi.cn/Article/details/gt2fsrwmxpa.html

[U17] Py：初始化日志
来源：http://dali.mhx1999.top/Article/details/gt2gxfivcoo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gt2oevquujq.html

[U18] Py：预编译正则
来源：http://dali.jianghu66.top/Article/details/gt2lsncshxg.html

pat = re.compile(r"\d+")
来源：http://dali.ivvv.top/Article/details/gt2mtbjjxnw.html

[U19] Py：正则替换带回调
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppwwjmnr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gt2ecnslwti.html

[U20] Py：缓存函数结果
来源：http://dali.daria6918.cn/Article/details/gt2mjciljbx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jlsjyb.cn/Article/details/gt2ptarwpcf.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gt2nnawqqzm.html

@contextlib.contextmanager
来源：http://dali.hywenlv.cn/Article/details/gt2fqqmtfxk.html

[U22] Py：矩阵转置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvuqklpp.html

list(zip(*m))
来源：http://dali.daria6918.cn/Article/details/gt2ahpsjxkm.html

[U23] Py：分块读取大文件
来源：http://dali.ehwqpu.com/Article/details/gt2vhehamxn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhongyouzk.top/Article/details/gt2bjkuygtu.html

[U24] Py：路径操作
来源：http://dali.jinqigufen.top/Article/details/gt2uottwmje.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gt2potssrkm.html

[U25] Py：CSV 按字典读
来源：http://dali.yueranfly.top/Article/details/gt2mdgrwalk.html

csv.DictReader(f)
来源：http://dali.chenzaomai.com/Article/details/gt2rrbvikcs.html

[U26] Py：并发下载
来源：http://dali.ivvv.top/Article/details/gt2elzqitzb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gt2pcvlztyp.html

[U27] Py：异步 HTTP
来源：http://dali.xuanzx.com/Article/details/gt2svahosba.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj20258888.top/Article/details/gt2wmlftefu.html

[U28] Py：类型别名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfwtbsmh.html

UserId = int
来源：http://dali.cdnleiting.top/Article/details/gt2snxoeebr.html

[U29] Py：属性校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vrmzrmry.html

@property 与 @x.setter 配合
来源：http://dali.cucudq.cn/Article/details/gt2tvnamxen.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gt2kcnjybwb.html

@dataclass(slots=True)
来源：http://dali.sufxvd.cn/Article/details/gt2oqiaiipg.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gt2jhydblfd.html

python -m pytest -q
来源：http://dali.wangdashe.top/Article/details/gt2iospnbtj.html

[U32] Py：代码格式化
来源：http://dali.xuanzx.com/Article/details/gt2tgtbnguy.html

ruff format . && ruff check --fix .
来源：http://dali.tianlin.xyz/Article/details/gt2jmvhhfkv.html

[U33] Py：打包发布
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycpvzira.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aizwys.cn/Article/details/gt2jideikgi.html

[U34] Py：判断编码
来源：http://dali.nanxuanxn.top/Article/details/gt2rwnkziwt.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfzcssop.html

[U35] Py：发送邮件
来源：http://dali.sweek.top/Article/details/gt2ywhlnsnp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenlongwang.top/Article/details/gt2sxpdyrlb.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2weqindty.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxinkj.top/Article/details/gt2ctgnnsrc.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gt2wbbsrqom.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2snzhwnlz.html

[U38] Py：获取脚本所在目录
来源：http://dali.tanke756.top/Article/details/gt2qkqwpjbs.html

Path(__file__).resolve().parent
来源：http://dali.316326.xyz/Article/details/gt2dfejawsj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhengqikj.top/Article/details/gt2hyeittym.html

sys.stdout.isatty()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhgxrtne.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntwddktp.html

print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2ipypzbej.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.smart0.xyz/Article/details/gt2zqpmqbwh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2peqmcivs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnxiangtu.top/Article/details/gt2rlujigot.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmhexeyo.html

[U43] PHP：声明命名空间
来源：http://dali.gaohongyu789.top/Article/details/gt2huvqanqr.html

namespace App\Http;
来源：http://dali.jinqigufen.top/Article/details/gt2musoqikz.html

[U44] PHP：开启严格类型
来源：http://dali.jiagoushi.top/Article/details/gt2qbpqevae.html

declare(strict_types=1);
来源：http://dali.cashguo.top/Article/details/gt2zblohnho.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzjtgnta.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ogmgyiea.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gt2toiotyuz.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gt2htswegjy.html

[U47] PHP：联合类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtumnlyp.html

int|string $id
来源：http://dali.hnxiangtu.top/Article/details/gt2hrjiedaq.html

[U48] PHP：纯枚举
来源：http://dali.fengsongda.top/Article/details/gt2ccqycimm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gt2pygxyrpd.html

[U49] PHP：只读属性
来源：http://dali.havefunace.top/Article/details/gt2jorwsguh.html

public readonly string $name
来源：http://dali.hammf.cn/Article/details/gt2dwluxtcc.html

[U50] PHP：构造器属性提升
来源：http://dali.fengsongda.top/Article/details/gt2cpyzefos.html

public function __construct(private int $id) {}
来源：http://dali.xylfe.cn/Article/details/gt2fjftddmr.html

[U51] PHP：数组解构
来源：http://dali.ivvv.top/Article/details/gt2qjlyswec.html

[$a, $b] = $arr;
来源：http://dali.zhongyouzk.top/Article/details/gt2izmwjavd.html

[U52] PHP：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvwkbkcq.html

$double = fn($x) => $x * 2;
来源：http://dali.gzhubu.top/Article/details/gt2oxmldfgu.html

[U53] PHP：空合并运算符
来源：http://dali.hammf.cn/Article/details/gt2lbmjqlqd.html

$v = $a ?? $b ?? "default";
来源：http://dali.vqdsnc.cn/Article/details/gt2uekbyawz.html

[U54] PHP：空安全调用
来源：http://dali.jqgfzy.top/Article/details/gt2cjgjliel.html

$obj?->method()
来源：http://dali.mhx1999.top/Article/details/gt2rmaordpl.html

[U55] PHP：match 表达式
来源：http://dali.zhixingplan.top/Article/details/gt2xxlgfces.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gt2uspokcwo.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2saietvhj.html

f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2omhsixbv.html

[U57] PHP：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2xounpcvn.html

"值: {$a}"
来源：http://dali.bjfxy.top/Article/details/gt2drytunrt.html

[U58] PHP：数组三件套
来源：http://dali.zhoulong.xyz/Article/details/gt2sbasdqle.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuxming.cn/Article/details/gt2fryytldj.html

[U59] PHP：自定义排序
来源：http://dali.jianghu66.top/Article/details/gt2ildooifv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gt2pkawcgfu.html

[U60] PHP：JSON 编解码
来源：http://dali.xinyue.icu/Article/details/gt2lxkxyezr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cucudq.cn/Article/details/gt2vxlvcvkg.html


<!-- 参考信息 -->