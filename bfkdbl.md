代发 wailian999

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gtmpzaghdz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gtpfqskgzj.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gtpljgfqjt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gtuekbetkt.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gtlwikeigy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtadpuooko.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtosahrviz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtlrtmxhmc.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtipjsgbbv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gtqcjnoczh.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gtkdimwdnu.html

std::sort(v.begin(), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gtmugmofoc.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gtgxatlacx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gtuhxfseoh.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gtaghovocs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtthnzxilm.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gtcoadeoak.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gthfxxgbhp.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gtcoajcmpn.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gthgxlkhsq.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtyejhujvw.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtdamkpioo.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gteftwgpiq.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gtzdtxvavc.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtwkuqdmgu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gtuvtaimpn.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gtdqspmapj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gtppeyiahx.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gtghutvotq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzvxwcfdb.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtlonhltkq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gtotqigjhl.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtawuitgty.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gtbswymbtd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gtvlphcpjq.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gtroejdrpk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtlyqraigy.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtwbncddmu.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gtywackabi.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gtdkolfidm.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtyvhpfgek.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gtgeywxpia.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gtjwtqtpcw.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gtasfgeykj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcckfiuct.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtqopyhepd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gtkaedolxe.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gtuwlnxuwy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gthyuomwlm.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gtzrwdhajb.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gtoyweguof.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtjjjefqsr.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhabjhlh.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gtktdmkgoe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gtaxxvdjig.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gttojmkkys.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtnyulgwqw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdwdruutm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gttjcozjok.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxxbxyxga.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gtzsnlixws.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtugogdayp.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtiiqwxmsg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gtuhsbubhw.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtrciicswm.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftpcwlpy.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gtxbbendgz.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gtnrmitunm.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtlqixolxv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gtjvpyxbwe.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gteuevaqqa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gtjowubzem.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtdhkhrjyf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtpvdaiyru.html

[T08] Kotlin：数据类
来源：http://dali.cashguo.top/Article/details/gtaprcwofy.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtwyrxveel.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtvedbqpjc.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gtdghizuke.html

[T10] Kotlin：默认参数
来源：http://dali.redwolf501.top/Article/details/gtjkandqhu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gtjwlptzvk.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gtbxdvemkf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.snrcjt.cn/Article/details/gtvtzehuzz.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gtvqptramz.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtajgltmgg.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gtftqnyplu.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtpmbhjryq.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gtqusifbpl.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtvvuzqhps.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyqzuych.html

interface Shape { fun area(): Double }
来源：http://dali.daria6918.cn/Article/details/gtqecqiawf.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gtmjeyevry.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtwxcztaur.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gtdxfzbehc.html

var a = 1;  let b = 2
来源：http://dali.316326.xyz/Article/details/gtysfmejca.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtovforgse.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gtsyqllvkf.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gtuyetqgga.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gtntdclmfl.html

[T20] Swift：数组操作
来源：http://dali.birdmap.top/Article/details/gthgpowbbr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gtwbqahkin.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gtwoginzyf.html

for x in a { print(x) }
来源：http://dali.sxryk.cn/Article/details/gtemfjrgnx.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gtdayvetqm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwobecig.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gtsgcxiuic.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gtzqzoavbn.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gtazfwoezc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtanhgzkep.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gtmwiawjtt.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gtbxjtqore.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gthwyigkdd.html

class A: Base { override func f() {} }
来源：http://dali.yangfankeji.com/Article/details/gtqnvzdbkc.html

[T27] Swift：错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtagybdmpe.html

do { try f() } catch { print(error) }
来源：http://dali.jqgfzy.top/Article/details/gtijshdxlc.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtmsrcsovp.html

enum Color { case red, green }
来源：http://dali.cheryme.top/Article/details/gtrxvkfvfd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gtglkhrawz.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gtcgpludzn.html

[T30] Swift：协议
来源：http://dali.cucudq.cn/Article/details/gtqgdluulk.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gtnwvpivos.html

[T31] Lua：Hello World
来源：http://dali.cucudq.cn/Article/details/gtzpvugbdo.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gttrgkezvz.html

[T32] Lua：局部变量
来源：http://dali.yonumen.top/Article/details/gtupxvgitz.html

local a = 1
来源：http://dali.nanxinkj.top/Article/details/gtojcxjkbw.html

[T33] Lua：表（数组）
来源：http://dali.cdnleiting.top/Article/details/gtkwdzicin.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtrmlmgzwx.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gtvwmzqbqj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.316326.xyz/Article/details/gtehdnbkkc.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gtytzybuir.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gtcfsiyasp.html

[T36] Lua：函数
来源：http://dali.yuxming.cn/Article/details/gtlqnqlfmf.html

function add(a, b) return a + b end
来源：http://dali.zdqjudy.top/Article/details/gtouoxjuhi.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtsapglaus.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtsclrugxd.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxvtwiok.html

if x > 0 then print("正") end
来源：http://dali.wangshuangyany.cn/Article/details/gtaecwfytf.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtcvahvgwv.html

string.find(s, "%d+")
来源：http://dali.yonumen.top/Article/details/gtcekynnjl.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gtpmyfkrsk.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gtigzskwin.html

[T41] Perl：Hello World
来源：http://dali.xziqi.cn/Article/details/gtiqjljwxn.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gtmbdnvahn.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gtouentijx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dianchejie.cn/Article/details/gttclvnros.html

[T43] Perl：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtgougxvjo.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gtluuxlxoo.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtskvcqzpz.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtadellfwd.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtlysbcrtz.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gtdtdtvelb.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gtogqcpppf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zdqjudy.top/Article/details/gtnpoxuopk.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gtuyikpbli.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gttwbkwgaz.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gthrtktbji.html

$s =~ s/old/new/g;
来源：http://dali.aibaodan.cn/Article/details/gtlucspvdc.html

[T49] Perl：函数
来源：http://dali.cashguo.top/Article/details/gtzbhawnfm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtygpbnfff.html

[T50] Perl：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gttvibkmzk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ydzc1.top/Article/details/gtjaojdukv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdplgysen.html

[T51] Scala：Hello World
来源：http://dali.316326.xyz/Article/details/gtooqgkdxh.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtnxctxcqm.html

[T52] Scala：变量
来源：http://dali.daxiang520.top/Article/details/gtkatqqzpm.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gtipbkmqsb.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtysurhkst.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gthzovezhy.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtdncwnigb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ehwqpu.com/Article/details/gtrexoekan.html

[T55] Scala：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtjfsabkmo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gtlcrrwprn.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gtzxfaepxg.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gtgwuwzfth.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtlbdtbylx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.0kj1m.cn/Article/details/gtxxhfybdq.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gtenoppnou.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gtxewtpfrj.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtxavbkacv.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtwkbsjqvx.html

[T60] Scala：折叠
来源：http://dali.tian-w.cn/Article/details/gtuszezhuf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkklelcrx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzooilvms.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gtgcjrlfcv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtytfsryan.html

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gtxgaqyvox.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuanzhike.top/Article/details/gtyteeaprt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xylfe.cn/Article/details/gtcfqkbibd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258.top/Article/details/gtlcdvupfx.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gtmbfqhjfk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cdnleiting.top/Article/details/gtimqedgrz.html

[U04] Py：变量调试打印
来源：http://dali.jinyuanbaomall.cn/Article/details/gtillyydhq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gtziicrmzd.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtzkutvzcq.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtovthxkxi.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gtpnwbhefx.html

{**a, **b}
来源：http://dali.gzhubu.top/Article/details/gtnsiotpam.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gtzmtnavfg.html

{v: k for k, v in d.items()}
来源：http://dali.jyoumei.cn/Article/details/gtfgtutnvh.html

[U08] Py：展平二维列表
来源：http://dali.nanxuanxn.top/Article/details/gtqvklhoqg.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gtbadddmli.html

[U09] Py：字典取最大值的键
来源：http://dali.snrcjt.cn/Article/details/gthcdrygxt.html

max(d, key=d.get)
来源：http://dali.gaohongyu789.top/Article/details/gtcpxfkros.html

[U10] Py：按值排序字典
来源：http://dali.jinghuilouyu.cn/Article/details/gthlseaoao.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gzhubu.top/Article/details/gtljnmvqvu.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gtxdppvyqw.html

(x * 2 for x in arr)
来源：http://dali.vqdsnc.cn/Article/details/gtyydjvmft.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gtcyrbdpqe.html

Counter(arr).most_common(3)
来源：http://dali.smart0.xyz/Article/details/gtmyxwlzmg.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gtmchaaghk.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gtzggtbljx.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gtaivoqlgq.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtlsznzwnz.html

[U15] Py：高精度计时
来源：http://dali.gotoacloud.top/Article/details/gteyamjori.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gtjkprlqti.html

[U16] Py：命令行参数解析
来源：http://dali.aizwys.cn/Article/details/gtqkynwsnb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.mhx1999.top/Article/details/gtzebzejxl.html

[U17] Py：初始化日志
来源：http://dali.gotoacloud.top/Article/details/gthurfyqiw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jiagoushi.top/Article/details/gthciqtsry.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gttkdxmzbu.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gtqhzofglp.html

[U19] Py：正则替换带回调
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokgcblug.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzkueaclb.html

[U20] Py：缓存函数结果
来源：http://dali.0kj1m.cn/Article/details/gtoklenjdn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cdnleiting.top/Article/details/gtmrxkihfu.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gtdogtxaca.html

@contextlib.contextmanager
来源：http://dali.shzxlz.cn/Article/details/gtfaahbypx.html

[U22] Py：矩阵转置
来源：http://dali.cheryme.top/Article/details/gtcdifumxv.html

list(zip(*m))
来源：http://dali.tianlin.xyz/Article/details/gtnpmxegox.html

[U23] Py：分块读取大文件
来源：http://dali.xuanzx.com/Article/details/gtteukgpsd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gtjfulgeav.html

[U24] Py：路径操作
来源：http://dali.yueranfly.top/Article/details/gthinzqzaw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gtyfjxvmpu.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gtxmeypmnj.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gtqdgfdgtf.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtkqwapipd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyekzidwr.html

[U27] Py：异步 HTTP
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkoxmvhs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.c1oappe.top/Article/details/gtgulaqluo.html

[U28] Py：类型别名
来源：http://dali.feifeiyinyue.top/Article/details/gtiltsejww.html

UserId = int
来源：http://dali.pengpengdd.cyou/Article/details/gtwueqxyai.html

[U29] Py：属性校验
来源：http://dali.dashuyun.cn/Article/details/gtfpkmnxpr.html

@property 与 @x.setter 配合
来源：http://dali.jlsjyb.cn/Article/details/gtqfmiosnc.html

[U30] Py：数据类
来源：http://dali.aizwys.cn/Article/details/gttshjuvcr.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpmlkdey.html

[U31] Py：单测
来源：http://dali.zhengqikj.top/Article/details/gttxuwxstc.html

python -m pytest -q
来源：http://dali.chenjidiqi.icu/Article/details/gtfurjhheu.html

[U32] Py：代码格式化
来源：http://dali.cqqwz.cn/Article/details/gtxddqwikd.html

ruff format . && ruff check --fix .
来源：http://dali.xylfe.cn/Article/details/gtxwfvpdna.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gttbnewlpm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jyoumei.cn/Article/details/gtputsecjj.html

[U34] Py：判断编码
来源：http://dali.yongpay.top/Article/details/gtkyrdvndu.html

chardet.detect(raw)
来源：http://dali.hammf.cn/Article/details/gthvshiisx.html

[U35] Py：发送邮件
来源：http://dali.jinqigufen.top/Article/details/gtsrlnpnqa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhiwuduotai.top/Article/details/gtxgwvwfbi.html

[U36] Py：定时任务
来源：http://dali.wangdashe.top/Article/details/gtdksagakq.html

schedule.every(10).minutes.do(job)
来源：http://dali.sufxvd.cn/Article/details/gtebxuchnm.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gtebpgkkii.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jianghu66.top/Article/details/gtktzmyhdf.html

[U38] Py：获取脚本所在目录
来源：http://dali.jiagoushi.top/Article/details/gtxvcpbiat.html

Path(__file__).resolve().parent
来源：http://dali.hywenlv.cn/Article/details/gtnitpuytc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpyolfyh.html

sys.stdout.isatty()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdruiolh.html

[U40] Py：打印到标准错误
来源：http://dali.haohaochexian.top/Article/details/gtnfgwvexo.html

print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gtqluohmdn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhengqikj.top/Article/details/gtxooicrvi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hywenlv.cn/Article/details/gtjzgitoul.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.svipenyu.cn/Article/details/gtmbrglizm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.vqdsnc.cn/Article/details/gtahfmfuif.html

[U43] PHP：声明命名空间
来源：http://dali.aizwys.cn/Article/details/gtwctczvqb.html

namespace App\Http;
来源：http://dali.yuanzhike.top/Article/details/gtngpgswpv.html

[U44] PHP：开启严格类型
来源：http://dali.hysaishi.cn/Article/details/gthtgrctde.html

declare(strict_types=1);
来源：http://dali.yanxiufei.cn/Article/details/gtgbnyyqkc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sweek.top/Article/details/gtzicwkwgj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtnyhaxuph.html

[U46] PHP：可空类型
来源：http://dali.yuanzhike.top/Article/details/gtaeicfclr.html

?string $name = null
来源：http://dali.shangyingyoupin.top/Article/details/gtpezcrwga.html

[U47] PHP：联合类型
来源：http://dali.9152youxi.cn/Article/details/gtxeliuoyu.html

int|string $id
来源：http://dali.gotoacloud.top/Article/details/gtkuytyjyd.html

[U48] PHP：纯枚举
来源：http://dali.zhongyouzk.top/Article/details/gtlgpxsses.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jlsjyb.cn/Article/details/gthvfhczsc.html

[U49] PHP：只读属性
来源：http://dali.svipenyu.cn/Article/details/gtdioudwri.html

public readonly string $name
来源：http://dali.hysaishi.cn/Article/details/gtwsntlukw.html

[U50] PHP：构造器属性提升
来源：http://dali.yangfankeji.com/Article/details/gterxcowna.html

public function __construct(private int $id) {}
来源：http://dali.xylfe.cn/Article/details/gtosspfiku.html

[U51] PHP：数组解构
来源：http://dali.daxiang520.top/Article/details/gtnuumgbov.html

[$a, $b] = $arr;
来源：http://dali.hammf.cn/Article/details/gtharlxhro.html

[U52] PHP：箭头函数
来源：http://dali.cheryme.top/Article/details/gtgtngezup.html

$double = fn($x) => $x * 2;
来源：http://dali.shzxlz.cn/Article/details/gtrmfxloti.html

[U53] PHP：空合并运算符
来源：http://dali.yuanzhike.top/Article/details/gtuaabctpn.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258888.top/Article/details/gtmutauuut.html

[U54] PHP：空安全调用
来源：http://dali.snrcjt.cn/Article/details/gtdquzbajm.html

$obj?->method()
来源：http://dali.ybcxt.top/Article/details/gtzhssteen.html

[U55] PHP：match 表达式
来源：http://dali.gzhubu.top/Article/details/gtseicbnvp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gttsqysgti.html

[U56] PHP：命名参数
来源：http://dali.iojbl.cn/Article/details/gtsawfzkuu.html

f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtvgssboqe.html

[U57] PHP：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtrdwnmauv.html

"值: {$a}"
来源：http://dali.shangyingyoupin.top/Article/details/gthuchszlo.html

[U58] PHP：数组三件套
来源：http://dali.chenzaomai.com/Article/details/gtimruenfw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.svipenyu.cn/Article/details/gtpkjpbvli.html


<!-- 参考信息 -->