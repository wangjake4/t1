代发 wailian999

[S33] C++：vector 增删
来源：http://dali.yuxming.cn/Article/details/gtydvcouns.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gtzbyujwle.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gtvhpxsbht.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gtwcwlgllo.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtmezekkip.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtubwfjxww.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gtzkttlesp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtvbklxqdd.html

[S37] C++：set
来源：http://dali.quarkkingdee.top/Article/details/gtfbqgkkzw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gtptkkznmd.html

[S38] C++：排序
来源：http://dali.xuanzx.com/Article/details/gtdpshyqxo.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtvxatzkil.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gteopjgtmv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gtuxxgyowi.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtiylljffx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gtmxocldzm.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gtimxghnts.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtabwsfgok.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtwaoanmtw.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtuvyjvvxt.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gtvephnuzb.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtvdlaxedx.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtsybwlkhy.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtossgnmmt.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gtvpstqmnm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gtepqzodpk.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtvbcnkvao.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jyoumei.cn/Article/details/gtzhqaldpr.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtfnyxwsrn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gtiurmgked.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtevefvtdf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtforojgei.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtlqtvfdho.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gtklttfzqj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gtkeautwbv.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gthruejrqh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gttpiocifn.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtvjxsbbnq.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gtjmyxkhqp.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtbbeowbqe.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gtcxnrjpat.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gtwcwmujgq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gtchzwhujn.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhiexezf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gtolwnrrzw.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gttcsrwmlx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gtvjtuuwrm.html

[S56] C++：optional
来源：http://dali.tianlin.xyz/Article/details/gtwfzzcemu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gtoxdcvxdg.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtnlrcnnby.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gtdggqldtl.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gthsrdbeab.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gthzlxumyr.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtyetqzcei.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtmvtvixse.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gtjquehkub.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtzhuzncpc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtctbjdtus.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtgajljzlx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbztpscqb.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtptjrkogb.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtsktqihtz.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gtvidjcrgc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gtttobksfh.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtdwxoasai.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtlydqobyh.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtfkyripdn.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gtifhbdljs.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgufenzy.top/Article/details/gtlsifhopy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gtxkqvkmkx.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtymbixjnk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangdashe.top/Article/details/gtlbaixymp.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtrcdpumis.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtnqykdras.html

[T08] Kotlin：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyyqceeh.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gttbhsvkio.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvramhbwa.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtogqxfphl.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gtrpnnidgs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hongshengwenyu.top/Article/details/gtffenjetq.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtbucdlxfz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gthlkxdato.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlcefwru.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gthadvogsk.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gtdqwgerkp.html

val m = mapOf("a" to 1)
来源：http://dali.0kj1m.cn/Article/details/gtxkkdoqso.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gtjxsftyks.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtfxxwseub.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gtelmjmkej.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gthtlnhxui.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gtwzdbwzno.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtquhmtnkg.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gtbqqmcapk.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtldladmgb.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gtoucikagc.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtdnonxdiq.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtxkquictu.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gtxlmezkht.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqcsjrra.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlanutint.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtekdjgjnz.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtvrsarzkw.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gtphaabtpf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gtrdegibhm.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtwvorulhs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtygpzdnpe.html

[T24] Swift：闭包
来源：http://dali.ppjwa.cn/Article/details/gthvnplnvt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtldpfsgwu.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gtykfelrxy.html

struct P { var x: Int }
来源：http://dali.ehwqpu.com/Article/details/gtzuvymfoz.html

[T26] Swift：类与重写
来源：http://dali.quarkkingdee.top/Article/details/gtimsanmaa.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtkbwhvwbq.html

[T27] Swift：错误处理
来源：http://dali.mhx1999.top/Article/details/gtnkfstzeh.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gtnvjzyeyv.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gtxsvbcvnc.html

enum Color { case red, green }
来源：http://dali.yuxming.cn/Article/details/gtahdeiqie.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gtxnvylivk.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gtykvpdzth.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gtbwfuclil.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayfaalcv.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gtqzqhetwz.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gtfyqrsrty.html

[T32] Lua：局部变量
来源：http://dali.ybcxt.top/Article/details/gtgidoixar.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmfuxosa.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtwxxmtmka.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gthocepyod.html

[T34] Lua：遍历表
来源：http://dali.yongpay.top/Article/details/gtbriaebrf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtmrezdrme.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtecvslpog.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtiupyaxou.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtpxhefulf.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gtbccropuw.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdmnizfj.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gtmkrvexyq.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gtwvejhbye.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtkdkprhlo.html

[T39] Lua：模式匹配
来源：http://dali.pycfn.com/Article/details/gtsxszksgb.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gtljaopjmt.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtjdqowwvt.html

setmetatable({}, { __index = base })
来源：http://dali.wangdashe.top/Article/details/gtydsowwxv.html

[T41] Perl：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtilcjsjye.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtlzgcbjfl.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gtmnpvfdth.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtxnucygdu.html

[T43] Perl：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtbkzhwiqi.html

"值: $a"
来源：http://dali.nwbrower.top/Article/details/gtwoeehsbl.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxisgjfh.html

if ($a > 0) { print "正"; }
来源：http://dali.hysaishi.cn/Article/details/gtlfaicxxd.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtqynoypvd.html

for my $x (@arr) { print $x; }
来源：http://dali.guowangkeji.top/Article/details/gtshspymrh.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gtqxvsddpi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.vqdsnc.cn/Article/details/gtdswphdbi.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gtmtufrmzj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gotoacloud.top/Article/details/gtwkbnttwh.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfajeofp.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcqhgukc.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gtqhaorzwd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtushpsrtq.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtvyeyipaj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gtgjabzdjo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xziqi.cn/Article/details/gtrdykyyox.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gtldngovvo.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtqwmoiavs.html

[T52] Scala：变量
来源：http://dali.c1oappe.top/Article/details/gttoatptbx.html

val a = 1;  var b = 2
来源：http://dali.hywenlv.cn/Article/details/gtzudfyybp.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtucscfase.html

s"值: $b"
来源：http://dali.xziqi.cn/Article/details/gtsmsndzze.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtnvyqxdhn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xuanzx.com/Article/details/gtoajwboxa.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtmlujkkir.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hongshengwenyu.top/Article/details/gttzhyafjc.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gtoftlpzbk.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtzmuriusw.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtflzrnggi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtyiovmhby.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gtuvodpozb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtnrjtlrws.html

[T59] Scala：循环
来源：http://dali.yj20258.top/Article/details/gtqbbbfrsw.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gthubokbtu.html

[T60] Scala：折叠
来源：http://dali.tianlin.xyz/Article/details/gtdixnymds.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gtqkhuknit.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtbzigdphl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gtsoykkyjv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuybqcgan.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrhxcplx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dianchejie.cn/Article/details/gtuazstqie.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gtbguuoaxj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gtjvecemni.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gtfmhsumqr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gtjdhqaevn.html

[U04] Py：变量调试打印
来源：http://dali.fzhhl.top/Article/details/gtwqynttey.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gtjunigxpm.html

[U05] Py：列表去重且保序
来源：http://dali.gotoacloud.top/Article/details/gtwktijglz.html

list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtpbsiviac.html

[U06] Py：合并两个字典
来源：http://dali.xylfe.cn/Article/details/gtlecxjpav.html

{**a, **b}
来源：http://dali.yj20258888.top/Article/details/gtaflacwud.html

[U07] Py：反转字典键值
来源：http://dali.316326.xyz/Article/details/gtiouqsyvh.html

{v: k for k, v in d.items()}
来源：http://dali.ehwqpu.com/Article/details/gtnymcogqm.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gtxhegtiod.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gtgziketlv.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gtjvsbkvek.html

max(d, key=d.get)
来源：http://dali.hfpthk.cn/Article/details/gtubxairyr.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtzcywicbh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dashuyun.cn/Article/details/gtcvqlazqs.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gtnpsqevjf.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gtbbvplbdh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gtetlcfegc.html

Counter(arr).most_common(3)
来源：http://dali.zhongyouzk.top/Article/details/gtyidhnfnq.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gtwwnnqzhe.html

deque(maxlen=10)
来源：http://dali.yueranfly.top/Article/details/gtkithaayt.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gtfqnynyza.html

defaultdict(list)
来源：http://dali.yj20258.top/Article/details/gtggohykfo.html

[U15] Py：高精度计时
来源：http://dali.zhoulong.xyz/Article/details/gtxnnbriku.html

t = time.perf_counter()
来源：http://dali.9152youxi.cn/Article/details/gtztznfctz.html

[U16] Py：命令行参数解析
来源：http://dali.tian-w.cn/Article/details/gtztitdozy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sysykeji.top/Article/details/gtrnooemgy.html

[U17] Py：初始化日志
来源：http://dali.snrcjt.cn/Article/details/gtjvqpacsq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yuxming.cn/Article/details/gtntvjpayx.html

[U18] Py：预编译正则
来源：http://dali.zdqjudy.top/Article/details/gtqeyomcio.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtdkpvfgrk.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gtfqgrohfe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gtlyjookkf.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gtuaheaojy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guowangkeji.top/Article/details/gtgvubmprw.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gtsxbxyytr.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmbmkymv.html

[U22] Py：矩阵转置
来源：http://dali.mhx1999.top/Article/details/gtoimkqxgo.html

list(zip(*m))
来源：http://dali.tianlin.xyz/Article/details/gtvykvxxbx.html

[U23] Py：分块读取大文件
来源：http://dali.wangshuangyany.cn/Article/details/gtgslxfbei.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gtkxgpobyi.html

[U24] Py：路径操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdliohroi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtyqmpypah.html

[U25] Py：CSV 按字典读
来源：http://dali.fengsongda.top/Article/details/gtwksbpxvg.html

csv.DictReader(f)
来源：http://dali.cucudq.cn/Article/details/gtafaixsjw.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gtaxlezqce.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pycfn.com/Article/details/gtqoyanhvg.html

[U27] Py：异步 HTTP
来源：http://dali.chenjidiqi.icu/Article/details/gtsjwzfjak.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gaohongyu789.top/Article/details/gtcimtfztx.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gtbisuwbeg.html

UserId = int
来源：http://dali.dianchejie.cn/Article/details/gtssaozqgn.html

[U29] Py：属性校验
来源：http://dali.hysaishi.cn/Article/details/gtzrhpgjfl.html

@property 与 @x.setter 配合
来源：http://dali.yj202588.top/Article/details/gtrhvymsux.html

[U30] Py：数据类
来源：http://dali.316326.xyz/Article/details/gtitxmfjpt.html

@dataclass(slots=True)
来源：http://dali.dashuyun.cn/Article/details/gtjcmfuuef.html

[U31] Py：单测
来源：http://dali.yonumen.top/Article/details/gtrrjylgrv.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gtkiptyvok.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksrvnklx.html

ruff format . && ruff check --fix .
来源：http://dali.zdqjudy.top/Article/details/gttnseduvt.html

[U33] Py：打包发布
来源：http://dali.xziqi.cn/Article/details/gtfdqtovdu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.birdmap.top/Article/details/gtguxmnahe.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gtojocegvx.html

chardet.detect(raw)
来源：http://dali.mhx1999.top/Article/details/gtryrkptbi.html

[U35] Py：发送邮件
来源：http://dali.9152youxi.cn/Article/details/gtddtpdlxe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gtdaqkdvte.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gtxnmoyyxh.html

schedule.every(10).minutes.do(job)
来源：http://dali.cucudq.cn/Article/details/gtkqyucnwh.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gtqkrlkdgc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pengpengdd.cyou/Article/details/gtuqwxuxbe.html

[U38] Py：获取脚本所在目录
来源：http://dali.cdnleiting.top/Article/details/gtzgvbepqs.html

Path(__file__).resolve().parent
来源：http://dali.svipenyu.cn/Article/details/gthpddcgmj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhiwuduotai.top/Article/details/gtyfvmozyl.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gtzmwkhxxy.html

[U40] Py：打印到标准错误
来源：http://dali.daria6918.cn/Article/details/gtixpuhgvy.html

print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtildcqsyy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenzaomai.com/Article/details/gthvppvnfl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pengpengdd.cyou/Article/details/gtfwesxikq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinghuilouyu.cn/Article/details/gtidiogcle.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gtifhoopcj.html

[U43] PHP：声明命名空间
来源：http://dali.zhengqikj.top/Article/details/gtmntbwfiz.html

namespace App\Http;
来源：http://dali.shuidangran.top/Article/details/gtqiutwitd.html

[U44] PHP：开启严格类型
来源：http://dali.ehwqpu.com/Article/details/gtawziwfsj.html

declare(strict_types=1);
来源：http://dali.cucudq.cn/Article/details/gtfszqkrsj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258.top/Article/details/gthovuqlhq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtvntmlxmq.html

[U46] PHP：可空类型
来源：http://dali.cheryme.top/Article/details/gtveammdxl.html

?string $name = null
来源：http://dali.sxryk.cn/Article/details/gtmquwgatr.html

[U47] PHP：联合类型
来源：http://dali.yueranfly.top/Article/details/gtprlkzqjv.html

int|string $id
来源：http://dali.chenjidiqi.icu/Article/details/gteluzfjci.html

[U48] PHP：纯枚举
来源：http://dali.mhx1999.top/Article/details/gtbtiyvqgl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhoulong.xyz/Article/details/gtdxjljzua.html

[U49] PHP：只读属性
来源：http://dali.jianghu66.top/Article/details/gtwmmppann.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gtdslnspzs.html

[U50] PHP：构造器属性提升
来源：http://dali.jiagoushi.top/Article/details/gttbqlkmfx.html

public function __construct(private int $id) {}
来源：http://dali.yj20258.top/Article/details/gtqfgqbydo.html

[U51] PHP：数组解构
来源：http://dali.hysaishi.cn/Article/details/gtpbwvrhrj.html

[$a, $b] = $arr;
来源：http://dali.zycfv.cn/Article/details/gtssnurmfb.html

[U52] PHP：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gtklkvbqqo.html

$double = fn($x) => $x * 2;
来源：http://dali.nwbrower.top/Article/details/gtkonmhqqi.html

[U53] PHP：空合并运算符
来源：http://dali.meibo888.top/Article/details/gtwciewwtl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhixingplan.top/Article/details/gtovzjzjpn.html

[U54] PHP：空安全调用
来源：http://dali.hywenlv.cn/Article/details/gtjdeqltar.html

$obj?->method()
来源：http://dali.tanke756.top/Article/details/gtibwkfflw.html

[U55] PHP：match 表达式
来源：http://dali.redwolf501.top/Article/details/gtelcnjwxz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gthhwqszev.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipvsvnly.html

f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtzqjnsdwc.html

[U57] PHP：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdeopqpba.html

"值: {$a}"
来源：http://dali.hnxiangtu.top/Article/details/gtwzmrmklt.html

[U58] PHP：数组三件套
来源：http://dali.zhongyouzk.top/Article/details/gtovcgyjwm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.svipenyu.cn/Article/details/gtbxoyapag.html


<!-- 参考信息 -->