代发 wailian999

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gt2mxmzadfp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gt2ltytwvde.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gt2wklkmdus.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gt2wnntthnj.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gt2nlekayfl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2bcifacwm.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfnpsufq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2wxmqppwn.html

[S37] C++：set
来源：http://dali.jyoumei.cn/Article/details/gt2ptnvcnwf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gt2rgbbzxjb.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gt2rhiobgwo.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gt2ccbleqgv.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gt2ssohlosn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gt2lncelowe.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gt2ddvjyqci.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gt2oeyfmhpw.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gt2jplobvpx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxffgckm.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gt2ecipgmyp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gt2zboaqsvf.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrdjpewu.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gt2yehsplzc.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gt2kpxewbis.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gt2zzlwaugb.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gt2hqvgynbs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gt2wglairfj.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gt2ygjdqsuw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gt2xeknvuoc.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2gumgqeng.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gt2yinilhxy.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2pqcopbzl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gt2faoxtfhk.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gt2nuyxcrqm.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inyrmaaa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gt2tdobbfup.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gt2lioqkyth.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2gvfiovjp.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2lvllgbda.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gt2jfqcijvp.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gt2sjrsmosb.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gt2ogexdboc.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gt2lkdeqibn.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gt2qjsdfgei.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gt2clgqzfjd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gt2ejxrvdut.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gt2utisbmff.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gt2qfahdslu.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gt2bapxxtvx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtxucaiu.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gt2ishzyymy.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2whfxzrhe.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gt2gorhmdfk.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2slrfedsh.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gt2yadojdul.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gt2dwvrscgy.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gt2aknsnstj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2ecmwgyxf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2vhbscgqu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gt2dnsycuus.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2vltvlhmt.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gt2tknqelii.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gt2jsjmpqme.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gt2tdnbxnmd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gt2houvsgrg.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gt2kyjokhrm.html

"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gt2ihzqkqjc.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gt2fcxqxlli.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gt2ivbexwkq.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2gjmkidny.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gt2thmcvmrf.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2kctulnjt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gt2trisltfl.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gt2vvnbicsj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gt2jleeylcn.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gt2zbexhdah.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gt2nasvirej.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gt2cwcddira.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gt2wuvafkfr.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gt2xbthbkkn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gt2wqqtvkrr.html

[T11] Kotlin：协程
来源：http://dali.yvedp.cn/Article/details/gt2apkvjotr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gt2tmfqozrg.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gt2cbzwrsme.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2kpvnrntj.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwsympyo.html

val m = mapOf("a" to 1)
来源：http://dali.cucudq.cn/Article/details/gt2ckkyvbff.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gt2ivkbvwym.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gt2jegesblf.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gt2jtsmeotg.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gt2ixhqiwyl.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gt2tviotken.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2qclbqqhn.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gt2iqpzhgcp.html

var a = 1;  let b = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2ywknsiui.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gt2xgagwczf.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gt2aichjwyn.html

[T19] Swift：可选绑定
来源：http://dali.tanke756.top/Article/details/gt2zkcmdhhe.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gt2jitjewtr.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gt2ccmgzhej.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gt2stjceymg.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2kuwsvgwj.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gt2fnpsoodi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcdkvnj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gt2xrhnebgl.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gt2evmcrmlh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2vgcoojse.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gt2gchqdjfd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2fljoxwhn.html

[T25] Swift：结构体
来源：http://dali.gotoacloud.top/Article/details/gt2lowsvrcr.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvjuhkla.html

[T26] Swift：类与重写
来源：http://dali.yonumen.top/Article/details/gt2zcuffdhv.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gt2otbwcuru.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2wleflgvm.html

do { try f() } catch { print(error) }
来源：http://dali.ehwqpu.com/Article/details/gt2aahoulob.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gt2ngjibvny.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukarmaus.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gt2yuybpryr.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uavbtefi.html

[T30] Swift：协议
来源：http://dali.yongpay.top/Article/details/gt2crcxvsuo.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gt2lehszuic.html

[T31] Lua：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2uszzufek.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2pwmnmsqm.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2novpyayx.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gt2hyxschug.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gt2slxvnrmc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gt2oovsxbvb.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gt2abhxokkx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gt2gtjcgnfo.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gt2bbtcaouf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zycfv.cn/Article/details/gt2vpxzefqy.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gt2ntgqgiid.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gt2kgiegnho.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2zqgytpis.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmgtvvgo.html

[T38] Lua：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmdzqebi.html

if x > 0 then print("正") end
来源：http://dali.zhoulong.xyz/Article/details/gt2kgtvdmsa.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2xkrfrbwn.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gt2yfoccyni.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejbhivgn.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gt2vmcppgki.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2gfugrfxu.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gt2iwcrjpgg.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gt2xtqehtwv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzozotzw.html

[T43] Perl：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2fcbpeppg.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzmqhyft.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gt2ezfhhbhp.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258888.top/Article/details/gt2ktqpwrsd.html

[T45] Perl：数组遍历
来源：http://dali.sysykeji.top/Article/details/gt2yqqogtxh.html

for my $x (@arr) { print $x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ymenwvqj.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gt2bctbeaou.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shuidangran.top/Article/details/gt2ixdqhtra.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajdxpxzx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ofaifvwo.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2iuasuuyu.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gt2anxvygez.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gt2hlndprjq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2xltbpvoa.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2thvhpiyl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gt2pszjksud.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gswuesup.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2fydqdyqp.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2gcvdmznr.html

[T52] Scala：变量
来源：http://dali.bjfxy.top/Article/details/gt2modztltj.html

val a = 1;  var b = 2
来源：http://dali.sxryk.cn/Article/details/gt2cwlsnfzz.html

[T53] Scala：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gt2esryyefh.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2tldngjxs.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odxpxnlj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gt2hjjsshcg.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2kgsvrdjo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2toonmmqd.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gt2oomfujfx.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gt2qrwkwijw.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2iaedtbks.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.9152youxi.cn/Article/details/gt2ewtkzzqn.html

[T58] Scala：函数定义
来源：http://dali.yangfankeji.com/Article/details/gt2wucphfjz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gt2zyytxamn.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gt2ntmglxim.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2fhddjksr.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gt2yjjfdbec.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gt2rzetockb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2fizajncb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gt2euudpdnf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2vlznxxxe.html

[U01] Py：创建虚拟环境
来源：http://dali.hnqzz.top/Article/details/gt2brlgznas.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iyxvcywm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gt2mzulurai.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylxnbojg.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gt2wmjwgjfn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tianlin.xyz/Article/details/gt2lgbnghrp.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gt2tytkyjab.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyevujiu.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gt2heodzqdp.html

list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gt2bdrkqlod.html

[U06] Py：合并两个字典
来源：http://dali.cheryme.top/Article/details/gt2gjqgawpz.html

{**a, **b}
来源：http://dali.yueranfly.top/Article/details/gt2gojpgwxr.html

[U07] Py：反转字典键值
来源：http://dali.smart0.xyz/Article/details/gt2iogdkwoo.html

{v: k for k, v in d.items()}
来源：http://dali.jiagoushi.top/Article/details/gt2rbwqjdkz.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gt2ntaaupqp.html

[y for x in nested for y in x]
来源：http://dali.jianghu66.top/Article/details/gt2quxxxvff.html

[U09] Py：字典取最大值的键
来源：http://dali.hysaishi.cn/Article/details/gt2zsaoukpt.html

max(d, key=d.get)
来源：http://dali.yj20258888.top/Article/details/gt2rdgxsynn.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwqtzqky.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gt2etlaunfj.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gt2sgwmehtc.html

(x * 2 for x in arr)
来源：http://dali.tanke756.top/Article/details/gt2uakndfaj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.smart0.xyz/Article/details/gt2epyfeqmj.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdbqfpey.html

[U13] Py：固定长度队列
来源：http://dali.yuxming.cn/Article/details/gt2bazgfvwk.html

deque(maxlen=10)
来源：http://dali.zhongyouzk.top/Article/details/gt2fqwpohwt.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gt2spjpxulu.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gt2uwnlgslr.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gt2dkbcwilc.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gt2ojhtqkvo.html

[U16] Py：命令行参数解析
来源：http://dali.ybcxt.top/Article/details/gt2ojmbcbzj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gt2vrhookjh.html

[U17] Py：初始化日志
来源：http://dali.sufxvd.cn/Article/details/gt2oshluoos.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xylfe.cn/Article/details/gt2exdidzdy.html

[U18] Py：预编译正则
来源：http://dali.tianlin.xyz/Article/details/gt2ibczuzcf.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2ygyjygvh.html

[U19] Py：正则替换带回调
来源：http://dali.wangdashe.top/Article/details/gt2kqsafthc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aizwys.cn/Article/details/gt2auinnnmn.html

[U20] Py：缓存函数结果
来源：http://dali.cdnleiting.top/Article/details/gt2gnqyvuyd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gt2ltjzjkjp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdhmdvu.html

@contextlib.contextmanager
来源：http://dali.jqgfzy.top/Article/details/gt2jeyjannh.html

[U22] Py：矩阵转置
来源：http://dali.andypj.xyz/Article/details/gt2zmelcrjz.html

list(zip(*m))
来源：http://dali.nwbrower.top/Article/details/gt2kfpgzdek.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gt2wwqozfof.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aibaodan.cn/Article/details/gt2tnrbefmk.html

[U24] Py：路径操作
来源：http://dali.tianlin.xyz/Article/details/gt2gxkgafyi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gt2fzybhrxt.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigfzy.top/Article/details/gt2bcldzlxz.html

csv.DictReader(f)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxjldsvs.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkdgvinv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daxiang520.top/Article/details/gt2srhbvutn.html

[U27] Py：异步 HTTP
来源：http://dali.mhx1999.top/Article/details/gt2dmjmlmvq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ehwqpu.com/Article/details/gt2updqrccv.html

[U28] Py：类型别名
来源：http://dali.jiagoushi.top/Article/details/gt2qlsumsmg.html

UserId = int
来源：http://dali.dianchejie.cn/Article/details/gt2neqjhrtg.html

[U29] Py：属性校验
来源：http://dali.ybcxt.top/Article/details/gt2jyycheti.html

@property 与 @x.setter 配合
来源：http://dali.cashguo.top/Article/details/gt2ihszszni.html

[U30] Py：数据类
来源：http://dali.tanke756.top/Article/details/gt2hiqrapqu.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gt2rgrdryqa.html

[U31] Py：单测
来源：http://dali.daxiang520.top/Article/details/gt2occfqxus.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gt2ytthpzzw.html

[U32] Py：代码格式化
来源：http://dali.yj202588.top/Article/details/gt2fhinzkxu.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigufen.top/Article/details/gt2euprapuo.html

[U33] Py：打包发布
来源：http://dali.jqgufenzy.top/Article/details/gt2felsztzr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.redwolf501.top/Article/details/gt2vfpqqlqw.html

[U34] Py：判断编码
来源：http://dali.sweek.top/Article/details/gt2ajbipyas.html

chardet.detect(raw)
来源：http://dali.pycfn.com/Article/details/gt2opoyzwrl.html

[U35] Py：发送邮件
来源：http://dali.zhixingplan.top/Article/details/gt2yeuzismr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.iojbl.cn/Article/details/gt2uchokibq.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gt2fsvvpsmx.html

schedule.every(10).minutes.do(job)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gyflddla.html

[U37] Py：读写 Excel
来源：http://dali.cqqwz.cn/Article/details/gt2hwxrblan.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yangfankeji.com/Article/details/gt2dolmkcvp.html

[U38] Py：获取脚本所在目录
来源：http://dali.haohaochexian.top/Article/details/gt2ldnbayli.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gt2rwrbdtuu.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxuanxn.top/Article/details/gt2htbwnexa.html

sys.stdout.isatty()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kotwlcxa.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2brspqvos.html

print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gt2vhrvxuos.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.iojbl.cn/Article/details/gt2jnrqffbt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gt2koszucbb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjmsamac.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jyoumei.cn/Article/details/gt2mbzqaqab.html

[U43] PHP：声明命名空间
来源：http://dali.ehwqpu.com/Article/details/gt2ccturxxw.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gt2gxypyety.html

[U44] PHP：开启严格类型
来源：http://dali.vqdsnc.cn/Article/details/gt2sdndeedi.html

declare(strict_types=1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vkgegosd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sysykeji.top/Article/details/gt2gbhpwogz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2czdgrbul.html

[U46] PHP：可空类型
来源：http://dali.pycfn.com/Article/details/gt2hlbngbcu.html

?string $name = null
来源：http://dali.ybcxt.top/Article/details/gt2zdimgbjs.html

[U47] PHP：联合类型
来源：http://dali.jlsjyb.cn/Article/details/gt2heyoyrki.html

int|string $id
来源：http://dali.redwolf501.top/Article/details/gt2capmnsmh.html

[U48] PHP：纯枚举
来源：http://dali.nanxinkj.top/Article/details/gt2efvdhnrx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tanke756.top/Article/details/gt2urxarhkf.html

[U49] PHP：只读属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgmvmkzb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mhearyrz.html

[U50] PHP：构造器属性提升
来源：http://dali.quarkkingdee.top/Article/details/gt2djmmdpqc.html

public function __construct(private int $id) {}
来源：http://dali.jqgfzy.top/Article/details/gt2plhtgdys.html

[U51] PHP：数组解构
来源：http://dali.hfpthk.cn/Article/details/gt2uwvjvfow.html

[$a, $b] = $arr;
来源：http://dali.snrcjt.cn/Article/details/gt2ithjeahd.html

[U52] PHP：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gt2vngjjakr.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258.top/Article/details/gt2gcannyyp.html

[U53] PHP：空合并运算符
来源：http://dali.yanxiufei.cn/Article/details/gt2rjvtoywh.html

$v = $a ?? $b ?? "default";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgzkjsmt.html

[U54] PHP：空安全调用
来源：http://dali.9152youxi.cn/Article/details/gt2qjddxivk.html

$obj?->method()
来源：http://dali.cqqwz.cn/Article/details/gt2frtxlfdo.html

[U55] PHP：match 表达式
来源：http://dali.tian-w.cn/Article/details/gt2feaxarud.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.quarkkingdee.top/Article/details/gt2enodqaki.html

[U56] PHP：命名参数
来源：http://dali.9152youxi.cn/Article/details/gt2lnmojazo.html

f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2pqzqteqc.html

[U57] PHP：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2nyjlumdn.html

"值: {$a}"
来源：http://dali.xinyue.icu/Article/details/gt2zurywayo.html

[U58] PHP：数组三件套
来源：http://dali.jinqigfzy.top/Article/details/gt2gffkaxga.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yueranfly.top/Article/details/gt2xpyjtfvd.html


<!-- 参考信息 -->