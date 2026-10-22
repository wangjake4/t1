代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.hammf.cn/Article/details/gtrwsgumey.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gtsjoosiav.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtswtjffuv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gtvfkskrpr.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtvxasjejm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenzaomai.com/Article/details/gtgrkbubjw.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gtsgtfrozf.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gtfkpzbqba.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gthjvinlbt.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gtwbenyrcg.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gtyeeacpgw.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gtfsgazupi.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtoootbtfi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gtknegzzpr.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gtxokqxycj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtvcwuzppf.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtyarkqoot.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gtcvjkoygz.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtwkamuudn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gtguqwnvkv.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtvxbjlwnn.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtjsunabvc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gtrfheeigt.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gtvcgjjsbo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtwmqjpdwp.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gtpxcvehor.html

static_cast<double>(a) / b
来源：http://dali.gzhubu.top/Article/details/gtfshwnfek.html

[S52] C++：const 与 noexcept
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauwcoojb.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gtreikszvm.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipfmbcos.html

std::vector<int> w = std::move(v);
来源：http://dali.hysaishi.cn/Article/details/gtksxfbbsl.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjvjtips.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gtuzxbsbuu.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtkggzlouv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtxkmmcwxe.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtavinmjfs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gtaaoryznt.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gtmkpxruai.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gttrewhaul.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvaycott.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtfejxnrmc.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gtujpvnzgr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gtlhdhiebe.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gtohykwapc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtvqryosvb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtikfjmcon.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gtbhiohuaw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtsdjagimk.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gtjyivtfml.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtssjluefo.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtsjhcbxde.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gtptjoogsz.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gtgnvoduck.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtuxjejtax.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gtvyjowubt.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtjbpwdrps.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gtzovdatuu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gtlclrtxld.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gttqawrecs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gtyrnzgreq.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtufeywfup.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtklqgovqh.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gthvvbrbpc.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtagwfdhmr.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gttysituia.html

fun String.exclaim() = this + "!"
来源：http://dali.yuxming.cn/Article/details/gtzuklpdyb.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gtxfzefslh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gtefekfpzo.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtnewkdvyb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gtcasuxsmq.html

[T12] Kotlin：解构声明
来源：http://dali.iojbl.cn/Article/details/gttakcriza.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gtfnmbylso.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtoaervdsm.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gtrmjueejv.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtkwsozgdt.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtyucddsly.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gtoesexwdb.html

interface Shape { fun area(): Double }
来源：http://dali.yueranfly.top/Article/details/gtwlslbzar.html

[T16] Swift：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtzdowtynv.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtblnjcqsr.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gtlcfuybsw.html

var a = 1;  let b = 2
来源：http://dali.yj202588.top/Article/details/gtlvnovcym.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtdqxybwdm.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gtdmwymxnu.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gtkftttjua.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtewhavnrc.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtfrjjzlhc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gtmjixnikb.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gtlwpnfqdi.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gtdrtnolls.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gtuvusbaso.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gtzebtznni.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gtkueowftd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gtjtcpmlhr.html

[T24] Swift：闭包
来源：http://dali.zhoulong.xyz/Article/details/gttynyzuxl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtgdnmwvyk.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gttnxauxdt.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gtdgttpgqg.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gtgxfdujlo.html

class A: Base { override func f() {} }
来源：http://dali.zhixingplan.top/Article/details/gtgxegbqvs.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gtjxjgjhoq.html

do { try f() } catch { print(error) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtprvrbyua.html

[T28] Swift：枚举
来源：http://dali.shzxlz.cn/Article/details/gtjfituydl.html

enum Color { case red, green }
来源：http://dali.gogol.net.cn/Article/details/gtdofsqsxj.html

[T29] Swift：guard 提前返回
来源：http://dali.vqdsnc.cn/Article/details/gttmgkxomi.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gtnklqsuzy.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gtrjcnwhsy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhengqikj.top/Article/details/gtghsaumst.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gtaomiehkp.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtkvnabhlb.html

[T32] Lua：局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtsybsqjno.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gtjmgfmpch.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gteyipgfyh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gtlgnjzjyn.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gtfonlarys.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gtsuaddjpo.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gtumwiumxa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhssjftp.html

[T36] Lua：函数
来源：http://dali.chenlongwang.top/Article/details/gtfmqhfryn.html

function add(a, b) return a + b end
来源：http://dali.zycfv.cn/Article/details/gtclquuvka.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gtnywlirwn.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gtknqkvyog.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobtcbcoa.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gtgrcdajlo.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtxipztoeh.html

string.find(s, "%d+")
来源：http://dali.316326.xyz/Article/details/gtkzszihum.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtfnwjdxei.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkwzcwcb.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctaludyd.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gtvwmxocom.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gtcpcrqorp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gtvfxjcxqd.html

[T43] Perl：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtronuzfvs.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gtqwoighbw.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gtmqgjsdbz.html

if ($a > 0) { print "正"; }
来源：http://dali.shuidangran.top/Article/details/gtuohvprps.html

[T45] Perl：数组遍历
来源：http://dali.zhengqikj.top/Article/details/gtzxacmwpm.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gtrypfrkwj.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gtppkvmlhi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gtfrjgomdo.html

[T47] Perl：正则捕获
来源：http://dali.jinqigfzy.top/Article/details/gtrfktmpzi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ehwqpu.com/Article/details/gthmzifeei.html

[T48] Perl：正则替换
来源：http://dali.cashguo.top/Article/details/gtfwtqrjdz.html

$s =~ s/old/new/g;
来源：http://dali.bjfxy.top/Article/details/gtarctpibo.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtxpqyreyd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvtalxde.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtszctmhef.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gtxyvubkqp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gtxmecdfpm.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtuechxpjf.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtpuxxznjh.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gtlfspfbny.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtkgbulcov.html

[T53] Scala：字符串插值
来源：http://dali.havefunace.top/Article/details/gtsrhgymyg.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtctvdzvyc.html

[T54] Scala：集合映射
来源：http://dali.yj202588.top/Article/details/gtgogncyko.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zdqjudy.top/Article/details/gtbcvxzlqj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtakiuzays.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sufxvd.cn/Article/details/gtyzosrjun.html

[T56] Scala：样例类
来源：http://dali.feifeiyinyue.top/Article/details/gtpnmyxhru.html

case class User(name: String, age: Int)
来源：http://dali.tanke756.top/Article/details/gtaiovmfpb.html

[T57] Scala：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtegbzgdme.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gtsdeaepve.html

[T58] Scala：函数定义
来源：http://dali.sxryk.cn/Article/details/gtkppjejdw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zdqjudy.top/Article/details/gtitlsnbig.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gtvclyxuyb.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtxirxcoxd.html

[T60] Scala：折叠
来源：http://dali.yvedp.cn/Article/details/gtvpikdlao.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gtiuiivcjp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gturnrezzi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtwgnfiyui.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkkhtburc.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gtwimmwzwd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.svipenyu.cn/Article/details/gtoyhglmgd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guowangkeji.top/Article/details/gtndkckpbj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jyoumei.cn/Article/details/gttzfertbv.html

[U03] Py：加载 .env 配置
来源：http://dali.aizwys.cn/Article/details/gtoghdcwzw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gtvppnlaaf.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gtebkovulv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.mhx1999.top/Article/details/gtfefzdbbk.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gtdpspvnhd.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gthhqrblfl.html

[U06] Py：合并两个字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmppohdv.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gtxuyrewtk.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gtrlkcntcb.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gtrwplxvxj.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrflyvyoy.html

[y for x in nested for y in x]
来源：http://dali.316326.xyz/Article/details/gtihetjyjn.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gtxrzkbabf.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gtuomcvoao.html

[U10] Py：按值排序字典
来源：http://dali.cheryme.top/Article/details/gtlvghovey.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbpbublw.html

[U11] Py：生成器表达式
来源：http://dali.yvedp.cn/Article/details/gtczgxzses.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gtodftxobi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.smart0.xyz/Article/details/gtjphxofmp.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gtyuaudesq.html

[U13] Py：固定长度队列
来源：http://dali.zhoulong.xyz/Article/details/gtvmehappj.html

deque(maxlen=10)
来源：http://dali.bjfxy.top/Article/details/gtrwwwvsvp.html

[U14] Py：分组收集到列表
来源：http://dali.andypj.xyz/Article/details/gtvambopbr.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gtybzwhoif.html

[U15] Py：高精度计时
来源：http://dali.gogol.net.cn/Article/details/gtzjfmnmsj.html

t = time.perf_counter()
来源：http://dali.zdqjudy.top/Article/details/gtcdciwbuj.html

[U16] Py：命令行参数解析
来源：http://dali.svipenyu.cn/Article/details/gtfmdphxrt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ybcxt.top/Article/details/gtqggmkjlc.html

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gtawlxdamj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gtuypeafnj.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gtaaqkhsqt.html

pat = re.compile(r"\d+")
来源：http://dali.zycfv.cn/Article/details/gtrdhphhgo.html

[U19] Py：正则替换带回调
来源：http://dali.yj202588.top/Article/details/gtbofmyigj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gttururlbb.html

[U20] Py：缓存函数结果
来源：http://dali.zhoulong.xyz/Article/details/gtcxzpbthu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xziqi.cn/Article/details/gtdskdtiax.html

[U21] Py：自定义上下文管理器
来源：http://dali.gotoacloud.top/Article/details/gtdkkqrxig.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gteufibrua.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gtbeaaxbpb.html

list(zip(*m))
来源：http://dali.dashuyun.cn/Article/details/gtvyeewdqi.html

[U23] Py：分块读取大文件
来源：http://dali.andypj.xyz/Article/details/gtnyfsnrtq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gtqbbtnfil.html

[U24] Py：路径操作
来源：http://dali.feifeiyinyue.top/Article/details/gtrtplmerd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtgenzdkfd.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gtsalqheil.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gtoizzylaa.html

[U26] Py：并发下载
来源：http://dali.daria6918.cn/Article/details/gteqygsznr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yvedp.cn/Article/details/gtlecctnwl.html

[U27] Py：异步 HTTP
来源：http://dali.tianlin.xyz/Article/details/gtzlbopfns.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cucudq.cn/Article/details/gtedztbibw.html

[U28] Py：类型别名
来源：http://dali.chenlongwang.top/Article/details/gtwwbcpwvr.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gtsnnrsgrx.html

[U29] Py：属性校验
来源：http://dali.yvedp.cn/Article/details/gthyeoedvb.html

@property 与 @x.setter 配合
来源：http://dali.gogol.net.cn/Article/details/gtovrgsrmy.html

[U30] Py：数据类
来源：http://dali.cdnleiting.top/Article/details/gtgoxokozd.html

@dataclass(slots=True)
来源：http://dali.yj20258888.top/Article/details/gtwhzevkns.html

[U31] Py：单测
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlunwwwgi.html

python -m pytest -q
来源：http://dali.jlsjyb.cn/Article/details/gtvcqbtbse.html

[U32] Py：代码格式化
来源：http://dali.ivvv.top/Article/details/gtzihncewf.html

ruff format . && ruff check --fix .
来源：http://dali.pengpengdd.cyou/Article/details/gtmzuyobho.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gtheempsho.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yongpay.top/Article/details/gthzgyyztr.html

[U34] Py：判断编码
来源：http://dali.hfpthk.cn/Article/details/gtclwsiufh.html

chardet.detect(raw)
来源：http://dali.kuanghao11.cn/Article/details/gttauzccyl.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gtkfrvuonw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gtqsjynfsg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtgjpdwuhz.html

schedule.every(10).minutes.do(job)
来源：http://dali.quarkkingdee.top/Article/details/gtiohryeeg.html

[U37] Py：读写 Excel
来源：http://dali.316326.xyz/Article/details/gtcaymocye.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.daxiang520.top/Article/details/gtrmzttaqf.html

[U38] Py：获取脚本所在目录
来源：http://dali.daria6918.cn/Article/details/gtoqzukwbb.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gtfypxgihu.html

[U39] Py：判断是否在交互环境
来源：http://dali.hongshengwenyu.top/Article/details/gtfjgjkkro.html

sys.stdout.isatty()
来源：http://dali.pycfn.com/Article/details/gtvgjpxxgd.html

[U40] Py：打印到标准错误
来源：http://dali.9152youxi.cn/Article/details/gtgmmhfkov.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gtndolfapi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shangyingyoupin.top/Article/details/gtfxbgaxnb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.c1oappe.top/Article/details/gtschrctcn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tian-w.cn/Article/details/gtetvripam.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.iojbl.cn/Article/details/gtlrdzmtgw.html

[U43] PHP：声明命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtvebkpnqg.html

namespace App\Http;
来源：http://dali.xinyue.icu/Article/details/gtxpgvqrim.html

[U44] PHP：开启严格类型
来源：http://dali.sysykeji.top/Article/details/gtppimrfho.html

declare(strict_types=1);
来源：http://dali.pycfn.com/Article/details/gtvtsnlxvp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zycfv.cn/Article/details/gtfrvgsxsb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtkmmmcvsa.html

[U46] PHP：可空类型
来源：http://dali.yongpay.top/Article/details/gtcuhirmjc.html

?string $name = null
来源：http://dali.jqgufenzy.top/Article/details/gtdtdruzwm.html

[U47] PHP：联合类型
来源：http://dali.xylfe.cn/Article/details/gtjaubdqys.html

int|string $id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsaeabsm.html

[U48] PHP：纯枚举
来源：http://dali.andypj.xyz/Article/details/gtzpyrltnp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hywenlv.cn/Article/details/gtpglphluq.html

[U49] PHP：只读属性
来源：http://dali.mhx1999.top/Article/details/gttjdgqfqs.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltrbmfku.html

[U50] PHP：构造器属性提升
来源：http://dali.xylfe.cn/Article/details/gtvfquoejn.html

public function __construct(private int $id) {}
来源：http://dali.dashuyun.cn/Article/details/gtrkcmbyra.html

[U51] PHP：数组解构
来源：http://dali.shzxlz.cn/Article/details/gtkknwlklm.html

[$a, $b] = $arr;
来源：http://dali.cucudq.cn/Article/details/gtewxcfvxq.html

[U52] PHP：箭头函数
来源：http://dali.xinyue.icu/Article/details/gtyoudszfb.html

$double = fn($x) => $x * 2;
来源：http://dali.cheryme.top/Article/details/gtpdbgereg.html

[U53] PHP：空合并运算符
来源：http://dali.jiagoushi.top/Article/details/gttuoihuxb.html

$v = $a ?? $b ?? "default";
来源：http://dali.sxryk.cn/Article/details/gtcgaqzknh.html

[U54] PHP：空安全调用
来源：http://dali.bjfxy.top/Article/details/gtcpreszuf.html

$obj?->method()
来源：http://dali.sweek.top/Article/details/gtxsdmvwdv.html

[U55] PHP：match 表达式
来源：http://dali.xinyue.icu/Article/details/gtqrqpuohr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gtpedfwvcj.html

[U56] PHP：命名参数
来源：http://dali.jyoumei.cn/Article/details/gtxphyfblc.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtgeoxorsk.html

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gttsqxdgdj.html

"值: {$a}"
来源：http://dali.cucudq.cn/Article/details/gtohlziwic.html

[U58] PHP：数组三件套
来源：http://dali.yj20258.top/Article/details/gtpqlspuiz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cdnleiting.top/Article/details/gtufmrubyg.html

[U59] PHP：自定义排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvxabtjx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtwtclzksf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhongyouzk.top/Article/details/gtpcqgahfi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ydzc1.top/Article/details/gtzvfoljag.html

[U61] PHP：正则
来源：http://dali.mhx1999.top/Article/details/gthmbwsibv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtzyxqmqlj.html

[U62] PHP：日期对象
来源：http://dali.hysaishi.cn/Article/details/gtmnqepvmx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.316326.xyz/Article/details/gtsfobwxch.html

[U63] PHP：文件读写
来源：http://dali.jyoumei.cn/Article/details/gtipkfwxca.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yvedp.cn/Article/details/gtslejepnm.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlcvzsty.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258888.top/Article/details/gtzehsotjp.html


<!-- 参考信息 -->