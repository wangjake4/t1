代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyxomdiv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gtrastjztd.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gtcoopxssc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdevqypoo.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gttciyanwm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gtgorjmklv.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gtcwhpjzin.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtoflzdxgv.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gtddpqzwbb.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gtzcurvrgi.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gtgfdptkok.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gtbzmxznme.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gtbxhtvswg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gtdqgvjaxa.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtnvnugiix.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gtpdtyfqwb.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gtxdjsdwza.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gtjymvmtqq.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtgzmrrzql.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gtxfyfgdkl.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gtsflwuznm.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gtjlbpstcd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtljxwseyx.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtyyifhysb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gthjmaqops.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gttbbhaofp.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtxleilghy.html

[S52] C++：const 与 noexcept
来源：http://dali.smart0.xyz/Article/details/gtkkgfiviz.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gtzynvohoz.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtzyimgtod.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gtkmkqnrfd.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gttolpmroq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gtjhwowcru.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gtoyootinq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtptmnvpza.html

[S56] C++：optional
来源：http://dali.tianlin.xyz/Article/details/gtqmubsffr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gtclkxfila.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gteducpdjc.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gtmkihfimo.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gtwzzxkild.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtdzwztwtw.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gtsrwlnokz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gtdlojcdgv.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gtepfxvxuo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtszrejokb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmkimaavx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gtnpoejbrz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtshlykjbk.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtfrdowjwd.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtewqanfqx.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtvwwymlop.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gtbzgooprw.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gtaupysbvl.html

"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gthdtmfkyp.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gtrnonrksn.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtcpjjwqjk.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gthxtfwydr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtapgzplif.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtudzffjqx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gtxqfxyhra.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtfwjtvqgc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtweyzfkuu.html

[T08] Kotlin：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gtchzgbcky.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gtvqqytalq.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtaeekqysi.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gtwieeggjr.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gtlhnsyyvx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gtbgsqwbcb.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gtfmqsqbqf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gttviixuvi.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gtjjfmxydw.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtcqxsecct.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigufen.top/Article/details/gtnpxkbnjj.html

val m = mapOf("a" to 1)
来源：http://dali.ybcxt.top/Article/details/gtauukoeyz.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gtpfqfmafq.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahnsxtaz.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtxpappwsi.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtzrobiery.html

[T16] Swift：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtvdsezlqz.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtckdksdgh.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gterklvtsl.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gtjodcobzm.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gtxduiehtm.html

"值: \(b)"
来源：http://dali.sysykeji.top/Article/details/gterwnebbe.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gtpxpuxfin.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gtvrfjilwx.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gtsjisilko.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gtsyuzfsmr.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtasgfectp.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gtukzdlhgl.html

[T22] Swift：字典
来源：http://dali.guannengcc.top/Article/details/gtaysuuona.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gtoqjqdzml.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gtrrnslcdc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gtmnvysnna.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtfhnkppam.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtoivvgbos.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtoibotgub.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gtdjcjqoah.html

[T26] Swift：类与重写
来源：http://dali.jianghu66.top/Article/details/gtsmzwskhj.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gtmqmskxqw.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtpyxrzagf.html

do { try f() } catch { print(error) }
来源：http://dali.0kj1m.cn/Article/details/gtuwacmyqp.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gtavpcogpq.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gtthgdlfhe.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gtwyguhxui.html

guard let x = opt else { return }
来源：http://dali.xziqi.cn/Article/details/gtcyypyygg.html

[T30] Swift：协议
来源：http://dali.sufxvd.cn/Article/details/gtdliegccs.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxuanxn.top/Article/details/gturoriywa.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gtshpdeaal.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtwwfoienj.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gtpriccfri.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gtzdholnoo.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gtlmmcawcq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.iojbl.cn/Article/details/gtkwvowiwc.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gtyznrrwhs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gtyrlsfpyn.html

[T35] Lua：字典表
来源：http://dali.hywenlv.cn/Article/details/gtxababxea.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gtgngmkyre.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfmtukcs.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsobqegg.html

[T37] Lua：字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtxwneusvu.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gteephxsdk.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gtakqkqffh.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gtnfzbzxof.html

[T39] Lua：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtrtugaciw.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gtaygptjqx.html

[T40] Lua：元表
来源：http://dali.nanxinkj.top/Article/details/gtjegpeuvg.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gttqgkmezy.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gtqpyitzrd.html

print "Hello\n";
来源：http://dali.cheryme.top/Article/details/gtiptknumq.html

[T42] Perl：变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkjjnsic.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jyoumei.cn/Article/details/gteatgwalf.html

[T43] Perl：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtmatzzkae.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gtaatkudpw.html

[T44] Perl：条件
来源：http://dali.hywenlv.cn/Article/details/gtdninexqm.html

if ($a > 0) { print "正"; }
来源：http://dali.fengsongda.top/Article/details/gttpyxzejn.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gttzgzyvyn.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258888.top/Article/details/gtjneurpyl.html

[T46] Perl：哈希操作
来源：http://dali.yuxming.cn/Article/details/gtbcwcuoif.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gogol.net.cn/Article/details/gtopmabkuk.html

[T47] Perl：正则捕获
来源：http://dali.jiagoushi.top/Article/details/gthgyooiby.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gtkhoicgni.html

[T48] Perl：正则替换
来源：http://dali.aizwys.cn/Article/details/gtxhnybdvc.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gtyqauaifz.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gtqsagyjsz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtbouvaoaf.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtpuaftydi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gtwpqgbsac.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtnebakuvj.html

[T51] Scala：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtgiwhngay.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtuxngjana.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gtfhstettz.html

val a = 1;  var b = 2
来源：http://dali.0kj1m.cn/Article/details/gtkhsmwhzp.html

[T53] Scala：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtnzzwizfz.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtfuoijboj.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtxalwelws.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cheryme.top/Article/details/gtbqgzcnqc.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtkjdghbyu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gotoacloud.top/Article/details/gtoixvxdin.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gtkhnjxlme.html

case class User(name: String, age: Int)
来源：http://dali.havefunace.top/Article/details/gtkdcwgimo.html

[T57] Scala：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtjsfuezgj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gtnderdqlt.html

[T58] Scala：函数定义
来源：http://dali.chenzaomai.com/Article/details/gtadxehppx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gtfrrhzfws.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gtcpzisadw.html

for (i <- 1 to 10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtlmkdmijp.html

[T60] Scala：折叠
来源：http://dali.aibaodan.cn/Article/details/gtmiaeresp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgufenzy.top/Article/details/gtozyzxzyu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcgxdqtbd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gttsddijgr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzfguduwl.html

[U01] Py：创建虚拟环境
来源：http://dali.sweek.top/Article/details/gtzokyolzg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtempejsif.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gtlmryzagg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtceawbrjk.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gtodvyynwu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258.top/Article/details/gtaojfwbpm.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gtowozkkrk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangtech.top/Article/details/gttffigowb.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gtvrsxsopv.html

list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gteasjxswo.html

[U06] Py：合并两个字典
来源：http://dali.nanxuanxn.top/Article/details/gtjaupornd.html

{**a, **b}
来源：http://dali.sufxvd.cn/Article/details/gtefvzqmwg.html

[U07] Py：反转字典键值
来源：http://dali.jinghuilouyu.cn/Article/details/gtyidjdevl.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gttscmqkel.html

[U08] Py：展平二维列表
来源：http://dali.tianlin.xyz/Article/details/gtnrhdryza.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gtgohaafra.html

[U09] Py：字典取最大值的键
来源：http://dali.nwbrower.top/Article/details/gtjzsxepvd.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gtudumfzdb.html

[U10] Py：按值排序字典
来源：http://dali.gogol.net.cn/Article/details/gtdndvsfae.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hammf.cn/Article/details/gtgnrutwps.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtefngbnds.html

(x * 2 for x in arr)
来源：http://dali.tian-w.cn/Article/details/gtoeopxfnq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gtwvrnlbkp.html

Counter(arr).most_common(3)
来源：http://dali.sxryk.cn/Article/details/gthhiwqwla.html

[U13] Py：固定长度队列
来源：http://dali.jinqigfzy.top/Article/details/gtpfybfbzm.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gtbxpeqzhd.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigufen.top/Article/details/gtaeffylfe.html

defaultdict(list)
来源：http://dali.tian-w.cn/Article/details/gtghrbfnxo.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gtkigxiiww.html

t = time.perf_counter()
来源：http://dali.sufxvd.cn/Article/details/gtdccxycmv.html

[U16] Py：命令行参数解析
来源：http://dali.daria6918.cn/Article/details/gtxxdiokcg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.bjfxy.top/Article/details/gtyngtihgs.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gtqxfblrjq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsununpm.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gtvcgnlawc.html

pat = re.compile(r"\d+")
来源：http://dali.xuanzx.com/Article/details/gtdyvdbkom.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangtech.top/Article/details/gthuzjrtch.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gtwbmozvrb.html

[U20] Py：缓存函数结果
来源：http://dali.daria6918.cn/Article/details/gtuhsexela.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yongpay.top/Article/details/gtulgomngl.html

[U21] Py：自定义上下文管理器
来源：http://dali.hysaishi.cn/Article/details/gtokpgaowb.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gtfkpyfyrd.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gtdvactdze.html

list(zip(*m))
来源：http://dali.gzhubu.top/Article/details/gtxhloazyp.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtbjofcpto.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gtxfnihete.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gtdywlwhbu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtpwrejhtk.html

[U25] Py：CSV 按字典读
来源：http://dali.cashguo.top/Article/details/gtqgrcrpbe.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gtggcihmxw.html

[U26] Py：并发下载
来源：http://dali.nanxuanxn.top/Article/details/gtudafargk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hfpthk.cn/Article/details/gtqkpveiiv.html

[U27] Py：异步 HTTP
来源：http://dali.havefunace.top/Article/details/gtczdrpamt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gtkibzctiz.html

[U28] Py：类型别名
来源：http://dali.hammf.cn/Article/details/gtrcjaaxdi.html

UserId = int
来源：http://dali.jiagoushi.top/Article/details/gtckhexmae.html

[U29] Py：属性校验
来源：http://dali.sysykeji.top/Article/details/gtsqdexapp.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gtwcmdzjhg.html

[U30] Py：数据类
来源：http://dali.tian-w.cn/Article/details/gttuqxlvio.html

@dataclass(slots=True)
来源：http://dali.jqgufenzy.top/Article/details/gtxywgxdvd.html

[U31] Py：单测
来源：http://dali.xylfe.cn/Article/details/gtdivsgpel.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gttytgutjz.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gtcybehzbx.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gtjwwsvvbb.html

[U33] Py：打包发布
来源：http://dali.xuanzx.com/Article/details/gtckjttvtv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dianchejie.cn/Article/details/gtbsjjuanq.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gtdjeiiwzb.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gtwtrwkeee.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gtxaebdghy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258.top/Article/details/gtnppyvjkh.html

[U36] Py：定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtehuqlbfj.html

schedule.every(10).minutes.do(job)
来源：http://dali.havefunace.top/Article/details/gtyuoreodw.html

[U37] Py：读写 Excel
来源：http://dali.snrcjt.cn/Article/details/gtuytswply.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuanzhike.top/Article/details/gtfxgjwzib.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcblrhtn.html

Path(__file__).resolve().parent
来源：http://dali.zhiwuduotai.top/Article/details/gtibjelxna.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhoulong.xyz/Article/details/gtcjmnzeaw.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangtech.top/Article/details/gtagvyteny.html

[U40] Py：打印到标准错误
来源：http://dali.0kj1m.cn/Article/details/gtumowgngc.html

print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtqrxfyqcm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ydzc1.top/Article/details/gtiezovxkt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yanxiufei.cn/Article/details/gtkdsprhxz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuetiantiany.cn/Article/details/gtruhpeblp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hfpthk.cn/Article/details/gtykssigae.html

[U43] PHP：声明命名空间
来源：http://dali.yueranfly.top/Article/details/gtbfmnpdwb.html

namespace App\Http;
来源：http://dali.guannengcc.top/Article/details/gticgvecot.html

[U44] PHP：开启严格类型
来源：http://dali.sysykeji.top/Article/details/gtmlqsaguz.html

declare(strict_types=1);
来源：http://dali.jianghu66.top/Article/details/gtabgjwyla.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xuetiantiany.cn/Article/details/gttpqeiwxt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtzjffanjq.html

[U46] PHP：可空类型
来源：http://dali.yvedp.cn/Article/details/gtkylvczsg.html

?string $name = null
来源：http://dali.shzxlz.cn/Article/details/gtmvttagig.html

[U47] PHP：联合类型
来源：http://dali.jqgfzy.top/Article/details/gtunpudynq.html

int|string $id
来源：http://dali.hfpthk.cn/Article/details/gtfxjbuzom.html

[U48] PHP：纯枚举
来源：http://dali.cqqwz.cn/Article/details/gtuctklvpo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daxiang520.top/Article/details/gtwtvvlxal.html

[U49] PHP：只读属性
来源：http://dali.0kj1m.cn/Article/details/gtldhgajtb.html

public readonly string $name
来源：http://dali.svipenyu.cn/Article/details/gtjffiwenm.html

[U50] PHP：构造器属性提升
来源：http://dali.xuetiantiany.cn/Article/details/gtidwlqzmj.html

public function __construct(private int $id) {}
来源：http://dali.havefunace.top/Article/details/gtmyhcxlxy.html

[U51] PHP：数组解构
来源：http://dali.0kj1m.cn/Article/details/gtfmxnmqug.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gtepcrgisl.html

[U52] PHP：箭头函数
来源：http://dali.cheryme.top/Article/details/gtfpbrfxfq.html

$double = fn($x) => $x * 2;
来源：http://dali.birdmap.top/Article/details/gtmqvqqsuk.html

[U53] PHP：空合并运算符
来源：http://dali.quarkkingdee.top/Article/details/gtkxvjeocp.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenjidiqi.icu/Article/details/gtdldkysnh.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gtjepitjeu.html

$obj?->method()
来源：http://dali.xziqi.cn/Article/details/gtqjntqnvt.html

[U55] PHP：match 表达式
来源：http://dali.hnxiangtu.top/Article/details/gtxwvcichr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtrymlapme.html

[U56] PHP：命名参数
来源：http://dali.tanke756.top/Article/details/gtamkeuuvn.html

f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtspraobdm.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtasoemyla.html

"值: {$a}"
来源：http://dali.yongpay.top/Article/details/gtqaepsbga.html

[U58] PHP：数组三件套
来源：http://dali.xuetiantiany.cn/Article/details/gtixmltaeh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aizwys.cn/Article/details/gtacleqelm.html

[U59] PHP：自定义排序
来源：http://dali.yongpay.top/Article/details/gtsxcircnt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtehwqqgum.html

[U60] PHP：JSON 编解码
来源：http://dali.hnxiangtu.top/Article/details/gtyrwetlmw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yonumen.top/Article/details/gtwuwleogv.html

[U61] PHP：正则
来源：http://dali.wangshuangyany.cn/Article/details/gtvgtbguho.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtwqrzkbdj.html

[U62] PHP：日期对象
来源：http://dali.smart0.xyz/Article/details/gtaurycdyf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sxryk.cn/Article/details/gtndtdbdpq.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpssskjzi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.kuanghao11.cn/Article/details/gtzcnjovij.html

[U64] PHP：目录遍历
来源：http://dali.yj20258.top/Article/details/gtigthqskg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daria6918.cn/Article/details/gtsdaqgwpz.html


<!-- 参考信息 -->